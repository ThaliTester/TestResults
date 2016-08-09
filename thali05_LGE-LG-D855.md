#### Test 80598852be6cebf_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
08-09 14:33:23.518  6603  6637 D serial_port: close(fd = 24)
,08-09 14:33:23.529  6603  6637 I UEI.SmartControl: Serial port is closed.
08-09 14:33:23.539  6603  6640 D UEI.SmartControl: Internal timer expired: 3
08-09 14:33:23.540  6603  6640 D UEI.SmartControl: unbind internal service
08-09 14:33:23.546  6603  6603 D UEI.SmartControl: Service.onUnbind: IControl
08-09 14:33:23.547  6603  6603 D UEI.SmartControl: Service.onDestroy
08-09 14:33:23.547  6603  6603 D UEI.SmartControl: Lock is in USE false
08-09 14:33:23.547  6603  6603 D UEI.SmartControl: unbind internal service
08-09 14:33:23.547  6603  6603 I UEI.SmartControl: Serial port is closed.
08-09 14:33:23.547  6603  6603 I UEI.SmartControl: Serial port is closed.
08-09 14:33:23.547  6603  6603 D UEI.SmartControl: Blaster closed
08-09 14:33:23.547  6603  6603 D UEI.SmartControl: Shut down QS...
08-09 14:33:23.547  6603  6603 D UEI.SmartControl: Stopping QS lib
08-09 14:33:23.547  6603  6603 D UEI.SmartControl: QS lib stop result = true
08-09 14:33:23.547  6603  6603 D UEI.SmartControl: Stopped QS lib
08-09 14:33:23.547  6603  6603 D UEI.SmartControl: QS shutdown complete
08-09 14:33:23.823  6649  6649 D AndroidRuntime: 
08-09 14:33:23.823  6649  6649 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-09 14:33:23.827  6649  6649 D AndroidRuntime: CheckJNI is OFF
08-09 14:33:23.952  6649  6649 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-09 14:33:23.957  1036  1051 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-09 14:33:23.966  1926  2923 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-09 14:33:23.969  1036  1051 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-09 14:33:23.970  1036  1051 V ActivityStackEx: create ActivityStackEx
08-09 14:33:23.984  1036  1051 D ActivityManager: setTaskToReturnTo : TaskRecord{2d14b524 #2 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-09 14:33:23.984  1036  1051 D ActivityManager: setTaskToReturnTo : TaskRecord{2d14b524 #2 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-09 14:33:23.986  1036  1051 D WindowStateEx: AppWindowTokenEx init.. 
08-09 14:33:23.987   339   356 E GBMv2   : DFP En is all cleared set to be enabled
08-09 14:33:24.005  1544  1544 D QuickStatusbarLayout: Notification difference=198
08-09 14:33:24.005  1544  1544 D QuickStatusbarLayout: child = android.widget.LinearLayout{1a899d07 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
08-09 14:33:24.008  1544  1544 D LgeAbsQuickCoverView: mCoverXPos: 0 ,mCoverYPos: 0
08-09 14:33:24.008  1544  1544 D LgeAbsQuickCoverView: mCoverWidth: 0 ,mCoverHeight: 0
08-09 14:33:24.034  1036  1051 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6669 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-09 14:33:24.038  6649  6649 D AndroidRuntime: Shutting down VM
08-09 14:33:24.079  1926  2923 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-09 14:33:24.079  1926  2923 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3ba5c1a9 co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
08-09 14:33:24.081  1926  1942 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-09 14:33:24.082  1926  1942 D SplitWindowPolicy: topRunningActivity=ActivityInfo{184b232e co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
08-09 14:33:24.115  6669  6669 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-09 14:33:24.177  6669  6669 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-09 14:33:24.183  6669  6669 I LibraryLoader: Loading: webviewchromium
08-09 14:33:24.185  6669  6669 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2402-2404)
08-09 14:33:24.185  6669  6669 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-09 14:33:24.210  6669  6669 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {35eda23f}
08-09 14:33:24.211  6669  6669 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-09 14:33:24.211  6669  6669 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-09 14:33:24.220  6669  6669 I BrowserStartupController: Initializing chromium process, renderers=0
08-09 14:33:24.221  6669  6669 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-09 14:33:24.231  6669  6669 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-09 14:33:24.231  6669  6669 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-09 14:33:24.231  6669  6669 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-09 14:33:24.236   315   315 V AudioPolicyService: registerClient() client 0xb558ab60, uid 10118
08-09 14:33:24.254  1036  1118 D BluetoothManagerService: Message: 20
08-09 14:33:24.254  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3bc2888e:true
08-09 14:33:24.257  6669  6669 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-09 14:33:24.257  6669  6669 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-09 14:33:24.257  6669  6669 I Adreno-EGL: Build Date: 12/12/14 금
08-09 14:33:24.257  6669  6669 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-09 14:33:24.257  6669  6669 I Adreno-EGL: Remote Branch: 
08-09 14:33:24.257  6669  6669 I Adreno-EGL: Local Patches: 
08-09 14:33:24.257  6669  6669 I Adreno-EGL: Reconstruct Branch: 
,08-09 14:33:24.337  6669  6699 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-09 14:33:24.344  6669  6669 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-09 14:33:24.362  6669  6669 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-09 14:33:24.367  6669  6669 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-09 14:33:24.371  6669  6669 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
,08-09 14:33:24.375  6669  6669 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
,08-09 14:33:24.375  6669  6669 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-09 14:33:24.391  6669  6669 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-09 14:33:24.398  6669  6669 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-09 14:33:24.399  6669  6669 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-09 14:33:24.431  6669  6711 D OpenGLRenderer: Render dirty regions requested: true
08-09 14:33:24.431  6669  6711 I OpenGLRenderer: Initialized EGL, version 1.4
08-09 14:33:24.441  6669  6711 D OpenGLRenderer: Enabling debug mode 0
,08-09 14:33:24.448  6669  6669 D Atlas   : Validating map...
08-09 14:33:24.451  1036  1051 D SplitWindow: check instance of lgWin Window{23b13d8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-09 14:33:24.505  6669  6709 D LgDataFeature: LgDataFeature() Constructor: none
08-09 14:33:24.505  6669  6709 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-09 14:33:24.554  1036  1119 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +476ms (total +567ms)
08-09 14:33:24.554  6669  6669 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@6cefa1a time:112773
08-09 14:33:24.554  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3eda488d u0 com.test.thalitest/.MainActivity t2} time:112773
,08-09 14:33:24.676  6669  6669 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-09 14:33:24.676  6669  6669 I chromium: 
,08-09 14:33:24.721  6669  6669 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-09 14:33:24.888  6669  6722 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435056640
,08-09 14:33:24.904  6669  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-09 14:33:24.904  6669  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-09 14:33:24.904  6669  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-09 14:33:24.904  6669  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-09 14:33:24.904  6669  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-09 14:33:24.904  6669  6722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@295d83be added. We now have 1 listener(s)
,08-09 14:33:24.911  1036  1871 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 14:33:24.918  6669  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-09 14:33:24.922  6669  6722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-09 14:33:24.923  6669  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-09 14:33:24.923  6669  6722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 14:33:24.932  6669  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-09 14:33:24.932  6669  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-09 14:33:24.932  6669  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-09 14:33:24.932  6669  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-09 14:33:24.932  6669  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-09 14:33:24.932  6669  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-09 14:33:24.932  6669  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-09 14:33:24.932  6669  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-09 14:33:24.932  6669  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-09 14:33:24.932  6669  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-09 14:33:24.932  6669  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-09 14:33:24.932  6669  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-09 14:33:24.932  6669  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-09 14:33:24.932  6669  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-09 14:33:24.932  6669  6722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26a7d535 added. We now have 1 listener(s)
08-09 14:33:24.932  6669  6722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 14:33:24.937  1036  1529 D WifiService: New client listening to asynchronous messages
,08-09 14:33:24.942  6669  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-09 14:33:24.943  6669  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-09 14:33:24.943  6669  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-09 14:33:24.943  6669  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-09 14:33:24.943  6669  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-09 14:33:24.947  6669  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 14:33:24.948  1036  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-09 14:33:24.950  6669  6722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-09 14:33:24.959  6669  6722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-09 14:33:24.960  6669  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 14:33:24.960  6669  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:24.960  6669  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:24.960  6669  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 14:33:24.960  6669  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 14:33:24.960  6669  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 14:33:24.960  6669  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 14:33:24.960  6669  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-09 14:33:24.960  6669  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-09 14:33:24.960  6669  6722 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 14:33:24.964  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:24.966  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:24.967  6669  6722 I io.jxcore.node.LifeCycleMonitor: start: OK
08-09 14:33:25.005  6669  6709 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-09 14:33:25.005  6669  6709 I chromium: 
,08-09 14:33:25.064  6669  6669 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-09 14:33:25.559   339   358 E GBMv2   : DFP En is all cleared set to be enabled
08-09 14:33:25.559   339   358 E GBMv2   : Set value is all cleared set the max
08-09 14:33:25.559   339   358 I GBMv2   : DFP Enabled. Ignore VFP set
,08-09 14:33:25.717  6669  6725 W jxcore-log: Initializing JXcore engine
,08-09 14:33:25.717  6669  6725 W jxcore-log: JXcore engine is ready
,08-09 14:33:25.785  6725  6725 W Thread-767: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[10323]" dev="sockfs" ino=10323 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-09 14:33:25.795  6725  6725 W Thread-767: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-09 14:33:25.795  6725  6725 W Thread-767: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7604]" dev="sockfs" ino=7604 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-09 14:33:25.795  6725  6725 W Thread-767: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-09 14:33:25.795  6725  6725 W Thread-767: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[31511]" dev="sockfs" ino=31511 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-09 14:33:25.820  6669  6725 W jxcore-log: Starting JXcore engine
,08-09 14:33:25.923  6669  6725 W jxcore-log: Platform android
08-09 14:33:25.923  6669  6725 W jxcore-log: 
08-09 14:33:25.924  6669  6725 W jxcore-log: Process ARCH arm
08-09 14:33:25.924  6669  6725 W jxcore-log: 
,08-09 14:33:26.206  6669  6725 I jxcore-log: JXcore Cordova bridge is ready!
08-09 14:33:26.206  6669  6725 I jxcore-log: 
08-09 14:33:26.207  6669  6725 W jxcore-log: JXcore engine is started
,08-09 14:33:26.214  6669  6722 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-09 14:33:26.218  6669  6669 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-09 14:33:26.229  1036  1099 I ActivityManager: Waited long enough for: ServiceRecord{321d02d0 u0 com.google.android.gms/.wearable.service.WearableService}
,08-09 14:33:27.212  2160  2160 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19981
,08-09 14:33:28.859  1036  1362 V AlarmManager: RTC_WAKEUP set : Alarm{259b1a8f type 0 when 1470746006825 com.android.vending} when 1470746006825
,08-09 14:33:28.910  1036  1890 V SIM_STK : Menu title from STK is T-Mobile
,08-09 14:33:28.923  4483  6726 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-09 14:33:29.215  6044  6044 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-09 14:33:36.182  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-09 14:33:36.182  6669  6725 I jxcore-log: 
,08-09 14:33:36.184  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-09 14:33:36.184  6669  6725 I jxcore-log: 
08-09 14:33:36.190  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 14:33:36.190  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:36.190  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:36.190  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 14:33:36.190  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 14:33:36.190  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 14:33:36.190  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 14:33:36.190  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 14:33:36.192  6669  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 14:33:36.194  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-09 14:33:36.194  6669  6725 I jxcore-log: 
,08-09 14:33:36.196  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-09 14:33:36.196  6669  6725 I jxcore-log: 
08-09 14:33:36.519  6669  6725 D ExecuteNativeTests: Running unit tests
,08-09 14:33:36.601  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 14:33:36.601  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@317226a4 added. We now have 2 listener(s)
,08-09 14:33:36.605  1036  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 14:33:36.606  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-09 14:33:36.606  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 14:33:36.606  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 14:33:36.606  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 14:33:36.606  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d added. We now have 2 listener(s)
08-09 14:33:36.606  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 14:33:36.607  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-09 14:33:36.609  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 14:33:36.612  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 14:33:36.612  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:36.612  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:36.612  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 14:33:36.612  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 14:33:36.612  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 14:33:36.612  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 14:33:36.612  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 14:33:36.613  6669  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 14:33:36.613  6669  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 14:33:36.615  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:36.616  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 14:33:36.619  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-09 14:33:36.621  6669  6725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-09 14:33:36.621  6669  6725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-09 14:33:36.623  6669  6725 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-09 14:33:36.623  6669  6725 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-09 14:33:36.623  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-09 14:33:36.623  6669  6725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-09 14:33:36.624  6669  6725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-09 14:33:36.624  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:36.625  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:36.625  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:36.625  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:36.625  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.626  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 14:33:36.626  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-09 14:33:36.626  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@317226a4 removed from the list
08-09 14:33:36.626  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.626  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d removed from the list
08-09 14:33:36.626  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:36.626  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.627  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.627  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.628  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:36.628  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:36.628  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.628  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.629  6669  6725 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-09 14:33:36.630  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:36.630  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:36.630  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:36.630  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:36.630  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.630  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.630  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@317226a4 not in the list
08-09 14:33:36.630  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.630  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.630  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:36.630  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.630  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.630  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.630  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.631  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:36.631  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:36.631  6669  672,5 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.631  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-09 14:33:36.635  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-09 14:33:36.635  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:36.635  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:36.635  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:36.635  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:36.636  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.636  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.636  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@317226a4 not in the list
08-09 14:33:36.636  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.636  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.636  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:36.636  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.636  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.636  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 14:33:36.636  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.636  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:36.636  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:36.636  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.636  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
,08-09 14:33:36.637  6669  6725 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-09 14:33:36.638  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 14:33:36.642  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 14:33:36.642  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:36.642  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:36.642  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 14:33:36.642  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 14:33:36.642  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 14:33:36.642  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,08-09 14:33:36.642  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 14:33:36.643  6669  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-09 14:33:36.643  6669  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 14:33:36.644  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:36.645  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:36.645  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-09 14:33:36.645  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-09 14:33:36.645  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-09 14:33:36.645  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 14:33:36.645  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
08-09 14:33:36.648  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-09 14:33:36.648  1036  1561 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 14:33:36.652  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-09 14:33:36.655  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-09 14:33:36.657  6669  6725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-09 14:33:36.658  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-09 14:33:36.658  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 14:33:36.659  6669  6725 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-09 14:33:36.659  6669  6725 I io.jxcore.node.ConnectionHelper: start: OK
08-09 14:33:36.661  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:36.661  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:36.661  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:36.661  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:36.661  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.661  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 14:33:36.662  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@317226a4 not in the list
08-09 14:33:36.662  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.662  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.662  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:36.662  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.662  6669  6725 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-09 14:33:36.663  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 14:33:36.665  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 14:33:36.665  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:36.665  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:36.665  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 14:33:36.665  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 14:33:36.665  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 14:33:36.665  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 14:33:36.665  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-09 14:33:36.666  6669  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 14:33:36.666  6669  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 14:33:36.667  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:36.667  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-09 14:33:36.667  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-09 14:33:36.668  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-09 14:33:36.668  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 14:33:36.668  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-09 14:33:36.668  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:36.671  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-09 14:33:36.671  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 14:33:36.672  6669  6725 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-09 14:33:36.672  6669  6725 I io.jxcore.node.ConnectionHelper: start: OK
08-09 14:33:36.673  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:36.673  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:36.673  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:36.673  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:36.673  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.673  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 14:33:36.673  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@317226a4 not in the list
08-09 14:33:36.673  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.674  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.674  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:36.674  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.674  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.674  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.674  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:36.674  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:36.675  6669  6725 D BluetoothLeScann,er: could not find callback wrapper
08-09 14:33:36.675  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 14:33:36.675  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.675  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.676  6669  6725 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-09 14:33:36.677  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 14:33:36.679  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 14:33:36.679  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:36.679  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:36.679  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 14:33:36.679  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 14:33:36.679  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 14:33:36.679  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 14:33:36.679  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 14:33:36.680  6669  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 14:33:36.680  6669  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 14:33:36.680  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-09 14:33:36.680  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-09 14:33:36.680  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-09 14:33:36.680  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 14:33:36.680  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-09 14:33:36.685  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:36.687  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 14:33:36.751  1036  1921 I art     : Explicit concurrent mark sweep GC freed 18300(946KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.462ms total 69.667ms
08-09 14:33:36.753  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-09 14:33:36.753  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 14:33:36.754  6669  6725 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-09 14:33:36.754  6669  6725 I io.jxcore.node.ConnectionHelper: start: OK
08-09 14:33:36.754  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:36.754  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:36.754  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:36.755  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:36.755  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:36.755  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:36.755  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:36.755  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.755  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 14:33:36.755  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@317226a4 not in the list
08-09 14:33:36.755  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.755  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.755  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:36.755  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.756  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.756  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.756  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:36.756  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:36.756  6669  6725 D BluetoothLeScanner: could not find callback wrapper
08-09 14:33:36.756  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 14:33:36.756  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.756  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.757  6669  6725 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-09 14:33:36.757  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:36.757  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:36.757  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, s,kipping...
08-09 14:33:36.758  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:36.758  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.758  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.758  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@317226a4 not in the list
08-09 14:33:36.758  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.758  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.758  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:36.758  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.758  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.758  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.758  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.761  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:36.761  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:36.761  6669  6725 D BluetoothLeScanner: could not find callback wrapper
08-09 14:33:36.761  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 14:33:36.761  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.761  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.762  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-09 14:33:36.762  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:36.762  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:36.762  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:36.762  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:36.762  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.762  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.762  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@317226a4 not in the list
08-09 14:33:36.762  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.763  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.763  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:36.763  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.763  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.763  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.763  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.764  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:36.764  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:36.764  6669  6725 D BluetoothLeScanner: could not find callback wrapper
08-09 14:33:36.764  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 14:33:36.764  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.764  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.765  6669  6725 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-09 14:33:36.765  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:36.765  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:36.765  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:36.765  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:36.765  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.766  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.766  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@317226a4 not in the list
08-09 14:33:36.766  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.766  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.766  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:36.766  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.766  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.766  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.766  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.771  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:36.771  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:36.772  6669  6725 D BluetoothLeScanner: could not find callback wrapper
08-09 14:33:36.772  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 14:33:36.773  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.773  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.773  6669  6725 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-09 14:33:36.773  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:36.773  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:36.773  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:36.780  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:36.780  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.780  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.781  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@317226a4 not in the list
08-09 14:33:36.781  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.781  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.781  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:36.781  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.781  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.781  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.781  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.781  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:36.781  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:36.782  6669  6725 D BluetoothLeScanner: could not find callback wrapper
08-09 14:33:36.782  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 14:33:36.782  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.782  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.782  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-09 14:33:36.782  6669  6725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-09 14:33:36.782  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-09 14:33:36.782  6669  6725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-09 14:33:36.783  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-09 14:33:36.783  6669  6725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-09 14:33:36.783  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:36.783  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:36.783  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:36.783  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:36.783  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.783  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.783  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@317226a4 not in the list
08-09 14:33:36.783  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.783  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.783  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:36.783  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.783  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.783  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.783  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.785  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:36.785  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:36.785  6669  6725 D BluetoothLeScanner: could not find callback wrapper
08-09 14:33:36.785  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 14:33:36.785  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.785  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.785  6669  6725 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-09 14:33:36.786  6669  6725 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-09 14:33:36.786  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-09 14:33:36.787  6669  6725 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-09 14:33:36.787  6669  6725 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-09 14:33:36.787  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-09 14:33:36.787  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-09 14:33:36.787  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-09 14:33:36.787  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-09 14:33:36.787  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-09 14:33:36.787  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-09 14:33:36.787  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-09 14:33:36.788  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-09 14:33:36.788  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-09 14:33:36.788  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-09 14:33:36.788  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-09 14:33:36.788  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-09 14:33:36.788  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-09 14:33:36.788  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-09 14:33:36.788  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-09 14:33:36.788  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-09 14:33:36.788  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-09 14:33:36.788  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-09 14:33:36.788  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-09 14:33:36.788  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-09 14:33:36.788  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-09 14:33:36.788  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-09 14:33:36.788  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-09 14:33:36.788  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-09 14:33:36.788  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-09 14:33:36.788  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-09 14:33:36.788  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-09 14:33:36.788  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-09 14:33:36.788  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-09 14:33:36.788  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-09 14:33:36.788  6669  6725 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-09 14:33:36.788  6669  6725 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-09 14:33:36.788  6669  6725 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-09 14:33:36.788  6669  6725 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-09 14:33:36.788  6669  6725 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-09 14:33:36.788  6669  6725 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-09 14:33:36.788  6669  6725 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-09 14:33:36.788  6669  6725 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-09 14:33:36.788  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-09 14:33:36.791  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-09 14:33:36.799  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-09 14:33:36.799  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-09 14:33:36.799  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-09 14:33:36.799  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-09 14:33:36.799  6669  6725 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-09 14:33:36.799  6669  6725 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-09 14:33:36.799  6669  6725 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-09 14:33:36.800  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:36.800  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:36.800  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:36.803  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:36.803  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.803  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.803  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-09 14:33:36.804  6669  6751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 831)
08-09 14:33:36.805  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@317226a4 not in the list
08-09 14:33:36.805  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.805  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.805  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:36.805  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.805  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.805  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.805  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 14:33:36.811  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:36.811  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:36.811  6669  6725 D BluetoothLeScanner: could not find callback wrapper
08-09 14:33:36.811  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 14:33:36.811  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.811  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.812  6669  6725 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-09 14:33:36.812  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:36.812  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:36.812  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:36.812  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:36.812  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.812  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.812  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@317226a4 not in the list
08-09 14:33:36.812  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.812  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.812  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:36.812  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.812  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.812  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.812  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.814  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:36.814  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:36.814  6669  6725 D BluetoothLeScanner: could not find callback wrapper
08-09 14:33:36.814  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 14:33:36.814  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.814  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.815  6669  6725 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-09 14:33:36.815  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:36.815  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:36.815  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:36.816  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:36.816  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.816  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.816  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@317226a4 not in the list
08-09 14:33:36.816  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.816  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.816  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:36.816  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.816  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.816  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.816  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.816  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:36.817  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:36.817  6669  6725 D BluetoothLeScanner: could not find callback wrapper
08-09 14:33:36.817  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 14:33:36.817  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.817  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.817  6669  6725 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-09 14:33:36.817  6669  6725 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-09 14:33:36.818  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-09 14:33:36.818  6669  6725 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-09 14:33:36.818  6669  6725 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-09 14:33:36.818  6669  6725 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-09 14:33:36.818  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-09 14:33:36.818  6669  6725 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-09 14:33:36.818  6669  6725 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-09 14:33:36.818  6669  6725 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-09 14:33:36.818  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-09 14:33:36.818  6669  6725 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-09 14:33:36.818  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:36.818  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:36.818  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:36.819  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:36.819  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.819  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.819  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@317226a4 not in the list
08-09 14:33:36.819  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.819  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.819  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:36.819  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.819  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.819  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.819  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.820  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:36.820  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:36.820  6669  6725 D BluetoothLeScanner: could not find callback wrapper
08-09 14:33:36.820  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 14:33:36.820  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.820  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.820  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:36.820  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.820  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.821  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@317226a4 not in the list
08-09 14:33:36.821  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.821  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.821  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:36.821  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.821  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.821  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.821  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.821  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:36.821  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.821  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.821  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@317226a4 not in the list
08-09 14:33:36.821  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:36.821  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:36.821  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:36.821  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:36.822  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.822  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.822  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@317226a4 not in the list
08-09 14:33:36.822  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.822  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.822  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:36.822  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.822  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.822  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.822  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.822  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:36.822  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:36.823  6669  6725 D BluetoothLeScanner: could not find callback wrapper
08-09 14:33:36.823  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 14:33:36.823  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.823  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.824  6669  6725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-09 14:33:36.824  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 14:33:36.824  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-09 14:33:36.825  6669  6725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-09 14:33:36.825  6669  6725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-09 14:33:36.828  6669  6669 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-09 14:33:36.833  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-09 14:33:36.833  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-09 14:33:36.838  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:36.838  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-09 14:33:36.838  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-09 14:33:36.838  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-09 14:33:36.838  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.838  6669  6725 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-09 14:33:36.839  6669  6669 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-09 14:33:36.839  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@317226a4 not in the list
08-09 14:33:36.839  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.839  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-09 14:33:36.839  6669  6725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-09 14:33:36.839  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-09 14:33:36.840  6669  6752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 831
08-09 14:33:36.840  6669  6752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 831)
08-09 14:33:36.840  6669  6752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 831)
08-09 14:33:36.841  1036  1997 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 14:33:36.842  6669  6753 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 14:33:36.843  3876  3896 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-09 14:33:36.848  6669  6753 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-09 14:33:36.848  6669  6753 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-09 14:33:36.848  6669  6753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-09 14:33:36.850  6669  6669 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-09 14:33:36.851  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-09 14:33:36.852  6669  6725 D BluetoothLeScanner: could not find callback wrapper
08-09 14:33:36.852  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 14:33:36.852  6669  6725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-09 14:33:36.852  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.852  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.853  6669  6725 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 14:33:36.853  6669  6669 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 14:33:36.853  6669  6669 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 14:33:36.853  6669  6669 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 14:33:36.854  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.854  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:36.854  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:36.854  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:36.854  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-09 14:33:36.854  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.854  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.854  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@317226a4 not in the list
,08-09 14:33:36.854  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.854  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.854  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:36.854  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.854  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.854  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.854  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.855  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-09 14:33:36.855  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:36.855  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.855  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.856  6669  6725 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-09 14:33:36.857  6669  6725 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-09 14:33:36.857  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-09 14:33:36.858  6669  6725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-09 14:33:36.858  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:36.858  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-09 14:33:36.858  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:36.858  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:36.859  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.859  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 14:33:36.859  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@317226a4 not in the list
08-09 14:33:36.859  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.859  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.859  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:36.859  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-09 14:33:36.859  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.859  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.859  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.860  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-09 14:33:36.860  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:36.860  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.860  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.862  1036  1890 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-09 14:33:36.863  1036  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 14:33:36.863  1036  1975 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 14:33:36.864  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:36.864  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-09 14:33:36.864  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:36.864  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:36.864  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.864  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 14:33:36.864  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@317226a4 not in the list
08-09 14:33:36.864  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.864  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.864  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
,08-09 14:33:36.864  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.864  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.864  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 14:33:36.864  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 14:33:36.865  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:36.865  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:36.865  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.865  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.866  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-09 14:33:36.866  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:36.866  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:36.866  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:36.867  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.867  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.867  6669  6725 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@317226a4 not in the list
08-09 14:33:36.867  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.867  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.867  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:36.867  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.867  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.867  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:36.867  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:36.868  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:36.868  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:36.868  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:36.868  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c389c0d not in the list
08-09 14:33:36.869  6669  6725 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-09 14:33:36.869  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-09 14:33:36.869  6669  6725 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-09 14:33:36.869  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-09 14:33:36.869  6669  6725 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-09 14:33:36.869  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-09 14:33:36.871  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-09 14:33:36.871  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-09 14:33:36.872  6669  6725 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-09 14:33:36.872  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-09 14:33:36.872  6669  6725 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-09 14:33:36.872  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-09 14:33:36.872  6669  6725 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,08-09 14:33:36.872  6669  6725 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-09 14:33:36.873  6669  6725 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-09 14:33:36.873  6669  6725 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-09 14:33:36.874  6669  6725 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-09 14:33:36.874  6669  6725 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-09 14:33:36.874  6669  6725 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-09 14:33:36.874  6669  6725 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-09 14:33:36.876  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-09 14:33:36.876  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@17115d1a added. We now have 2 listener(s)
08-09 14:33:36.876  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 14:33:36.877  6669  6725 D BluetoothAdapter: enable(): BT is already enabled..!
,08-09 14:33:36.878  1036  1928 D WifiServiceImplEx: setWifiEnabled: true pid=6669, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-09 14:33:36.878  1036  1928 D WifiService: setWifiEnabled: true pid=6669, uid=10118
08-09 14:33:36.878  1036  1928 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-09 14:33:36.880  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 14:33:36.880  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@38dec04b added. We now have 3 listener(s)
08-09 14:33:36.880  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 14:33:36.884  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 14:33:36.884  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a70ea28 added. We now have 4 listener(s)
08-09 14:33:36.884  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 14:33:36.886  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 14:33:36.886  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c5c1341 added. We now have 5 listener(s)
08-09 14:33:36.886  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 14:33:36.888  1036  1561 D WifiServiceImplEx: setWifiEnabled: false pid=6669, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-09 14:33:36.888  1036  1561 D WifiService: setWifiEnabled: false pid=6669, uid=10118
08-09 14:33:36.888  1036  1561 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-09 14:33:36.898  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-09 14:33:36.898  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-09 14:33:36.898  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-09 14:33:36.899  1036  1524 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-09 14:33:36.900  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-09 14:33:36.900  1036  1524 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-09 14:33:36.901  1036  1524 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-09 14:33:36.901  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 14:33:36.901  1036  1051 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3cf65e11 mBinding = false
08-09 14:33:36.901  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-09 14:33:36.901  1036  1524 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-09 14:33:36.902  1036  1524 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-09 14:33:36.902  1036  1524 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-09 14:33:36.902  1036  1524 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-09 14:33:36.902  1036  1524 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-09 14:33:36.908  1036  1524 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-09 14:33:36.908  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-09 14:33:36.908  1036  1518 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:36.909  1036  1518 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:36.909  2690  2690 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-09 14:33:36.909  1036  1524 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-09 14:33:36.909  1036  1524 D WifiNative-wlan0: doBoolean: SET ps 1
08-09 14:33:36.910  1036  1524 D WifiNative-wlan0: SET ps 1: returned true
08-09 14:33:36.910  1036  2849 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:36.910   306   894 D CommandListener: Clearing all IP addresses on wlan0
08-09 14:33:36.917  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-09 14:33:36.917  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-09 14:33:36.917  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-09 14:33:36.917  1036  1118 D BluetoothManagerService: Message: 2
08-09 14:33:36.918  1036  1118 D BluetoothManagerService: Sending off request.
08-09 14:33:36.919  3876  3895 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-09 14:33:36.920  3876  3954 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-09 14:33:36.920  3876  3954 D BluetoothAdapterProperties: Setting state to 13
08-09 14:33:36.920  3876  3954 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-09 14:33:36.920  3876  3954 D BluetoothAdapterProperties: onBluetoothDisable()
08-09 14:33:36.920  3876  3954 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-09 14:33:36.922  1036  1118 D BluetoothManagerService: Message: 60
08-09 14:33:36.923  3876  3958 D BluetoothAdapterProperties: Scan Mode:20
08-09 14:33:36.923  3876  3954 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-09 14:33:36.924  3876  4064 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
,08-09 14:33:36.924  3876  4064 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-09 14:33:36.924  3876  4301 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-09 14:33:36.924  3876  3954 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-09 14:33:36.925  3876  4064 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-09 14:33:36.925  3876  4064 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-09 14:33:36.925  3876  4064 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-09 14:33:36.925  3876  4064 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-09 14:33:36.925  3876  4064 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-09 14:33:36.925  3876  4064 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-09 14:33:36.925  3876  4064 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-09 14:33:36.925  3876  4064 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-09 14:33:36.925  3876  4064 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-09 14:33:36.925  3876  4064 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-09 14:33:36.925  3876  4064 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-09 14:33:36.925  3876  4280 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-09 14:33:36.925  3876  4064 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-09 14:33:36.925  3876  4244 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-09 14:33:36.925  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 14:33:36.926  3876  4299 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-09 14:33:36.926  3876  4243 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-09 14:33:36.926  3876  4243 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-09 14:33:36.926  3876  4243 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-09 14:33:36.926  3876  4243 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-09 14:33:36.926  3876  4243 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-09 14:33:36.926  3876  4243 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-09 14:33:36.926  3876  4243 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-09 14:33:36.926  3876  4243 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-09 14:33:36.928  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:36.928  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 14:33:36.928  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:36.928  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:36.928  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 14:33:36.928  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 14:33:36.928  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - BS,SID name: f4:f2:6d:22:99:3e
08-09 14:33:36.928  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 14:33:36.928  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 14:33:36.928  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:36.928  6669  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 14:33:36.929  6669  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 14:33:36.930  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-09 14:33:36.931  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:36.931  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-09 14:33:36.935  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:36.938  1036  1890 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-09 14:33:36.939  1036  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:36.939  1036  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:36.939  1036  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-09 14:33:36.939  1036  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:36.939  1036  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-09 14:33:36.940  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:36.940  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:36.940  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:36.940  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:36.940  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 14:33:36.940  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 14:33:36.940  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 14:33:36.940  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 14:33:36.940  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 14:33:36.941  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:36.941  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-09 14:33:36.949   306  6768 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-09 14:33:36.949  1036  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-09 14:33:36.949  1036  1116 D DSQN    : Dns fail occured do internet check.
08-09 14:33:36.950  1036  1036 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
08-09 14:33:36.950  1036  1036 D DSQN    : try Internet connection check
08-09 14:33:36.955  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-09 14:33:36.955  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-09 14:33:36.957  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:36.957  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:36.957  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:36.957  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:36.957  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 14:33:36.957  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 14:33:36.957  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:36.957  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 14:33:36.957  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 14:33:36.958  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:36.958  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-09 14:33:36.971  1036  1099 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6773 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-09 14:33:36.973  1036  1524 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:36.974  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:36.974  1036  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:36.974  1036  1518 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:36.974  1036  1518 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:36.974  1036  1518 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@de634f5
08-09 14:33:36.975  1036  1518 D LGWifiP2pService: P2pDisablingState
08-09 14:33:36.975  1036  1518 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:36.975  1036  1518 D LGWifiP2pService: p2p socket connection lost
08-09 14:33:36.975  1036  1518 D LGWifiP2pService: P2pDisabledState
08-09 14:33:36.976  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:36.976  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-09 14:33:36.977  3876  3876 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:36.977  3876  3876 D BluetoothMapService: STATE_TURNING_OFF
08-09 14:33:36.977  3876  3876 V BluetoothMapService: Handler(): got msg=4
08-09 14:33:36.977  3876  3876 D BluetoothMapService: MAP Service closeService in
08-09 14:33:36.977  3876  3876 D BluetoothMapMasInstance: MAP Service shutdown
08-09 14:33:36.978  3876  3876 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-09 14:33:36.978  3876  3876 V BluetoothMapService: MAP Service closeService out
08-09 14:33:36.978  1036  1524 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:36.978  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:36.978  3876  3876 V BtOppService: Receiver DISABLED_ACTION 
08-09 14:33:36.978  3876  3876 I BtOppRfcommListener: stopping Accept Thread
08-09 14:33:36.979  3876  3876 V BtOppRfcommListener: close mBtServerSocket
08-09 14:33:36.979  1036  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:36.979  3876  3876 V BtOppRfcommListener: waiting for thread to terminate
08-09 14:33:36.979  3876  4280 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-09 14:33:36.979  3876  3876 V BtOppRfcommListener: done waiting for thread to terminate
08-09 14:33:36.979  1036  1524 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-09 14:33:36.980  1036  1524 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:36.980  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:36.980  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:36.980  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:36.980  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:36.980  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 14:33:36.980  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 14:33:36.980  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:36.980  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:36.980  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 14:33:3,6.980  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:36.981  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:36.981  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-09 14:33:36.981  1036  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:36.981  1036  1524 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-09 14:33:36.982  1036  1518 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:36.982  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:36.982  1036  1518 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:36.982  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:36.982  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:36.982  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:36.982  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 14:33:36.982  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 14:33:36.982  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:36.982  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:36.982  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 14:33:36.982  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-09 14:33:36.982  2690  2690 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-09 14:33:36.983  1036  1524 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-09 14:33:36.983  1036  1524 D WifiNative-wlan0: doBoolean: SET ps 1
08-09 14:33:36.983  1036  1524 D WifiNative-wlan0: SET ps 1: returned true
08-09 14:33:37.004   306   894 D CommandListener: Clearing all IP addresses on wlan0
08-09 14:33:37.004  1036  1530 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-09 14:33:37.004  1036  1530 D DSQN    : disableDataServiceNotify
08-09 14:33:37.004  1036  1530 D DSQN    : stop dsqn bin
08-09 14:33:37.005   306  6793 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-09 14:33:37.006  1036  6770 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
08-09 14:33:37.006  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-09 14:33:37.006  1036  1099 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6792 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-09 14:33:37.006  1036  6769 D DSQN    : ThreadInternetCheck internet check NOK 
08-09 14:33:37.006  1036  6769 D DSQN    : InternetcheckProgress is not set don't send DS quality intent
,08-09 14:33:37.008  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-09 14:33:37.009  1926  1926 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-09 14:33:37.011  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:37.011  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:37.011  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-09 14:33:37.011  1036  1530 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-09 14:33:37.011  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 14:33:37.011  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 14:33:37.011  1036  1530 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 14:33:37.011  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-09 14:33:37.011  1036  1530 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-09 14:33:37.011  1036  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:37.012  1036  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:37.012  1036  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-09 14:33:37.012  1036  1530 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-09 14:33:37.012  1036  1530 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-09 14:33:37.012  1588  2058 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-09 14:33:37.012  6669  6751 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-09 14:33:37.012  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-09 14:33:37.012  6669  6751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 831)
08-09 14:33:37.013  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:37.013  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:37.013  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-09 14:33:37.013  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-09 14:33:37.013  1036  1542 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:37.013  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-09 14:33:,37.014  1036  1543 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:37.014  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-09 14:33:37.014  1926  1926 D WfdsService: WifiP2pState is changed : false
08-09 14:33:37.014  1926  2263 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-09 14:33:37.014  1926  2263 D WfdsService: Set the WFDS Monitor: false
08-09 14:33:37.015  1926  2263 D WfdsMonitor: WFDS Monitor is stopped
08-09 14:33:37.015  1926  2263 D WfdsService: STATE : WfdsDisabledState - enter
08-09 14:33:37.015  1926  2762 D CtrlSupplicant: Received on exit socket, terminate
08-09 14:33:37.015  1926  2762 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-09 14:33:37.015  1926  2762 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-09 14:33:37.015  1926  2762 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-09 14:33:37.015  1926  2263 W WfdsService: DefaultState - msg [9445378] is not handled
08-09 14:33:37.015  1036  1524 D WifiNative-p2p0: doBoolean: TERMINATE
08-09 14:33:37.015  1036  1524 D WifiNative-p2p0: TERMINATE: returned true
08-09 14:33:37.015  1036  1524 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-09 14:33:37.015  1036  1524 E WifiStateMachine: useWiFiOffloading() : false
08-09 14:33:37.015  1036  1524 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-09 14:33:37.016  1926  2269 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-09 14:33:37.016  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-09 14:33:37.018  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:37.018  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:37.018  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-09 14:33:37.018  1036  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:37.018  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-09 14:33:37.020  1036  1517 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
,08-09 14:33:37.023  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-09 14:33:37.023  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-09 14:33:37.023  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-09 14:33:37.023  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-09 14:33:37.026  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 14:33:37.026  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 14:33:37.026  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:37.028  3876  3876 V BtOppService: onDestroy
08-09 14:33:37.029  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-09 14:33:37.032  3876  3876 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,08-09 14:33:37.037  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-09 14:33:37.037  1036  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:37.037  1036  1530 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 14:33:37.037  1036  1530 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 14:33:37.038  1036  1530 D NetworkManagementService: Removing idletimer
08-09 14:33:37.038  1036  1530 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:37.038  1036  1517 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-09 14:33:37.038  1036  1530 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-09 14:33:37.038  1836  1836 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 14:33:37.038  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-09 14:33:37.039  1036  1524 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 14:33:37.039  1036  1524 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-09 14:33:37.039  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-09 14:33:37.039  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 14:33:37.039  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-09 14:33:37.039  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:37.040  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-09 14:33:37.040  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:37.040  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:37.040  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:37.040  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 14:33:37.040  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 14:33:37.040  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:37.040  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:37.040  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 14:33:37.040  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-09 14:33:37.040  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-09 14:33:37.041  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:37.041  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-,Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 14:33:37.042  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 14:33:37.042  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:37.042  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:37.042  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:37.042  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 14:33:37.042  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 14:33:37.042  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:37.042  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:37.042  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 14:33:37.043  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:37.044  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 14:33:37.052  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 14:33:37.052  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 14:33:37.052  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:37.053  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-09 14:33:37.053  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 14:33:37.054  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:37.055  6792  6792 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-09 14:33:37.055  6792  6792 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-09 14:33:37.055  6792  6792 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-09 14:33:37.055  6792  6792 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-09 14:33:37.056  6792  6792 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-09 14:33:37.056  6792  6792 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-09 14:33:37.070  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-09 14:33:37.070  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:37.071  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:37.071  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:37.083  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-09 14:33:37.083  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:37.084  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-09 14:33:37.101  2690  2690 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-09 14:33:37.101  2690  2690 I wpa_supplicant: monitor socket send errors count : 1
08-09 14:33:37.101  2690  2690 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1926-2\x00 that cannot receive messages
,08-09 14:33:37.102  1036  2743 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-09 14:33:37.102  1036  2743 D WifiMonitor: Dropping event because (p2p0) is stopped
08-09 14:33:37.107  6773  6773 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-09 14:33:37.107  6773  6773 W LG Account v2.2: No ProfileInfo entries
08-09 14:33:37.107  6773  6773 I LG Account v2.2: isEnabled: false
08-09 14:33:37.108  6773  6773 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-09 14:33:37.108  6773  6773 I Feature : [Lifetracker]Country: EU
08-09 14:33:37.108  6773  6773 I Feature : [Lifetracker]Operator: OPEN
08-09 14:33:37.108  6773  6773 I Feature : [Lifetracker]Ranking support: false
08-09 14:33:37.108  6773  6773 I Feature : [Lifetracker]Comfort support: false
08-09 14:33:37.108  6773  6773 I Feature : [Lifetracker]Accessory: true
08-09 14:33:37.108  6773  6773 I Feature : [Lifetracker]Health device: true
08-09 14:33:37.108  6773  6773 I Feature : [Lifetracker]Extra Pedometer: false
08-09 14:33:37.108  6773  6773 I Feature : [Lifetracker]Blood glucose device: false
08-09 14:33:37.108  6773  6773 I Feature : [Lifetracker]Device Number: 3
08-09 14:33:37.114  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-09 14:33:37.116  1036  2849 D DhcpStateMachine: StoppedState
,08-09 14:33:37.116  1036  2849 D DhcpStateMachine: StoppedState{ when=-133ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:37.133  6792  6792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-09 14:33:37.139  2690  2690 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-09 14:33:37.139  1036  2743 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-09 14:33:37.139  1036  2743 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-09 14:33:37.139  1036  2743 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-09 14:33:37.139  1036  2743 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-09 14:33:37.139  1036  1118 D Tethering: InitialState.processMessage what=4
08-09 14:33:37.140  2690  2690 W wpa_supplicant: USIM:  scard_deinit function
08-09 14:33:37.140  1036  1524 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=125345
08-09 14:33:37.140  1036  1524 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=125345
08-09 14:33:37.140  1036  2743 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-09 14:33:37.140  1036  2743 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-09 14:33:37.141  1036  1524 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=125345  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-09 14:33:37.141  1036  1524 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=125346  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-09 14:33:37.144  1036  2010 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6813 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-09 14:33:37.145  1036  2010 I ActivityManager: Killing 6176:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-09 14:33:37.182  2690  2690 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-09 14:33:37.182  1036  2743 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-09 14:33:37.182  1036  2743 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
,08-09 14:33:37.182  1036  2743 D WifiMonitor: Disconnecting from the supplicant, no more events
,08-09 14:33:37.183  1036  1524 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-09 14:33:37.195  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-09 14:33:37.199  3876  3876 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-09 14:33:37.199  3876  3876 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:37.199  3876  3876 V BluetoothPbapReceiver: ***********state = 13
08-09 14:33:37.202  3876  3876 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-09 14:33:37.203  1036  1118 D BluetoothManagerService: Message: 20
08-09 14:33:37.203  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1481bc50:true
08-09 14:33:37.212  1036  1052 W libprocessgroup: failed to open /acct/uid_10014/pid_6176/cgroup.procs: No such file or directory
,08-09 14:33:37.223  3876  3876 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:37.223  3876  3876 V BluetoothPbapService: state: 13
08-09 14:33:37.223  3876  3876 V BluetoothPbapService: Pbap Service closeService in
08-09 14:33:37.226  2140  2140 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-09 14:33:37.227  3876  3876 V BluetoothPbapService: successfully stopped pbap service
08-09 14:33:37.228  3876  3876 V BluetoothPbapService: Pbap Service closeService out
08-09 14:33:37.228  3876  3876 V BluetoothPbapService: Pbap Service onDestroy
08-09 14:33:37.228  3876  3876 V BluetoothPbapService: Pbap Service closeService in
08-09 14:33:37.228  3876  3876 V BluetoothPbapService: Pbap Service closeService out
08-09 14:33:37.228  3876  3876 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-09 14:33:37.232  1036  1118 D BluetoothManagerService: Message: 30
08-09 14:33:37.240  1036  1118 D BluetoothManagerService: Message: 30
08-09 14:33:37.243  6792  6792 D LocalBluetoothProfileManager: Adding local MAP profile
,08-09 14:33:37.245  6792  6792 D BluetoothMap: Create BluetoothMap proxy object
08-09 14:33:37.245  1036  1118 D BluetoothManagerService: Message: 30
08-09 14:33:37.250  1036  1118 D BluetoothManagerService: Message: 30
08-09 14:33:37.253  6792  6792 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-09 14:33:37.254  6792  6792 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,08-09 14:33:37.270  6792  6792 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-09 14:33:37.273  6792  6792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,08-09 14:33:37.284  1036  1524 D WifiOffDelayIfNotUsed: stopMonitoring
,08-09 14:33:37.284  1036  1524 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-09 14:33:37.284  1036  1524 E WifiStateMachine: useWiFiOffloading() : false
08-09 14:33:37.284  1036  1524 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-09 14:33:37.285  1926  1926 D WfdsService: Supplicant Connection state is changed : false
08-09 14:33:37.286  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:37.286  1926  2263 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-09 14:33:37.286  1926  2263 D WfdsService: Set the WFDS Monitor: false
08-09 14:33:37.286  1926  2263 D WfdsMonitor: WFDS Monitor is stopped
08-09 14:33:37.287  6792  6792 D DockEventReceiver: finishStartingService: stopping service
08-09 14:33:37.288  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-09 14:33:37.288  1036  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-09 14:33:37.288  1036  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-09 14:33:37.288  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-09 14:33:37.289  2454  2454 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:37.291  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:37.291  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:37.291  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:37.291  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:37.291  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 14:33:37.291  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 14:33:37.291  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:37.291  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:37.291  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 14:33:37.295  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:37.302  6792  6792 D BluetoothInputDevice: Proxy object connected
08-09 14:33:37.302  6792  6792 D HidProfile: Bluetooth service connected
08-09 14:33:37.303  6813  6813 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-09 14:33:37.304  6792  6792 D BluetoothPan: BluetoothPAN Proxy object connected
,08-09 14:33:37.304  6792  6792 D PanProfile: Bluetooth service connected
08-09 14:33:37.305  6792  6792 D BluetoothMap: Proxy object connected
08-09 14:33:37.306  6792  6792 D MapProfile: Bluetooth service connected
08-09 14:33:37.306  6792  6792 D BluetoothMap: getConnectedDevices()
08-09 14:33:37.307  6792  6792 D BluetoothMap: Bluetooth is Not enabled
08-09 14:33:37.307  6792  6792 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-09 14:33:37.308  6792  6792 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-09 14:33:37.313  6813  6813 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-09 14:33:37.313  6813  6813 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-09 14:33:37.313  6792  6792 D BluetoothPermissionRequest: onReceive
08-09 14:33:37.315  1036  1579 I ActivityManager: Killing 6443:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-09 14:33:37.315  6792  6792 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-09 14:33:37.354  6669  6669 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-09 14:33:37.361  1036  1052 W libprocessgroup: failed to open /acct/uid_10008/pid_6443/cgroup.procs: No such file or directory
,08-09 14:33:37.364  1036  1052 I ActivityManager: Killing 5974:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-09 14:33:37.382  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 14:33:37.419  6792  6792 D LgDataFeature: LgDataFeature() Constructor: none
08-09 14:33:37.419  6792  6792 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-09 14:33:37.432  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:33:37.441  1036  2017 W libprocessgroup: failed to open /acct/uid_10011/pid_5974/cgroup.procs: No such file or directory
08-09 14:33:37.449  3876  3876 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-09 14:33:37.449  3876  3876 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-09 14:33:37.450  3876  3876 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-09 14:33:37.454  6792  6792 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-09 14:33:37.462  3876  3876 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:37.463  3876  3876 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-09 14:33:37.464  3876  3876 V BluetoothFtpService: Ftp Service onStartCommand
08-09 14:33:37.465  3876  3876 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:37.465  3876  3876 V BluetoothFtpService: Ftp Service closeService
08-09 14:33:37.465  3876  3876 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,08-09 14:33:37.487  1036  1524 E WifiStateMachine:  InitialState CMD_TETHER_STATE_CHANGE 0 0
,08-09 14:33:37.488  1036  1524 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-09 14:33:37.490  1036  1524 E WifiStateMachine:  InitialState CMD_ON_QUIT 0 0
08-09 14:33:37.491  1036  1524 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-09 14:33:37.548  1036  1853 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6841 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-09 14:33:37.551  3876  3876 V BluetoothFtpService: successfully stopped ftp service
08-09 14:33:37.551  3876  3876 V BluetoothFtpService: Ftp Service onDestroy
08-09 14:33:37.551  3876  3876 V BluetoothFtpService: Ftp Service closeService
08-09 14:33:37.554  3876  3876 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-09 14:33:37.554  3876  3876 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-09 14:33:37.554  3876  3876 V BluetoothSapReceiver: SapReceiver onReceive 
08-09 14:33:37.554  3876  3876 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:37.554  3876  3876 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-09 14:33:37.554  3876  3876 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-09 14:33:37.556  3876  3876 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:37.556  3876  3876 V BluetoothSapService: state: 13
08-09 14:33:37.556  3876  3876 V BluetoothSapService: Stopping SAP server process
08-09 14:33:37.558  3876  3876 V BluetoothSapService: Sap Service closeSapService in
08-09 14:33:37.558  3876  3876 V BluetoothSapService: Close listen Socket : 
08-09 14:33:37.559  3876  3876 V BluetoothSapService: Close rfcomm Socket : 
08-09 14:33:37.559  3876  3876 V BluetoothSapService: Close sapd  Socket : 
08-09 14:33:37.614  1036  1579 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6858 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-09 14:33:37.617  3876  3876 V BluetoothSapService: Sap Service closeSapService out
08-09 14:33:37.617  3876  3876 V BluetoothSapService: Sap Service onDestroy
08-09 14:33:37.617  3876  3876 V BluetoothSapService: Sap Service closeSapService in
08-09 14:33:37.617  3876  3876 V BluetoothSapService: Close listen Socket : 
08-09 14:33:37.617  3876  3876 V BluetoothSapService: Close rfcomm Socket : 
08-09 14:33:37.617  3876  3876 V BluetoothSapService: Close sapd  Socket : 
08-09 14:33:37.624  3876  3876 V BluetoothSapService: Sap Service closeSapService out
08-09 14:33:37.641   345   345 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 480us total 27.722ms
,08-09 14:33:37.656  6841  6841 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-09 14:33:37.661   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 412us total 19.953ms
08-09 14:33:37.680   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 360us total 17.948ms
08-09 14:33:37.682  6858  6858 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-09 14:33:37.686  6841  6841 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-09 14:33:37.698  1036  1928 I ActivityManager: Killing 6294:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-09 14:33:37.715  6841  6841 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-09 14:33:37.716  6841  6841 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-09 14:33:37.716  6841  6841 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-09 14:33:37.716  6841  6841 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-09 14:33:37.716  6841  6841 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-09 14:33:37.718  6841  6841 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-09 14:33:37.722  6841  6841 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-09 14:33:37.767  1036  1871 W libprocessgroup: failed to open /acct/uid_10004/pid_6294/cgroup.procs: No such file or directory
,08-09 14:33:37.783  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-09 14:33:37.786  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 14:33:37.807  6841  6841 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-09 14:33:37.810  6841  6841 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-09 14:33:37.812  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 14:33:37.813  6841  6841 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-09 14:33:37.816  6813  6813 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-09 14:33:37.816  6813  6813 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-09 14:33:37.816  6813  6813 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-09 14:33:37.821  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 14:33:37.827  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:33:37.835  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 14:33:37.835  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-09 14:33:37.838  6841  6841 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-09 14:33:37.841  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 14:33:37.845  6813  6813 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-09 14:33:37.845  6813  6813 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-09 14:33:37.845  6813  6813 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-09 14:33:37.849  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 14:33:37.855  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:33:37.865  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-09 14:33:37.866  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-09 14:33:37.867  6841  6841 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-09 14:33:37.929  3876  4064 W bt-btif : ag scb idx 1 not allocated
08-09 14:33:37.929  3876  3958 D bt_hci_bdroid: cleanup
08-09 14:33:37.929  3876  4066 I bt_lpm  : LPM is already off!!!
08-09 14:33:37.929  3876  4064 E bt-btif : BTA AG is already disabled, ignoring ...
08-09 14:33:37.929  3876  4064 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-09 14:33:37.930  3876  4064 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-09 14:33:37.930  3876  4064 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-09 14:33:37.930  3876  4064 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-09 14:33:37.930  3876  4064 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-09 14:33:37.930  3876  4064 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-09 14:33:37.930  3876  4064 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-09 14:33:37.930  3876  4064 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-09 14:33:37.930  3876  4064 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-09 14:33:37.930  3876  4064 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-09 14:33:37.930  3876  4064 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-09 14:33:37.930  3876  4230 I bt_userial_mct: exiting userial_read_thread
08-09 14:33:37.930  3876  4064 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-09 14:33:37.930  3876  4230 D bt_userial_mct: Leaving userial_evt_read_thread()
08-09 14:33:37.930  3876  4064 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-09 14:33:37.930  3876  4064 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-09 14:33:37.930  3876  4064 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-09 14:33:37.930  3876  4064 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-09 14:33:37.930  3876  4064 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-09 14:33:37.930  3876  4064 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-09 14:33:37.930  3876  4064 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-09 14:33:37.931  3876  3958 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,08-09 14:33:37.931  3876  4066 I bt_vendor: hw_epilog_process
08-09 14:33:37.931  3876  3958 D bt_hci_bdroid: cleanup Finalizing cleanup,
08-09 14:33:37.931  3876  3958 D bt_userial_mct: userial_close
,08-09 14:33:37.931  3876  3958 E bt_userial_mct: pthread_join() FAILED result:3
08-09 14:33:37.931  3876  3958 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-09 14:33:37.934  1036  1561 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6881 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-09 14:33:38.008  1036  1036 D DSQN    : EVENT_INTERNET_CHECK_ENABLE received
,08-09 14:33:38.011  3876  3958 D bt_hci_bdroid: set_power 0
08-09 14:33:38.011  3876  3958 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-09 14:33:38.011  3876  3958 I bt_vendor: bluetooth satus is on
08-09 14:33:38.011  3876  3958 I bt_vendor: bt-vendor : resetting BT status
08-09 14:33:38.011  3876  3958 I bt_vendor: Starting hciattach daemon
08-09 14:33:38.011  3876  3958 I bt_vendor: try to set false
08-09 14:33:38.013  3876  3958 I bt_vendor: Starting hciattach daemon
08-09 14:33:38.013  3876  3958 I bt_vendor: try to set false
08-09 14:33:38.015  3876  3958 I bt_vendor: cleanup
08-09 14:33:38.016  3876  4064 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-09 14:33:38.016  3876  3958 I GKI_LINUX: GKI_exit_task 0 done
08-09 14:33:38.016  3876  3958 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-09 14:33:38.018  3876  3954 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-09 14:33:38.020  3876  3876 D HeadsetService: Received stop request...Stopping profile...
,08-09 14:33:38.025  3876  3876 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-09 14:33:38.025  3876  3876 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-09 14:33:38.025  3876  3876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1957770c
08-09 14:33:38.025  3876  3983 D HeadsetStateMachine: Exit Disconnected: -1
08-09 14:33:38.028  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-09 14:33:38.029  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-09 14:33:38.030  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-09 14:33:38.031  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-09 14:33:38.031  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-09 14:33:38.032  3876  3876 D A2dpService: Received stop request...Stopping profile...
,08-09 14:33:38.033  3876  4038 D A2dpStateMachine: Exit Disconnected: -1
08-09 14:33:38.035  3876  3876 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-09 14:33:38.036  3876  3954 D BluetoothAdapterState: Stopping profile services that were post enabled
08-09 14:33:38.038  3876  3876 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-09 14:33:38.038  3876  3876 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-09 14:33:38.038  3876  3876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1957770c
08-09 14:33:38.039  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-09 14:33:38.039  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-09 14:33:38.040  3876  3876 D HidService: Received stop request...Stopping profile...
08-09 14:33:38.040  3876  3876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1957770c
08-09 14:33:38.043  3876  3876 D HealthService: Received stop request...Stopping profile...
08-09 14:33:38.043  3876  3876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1957770c
08-09 14:33:38.045  6792  6792 D BluetoothInputDevice: Proxy object disconnected
,08-09 14:33:38.046  6792  6792 D HidProfile: Bluetooth service disconnected
08-09 14:33:38.046  3876  3876 D HeadsetStateMachine: Unbinding service...
08-09 14:33:38.048  3876  3876 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-09 14:33:38.048  3876  3876 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-09 14:33:38.048  3876  3876 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-09 14:33:38.048  3876  3876 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-09 14:33:38.048  3876  3876 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-09 14:33:38.048  3876  3876 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-09 14:33:38.049  3876  3876 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-09 14:33:38.050  3876  3876 D PanService: Received stop request...Stopping profile...
08-09 14:33:38.052  3876  3876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1957770c
08-09 14:33:38.053  3876  3876 D BtGatt.DebugUtils: handleDebugAction() action=null
08-09 14:33:38.053  6792  6792 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-09 14:33:38.053  6792  6792 D PanProfile: Bluetooth service disconnected
08-09 14:33:38.055  3876  3876 D BtGatt.GattService: Received stop request...Stopping profile...
08-09 14:33:38.055  3876  3876 D BtGatt.GattService: stop()
08-09 14:33:38.055  3876  3876 D BtGatt.AdvertiseManager: advertise clients cleared
08-09 14:33:38.056  3876  3876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1957770c
08-09 14:33:38.057  6813  6813 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-09 14:33:38.058  3876  3876 D BluetoothMapService: Received stop request...Stopping profile...
08-09 14:33:38.058  3876  3876 D BluetoothMapService: stop()
08-09 14:33:38.062  3876  3876 D BluetoothMapEmailAppObserver: deinitObservers()
08-09 14:33:38.063  3876  3876 D BluetoothMapEmailAppObserver: removeReceiver()
,08-09 14:33:38.063  3876  3876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1957770c
08-09 14:33:38.064  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-09 14:33:38.065  3876  3876 I BluetoothA2dpServiceJni: cleanupNative
08-09 14:33:38.065  3876  4040 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-09 14:33:38.065  3876  3876 I GKI_LINUX: GKI_exit_task 2 done
08-09 14:33:38.065  3876  3876 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-09 14:33:38.065  3876  3876 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-09 14:33:38.065  3876  3876 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-09 14:33:38.066  3876  3876 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-09 14:33:38.066  3876  3876 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-09 14:33:38.066  3876  3876 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-09 14:33:38.066  3876  3876 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-09 14:33:38.066  3876  3876 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-09 14:33:38.068  3876  3876 V BluetoothMapService: Handler(): got msg=4
08-09 14:33:38.068  3876  3876 D BluetoothMapService: MAP Service closeService in
08-09 14:33:38.068  3876  3876 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-09 14:33:38.068  3876  3876 V BluetoothMapService: MAP Service closeService out
08-09 14:33:38.068  3876  3876 D BluetoothMapService: cleanup()
08-09 14:33:38.068  3876  3876 D BluetoothMapService: MAP Service closeService in
08-09 14:33:38.068  3876  3876 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-09 14:33:38.068  3876  3876 V BluetoothMapService: MAP Service closeService out
08-09 14:33:38.068  3876  3954 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-09 14:33:38.068  3876  3954 D BluetoothAdapterProperties: Setting state to 10
08-09 14:33:38.068  3876  3954 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-09 14:33:38.069  1036  1118 D BluetoothManagerService: Message: 60
08-09 14:33:38.069  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-09 14:33:38.069  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-09 14:33:38.069  3876  3954 I BluetoothAdapterState: Entering OffState
08-09 14:33:38.070  1836  1851 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 14:33:38.071  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
08-09 14:33:38.072  6792  6809 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-09 14:33:38.073  6792  6810 D BluetoothPbap: onBluetoothStateChange: up=false
08-09 14:33:38.075  1836  2737 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 14:33:38.076  1836  1851 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 14:33:38.076  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:33:38.076  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 14:33:38.077  6792  6809 D BluetoothPan: onBluetoothStateChange on: false
08-09 14:33:38.078  6792  6810 D BluetoothMap: onBluetoothStateChange: up=false
08-09 14:33:38.085  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-09 14:33:38.085  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,08-09 14:33:38.090  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-09 14:33:38.090  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-09 14:33:38.090  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3cf65e11 mBinding = false
08-09 14:33:38.090  1036  1118 D BluetoothManagerService: Sending unbind request.
08-09 14:33:38.092  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-09 14:33:38.098  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:38.099  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:38.101  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:38.101  1926  2073 D LGBluetoothAPIService: Message: 2
08-09 14:33:38.101  1926  2073 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@204a2ecf mBinding = false
08-09 14:33:38.101  1926  2073 D LGBluetoothAPIService: Sending unbind request.
08-09 14:33:38.102  3876  3958 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-09 14:33:38.103  3876  3876 I GKI_LINUX: GKI_exit_task 1 done
08-09 14:33:38.103  3876  3876 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-09 14:33:38.103  3876  3876 I BluetoothServiceJni: cleanupNative: return from cleanup
08-09 14:33:38.103  3876  3876 I art     : --- WEIRD: removing null entry 246
08-09 14:33:38.103  3876  3876 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-09 14:33:38.103  3876  3876 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
,08-09 14:33:38.105  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-09 14:33:38.107  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-09 14:33:38.107  6792  6792 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-09 14:33:38.107  6792  6792 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-09 14:33:38.107  6792  6792 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-09 14:33:38.109  3876  3876 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-09 14:33:38.109  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-09 14:33:38.110  1588  1588 D BluetoothAdapter: 265765047: getState() :  mService = null. Returning STATE_OFF
08-09 14:33:38.110  1588  1588 D BluetoothAdapter: 265765047: getState() :  mService = null. Returning STATE_OFF
08-09 14:33:38.112  3876  3876 I art     : System.exit called, status: 0
08-09 14:33:38.112  3876  3876 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-09 14:33:38.115  6881  6901 W FormManager: Network not available. Please check & try again.
08-09 14:33:38.120  6792  6792 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-09 14:33:38.120  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-09 14:33:38.120  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-09 14:33:38.120  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-09 14:33:38.121  6792  6792 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-09 14:33:38.121  6792  6792 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-09 14:33:38.127  6881  6903 V FormManager: Network unavailable.
08-09 14:33:38.128  6792  6792 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-09 14:33:38.128  6792  6792 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-09 14:33:38.128  6792  6792 D LGBluetoothEventManager: [BTUI] clear device connection state
08-09 14:33:38.131  6792  6792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-09 14:33:38.133  6881  6903 V FormManager: Network unavailable.
,08-09 14:33:38.141   315  3988 V AudioFlinger: 3876 died, releasing its sessions
08-09 14:33:38.141   315  3988 V AudioFlinger:  pid 1836 @ 0
08-09 14:33:38.141   315  3988 V AudioFlinger:  pid 3490 @ 1
08-09 14:33:38.141   315  3988 V AudioFlinger:  pid 3490 @ 2
08-09 14:33:38.141  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-09 14:33:38.142  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-09 14:33:38.144  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-09 14:33:38.181  1036  1956 I ActivityManager: Process com.android.bluetooth (pid 3876) has died
,08-09 14:33:38.181  1036  1956 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-09 14:33:38.189  6792  6792 D DockEventReceiver: finishStartingService: stopping service
08-09 14:33:38.191  6792  6792 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-09 14:33:38.196  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-09 14:33:38.208  4305  6913 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-09 14:33:38.209  2140  2140 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-09 14:33:38.213  4305  6914 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-09 14:33:38.213  4305  6914 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-09 14:33:38.216  1036  1579 I ActivityManager: Killing 5996:com.android.contacts/u0a19 (adj 15): empty #17
08-09 14:33:38.306  1036  1889 W libprocessgroup: failed to open /acct/uid_10019/pid_5996/cgroup.procs: No such file or directory
,08-09 14:33:38.345  6813  6813 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-09 14:33:38.345  6813  6813 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-09 14:33:38.345  6813  6813 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-09 14:33:38.347  6881  6917 W FormManager: Network not available. Please check & try again.
08-09 14:33:38.357  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-09 14:33:38.365  6881  6918 V FormManager: Network unavailable.
08-09 14:33:38.368  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:33:38.369  6881  6918 V FormManager: Network unavailable.
08-09 14:33:38.371  6792  6792 D BluetoothPermissionRequest: onReceive
08-09 14:33:38.376  6792  6792 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-09 14:33:38.378  6792  6792 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-09 14:33:38.380  6792  6792 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-09 14:33:38.433  1036  1052 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6919 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-09 14:33:38.457  6841  6841 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-09 14:33:38.459  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-09 14:33:38.461  6841  6841 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-09 14:33:38.507  6919  6919 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-09 14:33:38.508  6919  6919 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-09 14:33:38.508  6841  6841 D LgDataFeature: LgDataFeature() Constructor: none
08-09 14:33:38.508  6919  6919 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-09 14:33:38.508  6841  6841 D LgDataFeature: LgDataFeature() Constructor Done, null
08-09 14:33:38.509  6919  6919 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-09 14:33:38.519  6841  6841 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-09 14:33:38.521  6841  6841 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-09 14:33:38.521  6841  6841 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-09 14:33:38.521  6841  6841 V SoundPool: doLoad: loading sample sampleID=1
,08-09 14:33:38.521  6841  6841 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-09 14:33:38.527  6841  6938 V SoundPool: Start decode
08-09 14:33:38.527  6841  6938 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-09 14:33:38.528   315  2155 V MediaPlayerService: decode(23, 10857164, 17813)
08-09 14:33:38.528   315  2155 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-09 14:33:38.528   315  2155 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-09 14:33:38.528   315  2155 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-09 14:33:38.528   315  2155 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-09 14:33:38.528   315  2155 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-09 14:33:38.528  6603  6603 D UEI.SmartControl: QS Service created
08-09 14:33:38.528   315  2155 V MediaPlayerService: player type = 3
08-09 14:33:38.528   315  2155 V AwesomePlayer: AwesomePlayer create()
08-09 14:33:38.529   315  2155 V AwesomePlayer: reset_l() 
08-09 14:33:38.529   315  2155 V AwesomePlayer: cancelPlayerEvents
08-09 14:33:38.529   315  2155 V AwesomePlayer: setAudioSink() 
08-09 14:33:38.529   315  2155 V AwesomePlayer: reset_l() 
08-09 14:33:38.529   315  2155 V AudioCache: notify(0xb1432f00, 8, 0, 0)
08-09 14:33:38.529   315  2155 V AudioCache: ignored
08-09 14:33:38.529   315  2155 V AwesomePlayer: cancelPlayerEvents
08-09 14:33:38.529  6919  6919 D BluetoothAdapterApp: Loading JNI Library
08-09 14:33:38.529   315  2155 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-09 14:33:38.529   315  2155 V AwesomePlayer: setDataSource_l dataSource
08-09 14:33:38.529   315  2155 V LGParserOSAL: SniffLGParser start
08-09 14:33:38.529   315  2155 V LGParserOSAL: MainType:5, SubType=0
08-09 14:33:38.529   315  2155 V LGParserOSAL: #### check Mime : application/ogg
08-09 14:33:38.529   315  2155 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-09 14:33:38.529   315  2155 E MediaExtractor: Use LGExtractor :application/ogg 
08-09 14:33:38.531  6841  6841 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-09 14:33:38.541  6841  6841 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-09 14:33:38.542  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-09 14:33:38.558  6603  6603 I UEI.SmartControl: Service initServices...
,08-09 14:33:38.559  6603  6603 D UEI.SmartControl: QS start get config
,08-09 14:33:38.566  6919  6919 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@49a29d Instance Count = 1
08-09 14:33:38.569  6841  6841 V LGMDMManager: Create singleton instance
08-09 14:33:38.572  6919  6919 D BluetoothAdapterApp: onCreate
08-09 14:33:38.580   315  2155 V LGParserOSAL: supported mime: application/ogg
08-09 14:33:38.580   315  2155 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-09 14:33:38.580   315  2155 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-09 14:33:38.580   315  2155 V AwesomePlayer: mBitrate = -1 bits/sec
08-09 14:33:38.580   315  2155 V AwesomePlayer: AudioTrack Setting
08-09 14:33:38.580   315  2155 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-09 14:33:38.580   315  2155 V AwesomePlayer: setAudioSource() 
08-09 14:33:38.580   315  2155 V MediaPlayerService: prepare
08-09 14:33:38.580   315  2155 V AwesomePlayer: prepareAsync_l() 
08-09 14:33:38.580   315  2155 V MediaPlayerService: wait for prepare
08-09 14:33:38.580   315  6939 V AwesomePlayer: onPrepareAsyncEvent() 
08-09 14:33:38.580   315  6939 V AwesomePlayer: initAudioDecoder() 
08-09 14:33:38.580   315  6939 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-09 14:33:38.580   315  6939 V AudioSystem: isOffloadSupported()
08-09 14:33:38.581   315  6939 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-09 14:33:38.581   315  6939 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-09 14:33:38.581   315  6939 I AudioFlinger: isAudioPlaybackHookOn() false
08-09 14:33:38.581   315  6939 V AwesomePlayer: getUseOffload() = 0 
08-09 14:33:38.581   315  6939 V OMXCodec: OMXCodec::Create
08-09 14:33:38.581   315  6939 V OMXCodec: findMatchingCodecs()
08-09 14:33:38.581   315  6939 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-09 14:33:38.581   315  6939 V OMXCodec: matchingCodecs.size()=1
08-09 14:33:38.581   315  6939 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-09 14:33:38.583   315  6939 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-09 14:33:38.583   315  6939 V LGCodecAdapter: LG Codec Adapter start
08-09 14:33:38.583   315  6939 V OMXCodec: OMXCodec Createtor
08-09 14:33:38.583   315  6939 V OMXCodec: setComponentRole
08-09 14:33:38.583   315  6939 V OMXCodec: configureCodec protected=0
08-09 14:33:38.583   315  6939 V LGCodecAdapter: called getLGCodecSpecificData
08-09 14:33:38.583   315  6939 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-09 14:33:38.583   315  6939 V LGCodecOSAL: Called LGconfigureCodecMETA
08-09 14:33:38.583   315  6939 V LGCodecOSAL: Called LGconfigureCodecMSG
08-09 14:33:38.583   315  6939 V LGCodecOSAL: Not support LGCodec
08-09 14:33:38.583   315  6939 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-09 14:33:38.583   315  6939 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-09 14:33:38.583   315  6939 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-09 14:33:38.583   315  6939 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-09 14:33:38.583   315  6939 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-09 14:33:38.583   315  6939 V AudioSystem: isOffloadSupported()
08-09 14:33:38.584   315  6939 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-09 14:33:38.584   315  6939 D AudioPo,licyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-09 14:33:38.584   315  6939 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-09 14:33:38.584   315  6939 V OMXCodec: init()
08-09 14:33:38.584   315  6939 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-09 14:33:38.584   315  6939 V OMXCodec: allocateBuffers
08-09 14:33:38.584   315  6939 V OMXCodec: allocateBuffersOnPort portIndex=0
08-09 14:33:38.584   315  6939 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-09 14:33:38.584   315  6939 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7650 on input port
08-09 14:33:38.584   315  6939 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
08-09 14:33:38.584   315  6939 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-09 14:33:38.584   315  6939 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-09 14:33:38.584   315  6939 V OMXCodec: allocateBuffersOnPort portIndex=1
08-09 14:33:38.584   315  6939 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-09 14:33:38.584   315  6939 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-09 14:33:38.584   315  6939 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-09 14:33:38.584   315  6939 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-09 14:33:38.584   315  6939 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
08-09 14:33:38.584   315  6939 V OMXCodec: init() mAsyncCompletion wait!!! 
08-09 14:33:38.585   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-09 14:33:38.585   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-09 14:33:38.585   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-09 14:33:38.585   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-09 14:33:38.585   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-09 14:33:38.585   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-09 14:33:38.585   315  6939 V OMXCodec: init() mAsyncCompletion wait free! 
08-09 14:33:38.585   315  6939 V AwesomePlayer: finishAsyncPrepare_l() 
08-09 14:33:38.585   315  6939 V AudioCache: notify(0xb1432f00, 5, 0, 0)
08-09 14:33:38.585   315  6939 V AudioCache: ignored
08-09 14:33:38.585   315  6939 V AudioCache: notify(0xb1432f00, 1, 0, 0)
08-09 14:33:38.585   315  6939 V AudioCache: prepared
08-09 14:33:38.585   315  2155 V AudioCache: wait - success
,08-09 14:33:38.585   315  2155 V MediaPlayerService: start
08-09 14:33:38.585   315  2155 V AwesomePlayer: play_l() 
08-09 14:33:38.585   315  2155 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-09 14:33:38.585   315  2155 V AwesomePlayer: createAudioPlayer_l
08-09 14:33:38.585   315  2155 V AwesomePlayer: seekAudioIfNecessary_l() 
08-09 14:33:38.585   315  2155 V AwesomePlayer: startAudioPlayer_l() 
08-09 14:33:38.585   315  2155 D AudioPlayer: start of Playback, useOffload 0
08-09 14:33:38.585   315  2155 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-09 14:33:38.585   315  2155 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
,08-09 14:33:38.588   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-09 14:33:38.588   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-09 14:33:38.588   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-09 14:33:38.588   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-09 14:33:38.588   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-09 14:33:38.588   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-09 14:33:38.588   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
08-09 14:33:38.588   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-09 14:33:38.588   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
,08-09 14:33:38.588   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-09 14:33:38.588   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
08-09 14:33:38.589   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-09 14:33:38.589   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885968
08-09 14:33:38.589   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-09 14:33:38.589   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-09 14:33:38.589   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-09 14:33:38.589   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-09 14:33:38.589   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
,08-09 14:33:38.589   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-09 14:33:38.589   315  6941 V OMXCodec: allocateBuffersOnPort portIndex=1
08-09 14:33:38.589   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-09 14:33:38.589   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-09 14:33:38.589   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-09 14:33:38.589   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-09 14:33:38.589   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb000f1f0 on output port
08-09 14:33:38.589   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
,08-09 14:33:38.589   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-09 14:33:38.591   315  2155 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-09 14:33:38.592   315  2155 V AudioCache: notify(0xb1432f00, 6, 0, 0)
08-09 14:33:38.592   315  2155 V AudioCache: ignored
08-09 14:33:38.592   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.592   315  6942 V AudioCache: memcpy(0xabeff000, 0xb17ed000, 4096)
08-09 14:33:38.592   315  2155 V MediaPlayerService: wait for playback complete
08-09 14:33:38.595   315  6942 V AudioCache: write(0xb17ed000, 4096)
,08-09 14:33:38.595   315  6942 V AudioCache: memcpy(0xabf00000, 0xb17ed000, 4096)
08-09 14:33:38.595   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.595   315  6942 V AudioCache: memcpy(0xabf01000, 0xb17ed000, 4096)
08-09 14:33:38.595   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.595   315  6942 V AudioCache: memcpy(0xabf02000, 0xb17ed000, 4096)
,08-09 14:33:38.596   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.596   315  6942 V AudioCache: memcpy(0xabf03000, 0xb17ed000, 4096)
08-09 14:33:38.596   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.596   315  6942 V AudioCache: memcpy(0xabf04000, 0xb17ed000, 4096)
08-09 14:33:38.597   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.597   315  6942 V AudioCache: memcpy(0xabf05000, 0xb17ed000, 4096)
08-09 14:33:38.598   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.598   315  6942 V AudioCache: memcpy(0xabf06000, 0xb17ed000, 4096)
08-09 14:33:38.598   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.598   315  6942 V AudioCache: memcpy(0xabf07000, 0xb17ed000, 4096)
08-09 14:33:38.599   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.599   315  6942 V AudioCache: memcpy(0xabf08000, 0xb17ed000, 4096)
08-09 14:33:38.600   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.600   315  6942 V AudioCache: memcpy(0xabf09000, 0xb17ed000, 4096)
08-09 14:33:38.601   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.601   315  6942 V AudioCache: memcpy(0xabf0a000, 0xb17ed000, 4096)
08-09 14:33:38.603   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.603   315  6942 V AudioCache: memcpy(0xabf0b000, 0xb17ed000, 4096)
08-09 14:33:38.604   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.604   315  6942 V AudioCache: memcpy(0xabf0c000, 0xb17ed000, 4096)
08-09 14:33:38.605   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.605   315  6942 V AudioCache: memcpy(0xabf0d000, 0xb17ed000, 4096)
08-09 14:33:38.606   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.606   315  6942 V AudioCache: memcpy(0xabf0e000, 0xb17ed000, 4096)
08-09 14:33:38.606  6919  6919 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-09 14:33:38.606   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.606   315  6942 V AudioCache: memcpy(0xabf0f000, 0xb17ed000, 4096)
08-09 14:33:38.607  6919  6919 D ProfileConfigQcom: Adding HeadsetService
08-09 14:33:38.607  6919  6919 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-09 14:33:38.607  6919  6919 D ProfileConfigQcom: Adding A2dpService
08-09 14:33:38.607  6919  6919 D ProfileConfigQcom: [BTUI] HidService is supported
08-09 14:33:38.607  6919  6919 D ProfileConfigQcom: Adding HidService
08-09 14:33:38.607   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.607   315  6942 V AudioCache: memcpy(0xabf10000, 0xb17ed000, 4096)
08-09 14:33:38.608  6919  6919 D ProfileConfigQcom: [BTUI] HealthService is supported
08-09 14:33:38.608  6919  6919 D ProfileConfigQcom: Adding HealthService
08-09 14:33:38.608   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.608   315  6942 V AudioCache: memcpy(0xabf11000, 0xb17ed000, 4096)
08-09 14:33:38.608  6919  6919 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-09 14:33:38.609   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.609   315  6942 V AudioCache: memcpy(0xabf12000, 0xb17ed000, 4096)
08-09 14:33:38.609   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.609   315  6942 V AudioCache: memcpy(0xabf13000, 0xb17ed000, 4096)
08-09 14:33:38.610  6919  6919 D ProfileConfigQcom: [BTUI] PanService is supported
08-09 14:33:38.610  6919  6919 D ProfileConfigQcom: Adding PanService
08-09 14:33:38.610  6919  6919 D ProfileConfigQcom: [BTUI] GattService is supported
08-09 14:33:38.610   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.610   315  6942 V AudioCache: memcpy(0xabf14000, 0xb17ed000, 4096)
08-09 14:33:38.610  6919  6919 D ProfileConfigQcom: Adding GattService
08-09 14:33:38.610  6919  6919 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-09 14:33:38.611  6919  6919 D ProfileConfigQcom: Adding BluetoothMapService
,08-09 14:33:38.611  6919  6919 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-09 14:33:38.611   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.611   315  6942 V AudioCache: memcpy(0xabf15000, 0xb17ed000, 4096)
08-09 14:33:38.612   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.612   315  6942 V AudioCache: memcpy(0xabf16000, 0xb17ed000, 4096)
08-09 14:33:38.612   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.613   315  6942 V AudioCache: memcpy(0xabf17000, 0xb17ed000, 4096)
08-09 14:33:38.613   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.613   315  6942 V AudioCache: memcpy(0xabf18000, 0xb17ed000, 4096)
08-09 14:33:38.614   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.614   315  6942 V AudioCache: memcpy(0xabf19000, 0xb17ed000, 4096)
08-09 14:33:38.614   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.614   315  6942 V AudioCache: memcpy(0xabf1a000, 0xb17ed000, 4096)
08-09 14:33:38.615   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.615   315  6942 V AudioCache: memcpy(0xabf1b000, 0xb17ed000, 4096)
08-09 14:33:38.616   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.616   315  6942 V AudioCache: memcpy(0xabf1c000, 0xb17ed000, 4096)
08-09 14:33:38.616  6919  6919 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-09 14:33:38.616   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.616   315  6942 V AudioCache: memcpy(0xabf1d000, 0xb17ed000, 4096)
08-09 14:33:38.617   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.617   315  6942 V AudioCache: memcpy(0xabf1e000, 0xb17ed000, 4096)
08-09 14:33:38.618   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.618   315  6942 V AudioCache: memcpy(0xabf1f000, 0xb17ed000, 4096)
08-09 14:33:38.618   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.618   315  6942 V AudioCache: memcpy(0xabf20000, 0xb17ed000, 4096)
08-09 14:33:38.619   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.619   315  6942 V AudioCache: memcpy(0xabf21000, 0xb17ed000, 4096)
08-09 14:33:38.620   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.620   315  6942 V AudioCache: memcpy(0xabf22000, 0xb17ed000, 4096)
08-09 14:33:38.620   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.620   315  6942 V AudioCache: memcpy(0xabf23000, 0xb17ed000, 4096)
08-09 14:33:38.621  6792  6792 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-09 14:33:38.621   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.621   315  6942 V AudioCache: memcpy(0xabf24000, 0xb17ed000, 4096)
08-09 14:33:38.622   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.622   315  6942 V AudioCache: memcpy(0xabf25000, 0xb17ed000, 4096)
08-09 14:33:38.622  6919  6919 V LGMDMManagerInternal: Create singleton instance
08-09 14:33:38.622   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.622   315  6942 V AudioCache: memcpy(0xabf26000, 0xb17ed000, 4096)
08-09 14:33:38.623   315  6942 V AudioCache: write(0xb17ed000, 4096)
,08-09 14:33:38.623   315  6942 V AudioCache: memcpy(0xabf27000, 0xb17ed000, 4096)
08-09 14:33:38.623   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.623   315  6942 V AudioCache: memcpy(0xabf28000, 0xb17ed000, 4096)
08-09 14:33:38.624   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.624   315  6942 V AudioCache: memcpy(0xabf29000, 0xb17ed000, 4096)
08-09 14:33:38.625   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.625   315  6942 V AudioCache: memcpy(0xabf2a000, 0xb17ed000, 4096)
08-09 14:33:38.625   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.625   315  6942 V AudioCache: memcpy(0xabf2b000, 0xb17ed000, 4096)
08-09 14:33:38.626   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.626   315  6942 V AudioCache: memcpy(0xabf2c000, 0xb17ed000, 4096)
08-09 14:33:38.626   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.626   315  6942 V AudioCache: memcpy(0xabf2d000, 0xb17ed000, 4096)
08-09 14:33:38.627   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.627   315  6942 V AudioCache: memcpy(0xabf2e000, 0xb17ed000, 4096)
08-09 14:33:38.628   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.628   315  6942 V AudioCache: memcpy(0xabf2f000, 0xb17ed000, 4096)
08-09 14:33:38.628   315  6942 V AudioCache: write(0xb17ed000, 4096)
08-09 14:33:38.628   315  6942 V AudioCache: memcpy(0xabf30000, 0xb17ed000, 4096)
08-09 14:33:38.628   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-09 14:33:38.628   315  6942 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-09 14:33:38.628   315  6942 V AwesomePlayer: postAudioEOS() 
08-09 14:33:38.628   315  6942 V AudioCache: write(0xb17ed000, 280)
08-09 14:33:38.628   315  6942 V AudioCache: memcpy(0xabf31000, 0xb17ed000, 280)
08-09 14:33:38.631   315  6939 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-09 14:33:38.631   315  6939 V AwesomePlayer: onStreamDone
08-09 14:33:38.631   315  6939 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-09 14:33:38.631   315  6939 V AudioCache: notify(0xb1432f00, 2, 0, 0)
08-09 14:33:38.631   315  6939 V AudioCache: playback complete
08-09 14:33:38.631   315  6939 V AwesomePlayer: pause_l() 
08-09 14:33:38.631   315  6939 V AudioCache: notify(0xb1432f00, 7, 0, 0)
08-09 14:33:38.631   315  6939 V AudioCache: ignored
08-09 14:33:38.631   315  6939 V AwesomePlayer: cancelPlayerEvents
08-09 14:33:38.631   315  2155 V AudioCache: wait - success
08-09 14:33:38.631   315  2155 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-09 14:33:38.631   315  6939 D AudioPlayer: Pause Playback at 1068125
08-09 14:33:38.631   315  2155 V AwesomePlayer: reset_l() 
08-09 14:33:38.631   315  2155 V AudioCache: notify(0xb1432f00, 8, 0, 0)
08-09 14:33:38.631   315  2155 V AudioCache: ignored
08-09 14:33:38.631   315  2155 V AwesomePlayer: cancelPlayerEvents
08-09 14:33:38.632   315  2155 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-09 14:33:38.632   315  2155 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-09 14:33:38.632   315  2155 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-09 14:33:38.632   315  2155 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-09 14:33:38.632   315  2155 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-09 14:33:38.632   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-09 14:33:38.632   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-09 14:33:38.632   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-09 14:33:38.632   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-09 14:33:38.632   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-09 14:33:38.633   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0x,b54f7970 on port 0
08-09 14:33:38.633   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-09 14:33:38.633   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
08-09 14:33:38.633   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-09 14:33:38.633   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7650 on port 0
08-09 14:33:38.633   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-09 14:33:38.633   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-09 14:33:38.633   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb000f1f0 on port 1
08-09 14:33:38.633   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-09 14:33:38.633   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
08-09 14:33:38.633   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-09 14:33:38.633   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
08-09 14:33:38.633   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-09 14:33:38.633   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
08-09 14:33:38.633   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-09 14:33:38.633   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-09 14:33:38.633   315  2155 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-09 14:33:38.633   315  2155 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-09 14:33:38.633   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-09 14:33:38.633   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-09 14:33:38.633   315  6941 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-09 14:33:38.633   315  2155 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-09 14:33:38.633   315  2155 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-09 14:33:38.634   315  2155 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-09 14:33:38.635   315  2155 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-09 14:33:38.635   315  2155 D AudioPlayer: AudioPlayer releasing audio source
08-09 14:33:38.635   315  2155 D AudioPlayer: AudioPlayer done releasing audio source
08-09 14:33:38.635   315  2155 V AwesomePlayer: reset_l() 
08-09 14:33:38.635   315  2155 V AwesomePlayer: cancelPlayerEvents
08-09 14:33:38.635   315  2155 V AwesomePlayer: ~AwesomePlayer call
08-09 14:33:38.635   315  2155 V AwesomePlayer: reset_l() 
08-09 14:33:38.635   315  2155 V AwesomePlayer: cancelPlayerEvents
08-09 14:33:38.635  6841  6938 V SoundPool: close(31)
08-09 14:33:38.636  6841  6938 V SoundPool: pointer = 0x9fea6000, size = 205080, sampleRate = 48000, numChannels = 2
,08-09 14:33:38.651  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-09 14:33:38.652  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-09 14:33:38.662  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7680
,08-09 14:33:38.689  6919  6919 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-09 14:33:38.692  6919  6919 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-09 14:33:38.692  6919  6919 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-09 14:33:38.692  6919  6919 V BluetoothSapReceiver: SapReceiver onReceive 
08-09 14:33:38.693  6919  6919 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:38.693  6919  6919 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-09 14:33:38.698  6858  6858 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-09 14:33:38.859  6603  6603 I UEI.SmartControl: Supports setup maps: true
,08-09 14:33:38.861  6603  6603 D UEI.SmartControl: QS start statue = true Error code = 0
08-09 14:33:38.862  6603  6603 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-09 14:33:38.862  6603  6603 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-09 14:33:38.862  6603  6603 I UEI.SmartControl: ### init IR Blaster...
08-09 14:33:38.865  6603  6603 D serial_port: Configuring serial port
08-09 14:33:38.866  6603  6603 E UEI.SmartControl: UEIBLaster setting for 616
08-09 14:33:38.866  6603  6603 I UEI.SmartControl: Setting serial record hearder size = 2
08-09 14:33:38.866  6603  6603 I UEI.SmartControl: configuring settings for MAXQ616
08-09 14:33:38.866  6603  6603 I UEI.SmartControl: Get version...
08-09 14:33:38.884  6603  6946 D UEI.SmartControl: serial port data available: 21
,08-09 14:33:38.911  6603  6603 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-09 14:33:38.911  6603  6603 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-09 14:33:38.911  6603  6603 I UEI.SmartControl: QS saving settings...
08-09 14:33:38.913  6603  6603 D UEI.SmartControl: IR Blaster version: 25672567
,08-09 14:33:38.930  6603  6946 D UEI.SmartControl: serial port data available: 4
,08-09 14:33:38.963  6603  6952 I UEI.SmartControl: Device manager: loading config....
,08-09 14:33:38.964  6603  6952 D UEI.SmartControl: ----------- loading internal config...
,08-09 14:33:38.965  6603  6603 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-09 14:33:38.969  6603  6603 E UEI.SmartControl: Services init done
08-09 14:33:38.969  6603  6603 D UEI.SmartControl: QS Service init finished
08-09 14:33:38.972  6603  6603 D UEI.SmartControl: QS Service version name: 2.1.91
08-09 14:33:38.972  6603  6603 D UEI.SmartControl: QS Service version code: 201091
08-09 14:33:38.973  6603  6603 D UEI.SmartControl: Service requested: Control
08-09 14:33:38.977  6603  6952 E UEI.SmartControl: Loading SETTINGS...
08-09 14:33:38.978  6603  6603 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-09 14:33:38.984  6603  6603 D UEI.SmartControl: Internal service binding...
08-09 14:33:38.984  6841  6841 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-09 14:33:38.986  6603  6618 I UEI.SmartControl: ------ IControl API: 11
08-09 14:33:38.986  6603  6618 D UEI.SmartControl: File observer start...
08-09 14:33:38.986  6603  6618 E UEI.SmartControl: IR Port is disabled: false
08-09 14:33:38.986  6603  6618 D UEI.SmartControl: Starting file observer...
08-09 14:33:38.988  6603  6618 I UEI.SmartControl: Registering callback...
08-09 14:33:38.989  6603  6619 I UEI.SmartControl: ------ IControl API: 19
08-09 14:33:38.991  6603  6952 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-09 14:33:38.991  6603  6619 I UEI.SmartControl: Registering Services Ready callback...
,08-09 14:33:39.002  6603  6951 I UEI.SmartControl: Notify AllClients services are ready: 0
08-09 14:33:39.003  6841  6856 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-09 14:33:39.003  6841  6936 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-09 14:33:39.004  6603  6951 D UEI.SmartControl: -----service ready thread exits
08-09 14:33:39.004  6841  6936 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-09 14:33:39.005  6841  6841 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-09 14:33:39.006  6841  6841 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-09 14:33:39.007  6603  6618 I UEI.SmartControl: ------ IControl API: 8
08-09 14:33:39.009  6841  6841 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-09 14:33:39.010  6841  6841 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-09 14:33:39.011  6841  6841 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-09 14:33:39.012  6841  6841 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,08-09 14:33:39.013  6841  6841 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-09 14:33:39.014  6841  6841 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-09 14:33:39.021  6841  6841 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-09 14:33:39.023  6841  6841 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-09 14:33:39.024  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-09 14:33:39.024  6841  6841 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-09 14:33:39.025  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-09 14:33:39.026  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-09 14:33:39.027  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-09 14:33:39.028  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-09 14:33:39.029  6841  6841 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470746019029]
08-09 14:33:39.031  6841  6841 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-09 14:33:39.034  1036  1889 I ActivityManager: Killing 6022:com.android.gallery3d/u0a27 (adj 15): empty #17
08-09 14:33:39.053  6841  6954 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-09 14:33:39.064  1036  1889 I ActivityManager: Killing 6483:com.lge.email/u0a23 (adj 15): empty #18
08-09 14:33:39.113  1036  2010 W libprocessgroup: failed to open /acct/uid_10027/pid_6022/cgroup.procs: No such file or directory
,08-09 14:33:39.116  1036  1921 W libprocessgroup: failed to open /acct/uid_10023/pid_6483/cgroup.procs: No such file or directory
08-09 14:33:39.124  6841  6841 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-09 14:33:39.125  6841  6841 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-09 14:33:39.126  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-09 14:33:39.127  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-09 14:33:39.129  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-09 14:33:39.130  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-09 14:33:39.131  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,08-09 14:33:39.149  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-09 14:33:39.933  1036  1051 D WifiServiceImplEx: setWifiEnabled: true pid=6669, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-09 14:33:39.935  1036  1051 D WifiService: setWifiEnabled: true pid=6669, uid=10118
,08-09 14:33:39.935  1036  1051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-09 14:33:39.966  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-09 14:33:39.966  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-09 14:33:39.966  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-09 14:33:39.970  1036  1524 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-09 14:33:39.970  1036  1524 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-09 14:33:39.972  1036  1524 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-09 14:33:39.972  1036  1524 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-09 14:33:39.973  1036  1524 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-09 14:33:39.973  1036  1524 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,08-09 14:33:39.973  1036  1524 I WifiUtil: Intf0MacAddress=C49A027FFB5D,
08-09 14:33:39.973  1036  1524 E WifiHW  : unknown target_country: EU , set to default,
,08-09 14:33:39.973  1036  1524 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
,08-09 14:33:39.973  1036  1524 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-09 14:33:39.973  1036  1524 I WifiUtil: gEnableBmps=1
,08-09 14:33:40.025  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,08-09 14:33:40.054  1036  1118 D Tethering: MasterInitialState.processMessage what=3
,08-09 14:33:40.065  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 14:33:40.069  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:40.072  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:40.074  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-09 14:33:40.083  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 14:33:40.088  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:40.088  1036  1098 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:40.090  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-09 14:33:40.093  6393  6425 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-09 14:33:40.104  5717  5717 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-09 14:33:40.113  5717  5717 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-09 14:33:40.132  2140  2140 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-09 14:33:40.164  1036  1098 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-09 14:33:40.193  1036  1871 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6962 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-09 14:33:40.210  1036  1098 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 14:33:40.210  1036  1098 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-09 14:33:40.292  6962  6962 I AppUp4:AppBoxCP: onCreate
08-09 14:33:40.293  6962  6962 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-09 14:33:40.303  6962  6962 I AppUp4:DB:  setFingerPrint start
,08-09 14:33:40.304  6962  6962 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-09 14:33:40.313  6962  6962 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-09 14:33:40.313  6962  6962 I AppUp4:DB:  SDK version = 21
08-09 14:33:40.313  6962  6962 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-09 14:33:40.315  6962  6962 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-09 14:33:40.316  6962  6962 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-09 14:33:40.317  6962  6962 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:40.319  6962  6962 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-09 14:33:40.319  6962  6962 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-09 14:33:40.328  6962  6962 I AppUp4:CustModeStarterReceiver: onReceive
,08-09 14:33:40.366  6962  6962 D LgDataFeature: LgDataFeature() Constructor: none
,08-09 14:33:40.366  6962  6962 D LgDataFeature: LgDataFeature() Constructor Done, null
08-09 14:33:40.376  6962  6962 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@35eda23f
08-09 14:33:40.376  6962  6962 D AppUp4:CustFacade: isCustomizationCompleted : false
08-09 14:33:40.376  6962  6962 D AppUp4:CustFacade: isPhone : true
08-09 14:33:40.376  6962  6962 D AppUp4:CustModeStarterReceiver: begin check event
08-09 14:33:40.377  6962  6962 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-09 14:33:40.377  6962  6962 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-09 14:33:40.378  6962  6993 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-09 14:33:40.378  6962  6993 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-09 14:33:40.378  6962  6993 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-09 14:33:40.379  1036  1975 I ActivityManager: Killing 6083:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-09 14:33:40.409  1036  1921 W libprocessgroup: failed to open /acct/uid_10080/pid_6083/cgroup.procs: No such file or directory
,08-09 14:33:40.410  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-09 14:33:40.411  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-09 14:33:40.415  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-09 14:33:40.420  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-09 14:33:40.427  4305  6998 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-09 14:33:40.432  4305  6999 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:40.432  4305  6999 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-09 14:33:40.500  1036  1956 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7000 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-09 14:33:40.631  7000  7000 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-09 14:33:40.632  7000  7000 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-09 14:33:40.634  7000  7000 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-09 14:33:40.634  7000  7000 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-09 14:33:40.736  7000  7000 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-09 14:33:40.761  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-09 14:33:40.761  1036  1118 D Tethering: InitialState.processMessage what=4
08-09 14:33:40.762  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-09 14:33:40.766   306   894 D SoftapController: Softap fwReload - Ok
08-09 14:33:40.766  7000  7000 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-09 14:33:40.771  1036  1524 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (794ms)
08-09 14:33:40.773   306   894 D CommandListener: Setting iface cfg
08-09 14:33:40.773   306   894 D CommandListener: Trying to bring down wlan0
08-09 14:33:40.773   306   894 D CommandListener: Clearing all IP addresses on wlan0
,08-09 14:33:40.781  1036  1524 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-09 14:33:40.775  7029  7029 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 14:33:40.775  7029  7029 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 14:33:40.808  7000  7000 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-09 14:33:40.809  7029  7029 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-09 14:33:40.844  7000  7000 D LgDataFeature: LgDataFeature() Constructor: none
08-09 14:33:40.845  7000  7000 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-09 14:33:40.858  7029  7029 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-09 14:33:40.858  7029  7029 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-09 14:33:40.881  1036  1524 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-09 14:33:40.881  1036  1524 E WifiStateMachine: useWiFiOffloading() : false
08-09 14:33:40.881  1036  1524 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-09 14:33:40.882  1036  1524 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-09 14:33:40.882  1036  1524 D WifiMonitor: connecting to supplicant
,08-09 14:33:40.886  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-09 14:33:40.887  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-09 14:33:40.889  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-09 14:33:40.890  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:40.891  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 14:33:40.955  7000  7000 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-09 14:33:40.983  7000  7000 I HubEmail: JNI_OnLoad()
,08-09 14:33:40.983  7000  7000 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-09 14:33:40.983  7000  7000 I HubEmail: registerNatives()
08-09 14:33:40.983  7000  7000 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-09 14:33:40.983  7000  7000 I HubEmail: registerNativeMethods()
08-09 14:33:40.983  7000  7000 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-09 14:33:40.984  7000  7000 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-09 14:33:40.984  7029  7029 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-09 14:33:41.004  6881  7040 W FormManager: Network not available. Please check & try again.
,08-09 14:33:41.005  7000  7038 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:41.008  3490  3490 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-09 14:33:41.008  3490  3490 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:41.008  3490  3490 I LgeMiscReceiver: networkInfo.isConnected() = false
08-09 14:33:41.023  7029  7029 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-09 14:33:41.030  1036  1524 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,08-09 14:33:41.030  7029  7029 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-09 14:33:41.031  7029  7029 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-09 14:33:41.031  1036  1524 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-09 14:33:41.031  1036  1524 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-09 14:33:41.031  1036  7043 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-09 14:33:41.031  1036  7043 D WifiMonitor: Dropping event because (p2p0) is stopped
08-09 14:33:41.031  1036  7043 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-09 14:33:41.031  1036  7043 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-09 14:33:41.032  1036  7043 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-09 14:33:41.032  1036  7043 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-09 14:33:41.032  1036  1524 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-09 14:33:41.032  1036  1524 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-09 14:33:41.032  1036  1524 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-09 14:33:41.033  1036  1524 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-09 14:33:41.033  1036  1524 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-09 14:33:41.033  1036  1524 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-09 14:33:41.034  1036  1524 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-09 14:33:41.034  1036  1524 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-09 14:33:41.071  1036  1561 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7044 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
08-09 14:33:41.074  1036  1524 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-09 14:33:41.074  1036  1524 E WifiStateMachine: useWiFiOffloading() : false
08-09 14:33:41.074  1036  1524 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-09 14:33:41.074  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:41.074  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:41.075  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:41.075  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:41.075  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-09 14:33:41.076  1036  1524 D WifiNative-wlan0: doBoolean: SET update_config 1
08-09 14:33:41.081  1926  1926 D WfdService: Waiting for WifiP2p enabling
08-09 14:33:41.082  1036  1524 D WifiNative-wlan0: SET update_config 1: returned true
08-09 14:33:41.082  1036  1524 D WifiConfigStore: Loading config and enabling all networks 
08-09 14:33:41.082  1036  1524 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-09 14:33:41.082  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-09 14:33:41.085  1036  1524 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-09 14:33:41.087  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:41.087  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:41.087  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:41.087  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:41.087  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 14:33:41.087  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 14:33:41.087  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:41.087  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:41.087  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 14:33:41.087  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:41.087  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-09 14:33:41.088  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-09 14:33:41.091  1036  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-09 14:33:41.092  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:41.092  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:41.092  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:41.092  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:41.092  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 14:33:41.092  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 14:33:41.092  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:41.092  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:41.092  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 14:33:41.092  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:41.092  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-09 14:33:41.095  6881  7041 V FormManager: Network unavailable.
08-09 14:33:41.098  1036  1524 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-09 14:33:41.107  6881  7041 V FormManager: Network unavailable.
08-09 14:33:41.109  1036  1524 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-09 14:33:41.109  1036  1524 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-09 14:33:41.111  1036  1524 D WifiStateMachine: enableVerboseLogging : level 2
08-09 14:33:41.111  1036  1524 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-09 14:33:41.111  1036  1524 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-09 14:33:41.111  1036  1524 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-09 14:33:41.112  1036  1524 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-09 14:33:41.112  1036  1524 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-09 14:33:41.112  1036  1524 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-09 14:33:41.112  1036  1524 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-09 14:33:41.113  1036  1524 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-09 14:33:41.113  1036  1524 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-09 14:33:41.114  1036  1524 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-09 14:33:41.114  1036  1524 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-09 14:33:41.114  1036  1524 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-09 14:33:41.114  1036  1524 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-09 14:33:41.115  1036  1524 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-09 14:33:41.116  1036  2010 I ActivityManager: Killing 6532:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-09 14:33:41.146  1036  1524 D WifiStateMachine: Setting OUI to DA-A1-19
08-09 14:33:41.146  1036  1524 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-09 14:33:41.146  1036  1524 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-09 14:33:41.146  1036  1524 D WifiNative-HAL: Setting external_sim to 1
08-09 14:33:41.147  1036  1524 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-09 14:33:41.147  1036  1524 D WifiNative-wlan0: SET external_sim 1: returned true
08-09 14:33:41.147  1036  1524 I WifiNative-HAL: startHal
08-09 14:33:41.147  1036  1524 D wifi    : setting scan oui 0xaf721300
08-09 14:33:41.147  1036  1524 D WifiStateMachine: Setting OUI to DA-A1-19
,08-09 14:33:41.147  1036  1524 I WifiNative-HAL: startHal
08-09 14:33:41.147  1036  1524 D wifi    : setting scan oui 0xaf721300
08-09 14:33:41.148  1036  1524 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-09 14:33:41.148  1036  1524 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-09 14:33:41.148  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-09 14:33:41.148  7029  7029 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-09 14:33:41.148  1036  1524 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-09 14:33:41.149  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-09 14:33:41.149  7029  7029 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-09 14:33:41.149  1036  1524 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-09 14:33:41.149  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-09 14:33:41.149  1036  1975 W libprocessgroup: failed to open /acct/uid_10061/pid_6532/cgroup.procs: No such file or directory
08-09 14:33:41.149  7029  7029 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-09 14:33:41.149  1036  1524 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-09 14:33:41.149  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-09 14:33:41.150  7029  7029 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-09 14:33:41.150  1036  1524 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-09 14:33:41.150  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-09 14:33:41.150  7029  7029 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-09 14:33:41.150  1036  1524 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-09 14:33:41.150  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-09 14:33:41.151  7029  7029 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-09 14:33:41.151  1036  1524 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-09 14:33:41.151  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-09 14:33:41.151  7029  7029 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-09 14:33:41.151  1036  1524 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-09 14:33:41.153  1036  1524 E WifiNative: : [129,356,674 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-09 14:33:41.153  1036  1524 D WifiNative-wlan0: doBoolean: RECONNECT
08-09 14:33:41.153  1036  1524 D WifiNative-wlan0: RECONNECT: returned true
08-09 14:33:41.153  1036  1524 D WifiNative-wlan0: doString: [STATUS]
08-09 14:33:41.153  1036  7043 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-09 14:33:41.153  1036  7043 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-09 14:33:41.154  1036  1524 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-09 14:33:41.154  1036  1524 D WifiNative-wlan0: doBoolean: SET ps 1
08-09 14:33:41.154  1926  1926 D WfdsService: Supplicant Connection state is changed : true
08-09 14:33:41.154  1926  2263 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-09 14:33:41.154  1926  2263 D WfdsService: Set the WFDS Monitor: true
08-09 14:33:41.154  1926  2263 D WfdsMonitor: WfdsMonitorThread create
08-09 14:33:41.154  1036  1524 D WifiNative-wlan0: SET ps 1: returned true
08-09 14:33:41.154  1926  2263 D WfdsMonitor: WFDS Monitor is created and started
08-09 14:33:41.154  1926  2263 D WfdsService: WiFi: Supplicant connection re-established
08-09 14:33:41.154  1036  1518 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:41.155  1036  1524 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATION,AL_MODE 1 0
08-09 14:33:41.155  1926  7061 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-09 14:33:41.155  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-09 14:33:41.155  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-09 14:33:41.156  1036  1542 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:41.156  1036  1542 I WifiNative-HAL: startHal
08-09 14:33:41.156  1036  1542 D wifi    : getting scan capabilities on interface[1] = 0xaf721300
08-09 14:33:41.156  1036  1542 D wifi    : failed to get capabilities : -3
08-09 14:33:41.156  1036  1542 E WifiScanningService: could not get scan capabilities
08-09 14:33:41.156  1036  1543 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:41.156  1926  7061 E CtrlSupplicant: Succeed to open control connection
08-09 14:33:41.156  1926  7061 E CtrlSupplicant: Succeed to open monitor connection
08-09 14:33:41.156   306   894 D CommandListener: Setting iface cfg
08-09 14:33:41.156   306   894 D CommandListener: Trying to bring up p2p0
08-09 14:33:41.156  1036  1524 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-09 14:33:41.156  1036  1518 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-09 14:33:41.156  1926  7061 D WfdsMonitor: Supplicant connection established
08-09 14:33:41.156  1036  1518 D LGWifiP2pService: P2pEnablingState
08-09 14:33:41.157  1036  1518 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:41.157  1036  1518 D LGWifiP2pService: P2p socket connection successful
08-09 14:33:41.157  1926  2263 D WfdsService: Connected to the supplicant for wfds
08-09 14:33:41.157  1036  1518 D LGWifiP2pService: P2pEnabledState
08-09 14:33:41.157  1036  1524 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-09 14:33:41.157  1036  1518 D LGWifiP2pService: sending p2p connection changed broadcast
08-09 14:33:41.157  1036  1524 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-09 14:33:41.157  1036  1518 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-09 14:33:41.158  1036  1518 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-09 14:33:41.158  1036  1518 D WifiNative-p2p0: doBoolean: SET device_name G3
08-09 14:33:41.158  1036  1518 D WifiNative-p2p0: SET device_name G3: returned true
08-09 14:33:41.158  1036  1518 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-09 14:33:41.158  1036  1518 D LGWifiP2pService: before postfix = G3
,08-09 14:33:41.158  1036  1518 D WifiServerServiceExt: postfix byte check : 2
08-09 14:33:41.158  1036  1518 D LGWifiP2pService: after postfix = G3
08-09 14:33:41.158  1036  1518 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-09 14:33:41.159  1036  1518 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-09 14:33:41.159  1036  1518 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-09 14:33:41.159  1036  1518 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-09 14:33:41.159  1036  1518 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-09 14:33:41.159  1036  1518 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
,08-09 14:33:41.159  1036  1518 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-09 14:33:41.160  1036  1518 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-09 14:33:41.160  1036  1518 D WifiNative-HAL: p2pGetDeviceAddress
08-09 14:33:41.160  1036  1518 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-09 14:33:41.160  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-09 14:33:41.160  1926  1926 D WfdsService: WifiP2pState is changed : true
,08-09 14:33:41.160  1036  1518 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-09 14:33:41.160  1036  1518 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-09 14:33:41.161  1926  2263 D WfdsService: Receive the WFDS_ENABLE Method
08-09 14:33:41.161  1926  2263 D WfdsService: Set the WFDS Monitor: true
08-09 14:33:41.161  1926  2263 D WfdsService: Connected to the supplicant for wfds
08-09 14:33:41.161  1926  2263 D WfdsJNI : doCommand: WFDS_SET TRUE
,08-09 14:33:41.161  7029  7029 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-09 14:33:41.161  1926  1926 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-09 14:33:41.161  1036  1518 D WifiNative-p2p0: P2P_FLUSH: returned true
08-09 14:33:41.161  1036  1518 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-09 14:33:41.161  1926  1926 D WfdsService: isConnected: false
,08-09 14:33:41.161  1036  1518 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-09 14:33:41.161  1036  1518 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-09 14:33:41.162  1036  1518 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-09 14:33:41.162  1036  1518 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-09 14:33:41.162  1926  2263 D WfdsService: selectPreferredScanChannel [36]
08-09 14:33:41.162  1926  2263 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
,08-09 14:33:41.163  1036  1524 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-09 14:33:41.163  1036  1524 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-09 14:33:41.164  1926  1926 I WfdStateTracker: handleP2pThisDeviceChanged
08-09 14:33:41.164  1036  1524 E WifiStateMachine:  DriverStartedState what:132106 1 0
,08-09 14:33:41.164  1926  1926 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-09 14:33:41.164  1036  1524 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-09 14:33:41.164  1926  1926 D WfdsService: Update P2p Interface State: 3
08-09 14:33:41.170  7029  7029 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-09 14:33:41.170  1036  1518 D WifiNative-p2p0: SAVE_CONFIG: returned true
,08-09 14:33:41.170  1036  1518 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-09 14:33:41.170  1036  1518 D LGWifiP2pService: InactiveState
08-09 14:33:41.170  1036  1518 D LGWifiP2pService: InactiveState{ when=-8ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:41.170  1036  1518 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:41.170  1036  1518 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-09 14:33:41.171  7029  7029 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-09 14:33:41.172  7029  7029 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ,
08-09 14:33:41.172  1926  7061 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-09 14:33:41.172  1036  1524 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-09 14:33:41.172  7029  7029 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ,
08-09 14:33:41.172  1036  1524 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-09 14:33:41.173  7029  7029 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-09 14:33:41.173  1926  7061 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-09 14:33:41.173  1036  1524 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-09 14:33:41.173  1036  1524 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-09 14:33:41.173  7029  7029 E wpa_supplicant: disconnect_rssi_lvl: -100
08-09 14:33:41.173  7029  7029 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 14:33:41.173  1926  7061 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-09 14:33:41.173  1036  1524 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-09 14:33:41.174  1036  1524 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-09 14:33:41.174  1036  7043 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
,08-09 14:33:41.174  1036  7043 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 14:33:41.174  1036  7043 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 14:33:41.174  1036  7043 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 14:33:41.174  1036  7043 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-09 14:33:41.174  1036  7043 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 14:33:41.174  1036  1524 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-09 14:33:41.174  1036  7043 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 14:33:41.174  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-09 14:33:41.174  1036  7043 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-09 14:33:41.174  1036  7043 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-09 14:33:41.174  1036  7043 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 14:33:41.174  1036  7043 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 14:33:41.174  1036  7043 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 14:33:41.176  1036  1518 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-09 14:33:41.176  1036  1518 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:41.176  1036  1518 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:41.176  1036  1518 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:41.176  1036  1518 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,08-09 14:33:41.176  1036  1518 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:41.177  7029  7029 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-09 14:33:41.177  1036  1518 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:41.177  7029  7029 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 14:33:41.177  1036  1518 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:41.177  1036  1518 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:41.177  1036  1518 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:41.177  1036  1518 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,08-09 14:33:41.177  1036  1518 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:41.178  1036  1518 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:41.178  7029  7029 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-09 14:33:41.178  7029  7029 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 14:33:41.178  1926  7061 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-09 14:33:41.178  7029  7029 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 14:33:41.178  1036  1036 E WifiServerServiceExt: No p2p device connected
08-09 14:33:41.178  1926  2263 W WfdsService: DefaultState - msg [9441285] is not handled
08-09 14:33:41.179  1926  7061 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-09 14:33:41.179  1036  7043 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
,08-09 14:33:41.179  1036  1524 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-09 14:33:41.179  1036  7043 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 14:33:41.179  1036  7043 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 14:33:41.179  1036  7043 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 14:33:41.179  1036  7043 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-09 14:33:41.179  1036  7043 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 14:33:41.179  1036  7043 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 14:33:41.179  1036  7043 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 14:33:41.180  1036  7043 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-09 14:33:41.180  1036  1524 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-09 14:33:41.180  1036  1524 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-09 14:33:41.180  1036  7043 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 14:33:41.180  1036  7043 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 14:33:41.180  1036  7043 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 14:33:41.181  1036  1524 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-09 14:33:41.181  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-09 14:33:41.181  1036  1518 D LGWifiP2pService: InactiveState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:41.181  7029  7029 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-09 14:33:41.181  1036  1518 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
,08-09 14:33:41.181  7029  7029 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-09 14:33:41.182  1036  7043 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-09 14:33:41.182  1036  7043 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-09 14:33:41.182  1036  1524 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-09 14:33:41.182  1036  7043 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-09 14:33:41.182  1036  1524 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-09 14:33:41.182  1036  7043 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-09 14:33:41.182  1036  1524 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-09 14:33:41.182  1036  1524 D WifiNative-wlan0: doBoolean: SCAN
08-09 14:33:41.183  1036  1524 D WifiNative-wlan0: SCAN: returned false
08-09 14:33:41.183  1036  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=129388  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-09 14:33:41.185  1036  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=129389  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-09 14:33:41.185  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:41.185  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:41.185  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-09 14:33:41.186  1036  1524 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-09 14:33:41.186  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 14:33:41.186  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 14:33:41.186  1036  1524 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-09 14:33:41.186  1036  1524 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-09 14:33:41.187  1036  1524 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-09 14:33:41.187  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:41.187  1036  1524 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-09 14:33:41.188  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 14:33:41.188  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-09 14:33:41.230  7044  7044 D LgDataFeature: LgDataFeature() Constructor: none
08-09 14:33:41.231  7044  7044 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-09 14:33:41.233  7044  7044 D PhoneMonitor: Register our PhoneStateListener
08-09 14:33:41.244  7044  7044 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-09 14:33:41.245  7044  7044 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-09 14:33:41.256  7044  7044 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-09 14:33:41.256  7044  7044 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-09 14:33:41.257  7044  7044 D TelephonyAutoProfiling: [parse] Load xml
08-09 14:33:41.259  7044  7044 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,08-09 14:33:41.259  7044  7044 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-09 14:33:41.259  7044  7044 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-09 14:33:41.259  7044  7044 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-09 14:33:41.259  7044  7044 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-09 14:33:41.259  7044  7044 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-09 14:33:41.259  7044  7044 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-09 14:33:41.259  7044  7044 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-09 14:33:41.259  7044  7044 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
,08-09 14:33:41.259  7044  7044 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-09 14:33:41.259  7044  7044 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-09 14:33:41.259  7044  7044 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-09 14:33:41.259  7044  7044 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-09 14:33:41.259  7044  7044 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-09 14:33:41.259  7044  7044 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-09 14:33:41.259  7044  7044 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-09 14:33:41.259  7044  7044 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-09 14:33:41.277  7044  7044 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-09 14:33:41.290  1036  1579 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7065 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-09 14:33:41.291  1036  1579 I ActivityManager: Killing 6113:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-09 14:33:41.342  1036  1997 W libprocessgroup: failed to open /acct/uid_10097/pid_6113/cgroup.procs: No such file or directory
,08-09 14:33:41.422  1036  1362 V AlarmManager: RTC_WAKEUP set : Alarm{375a127d type 0 when 1470746021355 android} when 1470746021355
08-09 14:33:41.423  1036  1362 V AlarmManager: ELAPSED_WAKEUP set : Alarm{caa2572 type 2 when 129624 com.google.android.gms} when 129624
,08-09 14:33:41.583  1036  7043 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-09 14:33:41.583  7029  7029 E wpa_supplicant: USIM:  scard_init function
08-09 14:33:41.583  1036  7043 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,08-09 14:33:41.584  1036  7043 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-09 14:33:41.584  1036  7043 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
,08-09 14:33:41.584  1036  7043 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-09 14:33:41.584  1036  1524 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
,08-09 14:33:41.585  1036  1524 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-09 14:33:41.585  1036  1524 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-09 14:33:41.586  1036  1524 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-09 14:33:41.586  1036  1524 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-09 14:33:41.586  7029  7029 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-09 14:33:41.589  1036  7043 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-09 14:33:41.589  1036  7043 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-09 14:33:41.619  1036  1997 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7089 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-09 14:33:41.624  1036  1997 I ActivityManager: Killing 6565:com.lge.eula/1000 (adj 15): empty #17
08-09 14:33:41.670  1036  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=129874  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-09 14:33:41.681  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:41.681  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:41.681  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-09 14:33:41.682  1036  1561 W libprocessgroup: failed to open /acct/uid_1000/pid_6565/cgroup.procs: No such file or directory
,08-09 14:33:41.685  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 14:33:41.685  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 14:33:41.689  1036  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=129885  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-09 14:33:41.690  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:41.690  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:41.690  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:41.691  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-09 14:33:41.692  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 14:33:41.692  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-09 14:33:41.693  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 14:33:41.693  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 14:33:41.694  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-09 14:33:41.700  7029  7029 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-09 14:33:41.703  1036  7043 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-09 14:33:41.704  1036  7043 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-09 14:33:41.704  1036  7043 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-09 14:33:41.704  1036  7043 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-09 14:33:41.704  1036  7043 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-09 14:33:41.704  1036  7043 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-09 14:33:41.705  1036  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=129910  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-09 14:33:41.706  1036  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=129911  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-09 14:33:41.708  1036  1524 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=129912
08-09 14:33:41.708  1036  1524 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=129913
08-09 14:33:41.709  1036  1524 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=129913
08-09 14:33:41.709  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=129914
08-09 14:33:41.709  1036  1524 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=129914
08-09 14:33:41.710  1036  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=129915  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-09 14:33:41.714  1036  7043 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-09 14:33:41.714  1036  7043 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-09 14:33:41.714  7029  7029 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-09 14:33:41.714  7029  7029 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-09 14:33:41.714  1036  7043 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-09 14:33:41.714  1036  7043 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-09 14:33:41.714  1036  7043 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-09 14:33:41.714  1036  7043 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-09 14:33:41.714  1036  7043 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-09 14:33:41.715  1036  7043 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-09 14:33:41.715  1036  7043 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-09 14:33:41.715  1036  7043 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-09 14:33:41.717  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 14:33:41.717  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 14:33:41.719  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:41.719  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:41.719  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-09 14:33:41.720  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-09 14:33:41.723  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-09 14:33:41.725  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:41.725  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:41.726  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-09 14:33:41.726  1036  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=129931  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-09 14:33:41.728  1036  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=129932  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-09 14:33:41.728  1036  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=129933  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-09 14:33:41.729  1036  1524 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=129934
08-09 14:33:41.729  1036  1524 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=129934
08-09 14:33:41.730  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 14:33:41.730  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-09 14:33:41.730  1036  1524 D WifiNative-wlan0: doString: [STATUS]
08-09 14:33:41.731  1036  7043 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-09 14:33:41.731  1036  7043 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-09 14:33:41.732  1036  1524 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-09 14:33:41.733  1036  1524 I WifiServiceExtension: setVHTCapabilityType  : false
08-09 14:33:41.740  1036  1524 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-09 14:33:41.740  1036  1524 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-09 14:33:41.742  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 14:33:41.742  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 14:33:41.745  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:41.752  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:41.752  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:41.752  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-09 14:33:41.757  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:41.757  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:41.758  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-09 14:33:41.760  1036  1524 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-09 14:33:41.760  1036  1524 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-09 14:33:41.760  1036  1524 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-09 14:33:41.760  1036  1530 D ConnectivityService: Got NetworkAgent Messenger
08-09 14:33:41.760  1036  1524 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-09 14:33:41.760  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-09 14:33:41.760  1036  1524 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-09 14:33:41.760  1036  1530 D ConnectivityService: NetworkAgent connected
08-09 14:33:41.764  1036  1524 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-09 14:33:41.764  1036  1524 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-09 14:33:41.764  1036  1524 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-09 14:33:41.765  1036  1524 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-09 14:33:41.765  1036  1524 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-09 14:33:41.766  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 14:33:41.766  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 14:33:41.768  1036  1524 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-09 14:33:41.768  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:41.769   306   894 D CommandListener: Setting iface cfg
08-09 14:33:41.771  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 14:33:41.771  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 14:33:41.772  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:41.802  1036  1561 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7119 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-09 14:33:41.803  1036  1561 I ActivityManager: Killing 6582:com.lge.bnr/1000 (adj 15): empty #17
,08-09 14:33:41.852  1036  1579 W libprocessgroup: failed to open /acct/uid_1000/pid_6582/cgroup.procs: No such file or directory
,08-09 14:33:41.858  1036  1524 E WifiStateMachine: Start Dhcp Watchdog 2
08-09 14:33:41.858  1036  7118 D DhcpStateMachine: StoppedState
08-09 14:33:41.858  1036  7118 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:41.858  1036  7118 D DhcpStateMachine: WaitBeforeStartState
08-09 14:33:41.859  1036  1524 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=130064  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-09 14:33:41.860  1036  1524 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=130064  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-09 14:33:41.860  1036  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=130065  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-09 14:33:41.861  1036  1524 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-09 14:33:41.862  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-09 14:33:41.863  1036  1524 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-09 14:33:41.863  1036  1524 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-09 14:33:41.864  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-09 14:33:41.864  1036  1524 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-09 14:33:41.865  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-09 14:33:41.865  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-09 14:33:41.867  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 14:33:41.867  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-09 14:33:41.868  1036  1524 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=130073  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-09 14:33:41.869  1036  1524 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=130073  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-09 14:33:41.869  1036  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=130074  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-09 14:33:41.871  1036  1524 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:84444] from screen [on:0 period:1867206639] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-09 14:33:41.873  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1867206640] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-09 14:33:41.873  1036  1524 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-09 14:33:41.877  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-09 14:33:41.879  1036  1530 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-09 14:33:41.880  1036  1524 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:41.881  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-09 14:33:41.881  1036  1524 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:41.881  7119  7119 I art     : Almond Protected OAT
08-09 14:33:41.882  1036  1524 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:41.882  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:41.883  1036  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:41.884  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-09 14:33:41.884  1036  1524 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=122,0,0
08-09 14:33:41.885  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=122,0,0
08-09 14:33:41.885  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-09 14:33:41.885  7029  7029 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-09 14:33:41.886  1036  1524 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-09 14:33:41.886  1036  1524 D WifiNative-wlan0: doBoolean: SET ps 0
08-09 14:33:41.886  1036  1524 D WifiNative-wlan0: SET ps 0: returned true
08-09 14:33:41.886  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-09 14:33:41.887  7029  7029 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-09 14:33:41.887  1036  1524 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-09 14:33:41.887  1036  1518 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@16b5a407 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:41.888  1036  1518 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@16b5a407 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:41.888  1036  7118 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:41.888  1036  7118 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-09 14:33:41.888  1036  1524 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-09 14:33:41.889  1036  1524 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-09 14:33:41.889  1036  1524 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-09 14:33:41.890   306   894 D CommandListener: Setting iface cfg
08-09 14:33:41.890   306   894 D CommandListener: Trying to bring up wlan0
08-09 14:33:41.891  1036  1524 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-09 14:33:41.893  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 14:33:41.893  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-09 14:33:41.894  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 14:33:41.894  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-09 14:33:41.894  1036  1524 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:41.895  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:41.895  1036  1524 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:41.896  1036  1524 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:41.896  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:41.897  1036  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:41.897  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-09 14:33:41.897  1036  1524 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-09 14:33:41.898  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-09 14:33:41.898  1036  1518 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:41.898  1036  1518 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:41.898  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-09 14:33:41.898  7029  7029 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-09 14:33:41.899  1036  1524 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-09 14:33:41.899  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-09 14:33:41.899  7029  7029 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-09 14:33:41.899  1036  1524 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-09 14:33:41.899  1036  1524 D WifiNative-wlan0: doBoolean: SET ps 1
08-09 14:33:41.917  1036  1524 D WifiNative-wlan0: SET ps 1: returned true
08-09 14:33:41.918  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-09 14:33:41.918  1036  1524 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-09 14:33:41.918  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-09 14:33:41.918  1036  1524 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-09 14:33:41.919  1036  1530 D ConnectivityService: ignoring duplicate network state non-change
08-09 14:33:41.921  7119  7119 D WeatherApplication: removeAccount
,08-09 14:33:41.923  7119  7119 D WeatherApplication: Account.length = 0
08-09 14:33:41.923  7119  7119 E WeatherApplication: OPERATOR:OPEN
08-09 14:33:41.923  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 14:33:41.923  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 14:33:41.924  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:41.924  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:41.924  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-09 14:33:41.925  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:41.927  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-09 14:33:41.928  1036  1524 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-09 14:33:41.928  1036  1530 D ConnectivityService: Adding iface wlan0 to network 101
08-09 14:33:41.942  7119  7119 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:33:41
,08-09 14:33:41.948  7119  7119 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-09 14:33:41.948  7119  7119 D Weather.Utils: 2 : All the weather widget is gone.
,08-09 14:33:41.951  7119  7119 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-09 14:33:41.954  7119  7119 D WeatherAncestor: connectivity changed - connection : true
08-09 14:33:41.955  7119  7119 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-09 14:33:41.966  1036  1530 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-09 14:33:41.966  1036  1530 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-09 14:33:41.968  1036  1530 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-09 14:33:41.969   306   894 E Netd    : netlink response contains error (File exists)
08-09 14:33:41.969  1036  1530 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-09 14:33:41.970  7119  7119 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-09 14:33:41.970  7119  7119 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-09 14:33:41.970  7119  7119 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-09 14:33:41.971  1036  1530 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-09 14:33:41.971  1036  1530 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-09 14:33:41.972  1036  1530 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-09 14:33:41.973  1036  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-09 14:33:41.973  1036  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-09 14:33:41.973  1036  1530 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-09 14:33:41.974  1036  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-09 14:33:41.974  1036  7116 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:41.974  1036  7116 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-09 14:33:41.974  1036  7116 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:41.974  1036  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-09 14:33:41.974  1036  7116 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-09 14:33:41.974  1036  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 14:33:41.974  1036  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-09 14:33:41.974  1036  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 14:33:41.974  1036  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-09 14:33:41.974  1036  1530 D ConnectivityService: currentScore = 0, newScore = 20
08-09 14:33:41.974  1036  1530 D ConnectivityService:    accepting network in place of null
08-09 14:33:41.975  1036  1530 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 14:33:41.975  1036  1524 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 14:33:41.975  1036  1524 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-09 14:33:41.975  1836  1836 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 14:33:41.976   306  7141 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-09 14:33:41.976  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW8,00 Specifier: <-1>]
08-09 14:33:41.976  1036  1518 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:41.976  1036  1518 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:41.976  1036  1518 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:41.977  1036  1530 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-09 14:33:41.977  1036  1530 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-09 14:33:41.977  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-09 14:33:41.979  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 14:33:41.979  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-09 14:33:41.981  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:41.981  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:41.981  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:41.981  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-09 14:33:41.983  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-09 14:33:41.985  1926  1926 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-09 14:33:41.986  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:41.987  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:41.987  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-09 14:33:41.987  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-09 14:33:41.991  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:41.991  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:41.991  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-09 14:33:41.992  1036  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:41.992  1036  1530 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-09 14:33:41.993  1036  1530 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-09 14:33:41.994  1036  1530 D ConnectivityService: validation of new default Network = false
08-09 14:33:41.994  1036  1530 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-09 14:33:41.994  1036  1530 D DSQN    : enableDataServiceNotify 
08-09 14:33:41.994  1036  1530 D DSQN    : start dsqn bin
08-09 14:33:41.998  7119  7119 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-09 14:33:41.998  7119  7119 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:33:41
08-09 14:33:41.998  1036  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-09 14:33:41.998  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 14:33:41.998  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 14:33:41.999  1036  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 14:33:41.985  7142  7142 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 14:33:41.999  1588  2058 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-09 14:33:41.985  7142  7142 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 14:33:42.003  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 14:33:42.004  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-09 14:33:42.004  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-09 14:33:42.006  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-09 14:33:42.006  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-09 14:33:42.006  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-09 14:33:42.006  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-09 14:33:42.011  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 14:33:42.011  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-09 14:33:42.011  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:42.018  1036  1524 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-09 14:33:42.018  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-09 14:33:42.018  1036  1524 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-09 14:33:42.019  1036  1524 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-09 14:33:42.019  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-09 14:33:42.020  7142  7142 E DSQN    : DSQN ssw
08-09 14:33:42.020  1036  1524 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-09 14:33:42.026   306  7141 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-09 14:33:42.041  1036  1890 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7146 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-09 14:33:42.042  1036  1890 I ActivityManager: Killing 2160:com.lge.music/u0a34 (adj 15): empty #17
,08-09 14:33:42.059   315  3988 V AudioFlinger: 2160 died, releasing its sessions
,08-09 14:33:42.059   315  3988 V AudioFlinger:  pid 1836 @ 0
08-09 14:33:42.059   315  3988 V AudioFlinger:  pid 3490 @ 1
08-09 14:33:42.059   315  3988 V AudioFlinger:  pid 3490 @ 2
08-09 14:33:42.062   306  7141 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-09 14:33:42.089  1036  7118 D DhcpStateMachine: DHCPV4 request on wlan0
,08-09 14:33:42.090  1036  7118 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-09 14:33:42.090  1036  7118 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-09 14:33:42.091   306   893 D LGDataListener: argv[0]=dsqncommand
08-09 14:33:42.091   306   893 D LGDataListener: argv[1]=wlan0
08-09 14:33:42.091   306   893 D LGDataListener: argv[2]=1
08-09 14:33:42.091   306   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-09 14:33:42.091  1036  1116 D DSQN    : DSQM DsqnNotification wlan0  1
08-09 14:33:42.091  1036  1116 D DSQN    : start to monitor internet connection
08-09 14:33:42.085  7166  7166 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 14:33:42.085  7166  7166 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 14:33:42.097  1036  2010 W libprocessgroup: failed to open /acct/uid_10034/pid_2160/cgroup.procs: No such file or directory
08-09 14:33:42.107  7166  7166 I dhcpcd  : version 5.5.6 starting
,08-09 14:33:42.110  7166  7166 E dhcpcd  : get_duid: m
08-09 14:33:42.110  7166  7166 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-09 14:33:42.110  7166  7166 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-09 14:33:42.118  1036  1517 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-09 14:33:42.120  1036  7116 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Aug 2016 12:33:42 GMT], X-Android-Received-Millis=[1470746022120], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470746022090]}
08-09 14:33:42.120  1036  7116 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-09 14:33:42.120  1036  7116 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-09 14:33:42.120  1036  1530 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-09 14:33:42.120  1036  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-09 14:33:42.120  1036  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-09 14:33:42.120  1036  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 14:33:42.120  1036  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-09 14:33:42.121  1036  1530 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-09 14:33:42.121  1036  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-09 14:33:42.121  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 14:33:42.121  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 14:33:42.121  1036  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 14:33:42.121  1036  1530 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 14:33:42.121  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-09 14:33:42.121  1036  1524 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 14:33:42.121  1036  1524 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-09 14:33:42.123  1836  1836 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 14:33:42.123  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-09 14:33:42.124  1588  2058 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-09 14:33:42.135  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-09 14:33:42.136  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:42.136  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-09 14:33:42.149  1801  7169 I CheckinService: active receiver: enabled
,08-09 14:33:42.160  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-09 14:33:42.161  1801  7169 I CheckinService: Preparing to send checkin request
,08-09 14:33:42.161  1801  7169 I EventLogService: Accumulating logs since 1470745949030
,08-09 14:33:42.161  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:42.161  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:42.176  7166  7166 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-09 14:33:42.176  7166  7166 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-09 14:33:42.176  7166  7166 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-09 14:33:42.176  7166  7166 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-09 14:33:42.176  7166  7166 D dhcpcd  : wlan0: sending REQUEST (xid 0xdbbf576c), next in 4.41 seconds
,08-09 14:33:42.195   278   396 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-09 14:33:42.195   278   396 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-09 14:33:42.195   278   396 W Vold    : Returning OperationFailed - no handler for errno 0
08-09 14:33:42.196  7146  7176 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-09 14:33:42.197   278   396 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-09 14:33:42.197   278   396 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-09 14:33:42.197   278   396 W Vold    : Returning OperationFailed - no handler for errno 0
08-09 14:33:42.197  7146  7176 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-09 14:33:42.202   278   396 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-09 14:33:42.202   278   396 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-09 14:33:42.202   278   396 W Vold    : Returning OperationFailed - no handler for errno 0
08-09 14:33:42.202  7146  7178 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-09 14:33:42.204   278   396 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-09 14:33:42.204   278   396 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-09 14:33:42.204   278   396 W Vold    : Returning OperationFailed - no handler for errno 0
08-09 14:33:42.204  7146  7178 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-09 14:33:42.209  7166  7166 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-09 14:33:42.212  1801  7169 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-09 14:33:42.230  7166  7166 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-09 14:33:42.230  7166  7166 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-09 14:33:42.231  7166  7166 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-09 14:33:42.232  7166  7166 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-09 14:33:42.232  7166  7166 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-09 14:33:42.233  7166  7166 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-09 14:33:42.233  7166  7166 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-09 14:33:42.233  7166  7166 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-09 14:33:42.337  1036  1561 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7192 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-09 14:33:42.409  7192  7192 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-09 14:33:42.409  7192  7192 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-09 14:33:42.432  7192  7192 I MultiDex: VM with version 2.1.0 has multidex support
08-09 14:33:42.432  7192  7192 I MultiDex: install
08-09 14:33:42.432  7192  7192 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-09 14:33:42.440  7192  7192 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-09 14:33:42.496  1036  7118 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-09 14:33:42.496  7146  7146 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-09 14:33:42.497  1036  7118 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-09 14:33:42.498  1036  7118 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-09 14:33:42.498  1036  7118 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-09 14:33:42.498  1036  7118 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-09 14:33:42.498  1036  7118 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-09 14:33:42.498  1036  7118 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-09 14:33:42.498  1036  7118 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
,08-09 14:33:42.498  1036  7118 D DhcpStateMachine: RunningState
08-09 14:33:42.504  7146  7146 I LibraryLoader: Loading: webviewchromium
08-09 14:33:42.507  7146  7146 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 723-726)
08-09 14:33:42.507  7146  7146 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-09 14:33:42.512  7146  7146 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d29de6}
08-09 14:33:42.513  7146  7146 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-09 14:33:42.513  7146  7146 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-09 14:33:42.522  7146  7146 I BrowserStartupController: Initializing chromium process, renderers=0
08-09 14:33:42.523  7146  7146 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-09 14:33:42.532  7146  7146 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-09 14:33:42.533  7146  7146 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-09 14:33:42.533  7146  7146 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,08-09 14:33:42.538   315  1372 V AudioPolicyService: registerClient() client 0xb00105c0, uid 10093
08-09 14:33:42.540  7146  7240 W AudioManagerAndroid: Requires BLUETOOTH permission
08-09 14:33:42.560  7146  7146 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-09 14:33:42.560  7146  7146 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-09 14:33:42.560  7146  7146 I Adreno-EGL: Build Date: 12/12/14 금
08-09 14:33:42.560  7146  7146 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-09 14:33:42.560  7146  7146 I Adreno-EGL: Remote Branch: 
08-09 14:33:42.560  7146  7146 I Adreno-EGL: Local Patches: 
08-09 14:33:42.560  7146  7146 I Adreno-EGL: Reconstruct Branch: 
,08-09 14:33:42.787  1036  1871 I art     : Explicit concurrent mark sweep GC freed 102894(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 2.371ms total 130.437ms
,08-09 14:33:42.788  7146  7146 I NSApplication: Starting up...
,08-09 14:33:42.791  7192  7215 D LgDataFeature: LgDataFeature() Constructor: none
08-09 14:33:42.792  7192  7215 D LgDataFeature: LgDataFeature() Constructor Done, null
08-09 14:33:42.837  1036  1921 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7256 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-09 14:33:42.837  1036  1921 I ActivityManager: Killing 6044:com.android.vending/u0a44 (adj 15): empty #17
,08-09 14:33:42.851   345   345 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 661us total 15.377ms,
08-09 14:33:42.862  1036  1524 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-09 14:33:42.862  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-09 14:33:42.863  1036  1524 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-09 14:33:42.863  1036  1524 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-09 14:33:42.863  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-09 14:33:42.864   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 251us total 12.068ms
,08-09 14:33:42.866  1036  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-09 14:33:42.866  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-09 14:33:42.866  1036  1530 D ConnectivityService: identical MTU - not setting
08-09 14:33:42.867  1036  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-09 14:33:42.867  1036  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-09 14:33:42.867  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 14:33:42.867  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 14:33:42.868  1036  1530 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 14:33:42.868  1588  2058 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-09 14:33:42.877   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 224us total 12.112ms
,08-09 14:33:42.999  1036  1530 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-09 14:33:43.024  1036  1871 W libprocessgroup: failed to open /acct/uid_10044/pid_6044/cgroup.procs: No such file or directory
,08-09 14:33:43.028  1036  2010 D WifiServiceImplEx: setWifiEnabled: false pid=6669, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-09 14:33:43.028  1036  2010 D WifiService: setWifiEnabled: false pid=6669, uid=10118
08-09 14:33:43.028  1036  2010 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-09 14:33:43.037  1036  1524 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-09 14:33:43.037  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
,08-09 14:33:43.037  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-09 14:33:43.038  1036  1524 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-09 14:33:43.038  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-09 14:33:43.038  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-09 14:33:43.038  1036  1524 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-09 14:33:43.038  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-09 14:33:43.038  1036  1524 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-09 14:33:43.039  1036  1524 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-09 14:33:43.039  1036  1524 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-09 14:33:43.040  1036  1524 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-09 14:33:43.040  1036  1524 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-09 14:33:43.045  7273  7273 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-09 14:33:43.047  1036  1524 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-09 14:33:43.047  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-09 14:33:43.047  1036  1518 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:43.047  1036  1518 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:43.047  7029  7029 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-09 14:33:43.047  1036  1524 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-09 14:33:43.048  1036  1524 D WifiNative-wlan0: doBoolean: SET ps 1
08-09 14:33:43.048  1036  1524 D WifiNative-wlan0: SET ps 1: returned true
08-09 14:33:43.048  1036  7118 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:43.051   306   894 D CommandListener: Clearing all IP addresses on wlan0
08-09 14:33:43.053  7256  7256 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-09 14:33:43.079  1036  1518 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:43.079  1036  1518 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:43.079  1036  1518 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@de634f5
08-09 14:33:43.080  1036  1524 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:43.080  1036  1518 D LGWifiP2pService: P2pDisablingState
08-09 14:33:43.080  1036  1518 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:43.080  1036  1518 D LGWifiP2pService: p2p socket connection lost
08-09 14:33:43.080  1036  1518 D LGWifiP2pService: P2pDisabledState
08-09 14:33:43.080  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:43.081  1036  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:43.081  1036  1524 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-09 14:33:43.081  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-09 14:33:43.082  7029  7029 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-09 14:33:43.082  1036  1524 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-09 14:33:43.082  1036  1524 D WifiNative-wlan0: doBoolean: SET ps 1
08-09 14:33:43.082  1036  1524 D WifiNative-wlan0: SET ps 1: returned true
08-09 14:33:43.083  1036  1518 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:43.083  1036  1518 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:43.083   306   894 D CommandListener: Clearing all IP addresses on wlan0
08-09 14:33:43.084  1036  1524 D WifiNative-p2p0: doBoolean: TERMINATE
08-09 14:33:43.084  1036  1524 D WifiNative-p2p0: TERMINATE: returned true
08-09 14:33:43.084  1036  1524 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-09 14:33:43.084  1036  1524 E WifiStateMachine: useWiFiOffloading() : false
08-09 14:33:43.084  1036  1524 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-09 14:33:43.085  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-09 14:33:43.085  1036  1530 D ConnectivityService: ignoring duplicate network state non-change
08-09 14:33:43.085  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-09 14:33:43.087  1036  1524 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-09 14:33:43.093  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 14:33:43.093  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 14:33:43.094  1926  1926 V WfdStateTracker: handleWifiStateChangedEvent: 0
,08-09 14:33:43.096  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-09 14:33:43.096  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:43.096  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:43.097  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-09 14:33:43.097  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-09 14:33:43.098  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:43.099  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:43.099  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:43.099  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-09 14:33:43.100  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-09 14:33:43.100  1036  1542 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:43.100  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 14:33:43.100  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 14:33:43.101  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-09 14:33:43.101  1036  1543 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:43.101  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:43.102  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-09 14:33:43.102  1926  1926 D WfdsService: WifiP2pState is changed : false
08-09 14:33:43.102  1926  2263 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-09 14:33:43.102  1926  2263 D WfdsService: Set the WFDS Monitor: false
08-09 14:33:43.103  1926  2263 D WfdsMonitor: WFDS Monitor is stopped
08-09 14:33:43.103  1926  2263 D WfdsService: STATE : WfdsDisabledState - enter
08-09 14:33:43.103  1926  7061 D CtrlSupplicant: Received on exit socket, terminate
08-09 14:33:43.103  1926  7061 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-09 14:33:43.103  1926  7061 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-09 14:33:43.103  1926  7061 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-09 14:33:43.103  1926  2269 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-09 14:33:43.103  1926  2263 W WfdsService: DefaultState - msg [9445378] is not handled
08-09 14:33:43.106  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-09 14:33:43.110  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-09 14:33:43.110  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:43.110  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-09 14:33:43.112  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-09 14:33:43.115  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-09 14:33:43.116  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 14:33:43.116  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-09 14:33:43.116  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:43.116  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:43.116  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:43.116  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:43.116  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 14:33:43.116  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 14:33:43.116  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:43.116  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:43.116  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 14:33:43.116  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:43.116  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 14:33:43.117  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:43.117  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:43.117  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:43.117  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:43.117  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 14:33:43.117  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 14:33:43.117  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:43.117  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:43.117  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 14:33:43.117  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:43.118  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 14:33:43.121  1036  1530 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-09 14:33:43.121  1036  1530 D DSQN    : disableDataServiceNotify
08-09 14:33:43.121  1036  1530 D DSQN    : stop dsqn bin
08-09 14:33:43.124  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: fa,lse, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-09 14:33:43.124  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 14:33:43.124  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-09 14:33:43.125  7273  7273 I dex2oat : dex2oat took 79.717ms (threads: 4)
08-09 14:33:43.126  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:43.128  1036  1530 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-09 14:33:43.128  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 14:33:43.128  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 14:33:43.129  1036  1530 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 14:33:43.129  1036  1530 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-09 14:33:43.129  1036  7116 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:43.129  1036  7116 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:43.129  1036  7116 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-09 14:33:43.129  1036  1530 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-09 14:33:43.129  1036  1530 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-09 14:33:43.129  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-09 14:33:43.130  1036  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:43.130  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-09 14:33:43.131  1588  2058 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-09 14:33:43.131  1036  1517 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-09 14:33:43.132  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-09 14:33:43.133  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-09 14:33:43.133  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-09 14:33:43.133  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-09 14:33:43.134  1036  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:43.134  1036  1530 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 14:33:43.134  1036  1530 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 14:33:43.134  1036  1517 V NetworkPolicy: [LG_RESTRICTED] !!!isConnec,ted  type  :1
08-09 14:33:43.134  1036  1524 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 14:33:43.134  1036  1524 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-09 14:33:43.135  1836  1836 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 14:33:43.135  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-09 14:33:43.137  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-09 14:33:43.137  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-09 14:33:43.137  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-09 14:33:43.137  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-09 14:33:43.137  1036  1530 D NetworkManagementService: Removing idletimer
08-09 14:33:43.138  1036  1530 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:43.140  7192  7215 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-09 14:33:43.140  7192  7215 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-09 14:33:43.140  7192  7215 I Adreno-EGL: Build Date: 12/12/14 금
08-09 14:33:43.140  7192  7215 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-09 14:33:43.140  7192  7215 I Adreno-EGL: Remote Branch: 
08-09 14:33:43.140  7192  7215 I Adreno-EGL: Local Patches: 
08-09 14:33:43.140  7192  7215 I Adreno-EGL: Reconstruct Branch: 
,08-09 14:33:43.156  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-09 14:33:43.157  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:43.157  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-09 14:33:43.170  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-09 14:33:43.170  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:43.171  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:43.181  7029  7029 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-09 14:33:43.181  7029  7029 I wpa_supplicant: monitor socket send errors count : 1
08-09 14:33:43.181  7029  7029 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1926-4\x00 that cannot receive messages
,08-09 14:33:43.183  1036  7043 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-09 14:33:43.183  1036  7043 D WifiMonitor: Dropping event because (p2p0) is stopped
08-09 14:33:43.203  7029  7029 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-09 14:33:43.203  1036  7043 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-09 14:33:43.203  1036  7043 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-09 14:33:43.203  1036  7043 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-09 14:33:43.203  1036  7043 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
,08-09 14:33:43.204  7029  7029 W wpa_supplicant: USIM:  scard_deinit function
08-09 14:33:43.204  1036  1524 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=131409
08-09 14:33:43.204  1036  7043 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-09 14:33:43.204  1036  7043 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-09 14:33:43.205  1036  1524 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=131410
08-09 14:33:43.206  1036  1118 D Tethering: InitialState.processMessage what=4
08-09 14:33:43.206  1036  1524 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=131410  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-09 14:33:43.207  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-09 14:33:43.207  1036  1524 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=131411  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-09 14:33:43.207  1036  1524 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-09 14:33:43.207  1036  1524 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-09 14:33:43.266  1036  7118 D DhcpStateMachine: StoppedState
08-09 14:33:43.266  1036  7118 D DhcpStateMachine: StoppedState{ when=-183ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-09 14:33:43.266  1036  1524 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-09 14:33:43.268  1036  1524 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-09 14:33:43.269  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-09 14:33:43.269  6393  6425 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-09 14:33:43.279  2140  2140 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-09 14:33:43.284  7192  7215 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-09 14:33:43.284  7192  7215 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-09 14:33:43.284  7192  7215 I Adreno-EGL: Build Date: 12/12/14 금
08-09 14:33:43.284  7192  7215 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-09 14:33:43.284  7192  7215 I Adreno-EGL: Remote Branch: 
08-09 14:33:43.284  7192  7215 I Adreno-EGL: Local Patches: 
08-09 14:33:43.284  7192  7215 I Adreno-EGL: Reconstruct Branch: 
08-09 14:33:43.292  6962  6962 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-09 14:33:43.292  6962  6962 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:43.292  6962  6962 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-09 14:33:43.292  6962  6962 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-09 14:33:43.294  6962  6962 I AppUp4:CustModeStarterReceiver: onReceive
,08-09 14:33:43.297  6962  6962 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@35eda23f
08-09 14:33:43.297  6962  6962 D AppUp4:CustFacade: isCustomizationCompleted : false
08-09 14:33:43.297  6962  6962 D AppUp4:CustFacade: isPhone : true
08-09 14:33:43.298  6962  6962 D AppUp4:CustModeStarterReceiver: begin check event
08-09 14:33:43.298  6962  6962 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-09 14:33:43.300  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:43.300  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-09 14:33:43.301  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-09 14:33:43.303  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-09 14:33:43.306  7000  7000 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-09 14:33:43.308  4305  7294 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-09 14:33:43.313  4305  7295 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:43.315  4305  7295 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-09 14:33:43.319  7000  7296 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-09 14:33:43.325  3490  3490 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-09 14:33:43.326  3490  3490 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:43.326  3490  3490 I LgeMiscReceiver: networkInfo.isConnected() = false
08-09 14:33:43.328  7044  7044 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-09 14:33:43.328  7044  7044 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-09 14:33:43.334  6881  7299 W FormManager: Network not available. Please check & try again.
,08-09 14:33:43.334  6881  7300 V FormManager: Network unavailable.
08-09 14:33:43.338  7119  7119 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:33:43
08-09 14:33:43.339  7192  7215 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-09 14:33:43.339  7192  7215 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-09 14:33:43.339  7192  7215 I Adreno-EGL: Build Date: 12/12/14 금
08-09 14:33:43.339  7192  7215 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-09 14:33:43.339  7192  7215 I Adreno-EGL: Remote Branch: 
08-09 14:33:43.339  7192  7215 I Adreno-EGL: Local Patches: 
08-09 14:33:43.339  7192  7215 I Adreno-EGL: Reconstruct Branch: 
08-09 14:33:43.341  6881  7300 V FormManager: Network unavailable.
08-09 14:33:43.341  7119  7119 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-09 14:33:43.341  7119  7119 D Weather.Utils: 2 : All the weather widget is gone.
08-09 14:33:43.342  7119  7119 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-09 14:33:43.342  7119  7119 D WeatherAncestor: connectivity changed - connection : true
,08-09 14:33:43.342  7119  7119 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@fcb8855
08-09 14:33:43.343  7119  7119 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-09 14:33:43.343  7119  7119 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-09 14:33:43.344  7119  7119 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-09 14:33:43.344  7119  7119 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-09 14:33:43.344  7119  7119 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:33:43
08-09 14:33:43.346  7029  7029 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-09 14:33:43.346  1036  7043 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-09 14:33:43.346  1036  7043 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-09 14:33:43.346  1036  7043 D WifiMonitor: Disconnecting from the supplicant, no more events
08-09 14:33:43.347  1036  1524 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
,08-09 14:33:43.378  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-09 14:33:43.378  6792  6792 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-09 14:33:43.379  6792  6792 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-09 14:33:43.379  6792  6792 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-09 14:33:43.379  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-09 14:33:43.380  6792  6792 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-09 14:33:43.380  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-09 14:33:43.380  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-09 14:33:43.380  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-09 14:33:43.380  6792  6792 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-09 14:33:43.380  6792  6792 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-09 14:33:43.387  6813  6813 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-09 14:33:43.390  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-09 14:33:43.397  6881  7305 W FormManager: Network not available. Please check & try again.
,08-09 14:33:43.397  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:33:43.404  6881  7306 V FormManager: Network unavailable.
,08-09 14:33:43.407  6881  7306 V FormManager: Network unavailable.
08-09 14:33:43.421  6813  6813 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-09 14:33:43.425  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-09 14:33:43.429  6881  7308 W FormManager: Network not available. Please check & try again.
08-09 14:33:43.429  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:33:43.440  6881  7309 V FormManager: Network unavailable.
08-09 14:33:43.444  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-09 14:33:43.444  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-09 14:33:43.445  6881  7309 V FormManager: Network unavailable.
08-09 14:33:43.446  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-09 14:33:43.447  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-09 14:33:43.449  1036  1524 D WifiOffDelayIfNotUsed: stopMonitoring
08-09 14:33:43.449  1036  1524 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-09 14:33:43.449  1036  1524 E WifiStateMachine: useWiFiOffloading() : false
08-09 14:33:43.449  1036  1524 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-09 14:33:43.450  1926  1926 D WfdsService: Supplicant Connection state is changed : false
08-09 14:33:43.450  1926  2263 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-09 14:33:43.450  1926  2263 D WfdsService: Set the WFDS Monitor: false
08-09 14:33:43.450  1926  2263 D WfdsMonitor: WFDS Monitor is stopped
08-09 14:33:43.450  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:43.452  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-09 14:33:43.454  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-09 14:33:43.454  1036  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-09 14:33:43.454  1036  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-09 14:33:43.455  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:43.455  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:43.455  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:43.455  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:43.455  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 14:33:43.455  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 14:33:43.455  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:43.455  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:43.455  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 14:33:43.456  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:43.456  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:43.456  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:43.456  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:43.456  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 14:33:43.456  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 14:33:43.456  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:43.456  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:43.456  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 14:33:43.457  2454  2454 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:43.457   306  7313 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-09 14:33:43.458  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-09 14:33:43.458  1801  7169 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,08-09 14:33:43.461  4305  7310 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-09 14:33:43.462  4305  7311 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-09 14:33:43.462  4305  7311 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-09 14:33:43.503  1036  1921 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7314 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-09 14:33:43.519  1801  7169 I CheckinService: active receiver: disabled
,08-09 14:33:43.601  7314  7314 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-09 14:33:43.602  7314  7314 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-09 14:33:43.611  7314  7314 V [BNRBootReceiver]: Boot Receiver Return
08-09 14:33:43.612  7314  7314 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-09 14:33:43.618  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-09 14:33:43.635  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 14:33:43.642  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:33:43.653  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 14:33:43.653  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-09 14:33:43.656  6841  6841 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-09 14:33:43.657  1036  2010 I ActivityManager: Killing 6773:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-09 14:33:43.660  1036  1524 E WifiStateMachine:  InitialState CMD_START_SCAN -2 -2 ic=1 proc(ms):1 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:1782] from screen [on:0 period:1867208428]
08-09 14:33:43.662  1036  1524 E WifiStateMachine:  DefaultState CMD_START_SCAN -2 -2 ic=1 proc(ms):3 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1867208429]
08-09 14:33:43.718  1036  1997 W libprocessgroup: failed to open /acct/uid_10037/pid_6773/cgroup.procs: No such file or directory
,08-09 14:33:43.725   306  7333 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-09 14:33:43.725  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-09 14:33:43.734  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-09 14:33:43.742  6792  6792 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-09 14:33:43.749  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-09 14:33:43.763  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 14:33:43.770  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-09 14:33:43.780  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 14:33:43.781  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-09 14:33:43.784  6841  6841 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-09 14:33:43.789  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 14:33:43.804  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 14:33:43.819  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:33:43.832  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 14:33:43.833  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 14:33:43.834  6841  6841 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-09 14:33:43.844  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 14:33:43.864  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 14:33:43.879  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-09 14:33:43.893  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-09 14:33:43.894  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-09 14:33:43.894  6841  6841 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-09 14:33:43.902  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 14:33:43.916  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 14:33:43.928  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:33:43.936  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 14:33:43.937  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-09 14:33:43.938  6841  6841 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-09 14:33:43.946  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 14:33:43.964  6603  6953 D UEI.SmartControl: Internal timer expired: 4
08-09 14:33:43.964  6603  6953 D UEI.SmartControl: unbind internal service
08-09 14:33:43.964  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 14:33:43.974  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:33:43.982  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 14:33:43.982  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 14:33:43.983  6841  6841 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-09 14:33:43.987  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-09 14:33:43.996  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 14:33:44.003  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:33:44.014  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 14:33:44.014  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 14:33:44.014  6841  6841 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-09 14:33:44.027  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.,
,08-09 14:33:44.043  6603  6947 D serial_port: close(fd = 24)
,08-09 14:33:44.048  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-09 14:33:44.054  6603  6947 I UEI.SmartControl: Serial port is closed.
,08-09 14:33:44.058  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:33:44.067  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-09 14:33:44.067  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-09 14:33:44.072  6841  6841 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-09 14:33:44.077  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 14:33:44.090  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 14:33:44.099  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:33:44.110  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-09 14:33:44.111  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-09 14:33:44.113  6841  6841 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-09 14:33:44.122  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 14:33:44.135  6813  6813 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-09 14:33:44.152  1036  1529 D WifiService: New client listening to asynchronous messages
,08-09 14:33:44.154  6813  6813 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-09 14:33:44.163  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 14:33:44.175  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-09 14:33:44.188  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-09 14:33:44.189  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-09 14:33:44.194  6841  6841 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-09 14:33:44.196  6841  6841 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-09 14:33:44.197  6841  6841 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-09 14:33:44.210  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-09 14:33:44.220  6813  6813 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-09 14:33:44.222  6813  6813 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-09 14:33:44.225  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 14:33:44.233  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:33:44.245  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 14:33:44.245  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 14:33:44.246  6841  6841 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-09 14:33:44.247  6841  6841 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-09 14:33:44.248  6841  6841 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-09 14:33:44.257  2140  2140 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-09 14:33:44.273  2140  2140 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-09 14:33:44.274  2140  2140 D c       : Getting all permits...
08-09 14:33:44.274  2140  2140 D a       : Opening database...
08-09 14:33:44.282  2140  2140 D a       : Opening database auth.proximity.permit_store...
,08-09 14:33:44.283  2140  2140 D a       : Closing database...
08-09 14:33:44.302  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-09 14:33:44.310  6813  6813 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-09 14:33:44.311  6813  6813 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-09 14:33:44.311  6813  6813 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-09 14:33:44.318  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 14:33:44.328  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:33:44.340  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-09 14:33:44.341  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 14:33:44.345  6841  6841 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-09 14:33:44.351  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 14:33:44.357  6813  6813 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-09 14:33:44.358  6813  6813 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-09 14:33:44.358  6813  6813 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-09 14:33:44.364  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-09 14:33:44.374  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-09 14:33:44.386  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 14:33:44.386  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-09 14:33:44.389  6841  6841 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-09 14:33:44.396  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 14:33:44.402  6813  6813 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-09 14:33:44.402  6813  6813 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-09 14:33:44.402  6813  6813 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-09 14:33:44.409  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 14:33:44.420  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:33:44.431  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 14:33:44.432  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-09 14:33:44.435  6841  6841 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-09 14:33:44.450  6813  6813 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-09 14:33:44.455  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-09 14:33:44.466  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:33:44.472  6881  7341 W FormManager: Network not available. Please check & try again.
08-09 14:33:44.481  6881  7342 V FormManager: Network unavailable.
,08-09 14:33:44.485  6881  7342 V FormManager: Network unavailable.
08-09 14:33:44.489  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-09 14:33:44.489  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-09 14:33:44.491  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-09 14:33:44.499  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-09 14:33:44.504  4305  7343 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-09 14:33:44.510  4305  7344 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-09 14:33:44.510  4305  7344 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-09 14:33:44.512  6813  6813 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-09 14:33:44.512  6813  6813 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-09 14:33:44.512  6813  6813 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-09 14:33:44.518  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-09 14:33:44.522  6881  7346 W FormManager: Network not available. Please check & try again.
08-09 14:33:44.524  6881  7347 V FormManager: Network unavailable.
,08-09 14:33:44.527  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:33:44.527  6881  7347 V FormManager: Network unavailable.
08-09 14:33:44.547  2140  2140 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-09 14:33:44.883  1036  1524 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1221] from screen [on:0 period:1867209651] gl rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-09 14:33:44.885  1036  1524 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1867209653] gl rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-09 14:33:44.994  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-09 14:33:45.008  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-09 14:33:45.019  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 14:33:45.023  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:45.026  1036  1098 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:45.029  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-09 14:33:45.030  6393  6425 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-09 14:33:45.040  5717  5717 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-09 14:33:45.059  2140  2140 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-09 14:33:45.077  6962  6962 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-09 14:33:45.077  6962  6962 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:45.077  6962  6962 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-09 14:33:45.077  6962  6962 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-09 14:33:45.083  6962  6962 I AppUp4:CustModeStarterReceiver: onReceive
08-09 14:33:45.087  6962  6962 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@35eda23f
08-09 14:33:45.087  6962  6962 D AppUp4:CustFacade: isCustomizationCompleted : false
08-09 14:33:45.087  6962  6962 D AppUp4:CustFacade: isPhone : true
08-09 14:33:45.088  6962  6962 D AppUp4:CustModeStarterReceiver: begin check event
08-09 14:33:45.088  6962  6962 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-09 14:33:45.094  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:45.094  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-09 14:33:45.096  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-09 14:33:45.102  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-09 14:33:45.109  7000  7000 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-09 14:33:45.131  4305  7356 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-09 14:33:45.139  7000  7355 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:45.147  4305  7357 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:45.148  4305  7357 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-09 14:33:45.161  1036  1098 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-09 14:33:45.170  6881  7358 W FormManager: Network not available. Please check & try again.
08-09 14:33:45.174  6881  7359 V FormManager: Network unavailable.
08-09 14:33:45.178  3490  3490 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-09 14:33:45.179  3490  3490 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:45.179  6881  7359 V FormManager: Network unavailable.
08-09 14:33:45.179  3490  3490 I LgeMiscReceiver: networkInfo.isConnected() = true
,08-09 14:33:45.179  3490  3490 D PhoneState: setPdpRejectCasuse : false
,08-09 14:33:45.182  7044  7044 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-09 14:33:45.182  7044  7044 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-09 14:33:45.195  7119  7119 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:33:45
,08-09 14:33:45.198  7119  7119 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-09 14:33:45.198  7119  7119 D Weather.Utils: 2 : All the weather widget is gone.
,08-09 14:33:45.199  7119  7119 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-09 14:33:45.199  7119  7119 D WeatherAncestor: connectivity changed - connection : true
,08-09 14:33:45.199  7119  7119 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@fcb8855
08-09 14:33:45.200  7119  7119 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-09 14:33:45.200  7119  7119 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-09 14:33:45.200  7119  7119 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-09 14:33:45.200  7119  7119 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-09 14:33:45.200  7119  7119 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:33:45
08-09 14:33:46.039  1036  2017 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 14:33:46.040  1036  2017 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-09 14:33:46.067  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-09 14:33:46.068  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-09 14:33:46.068  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-09 14:33:46.071  1036  1118 D BluetoothManagerService: Message: 1
08-09 14:33:46.071  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-09 14:33:46.101  1036  1118 D BluetoothManagerService: Message: 20
08-09 14:33:46.101  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3cd729f4:true
,08-09 14:33:46.104  6919  6919 D BluetoothAdapterState: make
08-09 14:33:46.109  6919  6919 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-09 14:33:46.109  6919  6919 I bluedroid-qcom: init
08-09 14:33:46.111  6919  7387 I BluetoothAdapterState: Entering OffState
08-09 14:33:46.111  6919  6919 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-09 14:33:46.112  6919  6919 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-09 14:33:46.112  6919  6919 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-09 14:33:46.112  6919  6919 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-09 14:33:46.112  6919  6919 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-09 14:33:46.114  6919  6919 I bluedroid-qcom: get_profile_interface socket
08-09 14:33:46.114  6919  6919 I bluedroid-qcom: get_profile_interface map_client
,08-09 14:33:46.118  6919  7391 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-09 14:33:46.115  7390  7390 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 14:33:46.115  7390  7390 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 14:33:46.129  7390  7390 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-09 14:33:46.129  7390  7390 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-09 14:33:46.129  7390  7390 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-09 14:33:46.133  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:46.136  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-09 14:33:46.136  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:46.136  1036  1098 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:46.141  7390  7390 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-09 14:33:46.144  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 14:33:46.148  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:46.149  7390  7390 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-09 14:33:46.149  7390  7390 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-09 14:33:46.157  1036  1118 D Tethering: MasterInitialState.processMessage what=3
,08-09 14:33:46.162  6919  7391 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-09 14:33:46.169  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 14:33:46.173  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:46.176  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-09 14:33:46.176  1036  1118 D BluetoothManagerService: Message: 40
08-09 14:33:46.176  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-09 14:33:46.177  6919  6935 I bluedroid-qcom: config_hci_snoop_log
08-09 14:33:46.178  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-09 14:33:46.178  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-09 14:33:46.183  6919  7391 D BluetoothAdapterProperties: Name is: G3
,08-09 14:33:46.187  6919  7387 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-09 14:33:46.187  6919  7387 D BluetoothAdapterProperties: Setting state to 11
08-09 14:33:46.187  6919  7387 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-09 14:33:46.189  6919  7387 I LGBluetoothServiceJni: classInitNative: succeeds
08-09 14:33:46.200  6919  7387 D BluetoothBondStateMachine: make
08-09 14:33:46.205  1036  1118 D BluetoothManagerService: Message: 60
,08-09 14:33:46.205  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-09 14:33:46.205  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-09 14:33:46.208  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-09 14:33:46.208  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
,08-09 14:33:46.213  6919  7387 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcb8855
08-09 14:33:46.213  6919  7387 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-09 14:33:46.213  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-09 14:33:46.213  6919  7387 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcb8855
08-09 14:33:46.213  6919  7387 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-09 14:33:46.214  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:46.215  6919  7387 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-09 14:33:46.216  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-09 14:33:46.216  6919  7405 I BluetoothBondStateMachine: StableState(): Entering Off State
08-09 14:33:46.216  6792  6792 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-09 14:33:46.220  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:46.221  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 14:33:46.222  6393  6425 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-09 14:33:46.225  6919  7387 E BluetoothAdapterService: File transfer profiles supported!!
08-09 14:33:46.227  5717  5717 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-09 14:33:46.233  1036  1098 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-09 14:33:46.240  6919  6919 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-09 14:33:46.242  6919  6919 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:46.242  6919  6919 V BluetoothPbapReceiver: ***********state = 11
08-09 14:33:46.243  5717  5717 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-09 14:33:46.244  6919  7387 E BluetoothAdapterService: File transfer profiles supported!!
08-09 14:33:46.247  6919  6919 D HeadsetService: Received start request. Starting profile...
,08-09 14:33:46.247  6919  6919 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-09 14:33:46.248  6919  6919 D LGBluetoothHfpAdapter: Version 1.6
08-09 14:33:46.251  6919  6919 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-09 14:33:46.254  6919  6919 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-09 14:33:46.254  6919  6919 D HeadsetStateMachine: make
08-09 14:33:46.257  2140  2140 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-09 14:33:46.259  1036  1098 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 14:33:46.259  1036  1098 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-09 14:33:46.262  6919  7387 E BluetoothAdapterService: File transfer profiles supported!!
08-09 14:33:46.290  6919  6919 D LgDataFeature: LgDataFeature() Constructor: none
08-09 14:33:46.290  6919  6919 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-09 14:33:46.304  1036  1890 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7412 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-09 14:33:46.312  6919  6919 D HeadsetStateMachine: max_hf_connections = 1
08-09 14:33:46.312  6919  6919 I bluedroid-qcom: get_profile_interface handsfree
08-09 14:33:46.313  6919  6919 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-09 14:33:46.314  6919  7387 E BluetoothAdapterService: File transfer profiles supported!!
,08-09 14:33:46.315   315  2155 V AudioPolicyService: registerClient() client 0xb0010580, uid 1002
08-09 14:33:46.315   315  3988 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
,08-09 14:33:46.315   315  3988 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-09 14:33:46.315   315  3988 V AudioPolicyManagerEx: getOutput() returns output 2
08-09 14:33:46.315  6919  6919 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-09 14:33:46.316   315  1372 V AudioFlinger: registerClient() client 0xb5581610, pid 6919
08-09 14:33:46.316   315  1367 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-09 14:33:46.316  6919  6919 V ToneGenerator: Create Track: 0xb4928080
08-09 14:33:46.316   315  1367 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-09 14:33:46.316  6919  6919 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-09 14:33:46.316  6919  6919 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-09 14:33:46.316   315   315 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-09 14:33:46.317   315   315 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
,08-09 14:33:46.317  1588  2086 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-09 14:33:46.317   315   315 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-09 14:33:46.317  1588  2086 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-09 14:33:46.317   315   315 V AudioPolicyManagerEx: getOutput() returns output 2
08-09 14:33:46.317  1836  1851 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-09 14:33:46.317  1836  1851 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-09 14:33:46.318  6919  6919 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-09 14:33:46.319  6919  6935 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-09 14:33:46.319  6919  6935 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-09 14:33:46.319   315  1368 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-09 14:33:46.319   315  1368 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-09 14:33:46.319   315  2155 I AudioFlinger: isAudioPlaybackHookOn() false
08-09 14:33:46.319  6919  6935 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-09 14:33:46.319  6919  6935 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-09 14:33:46.320  1836  1851 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-09 14:33:46.320  1836  1851 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-09 14:33:46.320  3490  3507 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-09 14:33:46.320  3490  3507 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-09 14:33:46.320  3490  3507 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-09 14:33:46.320  3490  3507 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-09 14:33:46.320  1036  2017 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-09 14:33:46.320  1036  2017 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-09 14:33:46.321  1588  1613 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-09 14:33:46.321  1588  1613 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-09 14:33:46.321  1036  2017 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-09 14:33:46.321  1036  2017 V AudioSystem: ioConfigChanged() opening already existing output! 4
,08-09 14:33:46.322   315  2155 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-09 14:33:46.322   315  2155 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-09 14:33:46.322   315  2155 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-09 14:33:46.322   315  2155 V AudioPolicyManagerEx: getOutput() returns output 2
08-09 14:33:46.322  6919  6919 V AudioSystem: getLatency() output 2, latency 50
08-09 14:33:46.322  6919  6919 V AudioSystem: getFrameCount() output 2, frameCount 960
08-09 14:33:46.322  6919  6919 V AudioTrack: createTrack_l() output 2 afLatency 50
08-09 14:33:46.322  2140  2140 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:46.323   315   315 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-09 14:33:46.323   315   315 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-09 14:33:46.323   315   315 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-09 14:33:46.323   315   315 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-09 14:33:46.323   315   315 V AudioFlinger: createTrack() lSessionId: 22
08-09 14:33:46.326  6919  6919 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-09 14:33:46.326   315   315 V AudioFlinger: acquiring 22 from 6919, for 6919
08-09 14:33:46.326   315   315 V AudioFlinger:  added new entry for 22
08-09 14:33:46.328  6919  6919 V ToneGenerator: ToneGenerator INIT OK, time: 134548
08-09 14:33:46.328  6919  6919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcb8855
08-09 14:33:46.329  6919  7411 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-09 14:33:46.329  6919  7411 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-09 14:33:46.330  6919  7411 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-09 14:33:46.330  6919  7411 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-09 14:33:46.331   315  1372 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6919
08-09 14:33:46.331  6919  6919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcb8855
08-09 14:33:46.331   315  1372 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-09 14:33:46.331   315  1372 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-09 14:33:46.331   315  1372 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-09 14:33:46.331   315  1372 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-09 14:33:46.331   315  1372 V voice   : voice_set_parameters: exit with code(0)
08-09 14:33:46.331   315  1372 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-09 14:33:46.331   315  1372 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-09 14:33:46.331   315  1372 V msm8974_platform: platform_set_parameters: exit with code(0)
08-09 14:33:46.331   315  1372 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-09 14:33:46.331   315  1372 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-09 14:33:46.331   315  1372 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-09 14:33:46.331  6919  7411 V ToneGenerator: ToneGenerator destructor
08-09 14:33:46.331  6919  7411 V ToneGenerator: stopTone
08-09 14:33:46.331  6919  7411 V ToneGenerator: Delete Track: 0xb4928080
08-09 14:33:46.333  6919  7387 E BluetoothAdapterService: File transfer profiles supported!!
08-09 14:33:46.333  6919  6919 D A2dpService: Received start request. Starting profile...
08-09 ,14:33:46.334  6919  6919 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-09 14:33:46.334  6919  7411 V AudioTrack: ~AudioTrack, releasing session id from 6919 on behalf of 6919
08-09 14:33:46.334   315  1373 V AudioPolicyService: AudioCommandThread() adding release output 2
08-09 14:33:46.334   315  3988 V AudioFlinger: releasing 22 from 6919 for 6919
08-09 14:33:46.334   315  3988 V AudioFlinger:  decremented refcount to 0
08-09 14:33:46.334   315  1373 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-09 14:33:46.334   315  3988 V AudioFlinger: purging stale effects
08-09 14:33:46.334   315  1373 V AudioFlinger: PlaybackThread::Track destructor
08-09 14:33:46.334   315  1270 V AudioPolicyService: AudioCommandThread() waking up
08-09 14:33:46.334   315  1373 V AudioFlinger: removeClient_l() pid 6919, calling pid 315
08-09 14:33:46.335   315  1270 V AudioPolicyService: AudioCommandThread() processing release output 2
08-09 14:33:46.335  6919  6919 V Avrcp   : make
08-09 14:33:46.335   315  1270 V AudioPolicyManager: releaseOutput() 2
08-09 14:33:46.335   315  1270 V AudioPolicyService: AudioCommandThread() going to sleep
08-09 14:33:46.335  6919  6919 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-09 14:33:46.335  6919  6919 I bluedroid-qcom: get_profile_interface avrcp
,08-09 14:33:46.339  6962  6962 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-09 14:33:46.340  6962  6962 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:46.340  6962  6962 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-09 14:33:46.340  6962  6962 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-09 14:33:46.342  6919  7387 E BluetoothAdapterService: File transfer profiles supported!!
08-09 14:33:46.342  6962  6962 I AppUp4:CustModeStarterReceiver: onReceive
08-09 14:33:46.346  6919  6919 V AudioManager: registerRemoteController: size of Media player list: 0
08-09 14:33:46.346  6919  7387 E BluetoothAdapterService: File transfer profiles supported!!
08-09 14:33:46.348  6919  6919 E AudioManager: No RCC entry present to update
08-09 14:33:46.348  6919  6919 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-09 14:33:46.352  6919  6919 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-09 14:33:46.353  6919  6919 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-09 14:33:46.353  6919  6919 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-09 14:33:46.357  6919  6919 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-09 14:33:46.358  6919  7387 V LGMDMManager: Create singleton instance
08-09 14:33:46.361  6919  7387 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-09 14:33:46.361  6962  6962 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@35eda23f
08-09 14:33:46.361  6962  6962 D AppUp4:CustFacade: isCustomizationCompleted : false
08-09 14:33:46.361  6962  6962 D AppUp4:CustFacade: isPhone : true
,08-09 14:33:46.393  6962  6962 D AppUp4:CustModeStarterReceiver: begin check event
,08-09 14:33:46.394  6962  6962 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-09 14:33:46.397  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:46.398  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-09 14:33:46.399  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-09 14:33:46.401  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-09 14:33:46.406  4305  7433 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-09 14:33:46.407  7000  7000 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-09 14:33:46.417  4305  7434 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:46.417  4305  7434 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-09 14:33:46.435  7000  7435 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-09 14:33:46.437  3490  3490 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-09 14:33:46.437  3490  3490 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:46.437  3490  3490 I LgeMiscReceiver: networkInfo.isConnected() = false
08-09 14:33:46.441  7044  7044 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-09 14:33:46.441  7044  7044 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-09 14:33:46.444  1036  1579 V SIM_STK : Menu title from STK is T-Mobile
08-09 14:33:46.444  1036  1579 V SIM_STK : Menu title from STK is T-Mobile
08-09 14:33:46.454  6881  7438 V FormManager: Network unavailable.
08-09 14:33:46.455  7412  7412 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-09 14:33:46.455  7412  7412 W LG Account v2.2: No ProfileInfo entries
08-09 14:33:46.455  7412  7412 I LG Account v2.2: isEnabled: false
08-09 14:33:46.455  7412  7412 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-09 14:33:46.455  7412  7412 I Feature : [Lifetracker]Country: EU
08-09 14:33:46.455  7412  7412 I Feature : [Lifetracker]Operator: OPEN
08-09 14:33:46.455  7412  7412 I Feature : [Lifetracker]Ranking support: false
08-09 14:33:46.455  7412  7412 I Feature : [Lifetracker]Comfort support: false
08-09 14:33:46.455  7412  7412 I Feature : [Lifetracker]Accessory: true
08-09 14:33:46.455  7412  7412 I Feature : [Lifetracker]Health device: true
08-09 14:33:46.455  7412  7412 I Feature : [Lifetracker]Extra Pedometer: false
08-09 14:33:46.455  7412  7412 I Feature : [Lifetracker]Blood glucose device: false
08-09 14:33:46.455  7412  7412 I Feature : [Lifetracker]Device Number: 3
08-09 14:33:46.456  6881  7437 W FormManager: Network not available. Please check & try again.
,08-09 14:33:46.457  7119  7119 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:33:46
,08-09 14:33:46.458  7119  7119 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-09 14:33:46.458  7119  7119 D Weather.Utils: 2 : All the weather widget is gone.
08-09 14:33:46.458  7119  7119 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-09 14:33:46.459  7119  7119 D WeatherAncestor: connectivity changed - connection : true
08-09 14:33:46.459  7119  7119 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@fcb8855
08-09 14:33:46.459  7119  7119 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-09 14:33:46.460  7119  7119 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-09 14:33:46.460  7119  7119 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-09 14:33:46.460  7119  7119 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-09 14:33:46.460  7119  7119 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:33:46
08-09 14:33:46.464  6792  6792 D BluetoothPermissionRequest: onReceive
08-09 14:33:46.465  6881  7438 V FormManager: Network unavailable.
,08-09 14:33:46.471  6792  6792 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-09 14:33:46.481  6393  6393 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-09 14:33:46.482  6393  6425 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-09 14:33:46.494  2140  2140 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-09 14:33:46.504  6962  6962 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-09 14:33:46.504  6962  6962 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:46.504  6962  6962 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-09 14:33:46.504  6962  6962 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-09 14:33:46.506  6962  6962 I AppUp4:CustModeStarterReceiver: onReceive
,08-09 14:33:46.510  6962  6962 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@35eda23f
08-09 14:33:46.510  6962  6962 D AppUp4:CustFacade: isCustomizationCompleted : false
08-09 14:33:46.510  6962  6962 D AppUp4:CustFacade: isPhone : true
08-09 14:33:46.510  6962  6962 D AppUp4:CustModeStarterReceiver: begin check event
08-09 14:33:46.510  6962  6962 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-09 14:33:46.513  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:46.514  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-09 14:33:46.515  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-09 14:33:46.517  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-09 14:33:46.520  4305  7442 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-09 14:33:46.523  1036  1997 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-09 14:33:46.524  7000  7000 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-09 14:33:46.526  4305  7443 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:46.526  4305  7443 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-09 14:33:46.529  6919  6919 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-09 14:33:46.533  6919  6919 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-09 14:33:46.533  6919  6919 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,08-09 14:33:46.534  6919  6919 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-09 14:33:46.534  6919  6919 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-09 14:33:46.534  6919  6919 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-09 14:33:46.534  6919  6919 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-09 14:33:46.534  6919  6919 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-09 14:33:46.534  6919  6919 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-09 14:33:46.534  6919  6919 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-09 14:33:46.534  6919  6919 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-09 14:33:46.534  6919  6919 I BluetoothA2dpServiceJni: classInitNative
08-09 14:33:46.534  6919  6919 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-09 14:33:46.534  6919  6919 D A2dpStateMachine: make
08-09 14:33:46.536  6919  6919 I bluedroid-qcom: get_profile_interface a2dp
08-09 14:33:46.536  6919  7446 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-09 14:33:46.539  6919  6919 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-09 14:33:46.539  6919  6919 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-09 14:33:46.541  6919  6919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcb8855
08-09 14:33:46.541  6919  7444 D A2dpStateMachine: Enter Disconnected: -2
,08-09 14:33:46.542  6919  6919 I BluetoothHidServiceJni: classInitNative: succeeds
08-09 14:33:46.545  6919  6919 D HidService: Received start request. Starting profile...
08-09 14:33:46.545  6919  6919 I bluedroid-qcom: get_profile_interface hidhost
08-09 14:33:46.545  6919  6919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcb8855
08-09 14:33:46.545  6919  6919 D HeadsetStateMachine: Proxy object connected
08-09 14:33:46.545  6919  6919 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-09 14:33:46.545  3490  3490 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-09 14:33:46.545  3490  3490 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:46.545  6919  6919 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-09 14:33:46.546  3490  3490 I LgeMiscReceiver: networkInfo.isConnected() = false
08-09 14:33:46.547  7000  7447 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:46.547  6881  7449 W FormManager: Network not available. Please check & try again.
08-09 14:33:46.548  6919  6919 I BluetoothHealthServiceJni: classInitNative: succeeds
08-09 14:33:46.550  6919  6919 D HealthService: Received start request. Starting profile...
08-09 14:33:46.551  7044  7044 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-09 14:33:46.551  7044  7044 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-09 14:33:46.552  6919  6919 I bluedroid-qcom: get_profile_interface health
08-09 14:33:46.552  6919  6919 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-09 14:33:46.552  6919  6919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcb8855
08-09 14:33:46.553  6919  7411 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-09 14:33:46.555  6919  6919 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-09 14:33:46.553  6919  7411 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-09 14:33:46.556  6919  7411 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-09 14:33:46.556  6919  6919 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-09 14:33:46.558  6919  6919 D PanService: Received start request. Starting profile...
08-09 14:33:46.558  6881  7450 V FormManager: Network unavailable.
08-09 14:33:46.558  6919  6919 D BluetoothPanServiceJni: initializeNative(L110): pan
08-09 14:33:46.558  6919  6919 I bluedroid-qcom: get_profile_interface pan
08-09 14:33:46.566  6881  7450 V FormManager: Network unavailable.
,08-09 14:33:46.567  6919  6919 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-09 14:33:46.567  6919  6919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcb8855
08-09 14:33:46.568  6919  6919 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-09 14:33:46.570  7119  7119 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:33:46
08-09 14:33:46.572  7119  7119 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-09 14:33:46.572  7119  7119 D Weather.Utils: 2 : All the weather widget is gone.
08-09 14:33:46.573  7119  7119 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-09 14:33:46.573  7119  7119 D WeatherAncestor: connectivity changed - connection : true
08-09 14:33:46.573  7119  7119 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@fcb8855
08-09 14:33:46.574  6919  6919 D BtGatt.DebugUtils: handleDebugAction() action=null
08-09 14:33:46.574  6919  6919 D BtGatt.GattService: Received start request. Starting profile...
08-09 14:33:46.574  6919  6919 D BtGatt.GattService: start()
08-09 14:33:46.574  6919  6919 I bluedroid-qcom: get_profile_interface gatt
08-09 14:33:46.574  7119  7119 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-09 14:33:46.574  7119  7119 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-09 14:33:46.574  7119  7119 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-09 14:33:46.574  7119  7119 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-09 14:33:46.574  7119  7119 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:33:46
08-09 14:33:46.574  6919  6919 D BtGatt.AdvertiseManager: advertise manager created
08-09 14:33:46.583  6919  6919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcb8855
,08-09 14:33:46.584  6919  6919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcb8855
08-09 14:33:46.585  6919  6919 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-09 14:33:46.586  6919  6919 V BluetoothMapService: BluetoothMapBinder()
08-09 14:33:46.586  6919  6919 D BluetoothMapService: Received start request. Starting profile...
08-09 14:33:46.586  6919  6919 D BluetoothMapService: start()
08-09 14:33:46.589  6919  6919 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-09 14:33:46.589  6919  6919 D BluetoothMapEmailAppObserver: createReceiver()
08-09 14:33:46.590  6919  6919 D BluetoothMapEmailAppObserver: initObservers()
08-09 14:33:46.590  6919  6919 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-09 14:33:46.595  6919  6919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcb8855
,08-09 14:33:46.598  6919  6919 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-09 14:33:46.601  6919  6919 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-09 14:33:46.603  6919  6919 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-09 14:33:46.603  6919  6919 V PanService: [BTUI] SIM Extra State :ABSENT
08-09 14:33:46.606  6919  6919 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-09 14:33:46.608  6919  6919 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,08-09 14:33:46.608  6919  6919 V BluetoothMapService: Handler(): got msg=1
,08-09 14:33:46.609  6919  7387 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-09 14:33:46.609  6919  7387 I bluedroid-qcom: enable
08-09 14:33:46.610  6919  7457 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-09 14:33:46.610  6919  7387 I bt_hci_bdroid: init
08-09 14:33:46.610  6919  7457 I bt-btu  : btu_task pending for preload complete event
08-09 14:33:46.611  6919  6919 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:46.611  6919  7387 I bt_vendor: bt-vendor : init
,08-09 14:33:46.611  6919  7387 I bt_vendor: bt-vendor : get_bt_soc_type
08-09 14:33:46.611  6919  7387 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-09 14:33:46.611  6919  7387 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-09 14:33:46.611  6919  7387 D bt_userial_mct: userial_init
08-09 14:33:46.613  6919  6919 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-09 14:33:46.613  6919  6919 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-09 14:33:46.613  6919  6919 V BluetoothSapReceiver: SapReceiver onReceive 
08-09 14:33:46.613  6919  6919 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:46.613  6919  7387 D bt_hci_bdroid: set_power 1
08-09 14:33:46.613  6919  7387 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-09 14:33:46.613  6919  6919 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-09 14:33:46.613  6919  7387 I bt_vendor: Starting hciattach daemon
08-09 14:33:46.613  6919  7387 I bt_vendor: try to set true
08-09 14:33:46.605  7460  7460 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 14:33:46.605  7460  7460 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 14:33:46.661  7461  7461 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-09 14:33:46.812  7467  7467 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-09 14:33:46.836  7468  7468 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-09 14:33:46.879  7473  7473 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-09 14:33:46.893  7474  7474 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-09 14:33:46.908  7475  7475 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-09 14:33:46.920  7476  7476 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-09 14:33:46.946  7478  7478 I libmdmdetect: ESOC framework not supported
,08-09 14:33:46.947  7478  7478 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-09 14:33:46.957  7478  7478 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-09 14:33:46.957  7478  7478 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-09 14:33:46.957  7478  7478 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-09 14:33:46.957  7478  7478 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-09 14:33:46.957  7478  7478 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-09 14:33:46.957  7478  7478 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-09 14:33:46.957  7478  7478 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-09 14:33:46.996  7478  7479 E QC-QMI  : qmi_client [7478] 14: failed to locate client data
08-09 14:33:46.999   464   464 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-09 14:33:46.999   464   464 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-09 14:33:47.047  7480  7480 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-09 14:33:47.062  7481  7481 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-09 14:33:47.090  1036  1099 W ProcessCpuTracker: Skipping unknown process pid 7460
,08-09 14:33:47.091  1036  1099 W ProcessCpuTracker: Skipping unknown process pid 7477
08-09 14:33:47.091  1036  1099 W ProcessCpuTracker: Skipping unknown process pid 7478
08-09 14:33:47.116  6919  7387 I bt_vendor: bluetooth satus is on
08-09 14:33:47.116  6919  7387 D bt_hci_bdroid: preload
08-09 14:33:47.117  6919  7459 D bt_userial_mct: userial_open(port:0)
08-09 14:33:47.117  6919  7459 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-09 14:33:47.121  6919  7459 I bt_vendor: Done intiailizing UART
08-09 14:33:47.126  6919  7459 I bt_vendor: Done intiailizing UART
08-09 14:33:47.126  6919  7459 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-09 14:33:47.126  6919  7459 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-09 14:33:47.127  6919  7457 I bt-btu  : btu_task received preload complete event
08-09 14:33:47.127  6919  7483 D bt_userial_mct: Entering userial_read_thread()
08-09 14:33:47.128  6919  7457 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-09 14:33:47.128  6919  7457 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-09 14:33:47.135  6919  7457 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-09 14:33:47.143  6919  7457 I         : BTE_InitTraceLevels -- TRC_HCI
,08-09 14:33:47.143  6919  7457 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-09 14:33:47.143  6919  7457 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-09 14:33:47.143  6919  7457 I         : BTE_InitTraceLevels -- TRC_AVDT
08-09 14:33:47.143  6919  7457 I         : BTE_InitTraceLevels -- TRC_AVRC
08-09 14:33:47.143  6919  7457 I         : BTE_InitTraceLevels -- TRC_A2D
08-09 14:33:47.143  6919  7457 I         : BTE_InitTraceLevels -- TRC_BNEP
08-09 14:33:47.143  6919  7457 I         : BTE_InitTraceLevels -- TRC_BTM
08-09 14:33:47.143  6919  7457 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-09 14:33:47.143  6919  7457 I         : BTE_InitTraceLevels -- TRC_GAP
08-09 14:33:47.143  6919  7457 I         : BTE_InitTraceLevels -- TRC_PAN
08-09 14:33:47.143  6919  7457 I         : BTE_InitTraceLevels -- TRC_SDP
08-09 14:33:47.143  6919  7457 I         : BTE_InitTraceLevels -- TRC_GATT
08-09 14:33:47.143  6919  7457 I         : BTE_InitTraceLevels -- TRC_SMP
08-09 14:33:47.143  6919  7457 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-09 14:33:47.143  6919  7457 I         : BTE_InitTraceLevels -- TRC_BTIF
08-09 14:33:47.192  6919  7457 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-09 14:33:47.192  6919  7457 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01b2061 
08-09 14:33:47.192  6919  7457 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01b2061 
,08-09 14:33:47.208  6919  7391 E bt-btif : Calling BTA_HhEnable
08-09 14:33:47.208  6919  7457 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-09 14:33:47.208  6919  7457 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-09 14:33:47.208  6919  7457 W bt-l2cap: btif_storage_get_adapter_propertyr PSM: 0x001b
08-09 14:33:47.208  6919  7391 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-09 14:33:47.208  6919  7457 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-09 14:33:47.208  6919  7457 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-09 14:33:47.208  6919  7391 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-09 14:33:47.211  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-09 14:33:47.212  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-09 14:33:47.212  6919  7391 D BluetoothAdapterProperties: Name is: G3
08-09 14:33:47.216  6919  7391 D BluetoothAdapterProperties: Scan Mode:20
08-09 14:33:47.216  6919  7391 D BluetoothAdapterProperties: Discoverable Timeout:120
08-09 14:33:47.216  6919  7391 D bt_hci_bdroid: postload
08-09 14:33:47.217  6919  7459 D bt_hci_bdroid: Used up Tx Cmd credits
08-09 14:33:47.218  6919  7391 D bte_conf: Device ID record 1 : primary
08-09 14:33:47.218  6919  7391 D bte_conf:   vendorId            = 00c4
08-09 14:33:47.218  6919  7391 D bte_conf:   vendorIdSource      = 0001
08-09 14:33:47.218  6919  7391 D bte_conf:   product             = 13a1
08-09 14:33:47.218  6919  7391 D bte_conf:   version             = 1000
08-09 14:33:47.219  6919  7391 D bte_conf:   clientExecutableURL = 
08-09 14:33:47.219  6919  7391 D bte_conf:   serviceDescription  = 
08-09 14:33:47.219  6919  7391 D bte_conf:   documentationURL    = 
08-09 14:33:47.219  6919  7391 D bte_conf: bte_load_did_conf no section named DID2.
08-09 14:33:47.220  6919  7457 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
,08-09 14:33:47.224  6919  7457 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-09 14:33:47.224  6919  7457 W bt-smp  : Plain text(LSB ~ MSB) = 49 9e 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-09 14:33:47.224  6919  7457 W bt-smp  : Encrypted text(LSB ~ MSB) = 1c ca 81 ba 26 3c 66 55 42 12 ef 4d 41 27 c1 bf 
08-09 14:33:47.224  6919  7457 W bt-btm  : Stopping oneshot timer
08-09 14:33:47.224  6919  7391 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-09 14:33:47.225  6919  7387 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-09 14:33:47.225  6919  7387 D BluetoothAdapterProperties: ScanMode =  20
08-09 14:33:47.225  6919  7387 D BluetoothAdapterProperties: State =  11
08-09 14:33:47.225  6919  7387 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-09 14:33:47.226  6919  7387 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-09 14:33:47.226  6919  7387 D BluetoothAdapterProperties: Setting state to 12
08-09 14:33:47.226  6919  7387 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-09 14:33:47.227  1036  1118 D BluetoothManagerService: Message: 60
08-09 14:33:47.227  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-09 14:33:47.228  6919  7387 I BluetoothAdapterState: Entering On State
08-09 14:33:47.229  6919  7459 D bt_hci_bdroid: Used up Tx Cmd credits
08-09 14:33:47.230  6919  7391 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-09 14:33:47.230  6919  7459 D bt_hci_bdroid: Used up Tx Cmd credits
08-09 14:33:47.232  6919  7459 D bt_hci_bdroid: Used up Tx Cmd credits
08-09 14:33:47.225  7486  7486 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 14:33:47.225  7486  7486 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 14:33:47.235  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:47.235  6919  7459 D bt_hci_bdroid: Used up Tx Cmd credits
08-09 14:33:47.235  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-09 14:33:47.236  1836  2463 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 14:33:47.239  6919  7483 E bt_mct  : hci lib postload completed
,08-09 14:33:47.242  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:47.242  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:47.242  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:47.242  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 14:33:47.242  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 14:33:47.242  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:47.242  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:47.242  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 14:33:47.243  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 14:33:47.248  6919  7387 D LGBluetoothServiceAdapter: [BTUI] OnState
08-09 14:33:47.248  6919  7387 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-09 14:33:47.248  6919  7387 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-09 14:33:47.249  6919  7387 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-09 14:33:47.252  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-09 14:33:47.252  6919  7391 D BluetoothAdapterProperties: Discoverable Timeout:120
08-09 14:33:47.252  6919  7391 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-09 14:33:47.254  1836  1836 D BluetoothHeadset: Proxy object connected
08-09 14:33:47.255  1036  1036 D BluetoothA2dp: Proxy object connected
08-09 14:33:47.256  6792  6810 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-09 14:33:47.257  7146  7179 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-09 14:33:47.260  6792  6809 D BluetoothPbap: onBluetoothStateChange: up=true
08-09 14:33:47.261  6792  6792 D BluetoothInputDevice: Proxy object connected
08-09 14:33:47.261  6792  6792 D HidProfile: Bluetooth service connected
08-09 14:33:47.261  6919  7457 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-09 14:33:47.261  6919  7457 W bt-smp  : Plain text(LSB ~ MSB) = ec fa 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-09 14:33:47.262  6919  7457 W bt-smp  : Encrypted text(LSB ~ MSB) = ea e6 08 fe 03 a9 2c ea fa 32 ec bd 56 5a e6 09 
08-09 14:33:47.262  6919  7457 W bt-btm  : Stopping oneshot timer
08-09 14:33:47.268  1836  1851 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-09 14:33:47.272  1836  1836 D BluetoothHeadset: Proxy object connected
08-09 14:33:47.274  1836  2463 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 14:33:47.276  1836  1836 D BluetoothHeadset: Proxy object connected
08-09 14:33:47.276  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 14:33:47.277  1036  1036 D BluetoothHeadset: Proxy object connected
08-09 14:33:47.278  6919  7457 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-09 14:33:47.278  6919  7457 W bt-smp  : Plain text(LSB ~ MSB) = 5e 42 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-09 14:33:47.278  6919  7457 W bt-smp  : Encrypted text(LSB ~ MSB) = b6 fb 40 46 75 ff b6 96 8e 68 c5 8a d8 bf c7 6b 
08-09 14:33:47.278  6919  7457 W bt-btm  : Stopping oneshot timer
08-09 14:33:47.278  6919  7387 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-09 14:33:47.280  6792  6810 D BluetoothPan: onBluetoothStateChange on: true
08-09 14:33:47.280  6792  6810 D BluetoothPan: onBluetoothStateChange call bindService
08-09 14:33:47.284  6792  6809 D BluetoothMap: onBluetoothStateChange: up=true
,08-09 14:33:47.286  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-09 14:33:47.287  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-09 14:33:47.288  6919  7457 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-09 14:33:47.288  6919  7457 W bt-smp  : Plain text(LSB ~ MSB) = e0 38 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-09 14:33:47.288  6919  7457 W bt-smp  : Encrypted text(LSB ~ MSB) = b3 c2 9a 8d 58 dd 36 11 6f 08 8f e3 6e 82 7e d9 
08-09 14:33:47.288  6919  7457 W bt-btm  : Stopping oneshot timer
08-09 14:33:47.288  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:47.289  1926  2073 D LGBluetoothAPIService: Message: 1
08-09 14:33:47.289  1926  2073 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-09 14:33:47.290  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-09 14:33:47.295  6792  6792 D BluetoothPan: BluetoothPAN Proxy object connected
08-09 14:33:47.295  6792  6792 D PanProfile: Bluetooth service connected
08-09 14:33:47.302  1926  2073 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-09 14:33:47.306  6919  7457 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-09 14:33:47.306  6919  7457 W bt-smp  : Plain text(LSB ~ MSB) = 53 f7 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-09 14:33:47.306  6919  7457 W bt-smp  : Encrypted text(LSB ~ MSB) = 51 0b f2 5c a9 d8 f2 ea c9 c3 e3 6b 23 22 a3 eb 
08-09 14:33:47.306  6919  7457 W bt-btm  : Stopping oneshot timer
08-09 14:33:47.307  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,08-09 14:33:47.308  1036  1118 D BluetoothManagerService: Message: 40
08-09 14:33:47.308  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-09 14:33:47.312  7492  7492 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-09 14:33:47.317  6669  6669 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-09 14:33:47.320  6919  6919 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:47.321  6919  6919 D BluetoothMapService: STATE_ON
,08-09 14:33:47.322  6792  6792 D LocalBluetoothProfileManager: Adding local A2DP profile
08-09 14:33:47.323  6919  6919 D LGBluetoothAPIServer: [BTUI] onCreate()
08-09 14:33:47.323  6919  6919 D LGBluetoothAPIServer: [BTUI] onBind()
08-09 14:33:47.325  1926  1926 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-09 14:33:47.325  1036  1118 D BluetoothManagerService: Message: 30
08-09 14:33:47.325  1926  2073 D LGBluetoothAPIService: Message: 100
08-09 14:33:47.326  1926  2073 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-09 14:33:47.331  6792  6792 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-09 14:33:47.334  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:47.334  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:47.334  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:47.334  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 14:33:47.334  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 14:33:47.334  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:47.334  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:47.334  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 14:33:47.336  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 14:33:47.338  1036  1118 D BluetoothManagerService: Message: 30
08-09 14:33:47.338  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 14:33:47.343  6919  6919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcb8855
08-09 14:33:47.343  6919  6919 V BluetoothPbapService: Pbap Service onCreate
08-09 14:33:47.344  6919  6919 V BluetoothPbapService: Starting PBAP service
08-09 14:33:47.344  6792  6792 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-09 14:33:47.345  6919  6919 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-09 14:33:47.345  6919  6919 V BluetoothPbapService: Pbap Service onBind
08-09 14:33:47.346  6792  6792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-09 14:33:47.346  6919  6919 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:47.347  6919  6919 V BluetoothPbapService: state: 12
08-09 14:33:47.347  6919  6919 V BluetoothMapService: Handler(): got msg=1
08-09 14:33:47.347  6919  6919 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-09 14:33:47.348  6919  6919 V BluetoothPbapService: Handler(): got msg=1
08-09 14:33:47.348  6919  6919 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-09 14:33:47.349  6919  7499 D BluetoothMapMasInstance: MAS initSocket()
08-09 14:33:47.350  6919  7499 D BluetoothMapMasInstance:   masId = 00
08-09 14:33:47.350  6919  7499 D BluetoothMapMasInstance:   msgTypes = 0e
08-09 14:33:47.350  6919  7499 D BluetoothMapMasInstance:   masName = SMS/MMS
08-09 14:33:47.350  6919  7499 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
,08-09 14:33:47.351  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 14:33:47.353  6919  7499 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 14:33:47.353  6792  6792 D BluetoothMap: Proxy object connected
08-09 14:33:47.353  6792  6792 D MapProfile: Bluetooth service connected
08-09 14:33:47.353  6792  6792 D BluetoothMap: getConnectedDevices()
08-09 14:33:47.354  6919  7500 V BluetoothPbapService: Pbap Service initSocket
08-09 14:33:47.354  6919  7497 V BluetoothMapService: getConnectedDevices()
08-09 14:33:47.355  6919  7499 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-09 14:33:47.355  6919  7499 V BluetoothMapMasInstance: Succeed to create listening socket 
08-09 14:33:47.355  6919  6919 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-09 14:33:47.355  1036  1997 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 14:33:47.356  6919  6919 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:47.356  6919  6919 V BluetoothPbapReceiver: ***********state = 12
08-09 14:33:47.356  6919  7391 D BluetoothAdapterProperties: Scan Mode:21
08-09 14:33:47.356  6792  6792 D BluetoothA2dp: Proxy object connected
08-09 14:33:47.357  6919  7499 D BluetoothMapMasInstance: Accepting socket connection...
08-09 14:33:47.357  6919  7391 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-09 14:33:47.357  6792  6792 D A2dpProfile: Bluetooth service connected
08-09 14:33:47.358  6919  7500 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 14:33:47.359  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:47.361  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 14:33:47.363  2140  2140 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-09 14:33:47.363  2140  2140 D c       : Getting all permits...
08-09 14:33:47.363  2140  2140 D a       : Opening database...
08-09 14:33:47.367  2140  2140 D a       : Opening database auth.proximity.permit_store...
08-09 14:33:47.368  2140  2140 D a       : Closing database...
08-09 14:33:47.370  6792  6792 D BluetoothHeadset: Proxy object connected
08-09 14:33:47.371  6919  7500 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-09 14:33:47.371  6919  7500 V BluetoothPbapService: Succeed to create listening socket 
08-09 14:33:47.371  6919  7500 V BluetoothPbapService: Accepting socket connection...
08-09 14:33:47.372  6792  6792 D HeadsetProfile: Bluetooth service connected
08-09 14:33:47.375  6792  6792 D BluetoothPbap: Proxy object connected
,08-09 14:33:47.379  6792  6792 D PbapServerProfile: Bluetooth service connected
08-09 14:33:47.383  6792  6792 D DockEventReceiver: finishStartingService: stopping service
08-09 14:33:47.387  6792  6792 D BluetoothPermissionRequest: onReceive
,08-09 14:33:47.389  6792  6792 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-09 14:33:47.391  6792  6792 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-09 14:33:47.394  6919  6919 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-09 14:33:47.396  6919  6919 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-09 14:33:47.403  6919  6919 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-09 14:33:47.430  6919  6919 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-09 14:33:47.430  6919  6919 V BtOppService: onCreate
,08-09 14:33:47.435  6919  6919 V BluetoothOppNotification: send message
08-09 14:33:47.439  6919  6919 V BtOppService: Starting RfcommListener
08-09 14:33:47.447  6919  6919 D BluetoothOppPreference: Dumping Names:  
,08-09 14:33:47.447  6919  6919 D BluetoothOppPreference: {}
08-09 14:33:47.447  6919  6919 D BluetoothOppPreference: Dumping Channels:  
08-09 14:33:47.447  6919  6919 D BluetoothOppPreference: {}
08-09 14:33:47.448  6919  6919 V BtOppService: onStartCommand
08-09 14:33:47.452  6919  6919 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:47.452  6919  6919 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-09 14:33:47.452  6919  7508 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-09 14:33:47.454  6919  7508 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-09 14:33:47.454  6919  7505 V BtOppService: Deleted complete outbound shares, number =  0
08-09 14:33:47.455  6919  6919 V BluetoothOppNotification: new notify threadi!
08-09 14:33:47.457  6919  6919 V BluetoothOppNotification: send delay message
08-09 14:33:47.457  6919  7505 V BtOppService: Deleted complete inbound failed shares, number = 0
08-09 14:33:47.457  6919  7505 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-09 14:33:47.458  6919  6919 V BtOppService: start RfcommListener
08-09 14:33:47.461  6919  7509 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-09 14:33:47.461  6919  7505 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f70746 on behalf of 
08-09 14:33:47.462  6919  7508 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a899d07 on behalf of 
08-09 14:33:47.464  6919  6919 V BtOppService: RfcommListener started
08-09 14:33:47.465  6919  7509 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@34da2e34 on behalf of 
08-09 14:33:47.465  6919  7508 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-09 14:33:47.468  6919  6919 V BtOppService: ContentObserver received notification
08-09 14:33:47.469  6919  7510 V BtOppRfcommListener: Starting RFCOMM listener....
08-09 14:33:47.470  1036  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 14:33:47.470  6919  7509 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-09 14:33:47.471  6919  7510 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 14:33:47.471  6919  7511 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-09 14:33:47.471  6919  7511 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-09 14:33:47.473  6919  7510 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-09 14:33:47.473  6919  7510 V BtOppRfcommListener: Started RFCOMM listener....
08-09 14:33:47.474  6919  7511 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b31b45d on behalf of 
08-09 14:33:47.474  6919  7510 I BtOppRfcommListener: Accept thread started.
,08-09 14:33:47.474  6919  7510 V BtOppRfcommListener: Accepting connection...
08-09 14:33:47.474  6919  7509 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-09 14:33:47.475  6919  7509 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@260c51d2 on behalf of 
08-09 14:33:47.476  6919  7511 V BluetoothOppNotification: update too frequent, put in queue
08-09 14:33:47.476  6919  7511 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-09 14:33:47.477  6919  7509 V BluetoothOppNotification: outbound: succ-0  fail-0
08-09 14:33:47.480  6919  7509 V BluetoothOppNotification: outbound notification was removed.
08-09 14:33:47.480  6919  7509 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-09 14:33:47.482  6919  7509 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e9902a3 on behalf of 
08-09 14:33:47.483  6919  7509 V BluetoothOppNotification: inbound: succ-0  fail-0
08-09 14:33:47.484  6919  7509 V BluetoothOppNotification: inbound notification was removed.
08-09 14:33:47.485  6919  7509 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-09 14:33:47.486  6919  7509 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@305f9a0 on behalf of 
08-09 14:33:47.496  6919  6919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcb8855
,08-09 14:33:47.496  6919  6919 V BluetoothFtpService: Ftp Service onCreate
08-09 14:33:47.496  6919  6919 I BluetoothFtpService: Ftp Service onCreate
08-09 14:33:47.496  6919  6919 V BluetoothFtpService: Ftp Service onStartCommand
08-09 14:33:47.496  6919  6919 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:47.497  6919  6919 V BluetoothFtpService: Starting Listening on sockets
08-09 14:33:47.497  6919  6919 V BtOppService: ContentObserver received notification
08-09 14:33:47.497  6919  6919 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-09 14:33:47.497  6919  6919 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-09 14:33:47.497  6919  6919 V BluetoothSapReceiver: SapReceiver onReceive 
08-09 14:33:47.497  6919  6919 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:47.497  6919  6919 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-09 14:33:47.498  6919  6919 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-09 14:33:47.499  6919  6919 V BluetoothFtpService: Handler(): got msg=1
08-09 14:33:47.500  6919  7512 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-09 14:33:47.500  6919  7512 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-09 14:33:47.500  6919  6919 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-09 14:33:47.500  6919  6919 V BluetoothFtpService: Ftp Service initSocket
08-09 14:33:47.502  6919  7512 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20b9b91e on behalf of 
08-09 14:33:47.502  1036  1579 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 14:33:47.503  6919  6919 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 14:33:47.503  6919  7512 V BluetoothOppNotification: update too frequent, put in queue
08-09 14:33:47.506  6919  7512 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-09 14:33:47.507  6919  6919 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-09 14:33:47.508  6919  6919 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-09 14:33:47.510  6919  7513 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-09 14:33:47.536  6919  6919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcb8855
,08-09 14:33:47.536  6919  6919 V BluetoothSapService: Sap Service onCreate
08-09 14:33:47.674  1036  1956 I art     : Explicit concurrent mark sweep GC freed 93638(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.627ms total 135.729ms
08-09 14:33:47.674  6919  6919 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:47.674  6919  6919 V BluetoothSapService: state: 12
,08-09 14:33:47.674  6919  6919 V BluetoothSapService: Starting SAP server process
08-09 14:33:47.676  6919  6919 V BluetoothSapService: SAP Service startRfcommListenerThread
08-09 14:33:47.677  6919  7515 V BluetoothSapService: Sap Service initRfcommSocket
08-09 14:33:47.677  1036  1561 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 14:33:47.665  7514  7514 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 14:33:47.665  7514  7514 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 14:33:47.681  6919  7515 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 14:33:47.683  6919  7515 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-09 14:33:47.683  6919  7515 V BluetoothSapService: Succeed to create listening socket 
08-09 14:33:47.683  6919  7515 V BluetoothSapService: Accepting socket connection...
08-09 14:33:47.685  7514  7514 V BT_SAP  : Event pipe created
08-09 14:33:47.685  7514  7514 V BT_SAP  : create_server_socket qcom.sap.server
08-09 14:33:47.685  7514  7514 V BT_SAP  : created socket fd 6
08-09 14:33:48.081  1036  1518 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:48.081  1036  1518 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-09 14:33:48.088  1036  1524 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-09 14:33:48.089  1036  1524 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
08-09 14:33:48.296  1036  1956 I ActivityManager: Killing 7314:com.lge.bnr/1000 (adj 15): empty #17
,08-09 14:33:48.327  1036  1561 W libprocessgroup: failed to open /acct/uid_1000/pid_7314/cgroup.procs: No such file or directory
,08-09 14:33:48.453  1036  2017 I ActivityManager: Killing 6603:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-09 14:33:48.457  6919  6919 V BluetoothOppNotification: new notify threadi!
,08-09 14:33:48.458  6919  6919 V BluetoothOppNotification: send delay message
08-09 14:33:48.471  6919  7525 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-09 14:33:48.481  6919  7525 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2044492a on behalf of 
08-09 14:33:48.482  6919  7525 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-09 14:33:48.486  6841  6841 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-09 14:33:48.486  6841  6841 W System.err: android.os.DeadObjectException
08-09 14:33:48.487  6841  6841 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-09 14:33:48.487  6841  6841 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-09 14:33:48.487  6841  6841 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-09 14:33:48.487  6841  6841 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-09 14:33:48.487  6841  6841 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-09 14:33:48.487  6841  6841 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-09 14:33:48.487  6841  6841 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-09 14:33:48.487  6841  6841 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-09 14:33:48.487  6841  6841 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-09 14:33:48.487  6841  6841 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-09 14:33:48.487  6841  6841 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 14:33:48.487  6841  6841 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 14:33:48.487  6841  6841 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-09 14:33:48.487  6841  6841 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-09 14:33:48.487  6841  6841 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-09 14:33:48.488  6841  6841 W System.err: android.os.DeadObjectException
08-09 14:33:48.488  6841  6841 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-09 14:33:48.488  6841  6841 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-09 14:33:48.488  6841  6841 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-09 14:33:48.488  6841  6841 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-09 14:33:48.488  6841  6841 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-09 14:33:48.488  6841  6841 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-09 14:33:48.488  6841  6841 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-09 14:33:48.488  6841  6841 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-09 14:33:48.488  6841  6841 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-09 14:33:48.488  6841  6841 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-09 14:33:48.488  6841  6841 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 14:33:48.488  6841  6841 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 14:33:48.488  6841  6841 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-09 14:33:48.488  6841  6841 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-09 14:33:48.489  6841  6841 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-09 14:33:48.489  6841  6841 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-09 14:33:48.497  6919  7525 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-09 14:33:48.498  6919  7525 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@bda231b on behalf of 
08-09 14:33:48.499  6919  7525 V BluetoothOppNotification: outbound: succ-0  fail-0
08-09 14:33:48.500  6919  7525 V BluetoothOppNotification: outbound notification was removed.
08-09 14:33:48.502  6919  7525 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-09 14:33:48.503  6919  7525 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@4755cb8 on behalf of 
08-09 14:33:48.503  6919  7525 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-09 14:33:48.508  6919  7525 V BluetoothOppNotification: inbound notification was removed.
08-09 14:33:48.508  6919  7525 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-09 14:33:48.509  6919  7525 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1688ba91 on behalf of 
08-09 14:33:48.512  1036  1052 W libprocessgroup: failed to open /acct/uid_1000/pid_6603/cgroup.procs: No such file or directory
08-09 14:33:48.512  1036  1052 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-09 14:33:48.516  6841  6841 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-09 14:33:48.517  6841  6841 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-09 14:33:48.556  1036  1051 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7526 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-09 14:33:48.556  6841  6841 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-09 14:33:48.631  7526  7526 D UEI.SmartControl: Quickset Services start...
08-09 14:33:48.632  7526  7526 I UEI.SmartControl: Manufacture = LGE
08-09 14:33:48.632  7526  7526 D UEI.SmartControl: Id = LGNevo
08-09 14:33:48.633  7526  7526 D UEI.SmartControl: File observer start...
08-09 14:33:48.634  7526  7526 E UEI.SmartControl: IR Port is disabled: false
08-09 14:33:48.634  7526  7526 D UEI.SmartControl: Starting file observer...
08-09 14:33:48.634  7526  7526 D UEI.SmartControl: Extracting JNI libs...
08-09 14:33:48.634  7526  7526 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-09 14:33:48.697  7526  7526 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-09 14:33:48.697  7526  7526 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-09 14:33:48.697  7526  7526 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-09 14:33:48.723  7526  7526 I UEI.SmartControl: --- Selecting new region: 6
08-09 14:33:48.724  7526  7526 I UEI.SmartControl: Model = LG-D855
08-09 14:33:48.725  7526  7526 D UEI.SmartControl: QS Service created
,08-09 14:33:48.737  7526  7526 I UEI.SmartControl: Service initServices...
08-09 14:33:48.741  7526  7526 D UEI.SmartControl: QS start get config
,08-09 14:33:48.776  7526  7526 D UEI.SmartControl: Loading JNI Libs...
,08-09 14:33:49.083  1036  1561 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-09 14:33:49.083  1036  1561 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2c94fe5f mBinding = false
,08-09 14:33:49.106  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-09 14:33:49.107  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-09 14:33:49.107  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-09 14:33:49.111  1036  1118 D BluetoothManagerService: Message: 2
08-09 14:33:49.113  1036  1118 D BluetoothManagerService: Sending off request.
08-09 14:33:49.114  6919  7497 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-09 14:33:49.115  6919  7387 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-09 14:33:49.115  6919  7387 D BluetoothAdapterProperties: Setting state to 13
08-09 14:33:49.115  6919  7387 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-09 14:33:49.115  6919  7387 D BluetoothAdapterProperties: onBluetoothDisable()
08-09 14:33:49.116  6919  7387 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-09 14:33:49.117  6919  7391 D BluetoothAdapterProperties: Scan Mode:20
08-09 14:33:49.118  6919  7387 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-09 14:33:49.119  6919  7510 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-09 14:33:49.119  6919  7515 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-09 14:33:49.119  6919  7387 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-09 14:33:49.120  6919  7499 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-09 14:33:49.120  6919  7499 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-09 14:33:49.120  6919  7499 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-09 14:33:49.120  6919  7499 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-09 14:33:49.120  6919  7499 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-09 14:33:49.120  6919  7499 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-09 14:33:49.120  6919  7499 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-09 14:33:49.120  6919  7499 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-09 14:33:49.122  6919  7500 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-09 14:33:49.123  6919  7457 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-09 14:33:49.123  6919  7457 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-09 14:33:49.132  6919  7457 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-09 14:33:49.132  6919  7457 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-09 14:33:49.132  6919  7457 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,08-09 14:33:49.132  6919  7457 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-09 14:33:49.132  6919  7457 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-09 14:33:49.132  6919  7457 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-09 14:33:49.132  6919  7457 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-09 14:33:49.132  6919  7457 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-09 14:33:49.132  6919  7457 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-09 14:33:49.132  6919  7457 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-09 14:33:49.132  6919  7457 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-09 14:33:49.132  6919  7457 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-09 14:33:49.133  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:49.133  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:49.133  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:49.133  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:49.133  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 14:33:49.133  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 14:33:49.133  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:49.133  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:49.133  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 14:33:49.135  6919  7513 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-09 14:33:49.136  1036  1118 D BluetoothManagerService: Message: 60
08-09 14:33:49.136  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,08-09 14:33:49.136  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:49.137  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 14:33:49.137  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-09 14:33:49.138  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:49.140  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-09 14:33:49.141  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:49.141  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:49.141  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:49.141  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:49.141  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 14:33:49.141  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 14:33:49.141  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:49.141  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:49.141  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 14:33:49.142  6919  6919 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:49.142  6919  6919 D BluetoothMapService: STATE_TURNING_OFF
08-09 14:33:49.142  6919  6919 V BluetoothMapService: Handler(): got msg=4
08-09 14:33:49.142  6919  6919 D BluetoothMapService: MAP Service closeService in
08-09 14:33:49.142  6919  6919 D BluetoothMapMasInstance: MAP Service shutdown
08-09 14:33:49.142  6919  6919 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-09 14:33:49.142  6919  6919 V BluetoothMapService: MAP Service closeService out
08-09 14:33:49.143  6669  6669 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:49.143  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 14:33:49.143  6919  6919 V BtOppService: Receiver DISABLED_ACTION 
08-09 14:33:49.143  6919  6919 I BtOppRfcommListener: stopping Accept Thread
08-09 14:33:49.143  6919  6919 V BtOppRfcommListener: close mBtServerSocket
08-09 14:33:49.143  6919  6919 V BtOppRfcommListener: waiting for thread to terminate
08-09 14:33:49.144  6919  7510 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-09 14:33:49.144  6919  6919 V BtOppRfcommListener: done waiting for thread to terminate
08-09 14:33:49.145  6919  6919 V BtOppService: onDestroy
08-09 14:33:49.146  6919  6919 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-09 14:33:49.147  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 14:33:49.144  6792  6792 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-09 14:33:49.150  6792  6792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-09 14:33:49.154  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:49.154  6919  6919 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-09 14:33:49.155  6919  6919 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:49.155  6919  6919 V BluetoothPbapReceiver: ***********state = 13
08-09 14:33:49.155  6919  6919 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-09 14:33:49.157  6919  6919 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:49.157  6919  6919 V BluetoothPbapService: state: 13
08-09 14:33:49.157  6919  6919 V BluetoothPbapService: Pbap Service closeService in
08-09 14:33:49.157  6792  6792 D DockEventReceiver: finishStartingService: stopping service
08-09 14:33:49.161  2140  2140 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-09 14:33:49.164  6792  6792 D BluetoothPbap: Proxy object disconnected
08-09 14:33:49.164  6792  6792 D PbapServerProfile: Bluetooth service disconnected
08-09 14:33:49.164  6919  6919 V BluetoothPbapService: successfully stopped pbap service
08-09 14:33:49.164  6919  6919 V BluetoothPbapService: Pbap Service closeService out
08-09 14:33:49.164  6919  6919 V BluetoothPbapService: Pbap Service onDestroy
08-09 14:33:49.164  6919  6919 V BluetoothPbapService: Pbap Service closeService in
08-09 14:33:49.164  6919  6919 V BluetoothPbapService: Pbap Service closeService out
08-09 14:33:49.164  6919  6919 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-09 14:33:49.167  7526  7526 I UEI.SmartControl: Supports setup maps: true
08-09 14:33:49.170  7526  7526 D UEI.SmartControl: QS start statue = true Error code = 0
08-09 14:33:49.170  7526  7526 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-09 14:33:49.170  7526  7526 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-09 14:33:49.170  7526  7526 I UEI.SmartControl: ### init IR Blaster...
08-09 14:33:49.175  7526  7526 D serial_port: Configuring serial port
08-09 14:33:49.177  7526  7526 E UEI.SmartControl: UEIBLaster setting for 616
08-09 14:33:49.177  7526  7526 I UEI.SmartControl: Setting serial record hearder size = 2
,08-09 14:33:49.179  7526  7526 I UEI.SmartControl: configuring settings for MAXQ616
08-09 14:33:49.180  7526  7526 I UEI.SmartControl: Get version...
08-09 14:33:49.185  6792  6792 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-09 14:33:49.187  6792  6792 D BluetoothPermissionRequest: onReceive
08-09 14:33:49.187  6792  6792 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-09 14:33:49.191  6792  6792 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-09 14:33:49.196  7526  7552 D UEI.SmartControl: serial port data available: 21
08-09 14:33:49.199  6919  6919 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-09 14:33:49.200  6919  6919 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-09 14:33:49.200  6919  6919 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-09 14:33:49.206  6919  6919 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-09 14:33:49.206  6919  6919 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-09 14:33:49.207  6919  6919 V BluetoothFtpService: Ftp Service onStartCommand
08-09 14:33:49.208  6919  6919 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:49.208  6919  6919 V BluetoothFtpService: Ftp Service closeService
08-09 14:33:49.208  6919  6919 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-09 14:33:49.210  6919  6919 V BluetoothFtpService: successfully stopped ftp service
08-09 14:33:49.210  6919  6919 V BluetoothFtpService: Ftp Service onDestroy
08-09 14:33:49.211  6919  6919 V BluetoothFtpService: Ftp Service closeService
08-09 14:33:49.212  6919  6919 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-09 14:33:49.213  6919  6919 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-09 14:33:49.213  6919  6919 V BluetoothSapReceiver: SapReceiver onReceive 
08-09 14:33:49.213  6919  6919 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:49.213  6919  6919 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-09 14:33:49.213  6919  6919 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-09 14:33:49.215  6919  6919 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:49.215  6919  6919 V BluetoothSapService: state: 13
08-09 14:33:49.215  6919  6919 V BluetoothSapService: Stopping SAP server process
08-09 14:33:49.216  6919  6919 V BluetoothSapService: Sap Service closeSapService in
08-09 14:33:49.216  6919  6919 V BluetoothSapService: Close listen Socket : 
08-09 14:33:49.216  6919  6919 V BluetoothSapService: Close rfcomm Socket : 
08-09 14:33:49.216  6919  6919 V BluetoothSapService: Close sapd  Socket : 
08-09 14:33:49.223  6919  6919 V BluetoothSapService: Sap Service closeSapService out
,08-09 14:33:49.224  6919  6919 V BluetoothSapService: Sap Service onDestroy,
08-09 14:33:49.224  6919  6919 V BluetoothSapService: Sap Service closeSapService in
,08-09 14:33:49.224  7526  7526 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-09 14:33:49.224  6919  6919 V BluetoothSapService: Close listen Socket : 
08-09 14:33:49.224  7526  7526 I UEI.SmartControl: IR Blaster version: 256702256704300002,
08-09 14:33:49.225  7526  7526 I UEI.SmartControl: QS saving settings...
08-09 14:33:49.224  6919  6919 V BluetoothSapService: Close rfcomm Socket : 
,08-09 14:33:49.225  6919  6919 V BluetoothSapService: Close sapd  Socket : 
08-09 14:33:49.226  6919  6919 V BluetoothSapService: Sap Service closeSapService out
08-09 14:33:49.227  7526  7526 D UEI.SmartControl: IR Blaster version: 25672567,
08-09 14:33:49.244  7526  7552 D UEI.SmartControl: serial port data available: 4
,08-09 14:33:49.282  7526  7564 I UEI.SmartControl: Device manager: loading config....
08-09 14:33:49.283  7526  7564 D UEI.SmartControl: ----------- loading internal config...
08-09 14:33:49.284  7526  7526 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-09 14:33:49.287  7526  7526 E UEI.SmartControl: Services init done
,08-09 14:33:49.287  7526  7526 D UEI.SmartControl: QS Service init finished
08-09 14:33:49.289  7526  7526 D UEI.SmartControl: QS Service version name: 2.1.91
08-09 14:33:49.290  7526  7526 D UEI.SmartControl: QS Service version code: 201091
08-09 14:33:49.291  7526  7526 D UEI.SmartControl: Service requested: Control
08-09 14:33:49.300  7526  7564 E UEI.SmartControl: Loading SETTINGS...
08-09 14:33:49.302  7526  7526 D UEI.SmartControl: Request IControl service: devices are loaded...
08-09 14:33:49.307  1036  1997 I ActivityManager: Killing 6841:com.lge.qremote/u0a112 (adj 15): empty #17
,08-09 14:33:49.315  7526  7564 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-09 14:33:49.339  7526  7563 I UEI.SmartControl: Notify AllClients services are ready: 0
08-09 14:33:49.339  7526  7563 D UEI.SmartControl: -----service ready thread exits
,08-09 14:33:49.344  1036  1561 W libprocessgroup: failed to open /acct/uid_10112/pid_6841/cgroup.procs: No such file or directory
,08-09 14:33:49.345  7526  7526 D UEI.SmartControl: Internal service binding...
08-09 14:33:50.029  6919  7391 D bt_hci_bdroid: cleanup
,08-09 14:33:50.037  6919  7459 I bt_lpm  : LPM is already off!!!
08-09 14:33:50.038  6919  7483 I bt_userial_mct: exiting userial_read_thread
08-09 14:33:50.038  6919  7483 D bt_userial_mct: Leaving userial_evt_read_thread()
08-09 14:33:50.039  6919  7457 W bt-btif : ag scb idx 1 not allocated
08-09 14:33:50.039  6919  7457 E bt-btif : BTA AG is already disabled, ignoring ...
08-09 14:33:50.039  6919  7457 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-09 14:33:50.039  6919  7457 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-09 14:33:50.039  6919  7457 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-09 14:33:50.039  6919  7457 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-09 14:33:50.039  6919  7457 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-09 14:33:50.039  6919  7457 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-09 14:33:50.039  6919  7457 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-09 14:33:50.040  6919  7457 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-09 14:33:50.040  6919  7457 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,08-09 14:33:50.040  6919  7457 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-09 14:33:50.040  6919  7457 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,08-09 14:33:50.040  6919  7457 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-09 14:33:50.040  6919  7457 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-09 14:33:50.040  6919  7457 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-09 14:33:50.040  6919  7457 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-09 14:33:50.040  6919  7457 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-09 14:33:50.040  6919  7457 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-09 14:33:50.040  6919  7457 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-09 14:33:50.040  6919  7457 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-09 14:33:50.043  6919  7391 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-09 14:33:50.044  6919  7459 I bt_vendor: hw_epilog_process
08-09 14:33:50.045  6919  7391 D bt_hci_bdroid: cleanup Finalizing cleanup,
08-09 14:33:50.045  6919  7391 D bt_userial_mct: userial_close
08-09 14:33:50.045  6919  7391 E bt_userial_mct: pthread_join() FAILED result:3
,08-09 14:33:50.045  6919  7391 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-09 14:33:50.051  6919  7391 D bt_hci_bdroid: set_power 0
,08-09 14:33:50.051  6919  7391 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-09 14:33:50.051  6919  7391 I bt_vendor: bluetooth satus is on
08-09 14:33:50.051  6919  7391 I bt_vendor: bt-vendor : resetting BT status
08-09 14:33:50.051  6919  7391 I bt_vendor: Starting hciattach daemon,
08-09 14:33:50.051  6919  7391 I bt_vendor: try to set false
,08-09 14:33:50.060  6919  7391 I bt_vendor: Starting hciattach daemon
08-09 14:33:50.060  6919  7391 I bt_vendor: try to set false
08-09 14:33:50.063  6919  7391 I bt_vendor: cleanup
08-09 14:33:50.063  6919  7457 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-09 14:33:50.064  6919  7391 I GKI_LINUX: GKI_exit_task 0 done
08-09 14:33:50.064  6919  7391 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-09 14:33:50.065  6919  7387 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-09 14:33:50.073  6919  6919 D HeadsetService: Received stop request...Stopping profile...
,08-09 14:33:50.076  6919  7387 D BluetoothAdapterState: Stopping profile services that were post enabled
08-09 14:33:50.077  6919  6919 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-09 14:33:50.077  6919  6919 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-09 14:33:50.077  6919  6919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcb8855
08-09 14:33:50.078  6919  7411 D HeadsetStateMachine: Exit Disconnected: -1
08-09 14:33:50.081  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-09 14:33:50.081  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-09 14:33:50.082  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-09 14:33:50.082  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-09 14:33:50.082  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-09 14:33:50.083  6919  6919 D A2dpService: Received stop request...Stopping profile...
08-09 14:33:50.085  6919  7444 D A2dpStateMachine: Exit Disconnected: -1
,08-09 14:33:50.089  6919  6919 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-09 14:33:50.091  6919  6919 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-09 14:33:50.091  6919  6919 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-09 14:33:50.091  6919  6919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcb8855
08-09 14:33:50.093  6919  6919 D HidService: Received stop request...Stopping profile...
08-09 14:33:50.093  6919  6919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcb8855
08-09 14:33:50.095  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-09 14:33:50.095  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-09 14:33:50.097  6919  6919 D HealthService: Received stop request...Stopping profile...
08-09 14:33:50.097  6919  6919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcb8855
,08-09 14:33:50.101  6919  6919 D PanService: Received stop request...Stopping profile...
08-09 14:33:50.103  6919  6919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcb8855
08-09 14:33:50.104  6919  6919 D BtGatt.DebugUtils: handleDebugAction() action=null
08-09 14:33:50.104  6919  6919 D BtGatt.GattService: Received stop request...Stopping profile...
08-09 14:33:50.105  6919  6919 D BtGatt.GattService: stop()
08-09 14:33:50.105  6919  6919 D BtGatt.AdvertiseManager: advertise clients cleared
08-09 14:33:50.106  6919  6919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcb8855
08-09 14:33:50.107  6919  6919 D BluetoothMapService: Received stop request...Stopping profile...
08-09 14:33:50.107  6919  6919 D BluetoothMapService: stop()
08-09 14:33:50.108  6919  6919 D BluetoothMapEmailAppObserver: deinitObservers()
08-09 14:33:50.108  6919  6919 D BluetoothMapEmailAppObserver: removeReceiver()
08-09 14:33:50.109  6919  6919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fcb8855
,08-09 14:33:50.112  6919  6919 D HeadsetStateMachine: Unbinding service...
08-09 14:33:50.114  6919  6919 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-09 14:33:50.114  6919  6919 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-09 14:33:50.114  6919  6919 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-09 14:33:50.114  6919  6919 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-09 14:33:50.114  6919  6919 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-09 14:33:50.114  6919  6919 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-09 14:33:50.114  6919  6919 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-09 14:33:50.115  6919  6919 I BluetoothA2dpServiceJni: cleanupNative
08-09 14:33:50.116  6919  7446 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-09 14:33:50.117  6919  6919 I GKI_LINUX: GKI_exit_task 2 done
08-09 14:33:50.117  6919  6919 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-09 14:33:50.117  6919  6919 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-09 14:33:50.117  6919  6919 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-09 14:33:50.117  6919  6919 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-09 14:33:50.118  6919  6919 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-09 14:33:50.118  6919  6919 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-09 14:33:50.118  6919  6919 V BluetoothMapService: Handler(): got msg=4
08-09 14:33:50.118  6919  6919 D BluetoothMapService: MAP Service closeService in
08-09 14:33:50.118  6919  6919 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-09 14:33:50.118  6919  6919 V BluetoothMapService: MAP Service closeService out
08-09 14:33:50.119  6919  7387 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-09 14:33:50.119  6919  7387 D BluetoothAdapterProperties: Setting state to 10
08-09 14:33:50.119  6919  7387 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-09 14:33:50.120  6919  6919 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-09 14:33:50.120  6919  6919 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-09 14:33:50.122  1036  1118 D BluetoothManagerService: Message: 60
08-09 14:33:50.122  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-09 14:33:50.122  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
,08-09 14:33:50.126  1836  1851 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 14:33:50.128  6919  7387 I BluetoothAdapterState: Entering OffState
08-09 14:33:50.130  6919  6919 D BluetoothMapService: cleanup()
08-09 14:33:50.130  6919  6919 D BluetoothMapService: MAP Service closeService in
08-09 14:33:50.130  6919  6919 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-09 14:33:50.130  6919  6919 V BluetoothMapService: MAP Service closeService out
08-09 14:33:50.131  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
08-09 14:33:50.132  6792  6809 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-09 14:33:50.132  6792  6809 D BluetoothA2dp: onBluetoothStateChange: up=false
08-09 14:33:50.133  6792  6809 D BluetoothPbap: onBluetoothStateChange: up=false
08-09 14:33:50.133  6792  6809 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-09 14:33:50.136  1836  2463 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 14:33:50.137  1836  1852 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 14:33:50.137  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 14:33:50.137  6792  6809 D BluetoothPan: onBluetoothStateChange on: false
08-09 14:33:50.138  6792  6809 D BluetoothMap: onBluetoothStateChange: up=false
08-09 14:33:50.140  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-09 14:33:50.140  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-09 14:33:50.142  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-09 14:33:50.142  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-09 14:33:50.142  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2c94fe5f mBinding = false
08-09 14:33:50.142  1036  1118 D BluetoothManagerService: Sending unbind request.
08-09 14:33:50.147  6919  7391 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-09 14:33:50.149  6919  6919 I GKI_LINUX: GKI_exit_task 1 done
08-09 14:33:50.149  6919  6919 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-09 14:33:50.150  6919  6919 I BluetoothServiceJni: cleanupNative: return from cleanup
08-09 14:33:50.150  6919  6919 I art     : --- WEIRD: removing null entry 248
08-09 14:33:50.151  6919  6919 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-09 14:33:50.151  6919  6919 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-09 14:33:50.152  6919  6919 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-09 14:33:50.153  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-09 14:33:50.155  6919  6919 I art     : System.exit called, status: 0
08-09 14:33:50.155  6919  6919 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-09 14:33:50.174   315  1372 V AudioFlinger: 6919 died, releasing its sessions
08-09 14:33:50.174   315  1372 V AudioFlinger:  pid 1836 @ 0
08-09 14:33:50.174   315  1372 V AudioFlinger:  pid 3490 @ 1
08-09 14:33:50.174   315  1372 V AudioFlinger:  pid 3490 @ 2
,08-09 14:33:50.178  1926  1926 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-09 14:33:50.178  1926  2073 D LGBluetoothAPIService: Message: 101
08-09 14:33:50.178  1926  2073 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-09 14:33:50.178  1926  2073 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-09 14:33:50.178  1926  2073 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-09 14:33:50.180  6792  6792 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-09 14:33:50.231  1036  1921 I ActivityManager: Process com.android.bluetooth (pid 6919) has died
08-09 14:33:50.231  1036  1921 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-09 14:33:50.231  1036  1921 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 10999ms
,08-09 14:33:50.241  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:50.242  1926  2073 D LGBluetoothAPIService: Message: 2
08-09 14:33:50.242  1926  2073 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-09 14:33:50.245  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 14:33:50.249  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:50.249  6792  6792 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-09 14:33:50.249  6792  6792 D LGBluetoothEventManager: [BTUI] clear device connection state
08-09 14:33:50.250  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-09 14:33:50.253  6792  6792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-09 14:33:50.263  1588  1588 D BluetoothAdapter: 265765047: getState() :  mService = null. Returning STATE_OFF
08-09 14:33:50.263  1588  1588 D BluetoothAdapter: 265765047: getState() :  mService = null. Returning STATE_OFF
,08-09 14:33:50.306  1036  1579 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7595 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-09 14:33:50.310  6792  6792 D DockEventReceiver: finishStartingService: stopping service
,08-09 14:33:50.368  7595  7595 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-09 14:33:50.369  7595  7595 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-09 14:33:50.369  7595  7595 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-09 14:33:50.370  7595  7595 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-09 14:33:50.391  7595  7595 D BluetoothAdapterApp: Loading JNI Library
,08-09 14:33:50.428  7595  7595 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@49a29d Instance Count = 1
,08-09 14:33:50.435  7595  7595 D BluetoothAdapterApp: onCreate
,08-09 14:33:50.460  7595  7595 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-09 14:33:50.460  7595  7595 D ProfileConfigQcom: Adding HeadsetService
08-09 14:33:50.460  7595  7595 D ProfileConfigQcom: [BTUI] A2dpService is supported
,08-09 14:33:50.460  7595  7595 D ProfileConfigQcom: Adding A2dpService
08-09 14:33:50.461  7595  7595 D ProfileConfigQcom: [BTUI] HidService is supported,
08-09 14:33:50.461  7595  7595 D ProfileConfigQcom: Adding HidService
,08-09 14:33:50.461  7595  7595 D ProfileConfigQcom: [BTUI] HealthService is supported
,08-09 14:33:50.461  7595  7595 D ProfileConfigQcom: Adding HealthService
,08-09 14:33:50.462  7595  7595 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-09 14:33:50.463  7595  7595 D ProfileConfigQcom: [BTUI] PanService is supported
,08-09 14:33:50.463  7595  7595 D ProfileConfigQcom: Adding PanService
08-09 14:33:50.463  7595  7595 D ProfileConfigQcom: [BTUI] GattService is supported
,08-09 14:33:50.463  7595  7595 D ProfileConfigQcom: Adding GattService
08-09 14:33:50.464  7595  7595 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
,08-09 14:33:50.464  7595  7595 D ProfileConfigQcom: Adding BluetoothMapService
08-09 14:33:50.464  7595  7595 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
,08-09 14:33:50.465  7595  7595 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-09 14:33:50.466  7595  7595 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-09 14:33:50.467  7595  7595 V BluetoothPbapReceiver: ***********state = 10
08-09 14:33:50.468  7595  7595 V LGMDMManagerInternal: Create singleton instance
,08-09 14:33:50.559  2140  2140 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-09 14:33:50.563  7595  7595 D LGBluetoothAPIServer: [BTUI] onCreate()
08-09 14:33:50.563  7595  7595 D LGBluetoothAPIServer: [BTUI] onBind()
,08-09 14:33:50.574  1926  1926 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,08-09 14:33:50.574  1926  2073 D LGBluetoothAPIService: Message: 100
08-09 14:33:50.574  1926  2073 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-09 14:33:50.577  6792  6792 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-09 14:33:50.581  6792  6792 D BluetoothPermissionRequest: onReceive
08-09 14:33:50.584  6792  6792 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-09 14:33:50.584  6792  6792 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-09 14:33:50.587  6792  6792 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-09 14:33:50.595  7595  7595 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-09 14:33:50.601  7595  7595 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:50.605  7595  7595 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-09 14:33:50.605  7595  7595 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-09 14:33:50.606  7595  7595 V BluetoothSapReceiver: SapReceiver onReceive 
,08-09 14:33:50.607  7595  7595 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:50.607  7595  7595 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-09 14:33:50.610  6858  6858 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-09 14:33:52.112  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
,08-09 14:33:52.112  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 14:33:52.231  1588  1588 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-09 14:33:52.249  1036  1366 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-09 14:33:52.339  1036  1099 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7624 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-09 14:33:52.342  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-09 14:33:52.343  1588  1588 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-09 14:33:52.345  1588  1588 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-09 14:33:52.346  1036  1036 D administrator: Handling package changes for user 0
,08-09 14:33:52.388  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-09 14:33:52.401  7624  7624 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-09 14:33:52.458  7624  7624 D LgDataFeature: LgDataFeature() Constructor: none
08-09 14:33:52.459  7624  7624 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-09 14:33:52.465  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-09 14:33:52.466  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-09 14:33:52.507  1036  1098 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-09 14:33:52.514  1036  1098 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-09 14:33:52.522  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-09 14:33:52.523  2454  2454 V GmsNetworkLocationProvi: DISABLE
,08-09 14:33:52.554  2454  2454 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-09 14:33:52.618  1036  1098 D LocationProviderProxy: applying state to connected service
,08-09 14:33:52.626  7624  7669 I Babel   : MmsConfig: mnc/mcc: 0/0
08-09 14:33:52.627  7624  7669 I Babel   : MmsConfig.loadMmsSettings
,08-09 14:33:52.632  7624  7669 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-09 14:33:52.632  7624  7669 I Babel   : MmsConfig.loadFromDatabase
,08-09 14:33:52.651  7624  7669 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,08-09 14:33:52.651  7624  7669 I Babel   : MmsConfig.loadFromResources
08-09 14:33:52.654  7624  7669 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-09 14:33:52.654  7624  7669 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-09 14:33:52.670  7624  7667 W AudioCapabilities: Unsupported mime audio/evrc
,08-09 14:33:52.673  7624  7667 W AudioCapabilities: Unsupported mime audio/qcelp
08-09 14:33:52.683  7624  7667 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-09 14:33:52.690  7624  7624 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-09 14:33:52.702  7624  7667 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-09 14:33:52.712  7624  7667 W AudioCapabilities: Unsupported mime audio/qcelp
08-09 14:33:52.714  7624  7667 W AudioCapabilities: Unsupported mime audio/evrc
08-09 14:33:52.725  1801  7672 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-09 14:33:52.725  1801  7672 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-09 14:33:52.730  6962  6962 I AppUp4:CustModeStarterReceiver: onReceive
,08-09 14:33:52.746  7624  7667 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-09 14:33:52.747  6962  6962 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@35eda23f
08-09 14:33:52.747  6962  6962 D AppUp4:CustFacade: isCustomizationCompleted : false
08-09 14:33:52.747  6962  6962 D AppUp4:CustFacade: isPhone : true
08-09 14:33:52.748  6962  6962 D AppUp4:CustModeStarterReceiver: begin check event
08-09 14:33:52.748  6962  6962 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-09 14:33:52.757  7624  7667 W VideoCapabilities: Unsupported mime video/divx
08-09 14:33:52.757  1801  4755 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-09 14:33:52.761  7624  7667 W VideoCapabilities: Unsupported mime video/divx311
08-09 14:33:52.763  7624  7667 W VideoCapabilities: Unsupported mime video/divx4
,08-09 14:33:52.773  7624  7667 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-09 14:33:52.785  1036  1561 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7675 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-09 14:33:52.789  1036  1956 I ActivityManager: Killing 6813:com.lge.sync/1000 (adj 15): empty #17
08-09 14:33:52.800  1036  1529 D WifiService: Client connection lost with reason: 4
,08-09 14:33:52.805  7624  7667 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-09 14:33:52.808  7624  7667 W AudioCapabilities: Unsupported mime audio/eac3
08-09 14:33:52.809  7624  7667 W AudioCapabilities: Unsupported mime audio/ac3
08-09 14:33:52.810  7624  7667 W AudioCapabilities: Unsupported mime audio/g726
08-09 14:33:52.810  7624  7667 W AudioCapabilities: Unsupported mime audio/wma-voice
08-09 14:33:52.811  7624  7667 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-09 14:33:52.812  7624  7667 W AudioCapabilities: Unsupported mime audio/adpcm
,08-09 14:33:52.814  7624  7667 W VideoCapabilities: Unsupported mime video/theora
08-09 14:33:52.815  7624  7667 W VideoCapabilities: Unsupported mime video/mjpg
08-09 14:33:52.913  1036  1579 W libprocessgroup: failed to open /acct/uid_1000/pid_6813/cgroup.procs: No such file or directory
,08-09 14:33:52.957  7675  7675 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-09 14:33:52.957  7675  7675 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-09 14:33:52.957  7675  7675 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-09 14:33:52.959  7675  7675 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,08-09 14:33:52.959  7675  7675 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-09 14:33:53.055  7675  7675 I SystemConfig: BUILD Country: EU
08-09 14:33:53.055  7675  7675 I SystemConfig: BUILD Operator: OPEN
,08-09 14:33:53.103  1036  1921 I ActivityManager: Killing 7000:com.lge.email/u0a23 (adj 15): empty #17
,08-09 14:33:53.144  1036  1530 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-09 14:33:53.167  1036  1928 W libprocessgroup: failed to open /acct/uid_10023/pid_7000/cgroup.procs: No such file or directory
,08-09 14:33:53.224  1036  1921 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7698 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
08-09 14:33:53.230  7675  7696 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-09 14:33:53.230  7675  7696 I SystemConfig: existFile = false
08-09 14:33:53.231  7675  7696 I SystemConfig: canReadFile = false
08-09 14:33:53.231  7675  7696 I SystemConfig: systemFeature RCS result false
08-09 14:33:53.231  7675  7696 D SystemConfig: refreshRcsSupport() :false
,08-09 14:33:53.316  7698  7698 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-09 14:33:53.317  7698  7698 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-09 14:33:53.317  7698  7698 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-09 14:33:53.318  7698  7698 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-09 14:33:53.440  7698  7698 I AppConfig: Total System Memory = 2995761152
,08-09 14:33:53.455  7698  7698 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-09 14:33:53.531  1036  1997 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7720 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-09 14:33:53.531  1036  1997 I ActivityManager: Killing 6881:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-09 14:33:53.652  1036  1561 W libprocessgroup: failed to open /acct/uid_10026/pid_6881/cgroup.procs: No such file or directory
,08-09 14:33:53.854  7720  7720 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-09 14:33:53.950  7720  7720 D LgDataFeature: LgDataFeature() Constructor: none
,08-09 14:33:53.950  7720  7720 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-09 14:33:54.017  7720  7720 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-09 14:33:54.039  7720  7720 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-09 14:33:54.040  7720  7720 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-09 14:33:54.059  7720  7720 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-09 14:33:54.059  7720  7720 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-09 14:33:54.078  1036  1579 I ActivityManager: Killing 6393:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-09 14:33:54.186  1036  1561 W libprocessgroup: failed to open /acct/uid_1000/pid_6393/cgroup.procs: No such file or directory
,08-09 14:33:54.197  4588  7765 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-09 14:33:54.211  2830  2848 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-09 14:33:54.214  2830  2848 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@c209c22 on behalf of 7720
08-09 14:33:54.238  1036  1956 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7766 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-09 14:33:54.269  7720  7720 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-09 14:33:54.282  7526  7565 D UEI.SmartControl: Internal timer expired: 1
,08-09 14:33:54.282  7526  7565 D UEI.SmartControl: unbind internal service
08-09 14:33:54.286  7526  7526 D UEI.SmartControl: Service.onUnbind: IControl
08-09 14:33:54.286  7526  7526 D UEI.SmartControl: Service.onDestroy
08-09 14:33:54.287  7526  7526 D UEI.SmartControl: Lock is in USE false
08-09 14:33:54.287  7526  7526 D UEI.SmartControl: unbind internal service
08-09 14:33:54.287  7526  7526 D serial_port: close(fd = 25)
08-09 14:33:54.288  7720  7720 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-09 14:33:54.292  7526  7526 I UEI.SmartControl: Serial port is closed.
08-09 14:33:54.292  7526  7526 I UEI.SmartControl: Serial port is closed.
08-09 14:33:54.292  7526  7526 D UEI.SmartControl: Blaster closed
08-09 14:33:54.292  7526  7526 D UEI.SmartControl: Shut down QS...
08-09 14:33:54.293  7526  7526 D UEI.SmartControl: Stopping QS lib
08-09 14:33:54.293  7526  7526 D UEI.SmartControl: QS lib stop result = true
08-09 14:33:54.293  7526  7526 D UEI.SmartControl: Stopped QS lib
08-09 14:33:54.293  7526  7526 D UEI.SmartControl: Stopped file observer...
08-09 14:33:54.293  7526  7526 D UEI.SmartControl: QS shutdown complete
,08-09 14:33:54.321  7766  7766 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-09 14:33:54.334  7766  7766 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-09 14:33:54.334  7766  7766 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-09 14:33:54.334  7766  7766 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-09 14:33:54.334  7766  7766 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-09 14:33:54.334  7766  7766 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-09 14:33:54.334  7766  7766 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-09 14:33:54.350  1036  1921 I ActivityManager: Killing 7044:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-09 14:33:54.365  1036  1051 W libprocessgroup: failed to open /acct/uid_10046/pid_7044/cgroup.procs: No such file or directory
,08-09 14:33:54.518  1036  1561 V SIM_STK : Menu title from STK is T-Mobile
,08-09 14:33:54.545  4588  7765 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 347 ms] updated apps [took 347 ms] 
,08-09 14:33:55.127  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-09 14:33:55.127  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a571627 added. We now have 6 listener(s)
,08-09 14:33:55.127  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-09 14:33:55.142  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 14:33:55.143  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8fe80d4 added. We now have 7 listener(s)
08-09 14:33:55.143  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 14:33:55.144  6669  6725 I System.out: IsBluetoothEnabled
08-09 14:33:55.145  1036  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 14:33:55.145  1036  1889 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-09 14:33:55.146  1036  1118 D BluetoothManagerService: Message: 2
08-09 14:33:55.149  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 14:33:55.151  1036  1997 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 14:33:55.151  1036  1997 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-09 14:33:55.169  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-09 14:33:55.170  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-09 14:33:55.170  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-09 14:33:55.170  1036  1118 D BluetoothManagerService: Message: 1
08-09 14:33:55.171  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-09 14:33:55.194  1036  1118 D BluetoothManagerService: Message: 20
08-09 14:33:55.195  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@371f128a:true
,08-09 14:33:55.199  7595  7595 D BluetoothAdapterState: make
08-09 14:33:55.203  7595  7595 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-09 14:33:55.204  7595  7595 I bluedroid-qcom: init
08-09 14:33:55.205  7595  7811 I BluetoothAdapterState: Entering OffState
08-09 14:33:55.205  7595  7595 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-09 14:33:55.206  7595  7595 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-09 14:33:55.206  7595  7595 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-09 14:33:55.206  7595  7595 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-09 14:33:55.206  7595  7595 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-09 14:33:55.208  7595  7595 I bluedroid-qcom: get_profile_interface socket
08-09 14:33:55.208  7595  7595 I bluedroid-qcom: get_profile_interface map_client
,08-09 14:33:55.212  7595  7815 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-09 14:33:55.205  7814  7814 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 14:33:55.218  7595  7815 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-09 14:33:55.205  7814  7814 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 14:33:55.228  7814  7814 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-09 14:33:55.228  7814  7814 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-09 14:33:55.228  7814  7814 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-09 14:33:55.232  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-09 14:33:55.233  1036  1118 D BluetoothManagerService: Message: 40
08-09 14:33:55.233  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-09 14:33:55.234  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-09 14:33:55.234  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-09 14:33:55.235  7595  7611 I bluedroid-qcom: config_hci_snoop_log
08-09 14:33:55.236  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-09 14:33:55.236  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-09 14:33:55.237  7814  7814 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-09 14:33:55.243  7814  7814 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-09 14:33:55.243  7814  7814 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-09 14:33:55.249  7595  7811 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-09 14:33:55.250  7595  7815 D BluetoothAdapterProperties: Name is: G3
08-09 14:33:55.250  7595  7811 D BluetoothAdapterProperties: Setting state to 11
08-09 14:33:55.250  7595  7811 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-09 14:33:55.251  1036  1118 D BluetoothManagerService: Message: 60
08-09 14:33:55.251  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-09 14:33:55.251  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-09 14:33:55.253  7595  7811 I LGBluetoothServiceJni: classInitNative: succeeds
08-09 14:33:55.259  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-09 14:33:55.262  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-09 14:33:55.264  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:55.269  6792  6792 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-09 14:33:55.275  7595  7595 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-09 14:33:55.275  7595  7595 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:55.275  7595  7595 V BluetoothPbapReceiver: ***********state = 11
,08-09 14:33:55.288  2140  2140 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-09 14:33:55.289  7595  7811 D BluetoothBondStateMachine: make
,08-09 14:33:55.296  7595  7811 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f1226a
08-09 14:33:55.297  7595  7828 I BluetoothBondStateMachine: StableState(): Entering Off State
08-09 14:33:55.296  7595  7811 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-09 14:33:55.297  7595  7811 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f1226a
08-09 14:33:55.297  7595  7811 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-09 14:33:55.297  7595  7811 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-09 14:33:55.302  7595  7811 E BluetoothAdapterService: File transfer profiles supported!!
,08-09 14:33:55.311  6792  6792 D BluetoothPermissionRequest: onReceive
08-09 14:33:55.312  7595  7811 E BluetoothAdapterService: File transfer profiles supported!!
,08-09 14:33:55.314  7595  7595 D HeadsetService: Received start request. Starting profile...
08-09 14:33:55.314  7595  7595 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-09 14:33:55.314  7595  7595 D LGBluetoothHfpAdapter: Version 1.6
08-09 14:33:55.317  7595  7595 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-09 14:33:55.318  7595  7595 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-09 14:33:55.318  6792  6792 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-09 14:33:55.319  7595  7595 D HeadsetStateMachine: make
,08-09 14:33:55.322  7595  7811 E BluetoothAdapterService: File transfer profiles supported!!
08-09 14:33:55.328  7595  7811 E BluetoothAdapterService: File transfer profiles supported!!
08-09 14:33:55.333  7595  7811 E BluetoothAdapterService: File transfer profiles supported!!
,08-09 14:33:55.339  7595  7811 E BluetoothAdapterService: File transfer profiles supported!!
08-09 14:33:55.344  7595  7811 E BluetoothAdapterService: File transfer profiles supported!!
08-09 14:33:55.359  7595  7595 D LgDataFeature: LgDataFeature() Constructor: none
08-09 14:33:55.359  7595  7595 D LgDataFeature: LgDataFeature() Constructor Done, null
08-09 14:33:55.360  7595  7811 V LGMDMManager: Create singleton instance
,08-09 14:33:55.364  7595  7595 D HeadsetStateMachine: max_hf_connections = 1
08-09 14:33:55.364  7595  7595 I bluedroid-qcom: get_profile_interface handsfree
08-09 14:33:55.364  7595  7811 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-09 14:33:55.366  7595  7595 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-09 14:33:55.366   315  2155 V AudioPolicyService: registerClient() client 0xb558aaa0, uid 1002
08-09 14:33:55.366   315  1373 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-09 14:33:55.366   315  1373 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-09 14:33:55.366   315  1373 V AudioPolicyManagerEx: getOutput() returns output 2
08-09 14:33:55.367  7595  7595 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-09 14:33:55.367   315   315 V AudioFlinger: registerClient() client 0xb5581760, pid 7595
08-09 14:33:55.367   315  1368 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-09 14:33:55.367   315  1368 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-09 14:33:55.368  1036  1051 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-09 14:33:55.368  1036  1051 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-09 14:33:55.368  1588  1606 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-09 14:33:55.368  1588  1606 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-09 14:33:55.368  1836  1852 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-09 14:33:55.368  1836  1852 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-09 14:33:55.368  3490  3506 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-09 14:33:55.368  3490  3506 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-09 14:33:55.368  7595  7612 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-09 14:33:55.368  7595  7612 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-09 14:33:55.368   315  1367 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-09 14:33:55.368   315  1367 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-09 14:33:55.368  1036  1975 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-09 14:33:55.368  1036  1975 V AudioSystem: ioConfigChanged() opening already existing output! 2
,08-09 14:33:55.369  1588  1613 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-09 14:33:55.369  1588  1613 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-09 14:33:55.369  7595  7611 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-09 14:33:55.369  1836  1851 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-09 14:33:55.369  1836  1851 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-09 14:33:55.369  7595  7611 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-09 14:33:55.369  3490  3507 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-09 14:33:55.369  3490  3507 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-09 14:33:55.369  7595  7595 V ToneGenerator: Create Track: 0xb4928a80
08-09 14:33:55.369  7595  7595 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-09 14:33:55.369  7595  7595 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-09 14:33:55.369   315  2155 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-09 14:33:55.369   315  2155 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-09 14:33:55.369   315  2155 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-09 14:33:55.369   315  2155 V AudioPolicyManagerEx: getOutput() returns output 2
08-09 14:33:55.369   315  1373 I AudioFlinger: isAudioPlaybackHookOn() false
08-09 14:33:55.369   315  3988 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-09 14:33:55.369   315  3988 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-09 14:33:55.370   315  3988 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-09 14:33:55.370   315  3988 V AudioPolicyManagerEx: getOutput() returns output 2
08-09 14:33:55.370  7595  7595 V AudioSystem: getLatency() output 2, latency 50
08-09 14:33:55.370  7595  7595 V AudioSystem: getFrameCount() output 2, frameCount 960
08-09 14:33:55.370  7595  7595 V AudioTrack: createTrack_l() output 2 afLatency 50
08-09 14:33:55.370   315  1372 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-09 14:33:55.370   315  1372 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-09 14:33:55.370   315  1372 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-09 14:33:55.370   315  1372 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-09 14:33:55.370   315  1372 V AudioFlinger: createTrack() lSessionId: 23
08-09 14:33:55.371  7595  7595 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-09 14:33:55.371   315  1372 V AudioFlinger: acquiring 23 from 7595, for 7595
08-09 14:33:55.371   315  1372 V AudioFlinger:  added new entry for 23
08-09 14:33:55.371  7595  7595 V ToneGenerator: ToneGenerator INIT OK, time: 143590
08-09 14:33:55.371  7595  7595 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f1226a
08-09 14:33:55.372  7595  7833 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-09 14:33:55.372  7595  7833 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-09 14:33:55.372  7595  7833 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-09 14:33:55.372  7595  7833 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-09 14:33:55.373   315   315 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7595
08-09 14:33:55.373   315   315 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-09 14:33:55.373   315   315 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-09 14:33:5,5.373   315   315 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-09 14:33:55.373   315   315 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-09 14:33:55.373   315   315 V voice   : voice_set_parameters: exit with code(0)
08-09 14:33:55.373   315   315 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-09 14:33:55.373   315   315 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-09 14:33:55.373   315   315 V msm8974_platform: platform_set_parameters: exit with code(0)
08-09 14:33:55.373   315   315 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-09 14:33:55.373   315   315 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-09 14:33:55.373   315   315 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-09 14:33:55.373  7595  7595 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f1226a
08-09 14:33:55.374  7595  7833 V ToneGenerator: ToneGenerator destructor
08-09 14:33:55.374  7595  7833 V ToneGenerator: stopTone
08-09 14:33:55.374  7595  7833 V ToneGenerator: Delete Track: 0xb4928a80
08-09 14:33:55.374  7595  7833 V AudioTrack: ~AudioTrack, releasing session id from 7595 on behalf of 7595
,08-09 14:33:55.374   315  1372 V AudioFlinger: releasing 23 from 7595 for 7595
,08-09 14:33:55.374   315  1372 V AudioFlinger:  decremented refcount to 0
08-09 14:33:55.374   315  1372 V AudioFlinger: purging stale effects
08-09 14:33:55.375   315  1372 V AudioPolicyService: AudioCommandThread() adding release output 2
08-09 14:33:55.375   315  1372 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-09 14:33:55.375   315  1270 V AudioPolicyService: AudioCommandThread() waking up
08-09 14:33:55.375   315  1270 V AudioPolicyService: AudioCommandThread() processing release output 2
08-09 14:33:55.375   315  1270 V AudioPolicyManager: releaseOutput() 2
08-09 14:33:55.375   315  1270 V AudioPolicyService: AudioCommandThread() going to sleep
08-09 14:33:55.375   315  1372 V AudioFlinger: PlaybackThread::Track destructor
08-09 14:33:55.375   315  1372 V AudioFlinger: removeClient_l() pid 7595, calling pid 315
08-09 14:33:55.375  7595  7595 D A2dpService: Received start request. Starting profile...
,08-09 14:33:55.376  7595  7595 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-09 14:33:55.377  7595  7595 V Avrcp   : make
08-09 14:33:55.377  7595  7595 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-09 14:33:55.377  7595  7595 I bluedroid-qcom: get_profile_interface avrcp
08-09 14:33:55.379  1036  1889 W Process : Unable to open /proc/7835/status
08-09 14:33:55.386  7595  7595 V AudioManager: registerRemoteController: size of Media player list: 0
08-09 14:33:55.387  7595  7595 E AudioManager: No RCC entry present to update
,08-09 14:33:55.387  7595  7595 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-09 14:33:55.391  7595  7595 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-09 14:33:55.392  7595  7595 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-09 14:33:55.392  7595  7595 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,08-09 14:33:55.395  7595  7595 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-09 14:33:55.523  1036  1975 V SIM_STK : Menu title from STK is T-Mobile
08-09 14:33:55.524  1036  1975 V SIM_STK : Menu title from STK is T-Mobile
,08-09 14:33:55.597  1036  1889 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-09 14:33:55.604  7595  7595 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-09 14:33:55.608  7595  7595 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-09 14:33:55.608  7595  7595 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-09 14:33:55.609  7595  7595 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-09 14:33:55.609  7595  7595 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-09 14:33:55.609  7595  7595 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-09 14:33:55.609  7595  7595 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-09 14:33:55.609  7595  7595 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-09 14:33:55.609  7595  7595 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-09 14:33:55.609  7595  7595 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-09 14:33:55.609  7595  7595 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-09 14:33:55.609  7595  7595 I BluetoothA2dpServiceJni: classInitNative
08-09 14:33:55.609  7595  7595 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-09 14:33:55.609  7595  7595 D A2dpStateMachine: make
08-09 14:33:55.613  7595  7595 I bluedroid-qcom: get_profile_interface a2dp
08-09 14:33:55.613  7595  7840 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-09 14:33:55.616  7595  7595 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-09 14:33:55.616  7595  7595 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-09 14:33:55.617  7595  7595 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f1226a
08-09 14:33:55.617  7595  7839 D A2dpStateMachine: Enter Disconnected: -2
08-09 14:33:55.619  7595  7595 I BluetoothHidServiceJni: classInitNative: succeeds
08-09 14:33:55.621  7595  7595 D HidService: Received start request. Starting profile...
08-09 14:33:55.621  7595  7595 I bluedroid-qcom: get_profile_interface hidhost
08-09 14:33:55.621  7595  7595 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f1226a
08-09 14:33:55.621  7595  7595 I BluetoothHealthServiceJni: classInitNative: succeeds
08-09 14:33:55.622  7595  7595 D HealthService: Received start request. Starting profile...
08-09 14:33:55.625  7595  7595 I bluedroid-qcom: get_profile_interface health
08-09 14:33:55.626  7595  7595 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-09 14:33:55.626  7595  7595 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f1226a
08-09 14:33:55.626  7595  7595 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-09 14:33:55.627  7595  7595 D PanService: Received start request. Starting profile...
08-09 14:33:55.628  7595  7595 D BluetoothPanServiceJni: initializeNative(L110): pan
08-09 14:33:55.628  7595  7595 I bluedroid-qcom: get_profile_interface pan
,08-09 14:33:55.636  7595  7595 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-09 14:33:55.636  7595  7595 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f1226a
08-09 14:33:55.637  7595  7595 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-09 14:33:55.640  7595  7595 D BtGatt.DebugUtils: handleDebugAction() action=null
08-09 14:33:55.641  7595  7595 D BtGatt.GattService: Received start request. Starting profile...
08-09 14:33:55.641  7595  7595 D BtGatt.GattService: start()
08-09 14:33:55.641  7595  7595 I bluedroid-qcom: get_profile_interface gatt
08-09 14:33:55.641  7595  7595 D BtGatt.AdvertiseManager: advertise manager created
,08-09 14:33:55.647  7595  7595 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f1226a
08-09 14:33:55.648  7595  7595 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f1226a
08-09 14:33:55.648  7595  7595 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-09 14:33:55.648  7595  7595 V BluetoothMapService: BluetoothMapBinder()
08-09 14:33:55.649  7595  7595 D BluetoothMapService: Received start request. Starting profile...
08-09 14:33:55.649  7595  7595 D BluetoothMapService: start()
08-09 14:33:55.651  7595  7595 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-09 14:33:55.651  7595  7595 D BluetoothMapEmailAppObserver: createReceiver()
08-09 14:33:55.652  7595  7595 D BluetoothMapEmailAppObserver: initObservers()
08-09 14:33:55.652  7595  7595 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-09 14:33:55.657  7595  7595 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f1226a
08-09 14:33:55.657  7595  7595 D HeadsetStateMachine: Proxy object connected
08-09 14:33:55.657  7595  7595 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-09 14:33:55.657  7595  7595 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-09 14:33:55.660  7595  7595 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-09 14:33:55.661  7595  7833 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-09 14:33:55.661  7595  7833 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-09 14:33:55.661  7595  7833 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-09 14:33:55.663  7595  7595 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-09 14:33:55.664  7595  7595 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:55.667  7595  7595 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-09 14:33:55.669  7595  7595 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-09 14:33:55.670  7595  7595 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-09 14:33:55.671  7595  7595 V PanService: [BTUI] SIM Extra State :ABSENT
08-09 14:33:55.673  7595  7595 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-09 14:33:55.673  7595  7595 V BluetoothMapService: Handler(): got msg=1
08-09 14:33:55.673  7595  7811 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-09 14:33:55.674  7595  7811 I bluedroid-qcom: enable
08-09 14:33:55.674  7595  7811 I bt_hci_bdroid: init
08-09 14:33:55.674  7595  7595 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-09 14:33:55.674  7595  7595 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-09 14:33:55.674  7595  7595 V BluetoothSapReceiver: SapReceiver onReceive 
08-09 14:33:55.674  7595  7595 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:55.674  7595  7595 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-09 14:33:55.675  7595  7811 I bt_vendor: bt-vendor : init
08-09 14:33:55.675  7595  7811 I bt_vendor: bt-vendor : get_bt_soc_type
08-09 14:33:55.675  7595  7811 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-09 14:33:55.675  7595  7811 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-09 14:33:55.675  7595  7811 D bt_userial_mct: userial_init
08-09 14:33:55.676  7595  7850 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-09 14:33:55.676  7595  7811 D bt_hci_bdroid: set_power 1
08-09 14:33:55.676  7595  7811 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-09 14:33:55.676  7595  7811 I bt_vendor: Starting hciattach daemon
08-09 14:33:55.676  7595  7811 I bt_vendor: try to set true
08-09 14:33:55.677  7595  7850 I bt-btu  : btu_task pending for preload complete event
08-09 14:33:55.665  7853  7853 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-09 14:33:55.665  7853  7853 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 14:33:55.696  7854  7854 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-09 14:33:55.755  7860  7860 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-09 14:33:55.763  7861  7861 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-09 14:33:55.804  7863  7863 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-09 14:33:55.815  7864  7864 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-09 14:33:55.826  7865  7865 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-09 14:33:55.836  7866  7866 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-09 14:33:55.868  7868  7868 I libmdmdetect: ESOC framework not supported
08-09 14:33:55.868  7868  7868 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-09 14:33:55.876  7868  7868 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-09 14:33:55.876  7868  7868 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-09 14:33:55.876  7868  7868 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-09 14:33:55.876  7868  7868 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-09 14:33:55.876  7868  7868 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-09 14:33:55.876  7868  7868 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-09 14:33:55.876  7868  7868 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-09 14:33:55.911  7868  7869 E QC-QMI  : qmi_client [7868] 15: failed to locate client data
08-09 14:33:55.912   464   464 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-09 14:33:55.912   464   464 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-09 14:33:56.006  7870  7870 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-09 14:33:56.020  7871  7871 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-09 14:33:56.031  7595  7811 I bt_vendor: bluetooth satus is on
08-09 14:33:56.031  7595  7811 D bt_hci_bdroid: preload
08-09 14:33:56.031  7595  7852 D bt_userial_mct: userial_open(port:0)
08-09 14:33:56.031  7595  7852 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-09 14:33:56.035  7595  7852 I bt_vendor: Done intiailizing UART
,08-09 14:33:56.043  7595  7852 I bt_vendor: Done intiailizing UART
08-09 14:33:56.043  7595  7852 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-09 14:33:56.043  7595  7852 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-09 14:33:56.043  7595  7873 D bt_userial_mct: Entering userial_read_thread()
08-09 14:33:56.043  7595  7850 I bt-btu  : btu_task received preload complete event
08-09 14:33:56.044  7595  7850 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-09 14:33:56.044  7595  7850 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-09 14:33:56.045  7595  7850 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-09 14:33:56.048  7595  7850 I         : BTE_InitTraceLevels -- TRC_HCI
08-09 14:33:56.048  7595  7850 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-09 14:33:56.048  7595  7850 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-09 14:33:56.048  7595  7850 I         : BTE_InitTraceLevels -- TRC_AVDT
08-09 14:33:56.048  7595  7850 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-09 14:33:56.048  7595  7850 I         : BTE_InitTraceLevels -- TRC_A2D
,08-09 14:33:56.048  7595  7850 I         : BTE_InitTraceLevels -- TRC_BNEP
08-09 14:33:56.048  7595  7850 I         : BTE_InitTraceLevels -- TRC_BTM
08-09 14:33:56.048  7595  7850 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-09 14:33:56.048  7595  7850 I         : BTE_InitTraceLevels -- TRC_GAP
08-09 14:33:56.048  7595  7850 I         : BTE_InitTraceLevels -- TRC_PAN
08-09 14:33:56.048  7595  7850 I         : BTE_InitTraceLevels -- TRC_SDP
08-09 14:33:56.048  7595  7850 I         : BTE_InitTraceLevels -- TRC_GATT
08-09 14:33:56.048  7595  7850 I         : BTE_InitTraceLevels -- TRC_SMP
08-09 14:33:56.048  7595  7850 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-09 14:33:56.048  7595  7850 I         : BTE_InitTraceLevels -- TRC_BTIF
08-09 14:33:56.139  7595  7850 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-09 14:33:56.139  7595  7850 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01b2061 
08-09 14:33:56.139  7595  7850 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01b2061 
,08-09 14:33:56.188  7595  7815 E bt-btif : Calling BTA_HhEnable
08-09 14:33:56.188  7595  7815 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-09 14:33:56.189  7595  7815 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-09 14:33:56.189  7595  7850 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-09 14:33:56.189  7595  7850 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
,08-09 14:33:56.189  7595  7850 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-09 14:33:56.192  7595  7815 D BluetoothAdapterProperties: Name is: G3
08-09 14:33:56.192  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-09 14:33:56.193  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-09 14:33:56.197  7595  7815 D BluetoothAdapterProperties: Scan Mode:20
08-09 14:33:56.197  7595  7815 D BluetoothAdapterProperties: Discoverable Timeout:120
08-09 14:33:56.198  7595  7815 D bt_hci_bdroid: postload
08-09 14:33:56.199  7595  7852 D bt_hci_bdroid: Used up Tx Cmd credits
08-09 14:33:56.200  7595  7815 D bte_conf: Device ID record 1 : primary
08-09 14:33:56.200  7595  7815 D bte_conf:   vendorId            = 00c4
08-09 14:33:56.200  7595  7815 D bte_conf:   vendorIdSource      = 0001
08-09 14:33:56.200  7595  7815 D bte_conf:   product             = 13a1
08-09 14:33:56.200  7595  7815 D bte_conf:   version             = 1000
08-09 14:33:56.200  7595  7815 D bte_conf:   clientExecutableURL = 
08-09 14:33:56.200  7595  7815 D bte_conf:   serviceDescription  = 
08-09 14:33:56.200  7595  7815 D bte_conf:   documentationURL    = 
08-09 14:33:56.201  7595  7815 D bte_conf: bte_load_did_conf no section named DID2.
08-09 14:33:56.202  7595  7850 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-09 14:33:56.202  7595  7850 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-09 14:33:56.202  7595  7850 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-09 14:33:56.203  7595  7852 D bt_hci_bdroid: Used up Tx Cmd credits
08-09 14:33:56.203  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:56.204  7595  7811 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-09 14:33:56.204  7595  7811 D BluetoothAdapterProperties: ScanMode =  20
08-09 14:33:56.204  7595  7811 D BluetoothAdapterProperties: State =  11
08-09 14:33:56.204  7595  7811 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-09 14:33:56.204  7595  7811 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-09 14:33:56.204  7595  7811 D BluetoothAdapterProperties: Setting state to 12
08-09 14:33:56.205  7595  7811 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-09 14:33:56.205  1036  1118 D BluetoothManagerService: Message: 60
08-09 14:33:56.205  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-09 14:33:56.205  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-09 14:33:56.205  7595  7811 I BluetoothAdapterState: Entering On State
08-09 14:33:56.206  7595  7815 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-09 14:33:56.206  7595  7815 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-09 14:33:56.206  7595  7852 D bt_hci_bdroid: Used up Tx Cmd credits
08-09 14:33:56.206  7595  7852 D bt_hci_bdroid: Used up Tx Cmd credits
08-09 14:33:56.195  7875  7875 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 14:33:56.206  1836  2737 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 14:33:56.195  7875  7875 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-09 14:33:56.210  7595  7852 D bt_hci_bdroid: Used up Tx Cmd credits
08-09 14:33:56.210  7595  7852 D bt_hci_bdroid: Used up Tx Cmd credits
08-09 14:33:56.214  7595  7873 E bt_mct  : hci lib postload completed
08-09 14:33:56.214  7595  7811 D LGBluetoothServiceAdapter: [BTUI] OnState
08-09 14:33:56.214  7595  7811 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-09 14:33:56.214  7595  7811 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-09 14:33:56.216  7595  7811 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-09 14:33:56.221  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-09 14:33:56.222  7595  7850 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-09 14:33:56.222  7595  7850 W bt-smp  : Plain text(LSB ~ MSB) = d9 23 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-09 14:33:56.222  7595  7850 W bt-smp  : Encrypted text(LSB ~ MSB) = 39 b7 7a 2f 75 f5 21 d4 1f 54 8c ac 3b 58 cb 70 
08-09 14:33:56.222  7595  7850 W bt-btm  : Stopping oneshot timer
08-09 14:33:56.225  1836  1836 D BluetoothHeadset: Proxy object connected
08-09 14:33:56.226  6792  6902 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-09 14:33:56.228  7595  7815 D BluetoothAdapterProperties: Discoverable Timeout:120
08-09 14:33:56.229  7595  7815 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-09 14:33:56.234  1036  1036 D BluetoothA2dp: Proxy object connected
08-09 14:33:56.236  6792  6902 D BluetoothA2dp: onBluetoothStateChange: up=true
08-09 14:33:56.238  6792  6792 D BluetoothInputDevice: Proxy object connected
08-09 14:33:56.238  6792  6792 D HidProfile: Bluetooth service connected
08-09 14:33:56.239  6792  6810 D BluetoothPbap: onBluetoothStateChange: up=true
,08-09 14:33:56.241  6792  6792 D BluetoothA2dp: Proxy object connected
08-09 14:33:56.241  6792  6792 D A2dpProfile: Bluetooth service connected
08-09 14:33:56.243  6792  6902 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 14:33:56.245  1836  1852 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 14:33:56.247  1836  1836 D BluetoothHeadset: Proxy object connected
08-09 14:33:56.247  1836  1851 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 14:33:56.248  6792  6792 D BluetoothHeadset: Proxy object connected
08-09 14:33:56.248  6792  6792 D HeadsetProfile: Bluetooth service connected
08-09 14:33:56.249  7595  7850 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-09 14:33:56.249  7595  7850 W bt-smp  : Plain text(LSB ~ MSB) = 7f 44 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-09 14:33:56.249  7595  7850 W bt-smp  : Encrypted text(LSB ~ MSB) = e8 a2 9a 5e 8f ee 6b 72 14 43 c6 88 af d7 c2 2b 
08-09 14:33:56.249  7595  7850 W bt-btm  : Stopping oneshot timer
08-09 14:33:56.251  1836  1836 D BluetoothHeadset: Proxy object connected
08-09 14:33:56.251  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-09 14:33:56.253  1036  1036 D BluetoothHeadset: Proxy object connected
08-09 14:33:56.253  6792  6810 D BluetoothPan: onBluetoothStateChange on: true
08-09 14:33:56.253  6792  6810 D BluetoothPan: onBluetoothStateChange call bindService
08-09 14:33:56.257  7595  7811 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-09 14:33:56.258  6792  6902 D BluetoothMap: onBluetoothStateChange: up=true
08-09 14:33:56.259  6792  6792 D BluetoothPan: BluetoothPAN Proxy object connected
08-09 14:33:56.259  6792  6792 D PanProfile: Bluetooth service connected
08-09 14:33:56.263  7595  7850 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-09 14:33:56.263  7595  7850 W bt-smp  : Plain text(LSB ~ MSB) = 48 54 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-09 14:33:56.263  7595  7850 W bt-smp  : Encrypted text(LSB ~ MSB) = 5f 92 20 d6 d0 d1 86 7f e2 d4 0f db 2c 56 49 bc 
08-09 14:33:56.263  7595  7850 W bt-btm  : Stopping oneshot timer
08-09 14:33:56.264  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-09 14:33:56.266  6792  6792 D BluetoothMap: Proxy object connected
08-09 14:33:56.267  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-09 14:33:56.270  7881  7881 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-09 14:33:56.272  1926  1926 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:56.273  1588  1588 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-09 14:33:56.274  6792  6792 D MapProfile: Bluetooth service connected
08-09 14:33:56.274  6792  6792 D BluetoothMap: getConnectedDevices()
,08-09 14:33:56.275  1926  2073 D LGBluetoothAPIService: Message: 1
08-09 14:33:56.275  1926  2073 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-09 14:33:56.275  1926  2073 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-09 14:33:56.276  1926  2073 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-09 14:33:56.276  7595  7850 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-09 14:33:56.276  7595  7850 W bt-smp  : Plain text(LSB ~ MSB) = 06 0d 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-09 14:33:56.276  7595  7850 W bt-smp  : Encrypted text(LSB ~ MSB) = 8f ee 65 64 13 40 c9 a4 bc 62 bb 34 ee 6b 47 5e 
08-09 14:33:56.276  7595  7850 W bt-btm  : Stopping oneshot timer
08-09 14:33:56.280  7595  7611 V BluetoothMapService: getConnectedDevices()
,08-09 14:33:56.282  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:56.282  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:56.282  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:56.282  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 14:33:56.282  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 14:33:56.282  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:56.282  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:56.282  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 14:33:56.284  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 14:33:56.287  7595  7850 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-09 14:33:56.287  7595  7850 W bt-smp  : Plain text(LSB ~ MSB) = fd 0b 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-09 14:33:56.287  7595  7850 W bt-smp  : Encrypted text(LSB ~ MSB) = dc 54 09 b2 f4 99 a6 9b 67 41 2b 69 c7 96 b8 22 
08-09 14:33:56.287  7595  7850 W bt-btm  : Stopping oneshot timer
,08-09 14:33:56.436  1036  1889 I art     : Explicit concurrent mark sweep GC freed 26632(1319KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.946ms total 165.890ms
,08-09 14:33:56.440  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-09 14:33:56.440  1036  1118 D BluetoothManagerService: Message: 40
08-09 14:33:56.440  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-09 14:33:56.446  7595  7595 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:56.446  7595  7595 D BluetoothMapService: STATE_ON
08-09 14:33:56.454  6792  6792 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-09 14:33:56.458  6792  6792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-09 14:33:56.461  7595  7595 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f1226a
08-09 14:33:56.461  7595  7595 V BluetoothPbapService: Pbap Service onCreate
08-09 14:33:56.462  7595  7595 V BluetoothPbapService: Starting PBAP service
08-09 14:33:56.463  7595  7595 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-09 14:33:56.463  7595  7595 V BluetoothPbapService: Pbap Service onBind
08-09 14:33:56.465  7595  7595 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:56.465  7595  7595 V BluetoothPbapService: state: 12
08-09 14:33:56.465  7595  7595 V BluetoothMapService: Handler(): got msg=1
08-09 14:33:56.466  7595  7595 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-09 14:33:56.467  7595  7595 V BluetoothPbapService: Handler(): got msg=1
08-09 14:33:56.467  7595  7595 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-09 14:33:56.469  7595  7888 D BluetoothMapMasInstance: MAS initSocket()
08-09 14:33:56.469  7595  7595 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-09 14:33:56.470  7595  7595 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:56.470  7595  7595 V BluetoothPbapReceiver: ***********state = 12
08-09 14:33:56.471  7595  7888 D BluetoothMapMasInstance:   masId = 00
08-09 14:33:56.471  7595  7888 D BluetoothMapMasInstance:   msgTypes = 0e
08-09 14:33:56.471  7595  7888 D BluetoothMapMasInstance:   masName = SMS/MMS
08-09 14:33:56.471  7595  7888 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-09 14:33:56.473  7595  7889 V BluetoothPbapService: Pbap Service initSocket
,08-09 14:33:56.473  2140  2140 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-09 14:33:56.474  2140  2140 D c       : Getting all permits...
08-09 14:33:56.474  2140  2140 D a       : Opening database...
08-09 14:33:56.478  2140  2140 D a       : Opening database auth.proximity.permit_store...
08-09 14:33:56.479  2140  2140 D a       : Closing database...
08-09 14:33:56.481  6792  6792 D DockEventReceiver: finishStartingService: stopping service
08-09 14:33:56.482  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 14:33:56.482  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 14:33:56.485  6792  6792 D BluetoothPbap: Proxy object connected
08-09 14:33:56.485  6792  6792 D PbapServerProfile: Bluetooth service connected
08-09 14:33:56.486  7595  7889 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 14:33:56.488  7595  7888 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 14:33:56.494  7595  7888 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-09 14:33:56.494  7595  7889 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
,08-09 14:33:56.495  7595  7888 V BluetoothMapMasInstance: Succeed to create listening socket 
08-09 14:33:56.495  7595  7888 D BluetoothMapMasInstance: Accepting socket connection...
08-09 14:33:56.495  7595  7815 D BluetoothAdapterProperties: Scan Mode:21
08-09 14:33:56.496  7595  7815 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-09 14:33:56.496  7595  7889 V BluetoothPbapService: Succeed to create listening socket 
08-09 14:33:56.496  7595  7889 V BluetoothPbapService: Accepting socket connection...
08-09 14:33:56.499  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:56.504  6792  6792 D BluetoothPermissionRequest: onReceive
08-09 14:33:56.506  6792  6792 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-09 14:33:56.509  6792  6792 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-09 14:33:56.516  7595  7595 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-09 14:33:56.518  7595  7595 I LGBluetoothOppAdapter: [BTUI] startOppService()
,08-09 14:33:56.524  7595  7595 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-09 14:33:56.540  7595  7595 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-09 14:33:56.541  7595  7595 V BtOppService: onCreate
,08-09 14:33:56.546  7595  7595 V BluetoothOppNotification: send message
08-09 14:33:56.549  7595  7595 V BtOppService: Starting RfcommListener
08-09 14:33:56.555  7595  7595 D BluetoothOppPreference: Dumping Names:  
08-09 14:33:56.555  7595  7595 D BluetoothOppPreference: {}
08-09 14:33:56.555  7595  7595 D BluetoothOppPreference: Dumping Channels:  
08-09 14:33:56.555  7595  7595 D BluetoothOppPreference: {}
08-09 14:33:56.557  7595  7595 V BtOppService: onStartCommand
,08-09 14:33:56.558  7595  7898 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-09 14:33:56.562  7595  7595 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:56.563  7595  7595 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-09 14:33:56.568  7595  7595 V BluetoothOppNotification: new notify threadi!
08-09 14:33:56.570  7595  7595 V BluetoothOppNotification: send delay message
08-09 14:33:56.572  7595  7595 V BtOppService: start RfcommListener
08-09 14:33:56.574  7595  7895 V BtOppService: Deleted complete outbound shares, number =  0
08-09 14:33:56.576  7595  7595 V BtOppService: RfcommListener started
,08-09 14:33:56.576  7595  7899 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-09 14:33:56.577  7595  7898 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-09 14:33:56.578  7595  7900 V BtOppRfcommListener: Starting RFCOMM listener....
08-09 14:33:56.580  1036  1853 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 14:33:56.582  7595  7895 V BtOppService: Deleted complete inbound failed shares, number = 0
08-09 14:33:56.583  7595  7900 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 14:33:56.583  7595  7895 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-09 14:33:56.585  7595  7900 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-09 14:33:56.585  7595  7900 V BtOppRfcommListener: Started RFCOMM listener....
08-09 14:33:56.586  7595  7900 I BtOppRfcommListener: Accept thread started.
08-09 14:33:56.586  7595  7895 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f70746 on behalf of 
08-09 14:33:56.587  7595  7898 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a899d07 on behalf of 
08-09 14:33:56.588  7595  7900 V BtOppRfcommListener: Accepting connection...
08-09 14:33:56.588  7595  7899 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@34da2e34 on behalf of 
,08-09 14:33:56.591  7595  7899 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-09 14:33:56.593  7595  7898 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-09 14:33:56.593  7595  7898 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-09 14:33:56.593  7595  7899 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-09 14:33:56.595  7595  7898 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b31b45d on behalf of 
08-09 14:33:56.596  7595  7898 V BluetoothOppNotification: update too frequent, put in queue
08-09 14:33:56.596  7595  7899 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@260c51d2 on behalf of 
,08-09 14:33:56.597  7595  7595 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f1226a
08-09 14:33:56.597  7595  7898 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-09 14:33:56.598  7595  7595 V BluetoothFtpService: Ftp Service onCreate
08-09 14:33:56.598  7595  7595 I BluetoothFtpService: Ftp Service onCreate
08-09 14:33:56.598  7595  7595 V BluetoothFtpService: Ftp Service onStartCommand
08-09 14:33:56.598  7595  7595 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:56.599  7595  7595 V BluetoothFtpService: Starting Listening on sockets
,08-09 14:33:56.599  7595  7595 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-09 14:33:56.599  7595  7595 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-09 14:33:56.599  7595  7595 V BluetoothSapReceiver: SapReceiver onReceive 
08-09 14:33:56.600  7595  7595 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:56.600  7595  7595 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-09 14:33:56.600  7595  7595 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-09 14:33:56.601  7595  7899 V BluetoothOppNotification: outbound: succ-0  fail-0
08-09 14:33:56.604  7595  7899 V BluetoothOppNotification: outbound notification was removed.
08-09 14:33:56.604  7595  7595 V BtOppService: ContentObserver received notification
08-09 14:33:56.604  7595  7899 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-09 14:33:56.604  7595  7595 V BtOppService: ContentObserver received notification
08-09 14:33:56.604  7595  7595 V BluetoothFtpService: Handler(): got msg=1
,08-09 14:33:56.606  7595  7901 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-09 14:33:56.607  7595  7595 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-09 14:33:56.607  7595  7901 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-09 14:33:56.607  7595  7595 V BluetoothFtpService: Ftp Service initSocket
08-09 14:33:56.609  7595  7901 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@305f9a0 on behalf of 
08-09 14:33:56.611  7595  7899 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d5a3959 on behalf of 
08-09 14:33:56.611  7595  7901 V BluetoothOppNotification: update too frequent, put in queue
08-09 14:33:56.612  7595  7899 V BluetoothOppNotification: inbound: succ-0  fail-0
08-09 14:33:56.613  7595  7901 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-09 14:33:56.613  7595  7899 V BluetoothOppNotification: inbound notification was removed.
08-09 14:33:56.613  7595  7899 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-09 14:33:56.614  1036  1997 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 14:33:56.616  7595  7595 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-09 14:33:56.618  7595  7595 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-09 14:33:56.618  7595  7899 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20b9b91e on behalf of 
08-09 14:33:56.618  7595  7595 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-09 14:33:56.622  7595  7902 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-09 14:33:56.636  7595  7595 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f1226a
08-09 14:33:56.636  7595  7595 V BluetoothSapService: Sap Service onCreate
,08-09 14:33:56.638  7595  7595 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:56.638  7595  7595 V BluetoothSapService: state: 12
08-09 14:33:56.638  7595  7595 V BluetoothSapService: Starting SAP server process
08-09 14:33:56.640  7595  7595 V BluetoothSapService: SAP Service startRfcommListenerThread
08-09 14:33:56.635  7903  7903 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 14:33:56.635  7903  7903 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 14:33:56.642  7595  7904 V BluetoothSapService: Sap Service initRfcommSocket
08-09 14:33:56.644  1036  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 14:33:56.645  7595  7904 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 14:33:56.646  7595  7904 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-09 14:33:56.646  7595  7904 V BluetoothSapService: Succeed to create listening socket 
08-09 14:33:56.646  7595  7904 V BluetoothSapService: Accepting socket connection...
08-09 14:33:56.662  7903  7903 V BT_SAP  : Event pipe created
08-09 14:33:56.662  7903  7903 V BT_SAP  : create_server_socket qcom.sap.server
08-09 14:33:56.662  7903  7903 V BT_SAP  : created socket fd 6
,08-09 14:33:57.198  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:57.198  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:57.198  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:57.198  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 14:33:57.198  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 14:33:57.198  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:57.198  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:57.198  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 14:33:57.212  6669  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 14:33:57.217  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 14:33:57.217  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1795a27d added. We now have 8 listener(s)
08-09 14:33:57.218  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-09 14:33:57.228  1036  2010 D WifiServiceImplEx: setWifiEnabled: false pid=6669, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-09 14:33:57.228  1036  2010 D WifiService: setWifiEnabled: false pid=6669, uid=10118
08-09 14:33:57.228  1036  2010 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-09 14:33:57.232  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:57.233  1036  1890 D WifiServiceImplEx: setWifiEnabled: true pid=6669, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-09 14:33:57.234  1036  1890 D WifiService: setWifiEnabled: true pid=6669, uid=10118
08-09 14:33:57.234  1036  1890 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-09 14:33:57.252  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-09 14:33:57.252  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-09 14:33:57.252  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-09 14:33:57.257  1036  1524 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-09 14:33:57.257  1036  1524 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-09 14:33:57.259  1036  1524 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-09 14:33:57.259  1036  1524 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-09 14:33:57.260  1036  1524 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
,08-09 14:33:57.260  1036  1524 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-09 14:33:57.260  1036  1524 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-09 14:33:57.260  1036  1524 E WifiHW  : unknown target_country: EU , set to default
08-09 14:33:57.260  1036  1524 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
,08-09 14:33:57.260  1036  1524 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-09 14:33:57.260  1036  1524 I WifiUtil: gEnableBmps=1
08-09 14:33:57.574  7595  7595 V BluetoothOppNotification: new notify threadi!
08-09 14:33:57.574  7595  7595 V BluetoothOppNotification: send delay message
,08-09 14:33:57.595  7595  7917 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-09 14:33:57.622  7595  7917 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2044492a on behalf of 
,08-09 14:33:57.623  7595  7917 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-09 14:33:57.628  7595  7917 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-09 14:33:57.629  7595  7917 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@bda231b on behalf of 
08-09 14:33:57.630  7595  7917 V BluetoothOppNotification: outbound: succ-0  fail-0
08-09 14:33:57.632  7595  7917 V BluetoothOppNotification: outbound notification was removed.
08-09 14:33:57.632  7595  7917 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-09 14:33:57.633  7595  7917 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@4755cb8 on behalf of 
08-09 14:33:57.634  7595  7917 V BluetoothOppNotification: inbound: succ-0  fail-0
08-09 14:33:57.635  7595  7917 V BluetoothOppNotification: inbound notification was removed.
08-09 14:33:57.635  7595  7917 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-09 14:33:57.636  7595  7917 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1688ba91 on behalf of 
,08-09 14:33:57.960   306   894 D SoftapController: Softap fwReload - Ok
,08-09 14:33:58.001  1036  1524 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (738ms)
,08-09 14:33:58.012  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-09 14:33:58.012  1036  1118 D Tethering: InitialState.processMessage what=4
,08-09 14:33:58.026   306   894 D CommandListener: Setting iface cfg
08-09 14:33:58.026   306   894 D CommandListener: Trying to bring down wlan0
08-09 14:33:58.032   306   894 D CommandListener: Clearing all IP addresses on wlan0
08-09 14:33:58.033  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-09 14:33:58.045  1036  1524 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-09 14:33:58.055  7925  7925 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-09 14:33:58.055  7925  7925 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 14:33:58.077  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-09 14:33:58.077  6792  6792 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-09 14:33:58.078  6792  6792 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-09 14:33:58.078  6792  6792 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-09 14:33:58.078  1036  1524 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-09 14:33:58.078  1036  1524 E WifiStateMachine: useWiFiOffloading() : false
08-09 14:33:58.078  1036  1524 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-09 14:33:58.079  1036  1524 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-09 14:33:58.079  1036  1524 D WifiMonitor: connecting to supplicant
08-09 14:33:58.082  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-09 14:33:58.085  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:58.087  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-09 14:33:58.096  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:58.096  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-09 14:33:58.098  6792  6792 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-09 14:33:58.098  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-09 14:33:58.098  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-09 14:33:58.099  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-09 14:33:58.099  6792  6792 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-09 14:33:58.099  6792  6792 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-09 14:33:58.102  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-09 14:33:58.103  6792  6792 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-09 14:33:58.103  6792  6792 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-09 14:33:58.103  6792  6792 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-09 14:33:58.103  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-09 14:33:58.104  6792  6792 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-09 14:33:58.104  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-09 14:33:58.104  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-09 14:33:58.104  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-09 14:33:58.104  6792  6792 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-09 14:33:58.104  6792  6792 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-09 14:33:58.106  7925  7925 I wpa_supplicant: Successfully initialized wpa_supplicant
08-09 14:33:58.142  7925  7925 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-09 14:33:58.142  7925  7925 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-09 14:33:58.155  1036  1890 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7944 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-09 14:33:58.185  7925  7925 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-09 14:33:58.232  7925  7925 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-09 14:33:58.236  7925  7925 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-09 14:33:58.237  1036  1524 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-09 14:33:58.237  1036  1524 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-09 14:33:58.237  1036  7964 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
,08-09 14:33:58.238  1036  7964 D WifiMonitor: Dropping event because (p2p0) is stopped
08-09 14:33:58.238  1036  1524 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-09 14:33:58.238  1036  1524 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-09 14:33:58.238  1036  1524 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-09 14:33:58.239  1036  1524 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-09 14:33:58.239  1036  1524 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-09 14:33:58.240  1036  1524 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-09 14:33:58.240  1036  1524 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-09 14:33:58.240  1036  1524 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-09 14:33:58.241  1036  1524 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-09 14:33:58.241  1036  1524 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-09 14:33:58.241  1036  1524 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-09 14:33:58.252  1036  7964 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-09 14:33:58.252  1036  7964 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-09 14:33:58.252  7925  7925 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-09 14:33:58.252  1036  7964 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-09 14:33:58.252  1036  7964 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-09 14:33:58.252  1036  7964 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-09 14:33:58.252  1036  7964 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,08-09 14:33:58.271  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:58.271  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:58.271  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:58.271  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 14:33:58.271  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 14:33:58.271  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:58.271  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:58.271  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 14:33:58.272  1036  1579 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7966 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-09 14:33:58.273  6669  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-09 14:33:58.274  1036  1524 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-09 14:33:58.274  1036  1524 E WifiStateMachine: useWiFiOffloading() : false
08-09 14:33:58.274  1036  1524 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-09 14:33:58.274  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:58.274  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:58.274  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:58.274  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:58.274  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-09 14:33:58.275  1036  1524 D WifiNative-wlan0: doBoolean: SET update_config 1
08-09 14:33:58.275  1036  1524 D WifiNative-wlan0: SET update_config 1: returned true
08-09 14:33:58.275  1036  1524 D WifiConfigStore: Loading config and enabling all networks 
08-09 14:33:58.275  1036  1524 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-09 14:33:58.276  1036  1524 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-09 14:33:58.276  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:58.277  1926  1926 D WfdService: Waiting for WifiP2p enabling
08-09 14:33:58.278  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-09 14:33:58.278  1036  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-09 14:33:58.283  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:58.283  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:58.283  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:58.283  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 14:33:58.283  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 14:33:58.283  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:58.283  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:58.283  6669  6669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 14:33:58.283  6669  6725 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-09 14:33:58.284  6669  6725 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-09 14:33:58.286  6669  6725 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2a20cd09 Bundle[{}]
08-09 14:33:58.289  6669  6725 I io.jxcore.node.LifeCycleMonitor: start: OK
08-09 14:33:58.290  6669  6669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-09 14:33:58.290  6669  6725 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-09 14:33:58.291  6669  6725 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-09 14:33:58.292  6669  6725 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-09 14:33:58.292   345   345 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 489us total 21.217ms
08-09 14:33:58.292  6669  6725 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-09 14:33:58.293  6669  6725 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-09 14:33:58.294  1036  1524 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-09 14:33:58.299  6669  6725 I System.out: Running OutgoingSocketThread
08-09 14:33:58.300  6669  7982 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 862)
,08-09 14:33:58.306  1036  1524 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-09 14:33:58.306  1036  1524 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-09 14:33:58.306  1036  1524 D WifiStateMachine: enableVerboseLogging : level 2
08-09 14:33:58.307  1036  1524 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-09 14:33:58.308  6669  7982 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 42835
08-09 14:33:58.308  6669  7982 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-09 14:33:58.309  1036  1524 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-09 14:33:58.309  1036  1524 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-09 14:33:58.309  1036  1524 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-09 14:33:58.309  1036  1524 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-09 14:33:58.309  1036  1524 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-09 14:33:58.310  1036  1524 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-09 14:33:58.310  1036  1524 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-09 14:33:58.310  1036  1524 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-09 14:33:58.310  1036  1524 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-09 14:33:58.311  1036  1524 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-09 14:33:58.311  1036  1524 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-09 14:33:58.311  1036  1524 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-09 14:33:58.311   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 439us total 18.497ms
08-09 14:33:58.312  1036  1524 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,08-09 14:33:58.314  1036  1524 D WifiStateMachine: Setting OUI to DA-A1-19
08-09 14:33:58.314  1036  1524 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-09 14:33:58.314  1036  1524 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-09 14:33:58.314  1036  1524 D WifiNative-HAL: Setting external_sim to 1
08-09 14:33:58.314  1036  1524 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-09 14:33:58.315  1036  1524 D WifiNative-wlan0: SET external_sim 1: returned true
08-09 14:33:58.315  1036  1524 I WifiNative-HAL: startHal
08-09 14:33:58.315  1036  1524 D wifi    : setting scan oui 0xaf721300
,08-09 14:33:58.315  1036  1524 D WifiStateMachine: Setting OUI to DA-A1-19
08-09 14:33:58.315  1036  1524 I WifiNative-HAL: startHal
08-09 14:33:58.315  1036  1524 D wifi    : setting scan oui 0xaf721300
08-09 14:33:58.315  1036  1524 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-09 14:33:58.316  1036  1524 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
,08-09 14:33:58.316  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-09 14:33:58.316  7925  7925 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
,08-09 14:33:58.316  1036  1524 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-09 14:33:58.316  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
,08-09 14:33:58.317  7925  7925 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-09 14:33:58.317  1036  1524 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-09 14:33:58.317  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-09 14:33:58.317  7925  7925 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-09 14:33:58.318  1036  1524 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-09 14:33:58.318  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-09 14:33:58.318  7925  7925 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-09 14:33:58.318  1036  1524 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-09 14:33:58.318  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-09 14:33:58.318  7925  7925 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-09 14:33:58.319  1036  1524 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-09 14:33:58.319  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-09 14:33:58.319  7925  7925 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-09 14:33:58.319  1036  1524 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-09 14:33:58.319  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-09 14:33:58.319  7925  7925 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-09 14:33:58.320  1036  1524 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-09 14:33:58.321  1036  1524 E WifiNative: : [146,525,073 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-09 14:33:58.321  1036  1524 D WifiNative-wlan0: doBoolean: RECONNECT
08-09 14:33:58.321  1036  1524 D WifiNative-wlan0: RECONNECT: returned true
08-09 14:33:58.321  1036  1524 D WifiNative-wlan0: doString: [STATUS]
08-09 14:33:58.321  1036  7964 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-09 14:33:58.321  1036  7964 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-09 14:33:58.322  1036  1524 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-09 14:33:58.322  1036  1524 D WifiNative-wlan0: doBoolean: SET ps 1
08-09 14:33:58.322  1036  1524 D WifiNative-wlan0: SET ps 1: returned true
08-09 14:33:58.322  1036  1518 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:58.324  1926  1926 D WfdsService: Supplicant Connection state is changed : true
08-09 14:33:58.324  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-09 14:33:58.324  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-09 14:33:58.324  1926  2263 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-09 14:33:58.324  1926  2263 D WfdsService: Set the WFDS Monitor: true
08-09 14:33:58.324  1926  2263 D WfdsMonitor: WfdsMonitorThread create
08-09 14:33:58.324  1926  2263 D WfdsMonitor: WFDS Monitor is created and started
08-09 14:33:58.324  1926  2263 D WfdsService: WiFi: Supplicant connection re-established
08-09 14:33:58.325   306   894 D CommandListener: Setting iface cfg
08-09 14:33:58.325  1036  1542 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:58.325  1036  1542 I WifiNative-HAL: startHal
,08-09 14:33:58.325   306   894 D CommandListener: Trying to bring up p2p0
,08-09 14:33:58.325  1036  1542 D wifi    : getting scan capabilities on interface[1] = 0xaf721300
08-09 14:33:58.325  1036  1542 D wifi    : failed to get capabilities : -3
08-09 14:33:58.325  1036  1542 E WifiScanningService: could not get scan capabilities
08-09 14:33:58.325  1036  1543 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:58.325  1036  1518 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-09 14:33:58.325  1036  1518 D LGWifiP2pService: P2pEnablingState
08-09 14:33:58.325  1036  1518 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
,08-09 14:33:58.325  1036  1518 D LGWifiP2pService: P2p socket connection successful
08-09 14:33:58.325  1036  1518 D LGWifiP2pService: P2pEnabledState
08-09 14:33:58.325  1036  1524 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-09 14:33:58.326  1036  1524 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-09 14:33:58.326  1036  1524 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-09 14:33:58.327  1036  1524 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-09 14:33:58.327  1926  1926 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
,08-09 14:33:58.327  1926  1926 D WfdsService: WifiP2pState is changed : true
08-09 14:33:58.327  1926  2263 D WfdsService: Receive the WFDS_ENABLE Method
08-09 14:33:58.327  1926  2263 D WfdsService: Set the WFDS Monitor: true
08-09 14:33:58.327  1926  2263 D WfdsService: Connected to the supplicant for wfds
08-09 14:33:58.327  1926  2263 D WfdsJNI : doCommand: WFDS_SET TRUE
08-09 14:33:58.327  1926  2263 E CtrlSupplicant: Not connected to wap_supplicant - "WFDS_SET TRUE" command dropped.
08-09 14:33:58.327  1926  2263 D WfdsJNI : wfds_send_command: [WFDS_SET TRUE] failed
,08-09 14:33:58.327  1926  2263 D WfdsService: selectPreferredScanChannel [36]
08-09 14:33:58.327  1926  2263 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-09 14:33:58.328  7624  7624 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,08-09 14:33:58.328   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 348us total 16.241ms
08-09 14:33:58.328  1036  1518 D LGWifiP2pService: sending p2p connection changed broadcast
08-09 14:33:58.329  1036  1518 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-09 14:33:58.329  1926  7985 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
,08-09 14:33:58.329  1036  1518 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-09 14:33:58.329  1036  1518 D WifiNative-p2p0: doBoolean: SET device_name G3
08-09 14:33:58.330  1036  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=146534  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-09 14:33:58.330  1036  1518 D WifiNative-p2p0: SET device_name G3: returned true
08-09 14:33:58.330  1036  1518 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-09 14:33:58.330  1036  1518 D LGWifiP2pService: before postfix = G3
,08-09 14:33:58.330  1036  1518 D WifiServerServiceExt: postfix byte check : 2
08-09 14:33:58.330  1036  1518 D LGWifiP2pService: after postfix = G3
08-09 14:33:58.330  1036  1518 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
,08-09 14:33:58.330  1036  1518 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-09 14:33:58.330  1036  1518 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-09 14:33:58.330  1036  1518 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-09 14:33:58.330  1036  1518 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-09 14:33:58.331  1036  1518 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-09 14:33:58.331  1036  1518 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
,08-09 14:33:58.331  1926  7985 E CtrlSupplicant: Succeed to open control connection
08-09 14:33:58.331  1036  1518 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-09 14:33:58.331  1926  7985 E CtrlSupplicant: Succeed to open monitor connection
08-09 14:33:58.331  1036  1518 D WifiNative-HAL: p2pGetDeviceAddress
08-09 14:33:58.331  1926  7985 D WfdsMonitor: Supplicant connection established
,08-09 14:33:58.331  1036  1518 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-09 14:33:58.331  1926  2263 D WfdsService: Received the Event that WfdsMonitor is connected to supplicant
,08-09 14:33:58.334  1036  1518 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-09 14:33:58.334  1036  1518 D WifiNative-p2p0: doBoolean: P2P_FLUSH
,08-09 14:33:58.334  1036  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=146539  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-09 14:33:58.335  1036  1524 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-09 14:33:58.335  1926  1926 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-09 14:33:58.335  1036  1524 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-09 14:33:58.335  1926  1926 D WfdsService: isConnected: false
08-09 14:33:58.336  1036  1524 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-09 14:33:58.336  1036  1524 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-09 14:33:58.336  7925  7925 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-09 14:33:58.337  1036  1518 D WifiNative-p2p0: P2P_FLUSH: returned true
08-09 14:33:58.337  1036  1518 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-09 14:33:58.337  1036  1518 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-09 14:33:58.337  1036  1518 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-09 14:33:58.337  1036  1518 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-09 14:33:58.337  1036  1518 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-09 14:33:58.338  1036  1524 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-09 14:33:58.339  1036  1524 E WifiStateMachine:  ConnectModeState what:132096 -100 0
,08-09 14:33:58.339  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 14:33:58.339  1036  1524 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-09 14:33:58.339  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 14:33:58.339  1036  1524 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-09 14:33:58.341  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:58.341  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:58.341  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-09 14:33:58.342  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:58.343  1926  1926 I WfdStateTracker: handleP2pThisDeviceChanged
08-09 14:33:58.343  1926  1926 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-09 14:33:58.343  1926  1926 D WfdsService: Update P2p Interface State: 3
08-09 14:33:58.343  7925  7925 E wpa_supplicant: disconnect_rssi_lvl: -100
08-09 14:33:58.343  1036  1518 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-09 14:33:58.343  1036  1518 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-09 14:33:58.344  1036  1524 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-09 14:33:58.344  1036  1524 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-09 14:33:58.344  7944  7963 W FormManager: Network not available. Please check & try again.
08-09 14:33:58.344  1036  1518 D LGWifiP2pService: InactiveState
08-09 14:33:58.344  1036  1518 D LGWifiP2pService: InactiveState{ when=-7ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:58.344  1036  1524 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-09 14:33:58.344  1036  1518 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:58.344  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-09 14:33:58.344  1036  1518 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-09 14:33:58.345  7925  7925 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-09 14:33:58.345  7925  7925 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 14:33:58.345  1036  7964 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-09 14:33:58.345  1036  7964 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 14:33:58.345  1036  7964 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 14:33:58.345  1036  7964 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 14:33:58.345  7925  7925 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-09 14:33:58.346  7925  7925 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 14:33:58.346  7925  7925 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 14:33:58.347  1926  7985 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-09 14:33:58.347  1926  7985 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-09 14:33:58.347  1036  1524 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-09 14:33:58.347  1036  7964 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-09 14:33:58.347  1036  7964 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 14:33:58.347  1036  7964 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 14:33:58.347  1036  7964 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 14:33:58.347  1036  7964 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-09 14:33:58.347  7925  7925 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-09 14:33:58.348  7925  7925 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 14:33:58.348  7925  7925 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-09 14:33:58.348  7925  7925 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 14:33:58.348  1926  7985 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-09 14:33:58.349  1036  1518 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-09 14:33:58.349  1926  7985 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-09 14:33:58.349  1036  1518 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:58.349  1036  1518 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:58.349  1036  1518 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:58.349  7925  7925 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 14:33:58.349  1036  7964 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 14:33:58.349  1036  7964 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 14:33:58.349  1036  7964 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 14:33:58.349  1036  7964 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-09 14:33:58.349  1036  7964 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 14:33:58.349  1036  7964 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 14:33:58.349  1036  7964 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-09 14:33:58.349  1036  7964 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-09 14:33:58.349  1036  7964 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 14:33:58.349  1036  7964 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 14:33:58.349  1036  7964 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 14:33:58.349  1036  7964 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-09 14:33:58.349  1926  7985 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-09 14:33:58.349  1036  7964 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 14:33:58.350  1036  7964 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 14:33:58.350  1036  7964 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-09 14:33:58.350  1036  1524 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-09 14:33:58.350  1036  1518 D LGWifiP2pService: InactiveState{ when=-6ms what=139285 arg2=6 target=co,m.android.internal.util.StateMachine$SmHandler }
08-09 14:33:58.350  1036  1518 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:58.350  1036  1518 D LGWifiP2pService: DefaultState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:58.350  1036  1524 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-09 14:33:58.350  1036  1524 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-09 14:33:58.350  1036  1518 D LGWifiP2pService: InactiveState{ when=-4ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:58.351  1036  1518 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:58.351  1036  1518 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:58.351  1036  1518 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:58.351  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-09 14:33:58.351  1036  1518 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:58.351  7925  7925 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-09 14:33:58.351  1036  1518 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:58.351  7925  7925 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-09 14:33:58.351  1926  2263 W WfdsService: DefaultState - msg [9441285] is not handled
08-09 14:33:58.351  1036  7964 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-09 14:33:58.351  1036  1518 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:58.351  1036  7964 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-09 14:33:58.351  1036  1518 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:58.352  1036  7964 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-09 14:33:58.352  1036  7964 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-09 14:33:58.352  1036  1036 E WifiServerServiceExt: No p2p device connected
08-09 14:33:58.352  1036  1524 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-09 14:33:58.352  1036  1524 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-09 14:33:58.352  1036  1524 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-09 14:33:58.352  1036  1524 D WifiNative-wlan0: doBoolean: SCAN
08-09 14:33:58.352  1036  1524 D WifiNative-wlan0: SCAN: returned false
08-09 14:33:58.353  1036  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=146557  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-09 14:33:58.354  1036  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=146559  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-09 14:33:58.355  1036  1524 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-09 14:33:58.355  1036  1524 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-09 14:33:58.355  7944  7965 V FormManager: Network unavailable.
08-09 14:33:58.355  1036  1524 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-09 14:33:58.356  1036  1524 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-09 14:33:58.356  1036  1524 E WifiStateMachine:  DefaultSt,ate P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-09 14:33:58.356  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:58.357  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:58.357  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-09 14:33:58.357  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 14:33:58.357  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-09 14:33:58.357  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 14:33:58.357  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-09 14:33:58.361  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 14:33:58.361  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 14:33:58.362  7944  7965 V FormManager: Network unavailable.
08-09 14:33:58.363  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:58.373  1036  1928 I ActivityManager: Killing 7065:com.android.chrome/u0a57 (adj 15): empty #17
,08-09 14:33:58.379  7966  7966 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-09 14:33:58.401  1036  1956 W libprocessgroup: failed to open /acct/uid_10057/pid_7065/cgroup.procs: No such file or directory
,08-09 14:33:58.405  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-09 14:33:58.409  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:33:58.410  1036  2010 I ActivityManager: Killing 7089:com.lge.drmservice/u0a62 (adj 15): empty #17
08-09 14:33:58.443  1036  1889 W libprocessgroup: failed to open /acct/uid_10062/pid_7089/cgroup.procs: No such file or directory
,08-09 14:33:58.472  7966  7966 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-09 14:33:58.477  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-09 14:33:58.486  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-09 14:33:58.501  7944  7989 W FormManager: Network not available. Please check & try again.
,08-09 14:33:58.511  7944  7990 V FormManager: Network unavailable.
,08-09 14:33:58.520  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-09 14:33:58.520  4305  4305 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-09 14:33:58.523  7944  7990 V FormManager: Network unavailable.
,08-09 14:33:58.526  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-09 14:33:58.531  4305  4305 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-09 14:33:58.545  4305  7991 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-09 14:33:58.552  4305  7992 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-09 14:33:58.552  4305  7992 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-09 14:33:58.618  1036  2010 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7993 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-09 14:33:58.764  7925  7925 E wpa_supplicant: USIM:  scard_init function
,08-09 14:33:58.764  7925  7925 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-09 14:33:58.764  1036  7964 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-09 14:33:58.765  1036  7964 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-09 14:33:58.765  1036  7964 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-09 14:33:58.765  1036  7964 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-09 14:33:58.765  1036  7964 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-09 14:33:58.765  1036  7964 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-09 14:33:58.766  1036  7964 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-09 14:33:58.768  1036  1524 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-09 14:33:58.769  1036  1524 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-09 14:33:58.771  1036  1524 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-09 14:33:58.772  1036  1524 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-09 14:33:58.772  1036  1524 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-09 14:33:58.782  1036  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=146987  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-09 14:33:58.790  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:58.790  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-09 14:33:58.790  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-09 14:33:58.792  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 14:33:58.792  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 14:33:58.793  1036  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=146997  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-09 14:33:58.793  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:58.795  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 14:33:58.795  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-09 14:33:58.813  7993  7993 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-09 14:33:58.814  7993  7993 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-09 14:33:58.822  7993  7993 V [BNRBootReceiver]: Boot Receiver Return
08-09 14:33:58.822  7993  7993 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-09 14:33:58.879  7925  7925 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-09 14:33:58.882  1036  7964 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-09 14:33:58.882  1036  7964 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-09 14:33:58.883  1036  7964 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-09 14:33:58.883  1036  7964 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-09 14:33:58.883  1036  7964 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-09 14:33:58.883  1036  7964 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-09 14:33:58.889  1036  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=147093  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-09 14:33:58.890  1036  1890 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8011 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-09 14:33:58.891  1036  1890 I ActivityManager: Killing 7119:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-09 14:33:58.892  1036  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=147096  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-09 14:33:58.893  1036  1524 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=147097
,08-09 14:33:58.893  1036  1524 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=147098
,08-09 14:33:58.894  1036  1524 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=147099
08-09 14:33:58.894  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=147099
08-09 14:33:58.895  1036  1524 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=147100
08-09 14:33:58.895  1036  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=147100  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-09 14:33:58.899  7925  7925 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-09 14:33:58.899  7925  7925 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-09 14:33:58.900  1036  7964 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-09 14:33:58.900  1036  7964 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-09 14:33:58.901  1036  7964 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-09 14:33:58.901  1036  7964 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-09 14:33:58.901  1036  7964 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-09 14:33:58.901  1036  7964 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-09 14:33:58.901  1036  7964 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-09 14:33:58.901  1036  7964 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-09 14:33:58.901  1036  7964 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-09 14:33:58.901  1036  7964 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-09 14:33:58.942  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-09 14:33:58.943  1036  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=147148  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-09 14:33:58.944  1036  1524 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=147149  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-09 14:33:58.945  1036  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=147150  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-09 14:33:58.945  1036  1524 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=147150
08-09 14:33:58.946  1036  1524 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=147151
,08-09 14:33:58.946  1036  1524 D WifiNative-wlan0: doString: [STATUS]
08-09 14:33:58.947  1036  7964 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-09 14:33:58.947  1036  7964 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-09 14:33:58.947  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:58.948  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:58.948  1036  1524 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-09 14:33:58.948  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-09 14:33:58.950  1036  1524 I WifiServiceExtension: setVHTCapabilityType  : false
08-09 14:33:58.950  1036  1889 W libprocessgroup: failed to open /acct/uid_10085/pid_7119/cgroup.procs: No such file or directory
08-09 14:33:58.951  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 14:33:58.951  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 14:33:58.953  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:58.953  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:58.953  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-09 14:33:58.953  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 14:33:58.953  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
,08-09 14:33:58.957  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:58.959  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 14:33:58.959  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 14:33:58.959  1036  1524 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-09 14:33:58.959  1036  1524 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-09 14:33:58.960  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:58.965  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:58.965  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:58.965  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-09 14:33:58.967  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:58.967  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:58.967  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-09 14:33:58.976  1036  1524 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-09 14:33:58.976  1036  1530 D ConnectivityService: Got NetworkAgent Messenger
08-09 14:33:58.976  1036  1524 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-09 14:33:58.976  1036  1524 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-09 14:33:58.976  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-09 14:33:58.976  1036  1530 D ConnectivityService: NetworkAgent connected
08-09 14:33:58.977  1036  1524 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-09 14:33:58.977  1036  1524 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-09 14:33:58.977  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 14:33:58.977  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 14:33:58.979  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:58.981  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 14:33:58.981  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 14:33:58.982  1036  1524 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-09 14:33:58.982  1036  1524 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-09 14:33:58.982  1036  1524 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-09 14:33:58.982  1036  1524 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-09 14:33:58.982  1036  1524 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-09 14:33:58.984  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:58.987  1036  1524 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-09 14:33:58.989   306   894 D CommandListener: Setting iface cfg
08-09 14:33:58.994  8011  8011 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-09 14:33:58.995  1036  1524 E WifiStateMachine: Start Dhcp Watchdog 3
,08-09 14:33:58.996  1036  1524 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=147200  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-09 14:33:58.997  1036  1524 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=147201  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-09 14:33:58.998  1036  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=147202  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-09 14:33:58.999  1036  8029 D DhcpStateMachine: StoppedState
08-09 14:33:58.999  1036  8029 D DhcpStateMachine: StoppedState{ when=-4ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:58.999  1036  8029 D DhcpStateMachine: WaitBeforeStartState
08-09 14:33:59.000  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 14:33:59.000  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-09 14:33:59.001  1036  1524 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-09 14:33:59.002  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-09 14:33:59.002  1036  1524 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-09 14:33:59.003  1036  1524 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-09 14:33:59.003  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-09 14:33:59.004  1036  1524 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-09 14:33:59.004  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 14:33:59.004  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-09 14:33:59.005  1036  1524 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=147209  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-09 14:33:59.005  1036  1524 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=147210  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-09 14:33:59.006  1036  1524 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=147210  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-09 14:33:59.007  1036  1524 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14121] from screen [on:0 period:1867223775] gl rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-09 14:33:59.008  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1867223776] gl rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-09 14:33:59.008  1036  1524 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-09 14:33:59.012  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:59.015  1036  1530 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-09 14:33:59.015  1036  1524 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:59.016  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:59.016  1036  1524 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:59.017  1036  1524 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:59.017  8011  8011 D PluginManager: init()
08-09 14:33:59.017  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:59.017  1036  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:59.018  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-09 14:33:59.018  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 14:33:59.018  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-09 14:33:59.019  1036  1524 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=131,0,0
08-09 14:33:59.019  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=131,0,0
08-09 14:33:59.019  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-09 14:33:59.019  7925  7925 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,08-09 14:33:59.020  1036  1524 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-09 14:33:59.020  1036  1524 D WifiNative-wlan0: doBoolean: SET ps 0
08-09 14:33:59.021  1036  1524 D WifiNative-wlan0: SET ps 0: returned true
08-09 14:33:59.021  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-09 14:33:59.021  7925  7925 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-09 14:33:59.021  1036  1524 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-09 14:33:59.022  1036  1518 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3523403 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:59.022  1036  1518 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3523403 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:59.022  1036  1524 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-09 14:33:59.022  1036  8029 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:59.022  1036  1524 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-09 14:33:59.022  1036  8029 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-09 14:33:59.022  1036  1524 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-09 14:33:59.023   306   894 D CommandListener: Setting iface cfg
08-09 14:33:59.024   306   894 D CommandListener: Trying to bring up wlan0
08-09 14:33:59.025  1036  1524 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-09 14:33:59.026  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-09 14:33:59.026  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-09 14:33:59.027  1036  1524 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:59.028  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:59.028  1036  1524 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:59.029  1036  1524 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:59.030  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:59.030  1036  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-09 14:33:59.031  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-09 14:33:59.031  1036  1524 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-09 14:33:59.032  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-09 14:33:59.032  1036  1518 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:59.032  1036  1518 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:59.032  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-09 14:33:59.032  7925  7925 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-09 14:33:59.033  1036  1524 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
,08-09 14:33:59.033  1036  1524 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
,08-09 14:33:59.033  7925  7925 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-09 14:33:59.034  1036  1524 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-09 14:33:59.034  1036  1524 D WifiNative-wlan0: doBoolean: SET ps 1
08-09 14:33:59.050  1036  1524 D WifiNative-wlan0: SET ps 1: returned true
,08-09 14:33:59.050  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-09 14:33:59.051  1036  1524 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-09 14:33:59.051  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-09 14:33:59.052  1036  1524 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-09 14:33:59.052  1036  1530 D ConnectivityService: ignoring duplicate network state non-change
08-09 14:33:59.056  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 14:33:59.056  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 14:33:59.057  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:59.057  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:59.057  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:59.057  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-09 14:33:59.060  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-09 14:33:59.061  1036  1530 D ConnectivityService: Adding iface wlan0 to network 102
08-09 14:33:59.062  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:59.062  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:59.062  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-09 14:33:59.063  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-09 14:33:59.066  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:59.066  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:59.066  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-09 14:33:59.068  1926  1926 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-09 14:33:59.069  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-09 14:33:59.072  1036  1524 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-09 14:33:59.073  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:59.073  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:59.073  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-09 14:33:59.077  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-09 14:33:59.077  1588  1588 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-09 14:33:59.078  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:59.080  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 14:33:59.080  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-09 14:33:59.080  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:59.091  1588  1588 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-09 14:33:59.091  1588  1588 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
,08-09 14:33:59.092  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:59.105  1036  1530 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-09 14:33:59.105  1036  1530 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-09 14:33:59.106  1036  1530 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-09 14:33:59.107   306   894 E Netd    : netlink response contains error (File exists)
08-09 14:33:59.107  1036  1530 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-09 14:33:59.108  1036  1530 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-09 14:33:59.108  1036  1530 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-09 14:33:59.108  1036  1530 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-09 14:33:59.109  1036  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-09 14:33:59.109  1036  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-09 14:33:59.109  1036  1530 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-09 14:33:59.109  1036  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-09 14:33:59.109  1036  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-09 14:33:59.109  1036  8028 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:59.109  1036  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 14:33:59.109  1036  8028 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-09 14:33:59.109  1036  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-09 14:33:59.109  1036  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 14:33:59.109  1036  8028 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-09 14:33:59.109  1036  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-09 14:33:59.109  1036  1530 D ConnectivityService: currentScore = 0, newScore = 20
08-09 14:33:59.109  1036  1530 D ConnectivityService:    accepting network in place of null
08-09 14:33:59.109  1036  8028 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-09 14:33:59.109  1036  1530 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 14:33:59.110  1036  1524 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 14:33:59.110  1036  1524 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-09 14:33:59.111  1036  1530 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,08-09 14:33:59.111  1036  1530 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-09 14:33:59.111  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-09 14:33:59.112  1836  1836 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 14:33:59.112  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-09 14:33:59.113   306  8033 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-09 14:33:59.115  1036  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:59.115  1036  1530 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-09 14:33:59.115  1036  1530 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-09 14:33:59.116  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-09 14:33:59.116  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-09 14:33:59.116  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-09 14:33:59.116  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-09 14:33:59.119  1036  1530 D ConnectivityService: validation of new default Network = false
08-09 14:33:59.119  1036  1530 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-09 14:33:59.119  1036  1530 D DSQN    : enableDataServiceNotify 
08-09 14:33:59.119  1036  1530 D DSQN    : start dsqn bin
08-09 14:33:59.125  1036  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-09 14:33:59.125  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 14:33:59.125  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 14:33:59.115  8034  8034 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 14:33:59.115  8034  8034 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 14:33:59.126  1036  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 14:33:59.126  1588  2058 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-09 14:33:59.136  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-09 14:33:59.136  1036  1517 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-09 14:33:59.136  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:59.137  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:59.137  8034  8034 E DSQN    : DSQN ssw
,08-09 14:33:59.162   306  8033 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-09 14:33:59.194   306  8033 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-09 14:33:59.224  1036  8029 D DhcpStateMachine: DHCPV4 request on wlan0
08-09 14:33:59.225  1036  8029 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,08-09 14:33:59.225  1036  8029 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-09 14:33:59.215  8038  8038 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-09 14:33:59.215  8038  8038 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-09 14:33:59.234  8038  8038 I dhcpcd  : version 5.5.6 starting
08-09 14:33:59.236  8038  8038 E dhcpcd  : get_duid: m
,08-09 14:33:59.236  8038  8038 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-09 14:33:59.236  8038  8038 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-09 14:33:59.239   306   893 D LGDataListener: argv[0]=dsqncommand
08-09 14:33:59.239   306   893 D LGDataListener: argv[1]=wlan0
,08-09 14:33:59.239   306   893 D LGDataListener: argv[2]=1
08-09 14:33:59.239   306   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-09 14:33:59.241  1036  1116 D DSQN    : DSQM DsqnNotification wlan0  1
08-09 14:33:59.241  1036  1116 D DSQN    : start to monitor internet connection
,08-09 14:33:59.283  1036  8028 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Aug 2016 12:33:59 GMT], X-Android-Received-Millis=[1470746039283], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470746039239]}
08-09 14:33:59.283  1036  8028 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-09 14:33:59.283  1036  8028 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,08-09 14:33:59.284  1036  1530 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-09 14:33:59.284  1036  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-09 14:33:59.284  1036  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-09 14:33:59.284  1036  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 14:33:59.284  1036  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-09 14:33:59.284  1036  1530 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-09 14:33:59.284  1036  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-09 14:33:59.284  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 14:33:59.284  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 14:33:59.285  1036  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 14:33:59.285  1036  1530 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 14:33:59.285  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-09 14:33:59.286  1836  1836 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 14:33:59.286  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-09 14:33:59.286  1036  1524 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 14:33:59.286  1036  1524 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-09 14:33:59.287  1588  2058 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-09 14:33:59.300  6669  6725 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 863)
08-09 14:33:59.300  6669  6725 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 863)
08-09 14:33:59.304  6669  6725 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 868)
08-09 14:33:59.304  8038  8038 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-09 14:33:59.305  8038  8038 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-09 14:33:59.305  8038  8038 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-09 14:33:59.305  8038  8038 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-09 14:33:59.305  8038  8038 D dhcpcd  : wlan0: sending REQUEST (xid 0xa9b4c32d), next in 4.82 seconds
08-09 14:33:59.305  6669  6725 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-09 14:33:59.305  6669  6725 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 869)
08-09 14:33:59.308  1588  1588 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-09 14:33:59.309  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:59.309  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 14:33:59.309  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@be67572 added. We now have 2 listener(s)
08-09 14:33:59.310  1036  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 14:33:59.311  1588  1588 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-09 14:33:59.313  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-09 14:33:59.313  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 14:33:59.313  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 14:33:59.313  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 14:33:59.313  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1114edc3 added. We now have 9 listener(s)
08-09 14:33:59.313  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 14:33:59.313  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-09 14:33:59.315  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 14:33:59.318  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 14:33:59.318  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:59.318  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:59.318  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 14:33:59.318  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 14:33:59.318  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 14:33:59.318  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 14:33:59.318  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-09 14:33:59.319  6669  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 14:33:59.319  6669  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 14:33:59.319  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 14:33:59.320  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27dee979 added. We now have 3 listener(s)
08-09 14:33:59.320  1036  1975 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 14:33:59.323  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-09 14:33:59.323  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 14:33:59.323  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 14:33:59.323  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 14:33:59.323  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31a276be added. We now have 10 listener(s)
08-09 14:33:59.323  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 14:33:59.324  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:59.324  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:59.324  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:59.324  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:59.324  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:59.324  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 14:33:59.324  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 14:33:59.324  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@be67572 removed from the list
08-09 14:33:59.324  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:59.324  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1114edc3 removed from the list
08-09 14:33:59.325  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:59.326  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:59.326  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:59.326  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:59.327  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:59.327  6669  6725 D org.tha,liproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:59.328  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:59.328  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:59.328  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:59.328  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1114edc3 not in the list
08-09 14:33:59.328  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:59.328  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:59.329  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:59.329  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:59.329  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:59.329  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31a276be removed from the list
08-09 14:33:59.329  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:59.329  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:59.329  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:59.329  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 14:33:59.329  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27dee979 removed from the list
08-09 14:33:59.330  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 14:33:59.330  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@374ea31f added. We now have 2 listener(s)
08-09 14:33:59.330  1036  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-09 14:33:59.332  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-09 14:33:59.332  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 14:33:59.332  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 14:33:59.332  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 14:33:59.332  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29166c added. We now have 9 listener(s)
08-09 14:33:59.332  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 14:33:59.333  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-09 14:33:59.334  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 14:33:59.337  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 14:33:59.337  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:59.337  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:59.337  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 14:33:59.337  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 14:33:59.337  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 14:33:59.337  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 14:33:59.337  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 14:33:59.338  6669  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 14:33:59.338  6669  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 14:33:59.338  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 14:33:59.338  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@278b40ca added. We now have 3 listener(s)
08-09 14:33:59.339  1036  1928 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 14:33:59.340  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:59.341  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-09 14:33:59.341  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 14:33:59.341  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 14:33:59.341  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 14:33:59.341  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a44523b added. We now have 10 listener(s)
08-09 14:33:59.341  6669  6725 D ,org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 14:33:59.341  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-09 14:33:59.341  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-09 14:33:59.342  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-09 14:33:59.342  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 14:33:59.342  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-09 14:33:59.343  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:59.345  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-09 14:33:59.346  1036  1889 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 14:33:59.350  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-09 14:33:59.350  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-09 14:33:59.351  8038  8038 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-09 14:33:59.353  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-09 14:33:59.353  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 14:33:59.355  6669  6725 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-09 14:33:59.355  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:59.355  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:59.356  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:59.357  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:59.357  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:59.357  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:59.357  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:59.357  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 14:33:59.357  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 14:33:59.357  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@374ea31f removed from the list
08-09 14:33:59.357  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-09 14:33:59.357  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29166c removed from the list
08-09 14:33:59.357  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:59.357  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:59.358  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:59.358  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:59.359  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:59.359  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:59.359  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:59.359  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29166c not in the list
08-09 14:33:59.359  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:59.359  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:59.359  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:59.360  6669  6725 D BluetoothLeScanner: could not find callback wrapper
08-09 14:33:59.360  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 14:33:59.360  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:59.360  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:59.360  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a44523b removed from the list
08-09 14:33:59.360  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:59.360  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:59.360  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:59.360  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 14:33:59.360  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@278b40ca removed from the list
08-09 14:33:59.361  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 14:33:59.361  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c849f96 added. We now have 2 listener(s)
08-09 14:33:59.361  1036  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 14:33:59.364  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-09 14:33:59.364  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 14:33:59.364  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdent,ityString: 
08-09 14:33:59.364  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 14:33:59.364  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@111bd717 added. We now have 9 listener(s)
08-09 14:33:59.364  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 14:33:59.365  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-09 14:33:59.367  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 14:33:59.371  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 14:33:59.371  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:59.371  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:59.371  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 14:33:59.371  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 14:33:59.371  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 14:33:59.371  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 14:33:59.371  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 14:33:59.372  6669  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 14:33:59.372  6669  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 14:33:59.372  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 14:33:59.372  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@223924ed added. We now have 3 listener(s)
08-09 14:33:59.372  1036  2010 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 14:33:59.374  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:59.376  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:59.376  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-09 14:33:59.376  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 14:33:59.376  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 14:33:59.376  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 14:33:59.376  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37e31f22 added. We now have 10 listener(s)
08-09 14:33:59.377  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 14:33:59.377  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-09 14:33:59.377  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-09 14:33:59.377  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-09 14:33:59.377  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-09 14:33:59.377  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 14:33:59.378  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-09 14:33:59.380  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-09 14:33:59.380  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 14:33:59.381  8038  8038 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-09 14:33:59.381  8038  8038 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-09 14:33:59.381  8038  8038 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-09 14:33:59.381  8038  8038 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-09 14:33:59.381  8038  8038 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-09 14:33:59.382  8038  8038 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-09 14:33:59.382  8038  8038 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-09 14:33:59.382  8038  8038 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-09 14:33:59.384  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-09 14:33:59.384  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-09 14:33:59.385  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-09 14:33:59.386  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 14:33:59.387  6669  6725 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-09 14:33:59.388  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:59.388  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:59.388  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:59.388  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:59.388  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:59.388  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 14:33:59.388  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 14:33:59.388  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c849f96 removed from the list
08-09 14:33:59.388  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:59.388  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@111bd717 removed from the list
08-09 14:33:59.388  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:59.388  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:59.389  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:59.389  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:59.390  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:59.390  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:59.390  6669  6725 I org.thaliproject.p2,p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:59.390  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@111bd717 not in the list
08-09 14:33:59.390  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:59.390  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:59.391  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-09 14:33:59.392  6669  6725 D BluetoothLeScanner: could not find callback wrapper
08-09 14:33:59.392  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 14:33:59.392  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:59.392  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:59.392  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37e31f22 removed from the list
08-09 14:33:59.392  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:59.392  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:59.392  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:59.392  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 14:33:59.392  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@223924ed removed from the list
08-09 14:33:59.393  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 14:33:59.393  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@291022e9 added. We now have 2 listener(s)
08-09 14:33:59.393  1036  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 14:33:59.395  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-09 14:33:59.395  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 14:33:59.395  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 14:33:59.395  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 14:33:59.396  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb80b6e added. We now have 9 listener(s)
08-09 14:33:59.396  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 14:33:59.396  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-09 14:33:59.398  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 14:33:59.401  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 14:33:59.401  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:59.401  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:59.401  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 14:33:59.401  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 14:33:59.401  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 14:33:59.401  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 14:33:59.401  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - active network t,ype is Wi-Fi: true
08-09 14:33:59.402  6669  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 14:33:59.402  6669  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 14:33:59.404  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 14:33:59.404  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:59.404  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14d4f29c added. We now have 3 listener(s)
08-09 14:33:59.404  1036  1853 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-09 14:33:59.406  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:59.408  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-09 14:33:59.408  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 14:33:59.408  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 14:33:59.408  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 14:33:59.408  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13f04a5 added. We now have 10 listener(s)
08-09 14:33:59.408  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 14:33:59.408  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-09 14:33:59.408  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-09 14:33:59.408  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-09 14:33:59.408  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 14:33:59.408  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-09 14:33:59.421  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-09 14:33:59.421  1036  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-09 14:33:59.427  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-09 14:33:59.428  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-09 14:33:59.429  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-09 14:33:59.430  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 14:33:59.431  6669  6725 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-09 14:33:59.433  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:59.433  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:59.433  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:59.433  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:59.433  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:59.433  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 14:33:59.433  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 14:33:59.433  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@291022e9 removed from the list
08-09 14:33:59.433  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:59.434  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb80b6e removed from the list
08-09 14:33:59.434  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:59.434  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:59.434  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:59.434  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 14:33:59.435  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:59.435  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:59.435  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:59.435  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb80b6e not in the list
08-09 14:33:59.435  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:59.435  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:59.436  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:59.436  6669  6725 D BluetoothLeScanner: could not find callback wrapper
08-09 14:33:59.436  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 14:33:59.436  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:59.437  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:59.437  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13f04a5 removed from the list
08-09 14:33:59.437  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:59.437  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:59.437  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:59.437  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 14:33:59.437  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14d4f29c removed from the list
08-09 14:33:59.437  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 14:33:59.437  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@148c9c88 added. We now have 2 listener(s)
08-09 14:33:59.438  1036  1579 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 14:33:59.440  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-09 14:33:59.441  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 14:33:59.441  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 14:33:59.441  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 14:33:59.441  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30c04621 added. We now have 9 listener(s)
08-09 14:33:59.441  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 14:33:59.441  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-09 14:33:59.444  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bluetoot,hManager: bind: Binding a new listener
08-09 14:33:59.447  6669  6725 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 14:33:59.447  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:59.447  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-09 14:33:59.447  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 14:33:59.447  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 14:33:59.447  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 14:33:59.447  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 14:33:59.447  6669  6725 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-09 14:33:59.448  6669  6725 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 14:33:59.448  6669  6725 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 14:33:59.450  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 14:33:59.450  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fcab407 added. We now have 3 listener(s)
08-09 14:33:59.450  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:59.450  1036  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-09 14:33:59.451  6669  6669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:59.453  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-09 14:33:59.453  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 14:33:59.453  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 14:33:59.453  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 14:33:59.453  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092f934 added. We now have 10 listener(s)
08-09 14:33:59.453  6669  6725 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 14:33:59.453  6669  6725 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-09 14:33:59.453  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:59.453  6669  6725 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:59.453  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:59.453  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:59.453  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 14:33:59.453  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 14:33:59.453  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@148c9c88 removed from the list
08-09 14:33:59.453  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:59.453  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30c04621 removed from the list
08-09 14:33:59.453  6669  6725 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:59.453  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:59.454  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:59.454  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:59.455  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:59.455  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:59.455  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:59.455  6669  6725 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30c04621 not in the list
08-09 14:33:59.455  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:59.455  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:59.455  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:59.455  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:59.455  6669  6725 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:59.456  6669  6725 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1092f934 removed from the list
08-09 14:33:59.456  6669  6725 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:59.456  6669  6725 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:59.456  6669  6725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:59.456  6669  6725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 14:33:59.456  6669  6725 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fcab407 removed fro,m the list
08-09 14:33:59.456  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-09 14:33:59.456  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-09 14:33:59.457  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-09 14:33:59.457  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-09 14:33:59.457  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-09 14:33:59.457  6669  6725 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-09 14:33:59.464  6669  8056 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 876, name: My test thread name)
08-09 14:33:59.465  6669  8056 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 876, thread name: My test thread name)
08-09 14:33:59.465  6669  8056 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 876, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-09 14:33:59.467  6669  8057 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 878, name: My test thread name)
08-09 14:33:59.467  6669  8057 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 878, thread name: My test thread name)
08-09 14:33:59.468  6669  8057 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 878, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-09 14:33:59.469  6669  6725 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-09 14:33:59.469  6669  6725 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-09 14:33:59.469  6669  6725 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-09 14:33:59.469  6669  6725 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-09 14:33:59.469  6669  6725 D com.test.thalitest.ThaliTestRunner: Total duration: 22871 ms
08-09 14:33:59.471  6669  6725 I jxcore-log: Total number of executed tests:  80
08-09 14:33:59.471  6669  6725 I jxcore-log: 
08-09 14:33:59.471  6669  6725 I jxcore-log: Number of passed tests:  80
08-09 14:33:59.471  6669  6725 I jxcore-log: 
08-09 14:33:59.471  6669  6725 I jxcore-log: Number of failed tests:  0
08-09 14:33:59.471  6669  6725 I jxcore-log: 
08-09 14:33:59.471  6669  6725 I jxcore-log: Number of ignored tests:  0
08-09 14:33:59.471  6669  6725 I jxcore-log: 
08-09 14:33:59.471  6669  6725 I jxcore-log: Total duration:  22871
08-09 14:33:59.471  6669  6725 I jxcore-log: 
08-09 14:33:59.471  6669  6725 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-09 14:33:59.471  6669  6725 I jxcore-log: 
08-09 14:33:59.473  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 14:33:59.473  6669  6725 I jxcore-log: 
08-09 14:33:59.476  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 14:33:59.476  6669  6725 I jxcore-log: 
08-09 14:33:59.476  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 14:33:59.476  6669  6725 I jxcore-log: 
,08-09 14:33:59.477  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 14:33:59.477  6669  6725 I jxcore-log: 
08-09 14:33:59.478  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 14:33:59.478  6669  6725 I jxcore-log: 
08-09 14:33:59.479  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 14:33:59.479  6669  6725 I jxcore-log: 
08-09 14:33:59.481  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 14:33:59.481  6669  6725 I jxcore-log: 
08-09 14:33:59.483  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-09 14:33:59.483  6669  6725 I jxcore-log: 
08-09 14:33:59.484  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-09 14:33:59.484  6669  6725 I jxcore-log: 
08-09 14:33:59.484  8011  8011 W ExternalStrings: load override strings
08-09 14:33:59.484  8011  8011 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-09 14:33:59.484  8011  8011 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-09 14:33:59.484  8011  8011 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-09 14:33:59.484  8011  8011 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-09 14:33:59.484  8011  8011 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-09 14:33:59.484  8011  8011 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-09 14:33:59.484  8011  8011 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-09 14:33:59.484  8011  8011 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-09 14:33:59.484  8011  8011 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-09 14:33:59.484  8011  8011 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-09 14:33:59.484  8011  8011 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-09 14:33:59.484  8011  8011 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 14:33:59.484  8011  8011 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-09 14:33:59.484  8011  8011 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-09 14:33:59.484  8011  8011 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 14:33:59.484  8011  8011 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 14:33:59.484  8011  8011 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-09 14:33:59.484  8011  8011 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-09 14:33:59.484  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 14:33:59.484  6669  6725 I jxcore-log: 
08-09 14:33:59.485  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 14:33:59.485  6669  6725 I jxcore-log: 
08-09 14:33:59.486  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-09 14:33:59.486  6669  6725 I jxcore-log: 
08-09 14:33:59.486  8011  8011 D StatusProvider: onCreate
08-09 14:33:59.487  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-09 14:33:59.487  6669  6725 I jxcore-log: 
08-09 14:33:59.487  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-09 14:33:59.487  6669  6725 I jxcore-log: 
08-09 14:33:59.488  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 14:33:59.488  6669  6725 I jxcore-log: 
08-09 14:33:59.488  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 14:33:59.488  6669  6725 I jxcore-log: 
08-09 14:33:59.489  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-09 14:33:59.489  6669  6725 I jxcore-log: 
08-09 14:33:59.490  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-09 14:33:59.490  6669  6725 I jxcore-log: 
08-09 14:33:59.490  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 14:33:59.490  6669  6725 I jxcore-log: 
08-09 14:33:59.491  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 14:33:59.491  6669  6725 I jxcore-log: 
08-09 14:33:59.492  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-09 14:33:59.492  6669  6725 I jxcore-log: 
08-09 14:33:59.493  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-09 14:33:59.493  6669  6725 I jxcore-log: 
08-09 14:33:59.493  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-09 14:33:59.493  6669  6725 I jxcore-log: 
08-09 14:33:59.494  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-09 14:33:59.494  6669  6725 I jxcore-log: 
08-09 14:33:59.494  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 14:33:59.494  6669  6725 I jxcore-log: 
08-09 14:33:59.495  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 14:33:59.495  6669  6725 I jxcore-log: 
08-09 14:33:59.495  6669  6669 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-09 14:33:59.496  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 14:33:59.496  6669  6725 I jxcore-log: 
08-09 14:33:59.496  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 14:33:59.496  6669  6725 I jxcore-log: 
08-09 14:33:59.497  6669  6725 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 14:33:59.497  6669  6725 I jxcore-log: 
,08-09 14:33:59.546  8011  8011 V Signer  : override build config not found
08-09 14:33:59.546  8011  8011 D Signer  : value of property debug is false
,08-09 14:33:59.578  8011  8011 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,08-09 14:33:59.579  8011  8011 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-09 14:33:59.579  8011  8011 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-09 14:33:59.579  8011  8011 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-09 14:33:59.580  8011  8011 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-09 14:33:59.580  8011  8011 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-09 14:33:59.580  8011  8011 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-09 14:33:59.581  8011  8011 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-09 14:33:59.581  8011  8011 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-09 14:33:59.581  8011  8011 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-09 14:33:59.581  8011  8011 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-09 14:33:59.581  8011  8011 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-09 14:33:59.581  8011  8011 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-09 14:33:59.590  8011  8011 V LGMDMManager: Create singleton instance
,08-09 14:33:59.627  1036  8029 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-09 14:33:59.628  8011  8011 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
08-09 14:33:59.629  1036  8029 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-09 14:33:59.629  1036  8029 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-09 14:33:59.629  1036  8029 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-09 14:33:59.629  1036  8029 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-09 14:33:59.629  1036  8029 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-09 14:33:59.629  1036  8029 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-09 14:33:59.629  1036  8029 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-09 14:33:59.630  1036  8029 D DhcpStateMachine: RunningState
,08-09 14:33:59.698  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-09 14:33:59.703  8011  8073 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-09 14:33:59.713  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 14:33:59.720  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:33:59.757  1036  1921 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8076 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-09 14:33:59.758  1036  1921 I ActivityManager: Killing 7146:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-09 14:33:59.782  8067  8067 D AndroidRuntime: 
08-09 14:33:59.782  8067  8067 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-09 14:33:59.785  8067  8067 D AndroidRuntime: CheckJNI is OFF
08-09 14:33:59.865  8011  8072 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-09 14:33:59.903  8067  8067 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-09 14:33:59.967  1036  1928 W libprocessgroup: failed to open /acct/uid_10093/pid_7146/cgroup.procs: No such file or directory
,08-09 14:34:00.009  1036  1099 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-09 14:34:00.010  1036  1099 I ActivityManager: Killing 6669:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-09 14:34:00.039  1588  1588 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-09 14:34:00.039  1588  1588 I KeyguardUpdateMonitor: called onTimeUpdated()
08-09 14:34:00.040  1588  1588 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-09 14:34:00.040  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
08-09 14:34:00.041  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
08-09 14:34:00.042  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
08-09 14:34:00.043  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
08-09 14:34:00.043  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
08-09 14:34:00.052  8076  8076 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-09 14:34:00.085  1036  1928 I WindowState: WIN DEATH: Window{23b13d8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-09 14:34:00.085  1036  1529 D WifiService: Client connection lost with reason: 4
,08-09 14:34:00.089  1036  1928 D InputDispatcher: Window went away: Window{23b13d8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-09 14:34:00.297  1036  1099 I ActivityManager:   Force finishing activity ActivityRecord{3eda488d u0 com.test.thalitest/.MainActivity t2}
,08-09 14:34:00.327   339   356 E GBMv2   : DFP En is all cleared set to be enabled
08-09 14:34:00.329  1036  1362 D PowerManagerServiceEx: acquireWakeLockInternal: lock=570406340, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
08-09 14:34:00.329  1036  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-09 14:34:00.332  1036  1124 I ActivityManager:   Force finishing activity ActivityRecord{3eda488d u0 com.test.thalitest/.MainActivity t2 f}
,08-09 14:34:00.333  1036  1124 W ActivityManager: Duplicate finish request for ActivityRecord{3eda488d u0 com.test.thalitest/.MainActivity t2 f}
,08-09 14:34:00.378  1036  1956 W ActivityManager: Spurious death for ProcessRecord{3631efe3 6669:com.test.thalitest/u0a118}, curProc for 6669: null
,08-09 14:34:00.383  2018  2018 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-09 14:34:00.387  2018  2018 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-09 14:34:00.389  1926  2923 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-09 14:34:00.390  1926  2923 D SplitWindowPolicy: topRunningActivity=ActivityInfo{10ea443a co.....Launcher}, taskId=1, activityType=1, bIsSplit=false
08-09 14:34:00.391  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-09 14:34:00.393  2018  2088 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-09 14:34:00.394  8076  8076 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-09 14:34:00.394  1926  1943 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-09 14:34:00.394  1926  1943 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1364e8eb co.....Launcher}, taskId=1, activityType=1, bIsSplit=false
,08-09 14:34:00.402  1036  1099 D SplitWindowManager: removeStackAndNeedHomeResume ActivityStack{36ec7de0 stackId=1, 0 tasks}
08-09 14:34:00.405  2018  2018 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-09 14:34:00.406  1891  1891 D ActionManagerService: notifyUserLog: 1000003
,08-09 14:34:00.408  3815  4474 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-09 14:34:00.408  2018  2018 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-09 14:34:00.411  2018  2018 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-09 14:34:00.437  1980  1980 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-09 14:34:00.438  1036  1366 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-09 14:34:00.440  3815  3815 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-09 14:34:00.442  2454  2644 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-09 14:34:00.442  1588  1588 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-09 14:34:00.443  7595  7595 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-09 14:34:00.443  7595  7595 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-09 14:34:00.487  2018  2018 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,08-09 14:34:00.491  4483  4483 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-09 14:34:00.491  4483  4483 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
,08-09 14:34:00.502  2018  2018 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-09 14:34:00.502  1891  1891 D ActionManagerService: notifyUserLog: 1000004
08-09 14:34:00.503  3815  4474 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-09 14:34:00.506  1588  1588 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-09 14:34:00.506  3815  4469 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-09 14:34:00.510  2018  2018 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-09 14:34:00.510  2018  2018 I GBoardWebViewUtils: , create_time: 1430832262123
08-09 14:34:00.510  2018  2018 I GBoardWebViewUtils: , expire_time: 0
08-09 14:34:00.510  2018  2018 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-09 14:34:00.510  2018  2018 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-09 14:34:00.510  2018  2018 I GBoardWebViewUtils: , display: false
08-09 14:34:00.510  2018  2018 I GBoardWebViewUtils: , animation: false }
08-09 14:34:00.510  2018  2018 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-09 14:34:00.510  2018  2018 I GBoardWebViewUtils: , create_time: 1430832262287
08-09 14:34:00.510  2018  2018 I GBoardWebViewUtils: , expire_time: 0
08-09 14:34:00.510  2018  2018 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-09 14:34:00.510  2018  2018 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-09 14:34:00.510  2018  2018 I GBoardWebViewUtils: , display: false
08-09 14:34:00.510  2018  2018 I GBoardWebViewUtils: , animation: false }
08-09 14:34:00.510  2018  2018 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1470393742816
08-09 14:34:00.510  2018  2018 I GBoardWebViewUtils: , create_time: 1470393743569
08-09 14:34:00.510  2018  2018 I GBoardWebViewUtils: , expire_time: 0
08-09 14:34:00.510  2018  2018 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-09 14:34:00.510  2018  2018 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-09 14:34:00.510  2018  2018 I GBoardWebViewUtils: , display: false
08-09 14:34:00.510  2018  2018 I GBoardWebViewUtils: , animation: false }
08-09 14:34:00.500  4483  4483 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-09 14:34:00.512  4483  4483 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-09 14:34:00.512  4483  4483 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-09 14:34:00.512  4483  4483 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-09 14:34:00.514  4483  4483 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-09 14:34:00.514  4483  4483 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-09 14:34:00.514  4483  4483 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 14:34:00.514  4483  4483 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 14:34:00.515  4483  4483 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-09 14:34:00.515  4483  4483 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-09 14:34:00.524  1036  1524 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-09 14:34:00.524  1036  1524 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-09 14:34:00.527  1036  1524 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-09 14:34:00.527  1036  1524 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-09 14:34:00.527  1036  1524 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-09 14:34:00.528  1036  1524 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-09 14:34:00.528  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-09 14:34:00.528  1036  1530 D ConnectivityService: identical MTU - not setting
08-09 14:34:00.529  1036  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-09 14:34:00.529  1036  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-09 14:34:00.529  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-09 14:34:00.529  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 14:34:00.529  1036  1530 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-09 14:34:00.530  1588  2058 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-09 14:34:00.533  2018  8129 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-09 14:34:00.533  1854  1854 D SplitUIManager: split_name #11 / not available #0
08-09 14:34:00.533  1854  1854 D SplitUIService: removed split : 
08-09 14:34:00.542  8076  8076 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-09 14:34:00.543  8076  8076 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-09 14:34:00.543  8076  8076 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-09 14:34:00.543  8076  8076 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-09 14:34:00.543  8076  8076 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-09 14:34:00.545  8076  8076 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-09 14:34:00.546  1036  1975 V SIM_STK : Menu title from STK is T-Mobile
,08-09 14:34:00.551  1588  1588 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-09 14:34:00.551  1588  1588 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-09 14:34:00.554  4588  4588 I art     : Explicit concurrent mark sweep GC freed 8239(471KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 1.577ms total 199.554ms
08-09 14:34:00.560  2018  2018 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,08-09 14:34:00.566  1036  1890 V SIM_STK : Menu title from STK is T-Mobile
08-09 14:34:00.566  1036  1890 V SIM_STK : Menu title from STK is T-Mobile
08-09 14:34:00.578  1854  1854 D SplitUIManager: split_name #11 / not available #0
08-09 14:34:00.578  1854  1854 I SplitUIService: split app #11
08-09 14:34:00.578  1588  1652 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-09 14:34:00.578  1588  1652 D KeyguardModel: createShortcutInfo...
08-09 14:34:00.580  1588  1652 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-09 14:34:00.580  1588  1652 D KeyguardModel: createShortcutInfo...
08-09 14:34:00.580  1036  1036 D administrator: Handling package changes for user 0
08-09 14:34:00.585  1588  1652 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-09 14:34:00.585  1588  1652 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-09 14:34:00.585  1588  1652 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-09 14:34:00.586  1588  1652 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-09 14:34:00.598  8011  8072 D LgDataFeature: LgDataFeature() Constructor: none
08-09 14:34:00.598  8011  8072 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-09 14:34:00.601  1588  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-09 14:34:00.601  1588  1652 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-09 14:34:00.616  1036  2010 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-09 14:34:00.616  1588  1652 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-09 14:34:00.616  1588  1652 D KeyguardModel: createShortcutInfo...
08-09 14:34:00.616  7595  7595 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-09 14:34:00.616  7595  7595 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-09 14:34:00.616  7595  7595 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-09 14:34:00.617  7595  7595 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-09 14:34:00.617  7595  7595 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-09 14:34:00.617  7595  7595 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,08-09 14:34:00.617  7595  7595 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-09 14:34:00.617  7595  7595 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-09 14:34:00.617  7595  7595 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
,08-09 14:34:00.617  7595  7595 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-09 14:34:00.617  7595  7595 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-09 14:34:00.626  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-09 14:34:00.630  1588  1652 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-09 14:34:00.630  1588  1652 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-09 14:34:00.633  2598  2598 D [Concierge]Service: onStartCommand(). Type : 9
08-09 14:34:00.633  1588  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-09 14:34:00.633  1588  1652 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-09 14:34:00.634  1588  1652 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-09 14:34:00.634  1588  1652 D KeyguardModel: createShortcutInfo...
08-09 14:34:00.634  8076  8076 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-09 14:34:00.639  1588  1652 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-09 14:34:00.639  1588  1652 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-09 14:34:00.639  1588  1652 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-09 14:34:00.639  1588  1652 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-09 14:34:00.640  8076  8076 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 14:34:00.640  1588  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-09 14:34:00.640  1588  1652 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-09 14:34:00.640  1588  1652 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-09 14:34:00.640  1588  1652 D KeyguardModel: createShortcutInfo...
08-09 14:34:00.643  8076  8076 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 14:34:00.655  1588  1652 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-09 14:34:00.655  1588  1652 D KeyguardModel: createShortcutInfo...
08-09 14:34:00.656  1588  1652 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-09 14:34:00.656  1588  1652 D KeyguardModel: createShortcutInfo...
08-09 14:34:00.657  1588  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-09 14:34:00.657  1588  1652 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-09 14:34:00.658  1588  1652 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-09 14:34:00.658  1588  1652 D KeyguardModel: createShortcutInfo...
,08-09 14:34:00.659  1588  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-09 14:34:00.659  1588  1652 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-09 14:34:00.660  1588  1588 D KeyguardModel: handleShortcutListChanged...
08-09 14:34:00.660  1588  1588 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-09 14:34:00.661  1588  1652 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-09 14:34:00.661  1588  1652 D KeyguardModel: createShortcutInfo...
08-09 14:34:00.662  1588  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-09 14:34:00.662  1588  1652 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-09 14:34:00.663  1588  1652 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-09 14:34:00.663  1588  1652 D KeyguardModel: createShortcutInfo...
08-09 14:34:00.663  8076  8076 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-09 14:34:00.665  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 14:34:00.665  8011  8073 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-09 14:34:00.669  1036  1124 I art     : Explicit concurrent mark sweep GC freed 79702(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 1.586ms total 281.652ms
08-09 14:34:00.669  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-09 14:34:00.670  8076  8076 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-09 14:34:00.672  8076  8076 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-09 14:34:00.679  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:34:00.685  1036  1052 V SIM_STK : Menu title from STK is T-Mobile
08-09 14:34:00.687  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-09 14:34:00.687  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-09 14:34:00.688  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-09 14:34:00.689  1036  1563 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
08-09 14:34:00.690  1036  1098 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-09 14:34:00.701  8076  8076 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 14:34:00.701  8076  8076 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-09 14:34:00.703   332   412 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-09 14:34:00.704  3198  8137 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-09 14:34:00.704  8076  8076 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-09 14:34:00.705  1588  1588 D KeyguardModel: handleShortcutListChanged...
08-09 14:34:00.705  1588  1588 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-09 14:34:00.707  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-09 14:34:00.710  6792  6792 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-09 14:34:00.712  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 14:34:00.716  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 14:34:00.724  8011  8073 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-09 14:34:00.759  2018  2018 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-09 14:34:00.760  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-09 14:34:00.763  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-09 14:34:00.764  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:34:00.764  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-09 14:34:00.765  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-09 14:34:00.766  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-09 14:34:00.767  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-09 14:34:00.787  8076  8076 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-09 14:34:00.788  8076  8076 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 14:34:00.788  8076  8076 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-09 14:34:00.788  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-09 14:34:00.788  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-09 14:34:00.794  2018  2137 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-09 14:34:00.794  2018  2137 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-09 14:34:00.795  8067  8067 D AndroidRuntime: Shutting down VM
08-09 14:34:00.796  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3e2bd919 u0 com.lge.launcher2/.Launcher t1} time:149015
08-09 14:34:00.798  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-09 14:34:00.798  6792  6792 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-09 14:34:00.798  6792  6792 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-09 14:34:00.798  6792  6792 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-09 14:34:00.799  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-09 14:34:00.801  6792  6792 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-09 14:34:00.801  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-09 14:34:00.801  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-09 14:34:00.801  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-09 14:34:00.801  6792  6792 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-09 14:34:00.801  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-09 14:34:00.801  6792  6792 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-09 14:34:00.803  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 14:34:00.804  8011  8073 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-09 14:34:00.804  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-09 14:34:00.805  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-09 14:34:00.805  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-09 14:34:00.809  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-09 14:34:00.809  8011  8072 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-09 14:34:00.815  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:34:00.815  2018  2018 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-09 14:34:00.838  1036  1124 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8141 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-09 14:34:00.849  2598  2598 D [Concierge]Service: onStartCommand(). Type : 8
08-09 14:34:00.849  2598  2598 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-09 14:34:00.850  2598  2598 D [Concierge]Service: Update widget ID : 11
,08-09 14:34:00.851  2018  2018 D [Concierge]WidgetView: change position of spinner
08-09 14:34:00.852  2018  2018 I [Concierge]WidgetView: initWebView(). Time : 1470746040852
08-09 14:34:00.853  8076  8076 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 14:34:00.854  8076  8076 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 14:34:00.854  8076  8076 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-09 14:34:00.855  2598  2598 D [Concierge]Service: onStartCommand(). Type : 0
08-09 14:34:00.856  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 14:34:00.856  8011  8073 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-09 14:34:00.860  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 14:34:00.864  8011  8072 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-09 14:34:00.866  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:34:00.870  8076  8076 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 14:34:00.871  8076  8076 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 14:34:00.871  8011  8072 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-09 14:34:00.871  8076  8076 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-09 14:34:00.872  8011  8072 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-09 14:34:00.872  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 14:34:00.872  8011  8073 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-09 14:34:00.872  8011  8072 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,08-09 14:34:00.875  8011  8072 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-09 14:34:00.876  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-09 14:34:00.879  8011  8072 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-09 14:34:00.880  8011  8072 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-09 14:34:00.882  8011  8072 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-09 14:34:00.882  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:34:00.884  2018  2018 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 311871030
08-09 14:34:00.884  2018  2018 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
,08-09 14:34:00.885  2018  2018 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-09 14:34:00.887  8076  8076 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 14:34:00.887  8076  8076 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 14:34:00.887  8076  8076 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-09 14:34:00.887  2018  2018 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2763db92
08-09 14:34:00.887  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-09 14:34:00.888  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-09 14:34:00.888  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-09 14:34:00.890  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 14:34:00.890  8011  8073 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-09 14:34:00.893  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-09 14:34:00.894  2018  2018 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-09 14:34:00.894  2018  2018 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-09 14:34:00.894  2018  2018 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470745918988, New one : 1470746040852
08-09 14:34:00.895  2018  2018 D [Concierge]WidgetView: Unregister all receivers
08-09 14:34:00.895  2018  2018 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-09 14:34:00.895  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-09 14:34:00.896  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-09 14:34:00.898  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-09 14:34:00.899  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
,08-09 14:34:00.900  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-09 14:34:00.901  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-09 14:34:00.902  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-09 14:34:00.904  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:34:00.905  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-09 14:34:00.905  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-09 14:34:00.909  1036  1098 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-09 14:34:00.911  1036  1997 I ActivityManager: Killing 7192:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-09 14:34:00.925  1036  1098 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-09 14:34:00.946  2018  2018 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-09 14:34:00.954  2018  2018 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,08-09 14:34:00.954  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-09 14:34:00.955  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-09 14:34:00.974  2018  2018 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2b638cef time:149193
,08-09 14:34:00.982  8076  8076 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 14:34:00.982  1036  2010 W libprocessgroup: failed to open /acct/uid_10005/pid_7192/cgroup.procs: No such file or directory
08-09 14:34:00.982  8076  8076 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 14:34:00.983  8076  8076 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-09 14:34:00.984  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-09 14:34:00.989  8011  8073 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-09 14:34:00.990  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-09 14:34:00.997  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 14:34:01.001  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:34:01.005  8076  8076 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 14:34:01.005  8076  8076 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 14:34:01.008  8076  8076 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-09 14:34:01.011  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 14:34:01.011  8011  8073 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-09 14:34:01.014  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-09 14:34:01.018  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:34:01.023  8076  8076 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 14:34:01.023  8076  8076 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 14:34:01.023  8076  8076 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-09 14:34:01.026  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 14:34:01.026  8011  8073 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-09 14:34:01.029  7966  7966 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-09 14:34:01.031  7966  7966 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-09 14:34:01.033  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-09 14:34:01.036  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:34:01.039  8076  8076 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-09 14:34:01.039  8076  8076 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 14:34:01.040  8076  8076 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-09 14:34:01.041  8076  8076 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-09 14:34:01.041  8076  8076 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-09 14:34:01.044  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-09 14:34:01.058  7966  7966 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-09 14:34:01.058  7966  7966 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-09 14:34:01.060  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-09 14:34:01.064  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-09 14:34:01.067  8076  8076 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-09 14:34:01.067  8076  8076 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-09 14:34:01.068  8076  8076 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-09 14:34:01.068  8076  8076 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-09 14:34:01.068  8076  8076 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-09 14:34:01.070  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-09 14:34:01.071  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-09 14:34:01.073  1801  1801 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-09 14:34:01.077  2140  2140 I ConfigService: onCreate
08-09 14:34:01.078  2140  2140 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-09 14:34:01.079  1801  1801 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-09 14:34:01.081  2140  2140 I ConfigService: onBind returning update interface
08-09 14:34:01.082  2140  2140 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-09 14:34:01.082  2140  2140 I ConfigService: onBind returning config service
,08-09 14:34:01.098  2018  2018 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-09 14:34:01.129  2140  2140 I ConfigService: onDestroy
,08-09 14:34:01.131  1801  8167 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-09 14:34:01.136  2018  2916 I GBoardtInterface: onReloaded()
08-09 14:34:01.137  2018  2018 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-09 14:34:01.139  3815  4469 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-09 14:34:01.142  3815  3834 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-09 14:34:01.147  1891  1891 D ActionManagerService: notifyUserLog: 1000001
08-09 14:34:01.148  3815  4474 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-09 14:34:01.148  3815  4474 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-09 14:34:01.152  1891  1891 D ActionManagerService: notifyUserLog: 1000001
08-09 14:34:01.154  3815  3834 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-09 14:34:01.154  3815  4474 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-09 14:34:01.154  3815  4474 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-09 14:34:01.154  3815  4474 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-09 14:34:01.154  3815  4474 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
,08-09 14:34:01.156  5901  8174 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-09 14:34:01.163  1801  8172 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/databases/metrics.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
08-09 14:34:01.163  1801  8172 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] disk I/O error
--------- beginning of crash
08-09 14:34:01.168  1801  8172 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
08-09 14:34:01.168  1801  8172 E AndroidRuntime: Process: com.google.android.gms, PID: 1801
08-09 14:34:01.168  1801  8172 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-09 14:34:01.168  1801  8172 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-09 14:34:01.168  1801  8172 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-09 14:34:01.168  1801  8172 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-09 14:34:01.168  1801  8172 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-09 14:34:01.168  1801  8172 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-09 14:34:01.168  1801  8172 E AndroidRuntime: 	at com.google.android.gms.googlehelp.d.e.a(SourceFile:215)
08-09 14:34:01.168  1801  8172 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
08-09 14:34:01.168  1801  8172 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-09 14:34:01.168  1801  8172 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 14:34:01.168  1801  8172 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-09 14:34:01.168  1801  8172 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-09 14:34:01.170  6962  6962 E SQLiteDatabase: Error inserting package=com.test.thalitest
08-09 14:34:01.170  6962  6962 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
08-09 14:34:01.170  6962  6962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-09 14:34:01.170  6962  6962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
08-09 14:34:01.170  6962  6962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
08-09 14:34:01.170  6962  6962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-09 14:34:01.170  6962  6962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
08-09 14:34:01.170  6962  6962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
08-09 14:34:01.170  6962  6962 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.insert(AppBoxContentProvider.java:220)
08-09 14:34:01.170  6962  6962 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
08-09 14:34:01.170  6962  6962 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
08-09 14:34:01.170  6962  6962 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeApp(PreloadListManagerHelper.java:134)
08-09 14:34:01.170  6962  6962 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeAppInternal(PreloadListManagerHelper.java:115)
08-09 14:34:01.170  6962  6962 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onRemoveAppEvent(PreloadListManagerHelper.java:100)
08-09 14:34:01.170  6962  6962 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.updateExDb(PreloadListManagerHelper.java:65)
08-09 14:34:01.170  6962  6962 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onReceive(PreloadListManagerHelper.java:46)
08-09 14:34:01.170  6962  6962 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
08-09 14:34:01.170  6962  6962 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
08-09 14:34:01.170  6962  6962 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
08-09 14:34:01.170  6962  6962 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 14:34:01.170  6962  6962 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-09 14:34:01.170  6962  6962 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-09 14:34:01.170  6962  6962 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 14:34:01.170  6962  6962 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 14:34:01.170  6962  6962 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-09 14:34:01.170  6962  6962 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-09 14:34:01.171  2018  2018 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-09 14:34:01.171  2018  2018 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-09 14:34:01.171  1801  8175 I PeopleContactsSync: CP2 sync disabled
08-09 14:34:01.173  2018  2018 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-09 14:34:01.173  2018  2018 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. ,return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-09 14:34:01.177  2018  2018 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-09 14:34:01.178  2018  2018 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-09 14:34:01.180  1801  4755 I Icing   : doRemovePackageData com.test.thalitest
08-09 14:34:01.180  1801  8172 I Process : Sending signal. PID: 1801 SIG: 9
,08-09 14:34:01.183  2351  2504 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-09 14:34:01.183  1036  8176 E DropBoxManagerService: Can't write: system_app_crash
08-09 14:34:01.183  1036  8176 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
08-09 14:34:01.183  1036  8176 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 14:34:01.183  1036  8176 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 14:34:01.183  1036  8176 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 14:34:01.183  1036  8176 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-09 14:34:01.183  1036  8176 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-09 14:34:01.183  1036  8176 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-09 14:34:01.183  1036  8176 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 14:34:01.183  1036  8176 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-09 14:34:01.183  1036  8176 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 14:34:01.183  1036  8176 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 14:34:01.183  1036  8176 E DropBoxManagerService: 	... 5 more
08-09 14:34:01.188  2351  2504 D ContactsProvider2ForLG: performBackgroundTask SQLiteDiskIOException during query
08-09 14:34:01.188  2351  2504 D ContactsProvider2ForLG: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-09 14:34:01.188  2351  2504 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-09 14:34:01.188  2351  2504 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-09 14:34:01.188  2351  2504 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-09 14:34:01.188  2351  2504 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-09 14:34:01.188  2351  2504 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-09 14:34:01.188  2351  2504 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-09 14:34:01.188  2351  2504 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
08-09 14:34:01.188  2351  2504 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
08-09 14:34:01.188  2351  2504 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
08-09 14:34:01.188  2351  2504 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
08-09 14:34:01.188  2351  2504 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
08-09 14:34:01.188  2351  2504 D ContactsProvider2ForLG: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 14:34:01.188  2351  2504 D ContactsProvider2ForLG: 	at android.os.Looper.loop(Looper.java:135)
08-09 14:34:01.188  2351  2504 D ContactsProvider2ForLG: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 14:34:01.188  2351  8177 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-09 14:34:01.195  2351  8177 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
08-09 14:34:01.196  235,1  8177 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-09 14:34:01.196  2351  8177 E AndroidRuntime: Process: android.process.acore, PID: 2351
08-09 14:34:01.196  2351  8177 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-09 14:34:01.196  2351  8177 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-09 14:34:01.196  2351  8177 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-09 14:34:01.196  2351  8177 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-09 14:34:01.196  2351  8177 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-09 14:34:01.196  2351  8177 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-09 14:34:01.196  2351  8177 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
08-09 14:34:01.196  2351  8177 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
08-09 14:34:01.196  2351  8177 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
08-09 14:34:01.196  2351  8177 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
08-09 14:34:01.196  2351  8177 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
08-09 14:34:01.196  2351  8177 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-09 14:34:01.196  2351  8177 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-09 14:34:01.196  2351  8177 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-09 14:34:01.196  2351  8177 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 14:34:01.196  2351  8177 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-09 14:34:01.196  2351  8177 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-09 14:34:01.203  1036  1529 D WifiService: Client connection lost with reason: 4
08-09 14:34:01.215  1036  1871 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8181 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-09 14:34:01.241  1036  1956 I ActivityManager: Process com.google.android.gms (pid 1801) has died
08-09 14:34:01.241  1036  1956 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
08-09 14:34:01.242  1036  1956 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 11000ms
08-09 14:34:01.242  1036  1956 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 11000ms
08-09 14:34:01.242  1036  1956 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 11000ms
08-09 14:34:01.242  1036  1956 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 11000ms
,08-09 14:34:01.253  2351  8177 I Process : Sending signal. PID: 2351 SIG: 9
08-09 14:34:01.254  1036  8198 E DropBoxManagerService: Can't write: system_app_crash
08-09 14:34:01.254  1036  8198 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
08-09 14:34:01.254  1036  8198 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 14:34:01.254  1036  8198 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 14:34:01.254  1036  8198 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 14:34:01.254  1036  8198 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-09 14:34:01.254  1036  8198 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-09 14:34:01.254  1036  8198 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-09 14:34:01.254  1036  8198 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 14:34:01.254  1036  8198 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-09 14:34:01.254  1036  8198 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 14:34:01.254  1036  8198 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 14:34:01.254  1036  8198 E DropBoxManagerService: 	... 5 more
,08-09 14:34:01.263  8181  8181 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-09 14:34:01.263  8181  8181 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-09 14:34:01.264  8181  8181 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-09 14:34:01.264  8181  8181 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-09 14:34:01.298  8181  8181 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/Downloads.db'.
08-09 14:34:01.298  8181  8181 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 14:34:01.298  8181  8181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 14:34:01.298  8181  8181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-09 14:34:01.298  8181  8181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-09 14:34:01.298  8181  8181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-09 14:34:01.298  8181  8181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-09 14:34:01.298  8181  8181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-09 14:34:01.298  8181  8181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-09 14:34:01.298  8181  8181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-09 14:34:01.298  8181  8181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-09 14:34:01.298  8181  8181 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-09 14:34:01.298  8181  8181 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-09 14:34:01.298  8181  8181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 14:34:01.298  8181  8181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 14:34:01.298  8181  8181 E SQLiteDatabase: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
08-09 14:34:01.298  8181  8181 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-09 14:34:01.298  8181  8181 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-09 14:34:01.298  8181  8181 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-09 14:34:01.298  8181  8181 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-09 14:34:01.298  8181  8181 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-09 14:34:01.298  8181  8181 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-09 14:34:01.298  8181  8181 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-09 14:34:01.298  8181  8181 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 14:34:01.298  8181  8181 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-09 14:34:01.298  8181  8181 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-09 14:34:01.298  8181  8181 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 14:34:01.298  8181  8181 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 14:34:01.298  8181  8181 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-09 14:34:01.298  8181  8181 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-09 14:34:01.298  8181  8181 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 14:34:01.298  8181  8181 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 14:34:01.298  8181  8181 W System.err: 	at a,ndroid.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-09 14:34:01.298  8181  8181 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-09 14:34:01.298  8181  8181 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-09 14:34:01.298  8181  8181 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-09 14:34:01.298  8181  8181 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-09 14:34:01.298  8181  8181 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-09 14:34:01.298  8181  8181 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-09 14:34:01.298  8181  8181 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-09 14:34:01.298  8181  8181 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-09 14:34:01.298  8181  8181 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-09 14:34:01.298  8181  8181 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 14:34:01.298  8181  8181 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 14:34:01.298  8181  8181 W System.err: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
08-09 14:34:01.298  8181  8181 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-09 14:34:01.298  8181  8181 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-09 14:34:01.298  8181  8181 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-09 14:34:01.298  8181  8181 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-09 14:34:01.298  8181  8181 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-09 14:34:01.298  8181  8181 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-09 14:34:01.298  8181  8181 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-09 14:34:01.299  8181  8181 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 14:34:01.299  8181  8181 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-09 14:34:01.299  8181  8181 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-09 14:34:01.299  8181  8181 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 14:34:01.299  8181  8181 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 14:34:01.299  8181  8181 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
,08-09 14:34:01.299  8181  8181 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-09 14:34:01.303  8181  8181 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/sqt.db'.
08-09 14:34:01.303  8181  8181 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 14:34:01.303  8181  8181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 14:34:01.303  8181  8181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-09 14:34:01.303  8181  8181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-09 14:34:01.303  8181  8181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-09 14:34:01.303  8181  8181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-09 14:34:01.303  8181  8181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-09 14:34:01.303  8181  8181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-09 14:34:01.303  8181  8181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-09 14:34:01.303  8181  8181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-09 14:34:01.303  8181  8181 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-09 14:34:01.303  8181  8181 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-09 14:34:01.303  8181  8181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 14:34:01.303  8181  8181 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 14:34:01.303  8181  8181 E SQLiteDatabase: 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
08-09 14:34:01.303  8181  8181 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-09 14:34:01.303  8181  8181 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-09 14:34:01.303  8181  8181 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-09 14:34:01.303  8181  8181 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-09 14:34:01.303  8181  8181 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-09 14:34:01.303  8181  8181 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-09 14:34:01.303  8181  8181 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-09 14:34:01.303  8181  8181 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 14:34:01.303  8181  8181 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-09 14:34:01.303  8181  8181 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-09 14:34:01.303  8181  8181 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 14:34:01.303  8181  8181 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 14:34:01.303  8181  8181 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-09 14:34:01.303  8181  8181 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-09 14:34:01.303  8181  8181 D AndroidRuntime: Shutting down VM
08-09 14:34:01.303  8181  8181 E AndroidRuntime: FATAL EXCEPTION: main
08-09 14:34:01.303  8181  8181 E AndroidRuntime: Process: com.lge.email, PID: 8181
08-09 14:34:01.303  8181  8181 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.lge.email.pr,oviders.sqt.SqtProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 14:34:01.303  8181  8181 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5017)
08-09 14:34:01.303  8181  8181 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-09 14:34:01.303  8181  8181 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-09 14:34:01.303  8181  8181 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-09 14:34:01.303  8181  8181 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-09 14:34:01.303  8181  8181 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 14:34:01.303  8181  8181 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-09 14:34:01.303  8181  8181 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-09 14:34:01.303  8181  8181 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 14:34:01.303  8181  8181 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 14:34:01.303  8181  8181 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-09 14:34:01.303  8181  8181 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-09 14:34:01.303  8181  8181 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 14:34:01.303  8181  8181 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 14:34:01.303  8181  8181 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-09 14:34:01.303  8181  8181 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-09 14:34:01.303  8181  8181 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-09 14:34:01.303  8181  8181 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-09 14:34:01.303  8181  8181 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-09 14:34:01.303  8181  8181 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-09 14:34:01.303  8181  8181 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-09 14:34:01.303  8181  8181 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-09 14:34:01.303  8181  8181 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-09 14:34:01.303  8181  8181 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-09 14:34:01.303  8181  8181 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 14:34:01.303  8181  8181 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 14:34:01.303  8181  8181 E AndroidRuntime: 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
08-09 14:34:01.303  8181  8181 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-09 14:34:01.303  8181  8181 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-09 14:34:01.303  8181  8181 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-09 14:34:01.303  8181  8181 E AndroidRuntime: 	... 11 more
08-09 14:34:01.340  1036  1956 I ActivityManager: Process android.process.acore (pid 2351) has died
08-09 14:34:01.341  10,36  1956 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/com.lge.providers.contacts.AliveAcoreService in 20901ms
08-09 14:34:01.341  1036  1956 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.voicemail.VoicemailCleanupService in 30901ms
,08-09 14:34:01.343  8181  8181 I Process : Sending signal. PID: 8181 SIG: 9
08-09 14:34:01.351  1036  8200 E DropBoxManagerService: Can't write: system_app_crash
08-09 14:34:01.351  1036  8200 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop134.tmp: open failed: EROFS (Read-only file system)
08-09 14:34:01.351  1036  8200 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-09 14:34:01.351  1036  8200 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 14:34:01.351  1036  8200 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 14:34:01.351  1036  8200 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-09 14:34:01.351  1036  8200 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-09 14:34:01.351  1036  8200 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-09 14:34:01.351  1036  8200 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 14:34:01.351  1036  8200 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-09 14:34:01.351  1036  8200 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 14:34:01.351  1036  8200 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-09 14:34:01.351  1036  8200 E DropBoxManagerService: 	... 5 more
08-09 14:34:01.403  1036  1975 I ActivityManager: Process com.lge.email (pid 8181) has died
,08-09 14:34:01.431  4483  4483 E SQLiteLog: (1034) os_unix.c:28207: (30) full_fsync(/mpt/MPT_MainData.db-wal) - 
,08-09 14:34:01.433  4483  4483 W System.err: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 1034)
,08-09 14:34:01.433  4483  4483 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-09 14:34:01.433  4483  4483 W System.err: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-09 14:34:01.433  4483  4483 W System.err: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-09 14:34:01.434  4483  4483 W System.err: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-09 14:34:01.434  4483  4483 W System.err: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-09 14:34:01.434  4483  4483 W System.err: 	at com.lge.mlt.MptMainLogProvider.delete(MptMainLogProvider.java:1313)
08-09 14:34:01.434  4483  4483 W System.err: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
08-09 14:34:01.434  4483  4483 W System.err: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
08-09 14:34:01.434  4483  4483 W System.err: 	at com.lge.mlt.MltMonitorService.checkMaxSizeAndRemove(MltMonitorService.java:1835)
08-09 14:34:01.434  4483  4483 W System.err: 	at com.lge.mlt.MltMonitorService$BlobManager.insertBlobRecord(MltMonitorService.java:1583)
08-09 14:34:01.434  4483  4483 W System.err: 	at com.lge.mlt.MltMonitorService.onLogInfoChanged(MltMonitorService.java:1094)
08-09 14:34:01.434  4483  4483 W System.err: 	at com.lge.mlt.MptOnLogReceiver$1.handleMessage(MptOnLogReceiver.java:78)
08-09 14:34:01.434  4483  4483 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 14:34:01.434  4483  4483 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-09 14:34:01.434  4483  4483 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-09 14:34:01.434  4483  4483 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 14:34:01.435  4483  4483 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-09 14:34:01.435  4483  4483 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-09 14:34:01.435  4483  4483 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-09 14:34:01.453  2018  2916 I GBoardtInterface: exportHTML()
,08-09 14:34:01.479  2018  2916 I GBoardtInterface: exportHTML()
,08-09 14:34:01.502  2018  2916 I GBoardtInterface: exportHTML()

```
