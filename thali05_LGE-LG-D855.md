#### Test 80598264be6cebf_thali05_LGE-LG-D855 Logs


```
--------- beginning of system
08-09 13:03:51.996  1030  1372 V AlarmManager: ELAPSED_WAKEUP set : Alarm{34fa627c type 2 when 175046 com.google.android.gms} when 175046
--------- beginning of main
08-09 13:03:52.020   328  5968 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-09 13:03:52.022  1030  1099 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-09 13:03:54.035  5979  5979 D AndroidRuntime: 
08-09 13:03:54.035  5979  5979 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-09 13:03:54.038  5979  5979 D AndroidRuntime: CheckJNI is OFF
08-09 13:03:54.165  5979  5979 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-09 13:03:54.169  1030  1721 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-09 13:03:54.178  1936  1952 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-09 13:03:54.182  1030  1721 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-09 13:03:54.183  1030  1721 V ActivityStackEx: create ActivityStackEx
08-09 13:03:54.197  1030  1721 D ActivityManager: setTaskToReturnTo : TaskRecord{3845135a #2 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-09 13:03:54.197  1030  1721 D ActivityManager: setTaskToReturnTo : TaskRecord{3845135a #2 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-09 13:03:54.200  1030  1721 D WindowStateEx: AppWindowTokenEx init.. 
08-09 13:03:54.200   347   373 E GBMv2   : DFP En is all cleared set to be enabled
08-09 13:03:54.212  1555  1555 D QuickStatusbarLayout: Notification difference=198
08-09 13:03:54.212  1555  1555 D QuickStatusbarLayout: child = android.widget.LinearLayout{253c1ae5 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
08-09 13:03:54.217  1555  1555 D LgeAbsQuickCoverView: mCoverXPos: 0 ,mCoverYPos: 0
08-09 13:03:54.217  1555  1555 D LgeAbsQuickCoverView: mCoverWidth: 0 ,mCoverHeight: 0
08-09 13:03:54.248  1030  1721 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5999 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-09 13:03:54.255  5979  5979 D AndroidRuntime: Shutting down VM
08-09 13:03:54.298  1936  1952 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-09 13:03:54.298  1936  1952 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3e24866c co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
08-09 13:03:54.299  1936  1953 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-09 13:03:54.299  1936  1953 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3a0a5435 co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
08-09 13:03:54.352  5999  5999 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-09 13:03:54.452  5999  5999 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-09 13:03:54.462  5999  5999 I LibraryLoader: Loading: webviewchromium
,08-09 13:03:54.466  5999  5999 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 7527-7532)
08-09 13:03:54.466  5999  5999 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-09 13:03:54.487  5999  5999 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2ee46fdd}
,08-09 13:03:54.489  5999  5999 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-09 13:03:54.489  5999  5999 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-09 13:03:54.500  5999  5999 I BrowserStartupController: Initializing chromium process, renderers=0
08-09 13:03:54.501  5999  5999 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-09 13:03:54.507  5999  6018 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,08-09 13:03:54.513  5999  5999 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-09 13:03:54.513   332  2163 V AudioPolicyService: registerClient() client 0xb0410ac0, uid 10118
08-09 13:03:54.514  5999  5999 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-09 13:03:54.515  5999  5999 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-09 13:03:54.517  1030  1101 D BluetoothManagerService: Message: 20
08-09 13:03:54.518  1030  1101 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@63a8514:true
,08-09 13:03:54.520  5999  6022 D BluetoothAdapter: 860301138: getState() :  mService = null. Returning STATE_OFF
08-09 13:03:54.530  5999  5999 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-09 13:03:54.530  5999  5999 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-09 13:03:54.530  5999  5999 I Adreno-EGL: Build Date: 12/12/14 금
08-09 13:03:54.530  5999  5999 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-09 13:03:54.530  5999  5999 I Adreno-EGL: Remote Branch: 
08-09 13:03:54.530  5999  5999 I Adreno-EGL: Local Patches: 
08-09 13:03:54.530  5999  5999 I Adreno-EGL: Reconstruct Branch: 
,08-09 13:03:54.598  5999  6028 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-09 13:03:54.600  5999  5999 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-09 13:03:54.630  5999  5999 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-09 13:03:54.636  5999  5999 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-09 13:03:54.640  5999  5999 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-09 13:03:54.643  5999  5999 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-09 13:03:54.643  5999  5999 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-09 13:03:54.658  5999  5999 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-09 13:03:54.764  1030  1982 I art     : Explicit concurrent mark sweep GC freed 25572(1232KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.934ms total 93.253ms
,08-09 13:03:54.768  5999  5999 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-09 13:03:54.768  5999  5999 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-09 13:03:54.797  1030  1087 W ActivityManager: Activity pause timeout for ActivityRecord{12ead98b u0 com.test.thalitest/.MainActivity t2}
,08-09 13:03:54.822  5999  6046 D OpenGLRenderer: Render dirty regions requested: true
08-09 13:03:54.822  5999  6046 I OpenGLRenderer: Initialized EGL, version 1.4
,08-09 13:03:54.827  5999  6046 D OpenGLRenderer: Enabling debug mode 0
08-09 13:03:54.835  5999  5999 D Atlas   : Validating map...
,08-09 13:03:54.843  1030  2027 D SplitWindow: check instance of lgWin Window{39e6fdae u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-09 13:03:54.904  5999  6044 D LgDataFeature: LgDataFeature() Constructor: none
,08-09 13:03:54.905  5999  6044 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-09 13:03:54.936  1030  1102 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +638ms (total +735ms)
,08-09 13:03:54.937  1030  1102 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{12ead98b u0 com.test.thalitest/.MainActivity t2} time:178003
08-09 13:03:54.937  5999  5999 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3ab5fe49 time:178004
08-09 13:03:55.095  5999  5999 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-09 13:03:55.095  5999  5999 I chromium: 
,08-09 13:03:55.167  5999  5999 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-09 13:03:55.226  5999  6044 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-09 13:03:55.226  5999  6044 I chromium: 
,08-09 13:03:55.372  5999  6059 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435167232
,08-09 13:03:55.395  5999  6059 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-09 13:03:55.395  5999  6059 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-09 13:03:55.395  5999  6059 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-09 13:03:55.395  5999  6059 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-09 13:03:55.395  5999  6059 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-09 13:03:55.395  5999  6059 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36bb20bd added. We now have 1 listener(s)
08-09 13:03:55.399  1030  1954 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 13:03:55.401  5999  6059 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-09 13:03:55.403  5999  6059 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-09 13:03:55.404  5999  6059 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 13:03:55.405  5999  6059 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-09 13:03:55.413  5999  6059 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-09 13:03:55.413  5999  6059 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-09 13:03:55.413  5999  6059 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-09 13:03:55.413  5999  6059 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-09 13:03:55.413  5999  6059 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-09 13:03:55.413  5999  6059 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-09 13:03:55.413  5999  6059 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-09 13:03:55.413  5999  6059 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-09 13:03:55.413  5999  6059 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-09 13:03:55.413  5999  6059 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-09 13:03:55.413  5999  6059 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-09 13:03:55.413  5999  6059 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-09 13:03:55.413  5999  6059 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-09 13:03:55.413  5999  6059 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-09 13:03:55.413  5999  6059 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a61980 added. We now have 1 listener(s)
08-09 13:03:55.413  5999  6059 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 13:03:55.418  1030  1541 D WifiService: New client listening to asynchronous messages
08-09 13:03:55.423  5999  6059 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-09 13:03:55.423  5999  6059 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-09 13:03:55.426  5999  6059 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-09 13:03:55.426  5999  6059 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-09 13:03:55.427  5999  6059 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-09 13:03:55.429  5999  6059 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 13:03:55.430  1030  1881 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 13:03:55.430  5999  6059 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-09 13:03:55.436  5999  6059 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 13:03:55.437  5999  6059 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 13:03:55.437  5999  6059 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 13:03:55.437  5999  6059 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 13:03:55.437  5999  6059 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 13:03:55.437  5999  6059 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 13:03:55.437  5999  6059 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 13:03:55.437  5999  6059 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 13:03:55.437  5999  6059 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 13:03:55.438  5999  6059 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-09 13:03:55.438  5999  6059 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 13:03:55.439  5999  6059 I io.jxcore.node.LifeCycleMonitor: start: OK
08-09 13:03:55.475  5999  5999 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-09 13:03:55.864   347   375 E GBMv2   : DFP En is all cleared set to be enabled
08-09 13:03:55.864   347   375 E GBMv2   : Set value is all cleared set the max
08-09 13:03:55.864   347   375 I GBMv2   : DFP Enabled. Ignore VFP set
,08-09 13:03:56.318  5999  6062 W jxcore-log: Initializing JXcore engine
08-09 13:03:56.318  5999  6062 W jxcore-log: JXcore engine is ready
,08-09 13:03:56.353  6062  6062 W Thread-666: type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[10262]" dev="sockfs" ino=10262 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-09 13:03:56.353  6062  6062 W Thread-666: type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-09 13:03:56.353  6062  6062 W Thread-666: type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[8058]" dev="sockfs" ino=8058 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-09 13:03:56.353  6062  6062 W Thread-666: type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-09 13:03:56.353  6062  6062 W Thread-666: type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[25466]" dev="sockfs" ino=25466 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-09 13:03:56.377  5999  6062 W jxcore-log: Starting JXcore engine
,08-09 13:03:56.462  5999  6062 W jxcore-log: Platform android
08-09 13:03:56.462  5999  6062 W jxcore-log: 
,08-09 13:03:56.462  5999  6062 W jxcore-log: Process ARCH arm
08-09 13:03:56.462  5999  6062 W jxcore-log: 
,08-09 13:03:56.634  5999  6062 I jxcore-log: JXcore Cordova bridge is ready!
08-09 13:03:56.634  5999  6062 I jxcore-log: 
08-09 13:03:56.635  5999  6062 W jxcore-log: JXcore engine is started
,08-09 13:03:56.644  5999  6059 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-09 13:03:56.647  5999  5999 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-09 13:04:00.051  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-09 13:04:00.052  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
08-09 13:04:00.052  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-09 13:04:00.052  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
,08-09 13:04:00.055  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
08-09 13:04:00.055  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
08-09 13:04:00.056  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
08-09 13:04:00.056  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
,08-09 13:04:06.528  5999  6062 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-09 13:04:06.528  5999  6062 I jxcore-log: 
,08-09 13:04:06.530  5999  6062 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-09 13:04:06.530  5999  6062 I jxcore-log: 
08-09 13:04:06.531  5999  6062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 13:04:06.531  5999  6062 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 13:04:06.531  5999  6062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 13:04:06.531  5999  6062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 13:04:06.531  5999  6062 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 13:04:06.531  5999  6062 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 13:04:06.531  5999  6062 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 13:04:06.531  5999  6062 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 13:04:06.531  5999  6062 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 13:04:06.532  5999  6062 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 13:04:06.532  5999  6062 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 13:04:06.534  5999  6062 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-09 13:04:06.534  5999  6062 I jxcore-log: 
08-09 13:04:06.536  5999  6062 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-09 13:04:06.536  5999  6062 I jxcore-log: 
08-09 13:04:06.854  5999  6062 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-09 13:04:06.854  5999  6062 I jxcore-log: Failed to execute UT.
08-09 13:04:06.854  5999  6062 I jxcore-log: 
08-09 13:04:06.854  5999  6062 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-09 13:04:06.854  5999  6062 I jxcore-log: 
,08-09 13:04:06.862  5999  5999 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-09 13:04:06.864  5999  6062 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 13:04:06.864  5999  6062 I jxcore-log: 
08-09 13:04:07.197  6064  6064 D AndroidRuntime: 
08-09 13:04:07.197  6064  6064 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-09 13:04:07.202  6064  6064 D AndroidRuntime: CheckJNI is OFF
08-09 13:04:07.333  6064  6064 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-09 13:04:07.342  1030  1087 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-09 13:04:07.342  1030  1087 I ActivityManager: Killing 5999:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-09 13:04:07.404  1030  1374 I WindowState: WIN DEATH: Window{39e6fdae u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-09 13:04:07.405  1030  1541 D WifiService: Client connection lost with reason: 4
,08-09 13:04:07.412  1030  1374 D InputDispatcher: Window went away: Window{39e6fdae u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-09 13:04:07.557  1030  1087 I ActivityManager:   Force finishing activity ActivityRecord{12ead98b u0 com.test.thalitest/.MainActivity t2}
,08-09 13:04:07.586   347   373 E GBMv2   : DFP En is all cleared set to be enabled
08-09 13:04:07.588  1030  1752 W ActivityManager: Spurious death for ProcessRecord{1fa61d74 5999:com.test.thalitest/u0a118}, curProc for 5999: null
08-09 13:04:07.588  1030  1119 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-09 13:04:07.594  1030  1119 I ActivityManager:   Force finishing activity ActivityRecord{12ead98b u0 com.test.thalitest/.MainActivity t2 f}
,08-09 13:04:07.594  1030  1119 W ActivityManager: Duplicate finish request for ActivityRecord{12ead98b u0 com.test.thalitest/.MainActivity t2 f}
,08-09 13:04:07.626  2028  2028 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-09 13:04:07.628  2028  2028 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-09 13:04:07.632  1936  1953 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-09 13:04:07.632  1936  1953 D SplitWindowPolicy: topRunningActivity=ActivityInfo{320c30ca co.....Launcher}, taskId=1, activityType=1, bIsSplit=false
08-09 13:04:07.634  1936  2564 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-09 13:04:07.635  1936  2564 D SplitWindowPolicy: topRunningActivity=ActivityInfo{c4a823b co.....Launcher}, taskId=1, activityType=1, bIsSplit=false
08-09 13:04:07.636  2028  2028 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-09 13:04:07.636  2028  2068 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-09 13:04:07.643  1030  1087 D SplitWindowManager: removeStackAndNeedHomeResume ActivityStack{126c129d stackId=1, 0 tasks}
,08-09 13:04:07.646  2028  2028 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-09 13:04:07.647  1899  1899 D ActionManagerService: notifyUserLog: 1000003
08-09 13:04:07.647  2028  2028 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-09 13:04:07.648  2707  4101 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-09 13:04:07.649  2028  2028 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-09 13:04:07.650  1599  1599 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-09 13:04:07.655  1991  1991 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-09 13:04:07.661  2707  2707 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,08-09 13:04:07.663  1030  1423 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-09 13:04:07.671  2499  2676 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-09 13:04:07.673  2028  2028 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-09 13:04:07.675  5112  5112 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-09 13:04:07.682  4208  4208 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-09 13:04:07.682  4208  4208 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-09 13:04:07.682  4208  4208 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-09 13:04:07.682  4208  4208 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-09 13:04:07.682  4208  4208 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-09 13:04:07.682  4208  4208 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-09 13:04:07.682  4208  4208 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-09 13:04:07.683  4208  4208 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-09 13:04:07.683  4208  4208 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 13:04:07.683  4208  4208 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 13:04:07.683  4208  4208 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-09 13:04:07.683  4208  4208 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-09 13:04:07.707  2028  2028 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,08-09 13:04:07.714  1599  1599 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-09 13:04:07.716  1811  1811 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-09 13:04:07.718  2707  2764 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-09 13:04:07.722  4303  4303 I art     : Explicit concurrent mark sweep GC freed 421(29KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 654us total 120.789ms
,08-09 13:04:07.724  1899  1899 D ActionManagerService: notifyUserLog: 1000004
08-09 13:04:07.725  2707  4101 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-09 13:04:07.733  1030  1086 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-09 13:04:07.761  1030  1030 I art     : Explicit concurrent mark sweep GC freed 13435(1169KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 42MB/64MB, paused 2.640ms total 147.016ms
,08-09 13:04:07.762  1030  1119 I art     : WaitForGcToComplete blocked for 116.778ms for cause Explicit
,08-09 13:04:07.766  2110  2110 I ConfigService: onCreate
08-09 13:04:07.766  2110  2110 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-09 13:04:07.767  2028  2028 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-09 13:04:07.767  2028  2028 I GBoardWebViewUtils: , create_time: 1430832262123
08-09 13:04:07.767  2028  2028 I GBoardWebViewUtils: , expire_time: 0
08-09 13:04:07.767  2028  2028 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-09 13:04:07.767  2028  2028 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-09 13:04:07.767  2028  2028 I GBoardWebViewUtils: , display: false
08-09 13:04:07.767  2028  2028 I GBoardWebViewUtils: , animation: false }
08-09 13:04:07.767  2028  2028 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-09 13:04:07.767  2028  2028 I GBoardWebViewUtils: , create_time: 1430832262287
08-09 13:04:07.767  2028  2028 I GBoardWebViewUtils: , expire_time: 0
08-09 13:04:07.767  2028  2028 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-09 13:04:07.767  2028  2028 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-09 13:04:07.767  2028  2028 I GBoardWebViewUtils: , display: false
08-09 13:04:07.767  2028  2028 I GBoardWebViewUtils: , animation: false }
08-09 13:04:07.767  2028  2028 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1470393742816
08-09 13:04:07.767  2028  2028 I GBoardWebViewUtils: , create_time: 1470393743569
08-09 13:04:07.767  2028  2028 I GBoardWebViewUtils: , expire_time: 0
08-09 13:04:07.767  2028  2028 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-09 13:04:07.767  2028  2028 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-09 13:04:07.767  2028  2028 I GBoardWebViewUtils: , display: false
08-09 13:04:07.767  2028  2028 I GBoardWebViewUtils: , animation: false }
08-09 13:04:07.768  1030  1948 V SIM_STK : Menu title from STK is T-Mobile
08-09 13:04:07.769  1811  1811 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-09 13:04:07.777  1599  1599 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-09 13:04:07.777  1599  1599 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-09 13:04:07.778   328  6100 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-09 13:04:07.778  1030  1099 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-09 13:04:07.781  1599  1660 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-09 13:04:07.781  1599  1660 D KeyguardModel: createShortcutInfo...
08-09 13:04:07.782  2028  6101 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-09 13:04:07.785  2110  2110 I ConfigService: onBind returning update interface
08-09 13:04:07.786  2110  2110 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-09 13:04:07.786  2110  2110 I ConfigService: onBind returning config service
08-09 13:04:07.789  1863  1863 D SplitUIManager: split_name #11 / not available #0
,08-09 13:04:07.790  1863  1863 D SplitUIService: removed split : 
08-09 13:04:07.790  2110  2110 I ConfigService: onDestroy
08-09 13:04:07.793  1599  1660 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-09 13:04:07.793  1599  1660 D KeyguardModel: createShortcutInfo...
08-09 13:04:07.794  1599  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-09 13:04:07.794  1599  1660 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-09 13:04:07.796  1599  1660 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-09 13:04:07.796  1599  1660 D KeyguardModel: createShortcutInfo...
08-09 13:04:07.797  1811  6103 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-09 13:04:07.801  2028  2028 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,08-09 13:04:07.808  1599  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-09 13:04:07.808  1599  1660 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-09 13:04:07.812  1599  1660 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-09 13:04:07.812  1599  1660 D KeyguardModel: createShortcutInfo...
08-09 13:04:07.815  1599  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-09 13:04:07.815  1599  1660 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-09 13:04:07.819  1599  1660 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-09 13:04:07.819  1599  1660 D KeyguardModel: createShortcutInfo...
08-09 13:04:07.820  1863  1863 D SplitUIManager: split_name #11 / not available #0
08-09 13:04:07.820  1863  1863 I SplitUIService: split app #11
08-09 13:04:07.823  5657  5657 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-09 13:04:07.825  5454  6107 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-09 13:04:07.828  1599  1599 D KeyguardModel: handleShortcutListChanged...
08-09 13:04:07.828  1599  1599 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-09 13:04:07.833  1599  1660 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-09 13:04:07.833  1599  1660 D KeyguardModel: createShortcutInfo...
,08-09 13:04:07.845  1811  6111 I PeopleContactsSync: CP2 sync disabled
08-09 13:04:07.846  1599  1660 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-09 13:04:07.846  1599  1660 D KeyguardModel: createShortcutInfo...
08-09 13:04:07.847  1599  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-09 13:04:07.847  1599  1660 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-09 13:04:07.848  1599  1660 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-09 13:04:07.848  1599  1660 D KeyguardModel: createShortcutInfo...
08-09 13:04:07.850  1599  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-09 13:04:07.850  1599  1660 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-09 13:04:07.851  1599  1660 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-09 13:04:07.851  1599  1660 D KeyguardModel: createShortcutInfo...
,08-09 13:04:07.854  1599  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-09 13:04:07.854  1599  1660 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-09 13:04:07.856  1599  1660 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-09 13:04:07.856  1599  1660 D KeyguardModel: createShortcutInfo...
08-09 13:04:07.865  1811  4498 I Icing   : doRemovePackageData com.test.thalitest
,08-09 13:04:07.866  2028  2028 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-09 13:04:07.870  2028  2028 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-09 13:04:07.881  1030  1046 V SIM_STK : Menu title from STK is T-Mobile
,08-09 13:04:07.899  5701  5701 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-09 13:04:07.909  2340  6112 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-09 13:04:07.925  1599  1599 D KeyguardModel: handleShortcutListChanged...
08-09 13:04:07.925  1599  1599 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-09 13:04:07.930  1811  6110 W GmsApplication: Using Auth Proxy for data requests.
08-09 13:04:07.931  2028  2028 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-09 13:04:07.932  1030  1030 D administrator: Handling package changes for user 0
08-09 13:04:07.936  2028  2028 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-09 13:04:07.938  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,08-09 13:04:07.939  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-09 13:04:07.940  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-09 13:04:07.941  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-09 13:04:07.950  1811  6110 W GmsApplication: Using Auth Proxy for data requests.
,08-09 13:04:07.955  1030  1102 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{27bbc4e9 u0 com.lge.launcher2/.Launcher t1} time:191021
08-09 13:04:07.959  2028  2028 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-09 13:04:07.960  2028  2028 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-09 13:04:07.961  2028  2819 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-09 13:04:07.961  2028  2819 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-09 13:04:07.970   341   423 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-09 13:04:07.970  3214  6117 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-09 13:04:07.978  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-09 13:04:07.979  2028  2028 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-09 13:04:07.979  2028  2028 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-09 13:04:07.979  1991  1991 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-09 13:04:07.979  1991  1991 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-09 13:04:07.981  1991  1991 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
,08-09 13:04:07.987  2028  2028 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-09 13:04:07.989  2573  2573 D [Concierge]Service: onStartCommand(). Type : 8
08-09 13:04:07.989  2573  2573 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-09 13:04:07.990  2573  2573 D [Concierge]Service: Update widget ID : 11
08-09 13:04:07.991  2028  2028 D [Concierge]WidgetView: change position of spinner
08-09 13:04:07.991  5112  5112 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-09 13:04:07.992  2028  2028 I [Concierge]WidgetView: initWebView(). Time : 1470740647992
08-09 13:04:07.992  2573  2573 D [Concierge]Service: onStartCommand(). Type : 0
,08-09 13:04:08.021  1030  1374 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6121 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-09 13:04:08.033  1030  1030 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-09 13:04:08.033  1030  1030 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-09 13:04:08.034  1030  1030 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-09 13:04:08.035  2028  2028 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 887141896
08-09 13:04:08.035  2028  2028 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-09 13:04:08.035  1030  1574 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
08-09 13:04:08.035  2028  2028 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-09 13:04:08.038  2028  2028 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@917f617
08-09 13:04:08.038  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-09 13:04:08.039  2028  2028 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-09 13:04:08.039  2028  2028 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-09 13:04:08.044  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-09 13:04:08.045  2028  2028 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-09 13:04:08.045  2028  2028 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470740484789, New one : 1470740647992
08-09 13:04:08.045  2028  2028 D [Concierge]WidgetView: Unregister all receivers
08-09 13:04:08.045  2028  2028 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-09 13:04:08.046  2028  2028 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-09 13:04:08.046  2028  2028 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-09 13:04:08.047  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,08-09 13:04:08.048  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-09 13:04:08.049  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-09 13:04:08.050  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-09 13:04:08.052  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-09 13:04:08.057  2028  2028 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-09 13:04:08.057  2028  2028 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-09 13:04:08.091  1030  1119 I art     : Explicit concurrent mark sweep GC freed 8947(476KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 3.813ms total 327.150ms
,08-09 13:04:08.093  2028  2028 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-09 13:04:08.101  2028  2028 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-09 13:04:08.101  1811  6138 I art     : Explicit concurrent mark sweep GC freed 19070(1276KB) AllocSpace objects, 15(240KB) LOS objects, 51% free, 29MB/61MB, paused 1.031ms total 38.456ms
08-09 13:04:08.101  2028  2028 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-09 13:04:08.102  1811  1822 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,08-09 13:04:08.103  2028  2028 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-09 13:04:08.104  1811  1822 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-09 13:04:08.104  1811  1822 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-09 13:04:08.125  2028  2028 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@12754c0d time:191191
,08-09 13:04:08.158  6121  6121 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-09 13:04:08.158  6121  6121 W LG Account v2.2: No ProfileInfo entries
,08-09 13:04:08.158  6121  6121 I LG Account v2.2: isEnabled: false
08-09 13:04:08.159  6121  6121 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-09 13:04:08.159  6121  6121 I Feature : [Lifetracker]Country: EU
08-09 13:04:08.159  6121  6121 I Feature : [Lifetracker]Operator: OPEN
08-09 13:04:08.159  6121  6121 I Feature : [Lifetracker]Ranking support: false
08-09 13:04:08.159  6121  6121 I Feature : [Lifetracker]Comfort support: false
08-09 13:04:08.159  6121  6121 I Feature : [Lifetracker]Accessory: true
08-09 13:04:08.159  6121  6121 I Feature : [Lifetracker]Health device: true
08-09 13:04:08.159  6121  6121 I Feature : [Lifetracker]Extra Pedometer: false
08-09 13:04:08.159  6121  6121 I Feature : [Lifetracker]Blood glucose device: false
08-09 13:04:08.159  6121  6121 I Feature : [Lifetracker]Device Number: 3
08-09 13:04:08.159  6121  6121 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-09 13:04:08.168  6064  6064 D AndroidRuntime: Shutting down VM
,08-09 13:04:08.177  1030  1046 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6141 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-09 13:04:08.178  1030  1046 I ActivityManager: Killing 4627:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-09 13:04:08.211  1030  1086 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-09 13:04:08.215  1030  1086 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-09 13:04:08.240  2028  2028 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-09 13:04:08.274  2028  2854 I GBoardtInterface: onReloaded()
,08-09 13:04:08.276  2028  2028 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-09 13:04:08.285  1030  1919 W libprocessgroup: failed to open /acct/uid_10014/pid_4627/cgroup.procs: No such file or directory
,08-09 13:04:08.291  2707  2764 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-09 13:04:08.294  2707  2762 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-09 13:04:08.299  1899  1899 D ActionManagerService: notifyUserLog: 1000001
,08-09 13:04:08.300  2707  4101 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-09 13:04:08.300  2707  4101 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-09 13:04:08.302  6141  6141 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-09 13:04:08.302  1899  1899 D ActionManagerService: notifyUserLog: 1000001
08-09 13:04:08.302  6141  6141 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-09 13:04:08.303  2707  4101 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-09 13:04:08.303  2707  4101 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-09 13:04:08.303  2707  4101 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-09 13:04:08.303  2707  4101 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-09 13:04:08.303  6141  6141 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-09 13:04:08.304  6141  6141 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-09 13:04:08.304  2707  2762 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-09 13:04:08.305  6141  6141 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-09 13:04:08.305  6141  6141 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-09 13:04:08.306  2028  2028 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-09 13:04:08.306  2028  2028 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-09 13:04:08.308  2028  2028 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-09 13:04:08.308  2028  2028 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-09 13:04:08.309  2028  2028 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-09 13:04:08.309  2028  2028 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-09 13:04:08.314  2028  2028 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-09 13:04:08.377  6141  6141 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-09 13:04:08.423  6141  6141 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
,08-09 13:04:08.423  6141  6141 D HideNavigationAppsReceiver: replacing : false
08-09 13:04:08.425  6141  6141 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-09 13:04:08.427  6141  6141 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-09 13:04:08.427  6141  6141 D ButtonCombinationReceiver: replacing : false
08-09 13:04:08.432  1030  2012 I ActivityManager: Killing 2164:com.lge.music/u0a34 (adj 15): empty #17
08-09 13:04:08.441   332   332 V AudioFlinger: 2164 died, releasing its sessions
08-09 13:04:08.441   332   332 V AudioFlinger:  pid 1846 @ 0
08-09 13:04:08.441   332   332 V AudioFlinger:  pid 3128 @ 1
08-09 13:04:08.441   332   332 V AudioFlinger:  pid 3128 @ 2
,08-09 13:04:08.495  1030  1374 W libprocessgroup: failed to open /acct/uid_10034/pid_2164/cgroup.procs: No such file or directory
,08-09 13:04:08.506  4303  6164 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-09 13:04:08.543  1030  1046 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6166 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-09 13:04:08.547  1030  1919 V SIM_STK : Menu title from STK is T-Mobile
08-09 13:04:08.554   360   360 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 195us total 18.930ms
08-09 13:04:08.564   360   360 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 188us total 9.290ms
,08-09 13:04:08.571  4303  6164 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
--------- beginning of crash
08-09 13:04:08.575  4303  6164 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-09 13:04:08.575  4303  6164 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 4303
08-09 13:04:08.575  4303  6164 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-09 13:04:08.575  4303  6164 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-09 13:04:08.575  4303  6164 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-09 13:04:08.575  4303  6164 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-09 13:04:08.575  4303  6164 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-09 13:04:08.575  4303  6164 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-09 13:04:08.575  4303  6164 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-09 13:04:08.575  4303  6164 E AndroidRuntime: 	at csx.d(PG:186)
08-09 13:04:08.575  4303  6164 E AndroidRuntime: 	at cun.g(PG:594)
08-09 13:04:08.575  4303  6164 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
08-09 13:04:08.575  4303  6164 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
08-09 13:04:08.575  4303  6164 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1349)
08-09 13:04:08.575  4303  6164 E AndroidRuntime: 	at cuw.Tg(PG:368)
08-09 13:04:08.575  4303  6164 E AndroidRuntime: 	at cuy.ub(PG:301)
08-09 13:04:08.575  4303  6164 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
08-09 13:04:08.575  4303  6164 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
08-09 13:04:08.575  4303  6164 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-09 13:04:08.575  4303  6164 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 13:04:08.575  4303  6164 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-09 13:04:08.575  4303  6164 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 13:04:08.575   360   360 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 182us total 9.747ms
,08-09 13:04:08.579  4303  6164 I Process : Sending signal. PID: 4303 SIG: 9
08-09 13:04:08.582  1030  6175 E DropBoxManagerService: Can't write: system_app_crash
08-09 13:04:08.582  1030  6175 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop103.tmp: open failed: EROFS (Read-only file system)
08-09 13:04:08.582  1030  6175 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 13:04:08.582  1030  6175 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 13:04:08.582  1030  6175 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 13:04:08.582  1030  6175 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-09 13:04:08.582  1030  6175 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-09 13:04:08.582  1030  6175 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-09 13:04:08.582  1030  6175 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 13:04:08.582  1030  6175 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-09 13:04:08.582  1030  6175 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 13:04:08.582  1030  6175 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 13:04:08.582  1030  6175 E DropBoxManagerService: 	... 5 more
08-09 13:04:08.593  1030  1541 D WifiService: Client connection lost with reason: 4
,08-09 13:04:08.597  4208  4247 E SQLiteDatabase: Error inserting f004=13 f005=6166 f002=1470740648565 f003=com.android.keychain f006=1000
08-09 13:04:08.597  4208  4247 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
08-09 13:04:08.597  4208  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-09 13:04:08.597  4208  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
08-09 13:04:08.597  4208  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
08-09 13:04:08.597  4208  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-09 13:04:08.597  4208  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
08-09 13:04:08.597  4208  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
08-09 13:04:08.597  4208  4247 E SQLiteDatabase: 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
08-09 13:04:08.597  4208  4247 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
08-09 13:04:08.597  4208  4247 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
08-09 13:04:08.597  4208  4247 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2584)
08-09 13:04:08.597  4208  4247 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.access$2700(MltMonitorService.java:38)
08-09 13:04:08.597  4208  4247 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3409)
08-09 13:04:08.597  4208  4247 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 13:04:08.597  4208  4247 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-09 13:04:08.597  4208  4247 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3518)
08-09 13:04:08.597  2028  2854 I GBoardtInterface: exportHTML()
08-09 13:04:08.624  2028  2854 I GBoardtInterface: exportHTML()
,08-09 13:04:08.633  1030  1954 I ActivityManager: Process com.google.android.googlequicksearchbox:search (pid 4303) has died
08-09 13:04:08.634  1030  1954 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 1000ms
08-09 13:04:08.634  1030  1954 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms

```
