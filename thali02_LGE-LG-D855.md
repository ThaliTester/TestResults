#### Test 8362733700cd7fa_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-13 12:58:00.017   308  6122 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,--------- beginning of system
09-13 12:58:00.021  1032  1092 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-13 12:58:00.045  2621  2621 D [Concierge]Service: onStartCommand(). Type : 9
09-13 12:58:00.065  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-13 12:58:00.065  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
09-13 12:58:00.065  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-13 12:58:00.065  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
09-13 12:58:00.069  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
09-13 12:58:00.069  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
09-13 12:58:00.069  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
09-13 12:58:00.072  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
09-13 12:58:00.329  6123  6123 D AndroidRuntime: 
09-13 12:58:00.329  6123  6123 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-13 12:58:00.332  6123  6123 D AndroidRuntime: CheckJNI is OFF
09-13 12:58:00.531  6123  6123 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-13 12:58:00.537  1032  2026 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-13 12:58:00.554  1936  1951 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-13 12:58:00.558  1032  2026 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-13 12:58:00.560  1032  2026 D ActivityManager: setTaskToReturnTo : TaskRecord{28292e3 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-13 12:58:00.560  1032  2026 D ActivityManager: setTaskToReturnTo : TaskRecord{28292e3 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-13 12:58:00.561  1032  2026 D WindowStateEx: AppWindowTokenEx init.. 
09-13 12:58:00.562   346   410 E GBMv2   : DFP En is all cleared set to be enabled
09-13 12:58:00.600  1032  2026 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6160 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-13 12:58:00.603  6123  6123 D AndroidRuntime: Shutting down VM
09-13 12:58:00.678  1936  1951 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-13 12:58:00.678  1936  1951 D SplitWindowPolicy: topRunningActivity=ActivityInfo{37a7ca7b co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-13 12:58:00.680  1936  1952 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-13 12:58:00.680  1936  1952 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2844e098 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-13 12:58:00.726  6160  6160 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-13 12:58:00.807  6160  6160 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-13 12:58:00.812  6160  6160 I LibraryLoader: Loading: webviewchromium
09-13 12:58:00.814  6160  6160 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3920-3923)
09-13 12:58:00.814  6160  6160 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 12:58:00.835  6160  6160 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2fe4a8c7}
09-13 12:58:00.836  6160  6160 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 12:58:00.837  6160  6160 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,09-13 12:58:00.848  6160  6160 I BrowserStartupController: Initializing chromium process, renderers=0
09-13 12:58:00.849  6160  6160 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 12:58:00.859  6160  6189 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,09-13 12:58:00.866  6160  6160 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-13 12:58:00.867  6160  6160 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-13 12:58:00.867   315  2167 V AudioPolicyService: registerClient() client 0xb1024e60, uid 10118
09-13 12:58:00.867  6160  6160 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-13 12:58:00.875  1032  1094 D BluetoothManagerService: Message: 20
09-13 12:58:00.876  1032  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@271f2055:true
,09-13 12:58:00.882  6160  6160 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 12:58:00.882  6160  6160 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 12:58:00.882  6160  6160 I Adreno-EGL: Build Date: 12/12/14 금
09-13 12:58:00.882  6160  6160 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 12:58:00.882  6160  6160 I Adreno-EGL: Remote Branch: 
09-13 12:58:00.882  6160  6160 I Adreno-EGL: Local Patches: 
09-13 12:58:00.882  6160  6160 I Adreno-EGL: Reconstruct Branch: 
,09-13 12:58:01.009  1032  1048 I art     : Explicit concurrent mark sweep GC freed 32534(1486KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.366ms total 121.844ms
,09-13 12:58:01.033  6160  6199 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-13 12:58:01.036  6160  6160 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-13 12:58:01.056  6160  6160 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 12:58:01.061  6160  6160 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-13 12:58:01.064  6160  6160 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-13 12:58:01.067  6160  6160 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-13 12:58:01.067  6160  6160 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,09-13 12:58:01.082  6160  6160 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-13 12:58:01.089  6160  6160 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 12:58:01.089  6160  6160 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 12:58:01.118  6160  6212 D OpenGLRenderer: Render dirty regions requested: true
09-13 12:58:01.118  6160  6212 I OpenGLRenderer: Initialized EGL, version 1.4
09-13 12:58:01.124  6160  6212 D OpenGLRenderer: Enabling debug mode 0
09-13 12:58:01.133  6160  6160 D Atlas   : Validating map...
,09-13 12:58:01.137  1032  1899 D SplitWindow: check instance of lgWin Window{3c0a5727 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 12:58:01.182  6160  6210 D LgDataFeature: LgDataFeature() Constructor: none
,09-13 12:58:01.182  6160  6210 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 12:58:01.296  1032  1095 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +620ms (total +733ms)
09-13 12:58:01.297  1032  1095 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{18ebe4e0 u0 com.test.thalitest/.MainActivity t6} time:174405
09-13 12:58:01.312  6160  6160 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@aba5242 time:174420
,09-13 12:58:01.457  6160  6160 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 12:58:01.532  6160  6210 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-13 12:58:01.532  6160  6210 I chromium: 
,09-13 12:58:01.678  6160  6230 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435135872
,09-13 12:58:01.693  6160  6230 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 12:58:01.693  6160  6230 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 12:58:01.693  6160  6230 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 12:58:01.693  6160  6230 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 12:58:01.693  6160  6230 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-13 12:58:01.693  6160  6230 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19e8e366 added. We now have 1 listener(s)
09-13 12:58:01.699  1032  1953 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 12:58:01.702  6160  6230 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-13 12:58:01.705  6160  6230 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-13 12:58:01.706  6160  6230 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 12:58:01.706  6160  6230 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 12:58:01.712  6160  6160 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-13 12:58:01.712  6160  6160 I chromium: 
09-13 12:58:01.714  6160  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 12:58:01.714  6160  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 12:58:01.714  6160  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 12:58:01.714  6160  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-13 12:58:01.714  6160  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 12:58:01.714  6160  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 12:58:01.714  6160  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 12:58:01.714  6160  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 12:58:01.714  6160  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 12:58:01.714  6160  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 12:58:01.714  6160  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 12:58:01.714  6160  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 12:58:01.714  6160  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 12:58:01.714  6160  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-13 12:58:01.714  6160  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@879d6fd added. We now have 1 listener(s)
09-13 12:58:01.714  6160  6230 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 12:58:01.718  1032  1442 D WifiService: New client listening to asynchronous messages
,09-13 12:58:01.722  6160  6230 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 12:58:01.722  6160  6230 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-13 12:58:01.723  6160  6230 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-13 12:58:01.723  6160  6230 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 12:58:01.723  6160  6230 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-13 12:58:01.729  6160  6230 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 12:58:01.730  1032  1047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 12:58:01.732  6160  6230 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
,09-13 12:58:01.743  6160  6230 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,09-13 12:58:01.746  6160  6230 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:58:01.746  6160  6230 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:01.746  6160  6230 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:01.746  6160  6230 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:01.746  6160  6230 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:01.746  6160  6230 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:01.746  6160  6230 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:01.746  6160  6230 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:01.746  6160  6230 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-13 12:58:01.746  6160  6230 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 12:58:01.747  6160  6230 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 12:58:01.748  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:01.777   346   412 E GBMv2   : DFP En is all cleared set to be enabled
09-13 12:58:01.777   346   412 E GBMv2   : Set value is all cleared set the max
09-13 12:58:01.777   346   412 I GBMv2   : DFP Enabled. Ignore VFP set
09-13 12:58:01.784  6160  6160 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 12:58:02.413  6160  6233 W jxcore-log: Initializing JXcore engine
09-13 12:58:02.413  6160  6233 W jxcore-log: JXcore engine is ready
,09-13 12:58:02.445  6233  6233 W Thread-697: type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[6126]" dev="sockfs" ino=6126 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,09-13 12:58:02.445  6233  6233 W Thread-697: type=1400 audit(0.0:161): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-13 12:58:02.445  6233  6233 W Thread-697: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[10088]" dev="sockfs" ino=10088 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-13 12:58:02.445  6233  6233 W Thread-697: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-13 12:58:02.445  6233  6233 W Thread-697: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[29302]" dev="sockfs" ino=29302 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-13 12:58:02.468  6160  6233 W jxcore-log: Starting JXcore engine
,09-13 12:58:02.544  6160  6233 W jxcore-log: Platform android
09-13 12:58:02.544  6160  6233 W jxcore-log: 
09-13 12:58:02.544  6160  6233 W jxcore-log: Process ARCH arm
09-13 12:58:02.544  6160  6233 W jxcore-log: 
,09-13 12:58:02.741  6160  6233 I jxcore-log: JXcore Cordova bridge is ready!
09-13 12:58:02.741  6160  6233 I jxcore-log: 
09-13 12:58:02.741  6160  6233 W jxcore-log: JXcore engine is started
,09-13 12:58:02.753  6160  6230 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-13 12:58:02.756  6160  6160 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 12:58:02.914  1032  1376 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3fa76d35 type 2 when 176008 com.google.android.gms} when 176008
,09-13 12:58:12.750  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 12:58:12.750  6160  6233 I jxcore-log: 
09-13 12:58:12.753  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 12:58:12.753  6160  6233 I jxcore-log: 
,09-13 12:58:12.755  6160  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:58:12.755  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:12.755  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:12.755  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:12.755  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:12.755  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:12.755  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:12.755  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:12.758  6160  6233 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:58:12.760  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 12:58:12.760  6160  6233 I jxcore-log: 
09-13 12:58:12.762  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 12:58:12.762  6160  6233 I jxcore-log: 
09-13 12:58:13.268  6160  6233 I jxcore-log: Unit Test app is loaded
09-13 12:58:13.268  6160  6233 I jxcore-log: 
,09-13 12:58:13.275  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:58:13.275  6160  6233 I jxcore-log: 
09-13 12:58:13.283  6160  6233 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 12:58:13.283  6160  6233 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f3d02f4 added. We now have 2 listener(s)
09-13 12:58:13.286  1032  1900 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 12:58:13.290  6160  6160 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-13 12:58:13.291  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 12:58:13.291  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 12:58:13.291  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 12:58:13.291  6160  6233 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 12:58:13.292  6160  6233 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98ca1d added. We now have 2 listener(s)
09-13 12:58:13.292  6160  6233 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 12:58:13.292  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 12:58:13.293  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 12:58:13.295  6160  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:58:13.295  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:13.295  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:13.295  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:13.295  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:13.295  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:13.295  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:13.295  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 12:58:13.296  6160  6233 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:58:13.297  6160  6233 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 12:58:13.298  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:13.298  6160  6233 D ExecuteNativeTests: Running unit tests
09-13 12:58:13.299  6160  6233 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 12:58:13.299  6160  6233 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c766e63 added. We now have 3 listener(s)
09-13 12:58:13.299  1032  1727 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 12:58:13.300  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 12:58:13.300  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 12:58:13.300  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 12:58:13.300  6160  6233 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 12:58:13.300  6160  6233 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37a15a60 added. We now have 3 listener(s)
09-13 12:58:13.300  6160  6233 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 12:58:13.301  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 12:58:13.302  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 12:58:13.304  6160  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:58:13.304  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:13.304  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:13.304  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:13.304  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:13.304  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:13.304  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:13.304  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:13.305  6160  6233 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:58:13.305  6160  6233 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 12:58:13.305  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:15.254  1599  1599 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-13 12:58:15.255  1599  1599 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-13 12:58:15.274  1936  2065 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-13 12:58:15.274  1936  2065 D LEDHandler: Battery Level Remaining: 100%
,09-13 12:58:15.276  1599  1599 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 306
09-13 12:58:15.276  1599  1599 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-13 12:58:15.278  1032  1442 D WifiController: battery changed pluggedType: 2
09-13 12:58:15.278  1936  2065 D LEDHandler: Battery Temp: 306, mChargingStatus=5, mChargingStop=false
09-13 12:58:15.279  1599  1599 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-13 12:58:15.284  3826  3941 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-13 12:58:15.286  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:15.287  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 12:58:15.290  1599  1599 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-13 12:58:15.290  1599  1599 I [SystemUI]LGPowerUI: On Skip Timer : true
09-13 12:58:15.291  5069  5069 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-13 12:58:23.461  6160  6233 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 12:58:23.461  6160  6233 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b8c048e added. We now have 4 listener(s)
,09-13 12:58:23.465  1032  1954 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 12:58:23.467  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 12:58:23.467  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 12:58:23.468  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 12:58:23.468  6160  6233 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 12:58:23.468  6160  6233 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27d564af added. We now have 4 listener(s)
09-13 12:58:23.468  6160  6233 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 12:58:23.468  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 12:58:23.471  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 12:58:23.473  6160  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:58:23.473  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:23.473  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:23.473  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:23.473  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:23.473  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:23.473  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:23.473  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:23.475  6160  6233 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:58:23.475  6160  6233 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 12:58:23.479  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:23.485  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 12:58:23.488  6160  6233 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 12:58:23.488  6160  6233 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 12:58:23.488  6160  6233 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 12:58:23.488  6160  6233 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 12:58:23.494  6160  6233 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-13 12:58:23.495  6160  6233 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 12:58:23.495  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 12:58:23.495  6160  6233 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 12:58:23.495  6160  6233 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 12:58:23.495  6160  6233 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 12:58:23.496  6160  6233 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 12:58:23.496  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:58:23.496  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 12:58:23.496  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 12:58:23.496  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 12:58:23.497  6160  6233 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b8c048e removed from the list
09-13 12:58:23.497  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:58:23.497  6160  6233 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27d564af removed from the list
09-13 12:58:23.497  6160  6233 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:58:23.497  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.500  6160  6233 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-13 12:58:23.500  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:58:23.500  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.500  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 12:58:23.503  6160  6233 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b8c048e not in the list
09-13 12:58:23.503  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:58:23.503  6160  6233 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27d564af not in the list
09-13 12:58:23.503  6160  6233 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:58:23.503  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.504  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.513  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 12:58:23.513  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 12:58:23.513  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 12:58:23.513  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 12:58:23.513  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 12:58:23.513  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 12:58:23.513  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 12:58:23.513  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 12:58:23.513  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 12:58:23.513  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 12:58:23.513  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 12:58:23.513  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 12:58:23.513  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 12:58:23.513  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 12:58:23.513  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 12:58:23.513  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 12:58:23.513  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 12:58:23.513  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 12:58:23.513  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 12:58:23.513  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 12:58:23.513  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 1,2:58:23.513  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 12:58:23.513  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 12:58:23.513  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 12:58:23.513  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 12:58:23.514  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 12:58:23.514  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 12:58:23.514  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 12:58:23.514  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 12:58:23.514  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 12:58:23.514  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 12:58:23.514  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:58:23.514  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.514  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.514  6160  6233 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b8c048e not in the list
09-13 12:58:23.514  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:58:23.514  6160  6233 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27d564af not in the list
09-13 12:58:23.514  6160  6233 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:58:23.514  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.514  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.515  6160  6233 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-13 12:58:23.520  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 12:58:23.523  6160  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:58:23.523  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:23.523  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:23.523  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:23.523  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:23.523  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:23.523  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:23.523  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:23.524  6160  6233 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:58:23.525  6160  6233 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 12:58:23.526  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:23.526  6160  6233 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 12:58:23.527  6160  6233 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 12:58:23.527  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 12:58:23.527  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 12:58:23.527  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 12:58:23.530  6160  6233 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 12:58:23.532  1032  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 12:58:23.537  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 12:58:23.542  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 12:58:23.545  6160  6233 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-13 12:58:23.547  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 12:58:23.547  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 12:58:23.548  6160  6233 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 12:58:23.549  6160  6233 I io.jxcore.node.ConnectionHelper: start: OK
09-13 12:58:23.550  6160  6233 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-13 12:58:23.550  6160  6233 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 12:58:23.550  6160  6233 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 12:58:23.551  6160  6233 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 12:58:23.551  6160  6233 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-13 12:58:23.551  6160  6233 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 12:58:23.551  6160  6233 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 12:58:23.551  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 12:58:23.552  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 12:58:23.552  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 12:58:23.555  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 12:58:23.558  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 12:58:23.559  6160  6233 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 12:58:23.560  6160  6233 I io.jxcore.node.ConnectionHelper: start: OK
09-13 12:58:23.560  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:58:23.560  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.560  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 12:58:23.560  6160  6233 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b8c048e not in the list
09-13 12:58:23.560  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:58:23.560  6160  6233 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27d564af not in the list
09-13 12:58:23.560  6160  6233 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:58:23.560  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.561  6160  6233 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 12:58:23.563  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 12:58:23.565  6160  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:58:23.565  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:23.565  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:23.565  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:23.565  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:23.565  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:23.565  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:23.565  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:23.566  6160  6233 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:58:23.566  6160  6233 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 12:58:23.566  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:23.567  6160  6233 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 12:58:23.567  6160  6233 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 12:58:23.567  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 12:58:23.567  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 12:58:23.567  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 12:58:23.572  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 12:58:23.572  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 12:58:23.573  6160  6233 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 12:58:23.574  6160  6233 I io.jxcore.node.ConnectionHelper: start: OK
09-13 12:58:23.574  6160  6233 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-13 12:58:23.574  6160  6233 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 12:58:23.574  6160  6233 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 12:58:23.575  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:58:23.576  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.576  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 12:58:23.576  6160  6233 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b8c048e not in the list
09-13 12:58:23.576  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:58:23.576  6160  6233 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27d564af not in the list
09-13 12:58:23.576  6160  6233 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:58:23.576  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.577  6160  6233 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-13 12:58:23.577  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:58:23.577  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.577  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.577  6160  6233 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b8c048e not in the list
09-13 12:58:23.577  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:58:23.577  6160  6233 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27d564af not in the list
09-13 12:58:23.577  6160  6233 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:58:23.577  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.577  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.578  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 12:58:23.578  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:58:23.578  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.578  6160  6233 D org.thaliproject.p,2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.578  6160  6233 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b8c048e not in the list
09-13 12:58:23.578  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:58:23.578  6160  6233 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27d564af not in the list
09-13 12:58:23.578  6160  6233 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:58:23.578  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.578  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.579  6160  6233 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-13 12:58:23.579  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:58:23.579  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.579  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.579  6160  6233 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b8c048e not in the list
09-13 12:58:23.579  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:58:23.579  6160  6233 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27d564af not in the list
09-13 12:58:23.579  6160  6233 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:58:23.579  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.579  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.580  6160  6233 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-13 12:58:23.580  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:58:23.580  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.580  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.580  6160  6233 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b8c048e not in the list
09-13 12:58:23.580  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:58:23.580  6160  6233 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27d564af not in the list
09-13 12:58:23.580  6160  6233 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:58:23.580  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.580  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.580  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 12:58:23,.583  6160  6233 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 12:58:23.583  6160  6233 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 12:58:23.583  6160  6233 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 12:58:23.583  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 12:58:23.583  6160  6233 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 12:58:23.583  6160  6233 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 12:58:23.583  6160  6233 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 12:58:23.583  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 12:58:23.583  6160  6233 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 12:58:23.583  6160  6233 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 12:58:23.583  6160  6233 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 12:58:23.583  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:58:23.583  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.583  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.583  6160  6233 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b8c048e not in the list
09-13 12:58:23.583  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 12:58:23.583  6160  6233 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27d564af not in the list
09-13 12:58:23.583  6160  6233 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:58:23.583  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.583  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.584  6160  6233 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 12:58:23.584  6160  6233 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 12:58:23.584  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 12:58:23.586  6160  6233 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 12:58:23.586  6160  6233 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-13 12:58:23.586  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 12:58:23.586  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 12:58:23.586  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 12:58:23.586  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 12:58:23.586  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 12:58:23.587  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 12:58:23.587  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 12:58:23.587  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 12:58:23.587  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 12:58:23.587  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 12:58:23.587  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 12:58:23.587  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 12:58:23.587  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 12:58:23.587  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 12:58:23.587  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 12:58:23.587  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 12:58:23.587  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 12:58:23.587  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 12:58:23.587  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 12:58:23.587  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 12:58:23.587  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 12:58:23.587  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 12:58:23.587  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 12:58:23.587  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 12:58:23.587  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 12:58:23.587  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 12:58:23.587  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 12:58:23.587  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 12:58:23.587  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 12:58:23.587  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 12:58:23.587  6160  6233 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-13 12:58:23.587  6160  6233 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 12:58:23.587  6160  6233 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 12:58:23.588  6160  6233 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 12:58:23.588  6160  6233 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 12:58:23.588  6160  6233 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-13 12:58:23.588  6160  6233 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 12:58:23.588  6160  6233 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 12:58:23.588  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-13 12:58:23.601  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-13 12:58:23.602  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-13 12:58:23.602  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-13 12:58:23.603  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 12:58:23.603  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-13 12:58:23.603  6160  6233 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-13 12:58:23.603  6160  6233 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 12:58:23.603  6160  6233 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-13 12:58:23.603  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:58:23.603  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.603  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.604  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-13 12:58:23.604  6160  6233 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b8c048e not in the list
09-13 12:58:23.604  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:58:23.604  6160  6233 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27d564af not in the list
09-13 12:58:23.604  6160  6233 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:58:23.604  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.604  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.605  6160  6233 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-13 12:58:23.605  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:58:23.605  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.605  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.605  6160  6233 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b8c048e not in the list
09-13 12:58:23.605  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:58:23.605  6160  6233 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27d564af not in the list
09-13 12:58:23.605  6160  6233 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:58:23.605  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.605  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09,-13 12:58:23.605  6160  6233 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-13 12:58:23.606  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:58:23.606  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.606  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.606  6160  6233 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b8c048e not in the list
09-13 12:58:23.606  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:58:23.606  6160  6233 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27d564af not in the list
09-13 12:58:23.606  6160  6233 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:58:23.606  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.606  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.606  6160  6233 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-13 12:58:23.606  6160  6233 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 12:58:23.607  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 12:58:23.610  6160  6240 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 794)
09-13 12:58:23.621  6160  6241 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 794
09-13 12:58:23.625  6160  6233 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 12:58:23.625  6160  6233 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 12:58:23.625  6160  6233 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 12:58:23.625  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 12:58:23.625  6160  6233 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 12:58:23.625  6160  6233 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 12:58:23.625  6160  6233 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 12:58:23.625  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 12:58:23.625  6160  6233 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 12:58:23.626  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:58:23.626  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.626  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.626  6160  6233 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b8c048e not in the list
09-13 12:58:23.626  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:58:23.626  6160  6233 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27d564af not in the list
09-13 12:58:23.626  6160  6233 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:58:23.626  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.626  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.626  6160  6233 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 12:58:23.634  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 12:58:23.636  6160  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:58:23.636  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:23.636  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:23.636  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:23.636  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:23.636  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:23.636  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:23.636  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:23.637  6160  6233 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:58:23.637  6160  6233 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 12:58:23.637  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:23.638  6160  6233 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 12:58:23.638  6160  6233 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 12:58:23.638  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 12:58:23.638  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 12:58:23.638  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 12:58:23.641  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 12:58:23.642  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 12:58:23.643  6160  6233 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 12:58:23.644  6160  6233 I io.jxcore.node.ConnectionHelper: start: OK
09-13 12:58:23.644  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:58:23.644  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.644  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 12:58:23.644  6160  6233 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b8c048e not in the list
09-13 12:58:23.644  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:58:23.644  6160  6233 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27d564af not in the list
09-13 12:58:23.644  6160  6233 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:58:23.644  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.646  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:58:23.646  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.646  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.646  6160  6233 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b8c048e not in the list
09-13 12:58:23.646  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:58:23.646  6160  6233 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27d564af not in the list
09-13 12:58:23.646  6160  6233 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:58:23.646  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.646  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.648  6160  6233 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 12:58:23.648  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 12:58:23.651  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 12:58:23.652  6160  6233 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 12:58:23.652  6160  6233 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 12:58:23.653  6160  6160 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 12:58:23.653  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 12:58:23.653  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 12:58:23.654  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:58:23.654  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 12:58:23.654  6160  6233 I org.thaliproject.p2p.btconnecto,rlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 12:58:23.655  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 12:58:23.655  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.655  6160  6233 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 12:58:23.655  6160  6160 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 12:58:23.655  6160  6233 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b8c048e not in the list
09-13 12:58:23.655  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:58:23.655  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 12:58:23.655  6160  6233 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 12:58:23.655  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 12:58:23.656  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 12:58:23.658  6160  6249 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 12:58:23.658  6160  6249 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 12:58:23.661  6160  6233 D BluetoothLeScanner: could not find callback wrapper
09-13 12:58:23.661  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 12:58:23.661  6160  6233 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
09-13 12:58:23.661  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.661  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 12:58:23.668  6160  6233 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 12:58:23.668  6160  6233 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27d564af not in the list
09-13 12:58:23.668  6160  6160 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 12:58:23.668  6160  6233 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:58:23.668  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.668  6160  6160 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 12:58:23.668  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.668  6160  6160 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 12:58:23.668  6160  6160 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 12:58:23.669  6160  6233 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-13 12:58:23.669  6160  6233 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 12:58:23.669  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 12:58:23.670  6160  6233 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 12:58:23.670  6160  6233 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 12:58:23.670  6160  6233 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 12:58:23.670  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:58:23.670  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.670  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.670  6160  6233 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b8c048e not in the list
09-13 12:58:23.670  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:58:23.670  6160  6233 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27d564af not in the list
09-13 12:58:23.670  6160  6233 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:58:23.670  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.670  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.672  1032  1572 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 12:58:23.672  1032  1047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 12:58:23.673  1032  2026 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 12:58:23.673  6160  6233 I org.thaliproject.p2p.b,tconnectorlib.ConnectionManager: dispose
09-13 12:58:23.673  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.673  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.673  6160  6233 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b8c048e not in the list
09-13 12:58:23.673  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:58:23.673  6160  6233 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27d564af not in the list
09-13 12:58:23.673  6160  6233 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:58:23.673  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.673  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 12:58:23.674  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:58:23.674  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.674  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.674  6160  6233 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b8c048e not in the list
09-13 12:58:23.674  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:58:23.674  6160  6233 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27d564af not in the list
09-13 12:58:23.674  6160  6233 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:58:23.674  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:23.674  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:23.675  6160  6233 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-13 12:58:23.675  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 12:58:23.675  6160  6233 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-13 12:58:23.675  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 12:58:23.675  6160  6233 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-13 12:58:23.675  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 12:58:23.677  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 12:58:23.677  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-13 12:58:23.678  6160  6233 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-13 12:58:23.678  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 12:58:23.678  6160  6233 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-13 12:58:23.678  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 12:58:23.678  6160  6233 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-13 12:58:23.678  6160  6233 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-13 12:58:23.678  6160  6233 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-13 12:58:23.678  6160  6233 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-13 12:58:23.679  6160  6233 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-13 12:58:23.679  6160  6233 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 12:58:23.679  6160  6233 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-13 12:58:23.679  6160  6233 D io,.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-13 12:58:23.681  6160  6233 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 12:58:23.681  6160  6233 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31299afd added. We now have 4 listener(s)
09-13 12:58:23.681  1032  1989 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 12:58:23.682  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 12:58:23.682  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 12:58:23.683  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 12:58:23.683  6160  6233 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 12:58:23.683  6160  6233 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@389e43f2 added. We now have 4 listener(s)
09-13 12:58:23.683  6160  6233 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 12:58:23.683  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 12:58:23.684  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 12:58:23.687  6160  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:58:23.687  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:23.687  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:23.687  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:23.687  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:23.687  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:23.687  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:23.687  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:23.688  6160  6233 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:58:23.688  6160  6233 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 12:58:23.688  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:58:23.689  6160  6233 D BluetoothAdapter: enable(): BT is already enabled..!
09-13 12:58:23.690  1032  1953 D WifiServiceImplEx: setWifiEnabled: true pid=6160, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 12:58:23.691  1032  1953 D WifiService: setWifiEnabled: true pid=6160, uid=10118
09-13 12:58:23.691  1032  1953 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 12:58:23.696  1032  2026 D WifiServiceImplEx: setWifiEnabled: false pid=6160, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 12:58:23.696  1032  2026 D WifiService: setWifiEnabled: false pid=6160, uid=10118
09-13 12:58:23.696  1032  2026 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 12:58:23.718  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 12:58:23.718  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 12:58:23.718  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-13 12:58:23.718  1032  1390 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT 0 0
09-13 12:58:23.719  1032  1390 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-13 12:58:23.719  1032  1390 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-13 12:58:23.719  1032  1390 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-13 12:58:23.720  6160  6240 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-13 12:58:23.720  6160  6240 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 12:58:23.720  1032  1387 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:23.720  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:23.720  1032  1387 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@360e7ebd
09-13 12:58:23.720  3826  3942 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 12:58:23.721  3826  4014 W bt-l2cap: L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 001122334455  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
09-13 12:58:23.721  3826  3942 D LGBluetoothServiceAdapter: [BTUI] connectSocket FD=84 mFd=82
09-13 12:58:23.721  1032  1387 D LGWifiP2pService: P2pDisablingState
09-13 12:58:23.721  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 1
09-13 12:58:23.721  1032  1387 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:23.721  1032  1552 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:23.721  1032  1387 D LGWifiP2pService: p2p socket connection lost
09-13 12:58:23.721  1032  1032 D RttService: SCAN_AVAILABLE : 1
09-13 12:58:23.721  1032  1553 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:23.722  1032  1387 D LGWifiP2pService: P2pDisabledState
09-13 12:58:23.722  1936  1936 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 12:58:23.723  1936  1936 D WfdsService: WifiP2pState is changed : false
09-13 12:58:23.723  1936  2261 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-13 12:58:23.723  1936  2261 D WfdsService: Set the WFDS Monitor: false
09-13 12:58:23.723  1936  2261 D WfdsMonitor: WFDS Monitor is stopped
09-13 12:58:23.724  1936  2261 D WfdsService: STATE : WfdsDisabledState - enter
09-13 12:58:23.724  1936  2803 D CtrlSupplicant: Received on exit socket, terminate
09-13 12:58:23.724  1936  2803 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-13 12:58:23.724  1936  2803 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-13 12:58:23.724  1936  2803 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-13 12:58:23.724  1936  2261 W WfdsService: DefaultState - msg [9445378] is not handled
09-13 12:58:23.724  1032  1390 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-13 12:58:23.724  1936  2276 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-13 12:58:23.724   308   890 D CommandListener: Clearing all IP addresses on wlan0
09-13 12:58:23.726  1032  1032 D WifiHS20: hidePasspointNotification off =false
09-13 12:58:23.727  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/,DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,09-13 12:58:23.727  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 12:58:23.729  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:23.729  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:23.729  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 12:58:23.730  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:23.730  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 12:58:23.730  1032  1390 D WifiNative-p2p0: doBoolean: TERMINATE
09-13 12:58:23.732  1032  1390 D WifiNative-p2p0: TERMINATE: returned true
09-13 12:58:23.732  1032  1032 D WifiHS20: hidePasspointNotification off =false
09-13 12:58:23.732  1032  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 12:58:23.732  1032  1390 E WifiStateMachine: useWiFiOffloading() : false
09-13 12:58:23.732  1032  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 12:58:23.732  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:23.732  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:23.732  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 12:58:23.734  1936  1936 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-13 12:58:23.735  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-13 12:58:23.735  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 12:58:23.735  1032  1032 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-13 12:58:23.736  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:23.736  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:23.736  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:23.736  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 12:58:23.736  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:23.736  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:23.736  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:23.736  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:23.738  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 12:58:23.741  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:23.741  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:23.741  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:23.741  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 12:58:23.741  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:23.741  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:23.741  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:23.741  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:23.742  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:58:23.744  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:23.744  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:23.744  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:23.744  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 12:58:23.744  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:23.744  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:23.744  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:23.744  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:23.745  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:58:23.747  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:23.747  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:23.747  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:23.747  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 12:58:23.747  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:23.747  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:23.747  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:23.747  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:23.748  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:58:23.749  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-13 12:58:23.749  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 12:58:23.750  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:23.766  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 12:58:23.778  1032  1727 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6263 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-13 12:58:23.823  6263  6263 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-13 12:58:23.826  6263  6263 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 12:58:23.826  6263  6263 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 12:58:23.832  2619  2619 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-13 12:58:23.832  2619  2619 I wpa_supplicant: monitor socket send errors count : 1
09-13 12:58:23.832  2619  2619 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1936-2\x00 that cannot receive messages
09-13 12:58:23.833  1032  2801 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-13 12:58:23.834  1032  2801 D WifiMonitor: Dropping event because (p2p0) is stopped
,09-13 12:58:23.865  1032  1953 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6285 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-13 12:58:23.867  2619  2619 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 12:58:23.868  2619  2619 W wpa_supplicant: USIM:  scard_deinit function
09-13 12:58:23.868  1032  2801 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-13 12:58:23.868  1032  2801 E WifiMonitor: WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 12:58:23.868  1032  2801 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 12:58:23.868  1032  2801 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-13 12:58:23.869  1032  2801 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 12:58:23.869  1032  2801 E WifiMonitor: WifiMonitor:wlan0 cnt=13 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 12:58:23.869  1032  1094 D Tethering: InitialState.processMessage what=4
09-13 12:58:23.870  1032  1953 I ActivityManager: Killing 4830:com.android.providers.calendar/u0a14 (adj 15): empty #17
09-13 12:58:23.870  1032  1390 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=196965
09-13 12:58:23.870  1032  1390 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=196966
09-13 12:58:23.870  1032  1390 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=196966  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 12:58:23.871  1032  1390 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=196967  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 12:58:23.912  1032  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-13 12:58:23.916  1032  1935 W libprocessgroup: failed to open /acct/uid_10014/pid_4830/cgroup.procs: No such file or directory
09-13 12:58:23.919  1032  1390 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-13 12:58:23.919  1032  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 12:58:23.919   308  6302 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-13 12:58:23.921  1032  1092 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-13 12:58:23.934  6285  6285 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 12:58:23.935  6285  6285 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,09-13 12:58:23.935  6285  6285 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 12:58:23.935  6285  6285 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-13 12:58:23.937  6285  6285 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 12:58:23.938  6285  6285 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-13 12:58:23.942  2619  2619 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-13 12:58:23.943  1032  2801 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-13 12:58:23.943  1032  2801 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-TERMINATING 
09-13 12:58:23.944  1032  2801 D WifiMonitor: Disconnecting from the supplicant, no more events
,09-13 12:58:23.946  1032  1390 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 14 0
09-13 12:58:24.037  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 12:58:24.049  1032  1390 D WifiOffDelayIfNotUsed: stopMonitoring
09-13 12:58:24.049  1032  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 12:58:24.049  1032  1390 E WifiStateMachine: useWiFiOffloading() : false
09-13 12:58:24.049  1032  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 12:58:24.052  1936  1936 D WfdsService: Supplicant Connection state is changed : false
,09-13 12:58:24.052  1936  2261 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-13 12:58:24.053  1936  2261 D WfdsService: Set the WFDS Monitor: false
,09-13 12:58:24.053  1936  2261 D WfdsMonitor: WFDS Monitor is stopped
09-13 12:58:24.053  1936  1936 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 12:58:24.054  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:24.057  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-13 12:58:24.058  2491  2491 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:24.058  1032  1439 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-13 12:58:24.059  1032  1439 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-13 12:58:24.059  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:24.060  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:24.062  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:24.064  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:24.085  6285  6285 D LgDataFeature: LgDataFeature() Constructor: none
,09-13 12:58:24.085  6285  6285 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 12:58:24.095  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:24.137  1032  1048 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6308 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-13 12:58:24.139  1032  1048 I ActivityManager: Killing 5703:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,09-13 12:58:24.168  6160  6160 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 12:58:24.172  1032  1899 W libprocessgroup: failed to open /acct/uid_10008/pid_5703/cgroup.procs: No such file or directory
09-13 12:58:24.195  6308  6308 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-13 12:58:24.218  6308  6308 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-13 12:58:24.225  6160  6258 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:24.228  1032  1047 D WifiServiceImplEx: setWifiEnabled: true pid=6160, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 12:58:24.229  1032  1047 D WifiService: setWifiEnabled: true pid=6160, uid=10118
09-13 12:58:24.229  1032  1047 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 12:58:24.245  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 12:58:24.246  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 12:58:24.246  1032  1032 D Ulp_jni : JNI:system_update. Event-4
,09-13 12:58:24.251  1032  1390 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-13 12:58:24.251  1032  1390 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-13 12:58:24.260  1032  1390 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-13 12:58:24.260  1032  1390 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-13 12:58:24.260  1032  1390 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-13 12:58:24.260  1032  1390 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-13 12:58:24.260  1032  1390 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-13 12:58:24.260  1032  1390 E WifiHW  : unknown target_country: EU , set to default
09-13 12:58:24.260  1032  1390 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-13 12:58:24.260  1032  1390 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-13 12:58:24.260  1032  1390 I WifiUtil: gEnableBmps=1
09-13 12:58:24.261  6308  6308 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,09-13 12:58:24.261  6308  6308 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-13 12:58:24.262  6308  6308 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-13 12:58:24.262  6308  6308 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-13 12:58:24.262  6308  6308 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-13 12:58:24.264  6308  6308 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-13 12:58:24.270  6308  6308 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-13 12:58:24.277  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 12:58:24.280  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 12:58:24.292  6308  6308 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-13 12:58:24.295  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 12:58:24.298  6263  6263 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 12:58:24.298  6263  6263 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 12:58:24.298  6263  6263 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 12:58:24.300  6308  6308 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-13 12:58:24.301  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 12:58:24.308  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:24.308  6308  6308 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-13 12:58:24.314  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 12:58:24.315  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 12:58:24.317  6308  6308 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-13 12:58:24.354  1032  2026 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6333 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-13 12:58:24.424  6263  6263 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 12:58:24.426  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 12:58:24.432  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:24.444  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 12:58:24.444  6285  6285 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 12:58:24.445  6285  6285 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 12:58:24.445  6285  6285 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,09-13 12:58:24.449  6333  6352 W FormManager: Network not available. Please check & try again.
09-13 12:58:24.449  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 12:58:24.455  6333  6353 V FormManager: Network unavailable.
09-13 12:58:24.456  6333  6353 V FormManager: Network unavailable.
09-13 12:58:24.458  6285  6285 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 12:58:24.458  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 12:58:24.458  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 12:58:24.458  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 12:58:24.458  6285  6285 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 12:58:24.459  6285  6285 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-13 12:58:24.464  4265  4265 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 12:58:24.464  4265  4265 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 12:58:24.466  4265  4265 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 12:58:24.469  4265  4265 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 12:58:24.472  1032  1772 I ActivityManager: Killing 5591:com.android.defcontainer/u0a4 (adj 15): empty #17
09-13 12:58:24.478  4265  6357 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,09-13 12:58:24.480  4265  6357 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 12:58:24.480  4265  6356 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 12:58:24.504  1032  2026 W libprocessgroup: failed to open /acct/uid_10004/pid_5591/cgroup.procs: No such file or directory
,09-13 12:58:24.516  6263  6263 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-13 12:58:24.516  6263  6263 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 12:58:24.516  6263  6263 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 12:58:24.521  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-13 12:58:24.531  6333  6360 W FormManager: Network not available. Please check & try again.
09-13 12:58:24.532  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:24.538  6333  6361 V FormManager: Network unavailable.
,09-13 12:58:24.545  6333  6361 V FormManager: Network unavailable.
09-13 12:58:24.551  6308  6308 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-13 12:58:24.554  6308  6308 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-13 12:58:24.554  6308  6308 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-13 12:58:24.592  6308  6308 D LgDataFeature: LgDataFeature() Constructor: none
09-13 12:58:24.592  6308  6308 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 12:58:24.600  6308  6308 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-13 12:58:24.602  6308  6308 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-13 12:58:24.602  6308  6308 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-13 12:58:24.602  6308  6308 V SoundPool: doLoad: loading sample sampleID=1
09-13 12:58:24.603  6308  6308 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-13 12:58:24.606  6308  6364 V SoundPool: Start decode
09-13 12:58:24.606  6308  6364 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,09-13 12:58:24.609   315  2166 V MediaPlayerService: decode(23, 10857164, 17813)
09-13 12:58:24.610   315  2166 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
,09-13 12:58:24.610   315  2166 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-13 12:58:24.610   315  2166 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-13 12:58:24.610   315  2166 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-13 12:58:24.611   315  2166 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
,09-13 12:58:24.611   315  2166 V MediaPlayerService: player type = 3
09-13 12:58:24.611   315  2166 V AwesomePlayer: AwesomePlayer create()
09-13 12:58:24.612   315  2166 V AwesomePlayer: reset_l() 
09-13 12:58:24.612   315  2166 V AwesomePlayer: cancelPlayerEvents
09-13 12:58:24.612   315  2166 V AwesomePlayer: setAudioSink() 
09-13 12:58:24.612   315  2166 V AwesomePlayer: reset_l() 
09-13 12:58:24.612   315  2166 V AudioCache: notify(0xb54745c0, 8, 0, 0)
09-13 12:58:24.612   315  2166 V AudioCache: ignored
09-13 12:58:24.612   315  2166 V AwesomePlayer: cancelPlayerEvents
09-13 12:58:24.613   315  2166 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-13 12:58:24.613   315  2166 V AwesomePlayer: setDataSource_l dataSource
09-13 12:58:24.613   315  2166 V LGParserOSAL: SniffLGParser start
09-13 12:58:24.613   315  2166 V LGParserOSAL: MainType:5, SubType=0
09-13 12:58:24.613   315  2166 V LGParserOSAL: #### check Mime : application/ogg
09-13 12:58:24.613   315  2166 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-13 12:58:24.613   315  2166 E MediaExtractor: Use LGExtractor :application/ogg 
09-13 12:58:24.614  6039  6039 D UEI.SmartControl: QS Service created
09-13 12:58:24.622  6308  6308 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-13 12:58:24.625  6308  6308 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-13 12:58:24.626  6308  6308 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-13 12:58:24.641  6308  6308 V LGMDMManager: Create singleton instance
09-13 12:58:24.648  6039  6039 I UEI.SmartControl: Service initServices...
09-13 12:58:24.648  6039  6039 D UEI.SmartControl: QS start get config
,09-13 12:58:24.677   315  2166 V LGParserOSAL: supported mime: application/ogg
09-13 12:58:24.677   315  2166 V AwesomePlayer: setDataSource_l() extractor countTracks=1
,09-13 12:58:24.677   315  2166 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-13 12:58:24.677   315  2166 V AwesomePlayer: mBitrate = -1 bits/sec
09-13 12:58:24.677   315  2166 V AwesomePlayer: AudioTrack Setting
09-13 12:58:24.677   315  2166 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-13 12:58:24.677   315  2166 V AwesomePlayer: setAudioSource() 
09-13 12:58:24.677   315  2166 V MediaPlayerService: prepare
09-13 12:58:24.677   315  2166 V AwesomePlayer: prepareAsync_l() 
09-13 12:58:24.678   315  2166 V MediaPlayerService: wait for prepare
09-13 12:58:24.678   315  6369 V AwesomePlayer: onPrepareAsyncEvent() 
09-13 12:58:24.678   315  6369 V AwesomePlayer: initAudioDecoder() 
09-13 12:58:24.678   315  6369 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-13 12:58:24.678   315  6369 V AudioSystem: isOffloadSupported()
09-13 12:58:24.678   315  6369 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-13 12:58:24.678   315  6369 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-13 12:58:24.679   315  6369 I AudioFlinger: isAudioPlaybackHookOn() false
09-13 12:58:24.679   315  6369 V AwesomePlayer: getUseOffload() = 0 
09-13 12:58:24.679   315  6369 V OMXCodec: OMXCodec::Create
09-13 12:58:24.679   315  6369 V OMXCodec: findMatchingCodecs()
09-13 12:58:24.679   315  6369 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-13 12:58:24.679   315  6369 V OMXCodec: matchingCodecs.size()=1
09-13 12:58:24.679   315  6369 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-13 12:58:24.681   315  6369 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-13 12:58:24.681   315  6369 V LGCodecAdapter: LG Codec Adapter start
09-13 12:58:24.681   315  6369 V OMXCodec: OMXCodec Createtor
09-13 12:58:24.681   315  6369 V OMXCodec: setComponentRole
09-13 12:58:24.681   315  6369 V OMXCodec: configureCodec protected=0
09-13 12:58:24.681   315  6369 V LGCodecAdapter: called getLGCodecSpecificData
09-13 12:58:24.681   315  6369 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-13 12:58:24.682   315  6369 V LGCodecOSAL: Called LGconfigureCodecMETA
09-13 12:58:24.682   315  6369 V LGCodecOSAL: Called LGconfigureCodecMSG
09-13 12:58:24.682   315  6369 V LGCodecOSAL: Not support LGCodec
09-13 12:58:24.682   315  6369 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-13 12:58:24.682   315  6369 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-13 12:58:24.682   315  6369 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-13 12:58:24.682   315  6369 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-13 12:58:24.682   315  6369 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-13 12:58:24.682   315  6369 V AudioSystem: isOffloadSupported()
09-13 12:58:24.682   315  6369 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-13 12:58:24.682   315  6369 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-13 12:58:24.682   315  6369 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-13 12:58:24.683   315  6369 V OMXCodec: init()
09-13 12:58:24.683   315  6369 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-13 12:58:24.683   315  6369 V OMXCodec: allocateBuffers
09-13 12:58:24.683   315  6369 V OMXCodec: allocateBuffersOnPort portIndex=0
09-1,3 12:58:24.683   315  6369 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-13 12:58:24.683   315  6369 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
09-13 12:58:24.683   315  6369 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
09-13 12:58:24.683   315  6369 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
09-13 12:58:24.683   315  6369 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on input port
09-13 12:58:24.683   315  6369 V OMXCodec: allocateBuffersOnPort portIndex=1
09-13 12:58:24.683   315  6369 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-13 12:58:24.683   315  6369 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
09-13 12:58:24.683   315  6369 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
09-13 12:58:24.683   315  6369 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bf060 on output port
09-13 12:58:24.683   315  6369 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bf240 on output port
09-13 12:58:24.683   315  6369 V OMXCodec: init() mAsyncCompletion wait!!! 
09-13 12:58:24.684   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-13 12:58:24.685   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-13 12:58:24.685   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-13 12:58:24.685   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-13 12:58:24.685   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-13 12:58:24.685   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-13 12:58:24.685   315  6369 V OMXCodec: init() mAsyncCompletion wait free! 
09-13 12:58:24.685   315  6369 V AwesomePlayer: finishAsyncPrepare_l() 
09-13 12:58:24.685   315  6369 V AudioCache: notify(0xb54745c0, 5, 0, 0)
09-13 12:58:24.685   315  6369 V AudioCache: ignored
09-13 12:58:24.685   315  6369 V AudioCache: notify(0xb54745c0, 1, 0, 0)
09-13 12:58:24.685   315  6369 V AudioCache: prepared
09-13 12:58:24.685   315  2166 V AudioCache: wait - success
09-13 12:58:24.685   315  2166 V MediaPlayerService: start
09-13 12:58:24.685   315  2166 V AwesomePlayer: play_l() 
09-13 12:58:24.685   315  2166 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-13 12:58:24.685   315  2166 V AwesomePlayer: createAudioPlayer_l
09-13 12:58:24.685   315  2166 V AwesomePlayer: seekAudioIfNecessary_l() 
09-13 12:58:24.685   315  2166 V AwesomePlayer: startAudioPlayer_l() 
09-13 12:58:24.685   315  2166 D AudioPlayer: start of Playback, useOffload 0
09-13 12:58:24.685   315  2166 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-13 12:58:24.685   315  2166 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
,09-13 12:58:24.688   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-13 12:58:24.688   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-13 12:58:24.688   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-13 12:58:24.688   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-13 12:58:24.688   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-13 12:58:24.689   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-13 12:58:24.689   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
09-13 12:58:24.689   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 12:58:24.689   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886128
09-13 12:58:24.689   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 12:58:24.689   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044798560
09-13 12:58:24.689   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 12:58:24.689   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044799040
,09-13 12:58:24.689   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 12:58:24.689   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-13 12:58:24.689   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-13 12:58:24.689   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-13 12:58:24.689   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-13 12:58:24.689   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-13 12:58:24.689   315  6371 V OMXCodec: allocateBuffersOnPort portIndex=1
09-13 12:58:24.689   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-13 12:58:24.689   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bf060 on output port
,09-13 12:58:24.690   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
09-13 12:58:24.690   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
09-13 12:58:24.690   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bf830 on output port
09-13 12:58:24.690   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-13 12:58:24.690   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
,09-13 12:58:24.697   315  2166 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-13 12:58:24.700   315  2166 V AudioCache: notify(0xb54745c0, 6, 0, 0)
09-13 12:58:24.700   315  2166 V AudioCache: ignored
09-13 12:58:24.700   315  2166 V MediaPlayerService: wait for playback complete
09-13 12:58:24.700   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.700   315  6373 V AudioCache: memcpy(0xaf006000, 0xb0406000, 4096)
09-13 12:58:24.703   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.703   315  6373 V AudioCache: memcpy(0xaf007000, 0xb0406000, 4096)
09-13 12:58:24.703   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.703   315  6373 V AudioCache: memcpy(0xaf008000, 0xb0406000, 4096)
09-13 12:58:24.703   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.703   315  6373 V AudioCache: memcpy(0xaf009000, 0xb0406000, 4096)
09-13 12:58:24.704   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.704   315  6373 V AudioCache: memcpy(0xaf00a000, 0xb0406000, 4096)
09-13 12:58:24.705   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.705   315  6373 V AudioCache: memcpy(0xaf00b000, 0xb0406000, 4096)
09-13 12:58:24.705   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.705   315  6373 V AudioCache: memcpy(0xaf00c000, 0xb0406000, 4096)
09-13 12:58:24.707   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.707   315  6373 V AudioCache: memcpy(0xaf00d000, 0xb0406000, 4096)
09-13 12:58:24.708   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.708   315  6373 V AudioCache: memcpy(0xaf00e000, 0xb0406000, 4096)
09-13 12:58:24.708   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.708   315  6373 V AudioCache: memcpy(0xaf00f000, 0xb0406000, 4096)
09-13 12:58:24.709   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.709   315  6373 V AudioCache: memcpy(0xaf010000, 0xb0406000, 4096)
09-13 12:58:24.710   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.710   315  6373 V AudioCache: memcpy(0xaf011000, 0xb0406000, 4096)
09-13 12:58:24.711   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.711   315  6373 V AudioCache: memcpy(0xaf012000, 0xb0406000, 4096)
09-13 12:58:24.711   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.712   315  6373 V AudioCache: memcpy(0xaf013000, 0xb0406000, 4096)
09-13 12:58:24.712   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.712   315  6373 V AudioCache: memcpy(0xaf014000, 0xb0406000, 4096)
09-13 12:58:24.713   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.713   315  6373 V AudioCache: memcpy(0xaf015000, 0xb0406000, 4096)
09-13 12:58:24.714   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.714   315  6373 V AudioCache: memcpy(0xaf016000, 0xb0406000, 4096)
09-13 12:58:24.714   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.714   315  6373 V AudioCache: memcpy(0xaf017000, 0xb0406000, 4096)
09-13 12:58:24.715   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.715   315  6373 V AudioCache: memcpy(0xaf018000, 0xb0406000, 4096)
09-13 12:58:24.716   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.716   315  6373 V AudioCache: memcpy(0xaf019000, 0xb0406000, 4096)
09-13 12:58:24.716   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.717   315  6373 V AudioCache: memcpy(0xaf01a000, 0xb0406000, 4096)
09-13 12:58:24.717   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.717   315  6373 V AudioCache: memcpy(0xaf01b000, 0xb0406000, 4096)
09-13 12:58:24.718   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.718   315  6373 V AudioCache: memcpy(0xaf01c000, 0xb0406000, 4096)
09-13 12:58:24.719   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.719   315  6373 V AudioCache: memcpy(0xaf01d000, 0xb0406000, 4096)
09-13 12:58:24.720   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.720   315  6373 V AudioCache: memcpy(0xaf01e000, 0xb040600,0, 4096)
09-13 12:58:24.720   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.720   315  6373 V AudioCache: memcpy(0xaf01f000, 0xb0406000, 4096)
,09-13 12:58:24.721   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.721   315  6373 V AudioCache: memcpy(0xaf020000, 0xb0406000, 4096)
09-13 12:58:24.722   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.722   315  6373 V AudioCache: memcpy(0xaf021000, 0xb0406000, 4096)
09-13 12:58:24.724   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.724   315  6373 V AudioCache: memcpy(0xaf022000, 0xb0406000, 4096)
09-13 12:58:24.725   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.725   315  6373 V AudioCache: memcpy(0xaf023000, 0xb0406000, 4096)
09-13 12:58:24.725   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.726   315  6373 V AudioCache: memcpy(0xaf024000, 0xb0406000, 4096)
09-13 12:58:24.726   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.726   315  6373 V AudioCache: memcpy(0xaf025000, 0xb0406000, 4096)
09-13 12:58:24.727   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.727   315  6373 V AudioCache: memcpy(0xaf026000, 0xb0406000, 4096)
09-13 12:58:24.728   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.728   315  6373 V AudioCache: memcpy(0xaf027000, 0xb0406000, 4096)
09-13 12:58:24.728   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.728   315  6373 V AudioCache: memcpy(0xaf028000, 0xb0406000, 4096)
09-13 12:58:24.729   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.729   315  6373 V AudioCache: memcpy(0xaf029000, 0xb0406000, 4096)
09-13 12:58:24.733   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.733   315  6373 V AudioCache: memcpy(0xaf02a000, 0xb0406000, 4096)
09-13 12:58:24.735   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.735   315  6373 V AudioCache: memcpy(0xaf02b000, 0xb0406000, 4096)
,09-13 12:58:24.735   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.735   315  6373 V AudioCache: memcpy(0xaf02c000, 0xb0406000, 4096)
09-13 12:58:24.736   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.736   315  6373 V AudioCache: memcpy(0xaf02d000, 0xb0406000, 4096)
09-13 12:58:24.737   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.737   315  6373 V AudioCache: memcpy(0xaf02e000, 0xb0406000, 4096)
09-13 12:58:24.737   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.737   315  6373 V AudioCache: memcpy(0xaf02f000, 0xb0406000, 4096)
09-13 12:58:24.738   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.738   315  6373 V AudioCache: memcpy(0xaf030000, 0xb0406000, 4096)
09-13 12:58:24.739   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.739   315  6373 V AudioCache: memcpy(0xaf031000, 0xb0406000, 4096)
09-13 12:58:24.740   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.740   315  6373 V AudioCache: memcpy(0xaf032000, 0xb0406000, 4096)
09-13 12:58:24.740   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.740   315  6373 V AudioCache: memcpy(0xaf033000, 0xb0406000, 4096)
09-13 12:58:24.741   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.741   315  6373 V AudioCache: memcpy(0xaf034000, 0xb0406000, 4096)
09-13 12:58:24.742   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.742   315  6373 V AudioCache: memcpy(0xaf035000, 0xb0406000, 4096)
09-13 12:58:24.742   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.743   315  6373 V AudioCache: memcpy(0xaf036000, 0xb0406000, 4096)
09-13 12:58:24.745   315  6373 V AudioCache: write(0xb0406000, 4096)
09-13 12:58:24.745   315  6373 V AudioCache: memcpy(0xaf037000, 0xb0406000, 4096)
09-13 12:58:24.746   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-13 12:58:24.746   315  6373 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-13 12:58:24.746   315  6373 V AwesomePlayer: postAudioEOS() 
09-13 12:58:24.746   315  6373 V AudioCache: write(0xb0406000, 280)
09-13 12:58:24.746   315  6373 V AudioCache: memcpy(0xaf038000, 0xb0406000, 280)
09-13 12:58:24.747   315  6369 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-13 12:58:24.747   315  6369 V AwesomePlayer: onStreamDone
09-13 12:58:24.747   315  6369 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-13 12:58:24.748   315  6369 V AudioCache: notify(0xb54745c0, 2, 0, 0)
09-13 12:58:24.748   315  6369 V AudioCache: playback complete
09-13 12:58:24.748   315  6369 V AwesomePlayer: pause_l() 
09-13 12:58:24.748   315  2166 V AudioCache: wait - success
09-13 12:58:24.748   315  2166 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-13 12:58:24.748   315  6369 V AudioCache: notify(0xb54745c0, 7, 0, 0)
09-13 12:58:24.748   315  6369 V AudioCache: ignored
09-13 12:58:24.748   315  6369 V AwesomePlayer: cancelPlayerEvents
09-13 12:58:24.748   315  6369 D AudioPlayer: Pause Playback at 1068125
09-13 12:58:24.748   315  2166 V AwesomePlayer: reset_l() 
09-13 12:58:24.748   315  2166 V AudioCache: notify(0xb54745c0, 8, 0, 0)
09-13 12:58:24.748   315  2166 V AudioCache: ignored
09-13 12:58:24.748   315  2166 V AwesomePlayer: cancelPlayerEvents
09-13 12:58:24.748   315  2166 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-13 12:58:24.749   315  2166 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-13 12:58:24.749   315  2166 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-13 12:58:24.749   315  2166 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-13 12:58:24.749   315  2166 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-13 12:58:24.749   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-13 12:58:24.749   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-13 12:58:24.749   315  63,71 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-13 12:58:24.749   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 0
09-13 12:58:24.749   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-13 12:58:24.749   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
09-13 12:58:24.749   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-13 12:58:24.749   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
09-13 12:58:24.749   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-13 12:58:24.750   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
09-13 12:58:24.750   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-13 12:58:24.750   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-13 12:58:24.750   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bf830 on port 1
09-13 12:58:24.750   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-13 12:58:24.750   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
09-13 12:58:24.750   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-13 12:58:24.750   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7fb0 on port 1
09-13 12:58:24.750   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-13 12:58:24.750   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bf060 on port 1
09-13 12:58:24.750   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-13 12:58:24.750   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-13 12:58:24.750   315  2166 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-13 12:58:24.750   315  2166 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-13 12:58:24.751   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-13 12:58:24.751   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
,09-13 12:58:24.751   315  6371 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-13 12:58:24.751   315  2166 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-13 12:58:24.751   315  2166 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-13 12:58:24.751   315  2166 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
,09-13 12:58:24.752  1032  1048 D WifiServiceImplEx: setWifiEnabled: true pid=6160, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 12:58:24.753  1032  1048 D WifiService: setWifiEnabled: true pid=6160, uid=10118
09-13 12:58:24.753  1032  1048 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 12:58:24.753  1032  1442 D WifiController: Mismatch in the state 1
09-13 12:58:24.762   315  2166 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-13 12:58:24.762   315  2166 D AudioPlayer: AudioPlayer releasing audio source
09-13 12:58:24.762   315  2166 D AudioPlayer: AudioPlayer done releasing audio source
09-13 12:58:24.762   315  2166 V AwesomePlayer: reset_l() 
09-13 12:58:24.762   315  2166 V AwesomePlayer: cancelPlayerEvents
09-13 12:58:24.762   315  2166 V AwesomePlayer: ~AwesomePlayer call
09-13 12:58:24.762   315  2166 V AwesomePlayer: reset_l() 
09-13 12:58:24.762   315  2166 V AwesomePlayer: cancelPlayerEvents
09-13 12:58:24.763  6308  6364 V SoundPool: close(31)
09-13 12:58:24.763  6308  6364 V SoundPool: pointer = 0xa0011000, size = 205080, sampleRate = 48000, numChannels = 2
,09-13 12:58:24.766  6308  6308 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-13 12:58:24.767  6308  6308 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-13 12:58:24.769  6308  6308 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6591
09-13 12:58:24.932  1032  1094 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-13 12:58:24.938  1032  1094 D Tethering: InitialState.processMessage what=4
09-13 12:58:24.939  1032  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-13 12:58:24.940  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 12:58:24.940  6285  6285 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 12:58:24.940  6285  6285 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 12:58:24.940  6285  6285 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 12:58:24.940  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 12:58:24.942  6285  6285 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 12:58:24.942  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-13 12:58:24.942  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 12:58:24.942  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 12:58:24.942  6285  6285 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 12:58:24.942  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-13 12:58:24.942  6285  6285 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 12:58:24.944  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 12:58:24.944  6285  6285 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 12:58:24.944  6285  6285 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 12:58:24.944  6285  6285 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 12:58:24.944  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 12:58:24.945  6285  6285 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 12:58:24.945  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 12:58:24.945  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 12:58:24.945  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 12:58:24.945  6285  6285 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 12:58:24.945  6285  6285 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 12:58:24.952   308   890 D SoftapController: Softap fwReload - Ok
,09-13 12:58:24.953  1032  1390 E NetdConnector: NDC Command {37 softap fwreload wlan0 STA} took too long (679ms)
09-13 12:58:24.956   308   890 D CommandListener: Setting iface cfg
09-13 12:58:24.956   308   890 D CommandListener: Trying to bring down wlan0
09-13 12:58:24.957   308   890 D CommandListener: Clearing all IP addresses on wlan0
09-13 12:58:24.958  1032  1390 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-13 12:58:24.959  1032  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 12:58:24.959  1032  1390 E WifiStateMachine: useWiFiOffloading() : false
09-13 12:58:24.959  1032  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 12:58:24.955  6388  6388 W wpa_supplicant: type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 12:58:24.955  6388  6388 W wpa_supplicant: type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 12:58:24.960  1032  1390 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-13 12:58:24.955  6388  6388 W wpa_supplicant: type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 12:58:24.955  6388  6388 W wpa_supplicant: type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 12:58:24.960  1032  1390 D WifiMonitor: connecting to supplicant
09-13 12:58:24.960  1032  1390 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
09-13 12:58:24.962  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:24.965  1936  1936 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-13 12:58:24.971  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:24.973  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:24.973  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-13 12:58:24.974  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:24.975  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:24.980  6263  6263 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 12:58:24.982  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 12:58:24.986  6388  6388 I wpa_supplicant: Successfully initialized wpa_supplicant
09-13 12:58:24.987  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:24.993  6333  6391 V FormManager: Network unavailable.
,09-13 12:58:24.998  6333  6390 W FormManager: Network not available. Please check & try again.
09-13 12:58:24.999  6333  6391 V FormManager: Network unavailable.
09-13 12:58:25.017  6388  6388 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-13 12:58:25.017  6388  6388 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-13 12:58:25.048  6039  6039 I UEI.SmartControl: Supports setup maps: true
,09-13 12:58:25.051  6039  6039 D UEI.SmartControl: QS start statue = true Error code = 0
09-13 12:58:25.051  6039  6039 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-13 12:58:25.051  6039  6039 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-13 12:58:25.051  6039  6039 I UEI.SmartControl: ### init IR Blaster...
09-13 12:58:25.055  6039  6039 D serial_port: Configuring serial port
09-13 12:58:25.055  6039  6039 E UEI.SmartControl: UEIBLaster setting for 616
09-13 12:58:25.055  6039  6039 I UEI.SmartControl: Setting serial record hearder size = 2
09-13 12:58:25.055  6039  6039 I UEI.SmartControl: configuring settings for MAXQ616
09-13 12:58:25.055  6039  6039 I UEI.SmartControl: Get version...
09-13 12:58:25.071  6039  6392 D UEI.SmartControl: serial port data available: 21
,09-13 12:58:25.097  6039  6039 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-13 12:58:25.097  6039  6039 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-13 12:58:25.097  6039  6039 I UEI.SmartControl: QS saving settings...
,09-13 12:58:25.100  6039  6039 D UEI.SmartControl: IR Blaster version: 25672567
09-13 12:58:25.108  6388  6388 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-13 12:58:25.120  6039  6392 D UEI.SmartControl: serial port data available: 4
,09-13 12:58:25.132  6388  6388 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-13 12:58:25.148  6388  6388 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,09-13 12:58:25.151  6039  6395 I UEI.SmartControl: Device manager: loading config....
,09-13 12:58:25.152  6039  6039 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-13 12:58:25.152  6039  6395 D UEI.SmartControl: ----------- loading internal config...
09-13 12:58:25.152  6388  6388 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-13 12:58:25.154  6039  6039 E UEI.SmartControl: Services init done
09-13 12:58:25.154  6039  6039 D UEI.SmartControl: QS Service init finished
09-13 12:58:25.155  6039  6039 D UEI.SmartControl: QS Service version name: 2.1.91
09-13 12:58:25.155  6039  6039 D UEI.SmartControl: QS Service version code: 201091
09-13 12:58:25.156  6039  6039 D UEI.SmartControl: Service requested: Control
09-13 12:58:25.162  6039  6395 E UEI.SmartControl: Loading SETTINGS...
,09-13 12:58:25.166  6039  6039 D UEI.SmartControl: Request IControl service: devices are loaded...
09-13 12:58:25.168  6039  6039 D UEI.SmartControl: Internal service binding...
09-13 12:58:25.170  6308  6308 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-13 12:58:25.171  6039  6054 I UEI.SmartControl: ------ IControl API: 11
09-13 12:58:25.171  6039  6054 D UEI.SmartControl: File observer start...
09-13 12:58:25.173  6039  6054 E UEI.SmartControl: IR Port is disabled: false
09-13 12:58:25.173  6039  6054 D UEI.SmartControl: Starting file observer...
09-13 12:58:25.173  6039  6395 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-13 12:58:25.174  6039  6054 I UEI.SmartControl: Registering callback...
,09-13 12:58:25.175  6039  6055 I UEI.SmartControl: ------ IControl API: 19
09-13 12:58:25.177  6039  6055 I UEI.SmartControl: Registering Services Ready callback...
09-13 12:58:25.189  6039  6394 I UEI.SmartControl: Notify AllClients services are ready: 0
09-13 12:58:25.189  6039  6394 D UEI.SmartControl: -----service ready thread exits
09-13 12:58:25.190  6308  6324 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-13 12:58:25.190  6308  6362 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
,09-13 12:58:25.190  6308  6362 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-13 12:58:25.191  6308  6308 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-13 12:58:25.191  6308  6308 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-13 12:58:25.192  6039  6054 I UEI.SmartControl: ------ IControl API: 8
09-13 12:58:25.193  6308  6308 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-13 12:58:25.194  6308  6308 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-13 12:58:25.194  6308  6308 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-13 12:58:25.195  6308  6308 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-13 12:58:25.196  6308  6308 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-13 12:58:25.196  6308  6308 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-13 12:58:25.198  6308  6308 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-13 12:58:25.201  6308  6308 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-13 12:58:25.203  6308  6308 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-13 12:58:25.204  6308  6308 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-13 12:58:25.204  6308  6308 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-13 12:58:25.205  6308  6308 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,09-13 12:58:25.207  6308  6308 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-13 12:58:25.207  6308  6308 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-13 12:58:25.210  6308  6308 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473764305209]
09-13 12:58:25.213  6308  6308 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-13 12:58:25.217  1032  2027 I ActivityManager: Killing 5736:com.lge.appbox.client/u0a11 (adj 15): empty #17
,09-13 12:58:25.249  6308  6397 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-13 12:58:25.311  1032  1572 W libprocessgroup: failed to open /acct/uid_10011/pid_5736/cgroup.procs: No such file or directory
,09-13 12:58:25.314  6308  6308 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
09-13 12:58:25.317  1032  1989 D WifiServiceImplEx: setWifiEnabled: true pid=6160, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 12:58:25.318  6308  6308 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-13 12:58:25.319  1032  1989 D WifiService: setWifiEnabled: true pid=6160, uid=10118
09-13 12:58:25.319  1032  1989 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 12:58:25.320  6308  6308 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-13 12:58:25.322  6308  6308 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-13 12:58:25.323  6308  6308 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
,09-13 12:58:25.324  6308  6308 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-13 12:58:25.325  6308  6308 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-13 12:58:25.340  6308  6308 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-13 12:58:25.831  1032  1900 D WifiServiceImplEx: setWifiEnabled: true pid=6160, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-13 12:58:25.839  1032  1900 D WifiService: setWifiEnabled: true pid=6160, uid=10118
09-13 12:58:25.839  1032  1900 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 12:58:25.970  1032  1390 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,09-13 12:58:25.977  1032  1390 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-13 12:58:25.978  1032  1390 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-13 12:58:25.980  1032  1390 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-13 12:58:25.985  1032  1390 E WifiStateMachine:  SupplicantStartingState CMD_START_SUPPLICANT 0 0
,09-13 12:58:25.987  1032  1390 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-13 12:58:25.988  1032  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 12:58:25.988  1032  1390 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-13 12:58:25.989  1032  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 12:58:25.989  1032  1390 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-13 12:58:25.989  1032  1390 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-13 12:58:25.990  1032  1390 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-13 12:58:25.990  1032  1390 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-13 12:58:25.990  1032  1390 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-13 12:58:25.992  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:25.992  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:25.992  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:25.992  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:25.992  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 12:58:25.993  1032  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 12:58:25.993  1032  1390 E WifiStateMachine: useWiFiOffloading() : false
09-13 12:58:25.993  1032  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 12:58:25.999  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 12:58:26.003  1936  1936 D WfdService: Waiting for WifiP2p enabling
09-13 12:58:26.009  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:26.009  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:26.009  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:26.009  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:26.009  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:26.009  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:26.009  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:26.009  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:26.011  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:58:26.015  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:26.015  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:26.015  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:26.015  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:26.015  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:26.015  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:26.015  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:26.015  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 12:58:26.018  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:58:26.021  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:26.021  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:26.021  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:26.021  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:26.021  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:26.021  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:26.021  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:26.021  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:26.023  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:58:26.026  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:26.026  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:26.026  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:26.026  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:26.026  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:26.026  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:26.026  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:26.026  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 12:58:26.029  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:58:26.036  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-13 12:58:26.037  1032  1439 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,09-13 12:58:26.040  1032  1390 D WifiNative-wlan0: doBoolean: SET update_config 1
09-13 12:58:26.040  1032  1390 D WifiNative-wlan0: SET update_config 1: returned true
09-13 12:58:26.040  1032  1390 D WifiConfigStore: Loading config and enabling all networks 
09-13 12:58:26.040  1032  1390 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-13 12:58:26.049  1032  1390 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,09-13 12:58:26.058  1032  1390 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-13 12:58:26.067  1032  1390 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-13 12:58:26.067  1032  1390 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-13 12:58:26.072  1032  1390 D WifiStateMachine: enableVerboseLogging : level 2
09-13 12:58:26.072  1032  1390 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-13 12:58:26.072  1032  1390 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-13 12:58:26.072  1032  1390 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-13 12:58:26.073  1032  1390 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-13 12:58:26.073  1032  1390 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-13 12:58:26.073  1032  1390 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-13 12:58:26.073  1032  1390 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-13 12:58:26.074  1032  1390 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-13 12:58:26.074  1032  1390 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-13 12:58:26.074  1032  1390 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-13 12:58:26.074  1032  1390 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-13 12:58:26.075  1032  1390 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-13 12:58:26.075  1032  1390 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-13 12:58:26.075  1032  1390 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-13 12:58:26.076  1032  1390 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 12:58:26.076  1032  1390 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-13 12:58:26.078  1032  1390 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-13 12:58:26.078  1032  1390 D WifiNative-HAL: Setting external_sim to 1
09-13 12:58:26.078  1032  1390 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-13 12:58:26.079  1032  1390 D WifiNative-wlan0: SET external_sim 1: returned true
09-13 12:58:26.079  1032  1390 I WifiNative-HAL: startHal
09-13 12:58:26.079  1032  1390 D wifi    : setting scan oui 0xaf73c7a0
09-13 12:58:26.080  1032  1390 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 12:58:26.080  1032  1390 I WifiNative-HAL: startHal
09-13 12:58:26.081  1032  1390 D wifi    : setting scan oui 0xaf73c7a0
09-13 12:58:26.081  1032  1390 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
,09-13 12:58:26.085  1032  1390 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-13 12:58:26.085  1032  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-13 12:58:26.085  6388  6388 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-13 12:58:26.086  1032  1390 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-13 12:58:26.086  1032  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 12:58:26.086  6388  6388 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-13 12:58:26.087  1032  1390 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 12:58:26.087  1032  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-13 12:58:26.087  6388  6388 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-13 12:58:26.087  1032  1390 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-13 12:58:26.087  1032  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 12:58:26.087  6388  6388 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 12:58:26.088  1032  1390 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-13 12:58:26.088  1032  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 12:58:26.088  6388  6388 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-13 12:58:26.088  1032  1390 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 12:58:26.088  1032  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-13 12:58:26.088  6388  6388 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-13 12:58:26.089  1032  1390 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-13 12:58:26.089  1032  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 12:58:26.089  6388  6388 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 12:58:26.089  1032  1390 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-13 12:58:26.091  1032  1390 E WifiNative: : [199,185,726 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-13 12:58:26.091  1032  1390 D WifiNative-wlan0: doBoolean: RECONNECT
09-13 12:58:26.091  1032  1390 D WifiNative-wlan0: RECONNECT: returned true
09-13 12:58:26.091  1032  1390 D WifiNative-wlan0: doString: [STATUS]
09-13 12:58:26.092  1032  6407 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-13 12:58:26.092  1032  6407 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-13 12:58:26.092  1032  1390 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-13 12:58:26.092  1032  1390 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 12:58:26.094  1032  1390 D WifiNative-wlan0: SET ps 1: returned true
,09-13 12:58:26.097  1032  1387 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:26.099   308   890 D CommandListener: Setting iface cfg
09-13 12:58:26.099   308   890 D CommandListener: Trying to bring up p2p0
09-13 12:58:26.099  1032  1387 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-13 12:58:26.099  1032  1387 D LGWifiP2pService: P2pEnablingState
09-13 12:58:26.099  1032  1387 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:26.099  1032  1387 D LGWifiP2pService: P2p socket connection successful
09-13 12:58:26.099  1032  1387 D LGWifiP2pService: P2pEnabledState
09-13 12:58:26.101  1936  1936 D WfdsService: Supplicant Connection state is changed : true
09-13 12:58:26.101  1936  2261 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-13 12:58:26.101  1936  2261 D WfdsService: Set the WFDS Monitor: true
09-13 12:58:26.102  1936  2261 D WfdsMonitor: WfdsMonitorThread create
09-13 12:58:26.102  1936  2261 D WfdsMonitor: WFDS Monitor is created and started
09-13 12:58:26.102  1936  2261 D WfdsService: WiFi: Supplicant connection re-established
09-13 12:58:26.102  1032  1387 D LGWifiP2pService: sending p2p connection changed broadcast
09-13 12:58:26.103  1032  1387 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-13 12:58:26.104  1032  1390 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-13 12:58:26.105  1032  1390 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-13 12:58:26.105  1032  1390 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-13 12:58:26.108  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 3
,09-13 12:58:26.111  1032  1032 D RttService: SCAN_AVAILABLE : 3
09-13 12:58:26.112  1032  1552 D WifiScanningService: DefaultState got{ when=-3ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:26.112  1032  1552 I WifiNative-HAL: startHal
09-13 12:58:26.112  1032  1553 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:26.112  1936  1936 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-13 12:58:26.115  1936  1936 D WfdsService: WifiP2pState is changed : true
09-13 12:58:26.115  1936  2261 D WfdsService: Receive the WFDS_ENABLE Method
09-13 12:58:26.115  1936  2261 D WfdsService: Set the WFDS Monitor: true
09-13 12:58:26.115  1936  2261 D WfdsService: Connected to the supplicant for wfds
09-13 12:58:26.115  1936  2261 D WfdsJNI : doCommand: WFDS_SET TRUE
09-13 12:58:26.115  1936  2261 E CtrlSupplicant: Not connected to wap_supplicant - "WFDS_SET TRUE" command dropped.
09-13 12:58:26.115  1936  2261 D WfdsJNI : wfds_send_command: [WFDS_SET TRUE] failed
09-13 12:58:26.115  1936  2261 D WfdsService: selectPreferredScanChannel [36]
09-13 12:58:26.116  1936  2261 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-13 12:58:26.116  1936  1936 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-13 12:58:26.117  1936  1936 D WfdsService: isConnected: false
09-13 12:58:26.118  1032  1387 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-13 12:58:26.119  1032  1387 D WifiNative-p2p0: doBoolean: SET device_name G3
09-13 12:58:26.123  1032  1387 D WifiNative-p2p0: SET device_name G3: returned true
,09-13 12:58:26.125  1032  1552 D wifi    : getting scan capabilities on interface[1] = 0xaf73c7a0
09-13 12:58:26.125  1032  1552 D wifi    : failed to get capabilities : -3
09-13 12:58:26.125  1032  1552 E WifiScanningService: could not get scan capabilities
09-13 12:58:26.125  1032  1387 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-13 12:58:26.125  1032  1387 D LGWifiP2pService: before postfix = G3
09-13 12:58:26.125  1032  1387 D WifiServerServiceExt: postfix byte check : 2
09-13 12:58:26.125  1032  1387 D LGWifiP2pService: after postfix = G3
09-13 12:58:26.125  1032  1387 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-13 12:58:26.126  1032  1390 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-13 12:58:26.127  1032  1390 E WifiStateMachine:  DisconnectedState CMD_START_SUPPLICANT 0 0
09-13 12:58:26.127  1032  1390 E WifiStateMachine:  ConnectModeState CMD_START_SUPPLICANT 0 0
09-13 12:58:26.127  1032  1390 E WifiStateMachine:  DriverStartedState CMD_START_SUPPLICANT 0 0
09-13 12:58:26.128  1032  1390 E WifiStateMachine:  SupplicantStartedState CMD_START_SUPPLICANT 0 0
09-13 12:58:26.128  1032  1390 E WifiStateMachine:  DefaultState CMD_START_SUPPLICANT 0 0
09-13 12:58:26.128  1032  1390 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-13 12:58:26.129  1032  1390 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-13 12:58:26.129  1032  1390 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-13 12:58:26.129  1032  1390 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-13 12:58:26.129  6388  6388 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-13 12:58:26.130  1032  1387 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-13 12:58:26.130  1032  1387 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-13 12:58:26.138  1032  1387 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-13 12:58:26.138  1032  1387 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-13 12:58:26.139  1936  6408 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
,09-13 12:58:26.139  1032  1390 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-13 12:58:26.139  1936  6408 E CtrlSupplicant: Succeed to open control connection
,09-13 12:58:26.139  1936  6408 E CtrlSupplicant: Succeed to open monitor connection
09-13 12:58:26.140  1936  6408 D WfdsMonitor: Supplicant connection established
09-13 12:58:26.140  1032  1390 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-13 12:58:26.140  1936  2261 D WfdsService: Received the Event that WfdsMonitor is connected to supplicant
09-13 12:58:26.141  1032  1387 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-13 12:58:26.141  1032  1387 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-13 12:58:26.141  1032  1387 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-13 12:58:26.141  1032  1387 D WifiNative-HAL: p2pGetDeviceAddress
09-13 12:58:26.142  1032  1387 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-13 12:58:26.142  1032  1390 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-13 12:58:26.142  1032  1387 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-13 12:58:26.142  1032  1387 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-13 12:58:26.142  1032  1390 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-13 12:58:26.142  6388  6388 E wpa_supplicant: disconnect_rssi_lvl: -100
09-13 12:58:26.143  1032  1387 D WifiNative-p2p0: P2P_FLUSH: returned true
09-13 12:58:26.143  1032  1387 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-13 12:58:26.143  1032  1387 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-13 12:58:26.143  1032  1387 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-13 12:58:26.144  1032  1387 D WifiNative-p2p0:    returned OK
09-13 12:58:26.144  1936  1936 I WfdStateTracker: handleP2pThisDeviceChanged
09-13 12:58:26.144  1032  1387 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-13 12:58:26.144  1936  1936 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-13 12:58:26.144  1936  1936 D WfdsService: Update P2p Interface State: 3
09-13 12:58:26.145  1032  1390 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-13 12:58:26.147  1032  1390 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-13 12:58:26.148  1032  1390 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-13 12:58:26.148  1032  1390 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-13 12:58:26.149  6263  6263 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 12:58:26.154  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-13 12:58:26.162  6333  6423 V FormManager: Network unavailable.
09-13 12:58:26.162  6333  6422 W FormManager: Network not available. Please check & try again.
,09-13 12:58:26.162  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:26.165  1032  1387 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-13 12:58:26.165  1032  1387 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-13 12:58:26.165  6388  6388 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 12:58:26.166  6388  6388 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 12:58:26.166  6388  6388 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 12:58:26.167  6388  6388 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:26.167  1032  1390 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-13 12:58:26.167  6388  6388 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:26.168  1032  1390 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-13 12:58:26.168  1032  1390 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-13 12:58:26.168  1936  6408 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 12:58:26.168  1032  1390 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-13 12:58:26.168  1936  6408 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 12:58:26.168  1032  1390 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-13 12:58:26.169  6388  6388 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-13 12:58:26.169  6388  6388 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 12:58:26.169  1032  1387 D LGWifiP2pService: InactiveState
09-13 12:58:26.169  1032  1387 D LGWifiP2pService: InactiveState{ when=-26ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:26.169  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=-26ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:26.169  1032  1387 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-13 12:58:26.169  1032  1390 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-13 12:58:26.170  1032  1390 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
,09-13 12:58:26.170  1032  6407 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 12:58:26.170  1032  6407 E WifiMonitor: WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 12:58:26.170  1032  6407 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 12:58:26.170  1032  6407 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 12:58:26.170  1032  6407 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 12:58:26.170  1032  6407 E WifiMonitor: WifiMonitor:p2p0 cnt=16 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:26.170  1032  6407 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:26.170  1032  6407 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:26.170  1032  6407 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 12:58:26.170  1032  6407 E WifiMonitor: WifiMonitor:p2p0 cnt=17 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:26.170  1032  6407 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:26.170  1032  6407 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:26.171  1032  6407 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-13 12:58:26.171  1032  6407 E WifiMonitor: WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 12:58:26.171  1032  6407 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 12:58:26.171  1032  6407 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 12:58:26.172  1032  1390 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-13 12:58:26.172  1032  1390 D WifiNative-wlan0: doBoolean: SCAN
09-13 12:58:26.172  1032  1390 D WifiNative-wlan0: SCAN: returned false
09-13 12:58:26.173  1032  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=199268  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,09-13 12:58:26.175  6333  6423 V FormManager: Network unavailable.
09-13 12:58:26.176  6388  6388 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 12:58:26.176  6388  6388 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 12:58:26.176  1032  6407 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 12:58:26.176  1032  6407 E WifiMonitor: WifiMonitor:p2p0 cnt=19 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 12:58:26.176  1032  6407 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 12:58:26.176  1032  6407 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 12:58:26.176  1936  6408 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 12:58:26.177  6388  6388 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 12:58:26.177  6388  6388 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:26.177  6388  6388 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:26.178  1032  1387 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-13 12:58:26.178  1032  1387 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:26.179  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:26.179  1032  1387 D LGWifiP2pService: InactiveState{ when=-9ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:26.179  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:26.179  1032  1387 D LGWifiP2pService: DefaultState{ when=-9ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:26.179  1032  1387 D LGWifiP2pService: InactiveState{ when=-10ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:26.179  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 12:58:26.179  1032  1387 D LGWifiP2pService: DefaultState{ when=-10ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:26.179  1032  1387 D LGWifiP2pService: InactiveState{ when=-10ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:26.179  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:26.179  1032  1387 D LGWifiP2pService: DefaultState{ when=-10ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:26.179  1032  1387 D LGWifiP2pService: InactiveState{ when=-10ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:26.179  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:26.179  1032  1387 D LGWifiP2pService: DefaultState{ when=-10ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:26.180  1032  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=199275  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 12:58:26.181  1936  2261 W WfdsService: DefaultState - msg [9441285] is not handled
09-13 12:58:26.181  1936  6408 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 12:58:26.181  1936  6408 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 12:58:26.181  1032  6407 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 12:58:26.181  1032  6407 E WifiMonitor: WifiMonitor:p2p0 cnt=20 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:26.182  1032  6407 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:26.182  1032  6407 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:26.182  1032  6407 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 12:58:26.182  1032  6407 E WifiMonitor: WifiMonitor:p2p0 cnt=21 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:26.182  1032  6407 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:26.182  1032  6407 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:26.182  1032  1390 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 12:58:26.182  1032  1390 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 12:58:26.183  1032  1390 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 12:58:26.183  1032  1390 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 12:58:26.183  1032  1390 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,09-13 12:58:26.184  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 12:58:26.184  1032  1032 E WifiServerServiceExt: No p2p device connected
09-13 12:58:26.185  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:26.185  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:26.185  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 12:58:26.185  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 12:58:26.186  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:26.188  4265  4265 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 12:58:26.188  4265  4265 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 12:58:26.190  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 12:58:26.190  1032  1032 D WifiServerServiceExt: setSupplicantStateSCANNING
09-13 12:58:26.191  4265  4265 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 12:58:26.193  4265  4265 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 12:58:26.196  5069  5069 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-13 12:58:26.196  5069  5069 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-13 12:58:26.198  5069  5069 V [BNRBootReceiver]: Boot Receiver Return
09-13 12:58:26.199  4265  6428 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 12:58:26.202  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 12:58:26.202  4265  6429 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 12:58:26.202  4265  6429 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 12:58:26.208  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 12:58:26.213  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 12:58:26.217  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 12:58:26.218  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 12:58:26.219  6308  6308 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 12:58:26.347  6160  6328 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:58:26.359  1032  1935 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 12:58:26.360  1032  1935 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@27ef67df mBinding = false
,09-13 12:58:26.389  1032  1094 D BluetoothManagerService: Message: 2
09-13 12:58:26.391  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 12:58:26.391  1032  1094 D BluetoothManagerService: Sending off request.
09-13 12:58:26.392  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 12:58:26.392  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-13 12:58:26.393  3826  3942 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-13 12:58:26.394  3826  3904 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-13 12:58:26.394  3826  3904 D BluetoothAdapterProperties: Setting state to 13
09-13 12:58:26.395  3826  3904 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 12:58:26.396  1032  1094 D BluetoothManagerService: Message: 60
09-13 12:58:26.396  3826  3904 D BluetoothAdapterProperties: onBluetoothDisable()
09-13 12:58:26.396  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-13 12:58:26.396  3826  3904 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-13 12:58:26.397  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,09-13 12:58:26.407  3826  3826 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-13 12:58:26.408  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 12:58:26.408  3826  3826 D BluetoothMapService: STATE_TURNING_OFF
09-13 12:58:26.409  3826  3826 V BtOppService: Receiver DISABLED_ACTION 
09-13 12:58:26.409  3826  3826 V BluetoothMapService: Handler(): got msg=4
09-13 12:58:26.409  3826  3826 D BluetoothMapService: MAP Service closeService in
09-13 12:58:26.409  3826  3826 D BluetoothMapMasInstance: MAP Service shutdown
,09-13 12:58:26.412  3826  4197 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-13 12:58:26.412  3826  4197 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 12:58:26.412  3826  4197 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-13 12:58:26.412  3826  4197 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-13 12:58:26.412  3826  4197 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-13 12:58:26.412  3826  4197 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-13 12:58:26.412  3826  4197 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-13 12:58:26.412  3826  4197 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-13 12:58:26.413  3826  3826 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 12:58:26.413  3826  3826 V BluetoothMapService: MAP Service closeService out
09-13 12:58:26.413  3826  3826 I BtOppRfcommListener: stopping Accept Thread
09-13 12:58:26.413  3826  3826 V BtOppRfcommListener: close mBtServerSocket
09-13 12:58:26.414  3826  3826 V BtOppRfcommListener: waiting for thread to terminate
09-13 12:58:26.414  1936  1936 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:26.414  3826  4252 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 12:58:26.415  3826  4252 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-13 12:58:26.415  3826  3826 V BtOppRfcommListener: done waiting for thread to terminate
09-13 12:58:26.416  6160  6160 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:58:26.416  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:26.416  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:26.416  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:26.416  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:26.416  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 12:58:26.416  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:26.416  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:26.416  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:26.417  6160  6160 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 12:58:26.418  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 12:58:26.424  3826  3907 D BluetoothAdapterProperties: Scan Mode:20
09-13 12:58:26.425  3826  3826 V BtOppService: onDestroy
09-13 12:58:26.425  3826  3904 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-13 12:58:26.426  3826  4253 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 12:58:26.426  3826  3904 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-13 12:58:26.426  6160  6160 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:58:26.427  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:26.427  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:26.427  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:26.427  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:26.427  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 12:58:26.427  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:26.427  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:26.427  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:26.427  3826  4014 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-13 12:58:26.428  6160  6240 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 794)
09-13 12:58:26.428  3826  4198 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 12:58:26.428  3826  4014 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-13 12:58:26.430  6160  6160 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:58:26.430  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 12:58:26.431  3826  4257 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 12:58:26.434  6160  6160 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:58:26.434  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:26.434  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:26.434  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:26.434  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:26.434  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 12:58:26.434  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:26.434  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:26.434  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:26.435  6160  6160 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:58:26.435  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:58:26.436  3826  4014 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 12:58:26.436  3826  4014 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 12:58:26.436  3826  4014 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 12:58:26.436  3826  4014 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 12:58:26.436  3826  4014 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 12:58:26.436  3826  4014 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 12:58:26.436  3826  4014 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 12:58:26.436  3826  4014 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 12:58:26.436  3826  4014 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 12:58:26.436  3826  4014 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-13 12:58:26.437  3826  4014 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
,09-13 12:58:26.437  6160  6160 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:58:26.437  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:26.437  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:26.437  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:26.437  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:26.437  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 12:58:26.437  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:26.437  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:26.437  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:26.437  3826  4014 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-13 12:58:26.438  6160  6160 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:58:26.438  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:58:26.439  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:26.440  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:26.442  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:26.444  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:26.449  6285  6285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-13 12:58:26.474  6388  6388 E wpa_supplicant: USIM:  scard_init function
,09-13 12:58:26.474  6388  6388 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-13 12:58:26.477  1032  6407 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-13 12:58:26.477  1032  6407 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-13 12:58:26.477  1032  6407 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-13 12:58:26.477  1032  6407 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: WPS-AP-AVAILABLE 
09-13 12:58:26.477  1032  6407 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-13 12:58:26.477  1032  6407 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-13 12:58:26.478  1032  6407 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-13 12:58:26.478  1032  1390 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-13 12:58:26.478  1032  1390 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-13 12:58:26.478  1032  1390 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-13 12:58:26.479  1032  1390 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
09-13 12:58:26.479  1032  1390 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-13 12:58:26.490  1032  1089 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6434 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-13 12:58:26.491  3826  3826 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,09-13 12:58:26.494  1032  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=199589  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-13 12:58:26.496  3826  3826 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 12:58:26.496  3826  3826 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:26.496  3826  3826 V BluetoothPbapReceiver: ***********state = 13
09-13 12:58:26.497  3826  3826 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-13 12:58:26.498  1032  1094 D BluetoothManagerService: Message: 20
09-13 12:58:26.498  1032  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b735c8a:true
09-13 12:58:26.500  3826  3826 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:26.500  3826  3826 V BluetoothPbapService: state: 13
09-13 12:58:26.500  3826  3826 V BluetoothPbapService: Pbap Service closeService in
09-13 12:58:26.501  2180  2180 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 12:58:26.503  3826  3826 V BluetoothPbapService: successfully stopped pbap service
09-13 12:58:26.503  3826  3826 V BluetoothPbapService: Pbap Service closeService out
09-13 12:58:26.503  3826  3826 V BluetoothPbapService: Pbap Service onDestroy
09-13 12:58:26.503  3826  3826 V BluetoothPbapService: Pbap Service closeService in
09-13 12:58:26.503  3826  3826 V BluetoothPbapService: Pbap Service closeService out
09-13 12:58:26.503  3826  3826 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-13 12:58:26.504  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:26.504  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:26.504  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 12:58:26.505  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 12:58:26.505  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 12:58:26.507  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:26.507  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:26.507  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-13 12:58:26.507  1032  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=199602  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-13 12:58:26.507  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:26.508  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 12:58:26.508  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-13 12:58:26.510  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 12:58:26.510  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 12:58:26.510  1032  1094 D BluetoothManagerService: Message: 30
09-13 12:58:26.511  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:26.514  1032  1094 D BluetoothManagerService: Message: 30
,09-13 12:58:26.516  6285  6285 D LocalBluetoothProfileManager: Adding local MAP profile
09-13 12:58:26.517  6285  6285 D BluetoothMap: Create BluetoothMap proxy object
09-13 12:58:26.518  1032  1094 D BluetoothManagerService: Message: 30
09-13 12:58:26.520  1032  1094 D BluetoothManagerService: Message: 30
09-13 12:58:26.522  6285  6285 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-13 12:58:26.522  6285  6285 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,09-13 12:58:26.533  6285  6285 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
09-13 12:58:26.535  6285  6285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-13 12:58:26.541  6285  6285 D DockEventReceiver: finishStartingService: stopping service
,09-13 12:58:26.541  6285  6285 D BluetoothInputDevice: Proxy object connected
,09-13 12:58:26.542  6285  6285 D HidProfile: Bluetooth service connected
09-13 12:58:26.543  6285  6285 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 12:58:26.544  6285  6285 D PanProfile: Bluetooth service connected
09-13 12:58:26.544  6285  6285 D BluetoothMap: Proxy object connected
09-13 12:58:26.545  6285  6285 D MapProfile: Bluetooth service connected
09-13 12:58:26.545  6285  6285 D BluetoothMap: getConnectedDevices()
09-13 12:58:26.549  6285  6285 D BluetoothMap: Bluetooth is Not enabled
09-13 12:58:26.549  6285  6285 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-13 12:58:26.575  6434  6434 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-13 12:58:26.575  6434  6434 W LG Account v2.2: No ProfileInfo entries
09-13 12:58:26.575  6434  6434 I LG Account v2.2: isEnabled: false
09-13 12:58:26.576  6434  6434 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-13 12:58:26.576  6434  6434 I Feature : [Lifetracker]Country: EU
09-13 12:58:26.576  6434  6434 I Feature : [Lifetracker]Operator: OPEN
09-13 12:58:26.576  6434  6434 I Feature : [Lifetracker]Ranking support: false
09-13 12:58:26.576  6434  6434 I Feature : [Lifetracker]Comfort support: false
09-13 12:58:26.576  6434  6434 I Feature : [Lifetracker]Accessory: true
09-13 12:58:26.576  6434  6434 I Feature : [Lifetracker]Health device: true
09-13 12:58:26.576  6434  6434 I Feature : [Lifetracker]Extra Pedometer: false
09-13 12:58:26.576  6434  6434 I Feature : [Lifetracker]Blood glucose device: false
09-13 12:58:26.576  6434  6434 I Feature : [Lifetracker]Device Number: 3
,09-13 12:58:26.579  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-13 12:58:26.580  6285  6285 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-13 12:58:26.581  6285  6285 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-13 12:58:26.584  6285  6285 D BluetoothPermissionRequest: onReceive
09-13 12:58:26.585  6285  6285 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-13 12:58:26.589  1032  1900 I ActivityManager: Killing 5757:com.android.contacts/u0a19 (adj 15): empty #17
09-13 12:58:26.591  6285  6285 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 12:58:26.627  3826  3826 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-13 12:58:26.627  3826  3826 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-13 12:58:26.627  3826  3826 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,09-13 12:58:26.629  1032  2027 W libprocessgroup: failed to open /acct/uid_10019/pid_5757/cgroup.procs: No such file or directory
09-13 12:58:26.632  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 12:58:26.636  3826  3826 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:26.636  3826  3826 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-13 12:58:26.640  3826  3826 V BluetoothFtpService: Ftp Service onStartCommand
09-13 12:58:26.641  3826  3826 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:26.641  3826  3826 V BluetoothFtpService: Ftp Service closeService
09-13 12:58:26.641  3826  3826 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-13 12:58:26.641  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 12:58:26.647  3826  3826 V BluetoothFtpService: successfully stopped ftp service
09-13 12:58:26.647  3826  3826 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 12:58:26.647  3826  3826 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 12:58:26.647  3826  3826 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 12:58:26.647  3826  3826 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:26.647  3826  3826 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-13 12:58:26.647  3826  3826 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-13 12:58:26.648  3826  3826 V BluetoothFtpService: Ftp Service onDestroy
,09-13 12:58:26.648  3826  3826 V BluetoothFtpService: Ftp Service closeService
09-13 12:58:26.648  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:26.693  1032  2027 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6460 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-13 12:58:26.695  3826  3826 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:26.695  3826  3826 V BluetoothSapService: state: 13
09-13 12:58:26.695  3826  3826 V BluetoothSapService: Stopping SAP server process
09-13 12:58:26.696  3826  3826 V BluetoothSapService: Sap Service closeSapService in
09-13 12:58:26.696  3826  3826 V BluetoothSapService: Close listen Socket : 
09-13 12:58:26.696  3826  3826 V BluetoothSapService: Close rfcomm Socket : 
09-13 12:58:26.696  3826  3826 V BluetoothSapService: Close sapd  Socket : 
09-13 12:58:26.698  3826  3826 V BluetoothSapService: Sap Service closeSapService out
09-13 12:58:26.699  3826  3826 V BluetoothSapService: Sap Service onDestroy
09-13 12:58:26.699  3826  3826 V BluetoothSapService: Sap Service closeSapService in
09-13 12:58:26.699  3826  3826 V BluetoothSapService: Close listen Socket : 
09-13 12:58:26.699  3826  3826 V BluetoothSapService: Close rfcomm Socket : 
09-13 12:58:26.699  3826  3826 V BluetoothSapService: Close sapd  Socket : 
09-13 12:58:26.699  3826  3826 V BluetoothSapService: Sap Service closeSapService out
,09-13 12:58:26.702  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 12:58:26.702  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 12:58:26.704  6308  6308 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 12:58:26.707  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 12:58:26.716  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 12:58:26.731  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:26.741  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 12:58:26.742  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 12:58:26.742  6308  6308 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 12:58:26.759  6460  6460 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-13 12:58:26.775  1032  1771 I ActivityManager: Killing 5793:com.lge.email/u0a23 (adj 15): empty #17
,09-13 12:58:26.815  1032  1954 W libprocessgroup: failed to open /acct/uid_10023/pid_5793/cgroup.procs: No such file or directory
,09-13 12:58:26.895  6160  6430 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:58:26.908  1032  1900 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 12:58:26.909  1032  1900 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@27ef67df mBinding = false
09-13 12:58:26.934  1032  1094 D BluetoothManagerService: Message: 1
09-13 12:58:26.934  1032  1094 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@27ef67df
,09-13 12:58:26.937  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 12:58:26.937  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 12:58:26.938  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-13 12:58:26.938  3826  3845 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-13 12:58:26.939  1032  1094 E BluetoothManagerService: IBluetooth.enable() returned false
09-13 12:58:27.335  3826  3907 D bt_hci_bdroid: cleanup
,09-13 12:58:27.341  3826  4016 I bt_lpm  : LPM is already off!!!
09-13 12:58:27.341  3826  4180 I bt_userial_mct: exiting userial_read_thread
09-13 12:58:27.342  3826  4180 D bt_userial_mct: Leaving userial_evt_read_thread()
09-13 12:58:27.343  3826  4014 W bt-btif : ag scb idx 1 not allocated
09-13 12:58:27.343  3826  4014 E bt-btif : BTA AG is already disabled, ignoring ...
09-13 12:58:27.343  3826  4014 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 12:58:27.343  3826  4014 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 12:58:27.343  3826  4014 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 12:58:27.343  3826  4014 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 12:58:27.343  3826  4014 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 12:58:27.343  3826  4014 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 12:58:27.343  3826  4014 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 12:58:27.343  3826  4014 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 12:58:27.344  3826  4014 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 12:58:27.344  3826  4014 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 12:58:27.344  3826  4014 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 12:58:27.344  3826  4014 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 12:58:27.344  3826  4014 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 12:58:27.344  3826  4014 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 12:58:27.344  3826  4014 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 12:58:27.344  3826  4014 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 12:58:27.344  3826  4014 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 12:58:27.344  3826  4014 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 12:58:27.344  3826  4014 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-13 12:58:27.348  3826  3907 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-13 12:58:27.352  3826  4016 I bt_vendor: hw_epilog_process
,09-13 12:58:27.355  3826  3907 D bt_hci_bdroid: cleanup Finalizing cleanup
09-13 12:58:27.355  3826  3907 D bt_userial_mct: userial_close
09-13 12:58:27.355  3826  3907 E bt_userial_mct: pthread_join() FAILED result:3
09-13 12:58:27.355  3826  3907 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-13 12:58:27.361  3826  3907 D bt_hci_bdroid: set_power 0
09-13 12:58:27.361  3826  3907 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-13 12:58:27.361  3826  3907 I bt_vendor: bluetooth satus is on
09-13 12:58:27.361  3826  3907 I bt_vendor: bt-vendor : resetting BT status
09-13 12:58:27.361  3826  3907 I bt_vendor: Starting hciattach daemon
09-13 12:58:27.361  3826  3907 I bt_vendor: try to set false
09-13 12:58:27.363  3826  3907 I bt_vendor: Starting hciattach daemon
,09-13 12:58:27.365  3826  3907 I bt_vendor: try to set false
09-13 12:58:27.366  3826  3907 I bt_vendor: cleanup
09-13 12:58:27.367  3826  4014 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-13 12:58:27.367  3826  3907 I GKI_LINUX: GKI_exit_task 0 done
09-13 12:58:27.367  3826  3907 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-13 12:58:27.369  3826  3904 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-13 12:58:27.375  3826  3904 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-13 12:58:27.378  3826  3826 D HeadsetService: Received stop request...Stopping profile...
09-13 12:58:27.380  3826  3826 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-13 12:58:27.380  3826  3826 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 12:58:27.380  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:27.380  3826  3941 D HeadsetStateMachine: Exit Disconnected: -1
09-13 12:58:27.383  1032  1032 D BluetoothHeadset: Proxy object disconnected
09-13 12:58:27.383  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-13 12:58:27.384  1847  1847 D BluetoothHeadset: Proxy object disconnected
09-13 12:58:27.384  1847  1847 D BluetoothHeadset: Proxy object disconnected
09-13 12:58:27.385  1847  1847 D BluetoothHeadset: Proxy object disconnected
09-13 12:58:27.388  3826  3826 D A2dpService: Received stop request...Stopping profile...
,09-13 12:58:27.392  3826  3974 D A2dpStateMachine: Exit Disconnected: -1
09-13 12:58:27.393  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-13 12:58:27.395  3826  3826 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-13 12:58:27.395  3826  3826 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 12:58:27.395  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:27.397  3826  3826 D HidService: Received stop request...Stopping profile...
09-13 12:58:27.398  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:27.398  1032  1032 D BluetoothA2dp: Proxy object disconnected
09-13 12:58:27.398  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-13 12:58:27.400  3826  3826 D HealthService: Received stop request...Stopping profile...
09-13 12:58:27.400  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:27.402  3826  3826 D PanService: Received stop request...Stopping profile...
,09-13 12:58:27.405  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:27.407  3826  3826 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 12:58:27.408  3826  3826 D BtGatt.GattService: Received stop request...Stopping profile...
09-13 12:58:27.408  3826  3826 D BtGatt.GattService: stop()
09-13 12:58:27.408  3826  3826 D BtGatt.AdvertiseManager: advertise clients cleared
09-13 12:58:27.409  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:27.410  3826  3826 D BluetoothMapService: Received stop request...Stopping profile...
09-13 12:58:27.410  3826  3826 D BluetoothMapService: stop()
09-13 12:58:27.411  3826  3826 D BluetoothMapEmailAppObserver: deinitObservers()
09-13 12:58:27.412  3826  3826 D BluetoothMapEmailAppObserver: removeReceiver()
09-13 12:58:27.412  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:27.413  3826  3826 D HeadsetStateMachine: Unbinding service...
09-13 12:58:27.415  3826  3826 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 12:58:27.415  3826  3826 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 12:58:27.415  3826  3826 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 12:58:27.415  3826  3826 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 12:58:27.415  3826  3826 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 12:58:27.415  3826  3826 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 12:58:27.415  3826  3826 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-13 12:58:27.415  3826  3826 I BluetoothA2dpServiceJni: cleanupNative
,09-13 12:58:27.419  3826  3975 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-13 12:58:27.419  3826  3826 I GKI_LINUX: GKI_exit_task 2 done
09-13 12:58:27.420  3826  3826 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-13 12:58:27.421  3826  3826 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 12:58:27.421  3826  3826 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 12:58:27.421  3826  3826 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 12:58:27.422  3826  3826 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 12:58:27.422  3826  3826 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 12:58:27.422  3826  3826 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 12:58:27.422  3826  3826 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 12:58:27.424  3826  3826 V BluetoothMapService: Handler(): got msg=4
09-13 12:58:27.424  3826  3826 D BluetoothMapService: MAP Service closeService in
09-13 12:58:27.424  3826  3826 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 12:58:27.424  3826  3826 V BluetoothMapService: MAP Service closeService out
,09-13 12:58:27.425  3826  3904 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-13 12:58:27.425  3826  3904 D BluetoothAdapterProperties: Setting state to 10
09-13 12:58:27.425  3826  3904 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-13 12:58:27.426  1032  1094 D BluetoothManagerService: Message: 60
09-13 12:58:27.426  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-13 12:58:27.426  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-13 12:58:27.426  3826  3904 I BluetoothAdapterState: Entering OffState
09-13 12:58:27.427  6285  6301 D BluetoothMap: onBluetoothStateChange: up=false
09-13 12:58:27.428  3826  3826 D BluetoothMapService: cleanup()
09-13 12:58:27.428  3826  3826 D BluetoothMapService: MAP Service closeService in
09-13 12:58:27.428  3826  3826 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 12:58:27.428  3826  3826 V BluetoothMapService: MAP Service closeService out
,09-13 12:58:27.436  1847  1862 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 12:58:27.437  1032  1771 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 12:58:27.438  1032  1771 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@27ef67df mBinding = false
09-13 12:58:27.438  6285  6300 D BluetoothPan: onBluetoothStateChange on: false
09-13 12:58:27.439  1032  1094 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 12:58:27.439  1847  4356 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 12:58:27.440  6285  6301 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 12:58:27.441  1032  1094 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 12:58:27.443  6285  6300 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 12:58:27.443  1847  1863 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 12:58:27.444  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-13 12:58:27.448  1936  1936 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:27.448  1936  2091 D LGBluetoothAPIService: Message: 2
09-13 12:58:27.449  1936  2091 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2f5220f1 mBinding = false
09-13 12:58:27.449  1936  2091 D LGBluetoothAPIService: Sending unbind request.
09-13 12:58:27.450  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-13 12:58:27.461  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:27.463  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:27.464  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:27.466  3826  3826 D LGBluetoothAPIServer: [BTUI] onUnbind()
09-13 12:58:27.466  3826  3826 D LGBluetoothAPIServer: [BTUI] cleanup() done
,09-13 12:58:27.468  3826  3826 D LGBluetoothAPIServer: [BTUI] onDestroy()
09-13 12:58:27.469  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:27.470  1032  1094 D BluetoothManagerService: Message: 1
09-13 12:58:27.470  1032  1094 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@27ef67df
09-13 12:58:27.473  6285  6285 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-13 12:58:27.474  6285  6285 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-13 12:58:27.474  6285  6285 D LGBluetoothEventManager: [BTUI] clear device connection state
09-13 12:58:27.475  3826  3904 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-13 12:58:27.475  3826  3904 D BluetoothAdapterProperties: Setting state to 11
09-13 12:58:27.475  3826  3904 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-13 12:58:27.476  1032  1094 D BluetoothManagerService: Message: 60
09-13 12:58:27.476  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-13 12:58:27.476  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-13 12:58:27.481  1936  1936 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,09-13 12:58:27.486  3826  3904 D BluetoothBondStateMachine: make
09-13 12:58:27.488  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:27.489  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:27.490  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:27.491  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:27.496  6285  6285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-13 12:58:27.500  3826  3904 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:27.500  3826  3904 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-13 12:58:27.500  3826  3904 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:27.500  3826  3904 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-13 12:58:27.500  3826  3904 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-13 12:58:27.500  3826  6489 I BluetoothBondStateMachine: StableState(): Entering Off State
09-13 12:58:27.505  3826  3904 E BluetoothAdapterService: File transfer profiles supported!!
09-13 12:58:27.511  3826  3826 D HeadsetService: Received start request. Starting profile...
09-13 12:58:27.511  3826  3826 D HeadsetStateMachine: make
,09-13 12:58:27.515  3826  3904 E BluetoothAdapterService: File transfer profiles supported!!
09-13 12:58:27.520  3826  3904 E BluetoothAdapterService: File transfer profiles supported!!
09-13 12:58:27.525  3826  3904 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 12:58:27.539  3826  3904 E BluetoothAdapterService: File transfer profiles supported!!
09-13 12:58:27.539  6388  6388 I wpa_supplicant: wlan0: CTRL-EVENT-ASSOC-REJECT bssid=f4:f2:6d:22:99:3e status_code=1
,09-13 12:58:27.543  1032  6407 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-ASSOC-REJECT bssid=f4:f2:6d:22:99:3e status_code=1]
09-13 12:58:27.543  1032  6407 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-ASSOC-REJECT bssid=f4:f2:6d:22:99:3e status_code=1
09-13 12:58:27.543  1032  6407 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700]
09-13 12:58:27.543  1032  6407 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
09-13 12:58:27.546  1032  1390 E WifiStateMachine:  DisconnectedState ASSOCIATION_REJECTION_EVENT 25 1 f4:f2:6d:22:99:3e blacklist=false rt=200642
09-13 12:58:27.547  3826  3904 E BluetoothAdapterService: File transfer profiles supported!!
09-13 12:58:27.547  1032  1390 E WifiStateMachine:  ConnectModeState ASSOCIATION_REJECTION_EVENT 25 1 f4:f2:6d:22:99:3e blacklist=false rt=200643
09-13 12:58:27.548  6285  6285 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-13 12:58:27.549  1032  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=200644  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: DISCONNECTED
09-13 12:58:27.549  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 12:58:27.551  1032  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=200646  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: DISCONNECTED
09-13 12:58:27.553  3826  3826 D HeadsetStateMachine: max_hf_connections = 1
09-13 12:58:27.553  3826  3826 I bluedroid-qcom: get_profile_interface handsfree
09-13 12:58:27.553  3826  3904 E BluetoothAdapterService: File transfer profiles supported!!
09-13 12:58:27.553  3826  3826 E LGBluetoothDtmfAdapter: LGBluetoothDtmfLocalPlay is not null
09-13 12:58:27.553  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
,09-13 12:58:27.558  1032  1032 D WifiHS20: hidePasspointNotification off =false
09-13 12:58:27.558  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:27.558  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:27.558  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 12:58:27.558  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 12:58:27.558  1032  1032 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-13 12:58:27.559  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:27.559  3826  6490 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-13 12:58:27.559  3826  6490 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 12:58:27.559  3826  6490 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 12:58:27.559  3826  6490 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-13 12:58:27.559   315  1395 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 3826
09-13 12:58:27.560  3826  3826 D A2dpService: Received start request. Starting profile...
09-13 12:58:27.560  3826  3826 V Avrcp   : make
09-13 12:58:27.560  3826  3826 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-13 12:58:27.560  3826  3826 I bluedroid-qcom: get_profile_interface avrcp
09-13 12:58:27.560  3826  3904 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-13 12:58:27.560   315  1395 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-13 12:58:27.561   315  1395 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-13 12:58:27.561   315  1395 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-13 12:58:27.561   315  1395 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-13 12:58:27.561   315  1395 V voice   : voice_set_parameters: exit with code(0)
09-13 12:58:27.561   315  1395 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-13 12:58:27.561   315  1395 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-13 12:58:27.561   315  1395 V msm8974_platform: platform_set_parameters: exit with code(0)
09-13 12:58:27.561   315  1395 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-13 12:58:27.561   315  1395 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-13 12:58:27.561   315  1395 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-13 12:58:27.561  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 12:58:27.563  3826  3826 V AudioManager: registerRemoteController: size of Media player list: 0
09-13 12:58:27.564  3826  3826 E AudioManager: No RCC entry present to update
09-13 12:58:27.564  3826  3826 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-13 12:58:27.565  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-13 12:58:27.565  3826  3826 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-13 12:58:27.568  6263  6263 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 12:58:27.568  6263  6263 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 12:58:27.568  6263  6263 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 12:58:27.568  6285  6285 D DockEventReceiver: finishStartingService: stopping service
09-13 12:58:27.568  3826  3826 D LGBluetoothAvrcpQcomAdapter: ,[BTUI] [+] updateMediaPlayerInfo
,09-13 12:58:27.623  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 12:58:27.624  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-13 12:58:27.626  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 12:58:27.627  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 12:58:27.641  1032  6407 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-13 12:58:27.641  1032  6407 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-13 12:58:27.641  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:27.641  6388  6388 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-13 12:58:27.642  1032  6407 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-13 12:58:27.642  1032  6407 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-13 12:58:27.642  1032  6407 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-13 12:58:27.643  1032  6407 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-13 12:58:27.643  1032  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=200739  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,09-13 12:58:27.651  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 12:58:27.651  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 12:58:27.652  1032  1032 D WifiHS20: hidePasspointNotification off =false
09-13 12:58:27.653  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:27.654  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:27.654  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:27.654  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 12:58:27.661  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 12:58:27.661  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 12:58:27.664  1032  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=200759  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 12:58:27.665  6308  6308 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-13 12:58:27.670  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:27.671  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:27.671  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 12:58:27.672  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 12:58:27.672  1032  1032 D WifiServerServiceExt: setSupplicantStateSCANNING
09-13 12:58:27.673  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 12:58:27.673  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 12:58:27.674  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:27.678  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 12:58:27.683  6263  6263 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 12:58:27.683  1032  1047 V SIM_STK : Menu title from STK is T-Mobile
09-13 12:58:27.683  1032  1047 V SIM_STK : Menu title from STK is T-Mobile
,09-13 12:58:27.683  6263  6263 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 12:58:27.683  6263  6263 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 12:58:27.686  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 12:58:27.695  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:27.701  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 12:58:27.702  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 12:58:27.704  6308  6308 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-13 12:58:27.709  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 12:58:27.717  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 12:58:27.725  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 12:58:27.732  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 12:58:27.732  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 12:58:27.735  6308  6308 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 12:58:27.739  1032  1935 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-13 12:58:27.740  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-13 12:58:27.740  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-13 12:58:27.740  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-13 12:58:27.740  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-13 12:58:27.740  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-13 12:58:27.740  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 12:58:27.740  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-13 12:58:27.740  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-13 12:58:27.740  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-13 12:58:27.740  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 12:58:27.740  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-13 12:58:27.740  3826  3826 D A2dpStateMachine: make
09-13 12:58:27.742  3826  3826 I bluedroid-qcom: get_profile_interface a2dp
09-13 12:58:27.743  3826  6512 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-13 12:58:27.744  3826  3826 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-13 12:58:27.744  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:27.744  3826  6511 D A2dpStateMachine: Enter Disconnected: -2
,09-13 12:58:27.745  3826  3826 D HidService: Received start request. Starting profile...
09-13 12:58:27.745  3826  3826 I bluedroid-qcom: get_profile_interface hidhost
09-13 12:58:27.745  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:27.746  3826  3826 D HealthService: Received start request. Starting profile...
09-13 12:58:27.748  3826  3826 I bluedroid-qcom: get_profile_interface health
09-13 12:58:27.749  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:27.749  3826  3826 D HeadsetStateMachine: Proxy object connected
09-13 12:58:27.749  3826  3826 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-13 12:58:27.749  3826  3826 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-13 12:58:27.750  3826  3826 D PanService: Received start request. Starting profile...
09-13 12:58:27.750  3826  3826 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 12:58:27.750  3826  3826 I bluedroid-qcom: get_profile_interface pan
09-13 12:58:27.751  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:27.751  3826  3826 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 12:58:27.751  3826  3826 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:27.751  3826  3826 V BluetoothPbapReceiver: ***********state = 10
09-13 12:58:27.752  3826  3826 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 12:58:27.755  3826  3826 D BtGatt.GattService: Received start request. Starting profile...
09-13 12:58:27.755  3826  3826 D BtGatt.GattService: start()
09-13 12:58:27.755  3826  3826 D BtGatt.AdvertiseManager: advertise manager created
09-13 12:58:27.755  2180  2180 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 12:58:27.764  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
,09-13 12:58:27.769  3826  3826 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 12:58:27.769  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:27.769  3826  3826 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-13 12:58:27.769  3826  3826 V BluetoothMapService: BluetoothMapBinder()
09-13 12:58:27.770  3826  3826 D BluetoothMapService: Received start request. Starting profile...
09-13 12:58:27.770  3826  3826 D BluetoothMapService: start()
09-13 12:58:27.775  6285  6285 D BluetoothPermissionRequest: onReceive
,09-13 12:58:27.777  3826  3826 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-13 12:58:27.777  3826  3826 D BluetoothMapEmailAppObserver: createReceiver()
09-13 12:58:27.778  3826  3826 D BluetoothMapEmailAppObserver: initObservers()
09-13 12:58:27.778  3826  3826 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-13 12:58:27.779  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:27.779  3826  6490 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-13 12:58:27.780  3826  6490 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-13 12:58:27.780  3826  6490 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-13 12:58:27.781  6285  6285 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-13 12:58:27.782  6285  6285 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-13 12:58:27.784  3826  3826 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 12:58:27.786  6285  6285 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 12:58:27.789  3826  3826 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-13 12:58:27.795  3826  3826 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 12:58:27.799  3826  3826 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 12:58:27.799  3826  3826 V PanService: [BTUI] SIM Extra State :ABSENT
09-13 12:58:27.803  3826  3826 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-13 12:58:27.803  3826  3826 V BluetoothMapService: Handler(): got msg=1
,09-13 12:58:27.803  3826  3904 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-13 12:58:27.803  3826  3904 I bluedroid-qcom: enable
09-13 12:58:27.804  3826  6519 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-13 12:58:27.804  3826  6519 I bt-btu  : btu_task pending for preload complete event
09-13 12:58:27.804  3826  3904 I bt_hci_bdroid: init
09-13 12:58:27.806  3826  3904 I bt_vendor: bt-vendor : init
09-13 12:58:27.806  3826  3904 I bt_vendor: bt-vendor : get_bt_soc_type
09-13 12:58:27.806  3826  3904 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-13 12:58:27.806  3826  3904 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-13 12:58:27.806  3826  3904 D bt_userial_mct: userial_init
09-13 12:58:27.806  3826  3904 D bt_hci_bdroid: set_power 1
09-13 12:58:27.806  3826  3904 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-13 12:58:27.806  3826  3904 I bt_vendor: Starting hciattach daemon
09-13 12:58:27.807  3826  3904 I bt_vendor: try to set true
09-13 12:58:27.795  6522  6522 W sh      : type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 12:58:27.811  3826  3826 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:27.805  6522  6522 W sh      : type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 12:58:27.815  3826  3826 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 12:58:27.815  3826  3826 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 12:58:27.815  3826  3826 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 12:58:27.815  3826  3826 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:27.816  3826  3826 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,09-13 12:58:27.828  6460  6460 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-13 12:58:27.844  3826  3826 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 12:58:27.844  3826  3826 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:27.844  3826  3826 V BluetoothPbapReceiver: ***********state = 11
,09-13 12:58:27.850  2180  2180 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 12:58:27.853  6524  6524 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
09-13 12:58:27.863  6285  6285 D BluetoothPermissionRequest: onReceive
,09-13 12:58:27.868  6285  6285 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 12:58:27.878  3826  3826 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-13 12:58:27.881  3826  3826 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 12:58:27.881  3826  3826 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 12:58:27.881  3826  3826 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 12:58:27.881  3826  3826 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:27.881  3826  3826 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-13 12:58:27.940  1032  1935 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 12:58:27.940  1032  1935 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@27ef67df mBinding = false
09-13 12:58:27.941  1032  1094 D BluetoothManagerService: Message: 1
09-13 12:58:27.941  1032  1094 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@27ef67df
,09-13 12:58:27.945  6530  6530 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-13 12:58:27.946  3826  3942 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-13 12:58:27.947  1032  1094 E BluetoothManagerService: IBluetooth.enable() returned false
09-13 12:58:27.970  6531  6531 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-13 12:58:28.024  6536  6536 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-13 12:58:28.052  6537  6537 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-13 12:58:28.074  6538  6538 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-13 12:58:28.086  6539  6539 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
09-13 12:58:28.105  6541  6541 I libmdmdetect: ESOC framework not supported
09-13 12:58:28.107  6541  6541 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-13 12:58:28.114  6541  6541 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-13 12:58:28.114  6541  6541 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-13 12:58:28.114  6541  6541 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-13 12:58:28.114  6541  6541 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-13 12:58:28.114  6541  6541 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-13 12:58:28.114  6541  6541 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-13 12:58:28.114  6541  6541 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-13 12:58:28.159  6541  6542 E QC-QMI  : qmi_client [6541] 14: failed to locate client data
,09-13 12:58:28.160   450   450 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-13 12:58:28.160   450   450 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
09-13 12:58:28.197  6546  6546 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-13 12:58:28.210  6547  6547 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-13 12:58:28.260  3826  3904 I bt_vendor: bluetooth satus is on
09-13 12:58:28.260  3826  3904 D bt_hci_bdroid: preload
09-13 12:58:28.261  3826  6521 D bt_userial_mct: userial_open(port:0)
09-13 12:58:28.261  3826  6521 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-13 12:58:28.262  3826  6521 I bt_vendor: Done intiailizing UART
,09-13 12:58:28.264  3826  6521 I bt_vendor: Done intiailizing UART
09-13 12:58:28.264  3826  6521 I bt_userial_mct: CMD=82, EVT=82, ACL_Out=83, ACL_In=83
09-13 12:58:28.264  3826  6521 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-13 12:58:28.264  3826  6519 I bt-btu  : btu_task received preload complete event
09-13 12:58:28.264  3826  6519 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-13 12:58:28.264  3826  6519 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-13 12:58:28.264  3826  6519 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-13 12:58:28.265  3826  6549 D bt_userial_mct: Entering userial_read_thread()
09-13 12:58:28.269  3826  6519 I         : BTE_InitTraceLevels -- TRC_HCI
09-13 12:58:28.269  3826  6519 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-13 12:58:28.269  3826  6519 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-13 12:58:28.269  3826  6519 I         : BTE_InitTraceLevels -- TRC_AVDT
09-13 12:58:28.269  3826  6519 I         : BTE_InitTraceLevels -- TRC_AVRC
09-13 12:58:28.269  3826  6519 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 12:58:28.269  3826  6519 I         : BTE_InitTraceLevels -- TRC_BNEP
09-13 12:58:28.269  3826  6519 I         : BTE_InitTraceLevels -- TRC_BTM
09-13 12:58:28.269  3826  6519 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-13 12:58:28.269  3826  6519 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 12:58:28.269  3826  6519 I         : BTE_InitTraceLevels -- TRC_PAN
09-13 12:58:28.269  3826  6519 I         : BTE_InitTraceLevels -- TRC_SDP
09-13 12:58:28.269  3826  6519 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 12:58:28.269  3826  6519 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 12:58:28.269  3826  6519 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 12:58:28.269  3826  6519 I         : BTE_InitTraceLevels -- TRC_BTIF
09-13 12:58:28.321  3826  6519 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-13 12:58:28.321  3826  6519 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa021f061 
09-13 12:58:28.321  3826  6519 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa021f061 
,09-13 12:58:28.332  3826  3907 E bt-btif : Calling BTA_HhEnable
09-13 12:58:28.332  3826  3907 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-13 12:58:28.332  3826  3907 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-13 12:58:28.333  3826  6519 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-13 12:58:28.333  3826  6519 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-13 12:58:28.333  3826  6519 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-13 12:58:28.333  3826  6519 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-13 12:58:28.333  3826  6519 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-13 12:58:28.334  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-13 12:58:28.335  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
,09-13 12:58:28.337  3826  3907 D BluetoothAdapterProperties: Name is: G3
09-13 12:58:28.339  3826  3907 D BluetoothAdapterProperties: Scan Mode:20
09-13 12:58:28.339  3826  3907 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 12:58:28.339  3826  3907 D bt_hci_bdroid: postload
09-13 12:58:28.339  3826  6521 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 12:58:28.340  3826  3907 D bte_conf: Device ID record 1 : primary
09-13 12:58:28.340  3826  3907 D bte_conf:   vendorId            = 00c4
09-13 12:58:28.340  3826  3907 D bte_conf:   vendorIdSource      = 0001
09-13 12:58:28.340  3826  3907 D bte_conf:   product             = 13a1
09-13 12:58:28.340  3826  3907 D bte_conf:   version             = 1000
09-13 12:58:28.340  3826  3907 D bte_conf:   clientExecutableURL = 
09-13 12:58:28.340  3826  3907 D bte_conf:   serviceDescription  = 
09-13 12:58:28.340  3826  3907 D bte_conf:   documentationURL    = 
09-13 12:58:28.340  3826  3907 D bte_conf: bte_load_did_conf no section named DID2.
09-13 12:58:28.341  3826  6519 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-13 12:58:28.342  3826  6521 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 12:58:28.342  3826  6521 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 12:58:28.344  3826  3904 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-13 12:58:28.344  3826  3904 D BluetoothAdapterProperties: ScanMode =  20
09-13 12:58:28.344  3826  3904 D BluetoothAdapterProperties: State =  11
09-13 12:58:28.344  3826  3904 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-13 12:58:28.345  3826  3904 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-13 12:58:28.345  3826  3904 D BluetoothAdapterProperties: Setting state to 12
09-13 12:58:28.345  3826  3904 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-13 12:58:28.345  3826  3907 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-13 12:58:28.346  3826  3907 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-13 12:58:28.349  3826  6519 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 12:58:28.349  3826  6519 W bt-smp  : Plain text(LSB ~ MSB) = 28 3d 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 12:58:28.349  3826  6519 W bt-smp  : Encrypted text(LSB ~ MSB) = 97 43 9e c8 60 93 24 ff 99 30 84 a3 c0 ff 1c 11 
,09-13 12:58:28.354  3826  6519 W bt-btm  : Stopping oneshot timer
09-13 12:58:28.354  3826  6521 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 12:58:28.355  3826  6549 E bt_mct  : hci lib postload completed
09-13 12:58:28.345  6554  6554 W sh      : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 12:58:28.345  6554  6554 W sh      : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 12:58:28.376  3826  6519 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 12:58:28.376  3826  6519 W bt-smp  : Plain text(LSB ~ MSB) = 50 1f 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 12:58:28.376  3826  6519 W bt-smp  : Encrypted text(LSB ~ MSB) = de de 7d d4 14 b0 d1 e4 79 f3 41 58 6e dc 3c 09 
,09-13 12:58:28.380  3826  6519 W bt-btm  : Stopping oneshot timer
09-13 12:58:28.383  1032  1094 D BluetoothManagerService: Message: 60
09-13 12:58:28.383  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-13 12:58:28.383  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-13 12:58:28.384  3826  3907 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 12:58:28.384  3826  3907 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-13 12:58:28.384  3826  3904 I BluetoothAdapterState: Entering On State
09-13 12:58:28.386  3826  3904 D LGBluetoothServiceAdapter: [BTUI] OnState
09-13 12:58:28.386  3826  3904 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-13 12:58:28.386  3826  3904 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-13 12:58:28.387  3826  3904 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-13 12:58:28.392  3826  6519 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,09-13 12:58:28.395  3826  6519 W bt-smp  : Plain text(LSB ~ MSB) = eb 73 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 12:58:28.395  3826  6519 W bt-smp  : Encrypted text(LSB ~ MSB) = 5a 0a c5 95 38 ae cc 0b 56 2c 37 1f a2 d9 39 68 
09-13 12:58:28.395  3826  6519 W bt-btm  : Stopping oneshot timer
09-13 12:58:28.398  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:28.398  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:28.398  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:28.398  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:28.398  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:28.398  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:28.398  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:28.398  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:28.403  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:58:28.407  3826  6519 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 12:58:28.407  3826  6519 W bt-smp  : Plain text(LSB ~ MSB) = e1 13 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 12:58:28.407  3826  6519 W bt-smp  : Encrypted text(LSB ~ MSB) = d0 28 74 35 f4 99 07 91 ed 15 99 d4 ca 77 c5 9e 
,09-13 12:58:28.409  3826  6519 W bt-btm  : Stopping oneshot timer
09-13 12:58:28.417  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:28.417  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:28.417  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:28.417  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:28.417  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:28.417  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:28.417  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:28.417  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:28.420  3826  6519 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 12:58:28.420  3826  6519 W bt-smp  : Plain text(LSB ~ MSB) = f2 20 65 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 12:58:28.420  3826  6519 W bt-smp  : Encrypted text(LSB ~ MSB) = 70 a8 0b ba cf 5b 08 5b 33 ed 70 b7 08 14 30 d5 
,09-13 12:58:28.422  3826  6519 W bt-btm  : Stopping oneshot timer
09-13 12:58:28.433  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 12:58:28.435  3826  3904 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-13 12:58:28.452  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:28.452  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:28.452  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:28.452  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:28.452  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:28.452  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:28.452  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:28.452  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 12:58:28.462  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:58:28.468  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:28.468  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:28.468  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:28.468  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:28.468  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:28.468  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:28.468  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:28.468  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 12:58:28.473  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:58:28.480  6559  6559 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,09-13 12:58:28.484  6160  6477 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:28.485  6160  6233 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:58:28.485  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:28.488  6285  6300 D BluetoothMap: onBluetoothStateChange: up=true
09-13 12:58:28.490  1847  3940 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 12:58:28.493  1847  1847 D BluetoothHeadset: Proxy object connected
09-13 12:58:28.493  6285  6300 D BluetoothPan: onBluetoothStateChange on: true
09-13 12:58:28.493  6285  6300 D BluetoothPan: onBluetoothStateChange call bindService
,09-13 12:58:28.498  1032  1094 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 12:58:28.500  1032  1032 D BluetoothA2dp: Proxy object connected
09-13 12:58:28.503  1847  1862 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 12:58:28.508  1847  1847 D BluetoothHeadset: Proxy object connected
09-13 12:58:28.509  6285  6301 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-13 12:58:28.522  6285  6285 D BluetoothMap: Proxy object connected
09-13 12:58:28.522  6285  6285 D MapProfile: Bluetooth service connected
09-13 12:58:28.522  6285  6285 D BluetoothMap: getConnectedDevices()
09-13 12:58:28.522  3826  3942 V BluetoothMapService: getConnectedDevices()
09-13 12:58:28.526  1032  1954 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 12:58:28.526  1032  1954 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@27ef67df mBinding = false
,09-13 12:58:28.531  1032  1094 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 12:58:28.532  6285  6285 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 12:58:28.532  6285  6285 D PanProfile: Bluetooth service connected
09-13 12:58:28.532  6285  6301 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 12:58:28.533  1032  1032 D BluetoothHeadset: Proxy object connected
09-13 12:58:28.535  1847  2430 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 12:58:28.535  6285  6285 D BluetoothInputDevice: Proxy object connected
09-13 12:58:28.535  6285  6285 D HidProfile: Bluetooth service connected
09-13 12:58:28.537  1847  1847 D BluetoothHeadset: Proxy object connected
09-13 12:58:28.538  1032  1094 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
,09-13 12:58:28.539  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,09-13 12:58:28.539  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 12:58:28.539  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 12:58:28.539  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-13 12:58:28.543  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 12:58:28.546  1936  1936 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:28.547  1936  2091 D LGBluetoothAPIService: Message: 1
09-13 12:58:28.547  1936  2091 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-13 12:58:28.547  1032  1094 D BluetoothManagerService: Message: 2
09-13 12:58:28.549  1032  1094 D BluetoothManagerService: Sending off request.
09-13 12:58:28.549  6160  6160 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-13 12:58:28.549  3826  3844 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-13 12:58:28.550  3826  3826 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:28.551  3826  3826 D BluetoothMapService: STATE_ON
09-13 12:58:28.551  3826  3826 D LGBluetoothAPIServer: [BTUI] onCreate()
09-13 12:58:28.551  1936  2091 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,09-13 12:58:28.555  3826  3826 V BluetoothMapService: Handler(): got msg=1
09-13 12:58:28.555  3826  3826 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-13 12:58:28.555  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:28.555  3826  3826 D LGBluetoothAPIServer: [BTUI] onBind()
09-13 12:58:28.555  6285  6285 D LocalBluetoothProfileManager: Adding local A2DP profile
09-13 12:58:28.557  1936  1936 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-13 12:58:28.557  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:28.557  1936  2091 D LGBluetoothAPIService: Message: 100
09-13 12:58:28.557  1936  2091 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-13 12:58:28.557  3826  3826 V BluetoothPbapService: Pbap Service onCreate
09-13 12:58:28.557  3826  3826 V BluetoothPbapService: Starting PBAP service
09-13 12:58:28.557  3826  6579 D BluetoothMapMasInstance: MAS initSocket()
09-13 12:58:28.558  3826  6579 D BluetoothMapMasInstance:   masId = 00
09-13 12:58:28.558  3826  6579 D BluetoothMapMasInstance:   msgTypes = 0e
09-13 12:58:28.558  3826  6579 D BluetoothMapMasInstance:   masName = SMS/MMS
09-13 12:58:28.558  3826  6579 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-13 12:58:28.558  1032  1772 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 12:58:28.558  3826  3826 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-13 12:58:28.559  3826  3826 V BluetoothPbapService: Pbap Service onBind
09-13 12:58:28.560  3826  3826 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:28.560  3826  3826 V BluetoothPbapService: state: 12
09-13 12:58:28.560  3826  3904 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-13 12:58:28.561  3826  3904 D BluetoothAdapterProperties: Setting state to 13
09-13 12:58:28.561  3826  3904 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 12:58:28.561  3826  3826 V BluetoothPbapService: Handler(): got msg=1
09-13 12:58:28.562  3826  3904 D BluetoothAdapterProperties: onBluetoothDisable()
09-13 12:58:28.562  3826  3904 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-13 12:58:28.562  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:28.563  3826  3826 V BluetoothPbapService: Pbap Service closeService in
09-13 12:58:28.566  3826  3907 D BluetoothAdapterProperties: Scan Mode:20
,09-13 12:58:28.569  6160  6160 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:58:28.569  3826  6579 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 12:58:28.569  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:28.569  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:28.569  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:28.569  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:28.569  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 12:58:28.569  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:28.569  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:28.569  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:28.569  3826  3904 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-13 12:58:28.570  3826  6519 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-13 12:58:28.570  3826  6519 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-13 12:58:28.570  3826  3826 V BluetoothPbapService: successfully stopped pbap service
09-13 12:58:28.570  3826  3826 V BluetoothPbapService: Pbap Service closeService out
09-13 12:58:28.571  3826  3904 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-13 12:58:28.571  6285  6285 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-13 12:58:28.572  3826  6579 E BluetoothServiceJni: Socket listen failed: 2
09-13 12:58:28.572  3826  6579 E BluetoothAdapterService(548581108): Failed to create socket channel
09-13 12:58:28.572  6160  6160 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:58:28.572  3826  6579 E BluetoothMapMasInstance: Error create RfcommServerSocket java.io.IOException: Error: -1
09-13 12:58:28.572  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:58:28.573  1032  1094 D BluetoothManagerService: Message: 30
09-13 12:58:28.573  3826  3826 V BluetoothPbapService: Pbap Service onDestroy
09-13 12:58:28.573  3826  3826 V BluetoothPbapService: Pbap Service closeService in
09-13 12:58:28.573  3826  3826 V BluetoothPbapService: Pbap Service closeService out
09-13 12:58:28.573  3826  3826 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-13 12:58:28.573  3826  6579 W BluetoothMapMasInstance: initServerSocket failed as BT is (being) turned off
09-13 12:58:28.573  3826  6579 E BluetoothMapMasInstance: Error to create listening socket after 10 try
09-13 12:58:28.573  1032  1094 D BluetoothManagerService: Message: 60
09-13 12:58:28.573  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-13 12:58:28.573  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-13 12:58:28.575  1032  1094 D BluetoothManagerService: Message: 30
09-13 12:58:28.575  1936  1936 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:28.576  3826  6519 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 12:58:28.576  3826  6519 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 12:58:28.576  3826  6519 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 12:58:28.576  3826  6519 W bt-l2cap: L2CAP - L2CA,_Deregister() called for PSM: 0x0019
09-13 12:58:28.576  3826  6519 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 12:58:28.576  3826  6519 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 12:58:28.576  3826  6519 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 12:58:28.576  3826  6519 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 12:58:28.576  3826  6519 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 12:58:28.576  3826  6519 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-13 12:58:28.576  3826  6519 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-13 12:58:28.576  3826  6519 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-13 12:58:28.577  6160  6160 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:58:28.577  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:28.577  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:28.577  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:28.577  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:28.577  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 12:58:28.577  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:28.577  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:28.577  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:28.577  6160  6160 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:58:28.577  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 12:58:28.581  3826  3826 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:28.581  3826  3826 D BluetoothMapService: STATE_TURNING_OFF
09-13 12:58:28.581  3826  3826 V BluetoothMapService: Handler(): got msg=4
09-13 12:58:28.581  3826  3826 D BluetoothMapService: MAP Service closeService in
09-13 12:58:28.581  3826  3826 D BluetoothMapMasInstance: MAP Service shutdown
09-13 12:58:28.581  3826  3826 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 12:58:28.581  3826  3826 V BluetoothMapService: MAP Service closeService out
09-13 12:58:28.582  6160  6160 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:58:28.582  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:28.582  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:28.582  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:28.582  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:28.582  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 12:58:28.582  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:28.582  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:28.582  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:28.582  6160  6160 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:58:28.582  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:58:28.583  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 12:58:28.584  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:28.585  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:28.586  6285  6285 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-13 12:58:28.586  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:28.587  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:28.587  6285  6285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 12:58:28.589  6285  6285 D BluetoothPbap: Proxy object connected
09-13 12:58:28.590  6285  6285 D PbapServerProfile: Bluetooth service connected
09-13 12:58:28.590  6285  6285 D BluetoothPbap: Proxy object disconnected
09-13 12:58:28.590  6285  6285 D PbapServerProfile: Bluetooth service disconnected
09-13 12:58:28.590  6285  6285 D BluetoothA2dp: Proxy object connected
09-13 12:58:28.591  6285  6285 D A2dpProfile: Bluetooth service connected
,09-13 12:58:28.592  3826  3826 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 12:58:28.593  3826  3826 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:28.593  3826  3826 V BluetoothPbapReceiver: ***********state = 12
,09-13 12:58:28.594  6285  6285 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
09-13 12:58:28.594  6285  6285 D BluetoothHeadset: Proxy object connected
09-13 12:58:28.595  6285  6285 D HeadsetProfile: Bluetooth service connected
09-13 12:58:28.595  2180  2180 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 12:58:28.596  2180  2180 D c       : Getting all permits...
09-13 12:58:28.596  2180  2180 D a       : Opening database...
09-13 12:58:28.598  2180  2180 D a       : Opening database auth.proximity.permit_store...
09-13 12:58:28.598  6285  6285 D DockEventReceiver: finishStartingService: stopping service
09-13 12:58:28.598  2180  2180 D a       : Closing database...
09-13 12:58:28.609  6285  6285 D BluetoothPermissionRequest: onReceive
,09-13 12:58:28.610  6285  6285 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-13 12:58:28.612  6285  6285 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 12:58:28.614  3826  3826 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-13 12:58:28.615  3826  3826 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-13 12:58:28.616  3826  3826 V BtOppService: onCreate
09-13 12:58:28.616  3826  3826 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-13 12:58:28.617  3826  3826 V BluetoothOppNotification: send message
09-13 12:58:28.619  3826  3826 D BluetoothOppPreference: Dumping Names:  
09-13 12:58:28.619  3826  3826 D BluetoothOppPreference: {}
09-13 12:58:28.619  3826  3826 D BluetoothOppPreference: Dumping Channels:  
09-13 12:58:28.619  3826  3826 D BluetoothOppPreference: {}
09-13 12:58:28.619  3826  3826 E BtOppService: [BTUI] updateFromProvider : mListenStarted is null
09-13 12:58:28.619  3826  3826 V BtOppService: onStartCommand
09-13 12:58:28.620  3826  6585 V BtOppService: Deleted complete outbound shares, number =  0
,09-13 12:58:28.622  3826  3826 E BtOppService: [BTUI] updateFromProvider : mListenStarted is null
09-13 12:58:28.622  3826  6585 V BtOppService: Deleted complete inbound failed shares, number = 0
09-13 12:58:28.622  3826  6585 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-13 12:58:28.623  3826  6585 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30ce78ae on behalf of 
09-13 12:58:28.624  3826  3826 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:28.624  3826  3826 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-13 12:58:28.626  3826  3826 V BluetoothOppNotification: previous thread is not finished yet
09-13 12:58:28.626  3826  3826 V BtOppService: ContentObserver received notification
09-13 12:58:28.626  3826  3826 E BtOppService: [BTUI] updateFromProvider : mListenStarted is null
09-13 12:58:28.627  3826  3826 V BtOppService: ContentObserver received notification
09-13 12:58:28.627  3826  3826 E BtOppService: [BTUI] updateFromProvider : mListenStarted is null
09-13 12:58:28.627  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:28.627  3826  3826 V BluetoothFtpService: Ftp Service onCreate
09-13 12:58:28.627  3826  3826 I BluetoothFtpService: Ftp Service onCreate
09-13 12:58:28.627  3826  3826 V BluetoothFtpService: Ftp Service onStartCommand
09-13 12:58:28.627  3826  3826 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:28.627  3826  3826 V BluetoothFtpService: Starting Listening on sockets
09-13 12:58:28.628  3826  3826 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 12:58:28.628  3826  3826 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 12:58:28.628  3826  3826 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 12:58:28.628  3826  3826 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:28.628  3826  3826 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-13 12:58:28.628  3826  3826 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-13 12:58:28.630  3826  3826 V BluetoothFtpService: Handler(): got msg=1
09-13 12:58:28.630  3826  3826 V BluetoothFtpService: Ftp Service closeService
09-13 12:58:28.634  3826  3826 V BluetoothFtpService: successfully stopped ftp service
09-13 12:58:28.635  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:28.635  3826  3826 V BluetoothSapService: Sap Service onCreate
,09-13 12:58:28.639  3826  3826 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:28.639  3826  3826 V BluetoothSapService: state: 12
09-13 12:58:28.639  3826  3826 V BluetoothSapService: Starting SAP server process
09-13 12:58:28.640  3826  3826 V BluetoothFtpService: Ftp Service onDestroy
,09-13 12:58:28.640  3826  3826 V BluetoothFtpService: Ftp Service closeService
09-13 12:58:28.635  6586  6586 W sapd    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 12:58:28.635  6586  6586 W sapd    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 12:58:28.642  6285  6285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 12:58:28.647  3826  3826 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 12:58:28.647  3826  3826 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:28.647  3826  3826 V BluetoothPbapReceiver: ***********state = 13
09-13 12:58:28.649  3826  3826 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,09-13 12:58:28.652  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:28.652  3826  3826 V BluetoothPbapService: Pbap Service onCreate
,09-13 12:58:28.652  3826  3826 V BluetoothPbapService: Starting PBAP service
09-13 12:58:28.654  3826  3826 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-13 12:58:28.654  6285  6285 D DockEventReceiver: finishStartingService: stopping service
09-13 12:58:28.654  3826  3826 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,09-13 12:58:28.654  3826  3826 V BluetoothPbapService: state: 13
09-13 12:58:28.654  3826  3826 V BluetoothPbapService: Pbap Service closeService in
09-13 12:58:28.655  3826  3826 V BluetoothPbapService: successfully stopped pbap service
09-13 12:58:28.656  3826  3826 V BluetoothPbapService: Pbap Service closeService out
09-13 12:58:28.656  6586  6586 V BT_SAP  : Event pipe created
09-13 12:58:28.656  6586  6586 V BT_SAP  : create_server_socket qcom.sap.server
09-13 12:58:28.656  3826  3826 V BluetoothPbapService: Pbap Service onDestroy
09-13 12:58:28.656  3826  3826 V BluetoothPbapService: Pbap Service closeService in
09-13 12:58:28.656  6586  6586 V BT_SAP  : created socket fd 6
09-13 12:58:28.656  3826  3826 V BluetoothPbapService: Pbap Service closeService out
09-13 12:58:28.656  3826  3826 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-13 12:58:28.656  2180  2180 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 12:58:28.669  6285  6285 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-13 12:58:28.675  6285  6285 D BluetoothPermissionRequest: onReceive
09-13 12:58:28.675  6285  6285 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-13 12:58:28.681  6285  6285 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-13 12:58:28.685  3826  3826 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-13 12:58:28.685  3826  3826 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-13 12:58:28.686  3826  3826 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-13 12:58:28.690  3826  3826 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:28.690  3826  3826 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-13 12:58:28.693  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:28.693  3826  3826 V BluetoothFtpService: Ftp Service onCreate
,09-13 12:58:28.693  3826  3826 I BluetoothFtpService: Ftp Service onCreate
09-13 12:58:28.694  3826  3826 V BluetoothFtpService: Ftp Service onStartCommand
09-13 12:58:28.694  3826  3826 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:28.694  3826  3826 V BluetoothFtpService: Ftp Service closeService
09-13 12:58:28.695  3826  3826 V BluetoothFtpService: successfully stopped ftp service
09-13 12:58:28.696  3826  3826 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 12:58:28.696  3826  3826 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 12:58:28.696  3826  3826 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 12:58:28.696  3826  3826 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:28.696  3826  3826 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-13 12:58:28.696  3826  3826 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-13 12:58:28.698  3826  3826 V BluetoothFtpService: Ftp Service onDestroy
09-13 12:58:28.698  3826  3826 V BluetoothFtpService: Ftp Service closeService
09-13 12:58:28.701  3826  3826 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:28.701  3826  3826 V BluetoothSapService: state: 13
09-13 12:58:28.701  3826  3826 V BluetoothSapService: Stopping SAP server process
09-13 12:58:28.702  3826  3826 V BluetoothSapService: Sap Service closeSapService in
09-13 12:58:28.702  3826  3826 V BluetoothSapService: Close listen Socket : 
09-13 12:58:28.702  3826  3826 V BluetoothSapService: Close rfcomm Socket : 
09-13 12:58:28.702  3826  3826 V BluetoothSapService: Close sapd  Socket : 
09-13 12:58:28.703  3826  3826 V BluetoothSapService: Sap Service closeSapService out
09-13 12:58:28.703  3826  3826 V BluetoothSapService: Sap Service onDestroy
09-13 12:58:28.703  3826  3826 V BluetoothSapService: Sap Service closeSapService in
09-13 12:58:28.703  3826  3826 V BluetoothSapService: Close listen Socket : 
09-13 12:58:28.703  3826  3826 V BluetoothSapService: Close rfcomm Socket : 
09-13 12:58:28.703  3826  3826 V BluetoothSapService: Close sapd  Socket : 
09-13 12:58:28.707  3826  3826 V BluetoothSapService: Sap Service closeSapService out
,09-13 12:58:28.722  1032  1387 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:28.722  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 12:58:28.722  1032  1387 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 12:58:28.735  1032  1390 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 12:58:28.735  1032  1390 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 12:58:28.736  1032  1390 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 12:58:28.737  1032  1390 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
,09-13 12:58:28.738  1032  1390 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
09-13 12:58:29.047  6160  6560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:58:29.047  6160  6560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:29.047  6160  6560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:29.047  6160  6560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:29.047  6160  6560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:29.047  6160  6560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 12:58:29.047  6160  6560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:29.047  6160  6560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:29.047  6160  6560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 12:58:29.056  6160  6560 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:58:29.056  6160  6560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:58:29.065  6160  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:58:29.072  1032  2026 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 12:58:29.072  1032  2026 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@27ef67df mBinding = false
09-13 12:58:29.088  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 12:58:29.088  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 12:58:29.088  1032  1032 D Ulp_jni : JNI:system_update. Event-4
,09-13 12:58:29.092  1032  1094 D BluetoothManagerService: Message: 1
09-13 12:58:29.092  1032  1094 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@27ef67df
09-13 12:58:29.095  3826  3845 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-13 12:58:29.095  1032  1094 E BluetoothManagerService: IBluetooth.enable() returned false
09-13 12:58:29.581  3826  3907 D bt_hci_bdroid: cleanup
,09-13 12:58:29.587  3826  6521 I bt_lpm  : LPM is already off!!!
09-13 12:58:29.588  3826  6519 W bt-btif : ag scb idx 1 not allocated
09-13 12:58:29.588  3826  6519 E bt-btif : BTA AG is already disabled, ignoring ...
09-13 12:58:29.588  3826  6519 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 12:58:29.588  3826  6519 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 12:58:29.588  3826  6519 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 12:58:29.588  3826  6519 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 12:58:29.589  3826  6519 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 12:58:29.589  3826  6519 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 12:58:29.589  3826  6519 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 12:58:29.589  3826  6519 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 12:58:29.589  3826  6519 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 12:58:29.589  3826  6519 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 12:58:29.589  3826  6519 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 12:58:29.589  3826  6519 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 12:58:29.589  3826  6519 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-13 12:58:29.589  3826  6519 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 12:58:29.589  3826  6519 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-13 12:58:29.589  3826  6519 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 12:58:29.589  3826  6519 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-13 12:58:29.589  3826  6519 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 12:58:29.589  3826  6519 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-13 12:58:29.593  3826  6549 I bt_userial_mct: exiting userial_read_thread
09-13 12:58:29.593  3826  6549 D bt_userial_mct: Leaving userial_evt_read_thread()
09-13 12:58:29.593  3826  3907 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-13 12:58:29.594  3826  6521 I bt_vendor: hw_epilog_process
09-13 12:58:29.594  3826  3907 D bt_hci_bdroid: cleanup Finalizing cleanup
09-13 12:58:29.594  3826  3907 D bt_userial_mct: userial_close
09-13 12:58:29.595  3826  3907 E bt_userial_mct: pthread_join() FAILED result:3
09-13 12:58:29.595  3826  3907 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-13 12:58:29.597  1032  1727 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 12:58:29.597  1032  1727 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@27ef67df mBinding = false
,09-13 12:58:29.601  1032  1094 D BluetoothManagerService: Message: 1
09-13 12:58:29.601  1032  1094 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@27ef67df
09-13 12:58:29.604  3826  3942 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-13 12:58:29.604  1032  1094 E BluetoothManagerService: IBluetooth.enable() returned false
09-13 12:58:29.612  3826  3907 D bt_hci_bdroid: set_power 0
,09-13 12:58:29.614  3826  3907 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-13 12:58:29.614  3826  3907 I bt_vendor: bluetooth satus is on
09-13 12:58:29.614  3826  3907 I bt_vendor: bt-vendor : resetting BT status
09-13 12:58:29.614  3826  3907 I bt_vendor: Starting hciattach daemon
09-13 12:58:29.615  3826  3907 I bt_vendor: try to set false
09-13 12:58:29.617  3826  3907 I bt_vendor: Starting hciattach daemon
09-13 12:58:29.617  3826  3907 I bt_vendor: try to set false
09-13 12:58:29.618  3826  3907 I bt_vendor: cleanup
09-13 12:58:29.618  3826  6519 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-13 12:58:29.619  3826  3907 I GKI_LINUX: GKI_exit_task 0 done
09-13 12:58:29.619  3826  3907 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-13 12:58:29.620  3826  3904 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-13 12:58:29.625  3826  3826 D HeadsetService: Received stop request...Stopping profile...
,09-13 12:58:29.630  3826  3826 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-13 12:58:29.630  3826  3826 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 12:58:29.630  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:29.631  3826  6490 D HeadsetStateMachine: Exit Disconnected: -1
09-13 12:58:29.635  1032  1032 D BluetoothHeadset: Proxy object disconnected
09-13 12:58:29.635  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-13 12:58:29.637  1847  1847 D BluetoothHeadset: Proxy object disconnected
,09-13 12:58:29.640  1847  1847 D BluetoothHeadset: Proxy object disconnected
09-13 12:58:29.640  3826  3826 D A2dpService: Received stop request...Stopping profile...
09-13 12:58:29.641  3826  6511 D A2dpStateMachine: Exit Disconnected: -1
09-13 12:58:29.643  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-13 12:58:29.644  3826  3904 D BluetoothAdapterState: Stopping profile services that were post enabled
09-13 12:58:29.645  3826  3826 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-13 12:58:29.645  3826  3826 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 12:58:29.645  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:29.646  1032  1032 D BluetoothA2dp: Proxy object disconnected
09-13 12:58:29.646  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-13 12:58:29.647  3826  3826 V BluetoothOppNotification: previous thread is not finished yet
09-13 12:58:29.649  3826  3826 D HidService: Received stop request...Stopping profile...
09-13 12:58:29.649  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:29.653  3826  3826 D HealthService: Received stop request...Stopping profile...
09-13 12:58:29.653  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
,09-13 12:58:29.657  3826  3826 D PanService: Received stop request...Stopping profile...
09-13 12:58:29.657  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:29.658  3826  3826 D HeadsetStateMachine: Unbinding service...
09-13 12:58:29.659  3826  3826 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 12:58:29.659  3826  3826 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 12:58:29.659  3826  3826 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 12:58:29.660  3826  3826 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 12:58:29.660  3826  3826 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 12:58:29.660  3826  3826 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 12:58:29.660  3826  3826 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-13 12:58:29.660  3826  3826 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 12:58:29.661  3826  3826 D BtGatt.GattService: Received stop request...Stopping profile...
09-13 12:58:29.661  3826  3826 D BtGatt.GattService: stop()
09-13 12:58:29.661  3826  3826 D BtGatt.AdvertiseManager: advertise clients cleared
09-13 12:58:29.663  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:29.665  3826  3826 D BluetoothMapService: Received stop request...Stopping profile...
09-13 12:58:29.665  3826  3826 D BluetoothMapService: stop()
,09-13 12:58:29.668  3826  3826 D BluetoothMapEmailAppObserver: deinitObservers()
09-13 12:58:29.668  3826  3826 D BluetoothMapEmailAppObserver: removeReceiver()
09-13 12:58:29.668  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:29.669  3826  3826 I BluetoothA2dpServiceJni: cleanupNative
09-13 12:58:29.670  3826  6512 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-13 12:58:29.670  3826  3826 I GKI_LINUX: GKI_exit_task 2 done
09-13 12:58:29.670  3826  3826 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-13 12:58:29.671  3826  3826 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 12:58:29.671  3826  3826 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 12:58:29.671  3826  3826 V BluetoothMapService: Handler(): got msg=4
09-13 12:58:29.671  3826  3826 D BluetoothMapService: MAP Service closeService in
09-13 12:58:29.671  3826  3826 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 12:58:29.671  3826  3826 V BluetoothMapService: MAP Service closeService out
09-13 12:58:29.672  3826  3904 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-13 12:58:29.672  3826  3904 D BluetoothAdapterProperties: Setting state to 10
09-13 12:58:29.672  3826  3904 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-13 12:58:29.673  1032  1094 D BluetoothManagerService: Message: 60
09-13 12:58:29.673  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-13 12:58:29.673  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-13 12:58:29.675  3826  3826 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 12:58:29.675  3826  3826 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 12:58:29.675  3826  3826 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 12:58:29.676  3826  3904 I BluetoothAdapterState: Entering OffState
,09-13 12:58:29.682  3826  3826 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 12:58:29.682  3826  3826 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 12:58:29.684  3826  3826 D BluetoothMapService: cleanup()
09-13 12:58:29.684  3826  3826 D BluetoothMapService: MAP Service closeService in
09-13 12:58:29.684  3826  3826 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-13 12:58:29.684  3826  3826 V BluetoothMapService: MAP Service closeService out
09-13 12:58:29.685  6285  6301 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 12:58:29.687  6285  6301 D BluetoothMap: onBluetoothStateChange: up=false
09-13 12:58:29.687  1847  1847 D BluetoothHeadset: Proxy object disconnected
,09-13 12:58:29.689  1847  3940 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 12:58:29.690  6285  6301 D BluetoothPan: onBluetoothStateChange on: false
09-13 12:58:29.691  6285  6301 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 12:58:29.691  1032  1094 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 12:58:29.692  1847  2430 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 12:58:29.692  6285  6301 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 12:58:29.693  1032  1094 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 12:58:29.693  6285  6301 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 12:58:29.693  1847  4356 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 12:58:29.694  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-13 12:58:29.696  1936  1936 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:29.696  1936  2091 D LGBluetoothAPIService: Message: 2
09-13 12:58:29.696  1936  2091 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@1767a4d6 mBinding = false
09-13 12:58:29.696  1936  2091 D LGBluetoothAPIService: Sending unbind request.
,09-13 12:58:29.702  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 12:58:29.709  6285  6285 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-13 12:58:29.709  6285  6285 D LGBluetoothEventManager: [BTUI] clear device connection state
09-13 12:58:29.715  3826  3826 D LGBluetoothAPIServer: [BTUI] onUnbind()
09-13 12:58:29.715  3826  3826 D LGBluetoothAPIServer: [BTUI] cleanup() done
,09-13 12:58:29.717  3826  3826 D LGBluetoothAPIServer: [BTUI] onDestroy()
09-13 12:58:29.719  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:29.720  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:29.722  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:29.723  6285  6285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 12:58:29.728  3826  3826 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 12:58:29.728  3826  3826 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:29.728  3826  3826 V BluetoothPbapReceiver: ***********state = 10
,09-13 12:58:29.740  2180  2180 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 12:58:29.748  6285  6285 D DockEventReceiver: finishStartingService: stopping service
09-13 12:58:29.761  6285  6285 D BluetoothPermissionRequest: onReceive
,09-13 12:58:29.763  6285  6285 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-13 12:58:29.763  6285  6285 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-13 12:58:29.765  6285  6285 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 12:58:29.770  3826  3826 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:29.772  3826  3826 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 12:58:29.772  3826  3826 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 12:58:29.772  3826  3826 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 12:58:29.772  3826  3826 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:29.772  3826  3826 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-13 12:58:29.774  6460  6460 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-13 12:58:29.978  1032  6407 E WifiMonitor: WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-13 12:58:29.978  1032  6407 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,09-13 12:58:29.980  1032  1390 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=7 known=0 got=7 bcn=0
,09-13 12:58:29.982  1032  1390 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=7 known=0 got=7 bcn=0
09-13 12:58:29.982  1032  6407 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-13 12:58:29.982  1032  6407 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: WPS-AP-AVAILABLE 
09-13 12:58:29.982  1032  6407 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-13 12:58:29.983  1032  1390 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=7 known=0 got=7 bcn=0
09-13 12:58:29.985  1032  1390 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=7 known=0 got=7 bcn=0
09-13 12:58:29.985  1032  1390 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-13 12:58:29.986  6388  6388 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-13 12:58:29.987  1032  6407 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-13 12:58:29.987  1032  6407 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-13 12:58:30.005  1032  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=203101  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-13 12:58:30.012  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:30.012  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 12:58:30.012  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:30.012  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 12:58:30.012  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 12:58:30.014  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 12:58:30.015  1032  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=203111  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-13 12:58:30.016  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:30.019  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:30.019  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:30.020  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-13 12:58:30.022  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 12:58:30.022  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-13 12:58:30.023  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 12:58:30.023  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-13 12:58:30.028  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:30.031  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 12:58:30.041  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:30.048  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 12:58:30.048  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 12:58:30.050  6308  6308 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-13 12:58:30.055  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 12:58:30.062  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 12:58:30.069  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 12:58:30.076  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 12:58:30.076  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 12:58:30.076  6308  6308 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 12:58:30.104  1032  1990 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 12:58:30.105  1032  1990 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@27ef67df mBinding = false
09-13 12:58:30.105  1032  1094 D BluetoothManagerService: Message: 1
09-13 12:58:30.105  1032  1094 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@27ef67df
,09-13 12:58:30.110  6388  6388 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-13 12:58:30.111  1032  6407 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-13 12:58:30.111  1032  6407 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-13 12:58:30.112  1032  6407 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-13 12:58:30.112  1032  6407 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-13 12:58:30.112  1032  6407 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 12:58:30.112  1032  6407 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 12:58:30.114  1032  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=203210  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-13 12:58:30.115  1032  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=203211  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,09-13 12:58:30.117  1032  1390 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 33 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=203213
09-13 12:58:30.118  1032  1390 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 33 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=203214
09-13 12:58:30.118  3826  3904 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,09-13 12:58:30.118  3826  3904 D BluetoothAdapterProperties: Setting state to 11
09-13 12:58:30.118  3826  3904 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-13 12:58:30.119  1032  1390 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 33 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=203214
09-13 12:58:30.119  3826  3904 D BluetoothBondStateMachine: make
09-13 12:58:30.120  1032  1390 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 33 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=203216
09-13 12:58:30.121  1032  1390 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 33 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=203216
09-13 12:58:30.122  1032  6407 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 12:58:30.122  1032  6407 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 12:58:30.122  6388  6388 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 12:58:30.122  1032  6407 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-13 12:58:30.122  6388  6388 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 12:58:30.122  1032  6407 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 12:58:30.122  1032  6407 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 12:58:30.122  1032  6407 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-13 12:58:30.122  1032  6407 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 12:58:30.123  1032  6407 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 12:58:30.124  1032  6407 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 12:58:30.124  1032  6407 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 12:58:30.125  1032  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=203220  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,09-13 12:58:30.128   308  6620 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-13 12:58:30.128  3826  3904 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:30.128  3826  3904 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-13 12:58:30.128  3826  3904 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:30.128  3826  3904 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-13 12:58:30.128  3826  3904 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-13 12:58:30.129  3826  6619 I BluetoothBondStateMachine: StableState(): Entering Off State
09-13 12:58:30.129  1032  1092 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-13 12:58:30.131  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 12:58:30.131  6285  6285 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 12:58:30.131  6285  6285 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 12:58:30.132  6285  6285 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 12:58:30.132  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 12:58:30.132  3826  3904 E BluetoothAdapterService: File transfer profiles supported!!
09-13 12:58:30.132  1032  1094 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-13 12:58:30.132  1032  1094 D BluetoothManagerService: Message: 60
09-13 12:58:30.133  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-13 12:58:30.133  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-13 12:58:30.137  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 12:58:30.137  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-13 12:58:30.139  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:30.141  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:30.141  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:30.141  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-13 12:58:30.143  1032  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=203238  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-13 12:58:30.145  3826  3826 D HeadsetService: Received start request. Starting profile...
09-13 12:58:30.145  3826  3826 D HeadsetStateMachine: make
09-13 12:58:30.146  1936  1936 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:30.147  3826  3904 E BluetoothAdapterService: File transfer profiles supported!!
,09-13 12:58:30.151  6039  6396 D UEI.SmartControl: Internal timer expired: 2
09-13 12:58:30.151  6039  6396 D UEI.SmartControl: unbind internal service
09-13 12:58:30.151  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:30.152  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:30.153  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:30.155  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:30.155  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:30.156  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-13 12:58:30.156  6285  6285 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 12:58:30.156  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-13 12:58:30.157  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 12:58:30.157  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 12:58:30.157  6285  6285 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 12:58:30.157  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-13 12:58:30.157  6285  6285 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 12:58:30.157  6285  6285 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-13 12:58:30.159  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 12:58:30.159  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-13 12:58:30.159  1032  1390 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-13 12:58:30.159  1032  1390 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-13 12:58:30.160  1032  1390 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 12:58:30.160  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 12:58:30.160  1032  1390 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 12:58:30.160  1032  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 12:58:30.162  3826  3826 D HeadsetStateMachine: max_hf_connections = 1
09-13 12:58:30.162  3826  3826 I bluedroid-qcom: get_profile_interface handsfree
09-13 12:58:30.162  3826  3826 E LGBluetoothDtmfAdapter: LGBluetoothDtmfLocalPlay is not null
09-13 12:58:30.162  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:30.162  3826  6621 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-13 12:58:30.162  3826  6621 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-13 12:58:30.162  3826  6621 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-13 12:58:30.162  3826  6621 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
,09-13 12:58:30.166  1032  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=203257  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-13 12:58:30.166  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:30.166   315  2167 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 3826
09-13 12:58:30.167   315  2167 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-13 12:58:30.167   315  2167 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-13 12:58:30.167   315  2167 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-13 12:58:30.167   315  2167 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-13 12:58:30.167   315  2167 V voice   : voice_set_parameters: exit with code(0)
09-13 12:58:30.167   315  2167 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-13 12:58:30.167   315  2167 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-13 12:58:30.167  3826  3904 E BluetoothAdapterService: File transfer profiles supported!!
09-13 12:58:30.167   315  2167 V msm8974_platform: platform_set_parameters: exit with code(0)
09-13 12:58:30.167  3826  3826 D HeadsetStateMachine: Proxy object connected
09-13 12:58:30.167   315  2167 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-13 12:58:30.167  3826  3826 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-13 12:58:30.167   315  2167 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-13 12:58:30.167   315  2167 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-13 12:58:30.167  3826  3826 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-13 12:58:30.169  1032  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=203264  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-13 12:58:30.169  1032  1390 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=203265
09-13 12:58:30.170  1032  1390 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=203266
09-13 12:58:30.171  1032  1390 D WifiNative-wlan0: doString: [STATUS]
09-13 12:58:30.171  1032  6407 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 12:58:30.171  1032  6407 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 12:58:30.172  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 12:58:30.172  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 12:58:30.172  1032  1390 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-13 12:58:30.172  3826  3826 D A2dpService: Received start request. Starting profile...
09-13 12:58:30.172  3826  3826 V Avrcp   : make
09-13 12:58:30.172  3826  3826 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-13 12:58:30.172  3826  3826 I bluedroid-qcom: get_profile_interface avrcp
09-13 12:58:30.173  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:30.174  1032  1390 I WifiServiceExtension: setVHTCapabilityType  : false
,09-13 12:58:30.176  3826  3904 E BluetoothAdapterService: File transfer profiles supported!!
09-13 12:58:30.179  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 12:58:30.180  1032  1390 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-13 12:58:30.180  1032  1390 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-13 12:58:30.180  3826  3826 V AudioManager: registerRemoteController: size of Media player list: 0
09-13 12:58:30.182  3826  3826 E AudioManager: No RCC entry present to update
09-13 12:58:30.182  3826  3826 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-13 12:58:30.182  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-13 12:58:30.182  3826  3826 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-13 12:58:30.183  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:30.184  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:30.184  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-13 12:58:30.186  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 12:58:30.186  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-13 12:58:30.188  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-13 12:58:30.189  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:30.190  3826  3904 E BluetoothAdapterService: File transfer profiles supported!!
09-13 12:58:30.194  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:30.194  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:30.194  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-13 12:58:30.217  1032  1390 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-13 12:58:30.217  1032  1455 D ConnectivityService: Got NetworkAgent Messenger
,09-13 12:58:30.218  1032  1455 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-13 12:58:30.218  1032  1390 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 12:58:30.218  1032  1390 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 12:58:30.219  1032  1455 D ConnectivityService: NetworkAgent connected
09-13 12:58:30.219  1032  1390 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 12:58:30.219  1032  1390 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 12:58:30.225  1032  1390 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 12:58:30.225  1032  1390 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 12:58:30.225  1032  1390 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 12:58:30.226  1032  1390 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 12:58:30.226  1032  1390 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 12:58:30.230  1032  1390 D WifiNative-wlan0: SAVE_CONFIG: returned true
,09-13 12:58:30.233   308   890 D CommandListener: Setting iface cfg
09-13 12:58:30.243  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 12:58:30.243  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-13 12:58:30.245  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:30.248  3826  3904 E BluetoothAdapterService: File transfer profiles supported!!
09-13 12:58:30.256  1032  1390 E WifiStateMachine: Start Dhcp Watchdog 1
09-13 12:58:30.256  1032  6625 D DhcpStateMachine: StoppedState
09-13 12:58:30.256  1032  6625 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:30.257  1032  1390 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=203352  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 12:58:30.257  1032  6625 D DhcpStateMachine: WaitBeforeStartState
09-13 12:58:30.257  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 12:58:30.257  1032  1390 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=203353  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 12:58:30.258  1032  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=203353  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 12:58:30.259  1032  1390 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=203354  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-13 12:58:30.259  1032  1390 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=203355  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 12:58:30.260  1032  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=203355  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-13 12:58:30.262  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 12:58:30.262  1032  1032 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-13 12:58:30.265  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:30.266  1032  1390 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:590527738] from screen [on:0 period:590527738]
09-13 12:58:30.266  3826  3904 E BluetoothAdapterService: File transfer profiles supported!!
09-13 12:58:30.271  1032  1390 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:590527743]
09-13 12:58:30.271  1032  1390 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-13 12:58:30.276  3826  3904 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-13 12:58:30.280  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:30.281  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 12:58:30.282  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 12:58:30.282  1032  1455 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
09-13 12:58:30.282  6308  6308 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 12:58:30.282  1032  1390 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,09-13 12:58:30.283  1032  1390 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,09-13 12:58:30.283  1032  1390 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,09-13 12:58:30.284  1032  1390 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 12:58:30.284  1032  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 12:58:30.285  1032  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 12:58:30.285  1032  1455 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
09-13 12:58:30.286  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 12:58:30.286  1032  1390 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
09-13 12:58:30.287  1032  1390 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
09-13 12:58:30.287  1032  1390 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-13 12:58:30.287  6388  6388 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-13 12:58:30.287  1032  1390 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-13 12:58:30.288  1032  1390 D WifiNative-wlan0: doBoolean: SET ps 0
09-13 12:58:30.288  1032  1390 D WifiNative-wlan0: SET ps 0: returned true
09-13 12:58:30.288  1032  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-13 12:58:30.288  6388  6388 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-13 12:58:30.289  1032  1390 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-13 12:58:30.290  1032  1387 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4885847 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:30.290  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4885847 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:30.290  1032  6625 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:30.291  1032  1390 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-13 12:58:30.291  1032  1390 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-13 12:58:30.291  1032  1390 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-13 12:58:30.291  1032  6625 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-13 12:58:30.291  1032  1390 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
09-13 12:58:30.293  1032  1772 V SIM_STK : Menu title from STK is T-Mobile
09-13 12:58:30.293  1032  1772 V SIM_STK : Menu title from STK is T-Mobile
09-13 12:58:30.294  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 12:58:30.294  1032  1032 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-13 12:58:30.295  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 12:58:30.295  1032  1032 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-13 12:58:30.299  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 12:58:30.305  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:30.310  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 12:58:30.311  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 12:58:30.311  6308  6308 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 12:58:30.315  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 12:58:30.321  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 12:58:30.326  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 12:58:30.332  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 12:58:30.333  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 12:58:30.333  6308  6308 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 12:58:30.335  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 12:58:30.340  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 12:58:30.345  1032  1048 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-13 12:58:30.345  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-13 12:58:30.345  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-13 12:58:30.345  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-13 12:58:30.345  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-13 12:58:30.345  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-13 12:58:30.345  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 12:58:30.345  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-13 12:58:30.345  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-13 12:58:30.345  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-13 12:58:30.345  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 12:58:30.345  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-13 12:58:30.345  3826  3826 D A2dpStateMachine: make
09-13 12:58:30.347  3826  3826 I bluedroid-qcom: get_profile_interface a2dp
09-13 12:58:30.347  3826  6627 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-13 12:58:30.347  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:30.348  3826  3826 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-13 12:58:30.348  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:30.348  3826  6626 D A2dpStateMachine: Enter Disconnected: -2
09-13 12:58:30.351  3826  3826 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 12:58:30.351  3826  3826 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 12:58:30.351  3826  3826 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:30.351  3826  3826 V BluetoothPbapReceiver: ***********state = 11
,09-13 12:58:30.354  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 12:58:30.355  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 12:58:30.355  3826  3826 D HidService: Received start request. Starting profile...
,09-13 12:58:30.355  3826  3826 I bluedroid-qcom: get_profile_interface hidhost
09-13 12:58:30.355  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:30.355  3826  6621 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-13 12:58:30.355  3826  6621 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-13 12:58:30.355  3826  6621 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-13 12:58:30.355  3826  3826 D HealthService: Received start request. Starting profile...
09-13 12:58:30.355  6308  6308 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 12:58:30.356  2180  2180 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 12:58:30.357  3826  3826 I bluedroid-qcom: get_profile_interface health
09-13 12:58:30.357  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:30.358  3826  3826 D PanService: Received start request. Starting profile...
09-13 12:58:30.358  3826  3826 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 12:58:30.358  3826  3826 I bluedroid-qcom: get_profile_interface pan
09-13 12:58:30.360  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:30.360  3826  3826 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 12:58:30.360  3826  3826 D BtGatt.GattService: Received start request. Starting profile...
09-13 12:58:30.360  3826  3826 D BtGatt.GattService: start()
09-13 12:58:30.360  3826  3826 D BtGatt.AdvertiseManager: advertise manager created
09-13 12:58:30.365  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:30.365  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:30.365  3826  3826 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-13 12:58:30.365  3826  3826 V BluetoothMapService: BluetoothMapBinder()
,09-13 12:58:30.367  3826  3826 D BluetoothMapService: Received start request. Starting profile...
09-13 12:58:30.367  3826  3826 D BluetoothMapService: start()
09-13 12:58:30.371  3826  3826 D BluetoothMapEmailSettingsLoader: Found 0 applications
,09-13 12:58:30.371  3826  3826 D BluetoothMapEmailAppObserver: createReceiver()
09-13 12:58:30.374  3826  3826 D BluetoothMapEmailAppObserver: initObservers()
09-13 12:58:30.374  3826  3826 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-13 12:58:30.374  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:30.376  6285  6285 D BluetoothPermissionRequest: onReceive
09-13 12:58:30.377  3826  3826 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 12:58:30.379  3826  3826 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-13 12:58:30.382  3826  3826 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 12:58:30.382  6285  6285 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 12:58:30.384  3826  3826 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-13 12:58:30.384  3826  3826 V PanService: [BTUI] SIM Extra State :ABSENT
09-13 12:58:30.386  3826  3826 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-13 12:58:30.386  3826  3826 V BluetoothMapService: Handler(): got msg=1
09-13 12:58:30.387  3826  3904 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-13 12:58:30.387  3826  3904 I bluedroid-qcom: enable
09-13 12:58:30.387  3826  3904 I bt_hci_bdroid: init
09-13 12:58:30.387  3826  6633 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-13 12:58:30.387  3826  6633 I bt-btu  : btu_task pending for preload complete event
09-13 12:58:30.389  3826  3904 I bt_vendor: bt-vendor : init
09-13 12:58:30.389  3826  3904 I bt_vendor: bt-vendor : get_bt_soc_type
09-13 12:58:30.389  3826  3904 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-13 12:58:30.389  3826  3904 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-13 12:58:30.389  3826  3904 D bt_userial_mct: userial_init
09-13 12:58:30.389  3826  3904 D bt_hci_bdroid: set_power 1
09-13 12:58:30.389  3826  3904 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-13 12:58:30.389  3826  3904 I bt_vendor: Starting hciattach daemon
09-13 12:58:30.389  3826  3904 I bt_vendor: try to set true
09-13 12:58:30.389  3826  3826 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:30.391  3826  3826 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-13 12:58:30.391  3826  3826 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 12:58:30.391  3826  3826 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 12:58:30.391  3826  3826 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:30.391  3826  3826 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-13 12:58:30.385  6636  6636 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 12:58:30.385  6636  6636 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 12:58:30.419  6637  6637 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-13 12:58:30.494  1032  6625 D DhcpStateMachine: DHCPV4 request on wlan0
,09-13 12:58:30.496  1032  6625 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-13 12:58:30.496  1032  6625 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-13 12:58:30.495  6643  6643 W dhcpcd  : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 12:58:30.495  6643  6643 W dhcpcd  : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 12:58:30.511  6644  6644 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-13 12:58:30.523  6645  6645 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-13 12:58:30.540  6643  6643 I dhcpcd  : version 5.5.6 starting
,09-13 12:58:30.542  6643  6643 E dhcpcd  : get_duid: m
,09-13 12:58:30.542  6643  6643 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-13 12:58:30.542  6643  6643 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-13 12:58:30.547  6647  6647 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
09-13 12:58:30.558  6649  6649 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-13 12:58:30.570  6650  6650 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-13 12:58:30.581  6652  6652 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-13 12:58:30.599  6655  6655 I libmdmdetect: ESOC framework not supported
09-13 12:58:30.599  6655  6655 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-13 12:58:30.605  6655  6655 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-13 12:58:30.605  6655  6655 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-13 12:58:30.605  6655  6655 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-13 12:58:30.605  6655  6655 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-13 12:58:30.605  6655  6655 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-13 12:58:30.605  6655  6655 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-13 12:58:30.605  6655  6655 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-13 12:58:30.612  1032  1772 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 12:58:30.612  1032  1772 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@27ef67df mBinding = false
09-13 12:58:30.613  1032  1094 D BluetoothManagerService: Message: 1
09-13 12:58:30.613  1032  1094 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@27ef67df
09-13 12:58:30.616  3826  6577 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
09-13 12:58:30.616  1032  1094 E BluetoothManagerService: IBluetooth.enable() returned false
09-13 12:58:30.649  3826  3826 V BluetoothOppNotification: previous thread is not finished yet
,09-13 12:58:30.650  6655  6657 E QC-QMI  : qmi_client [6655] 15: failed to locate client data
,09-13 12:58:30.651   450   450 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-13 12:58:30.651   450   450 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
09-13 12:58:30.660  6643  6643 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-13 12:58:30.661  6643  6643 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-13 12:58:30.661  6643  6643 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-13 12:58:30.669  6643  6643 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-13 12:58:30.669  6643  6643 D dhcpcd  : wlan0: sending REQUEST (xid 0x1a31b6d1), next in 4.96 seconds
,09-13 12:58:30.696  6643  6643 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-13 12:58:30.705  6663  6663 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-13 12:58:30.719  6664  6664 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-13 12:58:30.722  6643  6643 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
,09-13 12:58:30.723  6643  6643 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-13 12:58:30.724  6643  6643 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-13 12:58:30.724  6643  6643 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-13 12:58:30.725  6643  6643 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-13 12:58:30.725  6643  6643 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-13 12:58:30.726  6643  6643 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-13 12:58:30.726  6643  6643 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-13 12:58:30.726  1032  1390 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 12:58:30.726  1032  1390 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 12:58:30.727  1032  1390 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 12:58:30.728  1032  1390 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 12:58:30.728  1032  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 12:58:30.729  1032  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 12:58:30.729  1032  1455 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
09-13 12:58:30.750  3826  3904 I bt_vendor: bluetooth satus is on
09-13 12:58:30.750  3826  3904 D bt_hci_bdroid: preload
09-13 12:58:30.750  3826  6635 D bt_userial_mct: userial_open(port:0)
09-13 12:58:30.750  3826  6635 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-13 12:58:30.752  3826  6635 I bt_vendor: Done intiailizing UART
,09-13 12:58:30.754  3826  6635 I bt_vendor: Done intiailizing UART
,09-13 12:58:30.754  3826  6635 I bt_userial_mct: CMD=94, EVT=94, ACL_Out=95, ACL_In=95
09-13 12:58:30.754  3826  6635 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-13 12:58:30.754  3826  6668 D bt_userial_mct: Entering userial_read_thread()
09-13 12:58:30.755  3826  6633 I bt-btu  : btu_task received preload complete event
09-13 12:58:30.755  3826  6633 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-13 12:58:30.755  3826  6633 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-13 12:58:30.755  3826  6633 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-13 12:58:30.760  3826  6633 I         : BTE_InitTraceLevels -- TRC_HCI
09-13 12:58:30.760  3826  6633 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-13 12:58:30.760  3826  6633 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-13 12:58:30.760  3826  6633 I         : BTE_InitTraceLevels -- TRC_AVDT
09-13 12:58:30.760  3826  6633 I         : BTE_InitTraceLevels -- TRC_AVRC
09-13 12:58:30.760  3826  6633 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 12:58:30.760  3826  6633 I         : BTE_InitTraceLevels -- TRC_BNEP
09-13 12:58:30.760  3826  6633 I         : BTE_InitTraceLevels -- TRC_BTM
09-13 12:58:30.760  3826  6633 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-13 12:58:30.760  3826  6633 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 12:58:30.760  3826  6633 I         : BTE_InitTraceLevels -- TRC_PAN
09-13 12:58:30.760  3826  6633 I         : BTE_InitTraceLevels -- TRC_SDP
09-13 12:58:30.760  3826  6633 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 12:58:30.760  3826  6633 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 12:58:30.760  3826  6633 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 12:58:30.760  3826  6633 I         : BTE_InitTraceLevels -- TRC_BTIF
09-13 12:58:30.762  6039  6393 D serial_port: close(fd = 24)
09-13 12:58:30.765  6039  6393 I UEI.SmartControl: Serial port is closed.
,09-13 12:58:30.800  3826  6633 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-13 12:58:30.800  3826  6633 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa021f061 
,09-13 12:58:30.800  3826  6633 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa021f061 
09-13 12:58:30.809  3826  3907 E bt-btif : Calling BTA_HhEnable
09-13 12:58:30.809  3826  3907 E bt-btif : L2CAP - L2CA_Register() called for PSM: 0x0019
09-13 12:58:30.809  3826  6633 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-13 12:58:30.809  3826  6633 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-13 12:58:30.809  3826  6633 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-13 12:58:30.809  3826  6633 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-13 12:58:30.809  3826  6633 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-13 12:58:30.810  3826  3907 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-13 12:58:30.812  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-13 12:58:30.812  3826  3907 D BluetoothAdapterProperties: Name is: G3
09-13 12:58:30.813  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
,09-13 12:58:30.813  3826  3907 D BluetoothAdapterProperties: Scan Mode:20
09-13 12:58:30.814  3826  3907 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 12:58:30.814  3826  3907 D bt_hci_bdroid: postload
09-13 12:58:30.814  3826  6635 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 12:58:30.815  3826  3907 D bte_conf: Device ID record 1 : primary
09-13 12:58:30.815  3826  3907 D bte_conf:   vendorId            = 00c4
09-13 12:58:30.815  3826  3907 D bte_conf:   vendorIdSource      = 0001
09-13 12:58:30.815  3826  3907 D bte_conf:   product             = 13a1
09-13 12:58:30.815  3826  3907 D bte_conf:   version             = 1000
09-13 12:58:30.815  3826  3907 D bte_conf:   clientExecutableURL = 
09-13 12:58:30.815  3826  3907 D bte_conf:   serviceDescription  = 
09-13 12:58:30.815  3826  3907 D bte_conf:   documentationURL    = 
09-13 12:58:30.815  3826  3907 D bte_conf: bte_load_did_conf no section named DID2.
09-13 12:58:30.817  3826  3904 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-13 12:58:30.817  3826  3904 D BluetoothAdapterProperties: ScanMode =  20
09-13 12:58:30.818  3826  6633 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-13 12:58:30.817  3826  3904 D BluetoothAdapterProperties: State =  11
09-13 12:58:30.818  3826  3904 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-13 12:58:30.818  3826  3904 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-13 12:58:30.818  3826  3904 D BluetoothAdapterProperties: Setting state to 12
09-13 12:58:30.818  3826  3904 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-13 12:58:30.819  3826  3904 I BluetoothAdapterState: Entering On State
09-13 12:58:30.820  3826  3904 D LGBluetoothServiceAdapter: [BTUI] OnState
09-13 12:58:30.805  6675  6675 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 12:58:30.820  3826  3904 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-13 12:58:30.820  3826  3904 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-13 12:58:30.820  3826  3904 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-13 12:58:30.805  6675  6675 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 12:58:30.821  3826  6633 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 12:58:30.821  3826  6633 W bt-smp  : Plain text(LSB ~ MSB) = d1 ad 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 12:58:30.822  3826  6633 W bt-smp  : Encrypted text(LSB ~ MSB) = 98 7e 79 ee 74 56 a2 66 b1 95 e2 6e 06 6f bf 63 
09-13 12:58:30.822  3826  6633 W bt-btm  : Stopping oneshot timer
09-13 12:58:30.822  3826  6635 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 12:58:30.822  3826  6635 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 12:58:30.823  3826  6635 D bt_hci_bdroid: Used up Tx Cmd credits
09-13 12:58:30.823  3826  6668 E bt_mct  : hci lib postload completed
09-13 12:58:30.824  3826  3907 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-13 12:58:30.825  3826  3907 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-13 12:58:30.835  3826  6633 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 12:58:30.835  3826  6633 W bt-smp  : Plain text(LSB ~ MSB) = 52 96 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 12:58:30.835  3826  6633 W bt-smp  : Encrypted text(LSB ~ MSB) = aa 11 91 21 f4 52 8f 1b b3 ae 0a ba 3d f3 13 e5 
09-13 12:58:30.835  3826  6633 W bt-btm  : Stopping oneshot timer
09-13 12:58:30.837  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:30.837  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:30.837  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:30.837  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:30.837  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:30.837  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:30.837  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:30.837  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 12:58:30.847  3826  6633 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 12:58:30.847  3826  6633 W bt-smp  : Plain text(LSB ~ MSB) = 29 17 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 12:58:30.847  3826  6633 W bt-smp  : Encrypted text(LSB ~ MSB) = 05 ff a6 81 57 8a 42 fe fe 64 2c 79 4c ec 70 30 
09-13 12:58:30.847  3826  6633 W bt-btm  : Stopping oneshot timer
09-13 12:58:30.849  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:58:30.849  3826  3907 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 12:58:30.849  3826  3907 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,09-13 12:58:30.854  1032  1094 D BluetoothManagerService: Message: 60
09-13 12:58:30.854  1032  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-13 12:58:30.854  1032  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
09-13 12:58:30.854  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:30.854  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:30.854  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:30.854  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:30.854  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:30.854  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:30.854  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:30.854  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:30.856  3826  6633 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 12:58:30.856  3826  6633 W bt-smp  : Plain text(LSB ~ MSB) = 74 fe 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 12:58:30.856  3826  6633 W bt-smp  : Encrypted text(LSB ~ MSB) = 94 fc de 10 a8 b1 9d 1c aa 60 88 e0 fb db 10 e0 
09-13 12:58:30.856  3826  6633 W bt-btm  : Stopping oneshot timer
09-13 12:58:30.857  6285  6561 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 12:58:30.857  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:58:30.865  3826  6633 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-13 12:58:30.865  3826  6633 W bt-smp  : Plain text(LSB ~ MSB) = 84 28 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-13 12:58:30.865  3826  6633 W bt-smp  : Encrypted text(LSB ~ MSB) = 1f eb fe 71 71 d4 ad 95 6b 0b 22 56 da 4d 09 ee 
09-13 12:58:30.865  3826  6633 W bt-btm  : Stopping oneshot timer
,09-13 12:58:30.870  3826  3904 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-13 12:58:30.878  6285  6301 D BluetoothMap: onBluetoothStateChange: up=true
,09-13 12:58:30.899  6684  6684 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,09-13 12:58:30.913  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:30.913  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:30.913  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:30.913  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:30.913  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:30.913  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:30.913  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:30.913  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:30.915  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 12:58:31.007  1032  1954 I art     : Explicit concurrent mark sweep GC freed 83933(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 2.017ms total 142.037ms
,09-13 12:58:31.010  1847  2430 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 12:58:31.011  6285  6285 D BluetoothA2dp: Proxy object connected
09-13 12:58:31.011  6285  6285 D A2dpProfile: Bluetooth service connected
09-13 12:58:31.015  6285  6561 D BluetoothPan: onBluetoothStateChange on: true
09-13 12:58:31.015  6285  6561 D BluetoothPan: onBluetoothStateChange call bindService
09-13 12:58:31.017  6285  6285 D BluetoothMap: Proxy object connected
09-13 12:58:31.017  6285  6285 D MapProfile: Bluetooth service connected
09-13 12:58:31.017  6285  6285 D BluetoothMap: getConnectedDevices()
09-13 12:58:31.019  1847  1847 D BluetoothHeadset: Proxy object connected
09-13 12:58:31.019  3826  3942 V BluetoothMapService: getConnectedDevices()
,09-13 12:58:31.021  6285  6285 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 12:58:31.021  6285  6285 D PanProfile: Bluetooth service connected
09-13 12:58:31.021  6285  6300 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 12:58:31.024  1032  1094 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 12:58:31.024  6285  6285 D BluetoothHeadset: Proxy object connected
09-13 12:58:31.024  6285  6285 D HeadsetProfile: Bluetooth service connected
09-13 12:58:31.024  1032  1032 D BluetoothA2dp: Proxy object connected
09-13 12:58:31.024  1847  2430 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 12:58:31.026  1847  1847 D BluetoothHeadset: Proxy object connected
09-13 12:58:31.026  6285  6561 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 12:58:31.028  1032  1094 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 12:58:31.028  1032  1032 D BluetoothHeadset: Proxy object connected
09-13 12:58:31.029  6285  6285 D BluetoothInputDevice: Proxy object connected
09-13 12:58:31.029  6285  6285 D HidProfile: Bluetooth service connected
09-13 12:58:31.029  6285  6301 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 12:58:31.031  1847  1862 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 12:58:31.033  1847  1847 D BluetoothHeadset: Proxy object connected
09-13 12:58:31.033  1032  1094 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-13 12:58:31.033  1032  1094 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-13 12:58:31.034  1936  1936 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:31.034  1936  2091 D LGBluetoothAPIService: Message: 1
09-13 12:58:31.034  1936  2091 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-13 12:58:31.035  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-13 12:58:31.038  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:31.039  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:31.040  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:31.041  1936  2091 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-13 12:58:31.042  3826  3826 V BtOppService: Receiver BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-13 12:58:31.042  3826  3826 V BtOppService: start RfcommListener
09-13 12:58:31.042  3826  3826 V BtOppService: RfcommListener started
09-13 12:58:31.042  3826  3826 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:31.042  3826  3826 D BluetoothMapService: STATE_ON
09-13 12:58:31.043  3826  3826 D LGBluetoothAPIServer: [BTUI] onCreate()
09-13 12:58:31.043  3826  3826 D LGBluetoothAPIServer: [BTUI] onBind()
09-13 12:58:31.043  6285  6285 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-13 12:58:31.043  3826  3826 V BluetoothMapService: Handler(): got msg=1
09-13 12:58:31.043  1936  1936 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-13 12:58:31.044  1936  2091 D LGBluetoothAPIService: Message: 100
09-13 12:58:31.044  1936  2091 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,09-13 12:58:31.044  3826  3826 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-13 12:58:31.044  3826  6700 V BtOppRfcommListener: Starting RFCOMM listener....
09-13 12:58:31.045  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:31.045  3826  3826 V BluetoothPbapService: Pbap Service onCreate
09-13 12:58:31.045  3826  3826 V BluetoothPbapService: Starting PBAP service
09-13 12:58:31.045  6285  6285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-13 12:58:31.046  1032  1772 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 12:58:31.046  3826  6701 D BluetoothMapMasInstance: MAS initSocket()
09-13 12:58:31.046  3826  6701 D BluetoothMapMasInstance:   masId = 00
09-13 12:58:31.046  3826  6701 D BluetoothMapMasInstance:   msgTypes = 0e
09-13 12:58:31.046  3826  6701 D BluetoothMapMasInstance:   masName = SMS/MMS
09-13 12:58:31.046  3826  6701 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-13 12:58:31.046  3826  3826 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-13 12:58:31.046  3826  3826 V BluetoothPbapService: Pbap Service onBind
09-13 12:58:31.047  1032  1899 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 12:58:31.048  3826  6700 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 12:58:31.049  3826  3826 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:31.049  3826  3826 V BluetoothPbapService: state: 12
09-13 12:58:31.049  3826  3826 V BluetoothPbapService: Handler(): got msg=1
09-13 12:58:31.049  3826  3826 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-13 12:58:31.050  3826  3826 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-13 12:58:31.050  3826  3826 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:31.050  3826  3826 V BluetoothPbapReceiver: ***********state = 12
09-13 12:58:31.050  3826  6703 V BluetoothPbapService: Pbap Service initSocket
09-13 12:58:31.050  3826  6701 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 12:58:31.051  1032  2027 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 12:58:31.051  3826  6700 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=99 mFd=84
09-13 12:58:31.051  3826  6700 V BtOppRfcommListener: Started RFCOMM listener....
09-13 12:58:31.051  3826  6700 I BtOppRfcommListener: Accept thread started.
09-13 12:58:31.051  3826  6700 V BtOppRfcommListener: Accepting connection...
09-13 12:58:31.053  3826  3907 D BluetoothAdapterProperties: Scan Mode:21
09-13 12:58:31.053  3826  3907 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-13 12:58:31.054  3826  6703 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 12:58:31.055  3826  6701 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=101 mFd=99
,09-13 12:58:31.055  3826  6701 V BluetoothMapMasInstance: Succeed to create listening socket 
09-13 12:58:31.055  3826  6701 D BluetoothMapMasInstance: Accepting socket connection...
09-13 12:58:31.056  2180  2180 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 12:58:31.057  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:31.058  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:31.058  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:31.059  3826  6703 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=103 mFd=101
09-13 12:58:31.059  2180  2180 D c       : Getting all permits...
09-13 12:58:31.059  2180  2180 D a       : Opening database...
09-13 12:58:31.059  3826  6703 V BluetoothPbapService: Succeed to create listening socket 
09-13 12:58:31.059  3826  6703 V BluetoothPbapService: Accepting socket connection...
09-13 12:58:31.060  6285  6285 D DockEventReceiver: finishStartingService: stopping service
09-13 12:58:31.061  6285  6285 D BluetoothPbap: Proxy object connected
09-13 12:58:31.061  6285  6285 D PbapServerProfile: Bluetooth service connected
09-13 12:58:31.064  2180  2180 D a       : Opening database auth.proximity.permit_store...
09-13 12:58:31.065  2180  2180 D a       : Closing database...
09-13 12:58:31.072  6285  6285 D BluetoothPermissionRequest: onReceive
,09-13 12:58:31.074  6285  6285 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-13 12:58:31.075  6285  6285 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-13 12:58:31.078  3826  3826 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-13 12:58:31.079  3826  3826 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-13 12:58:31.079  3826  3826 V BtOppService: onStartCommand
09-13 12:58:31.080  3826  3826 V BtOppService: Starting RfcommListener
09-13 12:58:31.082  3826  6704 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-13 12:58:31.082  3826  6704 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-13 12:58:31.082  3826  3826 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:31.082  3826  3826 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-13 12:58:31.082  3826  6704 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30b17c35 on behalf of 
09-13 12:58:31.083  3826  3826 V BtOppService: start RfcommListener
09-13 12:58:31.083  3826  3826 V BtOppService: RfcommListener started
09-13 12:58:31.084  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
,09-13 12:58:31.084  3826  3826 V BluetoothFtpService: Ftp Service onCreate
09-13 12:58:31.084  3826  3826 I BluetoothFtpService: Ftp Service onCreate
09-13 12:58:31.084  3826  3826 V BluetoothFtpService: Ftp Service onStartCommand
09-13 12:58:31.084  3826  3826 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:31.084  3826  3826 V BluetoothFtpService: Starting Listening on sockets
09-13 12:58:31.084  3826  3826 V BluetoothFtpService: Handler(): got msg=1
09-13 12:58:31.084  3826  3826 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-13 12:58:31.084  3826  3826 V BluetoothFtpService: Ftp Service initSocket
09-13 12:58:31.084  3826  6704 V BluetoothOppNotification: update too frequent, put in queue
09-13 12:58:31.084  1032  1990 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 12:58:31.085  3826  6704 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,09-13 12:58:31.085  3826  3826 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 12:58:31.086  3826  3826 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=105 mFd=103
09-13 12:58:31.086  3826  3826 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-13 12:58:31.086  3826  3826 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-13 12:58:31.086  3826  3826 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-13 12:58:31.086  3826  3826 V BluetoothSapReceiver: SapReceiver onReceive 
09-13 12:58:31.086  3826  3826 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:31.087  3826  3826 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-13 12:58:31.087  3826  3826 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-13 12:58:31.087  3826  6705 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-13 12:58:31.088  3826  3826 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20b2aef4
09-13 12:58:31.088  3826  3826 V BluetoothSapService: Sap Service onCreate
09-13 12:58:31.090  3826  3826 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:58:31.090  3826  3826 V BluetoothSapService: state: 12
09-13 12:58:31.090  3826  3826 V BluetoothSapService: Starting SAP server process
09-13 12:58:31.091  3826  3826 V BluetoothSapService: SAP Service startRfcommListenerThread
09-13 12:58:31.092  3826  6707 V BluetoothSapService: Sap Service initRfcommSocket
09-13 12:58:31.085  6706  6706 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 12:58:31.085  6706  6706 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 12:58:31.094  1032  1047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 12:58:31.095  3826  6707 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 12:58:31.096  3826  6707 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=107 mFd=105
09-13 12:58:31.096  3826  6707 V BluetoothSapService: Succeed to create listening socket 
09-13 12:58:31.096  3826  6707 V BluetoothSapService: Accepting socket connection...
09-13 12:58:31.099  6706  6706 V BT_SAP  : Event pipe created
09-13 12:58:31.099  6706  6706 V BT_SAP  : create_server_socket qcom.sap.server
09-13 12:58:31.099  6706  6706 V BT_SAP  : created socket fd 6
,09-13 12:58:31.102  1032  6625 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-13 12:58:31.103  1032  6625 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-13 12:58:31.103  1032  6625 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-13 12:58:31.104  1032  6625 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-13 12:58:31.104  1032  6625 V LgDhcpStateMachineHelper: Add DhcpResults: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-13 12:58:31.104  1032  6625 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-13 12:58:31.104  1032  6625 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: true
09-13 12:58:31.104  1032  6625 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-13 12:58:31.104  1032  6625 D DhcpStateMachine: RunningState
09-13 12:58:31.104  1032  1390 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-13 12:58:31.105  1032  1390 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-13 12:58:31.105  1032  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 12:58:31.105  1032  1387 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:31.105  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:31.105  6388  6388 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 12:58:31.105  1032  1390 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 12:58:31.105  1032  1390 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-13 12:58:31.106  6388  6388 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-13 12:58:31.106  1032  1390 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-13 12:58:31.106  1032  1390 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 12:58:31.115  6160  6597 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:31.115  6160  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:31.115  6160  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:31.115  6160  6597 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:31.115  6160  6597 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:31.115  6160  6597 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:31.115  6160  6597 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:31.115  6160  6597 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:31.116  6160  6597 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 12:58:31.118  6160  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:31.119  1032  1935 D WifiServiceImplEx: setWifiEnabled: false pid=6160, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 12:58:31.120  1032  1935 D WifiService: setWifiEnabled: false pid=6160, uid=10118
09-13 12:58:31.120  1032  1935 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 12:58:31.122  1032  1390 D WifiNative-wlan0: SET ps 1: returned true
09-13 12:58:31.123  1032  1455 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
09-13 12:58:31.123  1032  1390 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 12:58:31.124  1032  1390 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 12:58:31.124  1032  1390 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-13 12:58:31.125  1032  1455 D ConnectivityService: ignoring duplicate network state non-change
09-13 12:58:31.128  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:31.128  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:31.128  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,09-13 12:58:31.134  1032  1455 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-13 12:58:31.136  1032  1455 D ConnectivityService: Adding iface wlan0 to network 100
09-13 12:58:31.137  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:31.137  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:31.137  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-13 12:58:31.139  1032  1390 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-13 12:58:31.140  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 12:58:31.140  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 12:58:31.140  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-13 12:58:31.141  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-13 12:58:31.143  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 12:58:31.145  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 12:58:31.145  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 12:58:31.149  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:31.149  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:31.149  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-13 12:58:31.150  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-13 12:58:31.152  1936  1936 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-13 12:58:31.152  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 12:58:31.158  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 12:58:31.158  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 12:58:31.162  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:31.162  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:31.163  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-13 12:58:31.163  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:31.167  1032  1727 D WifiServiceImplEx: setWifiEnabled: false pid=6160, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 12:58:31.167  1032  1727 D WifiService: setWifiEnabled: false pid=6160, uid=10118
09-13 12:58:31.167  1032  1727 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 12:58:31.168  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-13 12:58:31.170  1599  1599 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-13 12:58:31.171  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:31.173  1032  1455 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-13 12:58:31.173  1032  1455 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
09-13 12:58:31.173  1032  1390 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-13 12:58:31.174  1032  1390 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-13 12:58:31.174  1032  1455 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
09-13 12:58:31.174  1032  1390 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-13 12:58:31.175  1032  1390 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-13 12:58:31.175  1032  1390 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-13 12:58:31.175  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 12:58:31.175  1032  1455 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
09-13 12:58:31.175  1032  1390 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-13 12:58:31.175  1032  1390 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 12:58:31.175  1032  1390 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,09-13 12:58:31.176  1032  1390 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 12:58:31.176  1032  1390 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 12:58:31.176  1032  1455 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-13 12:58:31.176  1032  1455 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
09-13 12:58:31.176  1032  1455 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
09-13 12:58:31.178  1032  1455 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-13 12:58:31.178  1032  1455 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-13 12:58:31.178  1032  1455 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
09-13 12:58:31.178  1032  1455 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
09-13 12:58:31.179  1032  6624 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:31.179  1032  6624 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-13 12:58:31.179  1032  6624 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:31.180  1032  6624 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-13 12:58:31.182  1032  1455 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 12:58:31.182  1032  1455 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 12:58:31.182  1032  1455 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 12:58:31.182  1032  1455 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 12:58:31.182  1032  1455 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-13 12:58:31.182  1032  1455 D ConnectivityService: currentScore = 0, newScore = 20
09-13 12:58:31.183  1032  1455 D ConnectivityService:    accepting network in place of null
09-13 12:58:31.183  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 12:58:31.183  1032  1455 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 12:58:31.183  1599  1599 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-13 12:58:31.183  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:31.183  1032  1455 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
09-13 12:58:31.183  1847  1847 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 12:58:31.183  1847  1847 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 12:58:31.185   308  6713 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
,09-13 12:58:31.187  1032  1455 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-13 12:58:31.187  1032  1455 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-13 12:58:31.187  1032  1455 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 12:58:31.188  1032  1390 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 12:58:31.188  1032  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 12:58:31.189  6388  6388 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 12:58:31.189  1032  1387 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:31.189  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:31.190  1032  1032 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-13 12:58:31.190  1032  1390 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 12:58:31.190  1032  1390 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 12:58:31.190  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 12:58:31.190  1032  1390 D WifiNative-wlan0: SET ps 1: returned true
09-13 12:58:31.190  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 12:58:31.190   308  6714 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 12:58:31.190  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 12:58:31.190  1032  1032 D LocSvc_java: Sending msg: 5 arg1:0 arg2:1
09-13 12:58:31.190  1032  6625 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:31.190   308  6714 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
09-13 12:58:31.191   308  6714 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
09-13 12:58:31.191  1032  1455 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 12:58:31.191  1032  1455 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-13 12:58:31.192   308   890 D CommandListener: Clearing all IP addresses on wlan0
09-13 12:58:31.193  1032  1092 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-13 12:58:31.195  1032  1455 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{tr,ue} explicitlySelected{false} }
09-13 12:58:31.202  1032  1386 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-13 12:58:31.204   308  6716 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-13 12:58:31.205  1032  6715 D LocSvc_java: requestTime failed
09-13 12:58:31.205  1032  6715 D LocSvc_java: Sending msg: 10 arg1:0 arg2:1
09-13 12:58:31.205  1032  1092 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-13 12:58:31.208  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:31.211  1032  1455 D ConnectivityService: validation of new default Network = false
09-13 12:58:31.211  1032  1455 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-13 12:58:31.211  1032  1455 D DSQN    : enableDataServiceNotify 
09-13 12:58:31.211  1032  1455 D DSQN    : start dsqn bin
09-13 12:58:31.215  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 12:58:31.215  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 12:58:31.216  1032  1390 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 12:58:31.216  1032  1387 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:31.216  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:31.216  1032  1387 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@360e7ebd
09-13 12:58:31.217  1032  1390 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 12:58:31.217  1032  1390 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 12:58:31.217  1032  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 12:58:31.218  1032  1455 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
09-13 12:58:31.218  1032  1455 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 12:58:31.218  1032  1455 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 12:58:31.219  1032  1455 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 12:58:31.219  1032  1455 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-13 12:58:31.219  1032  1455 D ConnectivityService: ignoring duplicate network state non-change
09-13 12:58:31.219  1032  1455 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
09-13 12:58:31.205  6717  6717 W dsqn    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 12:58:31.205  6717  6717 W dsqn    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 12:58:31.220  1599  2066 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 12:58:31.223  1032  1032 D WifiHS20: hidePasspointNotification off =false
09-13 12:58:31.223  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:31.223  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:31.223  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 12:58:31.223  1032  1032 D WifiHS20: hidePasspointNotification off =false
09-13 12:58:31.224  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:31.224  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:31.224  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 12:58:31.224  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 1
09-13 12:58:31.224  1032  1032 D RttService: SCAN_AVAILABLE : 1
09-13 12:58:31.225  1936  1936 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-13 12:58:31.225  1032  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 12:58:31.225  1032  1390 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 12:58:31.225  1032  1390 E WifiStateMachine:  SupplicantSta,rtedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 12:58:31.226  1032  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 12:58:31.226  1032  1390 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-13 12:58:31.227  1032  1552 D WifiScanningService: DefaultState got{ when=-3ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 12:58:31.228  1032  1553 D RttService: EnabledState got{ when=-3ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:31.232  6717  6717 E DSQN    : DSQN ssw
09-13 12:58:31.232  1032  1387 D LGWifiP2pService: P2pDisablingState
09-13 12:58:31.232  1032  1387 D LGWifiP2pService: P2pDisablingState{ when=-16ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:31.232  1032  1387 D LGWifiP2pService: p2p socket connection lost
09-13 12:58:31.232  1032  1387 D LGWifiP2pService: P2pDisabledState
09-13 12:58:31.233  1032  1390 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-13 12:58:31.233  1032  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 12:58:31.233  1032  1387 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:31.233  1032  1387 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:31.233  6388  6388 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 12:58:31.233  1032  1390 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 12:58:31.233  1032  1390 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 12:58:31.233  1032  1390 D WifiNative-wlan0: SET ps 1: returned true
09-13 12:58:31.236  6308  6308 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 12:58:31.237  1936  1936 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 12:58:31.237  1936  1936 D WfdsService: WifiP2pState is changed : false
09-13 12:58:31.237  1936  2261 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-13 12:58:31.237  1936  2261 D WfdsService: Set the WFDS Monitor: false
09-13 12:58:31.238  1936  2261 D WfdsMonitor: WFDS Monitor is stopped
09-13 12:58:31.238  1936  2261 D WfdsService: STATE : WfdsDisabledState - enter
09-13 12:58:31.238  1936  2276 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-13 12:58:31.238  1936  6408 D CtrlSupplicant: Received on exit socket, terminate
09-13 12:58:31.238  1936  6408 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-13 12:58:31.238  1936  6408 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-13 12:58:31.238  1936  6408 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-13 12:58:31.239  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 12:58:31.241  1936  2261 W WfdsService: DefaultState - msg [9445378] is not handled
09-13 12:58:31.250  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 12:58:31.255  1599  1599 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 12:58:31.256  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:31.256  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:31.257  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:31.257  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 12:58:31.257  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 12:58:31.258  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:31.260   308   890 D CommandListener: Clearing all IP addresses on wlan0
09-13 12:58:31.260  1032  1455 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-13 12:58:31.260  1032  1455 D DSQN    : disableDataServiceNotify
09-13 12:58:31.260  1032  1455 D DSQN    : stop dsqn bin
09-13 12:58:31.260  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 12:58:31.260  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 12:58:31.262  1032  1390 D WifiNative-p2p0: doBoolean: TERMINATE
09-13 12:58:31.262  1032  1390 D WifiNative-p2p0: TERMINATE: returned true
09-13 12:58:31.262  1032  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 12:58:31.262  1032  1390 E WifiStateMachine: useWiFiOffloading() : false
09-13 12:58:31.262  1032  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 12:58:31.262  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 12:58:31.263  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 12:58:31.263  1032  1032 D WifiHS20: hidePasspointNotification off =false
09-13 12:58:31.263  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:31.263  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:31.263  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 12:58:31.264  1936  1936 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-13 12:58:31.265  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-13 12:58:31.266  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 12:58:31.266  1032  1032 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-13 12:58:31.266  6308  6308 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 12:58:31.267  1032  1455 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-13 12:58:31.268  1032  1455 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 12:58:31.268  1032  1455 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 12:58:31.268  1032  1455 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 12:58:31.268  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 12:58:31.268  1032  1455 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-13 12:58:31.268  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:31.269  1032  1455 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-13 12:58:31.269  1032  1455 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-13 12:58:31.269  1032  1455 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 12:58:31.269  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:31.269  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:31.269  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:31.269  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 12:58:31.269  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:31.269  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:31.269  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:31.269  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 12:58:31.269  1599  2066 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-13 12:58:31.270  1032  1455 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 12:58:31.270  1032  1455 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 12:58:31.270  1032  1455 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 12:58:31.270  1032  1455 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 12:58:31.270  1032  1455 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 12:58:31.271  1032  1455 D NetworkManagementService: Removing idletimer
09-13 12:58:31.271  1032  1455 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:31.271  1032  1390 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=,1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 12:58:31.271  1032  1390 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 12:58:31.271  1032  1386 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-13 12:58:31.271  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:58:31.272  6263  6263 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-13 12:58:31.272  1032  1032 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-13 12:58:31.273  1847  1847 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 12:58:31.273  1847  1847 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 12:58:31.273  1032  1386 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-13 12:58:31.274  1032  1032 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-13 12:58:31.275  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 12:58:31.275  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 12:58:31.275  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 12:58:31.275  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 12:58:31.275  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 12:58:31.275  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 12:58:31.276  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:31.276  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:31.276  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:31.276  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 12:58:31.276  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:31.276  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:31.276  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:31.276  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 12:58:31.277  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 12:58:31.278  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:31.278  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:31.278  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:31.278  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 12:58:31.278  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:31.278  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:31.278  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:31.278  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:31.279  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:58:31.280  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-13 12:58:31.280  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 12:58:31.281  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:31.283  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:31.284  1032  1442 D WifiService: New client listening to asynchronous messages
09-13 12:58:31.284  6263  6263 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 12:58:31.286  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 12:58:31.291  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:31.296  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 12:58:31.296  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 12:58:31.297  6308  6308 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-13 12:58:31.298  6308  6308 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 12:58:31.298  6308  6308 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-13 12:58:31.301  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 12:58:31.304  6263  6263 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-13 12:58:31.305  6263  6263 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 12:58:31.308  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 12:58:31.312  6388  6388 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-13 12:58:31.312  6388  6388 I wpa_supplicant: monitor socket send errors count : 1
09-13 12:58:31.312  6388  6388 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1936-4\x00 that cannot receive messages
09-13 12:58:31.312  1032  6407 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-13 12:58:31.313  1032  6407 D WifiMonitor: Dropping event because (p2p0) is stopped
,09-13 12:58:31.313  1599  1599 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 12:58:31.314  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:31.314  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:31.315  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:31.319  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 12:58:31.319  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 12:58:31.319  6308  6308 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-13 12:58:31.320  6308  6308 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 12:58:31.320  6308  6308 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-13 12:58:31.323  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 12:58:31.326  6263  6263 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-13 12:58:31.326  6263  6263 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 12:58:31.326  6263  6263 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 12:58:31.328  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 12:58:31.332  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:31.336  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 12:58:31.336  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 12:58:31.337  6308  6308 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-13 12:58:31.340  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 12:58:31.341  1599  1599 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 12:58:31.342  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:31.343  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:31.344  6263  6263 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 12:58:31.344  6263  6263 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 12:58:31.344  6263  6263 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 12:58:31.347  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 12:58:31.349  6388  6388 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 12:58:31.349  1032  6407 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-13 12:58:31.349  1032  6407 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 12:58:31.349  1032  6407 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 12:58:31.350  1032  6407 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-13 12:58:31.350  6388  6388 W wpa_supplicant: USIM:  scard_deinit function
09-13 12:58:31.350  1032  6407 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 12:58:31.350  1032  6407 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 12:58:31.350  1032  1390 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=204446
09-13 12:58:31.351  1032  1390 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=204447
09-13 12:58:31.351  1032  1390 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=204447  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 12:58:31.351  1032  1390 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=204447  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-13 12:58:31.352  1032  1094 D Tethering: InitialState.processMessage what=4
09-13 12:58:31.353  1032  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 12:58:31.353  1032  1390 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-13 12:58:31.354  1032  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 12:58:31.354  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:31.359  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 12:58:31.359  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 12:58:31.360  6308  6308 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 12:58:31.362  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 12:58:31.365  6263  6263 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-13 12:58:31.365  6263  6263 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 12:58:31.365  6263  6263 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 12:58:31.369  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 12:58:31.372  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:31.376  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 12:58:31.377  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 12:58:31.377  6308  6308 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 12:58:31.382  6263  6263 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 12:58:31.386  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 12:58:31.390  6333  6726 W FormManager: Network not available. Please check & try again.
09-13 12:58:31.390  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:31.397  6333  6727 V FormManager: Network unavailable.
,09-13 12:58:31.400  1032  6625 D DhcpStateMachine: StoppedState
09-13 12:58:31.400  1032  6625 D DhcpStateMachine: StoppedState{ when=-167ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:31.402  1032  1390 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-13 12:58:31.402  6388  6388 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-13 12:58:31.402  1032  1390 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-13 12:58:31.402  1032  6407 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-13 12:58:31.403  1032  6407 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-TERMINATING 
09-13 12:58:31.403  1032  6407 D WifiMonitor: Disconnecting from the supplicant, no more events
09-13 12:58:31.403  1032  1390 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 42 0
09-13 12:58:31.407  6333  6727 V FormManager: Network unavailable.
09-13 12:58:31.410  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,09-13 12:58:31.410  6285  6285 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 12:58:31.410  6285  6285 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 12:58:31.410  6285  6285 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 12:58:31.412  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 12:58:31.415  6285  6285 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 12:58:31.415  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 12:58:31.415  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 12:58:31.415  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 12:58:31.415  6285  6285 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 12:58:31.415  6285  6285 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 12:58:31.507  1936  1936 D WfdsService: Supplicant Connection state is changed : false
09-13 12:58:31.507  1936  2261 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-13 12:58:31.508  1936  2261 D WfdsService: Set the WFDS Monitor: false
09-13 12:58:31.508  1936  2261 D WfdsMonitor: WFDS Monitor is stopped
,09-13 12:58:31.512  1032  1390 D WifiOffDelayIfNotUsed: stopMonitoring
09-13 12:58:31.512  1032  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 12:58:31.512  1032  1390 E WifiStateMachine: useWiFiOffloading() : false
09-13 12:58:31.512  1032  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 12:58:31.513  4265  4265 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 12:58:31.514  4265  4265 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 12:58:31.517  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:31.519  1936  1936 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-13 12:58:31.522  2491  2491 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 12:58:31.528  4265  4265 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 12:58:31.529  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:31.529  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:31.529  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:31.529  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 12:58:31.529  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:31.529  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:31.529  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:31.529  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:31.541  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:31.541  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:31.541  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:31.541  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 12:58:31.541  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:31.541  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:31.541  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:31.541  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:31.542  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
,09-13 12:58:31.542  1032  1439 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-13 12:58:31.542  1032  1439 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-13 12:58:31.543  4265  4265 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 12:58:31.548  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:31.552  4265  6728 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 12:58:31.554  4265  6729 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 12:58:31.554  4265  6729 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-13 12:58:31.568  6263  6263 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-13 12:58:31.568  6263  6263 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-13 12:58:31.568  6263  6263 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 12:58:31.575  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-13 12:58:31.580  6333  6731 W FormManager: Network not available. Please check & try again.
,09-13 12:58:31.584  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 12:58:31.584  6333  6732 V FormManager: Network unavailable.
09-13 12:58:31.590  6333  6732 V FormManager: Network unavailable.
09-13 12:58:31.651  3826  3826 V BluetoothOppNotification: new notify threadi!
09-13 12:58:31.652  3826  3826 V BluetoothOppNotification: send delay message
,09-13 12:58:31.656  3826  6733 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-13 12:58:31.659  3826  6733 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17391796 on behalf of 
09-13 12:58:31.660  3826  6733 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-13 12:58:31.664  3826  6733 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-13 12:58:31.667  3826  6733 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1c82ef17 on behalf of 
,09-13 12:58:31.668  3826  6733 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-13 12:58:31.675  3826  6733 V BluetoothOppNotification: outbound notification was removed.
09-13 12:58:31.675  3826  6733 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-13 12:58:31.677  6160  6710 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:31.677  6160  6710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:31.677  6160  6710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:31.677  6160  6710 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 12:58:31.677  6160  6710 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:31.677  6160  6710 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:31.677  6160  6710 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:31.677  6160  6710 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:31.678  3826  6733 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b62ff04 on behalf of 
09-13 12:58:31.682  6160  6710 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:58:31.682  3826  6733 V BluetoothOppNotification: inbound: succ-0  fail-0
09-13 12:58:31.685  3826  6733 V BluetoothOppNotification: inbound notification was removed.
,09-13 12:58:31.685  3826  6733 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-13 12:58:31.687  6160  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:31.688  3826  6733 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f1fced on behalf of 
09-13 12:58:31.689  1032  1990 D WifiServiceImplEx: setWifiEnabled: true pid=6160, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 12:58:31.691  1032  1990 D WifiService: setWifiEnabled: true pid=6160, uid=10118
09-13 12:58:31.691  1032  1990 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 12:58:31.719  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-13 12:58:31.720  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-13 12:58:31.720  1032  1032 D Ulp_jni : JNI:system_update. Event-4
09-13 12:58:31.720  1032  1390 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-13 12:58:31.720  1032  1390 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-13 12:58:31.723  1032  1390 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-13 12:58:31.723  1032  1390 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-13 12:58:31.723  1032  1390 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-13 12:58:31.724  1032  1390 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-13 12:58:31.724  1032  1390 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-13 12:58:31.724  1032  1390 E WifiHW  : unknown target_country: EU , set to default
09-13 12:58:31.724  1032  1390 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-13 12:58:31.724  1032  1390 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-13 12:58:31.724  1032  1390 I WifiUtil: gEnableBmps=1
09-13 12:58:31.725  1032  2026 D WifiServiceImplEx: setWifiEnabled: true pid=6160, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 12:58:31.727  1032  2026 D WifiService: setWifiEnabled: true pid=6160, uid=10118
09-13 12:58:31.727  1032  2026 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 12:58:31.728  1032  1442 D WifiController: Mismatch in the state 1
09-13 12:58:32.230  1032  1047 D WifiServiceImplEx: setWifiEnabled: true pid=6160, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-13 12:58:32.236  1032  1047 D WifiService: setWifiEnabled: true pid=6160, uid=10118
09-13 12:58:32.236  1032  1047 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 12:58:32.237  1032  1442 D WifiController: Mismatch in the state 1
09-13 12:58:32.407   308   890 D SoftapController: Softap fwReload - Ok
,09-13 12:58:32.412  1032  1390 E NetdConnector: NDC Command {67 softap fwreload wlan0 STA} took too long (675ms)
09-13 12:58:32.413   308   890 D CommandListener: Setting iface cfg
09-13 12:58:32.414   308   890 D CommandListener: Trying to bring down wlan0
09-13 12:58:32.415  1032  1094 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-13 12:58:32.432   308   890 D CommandListener: Clearing all IP addresses on wlan0
09-13 12:58:32.441  1032  1094 D Tethering: InitialState.processMessage what=4
,09-13 12:58:32.445  1032  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 12:58:32.447  1032  1390 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-13 12:58:32.452  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 12:58:32.452  6285  6285 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 12:58:32.452  6285  6285 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 12:58:32.452  6285  6285 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 12:58:32.454  1032  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 12:58:32.454  1032  1390 E WifiStateMachine: useWiFiOffloading() : false
09-13 12:58:32.454  1032  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-13 12:58:32.445  6752  6752 W wpa_supplicant: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 12:58:32.469  1032  1390 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-13 12:58:32.469  1032  1390 D WifiMonitor: connecting to supplicant
,09-13 12:58:32.465  6752  6752 W wpa_supplicant: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-13 12:58:32.501  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 12:58:32.504  1936  1936 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-13 12:58:32.506  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-13 12:58:32.514  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:58:32.522  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:32.538  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-13 12:58:32.549  6285  6285 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 12:58:32.549  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-13 12:58:32.549  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:32.549  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 12:58:32.549  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 12:58:32.549  6285  6285 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 12:58:32.549  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-13 12:58:32.550  6752  6752 I wpa_supplicant: Successfully initialized wpa_supplicant
09-13 12:58:32.550  6285  6285 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 12:58:32.554  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 12:58:32.554  6285  6285 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 12:58:32.554  6285  6285 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 12:58:32.554  6285  6285 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 12:58:32.555  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-13 12:58:32.555  6285  6285 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 12:58:32.556  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-13 12:58:32.556  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 12:58:32.556  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 12:58:32.556  6285  6285 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 12:58:32.556  6285  6285 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-13 12:58:32.565  6263  6263 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 12:58:32.568  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-13 12:58:32.574  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:32.577  6333  6770 W FormManager: Network not available. Please check & try again.
09-13 12:58:32.586  6333  6771 V FormManager: Network unavailable.
09-13 12:58:32.586  6752  6752 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-13 12:58:32.587  6752  6752 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-13 12:58:32.589  6333  6771 V FormManager: Network unavailable.
09-13 12:58:32.694  6752  6752 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-13 12:58:32.715  6752  6752 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-13 12:58:32.722  6752  6752 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-13 12:58:32.723  1032  1390 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-13 12:58:32.724  1032  1390 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-13 12:58:32.724  1032  1390 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-13 12:58:32.725  1032  1390 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-13 12:58:32.726  1032  1390 E WifiStateMachine:  SupplicantStartingState CMD_START_SUPPLICANT 0 0
09-13 12:58:32.727  1032  1390 E WifiStateMachine:  SupplicantStartingState CMD_START_SUPPLICANT 0 0
09-13 12:58:32.728  1032  1390 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-13 12:58:32.728  1032  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 12:58:32.729  1032  1390 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,09-13 12:58:32.730  1032  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 12:58:32.731  1032  6772 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-13 12:58:32.731  1032  6772 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-13 12:58:32.732  1032  6772 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,09-13 12:58:32.732  1032  6772 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-13 12:58:32.732  1032  1390 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-13 12:58:32.732  1032  1390 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-13 12:58:32.733  1032  1390 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-13 12:58:32.734  1032  1390 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-13 12:58:32.734  1032  1390 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-13 12:58:32.736  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:32.736  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:32.737  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:32.737  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:32.737  1032  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-13 12:58:32.737  1032  1390 E WifiStateMachine: useWiFiOffloading() : false
09-13 12:58:32.737  1032  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-13 12:58:32.737  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 12:58:32.740  1032  1390 D WifiNative-wlan0: doBoolean: SET update_config 1
09-13 12:58:32.741  1936  1936 D WfdService: Waiting for WifiP2p enabling
09-13 12:58:32.742  1032  1390 D WifiNative-wlan0: SET update_config 1: returned true
09-13 12:58:32.742  1032  1390 D WifiConfigStore: Loading config and enabling all networks 
09-13 12:58:32.742  1032  1390 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-13 12:58:32.743  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:32.748  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-13 12:58:32.750  1032  1390 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,09-13 12:58:32.752  1032  1439 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-13 12:58:32.753  6160  6735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:32.753  6160  6735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:32.753  6160  6735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:32.753  6160  6735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:32.753  6160  6735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:32.753  6160  6735 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:32.753  6160  6735 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:32.753  6160  6735 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:32.755  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:32.755  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:32.755  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:32.755  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:32.755  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:32.755  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:32.755  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:32.755  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:32.756  1032  1390 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-13 12:58:32.763  6160  6735 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 12:58:32.765  1032  1390 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-13 12:58:32.766  1032  1390 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-13 12:58:32.768  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 12:58:32.768  6160  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:32.771  6160  6233 D BluetoothAdapter: enable(): BT is already enabled..!
09-13 12:58:32.772  6263  6263 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-13 12:58:32.773  1032  1390 D WifiStateMachine: enableVerboseLogging : level 2
09-13 12:58:32.773  1032  1390 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-13 12:58:32.773  1032  1572 D WifiServiceImplEx: setWifiEnabled: true pid=6160, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-13 12:58:32.773  1032  1390 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-13 12:58:32.773  1032  1390 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-13 12:58:32.773  1032  1572 D WifiService: setWifiEnabled: true pid=6160, uid=10118
09-13 12:58:32.774  1032  1572 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 12:58:32.774  1032  1390 D WifiNative-wlan0: SET manufacturer LGE: returned true
,09-13 12:58:32.774  1032  1390 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-13 12:58:32.774  1032  1390 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-13 12:58:32.774  1032  1390 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-13 12:58:32.775  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:32.775  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:32.775  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:32.775  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:32.775  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:32.775  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:32.775  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:32.775  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:32.778  1032  1390 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-13 12:58:32.778  1032  1390 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-13 12:58:32.778  1032  1390 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-13 12:58:32.778  1032  1390 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-13 12:58:32.779  1032  1390 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-13 12:58:32.779  1032  1390 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-13 12:58:32.779  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-13 12:58:32.779  1032  1390 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-13 12:58:32.779  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 12:58:32.780  1936  1936 D WfdsService: Supplicant Connection state is changed : true
09-13 12:58:32.780  1936  2261 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-13 12:58:32.780  1936  2261 D WfdsService: Set the WFDS Monitor: true
09-13 12:58:32.780  1936  2261 D WfdsMonitor: WfdsMonitorThread create
09-13 12:58:32.781  1936  2261 D WfdsMonitor: WFDS Monitor is created and started
09-13 12:58:32.781  1936  2261 D WfdsService: WiFi: Supplicant connection re-established
09-13 12:58:32.781  1032  1390 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 12:58:32.781  1032  1390 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-13 12:58:32.782  1032  1390 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-13 12:58:32.782  1032  1390 D WifiNative-HAL: Setting external_sim to 1
09-13 12:58:32.782  1032  1390 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-13 12:58:32.782  1936  6779 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-13 12:58:32.782  1032  1390 D WifiNative-wlan0: SET external_sim 1: returned true
09-13 12:58:32.782  1032  1390 I WifiNative-HAL: startHal
09-13 12:58:32.782  1032  1390 D wifi    : setting scan oui 0xaf73c7a0
09-13 12:58:32.783  1936  6779 E CtrlSupplicant: Succeed to open control connection
09-13 12:58:32.783  1936  6779 E CtrlSupplicant: Succeed to open monitor connection
09-13 12:58:32.783  1032  1390 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 12:58:32.783  1032  1390 I WifiNative-HAL: startHal
09-13 12:58:32.783  1032  1390 D wifi    : setting scan oui 0xaf73c7a0
09-13 12:58:32.783  1032  1390 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-13 12:58:32.784  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:32.784  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:32.784  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:32.784  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:32.784  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:32.784  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:58:32.784  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:58:32.784  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:58:32.784  1032  1390 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-13 12:58:32.784  1032  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-13 12:58:32.784  1936  6779 D WfdsMonitor: Supplicant connection established
09-13 12:58:32.784  6752  6752 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-13 12:58:32.784  1936  2261 D WfdsService: Connected to the supplicant for wfds
09-13 12:58:32.785  1032  1390 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-13 12:58:32.785  1032  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 12:58:32.785  6752  6752 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-13 12:58:32.786  1032  1390 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 12:58:32.786  1032  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-13 12:58:32.786  6752  6752 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-13 12:58:32.786  1032  1390 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-13 12:58:32.786  1032  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 12:58:32.786  6752  6752 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 12:58:32.787  1032  1390 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-13 12:58:32.787  6160  6777 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-13 12:58:32.787  1032  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-13 12:58:3,2.787  6160  6777 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-13 12:58:32.787  6752  6752 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-13 12:58:32.787  1032  1390 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-13 12:58:32.787  1032  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-13 12:58:32.787  6752  6752 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-13 12:58:32.787  1032  1390 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-13 12:58:32.787  1032  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-13 12:58:32.788  6752  6752 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-13 12:58:32.788  1032  1390 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-13 12:58:32.788  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:58:32.789  6333  6775 W FormManager: Network not available. Please check & try again.
09-13 12:58:32.789  1032  1390 E WifiNative: : [205,884,114 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-13 12:58:32.789  1032  1390 D WifiNative-wlan0: doBoolean: RECONNECT
09-13 12:58:32.789  1032  1390 D WifiNative-wlan0: RECONNECT: returned true
09-13 12:58:32.789  1032  1390 D WifiNative-wlan0: doString: [STATUS]
09-13 12:58:32.790  1032  6772 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-13 12:58:32.790  1032  6772 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-13 12:58:32.790  1032  1390 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-13 12:58:32.790  1032  1390 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 12:58:32.790  1032  1390 D WifiNative-wlan0: SET ps 1: returned true
09-13 12:58:32.791  1032  1387 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 12:58:32.792  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:32.792   308   890 D CommandListener: Setting iface cfg
09-13 12:58:32.792   308   890 D CommandListener: Trying to bring up p2p0
09-13 12:58:32.793  1032  1390 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-13 12:58:32.794  1032  1390 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-13 12:58:32.794  1032  1390 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-13 12:58:32.794  1032  1390 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-13 12:58:32.795  1032  1390 E WifiStateMachine:  DisconnectedState CMD_START_SUPPLICANT 0 0
09-13 12:58:32.795  6333  6776 V FormManager: Network unavailable.
09-13 12:58:32.795  1032  1390 E WifiStateMachine:  ConnectModeState CMD_START_SUPPLICANT 0 0
09-13 12:58:32.796  1032  1390 E WifiStateMachine:  DriverStartedState CMD_START_SUPPLICANT 0 0
09-13 12:58:32.796  1032  1390 E WifiStateMachine:  SupplicantStartedState CMD_START_SUPPLICANT 0 0
09-13 12:58:32.796  1032  1390 E WifiStateMachine:  DefaultState CMD_START_SUPPLICANT 0 0
09-13 12:58:32.796  1032  1387 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-13 12:58:32.797  1032  1387 D LGWifiP2pService: P2pEnablingState
09-13 12:58:32.797  1032  1387 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:32.797  1032  1387 D LGWifiP2pService: P2p socket connection successful
09-13 12:58:32.797  1032  1387 D LGWifiP2pService: P2pEnabledState
09-13 12:58:32.797  1032  1390 E WifiStateMachine:  DisconnectedState CMD_START_SUPPLICANT 0 0
09-13 12:58:32.797  1032  1390 E WifiStateMachine:  ConnectModeState CMD_START_SUPPLICANT 0 0
09-13 12:58:32.797  6333  6776 V FormManager: Network unavailable.
09-13 12:58:32.798  1032  1390 E WifiStateMachine:  DriverStartedState CMD_START_SUPPLICANT 0 0
09-13 12:58:32.798  1032  1390 E WifiStateMachine:  SupplicantStartedState CMD_START_SUPPLICANT 0 0
09-13 12:58:32.798  1032  1390 E WifiStateMachine:  DefaultState CMD_START_SUPPLICANT 0 0
09-13 12:58:32.799  1032  1390 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-13 12:58:32.800  1032  1390 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-13 12:58:32.800  1032  1390 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-13 12:58:32.800  1032  1390 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-13 12:58:32.801  6752  6752 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-13 12:58:32.801  1032  1387 D LGWifiP2pService: sending p2p connection changed broadcast
09-13 12:58:32.801  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 3
09-13 12:58:32.801  1032  1032 D RttService: SCAN_AVAILABLE : 3
09-13 12:58:32.801  1032  1552 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:32.801  1032  1552 I WifiNative-HAL: startHal
,09-13 12:58:32.801  1032  1552 D wifi    : getting scan capabilities on interface[1] = 0xaf73c7a0
09-13 12:58:32.801  1032  1552 D wifi    : failed to get capabilities : -3
09-13 12:58:32.801  1032  1552 E WifiScanningService: could not get scan capabilities
09-13 12:58:32.801  1032  1390 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-13 12:58:32.802  1032  1553 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:32.802  1032  1390 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-13 12:58:32.802  1032  1390 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-13 12:58:32.802  1032  1390 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-13 12:58:32.802  1936  1936 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-13 12:58:32.802  6752  6752 E wpa_supplicant: disconnect_rssi_lvl: -100
09-13 12:58:32.802  1936  1936 D WfdsService: WifiP2pState is changed : true
09-13 12:58:32.803  1032  1390 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-13 12:58:32.803  1032  1390 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
,09-13 12:58:32.804  1032  1390 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-13 12:58:32.804  1032  1390 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-13 12:58:32.805  6752  6752 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 12:58:32.805  6752  6752 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 12:58:32.806  6752  6752 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 12:58:32.806  6752  6752 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:32.806  6752  6752 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:32.807  1032  6772 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 12:58:32.807  1032  6772 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 12:58:32.807  1032  6772 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 12:58:32.807  1032  6772 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 12:58:32.807  1032  6772 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 12:58:32.807  1032  6772 E WifiMonitor: WifiMonitor:p2p0 cnt=45 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:32.807  1032  6772 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:32.807  1032  6772 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:32.807  1032  6772 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 12:58:32.807  1032  6772 E WifiMonitor: WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:32.808  1032  6772 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:32.808  1032  6772 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:32.808  1032  1390 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-13 12:58:32.809  1032  1390 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-13 12:58:32.809  1032  1390 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-13 12:58:32.809  1032  1390 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-13 12:58:32.809  1032  1390 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-13 12:58:32.810  6752  6752 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-13 12:58:32.810  6752  6752 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 12:58:32.803  1032  1387 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-13 12:58:32.810  1936  2261 D WfdsService: Receive the WFDS_ENABLE Method
09-13 12:58:32.810  1936  2261 D WfdsService: Set the WFDS Monitor: true
09-13 12:58:32.810  1936  2261 D WfdsService: Connected to the supplicant for wfds
09-13 12:58:32.810  1936  2261 D WfdsJNI : doCommand: WFDS_SET TRUE
09-13 12:58:32.810  1936  6779 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 12:58:32.810  1936  6779 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 12:58:32.810  6752  6752 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-13 12:58:32.810  1032  6772 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-13 12:58:32.810  1032  6772 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 12:58:32.810  1936  2261 D WfdsService: selectPreferredScanChannel [36]
09-13 12:58:32.810  1032  6772 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 12:58:32.810  1936  2261 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb,:5d
09-13 12:58:32.810  1032  6772 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-13 12:58:32.811  1032  1390 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-13 12:58:32.811  1032  1390 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-13 12:58:32.812  1032  1387 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-13 12:58:32.812  1032  1387 D WifiNative-p2p0: doBoolean: SET device_name G3
09-13 12:58:32.813  1936  1936 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-13 12:58:32.813  1032  1387 D WifiNative-p2p0: SET device_name G3: returned true
09-13 12:58:32.813  1032  1387 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-13 12:58:32.813  1032  1387 D LGWifiP2pService: before postfix = G3
09-13 12:58:32.813  1032  1387 D WifiServerServiceExt: postfix byte check : 2
09-13 12:58:32.813  1032  1387 D LGWifiP2pService: after postfix = G3
09-13 12:58:32.813  1032  1387 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-13 12:58:32.813  1936  1936 D WfdsService: isConnected: false
09-13 12:58:32.813  1032  1387 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-13 12:58:32.813  1032  1387 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-13 12:58:32.814  1032  1387 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-13 12:58:32.814  1032  1387 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-13 12:58:32.815  1032  1387 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-13 12:58:32.815  1032  1387 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-13 12:58:32.815  1032  1387 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-13 12:58:32.815  1032  1387 D WifiNative-HAL: p2pGetDeviceAddress
09-13 12:58:32.816  1032  1387 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
,09-13 12:58:32.818  1032  1387 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-13 12:58:32.818  1032  1387 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-13 12:58:32.819  1032  1387 D WifiNative-p2p0: P2P_FLUSH: returned true
09-13 12:58:32.819  1032  1387 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-13 12:58:32.819  1032  1390 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-13 12:58:32.819  1032  1390 D WifiNative-wlan0: doBoolean: SCAN
09-13 12:58:32.820  1936  1936 I WfdStateTracker: handleP2pThisDeviceChanged
09-13 12:58:32.820  1936  1936 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-13 12:58:32.820  1936  1936 D WfdsService: Update P2p Interface State: 3
09-13 12:58:32.820  1032  1390 D WifiNative-wlan0: SCAN: returned false
09-13 12:58:32.821  1032  1387 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-13 12:58:32.821  1032  1387 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-13 12:58:32.822  1032  1387 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-13 12:58:32.822  1032  1387 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-13 12:58:32.822  4265  4265 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 12:58:32.822  4265  4265 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 12:58:32.822  1032  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=205917  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 12:58:32.824  4265  4265 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 12:58:32.824  1032  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=205920  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-13 12:58:32.824  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 12:58:32.824  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 12:58:32.825  1032  1390 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 12:58:32.825  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:32.826  1032  1390 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 12:58:32.826  1032  1390 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 12:58:32.827  1032  1390 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-13 12:58:32.827  1032  1390 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,09-13 12:58:32.830  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:32.830  4265  4265 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 12:58:32.830  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:32.830  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 12:58:32.833  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 12:58:32.833  1032  1032 D WifiServerServiceExt: setSupplicantStateSCANNING
09-13 12:58:32.834  1032  1387 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-13 12:58:32.834  1032  1387 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-13 12:58:32.835  1032  1387 D LGWifiP2pService: InactiveState
09-13 12:58:32.835  5069  5069 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-13 12:58:32.835  5069  5069 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-13 12:58:32.835  5069  5069 V [BNRBootReceiver]: Boot Receiver Return
09-13 12:58:32.835  1032  1387 D LGWifiP2pService: InactiveState{ when=-26ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:32.835  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=-26ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:32.835  1032  1387 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-13 12:58:32.835  6752  6752 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-13 12:58:32.836  6752  6752 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 12:58:32.836  1032  6772 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 12:58:32.836  1032  6772 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 12:58:32.836  1032  6772 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 12:58:32.836  1032  6772 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-13 12:58:32.836  6752  6752 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-13 12:58:32.837  6752  6752 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:32.837  1032  1387 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-13 12:58:32.837  1936  6779 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-13 12:58:32.837  1032  1387 D LGWifiP2pService: InactiveState{ when=-16ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:32.837  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=-16ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:32.837  1936  6779 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 12:58:32.837  1032  1387 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:32.837  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:32.837  4265  6780 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 12:58:32.837  1032  1387 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 ,12:58:32.837  6752  6752 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:32.837  1032  1387 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:32.837  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:32.837  1032  1387 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:32.838  1032  1387 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:32.838  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:32.838  1032  1387 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:32.838  1032  1387 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:32.838  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:32.838  1936  6779 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 12:58:32.838  1032  1387 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:32.838  1032  6772 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 12:58:32.838  1032  6772 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:32.838  1032  6772 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:32.838  1032  6772 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:32.838  1032  6772 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-13 12:58:32.838  1032  6772 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:32.838  1032  6772 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:32.838  1032  6772 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 12:58:32.838  1032  1032 E WifiServerServiceExt: No p2p device connected
09-13 12:58:32.839  1936  2261 W WfdsService: DefaultState - msg [9441285] is not handled
,09-13 12:58:32.841  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 12:58:32.846  4265  6781 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-13 12:58:32.846  4265  6781 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 12:58:32.851  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 12:58:32.856  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-13 12:58:32.861  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 12:58:32.862  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 12:58:32.862  6308  6308 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 12:58:33.285  1032  1390 E WifiStateMachine:  DisconnectedState CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:590530757] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,09-13 12:58:33.303  1032  1390 E WifiStateMachine:  ConnectModeState CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:15] from screen [on:0 period:590530772] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 12:58:33.306  1032  1390 E WifiStateMachine:  DriverStartedState CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:6] from screen [on:0 period:590530778] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 12:58:33.308  1032  1390 E WifiStateMachine:  SupplicantStartedState CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:590530780] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 12:58:33.310  1032  1390 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:590530782] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,09-13 12:58:33.322  6160  6777 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-13 12:58:33.323  6160  6777 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 12:58:33.323  6160  6777 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 12:58:33.323  6160  6777 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 12:58:33.324  6160  6777 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-13 12:58:33.326  6160  6792 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-13 12:58:33.326  6160  6792 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 12:58:33.326  6160  6792 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 12:58:33.326  6160  6792 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 12:58:33.326  6160  6792 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-13 12:58:33.333  6752  6752 E wpa_supplicant: USIM:  scard_init function
09-13 12:58:33.334  6752  6752 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-13 12:58:33.337  1032  6772 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-13 12:58:33.337  1032  6772 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-13 12:58:33.337  1032  6772 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-13 12:58:33.337  1032  6772 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: WPS-AP-AVAILABLE 
09-13 12:58:33.337  1032  6772 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-13 12:58:33.337  1032  6772 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-13 12:58:33.337  1032  6772 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-13 12:58:33.340  1032  1390 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-13 12:58:33.340  1032  1390 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
,09-13 12:58:33.347  6160  6796 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 855, name: OutgoingSocketThread/Receiver)
09-13 12:58:33.347  6160  6796 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 855, thread name: OutgoingSocketThread/Receiver)
09-13 12:58:33.347  6160  6796 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 12:58:33.348  6160  6796 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 855, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-13 12:58:33.350  6160  6797 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 856, name: IncomingSocketThread/Sender)
09-13 12:58:33.351  6160  6795 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 854, name: OutgoingSocketThread/Sender)
09-13 12:58:33.352  6160  6798 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 857, name: IncomingSocketThread/Receiver)
09-13 12:58:33.353  6160  6798 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 857, thread name: IncomingSocketThread/Receiver)
09-13 12:58:33.353  6160  6798 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 12:58:33.353  6160  6798 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 857, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-13 12:58:33.354  1032  1390 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-13 12:58:33.354  1032  1390 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-13 12:58:33.355  1032  1390 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,09-13 12:58:33.369  1032  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=206465  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-13 12:58:33.374  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-13 12:58:33.377  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:33.377  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:33.377  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-13 12:58:33.378  1032  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=206474  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-13 12:58:33.379  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 12:58:33.379  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 12:58:33.384  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:33.384  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:33.384  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,09-13 12:58:33.387  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 12:58:33.387  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-13 12:58:33.398  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 12:58:33.403  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 12:58:33.403  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 12:58:33.404  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-13 12:58:33.413  6285  6285 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-13 12:58:33.421  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 12:58:33.431  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 12:58:33.439  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:33.446  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-13 12:58:33.452  6752  6752 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-13 12:58:33.456  1032  6772 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-13 12:58:33.456  1032  6772 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-13 12:58:33.456  1032  6772 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-13 12:58:33.456  1032  6772 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-13 12:58:33.456  1032  6772 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 12:58:33.457  1032  6772 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 12:58:33.460  6752  6752 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 12:58:33.460  6752  6752 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-13 12:58:33.465  1032  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=206560  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-13 12:58:33.466  1032  1094 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-13 12:58:33.470  1032  6772 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 12:58:33.470  1032  6772 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 12:58:33.470  1032  6772 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-13 12:58:33.470  1032  6772 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 12:58:33.470  1032  6772 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 12:58:33.470  1032  6772 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-13 12:58:33.470  1032  6772 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 12:58:33.470  1032  6772 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-13 12:58:33.470  1032  6772 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-13 12:58:33.470  1032  6772 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 12:58:33.471  1032  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=206567  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-13 12:58:33.472  1032  1390 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 55 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206567
09-13 12:58:33.472  1032  1390 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 55 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206568
09-13 12:58:33.472  1032  1390 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 55 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206568
09-13 12:58:33.473  1032  1390 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 55 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206568
09-13 12:58:33.473  1032  1390 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 55 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206569
09-13 12:58:33.474  1032  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=206569  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-13 12:58:33.475   308  6799 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,09-13 12:58:33.480  1032  1092 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-13 12:58:33.490  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 12:58:33.490  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 12:58:33.495  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:33.497  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 12:58:33.501  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:33.503  1032  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=206598  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-13 12:58:33.503  1032  1390 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-13 12:58:33.504  1032  1390 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-13 12:58:33.504  1032  1390 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 12:58:33.505  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 12:58:33.505  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-13 12:58:33.506  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:33.506  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:33.506  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-13 12:58:33.504  1032  1390 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-13 12:58:33.508  1032  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-13 12:58:33.508  6308  6308 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-13 12:58:33.508  1032  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=206604  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-13 12:58:33.509  1032  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=206605  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-13 12:58:33.510  1032  1390 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=206606
09-13 12:58:33.510  1032  1390 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=206606
09-13 12:58:33.511  1032  1390 D WifiNative-wlan0: doString: [STATUS]
09-13 12:58:33.512  1032  6772 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,09-13 12:58:33.512  1032  6772 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-13 12:58:33.512  1032  1390 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-13 12:58:33.514  1032  1390 I WifiServiceExtension: setVHTCapabilityType  : false
09-13 12:58:33.517  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 12:58:33.522  1032  1390 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-13 12:58:33.522  1032  1390 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-13 12:58:33.526  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 12:58:33.530  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:33.530  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:33.530  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-13 12:58:33.534  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:33.534  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 12:58:33.534  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-13 12:58:33.535  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 12:58:33.535  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 12:58:33.537  1032  1390 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-13 12:58:33.537  1032  1390 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 12:58:33.537  1032  1390 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 12:58:33.537  1032  1390 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 12:58:33.537  1032  1390 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 12:58:33.538  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:33.540  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 12:58:33.540  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 12:58:33.541  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:33.541  1032  1455 D ConnectivityService: Got NetworkAgent Messenger
09-13 12:58:33.542  1032  1455 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-13 12:58:33.542  1032  1455 D ConnectivityService: NetworkAgent connected
09-13 12:58:33.542  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 12:58:33.542  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 12:58:33.543  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:33.545  1032  1390 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 12:58:33.545  1032  1390 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 12:58:33.546  1032  1390 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-13 12:58:33.546  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:33.546  1032  1390 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-13 12:58:33.546  1032  1390 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-13 12:58:33.552  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 12:58:33.552  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 12:58:33.553  6308  6308 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 12:58:33.553  1032  1390 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-13 12:58:33.554   308   890 D CommandListener: Setting iface cfg
09-13 12:58:33.558  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-13 12:58:33.558  6285  6285 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-13 12:58:33.558  6285  6285 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-13 12:58:33.558  6285  6285 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-13 12:58:33.559  1032  1390 E WifiStateMachine: Start Dhcp Watchdog 2
09-13 12:58:33.559  1032  6817 D DhcpStateMachine: StoppedState
09-13 12:58:33.559  1032  6817 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:33.559  1032  6817 D DhcpStateMachine: WaitBeforeStartState
09-13 12:58:33.560  1032  1390 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=206655  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 12:58:33.560  1032  1390 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=206656  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 12:58:33.561  1032  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=206656  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 12:58:33.561  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-13 12:58:33.562  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 12:58:33.562  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-13 12:58:33.562  6285  6285 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-13 12:58:33.562  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-13 12:58:33.562  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-13 12:58:33.562  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-13 12:58:33.562  6285  6285 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-13 12:58:33.562  6285  6285 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-13 12:58:33.563  6285  6285 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-13 12:58:33.563  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 12:58:33.563  1032  1032 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-13 12:58:33.565  1032  1390 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=206661  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-13 12:58:33.565  1032  1390 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=206661  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 12:58:33.566  1032  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=206662  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-13 12:58:33.567  1032  1390 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:248] from screen [on:0 period:590531039] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 12:58:33.568  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 12:58:33.568  1032  1032 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-13 12:58:33.568  1032  1390 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:590531040] gl rssi=-45 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 12:58:33.568  1032  1390 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-13 12:58:33.568  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 12:58:33.574  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 12:58:33.576  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:33.577  1032  1390 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 12:58:33.577  1032  1390 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 12:58:33.577  1032  1390 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 12:58:33.578  1032  1390 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 12:58:33.578  1032  1455 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-13 12:58:33.578  1032  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 12:58:33.579  1032  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 12:58:33.579  1032  1455 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-13 12:58:33.580  1032  1390 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=4,0,0
09-13 12:58:33.580  1032  1390 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=4,0,0
09-13 12:58:33.580  1032  1390 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-13 12:58:33.580  6752  6752 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-13 12:58:33.581  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:33.581  1032  1390 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-13 12:58:33.581  1032  1390 D WifiNative-wlan0: doBoolean: SET ps 0
09-13 12:58:33.582  1032  1390 D WifiNative-wlan0: SET ps 0: returned true
09-13 12:58:33.582  1032  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-13 12:58:33.582  6752  6752 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-13 12:58:33.582  1032  1390 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-13 12:58:33.582  1032  1387 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@83863a6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:33.582  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@83863a6 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:33.583  1032  6817 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:33.583  1032  6817 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-13 12:58:33.583  1032  1390 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-13 12:58:33.583  1032  1390 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-13 12:58:33.583  1032  1390 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-13 12:58:33.584   308   890 D CommandListener: Setting iface cfg
09-13 12:58:33.584   308   890 D CommandListener: Trying to bring up wlan0
09-13 12:58:33.584  1032  1390 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-13 12:58:33.587  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 12:58:33.587  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 12:58:33.588  6308  6308 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 12:58:33.589  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 12:58:33.589  1032  1032 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-13 12:58:33.590  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 12:58:33.590  1032  1032 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-13 12:58:33.591  1032  1390 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 12:58:33.591  1032  1390 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 12:58:33.592  1032  1390 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 12:58:33.592  1032  1390 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 12:58:33.593  1032  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 12:58:33.593  1032  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-13 12:58:33.593  1032  1455 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-13 12:58:33.594  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 12:58:33.594  1032  1390 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-13 12:58:33.595  1032  1390 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-13 12:58:33.595  1032  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-13 12:58:33.595  1032  1387 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:33.595  6752  6752 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-13 12:58:33.595  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:33.595  1032  1390 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-13 12:58:33.595  1032  1390 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-13 12:58:33.595  6752  6752 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-13 12:58:33.596  1032  1390 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-13 12:58:33.596  1032  1390 D WifiNative-wlan0: doBoolean: SET ps 1
09-13 12:58:33.600  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 12:58:33.603  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:33.608  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 12:58:33.608  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 12:58:33.608  6308  6308 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 12:58:33.610  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 12:58:33.612  1032  1390 D WifiNative-wlan0: SET ps 1: returned true
09-13 12:58:33.612  1032  1390 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 12:58:33.612  1032  1390 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-13 12:58:33.612  1032  1390 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-13 12:58:33.613  1032  1455 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-13 12:58:33.613  1032  1455 D ConnectivityService: ignoring duplicate network state non-change
09-13 12:58:33.614  1032  1455 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-13 12:58:33.614  1032  1455 D ConnectivityService: Adding iface wlan0 to network 101
09-13 12:58:33.615  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 12:58:33.615  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 12:58:33.616  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:33.618  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:33.618  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:33.618  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-13 12:58:33.622  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:33.622  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:33.622  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-13 12:58:33.624  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-13 12:58:33.626  1936  1936 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-13 12:58:33.627  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:33.627  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:33.627  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-13 12:58:33.627  1032  1390 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-13 12:58:33.628  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-13 12:58:33.631  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:33.632  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:33.632  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-13 12:58:33.637  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 12:58:33.637  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 12:58:33.641  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 12:58:33.642  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:33.644  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 12:58:33.644  1599  1599 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 2
09-13 12:58:33.644  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:33.647  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 12:58:33.647  1599  1599 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 2
09-13 12:58:33.647  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:33.650  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:33.654  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 12:58:33.655  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 12:58:33.655  6308  6308 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 12:58:33.657  1032  1455 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-13 12:58:33.657  1032  1455 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-13 12:58:33.658  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 12:58:33.658  1032  1455 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-13 12:58:33.659   308   890 E Netd    : netlink response contains error (File exists)
09-13 12:58:33.659  1032  1455 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-13 12:58:33.660  1032  1455 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-13 12:58:33.660  1032  1455 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-13 12:58:33.660  1032  1455 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-13 12:58:33.661  1032  1455 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-13 12:58:33.661  1032  1455 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-13 12:58:33.661  1032  1455 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-13 12:58:33.661  1032  1455 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-13 12:58:33.661  1032  1455 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 12:58:33.661  1032  1455 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 12:58:33.661  1032  1455 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 12:58:33.661  1032  6816 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:33.661  1032  6816 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-13 12:58:33.661  1032  1455 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 12:58:33.661  1032  6816 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:33.661  1032  1455 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-13 12:58:33.661  1032  1455 D ConnectivityService: currentScore = 0, newScore = 20
09-13 12:58:33.661  1032  1455 D ConnectivityService:    accepting network in place of null
09-13 12:58:33.661  1032  6816 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-13 12:58:33.661  1032  1455 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 12:58:33.662  1032  1390 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 12:58:33.662  1032  1390 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 12:58:33.662  1847  1847 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 12:58:33.662  1847  1847 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 ,12:58:33.663   308  6823 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-13 12:58:33.665  1032  1455 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-13 12:58:33.665  1032  1455 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-13 12:58:33.665  1032  1455 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 12:58:33.666  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 12:58:33.666  1032  1032 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-13 12:58:33.666  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-13 12:58:33.666  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-13 12:58:33.666  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-13 12:58:33.667  1032  1455 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 12:58:33.667  1032  1455 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-13 12:58:33.668  1032  1455 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-13 12:58:33.669  1032  1455 D ConnectivityService: validation of new default Network = false
09-13 12:58:33.669  1032  1455 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-13 12:58:33.669  1032  1455 D DSQN    : enableDataServiceNotify 
09-13 12:58:33.669  1032  1455 D DSQN    : start dsqn bin
,09-13 12:58:33.670   308  6824 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 12:58:33.670   308  6824 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
09-13 12:58:33.675  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:33.678  1032  1455 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-13 12:58:33.678  1032  1455 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 12:58:33.665  6825  6825 W dsqn    : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 12:58:33.665  6825  6825 W dsqn    : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 12:58:33.678  1032  1455 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 12:58:33.678  1032  1455 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 12:58:33.679  1599  2066 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 12:58:33.681  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 12:58:33.682  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 12:58:33.682  6308  6308 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 12:58:33.688  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 12:58:33.691  6825  6825 E DSQN    : DSQN ssw
09-13 12:58:33.696  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 12:58:33.699  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:33.703  1599  1599 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 12:58:33.704  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:33.704  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:33.705  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 12:58:33.705  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 12:58:33.706  6308  6308 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-13 12:58:33.709  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 12:58:33.714  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 12:58:33.718  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:33.724  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 12:58:33.725  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-13 12:58:33.725  6308  6308 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-13 12:58:33.732  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-13 12:58:33.734   308  6823 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-13 12:58:33.734   308  6824 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org succeed
09-13 12:58:33.737  6263  6263 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-13 12:58:33.738  6263  6263 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,09-13 12:58:33.743  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-13 12:58:33.748  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:33.756  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 12:58:33.756  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 12:58:33.757  6308  6308 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-13 12:58:33.758  6308  6308 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 12:58:33.758  6308  6308 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-13 12:58:33.765  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-13 12:58:33.772  6263  6263 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-13 12:58:33.773  6263  6263 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-13 12:58:33.778  6285  6285 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-13 12:58:33.778   308  6823 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-13 12:58:33.784  1032  6817 D DhcpStateMachine: DHCPV4 request on wlan0
09-13 12:58:33.785  1032  6817 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-13 12:58:33.785  1032  6817 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-13 12:58:33.790  1032  1386 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-13 12:58:33.775  6829  6829 W dhcpcd  : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-13 12:58:33.775  6829  6829 W dhcpcd  : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-13 12:58:33.793  6285  6285 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-13 12:58:33.803  6308  6308 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-13 12:58:33.804  6308  6308 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-13 12:58:33.805  6308  6308 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-13 12:58:33.806  6308  6308 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-13 12:58:33.807  6308  6308 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-13 12:58:33.811   308   889 D LGDataListener: argv[0]=dsqncommand
09-13 12:58:33.811   308   889 D LGDataListener: argv[1]=wlan0
09-13 12:58:33.811   308   889 D LGDataListener: argv[2]=1
09-13 12:58:33.811   308   889 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-13 12:58:33.812  1032  1092 D DSQN    : DSQM DsqnNotification wlan0  1
09-13 12:58:33.812  1032  1092 D DSQN    : start to monitor internet connection
09-13 12:58:33.813  6829  6829 I dhcpcd  : version 5.5.6 starting
09-13 12:58:33.816  6829  6829 E dhcpcd  : get_duid: m
09-13 12:58:33.816  6829  6829 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-13 12:58:33.816  6829  6829 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,09-13 12:58:33.825  6160  6233 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-13 12:58:33.826  6160  6233 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-13 12:58:33.828  6160  6233 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@21c56051 Bundle[{}]
09-13 12:58:33.829  6160  6233 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 12:58:33.830  6160  6233 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-13 12:58:33.831  6160  6233 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-13 12:58:33.832  6160  6233 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-13 12:58:33.834  6160  6233 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-13 12:58:33.834  6160  6233 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 12:58:33.845  6160  6835 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-13 12:58:33.845  6160  6835 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-13 12:58:33.845  1032  6816 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 10:58:34 GMT], X-Android-Received-Millis=[1473764313845], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473764313810]}
09-13 12:58:33.846  1032  6816 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,09-13 12:58:33.846  1032  6816 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-13 12:58:33.847  1032  1455 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-13 12:58:33.847  1032  1455 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-13 12:58:33.847  1032  1455 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 12:58:33.847  1032  1455 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 12:58:33.847  1032  1455 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 12:58:33.847  1032  1455 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-13 12:58:33.847  1032  1455 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-13 12:58:33.848  1032  1455 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 12:58:33.848  1032  1455 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 12:58:33.848  1032  1455 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 12:58:33.848  1032  1455 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 12:58:33.849  1032  1455 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-13 12:58:33.850  1032  1390 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 12:58:33.850  1599  2066 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 12:58:33.850  1032  1390 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 12:58:33.850  1847  1847 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 12:58:33.850  1847  1847 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-13 12:58:33.855  6160  6837 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-13 12:58:33.855  6160  6837 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 12:58:33.856  6160  6837 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 12:58:33.856  6160  6835 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-13 12:58:33.856  6160  6835 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 12:58:33.856  6160  6835 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 12:58:33.861  6160  6835 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 12:58:33.864  6160  6837 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 12:58:33.864  6160  6835 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-13 12:58:33.867  6160  6841 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 868, name: IncomingSocketThread/Sender)
09-13 12:58:33.868  6160  6837 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 12:58:33.869  6160  6840 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 869, name: OutgoingSocketThread/Sender)
09-13 12:58:33.871  6160  6844 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 871, name: IncomingSocketThread/Receiver)
09-13 12:58:33.871  1599  1599 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 12:58:33.871  6160  6844 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 871, thread name: IncomingSocketThread/Receiver)
09-13 12:58:33.871  6160  6844 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 12:58:33.871  6160  6844 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 871, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-13 12:58:33.872  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:33.873  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:33.873  6160  6843 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 870, name: OutgoingSocketThread/Receiver)
09-13 12:58:33.874  6160  6233 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 880)
,09-13 12:58:33.874  6160  6843 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 870, thread name: OutgoingSocketThread/Receiver)
09-13 12:58:33.874  6160  6843 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 12:58:33.874  6160  6843 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 870, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-13 12:58:33.875  6160  6233 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-13 12:58:33.875  6160  6233 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 881)
09-13 12:58:33.878  6160  6233 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 12:58:33.878  6160  6233 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3048ad3e added. We now have 5 listener(s)
09-13 12:58:33.878  1032  1900 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 12:58:33.881  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 12:58:33.881  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 12:58:33.881  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 12:58:33.881  6160  6233 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 12:58:33.881  6160  6233 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2faed79f added. We now have 5 listener(s)
09-13 12:58:33.881  6160  6233 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 12:58:33.882  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 12:58:33.884  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 12:58:33.888  6160  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:58:33.888  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:33.888  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:33.888  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:33.888  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:33.888  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:58:33.888  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:58:33.888  6160  6233 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 12:58:33.890  6160  6233 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 12:58:33.890  6160  6233 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 12:58:33.893  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:33.894  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:58:33.894  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:33.894  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 12:58:33.894  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 12:58:33.894  6160  6233 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3048ad3e removed from the list
09-13 12:58:33.894  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 12:58:33.894  6160  6233 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2faed79f removed from the list
,09-13 12:58:33.894  6160  6233 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:58:33.894  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:33.896  6160  6233 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 12:58:33.896  6160  6233 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 12:58:33.896  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 12:58:33.896  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 12:58:33.896  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 12:58:33.898  6829  6829 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-13 12:58:33.898  6829  6829 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-13 12:58:33.898  6829  6829 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-13 12:58:33.898  6829  6829 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-13 12:58:33.899  6829  6829 D dhcpcd  : wlan0: sending REQUEST (xid 0x79657ac6), next in 3.27 seconds
09-13 12:58:33.899  6160  6233 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 12:58:33.899  1032  1727 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 12:58:33.903  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 12:58:33.904  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 12:58:33.905  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 12:58:33.905  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 12:58:33.907  6160  6233 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-13 12:58:33.922  6829  6829 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-13 12:58:33.931  6829  6829 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
,09-13 12:58:33.931  6829  6829 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-13 12:58:33.931  6829  6829 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
,09-13 12:58:33.931  6829  6829 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-13 12:58:33.931  6829  6829 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-13 12:58:33.932  6829  6829 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-13 12:58:33.932  6829  6829 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-13 12:58:33.932  6829  6829 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-13 12:58:34.192  1032  1455 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 12:58:34.205  1032  1094 D Tethering: MasterInitialState.processMessage what=3
09-13 12:58:34.206  1032  1088 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 12:58:34.213  1032  1088 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 12:58:34.218  1032  1818 D AlarmManagerService: Setting time of day to sec=1473764315
,09-13 12:58:35.128  1032  1818 W AlarmManagerService: Unable to set rtc to 1473764315: Invalid argument
09-13 12:58:35.134  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:35.134  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:35.134  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:35.134  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:35.134  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:35.134  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:58:35.134  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:58:35.134  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:58:35.137  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 12:58:35.141  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:35.141  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:35.141  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:35.141  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:35.141  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:35.141  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:58:35.141  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:58:35.141  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 12:58:35.151  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 12:58:35.160  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-13 12:58:35.161  3674  6262 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-13 12:58:35.162  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:58:35.162  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:58:35.162  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 12:58:35.162  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:58:35.162  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:58:35.162  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:58:35.162  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:58:35.162  6160  6160 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 12:58:35.165  5344  5344 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-13 12:58:35.171  1032  1455 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 12:58:35.190  6160  6160 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 12:58:35.197  1936  1936 I SecureClockService: Intent.ACTION_TIME_CHANGED 
09-13 12:58:35.198  1599  1599 I [SystemUI]Clock: onReceive = android.intent.action.TIME_SET
09-13 12:58:35.200  3768  3768 D LIA_Informant_Tips_DateChangeManager: onReceive() : ACTION_TIME_CHANGED
09-13 12:58:35.201  3768  3768 I LIA_Informant_Tips_LogTracer: [Log Tracer - Schedule Transition] Time Change Event Received : 2016-09-13 12:58:35...... Request
09-13 12:58:35.201  3768  3768 I LIA_Informant_Tips_LogTracer: [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 5, total count : 85, new day : false...... Request
09-13 12:58:35.201  3768  3768 D LIA_Informant_Tips_DateChangeManager: DateInfo : SmartTips Total Working Day Count = 85
09-13 12:58:35.201  3768  3768 D LIA_Informant_Tips_DateChangeManager: DateInfo : UserGuide Working Duration Count = 5
09-13 12:58:35.201  3768  3768 D LIA_Informant_Tips_DateChangeManager: DateInfo : Last Date Check Time = 2016-09-13 12:58:35
09-13 12:58:35.202  1599  1599 I LgeClockWidgetControlView: time changed, timezoneChanged : false
09-13 12:58:35.204  1032  1771 W ActivityManager: getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
09-13 12:58:35.205  1032  1455 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 12:58:35.210  1032  1094 D Tethering: MasterInitialState.processMessage what=3
09-13 12:58:35.216  1032  1094 D Tethering: MasterInitialState.processMessage what=3
09-13 12:58:35.218  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:35.219  2028  2028 I [LGHome]LGDateChangeReceiver: [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=13 currentDate=-1 dayofweek=3 currentDayOfWeek=-1
,09-13 12:58:35.220  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:35.221  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
09-13 12:58:35.221  2028  2028 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 13
09-13 12:58:35.231  2028  2028 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 13
09-13 12:58:35.231  2028  2028 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-13 12:58:35.235  1032  1088 E GpsLocationProvider: No APN found to select.
09-13 12:58:35.238  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:35.240  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:35.242  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:35.245  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:58:35.247  5344  5344 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-13 12:58:35.250  5344  5344 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-13 12:58:35.256  1032  1088 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 12:58:35.256  1032  1088 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 12:58:35.257  1032  1088 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 12:58:35.257  1032  1088 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-13 12:58:35.260  2621  2621 D [Concierge]Service: onStartCommand(). Type : 9
09-13 12:58:35.289  1032  6817 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-13 12:58:35.290  1032  6817 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-13 12:58:35.290  1032  6817 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-13 12:58:35.291  1032  6817 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-13 12:58:35.291  1032  6817 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-13 12:58:35.291  1032  6817 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-13 12:58:35.291  1032  6817 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-13 12:58:35.291  1032  6817 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-13 12:58:35.291  1032  6817 D DhcpStateMachine: RunningState
09-13 12:58:35.295  2180  2180 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-13 12:58:35.302  1032  1900 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
,09-13 12:58:35.303  1032  6816 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:35.303  1032  6816 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:35.304  1032  6816 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
,09-13 12:58:35.304  1032  6816 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:35.304  1032  6816 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-13 12:58:35.305   308  6892 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 12:58:35.305   308  6892 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
09-13 12:58:35.331  1032  6816 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 10:58:35 GMT], X-Android-Received-Millis=[1473764315329], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473764315305]}
09-13 12:58:35.331  1032  6816 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-13 12:58:35.331  1032  6816 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-13 12:58:35.331  1032  1455 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-13 12:58:35.331  1032  1455 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-13 12:58:35.331  1032  1455 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 12:58:35.331  1032  1455 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 12:58:35.331  1032  1455 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-13 12:58:35.331  1032  1455 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-13 12:58:35.331  1032  1455 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-13 12:58:35.332  1032  1455 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 12:58:35.332  1032  1455 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 12:58:35.332  1032  1455 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 12:58:35.332  1599  2066 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-13 12:58:35.344   308  6892 D libc-netbsd: res_queryN name = mtalk.google.com succeed
09-13 12:58:35.344  1032  1989 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6893 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-13 12:58:35.445  6893  6893 I AppUp4:AppBoxCP: onCreate
,09-13 12:58:35.445  6893  6893 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-13 12:58:35.451  2180  6891 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-13 12:58:35.453  6893  6893 I AppUp4:DB:  setFingerPrint start
,09-13 12:58:35.453  6893  6893 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,09-13 12:58:35.460  6893  6893 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-13 12:58:35.460  6893  6893 I AppUp4:DB:  SDK version = 21
09-13 12:58:35.460  6893  6893 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-13 12:58:35.463  6893  6893 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-13 12:58:35.464  6893  6893 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 12:58:35.464  6893  6893 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 12:58:35.467  6893  6893 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 12:58:35.468  6893  6893 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 12:58:35.473  6893  6893 I AppUp4:CustModeStarterReceiver: onReceive
,09-13 12:58:35.512  6893  6893 D LgDataFeature: LgDataFeature() Constructor: none
,09-13 12:58:35.515  6893  6893 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 12:58:35.524  6893  6893 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2fe4a8c7
09-13 12:58:35.524  6893  6893 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 12:58:35.524  6893  6893 D AppUp4:CustFacade: isPhone : true
,09-13 12:58:35.525  6893  6893 D AppUp4:CustModeStarterReceiver: begin check event
09-13 12:58:35.525  6893  6893 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-13 12:58:35.525  6893  6893 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-13 12:58:35.544  6893  6911 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-13 12:58:35.544  6893  6911 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-13 12:58:35.544  6893  6911 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-13 12:58:35.546  1032  1727 I ActivityManager: Killing 5831:com.android.gallery3d/u0a27 (adj 15): empty #17
,09-13 12:58:35.579  1032  1455 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-13 12:58:35.584  1032  1048 W libprocessgroup: failed to open /acct/uid_10027/pid_5831/cgroup.procs: No such file or directory
09-13 12:58:35.585  4265  4265 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 12:58:35.585  4265  4265 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 12:58:35.587  4265  4265 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 12:58:35.590  4265  4265 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 12:58:35.602  3427  3427 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,09-13 12:58:35.607  4265  6919 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 12:58:35.610  4265  6919 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-13 12:58:35.613  3427  3427 V DownloadManager: DownloadService onCreate
09-13 12:58:35.614  4265  6920 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 12:58:35.614  4265  6920 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 12:58:35.616  3427  6921 I DownloadManager: in removeSpuriousFiles
09-13 12:58:35.618  3427  6921 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,09-13 12:58:35.621  3427  6921 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@879d6fd on behalf of 3427
09-13 12:58:35.622  3427  6921 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-13 12:58:35.622  3427  6921 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-13 12:58:35.623  3427  6921 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-13 12:58:35.623  3427  6921 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-13 12:58:35.623  3427  6921 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-13 12:58:35.623  3427  6921 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-13 12:58:35.623  3427  6921 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-13 12:58:35.623  3427  6921 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-13 12:58:35.623  3427  6921 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-13 12:58:35.623  3427  6921 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-13 12:58:35.623  3427  6921 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-13 12:58:35.625  3427  6921 I DownloadManager: in trimDatabase
09-13 12:58:35.625  3427  6921 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-13 12:58:35.626  3427  6921 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@fcff2 on behalf of 3427
09-13 12:58:35.641  1032  1089 W ProcessCpuTracker: Skipping unknown process pid 6880
,09-13 12:58:35.641  1032  1089 W ProcessCpuTracker: Skipping unknown process pid 6881
09-13 12:58:35.642  1032  1089 W ProcessCpuTracker: Skipping unknown process pid 6885
09-13 12:58:35.643  1032  1089 W ProcessCpuTracker: Skipping unknown process pid 6902
09-13 12:58:35.644  1032  1089 W ProcessCpuTracker: Skipping unknown process pid 6915
09-13 12:58:35.659  1032  1899 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6925 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-13 12:58:35.665  3427  3427 V DownloadManager: DownloadService onStartCommand
09-13 12:58:35.666  3427  6922 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-13 12:58:35.669  4265  6919 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-13 12:58:35.675  4265  4265 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-13 12:58:35.678  4265  4265 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-13 12:58:35.678  4265  4265 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-13 12:58:35.680  4265  4265 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-13 12:58:35.681   350   350 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 430us total 20.530ms
,09-13 12:58:35.686  3427  6922 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1811e5f9 on behalf of 3427
09-13 12:58:35.689  3427  6922 V DownloadManager: processing inserted download 1
09-13 12:58:35.690  3427  6922 V DownloadManager: processing inserted download 4
09-13 12:58:35.691  3427  6922 V DownloadManager: processing inserted download 7
09-13 12:58:35.693  4265  4265 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-13 12:58:35.698  3427  6922 V DownloadManager: processing inserted download 8
09-13 12:58:35.699  3427  6922 V DownloadManager: processing inserted download 9
09-13 12:58:35.700  3427  6922 V DownloadManager: processing inserted download 10
09-13 12:58:35.701  3427  6922 V DownloadManager: processing inserted download 11
,09-13 12:58:35.705  3427  6922 V DownloadManager: processing inserted download 12
09-13 12:58:35.706  3427  6922 V DownloadManager: processing inserted download 13
09-13 12:58:35.707  3427  6922 V DownloadManager: processing inserted download 14
09-13 12:58:35.708  3427  6922 V DownloadManager: processing inserted download 16
09-13 12:58:35.711  3427  3427 V DownloadManager: DownloadService onDestroy
09-13 12:58:35.712   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 446us total 19.876ms
,09-13 12:58:35.732   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 418us total 19.394ms
,09-13 12:58:35.740  6925  6925 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 12:58:35.740  6925  6925 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 12:58:35.741  6925  6925 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 12:58:35.742  6925  6925 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-13 12:58:35.811  6925  6925 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-13 12:58:35.822  6925  6925 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-13 12:58:35.857  6925  6925 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-13 12:58:35.883  6925  6925 D LgDataFeature: LgDataFeature() Constructor: none
,09-13 12:58:35.883  6925  6925 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 12:58:35.984  6925  6925 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-13 12:58:36.018  6925  6925 I HubEmail: JNI_OnLoad()
09-13 12:58:36.018  6925  6925 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-13 12:58:36.018  6925  6925 I HubEmail: registerNatives()
09-13 12:58:36.018  6925  6925 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-13 12:58:36.018  6925  6925 I HubEmail: registerNativeMethods()
,09-13 12:58:36.018  6925  6925 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-13 12:58:36.019  6925  6925 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-13 12:58:36.022  3355  3355 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 12:58:36.023  3355  3355 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 12:58:36.024  3355  3355 I LgeMiscReceiver: networkInfo.isConnected() = true
09-13 12:58:36.024  3355  3355 D PhoneState: setPdpRejectCasuse : false
09-13 12:58:36.027  1032  1390 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 12:58:36.028  1032  1390 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 12:58:36.029  1032  1390 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 12:58:36.030  1032  1390 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 12:58:36.032  1032  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 12:58:36.033  1032  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-13 12:58:36.034  1032  1455 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
09-13 12:58:36.034  1032  1455 D ConnectivityService: identical MTU - not setting
09-13 12:58:36.034  1032  1455 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-13 12:58:36.034  1032  1455 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-13 12:58:36.034  1032  1455 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 12:58:36.034  1032  1455 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 12:58:36.035  1032  1455 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 12:58:36.036  1599  2066 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-13 12:58:36.068   308  6961 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 12:58:36.068   308  6961 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
,09-13 12:58:36.082  1032  1900 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6962 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
09-13 12:58:36.084  6925  6959 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 12:58:36.113   308  6961 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,09-13 12:58:36.170  6962  6962 D LgDataFeature: LgDataFeature() Constructor: none
09-13 12:58:36.170  6962  6962 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 12:58:36.173  6962  6962 D PhoneMonitor: Register our PhoneStateListener
09-13 12:58:36.178  6333  6958 V FormManager: There are no updated forms. The schedule will be deleted.
09-13 12:58:36.180  6333  6958 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-13 12:58:36.182  6962  6962 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 12:58:36.184  6962  6962 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-13 12:58:36.201  6962  6962 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-13 12:58:36.202  6962  6962 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-13 12:58:36.204  6962  6962 D TelephonyAutoProfiling: [parse] Load xml
,09-13 12:58:36.208  6962  6962 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-13 12:58:36.208  6962  6962 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-13 12:58:36.208  6962  6962 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-13 12:58:36.208  6962  6962 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-13 12:58:36.208  6962  6962 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-13 12:58:36.208  6962  6962 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-13 12:58:36.208  6962  6962 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-13 12:58:36.208  6962  6962 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-13 12:58:36.208  6962  6962 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-13 12:58:36.208  6962  6962 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-13 12:58:36.208  6962  6962 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-13 12:58:36.208  6962  6962 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-13 12:58:36.208  6962  6962 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-13 12:58:36.208  6962  6962 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-13 12:58:36.208  6962  6962 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-13 12:58:36.208  6962  6962 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-13 12:58:36.208  6962  6962 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
09-13 12:58:36.213  6962  6962 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-13 12:58:36.235  1032  1900 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6981 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 12:58:36.237  1032  1900 I ActivityManager: Killing 5894:com.google.android.apps.docs/u0a61 (adj 15): empty #17
09-13 12:58:36.274  1032  1727 W libprocessgroup: failed to open /acct/uid_10061/pid_5894/cgroup.procs: No such file or directory
,09-13 12:58:36.286  1032  1953 I ActivityManager: Killing 5942:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
09-13 12:58:36.338  1032  1727 W libprocessgroup: failed to open /acct/uid_10080/pid_5942/cgroup.procs: No such file or directory
,09-13 12:58:36.355  1809  6998 I CheckinService: active receiver: enabled
,09-13 12:58:36.399  1809  6998 I CheckinService: Preparing to send checkin request
09-13 12:58:36.399  1809  6998 I EventLogService: Accumulating logs since 1473764063694
09-13 12:58:36.451  1809  6998 W EventLogAggregator: Unknown tag: snet_gcore
09-13 12:58:36.451  1809  6998 W EventLogAggregator: Unknown tag: snet_launch_service
,09-13 12:58:36.520  1809  6998 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-13 12:58:36.528  1032  1442 D WifiService: New client listening to asynchronous messages
,09-13 12:58:36.615  1032  1900 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7002 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-13 12:58:36.617  1032  1900 I ActivityManager: Killing 5968:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,09-13 12:58:36.674  1032  1772 W libprocessgroup: failed to open /acct/uid_10097/pid_5968/cgroup.procs: No such file or directory
,09-13 12:58:36.746  7002  7002 D DrmBroadcastReceiver: Receive CONNECTIVITY_ACTION
09-13 12:58:36.748  7002  7002 D DrmBroadcastReceiver: 1  network is available. Sync DRM Time with NTP
,09-13 12:58:36.756  7002  7002 V DrmService: Service onCreate
09-13 12:58:36.756  7002  7002 D DrmService: Received new request = 2
09-13 12:58:36.762  7002  7019 I DrmSntpClient: Start Sync process
,09-13 12:58:36.762  7002  7019 D DrmSntpClient: Server : 0
,09-13 12:58:36.771   308  7020 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 12:58:36.772   308  7020 D libc-netbsd: res_queryN name = pool.ntp.org, class = 1, type = 1
09-13 12:58:36.809  1032  1899 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7021 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 12:58:36.813   308  7020 D libc-netbsd: res_queryN name = pool.ntp.org succeed
09-13 12:58:36.851  7002  7019 I LGDrmClient: _DRM_ServiceGet() : Bind lgdrm service
09-13 12:58:36.853   322   322 V ILGDrmService: eDRM_SetDRMTime +++
09-13 12:58:36.854   322   322 I LGDRM   : [DRM] SET TIME : YR=2016, MON=9, DAY=13
09-13 12:58:36.854   322   322 I LGDRM   : [DRM] SET TIME : HR=10, MIN=58, SEC=35
,09-13 12:58:36.859   322   322 V ILGDrmService: eDRM_SetDRMTime ---
09-13 12:58:36.860  7002  7019 I DrmSntpClient: Synched
09-13 12:58:36.868  1032  1953 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7038 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,09-13 12:58:36.871  7002  7002 D DrmService: Completed !! request = 2
09-13 12:58:36.871  7002  7002 D DrmService: Request count = 0
09-13 12:58:36.881  7002  7002 V DrmService: Service onDestroy
09-13 12:58:36.883  1032  1572 I ActivityManager: Killing 6001:com.lge.eula/1000 (adj 15): empty #17
,09-13 12:58:36.915  7021  7021 I art     : Almond Protected OAT
,09-13 12:58:36.995  1032  1990 W libprocessgroup: failed to open /acct/uid_1000/pid_6001/cgroup.procs: No such file or directory
,09-13 12:58:37.014  7021  7021 D WeatherApplication: removeAccount
,09-13 12:58:37.018  7021  7021 D WeatherApplication: Account.length = 0
09-13 12:58:37.019  7021  7021 E WeatherApplication: OPERATOR:OPEN
09-13 12:58:37.032  7021  7021 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:58:37
,09-13 12:58:37.039  7038  7038 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-13 12:58:37.039  7038  7038 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-13 12:58:37.040  7021  7021 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 12:58:37.040  7021  7021 D Weather.Utils: 2 : All the weather widget is gone.
09-13 12:58:37.045  7021  7021 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,09-13 12:58:37.052  7021  7021 D WeatherAncestor: connectivity changed - connection : true
09-13 12:58:37.053  7021  7021 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-13 12:58:37.066  7021  7021 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 12:58:37.066  7021  7021 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 12:58:37.066  7021  7021 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,09-13 12:58:37.071  7038  7038 I MultiDex: VM with version 2.1.0 has multidex support
09-13 12:58:37.071  7038  7038 I MultiDex: install
09-13 12:58:37.071  7038  7038 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-13 12:58:37.084  7038  7038 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,09-13 12:58:37.091   308  6713 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-13 12:58:37.092   308  6713 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 28
09-13 12:58:37.093   308  6713 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 1
09-13 12:58:37.095  1032  1092 D DSQN    : Dns fail occured do internet check.
09-13 12:58:37.095  1032  1032 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
09-13 12:58:37.095  1032  1032 D DSQN    : try Internet connection check
09-13 12:58:37.095  1032  6624 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-13 12:58:37.096  1032  6624 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-4s927ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:37.096  1032  6624 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-4s927ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:37.096  1032  6624 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,09-13 12:58:37.104  7021  7021 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 12:58:37.105  7021  7021 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:58:37
09-13 12:58:37.108   308  7059 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 12:58:37.109   308  7059 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-13 12:58:37.109   308  7059 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-13 12:58:37.110  1032  7058 D DSQN    : ThreadTCPConnectionCheck connect try to216.58.214.238
09-13 12:58:37.136  1032  1387 D LGWifiP2pService: InactiveState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:37.136  1032  1387 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 12:58:37.136  1032  1387 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-13 12:58:37.146  1032  1048 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7060 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 12:58:37.147  1032  1048 I ActivityManager: Killing 2151:com.lge.music/u0a34 (adj 15): empty #17
09-13 12:58:37.155  1032  7057 D DSQN    : ThreadInternetCheck internet check OK 
,09-13 12:58:37.166  1032  1390 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 2 0
09-13 12:58:37.166  1032  1390 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 2 0
09-13 12:58:37.166  1032  1390 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 2 0
09-13 12:58:37.167  1032  1390 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 2 0
09-13 12:58:37.167  1032  1390 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-13 12:58:37.168  1032  1390 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-13 12:58:37.179   315   315 V AudioFlinger: 2151 died, releasing its sessions
09-13 12:58:37.180   315   315 V AudioFlinger:  pid 1847 @ 0
09-13 12:58:37.180   315   315 V AudioFlinger:  pid 3355 @ 1
09-13 12:58:37.180   315   315 V AudioFlinger:  pid 3355 @ 2
,09-13 12:58:37.204  1032  1900 W libprocessgroup: failed to open /acct/uid_10034/pid_2151/cgroup.procs: No such file or directory
,09-13 12:58:37.335   278   426 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 12:58:37.335   278   426 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-13 12:58:37.335   278   426 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 12:58:37.340  7060  7078 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-13 12:58:37.343   278   426 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 12:58:37.344   278   426 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-13 12:58:37.344   278   426 W Vold    : Returning OperationFailed - no handler for errno 0
09-13 12:58:37.345  7060  7078 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-13 12:58:37.369   278   426 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 12:58:37.369   278   426 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-13 12:58:37.369   278   426 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 12:58:37.370  7060  7082 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-13 12:58:37.372   278   426 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-13 12:58:37.372   278   426 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-13 12:58:37.372   278   426 W Vold    : Returning OperationFailed - no handler for errno 0
09-13 12:58:37.373  7060  7082 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-13 12:58:37.477  1032  1390 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-59 f=2437 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3901] from screen [on:0 period:590534949] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 12:58:37.478  1032  1390 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-59 f=2437 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:590534950] gl rssi=-59 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-13 12:58:37.478  1032  1390 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-13 12:58:37.484  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-13 12:58:37.528  1032  1435 V WifiInternetCheck: Single check msg out of sync, ignoring.
,09-13 12:58:37.560  7038  7054 D LgDataFeature: LgDataFeature() Constructor: none
,09-13 12:58:37.560  7038  7054 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 12:58:37.564  7060  7060 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
09-13 12:58:37.569  1032  1455 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-13 12:58:37.572  1032  1094 D Tethering: MasterInitialState.processMessage what=3
09-13 12:58:37.573  1032  1088 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-13 12:58:37.573  1032  1088 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-13 12:58:37.585  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:37.588  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:58:37.588  5344  5344 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-13 12:58:37.591  6160  6160 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:58:37.596  7060  7060 I LibraryLoader: Loading: webviewchromium
09-13 12:58:37.604  7060  7060 I LibraryLoader: Time to load native libraries: 10 ms (timestamps 9802-9812)
09-13 12:58:37.605  7060  7060 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-13 12:58:37.612  7060  7060 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {51f508e}
09-13 12:58:37.615  7060  7060 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 12:58:37.615  7060  7060 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,09-13 12:58:37.630  7060  7060 I BrowserStartupController: Initializing chromium process, renderers=0
09-13 12:58:37.632  7060  7060 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 12:58:37.653   315  1396 V AudioPolicyService: registerClient() client 0xb1024ec0, uid 10093
09-13 12:58:37.653  7060  7060 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-13 12:58:37.655  7060  7060 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-13 12:58:37.655  7060  7060 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-13 12:58:37.655  7060  7107 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-13 12:58:37.677  7060  7060 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 12:58:37.677  7060  7060 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 12:58:37.677  7060  7060 I Adreno-EGL: Build Date: 12/12/14 금
09-13 12:58:37.677  7060  7060 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 12:58:37.677  7060  7060 I Adreno-EGL: Remote Branch: 
09-13 12:58:37.677  7060  7060 I Adreno-EGL: Local Patches: 
09-13 12:58:37.677  7060  7060 I Adreno-EGL: Reconstruct Branch: 
,09-13 12:58:37.748  7060  7060 I NSApplication: Starting up...
,09-13 12:58:37.782  7115  7115 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-13 12:58:37.808  6160  6233 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 12:58:37.808  6160  6233 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 12:58:37.813  1032  1935 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7123 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-13 12:58:37.815  1032  1048 I ActivityManager: Killing 5854:com.android.vending/u0a44 (adj 15): empty #17
09-13 12:58:37.824  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:58:37.824  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:37.824  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:37.824  6160  6233 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3048ad3e not in the list
09-13 12:58:37.824  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:58:37.825  6160  6233 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2faed79f not in the list
09-13 12:58:37.825  6160  6233 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:58:37.825  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:37.825  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 12:58:37.827  6160  6233 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 12:58:37.828  6160  6233 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-13 12:58:37.829  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-13 12:58:37.829  6160  6233 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 12:58:37.829  6160  6233 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 12:58:37.829  6160  6233 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 12:58:37.829  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 12:58:37.832  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 12:58:37.832  6160  6233 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 12:58:37.832  6160  6233 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 12:58:37.832  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 12:58:37.832  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 12:58:37.832  6160  6160 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 12:58:37.832  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 12:58:37.832  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 12:58:37.853  7115  7115 I dex2oat : dex2oat took 70.919ms (threads: 4)
,09-13 12:58:37.867  7038  7054 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 12:58:37.867  7038  7054 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 12:58:37.867  7038  7054 I Adreno-EGL: Build Date: 12/12/14 금
09-13 12:58:37.867  7038  7054 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 12:58:37.867  7038  7054 I Adreno-EGL: Remote Branch: 
09-13 12:58:37.867  7038  7054 I Adreno-EGL: Local Patches: 
09-13 12:58:37.867  7038  7054 I Adreno-EGL: Reconstruct Branch: 
,09-13 12:58:37.875  1032  1900 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 12:58:37.876  1032  1990 W libprocessgroup: failed to open /acct/uid_10044/pid_5854/cgroup.procs: No such file or directory
09-13 12:58:37.881  6160  7138 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 12:58:37.883  3826  3844 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=109 mFd=107
,09-13 12:58:37.884  6160  7138 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-13 12:58:37.885  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 12:58:37.886  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 12:58:37.887  6160  6233 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 12:58:37.887  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:58:37.887  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 12:58:37.887  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 12:58:37.887  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 12:58:37.887  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:37.887  6160  6233 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 12:58:37.887  6160  6233 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3048ad3e not in the list
09-13 12:58:37.887  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:58:37.887  6160  6233 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2faed79f not in the list
09-13 12:58:37.887  6160  6233 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:58:37.887  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:37.888  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:37.888  6160  6233 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 12:58:37.888  6160  6233 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 12:58:37.888  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 12:58:37.888  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 12:58:37.888  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 12:58:37.890  6160  7138 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 12:58:37.890  6160  7138 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 12:58:37.890  6160  7138 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 12:58:37.894  6160  6233 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 12:58:37.895  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:37.896  6160  6233 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 12:58:37.896  6160  6160 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 12:58:37.896  6160  6160 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 12:58:37.912  7123  7123 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 12:58:38.003  7038  7054 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 12:58:38.003  7038  7054 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 12:58:38.003  7038  7054 I Adreno-EGL: Build Date: 12/12/14 금
09-13 12:58:38.003  7038  7054 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 12:58:38.003  7038  7054 I Adreno-EGL: Remote Branch: 
09-13 12:58:38.003  7038  7054 I Adreno-EGL: Local Patches: 
09-13 12:58:38.003  7038  7054 I Adreno-EGL: Reconstruct Branch: 
,09-13 12:58:38.140  7038  7054 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 12:58:38.140  7038  7054 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 12:58:38.140  7038  7054 I Adreno-EGL: Build Date: 12/12/14 금
09-13 12:58:38.140  7038  7054 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 12:58:38.140  7038  7054 I Adreno-EGL: Remote Branch: 
09-13 12:58:38.140  7038  7054 I Adreno-EGL: Local Patches: 
09-13 12:58:38.140  7038  7054 I Adreno-EGL: Reconstruct Branch: 
,09-13 12:58:38.155  1032  1032 D DSQN    : EVENT_INTERNET_CHECK_ENABLE received
,09-13 12:58:38.264  1032  1727 I art     : Explicit concurrent mark sweep GC freed 136666(6MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 1.846ms total 134.572ms
,09-13 12:58:38.283   308  7154 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-13 12:58:38.283   308  7154 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,09-13 12:58:38.313  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,09-13 12:58:38.326   308  7154 D libc-netbsd: res_queryN name = android.clients.google.com succeed
09-13 12:58:38.380  1032  1954 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=7165 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,09-13 12:58:38.449  1809  6998 I CheckinTask: Sending checkin request (7894 bytes)
,09-13 12:58:38.469  7165  7187 D ALBootInit: ====action==>android.intent.action.TIME_SET
,09-13 12:58:38.473  7165  7187 D ALBootInit: Alarm ALBootInit: TIME_SET
09-13 12:58:38.475  7165  7187 D Alarms  : [setNextAlert] start
09-13 12:58:38.488  7165  7187 D Alarms  : [setNextAlert] (1)
,09-13 12:58:38.490  7165  7187 D Alarms  :  minTime  = 0
09-13 12:58:38.492  7165  7187 D Alarms  :  -- OK multi -- 0
09-13 12:58:38.493  7165  7187 E jeny.kim: [setNextAlert] setNextAlert  temp_Alarmlink + 
09-13 12:58:38.493  7165  7187 E jeny.kim: [setNextAlert]setNextAlert temp_AlarmLinkText + 
09-13 12:58:38.515  7165  7187 I CommonUtil: BUILD Country: EU
09-13 12:58:38.517  7165  7187 D Alarms  : broadcastToWidgetProvider : false
,09-13 12:58:38.525  7165  7187 D Alarms  : Enter formatDayAndTime(final Context context, long timeInMiliSec)
09-13 12:58:38.540  1032  1047 V SettingsProvider: call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,09-13 12:58:38.549  7165  7165 I DigitalAppWidgetProvider: onReceive: android.intent.action.TIME_SET
09-13 12:58:38.553  7165  7165 V DigitalAppWidgetProvider: cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@20b2aef4
09-13 12:58:38.556  7165  7165 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@20b2aef4
,09-13 12:58:38.562  7165  7165 D QuickCoverProvider: onReceiver
09-13 12:58:38.576  1555  1555 I indal   : SmartCoverWidgetContext createApplicationContext
09-13 12:58:38.576  1555  1555 I indal   : SmartCoverWidgetContext createApplicationContext
,09-13 12:58:38.609  7021  7021 D WeatherAncestor: 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:58:38
,09-13 12:58:38.614  7021  7021 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 12:58:38.614  7021  7021 D Weather.Utils: 2 : All the weather widget is gone.
09-13 12:58:38.614  7021  7021 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 12:58:38.618  7021  7021 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@221b061d
09-13 12:58:38.619  7021  7021 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 12:58:38.619  7021  7021 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 12:58:38.619  7021  7021 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 12:58:38.625  7021  7021 D Weather_cast: 2 : set auto-update time : 9/13 15:58
,09-13 12:58:38.633  7021  7021 D WeatherAncestor: 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 12:58:38
,09-13 12:58:38.690  1032  1048 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7193 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-13 12:58:38.696  1032  1048 I ActivityManager: Killing 6434:com.lge.lifetracker/u0a37 (adj 15): empty #17
,09-13 12:58:38.740   308  7210 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-13 12:58:38.741   308  7210 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,09-13 12:58:38.753  1032  1954 W libprocessgroup: failed to open /acct/uid_10037/pid_6434/cgroup.procs: No such file or directory
,09-13 12:58:38.781   308  7210 D libc-netbsd: res_queryN name = www.google.com succeed
,09-13 12:58:38.829  7193  7193 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1473764318829
09-13 12:58:38.829  7193  7193 D         : TimeServiceNative: User Time to be set is 1473764318829
09-13 12:58:38.829  7193  7193 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
09-13 12:58:38.829  7193  7193 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
09-13 12:58:38.829  7193  7193 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1473764318829
09-13 12:58:38.830  7193  7193 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
09-13 12:58:38.830   423  1031 D QC-time-services: Daemon: Connection accepted:time_genoff
09-13 12:58:38.830   423  7212 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1473764318829
09-13 12:58:38.831   423  7212 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1473764318829, operation = 0
09-13 12:58:38.831   423  7212 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/26/70 5:26:1
09-13 12:58:38.831   423  7212 D QC-time-services: Daemon:Value read from RTC seconds = 7277161000
09-13 12:58:38.831   423  7212 D QC-time-services: Daemon:new time 1473764318829 
09-13 12:58:38.831   423  7212 D QC-time-services: Daemon: delta 1466487157829 genoff 1466487157829 
09-13 12:58:38.831   423  7212 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1466487157829 to memory
09-13 12:58:38.831   423  7212 D QC-time-services: Daemon:Opening File: /data/time/ats_2
09-13 12:58:38.831   423  7212 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
09-13 12:58:38.838   423  7212 D QC-time-services: Updating the TOD offset
09-13 12:58:38.839   423  7212 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1466487157829 to memory
09-13 12:58:38.839   423  7212 D QC-time-services: Daemon:Opening File: /data/time/ats_1
09-13 12:58:38.839   423  7212 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,09-13 12:58:38.844   423  7212 E QC-time-services: Daemon:Update to modem bit set
09-13 12:58:38.844  7193  7193 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
09-13 12:58:38.844   423  7212 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
09-13 12:58:38.844   423  7212 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1150522357829
09-13 12:58:38.845  1032  1436 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
09-13 12:58:38.846   423  1029 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
09-13 12:58:38.847   423  1031 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
09-13 12:58:38.848  5069  5069 V [BNRBootReceiver]: boot receiver action = android.intent.action.TIME_SET
09-13 12:58:38.849  5069  5069 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
09-13 12:58:38.850  1599  1599 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
09-13 12:58:38.850  1599  1599 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
09-13 12:58:38.850  1599  1599 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
09-13 12:58:38.852  5069  5069 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:230 com.lge.bnr.service.BNRBootReceiver.onReceive:121 
09-13 12:58:38.853  5069  5069 V [BNRBootReceiver]: Boot Receiver Return
,09-13 12:58:38.914  1032  1989 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=7213 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,09-13 12:58:38.915  1032  1989 I ActivityManager: Killing 6460:com.lge.settings.easy/1000 (adj 15): empty #17
09-13 12:58:38.928  1809  6998 I art     : Explicit concurrent mark sweep GC freed 21236(1542KB) AllocSpace objects, 16(256KB) LOS objects, 51% free, 29MB/61MB, paused 1.649ms total 91.980ms
,09-13 12:58:38.973  1032  1990 W libprocessgroup: failed to open /acct/uid_1000/pid_6460/cgroup.procs: No such file or directory
,09-13 12:58:38.989  1809  6998 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,09-13 12:58:39.013  7213  7213 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 12:58:39.016  1809  6998 I CheckinService: active receiver: disabled
,09-13 12:58:39.046  1809  7230 I CheckinService: active receiver: disabled
09-13 12:58:39.065  7213  7213 D CalendarApplication: CalendarApplication.onCreate()
,09-13 12:58:39.081  7213  7213 D PreferenceKeysParser: [debug_displayParseInfos] preference keys.size() = 44
,09-13 12:58:39.083  7213  7213 D PreferenceKeysParser: [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@b4a68eb, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@b687648, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@33347ce1, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@26bea06, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2fe4a8c7, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@20b2aef4, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@221b061d, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@18cca092, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@2af90a63, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@18c5c660, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@1ce6e719, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3f1033de, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@567e9bf, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@3f30e88c, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@36f5dbd5, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@2b67afea, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@bbb62db, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@274a0178, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@21c56051, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@1408e0b6, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@3f0351b7, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@1d9bd24, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@f2eb08d, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@aba5242, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@37715253, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@21878790, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@3b62c889, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@51f508e, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@14b4c0af, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1a058cbc, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@1aa66445, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@1dc3e79a, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@1816b8cb, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@25fcb8a8, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@26cdffc1, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@19e8e366, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@45616a7, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@3fb8b754, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@879d6fd, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@fcff2, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@1f437643, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@,1893f4c0, lg
09-13 12:58:39.090  7213  7213 D GeneralPreferenceUtils: [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
09-13 12:58:39.109  7213  7213 D Config  : [init]
09-13 12:58:39.111  7213  7213 I Config  : LGCalendar ver.4.40.16
09-13 12:58:39.112  7213  7213 I Config  : start check model
09-13 12:58:39.112  7213  7213 I Config  : start check native_ca
09-13 12:58:39.114  7213  7213 I Config  : Config Operator=OPEN, Country=EU
09-13 12:58:39.114  7213  7213 D Config  : [setDefaultValuesToPref]
09-13 12:58:39.114  7213  7213 D Config  : [parseProfiles]
09-13 12:58:39.119  7213  7213 D ProfilesParser: [debug_displayParseInfos] profile.country = null
09-13 12:58:39.119  7213  7213 D ProfilesParser: [debug_displayParseInfos] profile.operator = null
09-13 12:58:39.120  7213  7213 D Config  : [updateProfiletoCountryInfo]
09-13 12:58:39.121  7213  7213 D GeneralPreference: [checkAndMigrateOldPreference]
09-13 12:58:39.140  7213  7213 E AgendaWidgetManager: [updateWidgets] 
,09-13 12:58:39.146  7213  7233 I InitNotificationRingtoneService: Start InitializeAlertRingtoneService.onHandleIntent
09-13 12:58:39.155  7213  7233 I AlertUtils: [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
,09-13 12:58:39.187  7213  7233 I AlertUtils: [getCalendarNotiSoundURIFromCursor] getCount()= 21
,09-13 12:58:39.199  7213  7233 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
09-13 12:58:39.207  7213  7233 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,09-13 12:58:39.216  7213  7233 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
09-13 12:58:39.224  7213  7233 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,09-13 12:58:39.233  7213  7233 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
09-13 12:58:39.238  7213  7233 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,09-13 12:58:39.244  7213  7233 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
09-13 12:58:39.248  7213  7233 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
09-13 12:58:39.254  7213  7233 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,09-13 12:58:39.260  7213  7233 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
09-13 12:58:39.264  7213  7233 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
09-13 12:58:39.268  7213  7233 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,09-13 12:58:39.273  7213  7233 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
09-13 12:58:39.279  7213  7233 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
09-13 12:58:39.285  7213  7233 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
09-13 12:58:39.286  7213  7233 I AlertUtils: [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
,09-13 12:58:39.290  7213  7233 I AlertUtils: set default noti to content://media/internal/audio/media/41
09-13 12:58:39.297  7213  7233 I InitNotificationRingtoneService: End InitializeAlertRingtoneService.onHandleIntent
09-13 12:58:39.329  7213  7213 D MonthWidgetProvider: [onReceive]
09-13 12:58:39.329  7213  7213 D CalendarWidgetProvider: [onReceive]
,09-13 12:58:39.330  7213  7213 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
09-13 12:58:39.331  7213  7239 W HolidayIntentService: onHandleIntent
09-13 12:58:39.333  7213  7239 D HolidayDataLoader: readJsonAsset : holiday.json
09-13 12:58:39.335  7213  7213 D CalendarTypeController: [onUpdateAndInitCalendarTime]
09-13 12:58:39.342  7213  7213 D WeekWidgetProvider: [onReceive]
09-13 12:58:39.342  7213  7213 D CalendarWidgetProvider: [onReceive]
09-13 12:58:39.342  7213  7213 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
09-13 12:58:39.343  7213  7213 D CalendarTypeController: [onUpdateAndInitCalendarTime]
,09-13 12:58:39.347  6308  6308 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
09-13 12:58:39.348  6308  6308 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:6591
09-13 12:58:39.356  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-13 12:58:39.357  3674  6262 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-13 12:58:39.383  2180  2180 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 12:58:39.394   308  7242 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-13 12:58:39.395   308  7242 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
09-13 12:58:39.395   308  7242 D libc-netbsd: res_queryN name = mtalk.google.com succeed
09-13 12:58:39.399  6893  6893 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 12:58:39.399  6893  6893 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 12:58:39.399  6893  6893 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 12:58:39.399  6893  6893 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-13 12:58:39.402  6893  6893 I AppUp4:CustModeStarterReceiver: onReceive
09-13 12:58:39.406  6893  6893 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2fe4a8c7
09-13 12:58:39.406  6893  6893 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 12:58:39.406  6893  6893 D AppUp4:CustFacade: isPhone : true
09-13 12:58:39.406  6893  6893 D AppUp4:CustModeStarterReceiver: begin check event
09-13 12:58:39.407  6893  6893 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 12:58:39.411  4265  4265 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 12:58:39.411  4265  4265 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-13 12:58:39.415  4265  4265 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 12:58:39.417  4265  4265 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 12:58:39.421  3427  3427 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-13 12:58:39.424  3427  3427 V DownloadManager: DownloadService onCreate
09-13 12:58:39.427  4265  7243 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-13 12:58:39.429  3427  7244 I DownloadManager: in removeSpuriousFiles
09-13 12:58:39.429  3427  7244 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-13 12:58:39.435  4265  7243 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-13 12:58:39.435  4265  7246 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 12:58:39.436  4265  7246 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 12:58:39.438  3427  7244 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1b239cec on behalf of 3427
09-13 12:58:39.439  3427  7244 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-13 12:58:39.439  3427  7244 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-13 12:58:39.439  3427  7244 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-13 12:58:39.439  3427  7244 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-13 12:58:39.439  3427  7244 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-13 12:58:39.439  3427  7244 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-13 12:58:39.439  3427  7244 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-13 12:58:39.439  3427  7244 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-13 12:58:39.439  3427  7244 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-13 12:58:39.439  3427  7244 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-13 12:58:39.439  3427  7244 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,09-13 12:58:39.445  7213  7239 E HolidayIntentService: onHandleIntent:holiday data empty
,09-13 12:58:39.449  3427  7244 I DownloadManager: in trimDatabase,
09-13 12:58:39.450  3427  7244 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-13 12:58:39.451  3427  7244 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3281e8b5 on behalf of 3427
09-13 12:58:39.462  3427  3427 V DownloadManager: DownloadService onStartCommand
,09-13 12:58:39.465  3427  7245 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-13 12:58:39.469  6925  7248 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:39.471  4265  7243 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-13 12:58:39.472  3427  7245 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@24239bd8 on behalf of 3427
09-13 12:58:39.476  4265  4265 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,09-13 12:58:39.476  4265  4265 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-13 12:58:39.477  4265  4265 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-13 12:58:39.479  3355  3355 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 12:58:39.479  3355  3355 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 12:58:39.480  3355  3355 I LgeMiscReceiver: networkInfo.isConnected() = false
09-13 12:58:39.483  3427  7245 V DownloadManager: processing inserted download 1
09-13 12:58:39.483  6962  6962 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 12:58:39.483  6962  6962 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-13 12:58:39.484  3427  7245 V DownloadManager: processing inserted download 4
09-13 12:58:39.485  4265  4265 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-13 12:58:39.486  3427  7245 V DownloadManager: processing inserted download 7
09-13 12:58:39.487  3427  7245 V DownloadManager: processing inserted download 8
,09-13 12:58:39.488  3427  7245 V DownloadManager: processing inserted download 9
09-13 12:58:39.490  3427  7245 V DownloadManager: processing inserted download 10
09-13 12:58:39.493  3427  7245 V DownloadManager: processing inserted download 11
09-13 12:58:39.494  4265  4265 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-13 12:58:39.495  3427  7245 V DownloadManager: processing inserted download 12
09-13 12:58:39.496  3427  7245 V DownloadManager: processing inserted download 13
09-13 12:58:39.497  3427  7245 V DownloadManager: processing inserted download 14
09-13 12:58:39.498  7021  7021 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:58:39
09-13 12:58:39.499  7021  7021 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,09-13 12:58:39.499  7021  7021 D Weather.Utils: 2 : All the weather widget is gone.
09-13 12:58:39.499  7021  7021 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 12:58:39.499  3427  7245 V DownloadManager: processing inserted download 16
09-13 12:58:39.500  7021  7021 D WeatherAncestor: connectivity changed - connection : true
09-13 12:58:39.500  7021  7021 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@221b061d
09-13 12:58:39.501  7021  7021 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 12:58:39.501  7021  7021 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 12:58:39.501  7021  7021 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 12:58:39.501  7021  7021 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 12:58:39.501  7021  7021 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:58:39
09-13 12:58:39.512  3427  3427 V DownloadManager: DownloadService onDestroy
,09-13 12:58:39.526  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-13 12:58:39.527  3674  6262 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-13 12:58:39.541  2180  2180 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 12:58:39.551  6893  6893 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 12:58:39.551  6893  6893 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 12:58:39.551  6893  6893 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 12:58:39.551  6893  6893 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 12:58:39.553  6893  6893 I AppUp4:CustModeStarterReceiver: onReceive
,09-13 12:58:39.557  6893  6893 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2fe4a8c7
09-13 12:58:39.557  6893  6893 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 12:58:39.557  6893  6893 D AppUp4:CustFacade: isPhone : true
09-13 12:58:39.557  6893  6893 D AppUp4:CustModeStarterReceiver: begin check event
09-13 12:58:39.557  6893  6893 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 12:58:39.560  4265  4265 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 12:58:39.560  4265  4265 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 12:58:39.560  6333  7255 V FormManager: There are no updated forms. The schedule will be deleted.
09-13 12:58:39.562  4265  4265 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 12:58:39.563  6333  7255 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-13 12:58:39.564  4265  4265 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 12:58:39.568  3427  3427 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,09-13 12:58:39.569  4265  7261 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-13 12:58:39.571  3427  3427 V DownloadManager: DownloadService onCreate
09-13 12:58:39.574  4265  7261 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-13 12:58:39.576  4265  7262 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 12:58:39.576  4265  7262 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-13 12:58:39.577  3427  7263 I DownloadManager: in removeSpuriousFiles
09-13 12:58:39.577  3427  7263 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-13 12:58:39.580  3427  7263 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@20e6f216 on behalf of 3427
,09-13 12:58:39.581  3427  7263 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-13 12:58:39.581  3427  7263 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-13 12:58:39.581  3427  7263 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-13 12:58:39.581  3427  7263 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-13 12:58:39.581  3427  7263 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-13 12:58:39.581  3427  7263 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-13 12:58:39.581  3427  7263 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-13 12:58:39.581  3427  7263 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-13 12:58:39.581  3427  7263 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-13 12:58:39.583  3427  7263 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-13 12:58:39.583  3427  7263 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-13 12:58:39.584  3427  7263 I DownloadManager: in trimDatabase
09-13 12:58:39.584  3427  7263 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-13 12:58:39.585  3427  7263 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@331bf797 on behalf of 3427
09-13 12:58:39.587  4265  7261 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-13 12:58:39.591  4265  4265 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-13 12:58:39.591  6925  7266 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:58:39.591  4265  4265 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
,09-13 12:58:39.592  4265  4265 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,09-13 12:58:39.595  4265  4265 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-13 12:58:39.595  3427  3427 V DownloadManager: DownloadService onStartCommand
09-13 12:58:39.596  3427  7264 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-13 12:58:39.598  3427  7264 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@385819a2 on behalf of 3427
09-13 12:58:39.600  4265  4265 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-13 12:58:39.600  3355  3355 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 12:58:39.601  3355  3355 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 12:58:39.601  3355  3355 I LgeMiscReceiver: networkInfo.isConnected() = false
09-13 12:58:39.602  3427  7264 V DownloadManager: processing inserted download 1
09-13 12:58:39.604  6962  6962 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 12:58:39.605  6962  6962 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-13 12:58:39.606  3427  7264 V DownloadManager: processing inserted download 4
,09-13 12:58:39.607  3427  7264 V DownloadManager: processing inserted download 7
09-13 12:58:39.608  3427  7264 V DownloadManager: processing inserted download 8
09-13 12:58:39.610  3427  7264 V DownloadManager: processing inserted download 9
09-13 12:58:39.611  3427  7264 V DownloadManager: processing inserted download 10
09-13 12:58:39.612  3427  7264 V DownloadManager: processing inserted download 11
09-13 12:58:39.613  3427  7264 V DownloadManager: processing inserted download 12
09-13 12:58:39.614  7021  7021 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:58:39
09-13 12:58:39.615  7021  7021 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 12:58:39.615  7021  7021 D Weather.Utils: 2 : All the weather widget is gone.
09-13 12:58:39.616  7021  7021 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 12:58:39.616  7021  7021 D WeatherAncestor: connectivity changed - connection : true
09-13 12:58:39.616  7021  7021 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@221b061d
09-13 12:58:39.616  7021  7021 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 12:58:39.616  7021  7021 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 12:58:39.617  7021  7021 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 12:58:39.617  7021  7021 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,09-13 12:58:39.617  7021  7021 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:58:39
09-13 12:58:39.617  3427  7264 V DownloadManager: processing inserted download 13
09-13 12:58:39.618  3427  7264 V DownloadManager: processing inserted download 14
09-13 12:58:39.619  3427  7264 V DownloadManager: processing inserted download 16
09-13 12:58:39.626  3427  3427 V DownloadManager: DownloadService onDestroy
09-13 12:58:39.638  2180  2180 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-13 12:58:39.645  2180  2180 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
09-13 12:58:39.645  2180  2180 D c       : Getting all permits...
09-13 12:58:39.645  2180  2180 D a       : Opening database...
09-13 12:58:39.648  2180  2180 D a       : Opening database auth.proximity.permit_store...
,09-13 12:58:39.649  2180  2180 D a       : Closing database...
,09-13 12:58:39.660  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-13 12:58:39.663  3674  6262 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-13 12:58:39.665  2180  7259 D GCM     : Connected
,09-13 12:58:39.685  6333  7269 V FormManager: There are no updated forms. The schedule will be deleted.
09-13 12:58:39.687  2180  2180 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-13 12:58:39.691  6333  7269 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-13 12:58:39.693  2180  7259 D GCM     : Message class com.google.e.a.a.q
09-13 12:58:39.698  1809  7272 I CheckinService: active receiver: disabled
09-13 12:58:39.699  6893  6893 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-13 12:58:39.699  6893  6893 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-13 12:58:39.699  6893  6893 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-13 12:58:39.700  6893  6893 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-13 12:58:39.701  6893  6893 I AppUp4:CustModeStarterReceiver: onReceive
,09-13 12:58:39.704  6893  6893 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2fe4a8c7
09-13 12:58:39.704  6893  6893 D AppUp4:CustFacade: isCustomizationCompleted : false
09-13 12:58:39.704  6893  6893 D AppUp4:CustFacade: isPhone : true
09-13 12:58:39.705  6893  6893 D AppUp4:CustModeStarterReceiver: begin check event
09-13 12:58:39.705  6893  6893 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-13 12:58:39.708  4265  4265 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-13 12:58:39.708  4265  4265 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-13 12:58:39.710  4265  4265 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 12:58:39.712  4265  4265 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-13 12:58:39.717  3427  3427 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-13 12:58:39.717  4265  7273 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-13 12:58:39.719  4265  7273 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-13 12:58:39.720  1032  2026 I ActivityManager: Killing 6263:com.lge.sync/1000 (adj 15): empty #17
09-13 12:58:39.721  4265  7274 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-13 12:58:39.721  4265  7274 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-13 12:58:39.722  3427  3427 V DownloadManager: DownloadService onCreate
09-13 12:58:39.729  3427  7275 I DownloadManager: in removeSpuriousFiles
09-13 12:58:39.729  3427  7275 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,09-13 12:58:39.731  3427  7275 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2bee0df0 on behalf of 3427
09-13 12:58:39.731  3427  7275 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-13 12:58:39.731  3427  7275 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-13 12:58:39.731  3427  7275 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-13 12:58:39.732  3427  7275 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-13 12:58:39.732  3427  7275 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-13 12:58:39.732  3427  7275 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-13 12:58:39.732  3427  7275 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-13 12:58:39.732  3427  7275 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-13 12:58:39.732  3427  7275 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-13 12:58:39.732  3427  7275 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-13 12:58:39.732  3427  7275 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-13 12:58:39.734  3427  7275 I DownloadManager: in trimDatabase
09-13 12:58:39.735  3427  7275 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-13 12:58:39.737  3427  7275 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3ec22dee on behalf of 3427
09-13 12:58:39.737  1032  1442 D WifiService: Client connection lost with reason: 4
09-13 12:58:39.753  1032  1935 W libprocessgroup: failed to open /acct/uid_1000/pid_6263/cgroup.procs: No such file or directory
,09-13 12:58:39.753  3427  3427 V DownloadManager: DownloadService onStartCommand
09-13 12:58:39.753  3427  7276 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-13 12:58:39.754  3427  7276 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@dbe191c on behalf of 3427
09-13 12:58:39.756  4265  7273 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-13 12:58:39.757  3427  7276 V DownloadManager: processing inserted download 1
09-13 12:58:39.759  3427  7276 V DownloadManager: processing inserted download 4
09-13 12:58:39.760  3427  7276 V DownloadManager: processing inserted download 7
09-13 12:58:39.760  4265  4265 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-13 12:58:39.760  4265  4265 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-13 12:58:39.761  4265  4265 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-13 12:58:39.763  4265  4265 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-13 12:58:39.763  3427  7276 V DownloadManager: processing inserted download 8
,09-13 12:58:39.764  3427  7276 V DownloadManager: processing inserted download 9
09-13 12:58:39.765  3427  7276 V DownloadManager: processing inserted download 10
09-13 12:58:39.765  3427  7276 V DownloadManager: processing inserted download 11
09-13 12:58:39.766  3427  7276 V DownloadManager: processing inserted download 12
09-13 12:58:39.767  3427  7276 V DownloadManager: processing inserted download 13
09-13 12:58:39.767  4265  4265 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-13 12:58:39.767  3427  7276 V DownloadManager: processing inserted download 14
09-13 12:58:39.769  3427  7276 V DownloadManager: processing inserted download 16
09-13 12:58:39.775  3427  3427 V DownloadManager: DownloadService onDestroy
09-13 12:58:39.780  3355  3355 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-13 12:58:39.780  3355  3355 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-13 12:58:39.780  3355  3355 I LgeMiscReceiver: networkInfo.isConnected() = true
,09-13 12:58:39.780  3355  3355 D PhoneState: setPdpRejectCasuse : false
,09-13 12:58:39.785  6962  6962 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-13 12:58:39.786  6962  6962 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-13 12:58:39.795  7021  7021 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:58:39
09-13 12:58:39.796  6925  7279 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 12:58:39.797  7021  7021 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 12:58:39.797  7021  7021 D Weather.Utils: 2 : All the weather widget is gone.
09-13 12:58:39.797  7021  7021 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 12:58:39.797  7021  7021 D WeatherAncestor: connectivity changed - connection : true
09-13 12:58:39.797  7021  7021 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@221b061d
09-13 12:58:39.798  7021  7021 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-13 12:58:39.798  7021  7021 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-13 12:58:39.798  7021  7021 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-13 12:58:39.798  7021  7021 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-13 12:58:39.798  7021  7021 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:58:39
09-13 12:58:39.818  7165  7165 I DigitalAppWidgetProvider: onReceive: android.intent.action.ALARM_CHANGED
,09-13 12:58:39.821  7021  7021 D WeatherAncestor: 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 12:58:39
09-13 12:58:39.822  7021  7021 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-13 12:58:39.822  7021  7021 D Weather.Utils: 2 : All the weather widget is gone.
09-13 12:58:39.823  7021  7021 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-13 12:58:39.824  7021  7021 D Weather_cast: 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
09-13 12:58:39.824  7021  7021 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 12:58:39,
09-13 12:58:39.828  2028  2028 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
09-13 12:58:39.829  2028  2814 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
09-13 12:58:39.829  2028  2814 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
09-13 12:58:39.830  2028  2814 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
,09-13 12:58:39.830  5069  5069 V [BNRBootReceiver]: boot receiver action = com.lge.bnr.releasebadge
09-13 12:58:39.831  5069  5069 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
09-13 12:58:39.832  2028  2814 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
09-13 12:58:39.832  2028  2814 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
09-13 12:58:39.833  1599  1599 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
09-13 12:58:39.833  1599  1599 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
09-13 12:58:39.833  1599  1599 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
09-13 12:58:39.835  5069  5069 V [BNRBootReceiver]: Boot Receiver Return
09-13 12:58:39.837  6333  7282 V FormManager: There are no updated forms. The schedule will be deleted.
09-13 12:58:39.840  6333  7282 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-13 12:58:39.841  2180  2180 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-13 12:58:39.857  2180  2180 I GCM     : GCM config loaded
,09-13 12:58:39.878  6962  6962 V SetupWizard: Connected to Gservices successfully
,09-13 12:58:39.888  2180  2180 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
09-13 12:58:39.903  2028  2028 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
,09-13 12:58:39.905  2028  5378 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
09-13 12:58:39.905  2028  5378 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
09-13 12:58:39.905  2028  5378 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
09-13 12:58:39.906  2028  5378 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
09-13 12:58:39.906  2028  5378 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
09-13 12:58:40.490  1032  1390 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=16.5, 0.0, 0.0  rx=12.2 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:590537962] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-13 12:58:40.503  1032  1390 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=16.5, 0.0, 0.0  rx=12.2 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:590537975] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-13 12:58:40.503  1032  1390 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-13 12:58:40.897  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:58:40.897  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 12:58:40.897  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:40.898  6160  6233 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3048ad3e not in the list
,09-13 12:58:40.898  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:58:40.898  6160  6233 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2faed79f not in the list
09-13 12:58:40.898  6160  6233 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:58:40.898  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 12:58:40.898  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 12:58:40.914  6160  6233 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:58:40.914  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:40.915  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:40.915  6160  6233 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3048ad3e not in the list
09-13 12:58:40.915  6160  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:58:40.915  6160  6233 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2faed79f not in the list
09-13 12:58:40.915  6160  6233 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:58:40.915  6160  6233 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:58:40.915  6160  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:58:40.917  6160  6233 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-13 12:58:40.917  6160  6233 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 12:58:40.917  6160  6233 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-13 12:58:40.917  6160  6233 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 12:58:40.918  6160  6233 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 12:58:40.918  6160  6233 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 12:58:40.932  6160  7297 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 900, name: My test thread name)
,09-13 12:58:42.373  7060  7080 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-13 12:58:42.931  6160  6233 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 900
09-13 12:58:42.932  6160  6233 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 900, name: My test thread name)
,09-13 12:58:42.938  6160  7300 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 901, name: My test thread name)
09-13 12:58:42.938  6160  7300 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 901, thread name: My test thread name)
09-13 12:58:42.938  6160  7300 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 901, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-13 12:58:42.940  6160  6233 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 12:58:42.944  6160  7301 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 905, name: My test thread name)
09-13 12:58:42.945  6160  7301 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 905, thread name: My test thread name): Test exception.
09-13 12:58:42.945  6160  7301 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 905, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-13 12:58:42.946  6160  6233 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.OutgoingSocketThreadTest)
09-13 12:58:42.946  6160  6233 E com.test.thalitest.ThaliTestRunner: OutgoingSocketThread should get inputStream from IncomingSocketThread and copy it to local outgoingOutputStream
09-13 12:58:42.946  6160  6233 E com.test.thalitest.ThaliTestRunner: Expected: is "Lorem ipsum dolor sit amet elit nibh, imperdiet dignissim, imperdiet wisi. Morbi vel risus. Nunc molestie placerat, nulla mi, id nulla ornare risus. Sed lacinia, urna eros lacus, elementum eu."
09-13 12:58:42.946  6160  6233 E com.test.thalitest.ThaliTestRunner:      but: was ""
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: OutgoingSocketThread should get inputStream from IncomingSocketThread and copy it to local outgoingOutputStream
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: Expected: is "Lorem ipsum dolor sit amet elit nibh, imperdiet dignissim, imperdiet wisi. Morbi vel risus. Nunc molestie placerat, nulla mi, id nulla ornare risus. Sed lacinia, urna eros lacus, elementum eu."
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner:      but: was ""
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.OutgoingSocketThreadTest.testRun(OutgoingSocketThreadTest.java:174)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	,at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:74)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:81)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
09-13 ,12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.loopOnce(Native Method)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$6$1.run(jxcore.java:348)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:135)
09-13 12:58:42.948  6160  6233 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
09-13 12:58:42.949  6160  6233 I jxcore-log: Total number of executed tests:  82
09-13 12:58:42.949  6160  6233 I jxcore-log: 
09-13 12:58:42.950  6160  6233 I jxcore-log: Number of passed tests:  81
09-13 12:58:42.950  6160  6233 I jxcore-log: 
09-13 12:58:42.950  6160  6233 I jxcore-log: Number of failed tests:  1
09-13 12:58:42.950  6160  6233 I jxcore-log: 
09-13 12:58:42.951  6160  6233 I jxcore-log: Number of ignored tests:  0
09-13 12:58:42.951  6160  6233 I jxcore-log: 
09-13 12:58:42.951  6160  6233 I jxcore-log: Total duration:  19489
09-13 12:58:42.951  6160  6233 I jxcore-log: 
,09-13 12:58:42.957  6160  6233 I jxcore-log: Failed to execute UT.
09-13 12:58:42.957  6160  6233 I jxcore-log: 
09-13 12:58:42.958  6160  6233 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
09-13 12:58:42.958  6160  6233 I jxcore-log: 
09-13 12:58:42.963  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:58:42.963  6160  6233 I jxcore-log: 
09-13 12:58:42.965  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:58:42.965  6160  6233 I jxcore-log: 
09-13 12:58:42.966  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:58:42.966  6160  6233 I jxcore-log: 
09-13 12:58:42.967  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:58:42.967  6160  6233 I jxcore-log: 
09-13 12:58:42.968  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:58:42.968  6160  6233 I jxcore-log: 
09-13 12:58:42.971  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:58:42.971  6160  6233 I jxcore-log: 
,09-13 12:58:42.976  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:58:42.976  6160  6233 I jxcore-log: 
09-13 12:58:42.977  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 12:58:42.977  6160  6233 I jxcore-log: 
09-13 12:58:42.978  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 12:58:42.978  6160  6233 I jxcore-log: 
09-13 12:58:42.979  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 12:58:42.979  6160  6233 I jxcore-log: 
09-13 12:58:42.980  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 12:58:42.980  6160  6233 I jxcore-log: 
09-13 12:58:42.981  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 12:58:42.981  6160  6233 I jxcore-log: 
09-13 12:58:42.984  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:58:42.984  6160  6233 I jxcore-log: 
09-13 12:58:42.985  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:58:42.985  6160  6233 I jxcore-log: 
09-13 12:58:42.986  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:58:42.986  6160  6233 I jxcore-log: 
09-13 12:58:42.986  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:58:42.986  6160  6233 I jxcore-log: 
09-13 12:58:42.987  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 12:58:42.987  6160  6233 I jxcore-log: 
09-13 12:58:42.988  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 12:58:42.988  6160  6233 I jxcore-log: 
09-13 12:58:42.989  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 12:58:42.989  6160  6233 I jxcore-log: 
09-13 12:58:42.989  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 12:58:42.989  6160  6233 I jxcore-log: 
09-13 12:58:42.990  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:58:42.990  6160  6233 I jxcore-log: 
09-13 12:58:42.991  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:58:42.991  6160  6233 I jxcore-log: 
09-13 12:58:42.991  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:58:42.991  6160  6233 I jxcore-log: 
,09-13 12:58:42.996  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:58:42.996  6160  6233 I jxcore-log: 
09-13 12:58:42.997  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 12:58:42.997  6160  6233 I jxcore-log: 
09-13 12:58:42.998  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 12:58:42.998  6160  6233 I jxcore-log: 
09-13 12:58:42.998  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 12:58:42.998  6160  6233 I jxcore-log: 
09-13 12:58:42.999  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 12:58:42.999  6160  6233 I jxcore-log: 
09-13 12:58:43.000  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:58:43.000  6160  6233 I jxcore-log: 
09-13 12:58:43.000  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:58:43.000  6160  6233 I jxcore-log: 
09-13 12:58:43.001  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:58:43.001  6160  6233 I jxcore-log: 
09-13 12:58:43.004  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:58:43.004  6160  6233 I jxcore-log: 
09-13 12:58:43.005  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 12:58:43.005  6160  6233 I jxcore-log: 
09-13 12:58:43.005  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 12:58:43.005  6160  6233 I jxcore-log: 
09-13 12:58:43.006  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 12:58:43.006  6160  6233 I jxcore-log: 
09-13 12:58:43.007  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 12:58:43.007  6160  6233 I jxcore-log: 
09-13 12:58:43.008  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:58:43.008  6160  6233 I jxcore-log: 
09-13 12:58:43.008  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:58:43.008  6160  6233 I jxcore-log: 
09-13 12:58:43.009  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:58:43.009  6160  6233 I jxcore-log: 
09-13 12:58:43.010  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:58:43.010  6160  6233 I jxcore-log: 
09-13 12:58:43.011  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:58:43.011  6160  6233 I jx,core-log: 
09-13 12:58:43.011  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:58:43.011  6160  6233 I jxcore-log: 
,09-13 12:58:43.016  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:58:43.016  6160  6233 I jxcore-log: 
09-13 12:58:43.017  6160  6233 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:58:43.017  6160  6233 I jxcore-log: 
09-13 12:58:43.066  6160  7297 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 900, name: My test thread name), during the lifetime of the thread the total number of bytes read was 121 and the total number of bytes written 121
,09-13 12:58:43.222  7302  7302 D AndroidRuntime: 
09-13 12:58:43.222  7302  7302 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-13 12:58:43.227  7302  7302 D AndroidRuntime: CheckJNI is OFF
09-13 12:58:43.242  1032  1990 I ActivityManager: Killing 6285:com.android.settings/1000 (adj 15): empty #17
,09-13 12:58:43.404  1032  1047 W libprocessgroup: failed to open /acct/uid_1000/pid_6285/cgroup.procs: No such file or directory
,09-13 12:58:43.425  7302  7302 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-13 12:58:43.439  1032  1727 I ActivityManager: Killing 7193:com.qualcomm.timeservice/1000 (adj 15): empty #17
,09-13 12:58:43.493  1032  1089 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
09-13 12:58:43.493  1032  1089 I ActivityManager: Killing 6160:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,09-13 12:58:43.519  1032  1390 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=25.8, 0.0, 0.0  rx=19.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:590540991] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 12:58:43.520  1032  1390 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=25.8, 0.0, 0.0  rx=19.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:590540992] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-13 12:58:43.520  1032  1390 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-13 12:58:43.554  1032  1989 I WindowState: WIN DEATH: Window{3c0a5727 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 12:58:43.555  1032  1442 D WifiService: Client connection lost with reason: 4
09-13 12:58:43.573  1032  1989 D InputDispatcher: Window went away: Window{3c0a5727 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 12:58:43.717  1032  1089 I ActivityManager:   Force finishing activity ActivityRecord{18ebe4e0 u0 com.test.thalitest/.MainActivity t6}
,09-13 12:58:43.754   346   410 E GBMv2   : DFP En is all cleared set to be enabled
09-13 12:58:43.758  1032  1899 W libprocessgroup: failed to open /acct/uid_1000/pid_7193/cgroup.procs: No such file or directory
,09-13 12:58:43.773  1032  1100 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-13 12:58:43.774  1032  1100 I ActivityManager:   Force finishing activity ActivityRecord{18ebe4e0 u0 com.test.thalitest/.MainActivity t6 f}
09-13 12:58:43.774  1032  1100 W ActivityManager: Duplicate finish request for ActivityRecord{18ebe4e0 u0 com.test.thalitest/.MainActivity t6 f}
,09-13 12:58:43.841  1032  2027 W ActivityManager: Spurious death for ProcessRecord{d4fc967 6160:com.test.thalitest/u0a118}, curProc for 6160: null
,09-13 12:58:43.844  1936  3930 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-13 12:58:43.844  1936  3930 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1ede9357 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-13 12:58:43.845  2028  2028 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-13 12:58:43.847  2028  2028 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-13 12:58:43.848  1936  1952 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-13 12:58:43.848  1936  1952 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1f36e44 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-13 12:58:43.850  4532  4532 I art     : Explicit concurrent mark sweep GC freed 747(42KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 531us total 62.592ms
09-13 12:58:43.853  2028  2028 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-13 12:58:43.854  2028  2100 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,09-13 12:58:43.854  1599  1599 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-13 12:58:43.869  1032  1378 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-13 12:58:43.878  2491  2637 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-13 12:58:43.879  1991  1991 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-13 12:58:43.880  3768  3768 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
09-13 12:58:43.883  3826  3826 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-13 12:58:43.883  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-13 12:58:43.912  1032  1088 W InputMethodInfo: Duplicated subtype definition found: , voice
,09-13 12:58:43.939  3674  3674 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,09-13 12:58:43.942  4419  4419 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-13 12:58:43.943  4419  4419 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-13 12:58:43.943  4419  4419 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-13 12:58:43.943  4419  4419 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-13 12:58:43.943  4419  4419 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 12:58:43.944  4419  4419 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 12:58:43.944  4419  4419 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-13 12:58:43.944  4419  4419 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 12:58:43.944  4419  4419 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 12:58:43.944  4419  4419 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 12:58:43.944  4419  4419 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 12:58:43.944  4419  4419 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 12:58:43.969  1864  1864 D SplitUIManager: split_name #11 / not available #0
09-13 12:58:43.970  1864  1864 D SplitUIService: removed split : 
,09-13 12:58:43.981  1032  1572 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7341 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
09-13 12:58:43.981   350   350 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 270us total 13.275ms
09-13 12:58:43.982  2028  2028 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,09-13 12:58:43.984  1809  1809 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-13 12:58:43.992  1901  1901 D ActionManagerService: notifyUserLog: 1000003
,09-13 12:58:43.992  3768  4413 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-13 12:58:43.995   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 229us total 12.474ms
09-13 12:58:43.996  2180  2180 I ConfigService: onCreate
09-13 12:58:44.000  2028  2028 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-13 12:58:44.001  1599  1599 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-13 12:58:44.001  2180  2180 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-13 12:58:44.002  2028  2028 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-13 12:58:44.004  1809  1809 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-13 12:58:44.006  2028  2028 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-13 12:58:44.007   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 204us total 11.484ms
,09-13 12:58:44.012  1864  1864 D SplitUIManager: split_name #11 / not available #0
09-13 12:58:44.012  1864  1864 I SplitUIService: split app #11
09-13 12:58:44.016  1901  1901 D ActionManagerService: notifyUserLog: 1000004
09-13 12:58:44.016  3768  4413 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-13 12:58:44.017  2028  2028 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-13 12:58:44.018  3768  4411 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-13 12:58:44.021  2028  2028 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-13 12:58:44.021  2028  2028 I GBoardWebViewUtils: , create_time: 1430832262123
09-13 12:58:44.021  2028  2028 I GBoardWebViewUtils: , expire_time: 0
09-13 12:58:44.021  2028  2028 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-13 12:58:44.021  2028  2028 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-13 12:58:44.021  2028  2028 I GBoardWebViewUtils: , display: false
09-13 12:58:44.021  2028  2028 I GBoardWebViewUtils: , animation: false }
09-13 12:58:44.021  2028  2028 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-13 12:58:44.021  2028  2028 I GBoardWebViewUtils: , create_time: 1430832262287
09-13 12:58:44.021  2028  2028 I GBoardWebViewUtils: , expire_time: 0
09-13 12:58:44.021  2028  2028 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-13 12:58:44.021  2028  2028 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-13 12:58:44.021  2028  2028 I GBoardWebViewUtils: , display: false
09-13 12:58:44.021  2028  2028 I GBoardWebViewUtils: , animation: false }
09-13 12:58:44.021  2028  2028 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1473420112499
09-13 12:58:44.021  2028  2028 I GBoardWebViewUtils: , create_time: 1473420113195
09-13 12:58:44.021  2028  2028 I GBoardWebViewUtils: , expire_time: 0
09-13 12:58:44.021  2028  2028 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-13 12:58:44.021  2028  2028 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-13 12:58:44.021  2028  2028 I GBoardWebViewUtils: , display: false
09-13 12:58:44.021  2028  2028 I GBoardWebViewUtils: , animation: false }
09-13 12:58:44.024  2180  2180 I ConfigService: onBind returning update interface
,09-13 12:58:44.030  1032  1954 V SIM_STK : Menu title from STK is T-Mobile
09-13 12:58:44.034  2028  7361 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-13 12:58:44.041  2180  2180 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-13 12:58:44.041  2180  2180 I ConfigService: onBind returning config service
,09-13 12:58:44.042  1599  1599 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-13 12:58:44.042  1599  1599 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-13 12:58:44.051  2180  2180 I ConfigService: onDestroy
09-13 12:58:44.057  1809  7362 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-13 12:58:44.062  1032  1032 I art     : Explicit concurrent mark sweep GC freed 42244(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 2.182ms total 246.059ms
09-13 12:58:44.063  1032  1100 I art     : WaitForGcToComplete blocked for 216.695ms for cause Explicit
09-13 12:58:44.091  1032  1900 V SIM_STK : Menu title from STK is T-Mobile
09-13 12:58:44.091  1032  1900 V SIM_STK : Menu title from STK is T-Mobile
,09-13 12:58:44.145  1032  1032 D administrator: Handling package changes for user 0
,09-13 12:58:44.156  5495  7367 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
09-13 12:58:44.157  1032  1953 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-13 12:58:44.158  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-13 12:58:44.158  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-13 12:58:44.158  6893  6893 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
09-13 12:58:44.158  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-13 12:58:44.158  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-13 12:58:44.158  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-13 12:58:44.158  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 12:58:44.158  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-13 12:58:44.158  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-13 12:58:44.158  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-13 12:58:44.158  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 12:58:44.158  3826  3826 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-13 12:58:44.165  1809  7370 I PeopleContactsSync: CP2 sync disabled
,09-13 12:58:44.169   331   404 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,09-13 12:58:44.169  3195  7373 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-13 12:58:44.194  1032  1990 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7374 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-13 12:58:44.197  1032  1771 V SIM_STK : Menu title from STK is T-Mobile
,09-13 12:58:44.209  1809  4665 I Icing   : doRemovePackageData com.test.thalitest
,09-13 12:58:44.213  1809  7368 W GmsApplication: Using Auth Proxy for data requests.
09-13 12:58:44.224  1032  1032 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-13 12:58:44.224  1032  1032 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-13 12:58:44.224  1032  1032 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-13 12:58:44.229  1032  1574 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-13 12:58:44.236  1032  1100 I art     : Explicit concurrent mark sweep GC freed 6393(311KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.355ms total 172.773ms
,09-13 12:58:44.238  1032  1899 I art     : WaitForGcToComplete blocked for 193.945ms for cause Explicit
09-13 12:58:44.242  2180  2196 I art     : Explicit concurrent mark sweep GC freed 7948(511KB) AllocSpace objects, 8(128KB) LOS objects, 52% free, 29MB/61MB, paused 681us total 22.375ms
09-13 12:58:44.249  1809  7368 W GmsApplication: Using Auth Proxy for data requests.
,09-13 12:58:44.308  1032  1899 I art     : Explicit concurrent mark sweep GC freed 4761(273KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.709ms total 69.202ms
,09-13 12:58:44.321  2028  2028 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-13 12:58:44.321  2028  2028 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,09-13 12:58:44.341  7374  7374 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 12:58:44.341  7374  7374 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 12:58:44.342  7374  7374 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,09-13 12:58:44.342  7374  7374 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-13 12:58:44.342  7374  7374 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 12:58:44.343  7302  7302 D AndroidRuntime: Shutting down VM
09-13 12:58:44.346  7341  7341 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
09-13 12:58:44.374  1032  1100 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7394 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-13 12:58:44.384  1599  1650 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-13 12:58:44.384  1599  1650 D KeyguardModel: createShortcutInfo...
09-13 12:58:44.388  1599  1650 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-13 12:58:44.388  1599  1650 D KeyguardModel: createShortcutInfo...
09-13 12:58:44.393  1032  1088 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 12:58:44.394  2028  2028 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-13 12:58:44.397  1032  1088 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-13 12:58:44.398  1599  1650 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-13 12:58:44.399  1599  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 12:58:44.399  1599  1650 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-13 12:58:44.400  1599  1650 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-13 12:58:44.402  1599  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 12:58:44.402  1599  1650 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-13 12:58:44.402  7374  7374 I SystemConfig: BUILD Country: EU
09-13 12:58:44.403  1599  1650 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-13 12:58:44.403  1599  1650 D KeyguardModel: createShortcutInfo...
09-13 12:58:44.406  1599  1650 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-13 12:58:44.406  1599  1650 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 12:58:44.406  1599  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 12:58:44.406  1599  1650 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-13 12:58:44.407  7374  7374 I SystemConfig: BUILD Operator: OPEN
09-13 12:58:44.407  1599  1650 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-13 12:58:44.407  1599  1650 D KeyguardModel: createShortcutInfo...
,09-13 12:58:44.411  1599  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 12:58:44.411  1599  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-13 12:58:44.412  1599  1650 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-13 12:58:44.412  1599  1650 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-13 12:58:44.412  1599  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 12:58:44.412  1599  1650 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-13 12:58:44.413  1599  1650 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-13 12:58:44.413  1599  1650 D KeyguardModel: createShortcutInfo...
09-13 12:58:44.415  1599  1599 D KeyguardModel: handleShortcutListChanged...
09-13 12:58:44.415  1599  1599 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-13 12:58:44.419  1599  1650 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-13 12:58:44.419  1599  1650 D KeyguardModel: createShortcutInfo...
09-13 12:58:44.423  1599  1650 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-13 12:58:44.423  1599  1650 D KeyguardModel: createShortcutInfo...
,09-13 12:58:44.424  1599  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 12:58:44.424  1599  1650 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-13 12:58:44.425  1599  1650 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-13 12:58:44.425  1599  1650 D KeyguardModel: createShortcutInfo...
09-13 12:58:44.425  1599  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 12:58:44.426  1599  1650 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-13 12:58:44.429  1599  1650 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-13 12:58:44.429  1599  1650 D KeyguardModel: createShortcutInfo...
,09-13 12:58:44.430  1599  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 12:58:44.430  1599  1650 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-13 12:58:44.431  1599  1650 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-13 12:58:44.431  1599  1650 D KeyguardModel: createShortcutInfo...
09-13 12:58:44.444  1032  1572 I ActivityManager: Killing 6039:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
09-13 12:58:44.456  6308  6308 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-13 12:58:44.457  6308  6308 W System.err: android.os.DeadObjectException
09-13 12:58:44.457  6308  6308 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 12:58:44.457  6308  6308 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-13 12:58:44.457  6308  6308 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-13 12:58:44.457  6308  6308 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-13 12:58:44.457  6308  6308 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-13 12:58:44.457  6308  6308 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-13 12:58:44.457  6308  6308 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
,09-13 12:58:44.457  6308  6308 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 12:58:44.457  6308  6308 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-13 12:58:44.457  6308  6308 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 12:58:44.457  6308  6308 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 12:58:44.457  6308  6308 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 12:58:44.457  6308  6308 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 12:58:44.457  6308  6308 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 12:58:44.457  6308  6308 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-13 12:58:44.457  6308  6308 W System.err: android.os.DeadObjectException
09-13 12:58:44.458  6308  6308 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 12:58:44.458  6308  6308 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-13 12:58:44.458  6308  6308 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-13 12:58:44.458  6308  6308 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-13 12:58:44.458  6308  6308 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-13 12:58:44.458  6308  6308 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-13 12:58:44.458  6308  6308 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 12:58:44.458  6308  6308 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 12:58:44.458  6308  6308 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-13 12:58:44.458  6308  6308 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 12:58:44.458  6308  6308 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 12:58:44.458  6308  6308 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 12:58:44.458  6308  6308 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 12:58:44.458  6308  6308 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 12:58:44.458  6308  6308 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-13 12:58:44.458  6308  6308 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
09-13 12:58:44.459  2028  2028 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
09-13 12:58:44.462  2028  2028 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 12:58:44.464  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-13 12:58:44.465  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-13 12:58:44.466  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-13 12:58:44.466  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-13 12:58:44.480  2028  2028 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-13 12:58:44.481  2028  2028 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-13 12:58:44.481  2028  2028 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 12:58:44.481  2028  2149 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-13 12:58:44.481  2028  2149 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-13 12:58:44.494  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,09-13 12:58:44.495  2028  2028 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-13 12:58:44.495  2028  2028 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 12:58:44.501  2028  2028 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-13 12:58:44.604  1032  1900 I ActivityManager: Killing 7213:com.android.calendar/u0a13 (adj 15): empty #17
,09-13 12:58:44.633  1032  1048 W libprocessgroup: failed to open /acct/uid_1000/pid_6039/cgroup.procs: No such file or directory
09-13 12:58:44.633  1599  1599 D KeyguardModel: handleShortcutListChanged...
09-13 12:58:44.633  1599  1599 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-13 12:58:44.633  1032  1048 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-13 12:58:44.636  6308  6308 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-13 12:58:44.636  6308  6308 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-13 12:58:44.637  1032  1899 W libprocessgroup: failed to open /acct/uid_10013/pid_7213/cgroup.procs: No such file or directory
09-13 12:58:44.638  2621  2621 D [Concierge]Service: onStartCommand(). Type : 8
09-13 12:58:44.638  2621  2621 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-13 12:58:44.639  1032  1095 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{300a4a74 u0 com.lge.launcher2/.Launcher t5} time:216847
09-13 12:58:44.640  2621  2621 D [Concierge]Service: Update widget ID : 11
09-13 12:58:44.641  1032  1048 I ActivityManager: Killing 6308:com.lge.qremote/u0a112 (adj 15): empty #17
09-13 12:58:44.641  2028  2028 D [Concierge]WidgetView: change position of spinner
09-13 12:58:44.673  2028  2028 I [Concierge]WidgetView: initWebView(). Time : 1473764324673
09-13 12:58:44.674  2621  2621 D [Concierge]Service: onStartCommand(). Type : 0
,09-13 12:58:44.676  2370  2460 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
09-13 12:58:44.678  2370  7419 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-13 12:58:44.680  2370  2460 D ContactsProvider2ForLG: performBackgroundTask SQLiteDiskIOException during query
09-13 12:58:44.680  2370  2460 D ContactsProvider2ForLG: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 12:58:44.680  2370  2460 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-13 12:58:44.680  2370  2460 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
09-13 12:58:44.680  2370  2460 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-13 12:58:44.680  2370  2460 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-13 12:58:44.680  2370  2460 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-13 12:58:44.680  2370  2460 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
09-13 12:58:44.680  2370  2460 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
09-13 12:58:44.680  2370  2460 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
09-13 12:58:44.680  2370  2460 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
09-13 12:58:44.680  2370  2460 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
09-13 12:58:44.680  2370  2460 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
09-13 12:58:44.680  2370  2460 D ContactsProvider2ForLG: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:58:44.680  2370  2460 D ContactsProvider2ForLG: 	at android.os.Looper.loop(Looper.java:135)
09-13 12:58:44.680  2370  2460 D ContactsProvider2ForLG: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 12:58:44.682  2370  7419 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
09-13 12:58:44.683  2370  7419 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-13 12:58:44.683  2370  7419 E AndroidRuntime: Process: android.process.acore, PID: 2370
09-13 12:58:44.683  2370  7419 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 12:58:44.683  2370  7419 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 12:58:44.683  2370  7419 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
09-13 12:58:44.683  2370  7419 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
09-13 12:58:44.683  2370  7419 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 12:58:44.683  2370  7419 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
09-13 12:58:44.683  2370  7419 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
09-13 12:58:44.683  2370  7419 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
09-13 12:58:44.683  2370  7419 E AndroidRuntime: 	at com.android.providers.c,ontacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
09-13 12:58:44.683  2370  7419 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
09-13 12:58:44.683  2370  7419 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
09-13 12:58:44.683  2370  7419 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-13 12:58:44.683  2370  7419 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-13 12:58:44.683  2370  7419 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-13 12:58:44.683  2370  7419 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:58:44.683  2370  7419 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
09-13 12:58:44.683  2370  7419 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 12:58:44.704  1032  1572 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7420 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-13 12:58:44.705  1032  1899 W libprocessgroup: failed to open /acct/uid_10112/pid_6308/cgroup.procs: No such file or directory
09-13 12:58:44.708  7374  7416 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-13 12:58:44.708  7374  7416 I SystemConfig: existFile = false
09-13 12:58:44.708  7374  7416 I SystemConfig: canReadFile = false
09-13 12:58:44.708  7374  7416 I SystemConfig: systemFeature RCS result false
09-13 12:58:44.708  7374  7416 D SystemConfig: refreshRcsSupport() :false
09-13 12:58:44.708  2028  2028 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/com.lge.concierge.widgetbroadcast.map.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/com.lge.concierge.widgetbroadcast.map.xml.bak
09-13 12:58:44.710  2028  2028 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/com.lge.concierge.widgetbroadcast.map.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/com.lge.concierge.widgetbroadcast.map.xml.bak
09-13 12:58:44.711  2370  7419 I Process : Sending signal. PID: 2370 SIG: 9
09-13 12:58:44.711  2028  2028 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 821632537
09-13 12:58:44.712  6925  6925 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
09-13 12:58:44.712  2028  2028 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-13 12:58:44.712  2028  2028 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-13 12:58:44.713  1032  7430 E DropBoxManagerService: Can't write: system_app_crash
09-13 12:58:44.713  1032  7430 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-13 12:58:44.713  1032  7430 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-13 12:58:44.713  1032  7430 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 12:58:44.713  1032  7430 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 12:58:44.713  1032  7430 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 12:58:44.713  1032  7430 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-13 12:58:44.713  1032  7430 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
09-13 12:58:44.713  1032  7430 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 12:58:44.713  1032  7430 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 12:58:44.713  1032  7430 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 12:58:44.713  1032  7430 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-13 12:58:44.713  1032  7430 E DropBoxManagerService: 	... 5 more
09-13 12:58:44.716  2028  2028 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@17ec64dc

```
