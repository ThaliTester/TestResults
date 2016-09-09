#### Test 84648740f6d448c_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-09 17:17:31.867  1829  4790 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
09-09 17:17:31.902  1829  4790 D Icing   : Loaded CLD2 Version V2.0 - 20140131
09-09 17:17:31.996  1829  4790 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
09-09 17:17:32.047  3233  6521 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-09 17:17:32.047   333   421 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,09-09 17:17:32.329  6492  6492 D LgDataFeature: LgDataFeature() Constructor: none
09-09 17:17:32.329  6492  6492 D LgDataFeature: LgDataFeature() Constructor Done, null
09-09 17:17:32.343  6522  6522 D AndroidRuntime: 
09-09 17:17:32.343  6522  6522 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-09 17:17:32.347  6522  6522 D AndroidRuntime: CheckJNI is OFF
09-09 17:17:32.460  6157  6157 I LockScreenSettings: New app installed broadcast received ..
09-09 17:17:32.462  6157  6157 I LockScreenSettings: Number of installed packages  1
09-09 17:17:32.479  6492  6492 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
09-09 17:17:32.505  1036  2053 V SIM_STK : Menu title from STK is T-Mobile
09-09 17:17:32.535  6522  6522 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-09 17:17:32.543  1036  1990 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6553 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-09 17:17:32.544  1036  1704 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-09 17:17:32.555  1959  1979 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-09 17:17:32.558  1036  1704 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-09 17:17:32.559  1036  1704 D ActivityManager: setTaskToReturnTo : TaskRecord{3c509e82 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-09 17:17:32.559  1036  1704 D ActivityManager: setTaskToReturnTo : TaskRecord{3c509e82 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-09 17:17:32.560  1036  1704 D WindowStateEx: AppWindowTokenEx init.. 
09-09 17:17:32.561   339   377 E GBMv2   : DFP En is all cleared set to be enabled
09-09 17:17:32.598  1036  1704 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6571 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-09 17:17:32.600  6522  6522 D AndroidRuntime: Shutting down VM
09-09 17:17:32.638  1959  3957 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-09 17:17:32.639  1959  3957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{20730407 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-09 17:17:32.640  1959  1976 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-09 17:17:32.640  1959  1976 D SplitWindowPolicy: topRunningActivity=ActivityInfo{9d0934 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-09 17:17:32.645  6553  6553 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
09-09 17:17:32.645  6553  6553 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
09-09 17:17:32.689  1036  2081 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6589 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
09-09 17:17:32.691  1036  2081 I ActivityManager: Killing 5854:com.google.android.gm/u0a64 (adj 15): empty #17
09-09 17:17:32.757  1036  2075 W libprocessgroup: failed to open /acct/uid_10064/pid_5854/cgroup.procs: No such file or directory
09-09 17:17:32.771  6571  6571 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,09-09 17:17:32.836  6589  6589 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,09-09 17:17:32.848  6571  6571 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-09 17:17:32.855  6571  6571 I LibraryLoader: Loading: webviewchromium
09-09 17:17:32.857  6571  6571 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4187-4190)
09-09 17:17:32.857  6571  6571 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 17:17:32.858  6589  6589 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,09-09 17:17:32.861  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
09-09 17:17:32.875  6571  6571 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7f005e4}
,09-09 17:17:32.877  6571  6571 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 17:17:32.877  6571  6571 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 17:17:32.881  6363  6363 D PostponalbeReceiver: OasPackageInstalledReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
09-09 17:17:32.883  1036  1952 I ActivityManager: Killing 5896:com.google.android.talk/u0a72 (adj 15): empty #17
09-09 17:17:32.888  6571  6571 I BrowserStartupController: Initializing chromium process, renderers=0
09-09 17:17:32.889  6571  6571 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 17:17:32.911  6571  6571 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-09 17:17:32.912  6571  6571 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-09 17:17:32.912  6571  6571 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,09-09 17:17:32.914   323  1369 V AudioPolicyService: registerClient() client 0xb558a380, uid 10118
09-09 17:17:32.919  1036  1934 W libprocessgroup: failed to open /acct/uid_10072/pid_5896/cgroup.procs: No such file or directory
09-09 17:17:32.928  6571  6571 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 17:17:32.928  6571  6571 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 17:17:32.928  6571  6571 I Adreno-EGL: Build Date: 12/12/14 금
09-09 17:17:32.928  6571  6571 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 17:17:32.928  6571  6571 I Adreno-EGL: Remote Branch: 
09-09 17:17:32.928  6571  6571 I Adreno-EGL: Local Patches: 
09-09 17:17:32.928  6571  6571 I Adreno-EGL: Reconstruct Branch: 
,09-09 17:17:32.937  1036  1118 D BluetoothManagerService: Message: 20
09-09 17:17:32.937  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@21b0580b:true
09-09 17:17:33.025  6571  6619 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-09 17:17:33.030  6571  6571 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-09 17:17:33.050  6571  6571 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 17:17:33.056  6571  6571 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-09 17:17:33.060  6571  6571 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-09 17:17:33.063  6571  6571 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-09 17:17:33.063  6571  6571 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,09-09 17:17:33.081  6571  6571 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-09 17:17:33.090  6571  6571 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 17:17:33.090  6571  6571 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 17:17:33.118  6571  6631 D OpenGLRenderer: Render dirty regions requested: true
09-09 17:17:33.118  6571  6631 I OpenGLRenderer: Initialized EGL, version 1.4
09-09 17:17:33.138  6571  6631 D OpenGLRenderer: Enabling debug mode 0
09-09 17:17:33.138  1036  1103 W ActivityManager: Activity pause timeout for ActivityRecord{192b4993 u0 com.test.thalitest/.MainActivity t6}
,09-09 17:17:33.148  6571  6571 D Atlas   : Validating map...
09-09 17:17:33.152  1036  1910 D SplitWindow: check instance of lgWin Window{af1eead u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-09 17:17:33.214  6571  6629 D LgDataFeature: LgDataFeature() Constructor: none
,09-09 17:17:33.214  6571  6629 D LgDataFeature: LgDataFeature() Constructor Done, null
09-09 17:17:33.251  1036  1119 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +614ms (total +689ms)
09-09 17:17:33.251  6571  6571 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@38d5603 time:104584
09-09 17:17:33.251  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{192b4993 u0 com.test.thalitest/.MainActivity t6} time:104585
,09-09 17:17:33.420  6571  6571 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-09 17:17:33.490  6571  6629 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-09 17:17:33.490  6571  6629 I chromium: 
,09-09 17:17:33.622   339   379 E GBMv2   : DFP En is all cleared set to be enabled
09-09 17:17:33.622   339   379 E GBMv2   : Set value is all cleared set the max
09-09 17:17:33.622   339   379 I GBMv2   : DFP Enabled. Ignore VFP set
,09-09 17:17:33.627  6571  6644 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435044352
09-09 17:17:33.639  6571  6644 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 17:17:33.639  6571  6644 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 17:17:33.639  6571  6644 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 17:17:33.639  6571  6644 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 17:17:33.639  6571  6644 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-09 17:17:33.640  6571  6644 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1273cb57 added. We now have 1 listener(s)
09-09 17:17:33.645  1036  2075 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:17:33.648  6571  6644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-09 17:17:33.648  6571  6571 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-09 17:17:33.648  6571  6571 I chromium: 
09-09 17:17:33.651  6571  6644 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-09 17:17:33.653  6571  6644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:17:33.653  6571  6644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:17:33.661  6571  6644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 17:17:33.661  6571  6644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 17:17:33.661  6571  6644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 17:17:33.661  6571  6644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-09 17:17:33.661  6571  6644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 17:17:33.661  6571  6644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 17:17:33.661  6571  6644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 17:17:33.661  6571  6644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 17:17:33.661  6571  6644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 17:17:33.661  6571  6644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 17:17:33.661  6571  6644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 17:17:33.661  6571  6644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 17:17:33.661  6571  6644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 17:17:33.661  6571  6644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-09 17:17:33.661  6571  6644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b1d062 added. We now have 1 listener(s)
09-09 17:17:33.661  6571  6644 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:17:33.665  1036  1531 D WifiService: New client listening to asynchronous messages
,09-09 17:17:33.670  6571  6644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 17:17:33.670  6571  6644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-09 17:17:33.672  6571  6644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-09 17:17:33.672  6571  6644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-09 17:17:33.672  6571  6644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-09 17:17:33.676  6571  6644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:17:33.677  1036  1934 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:17:33.678  6571  6644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-09 17:17:33.687  6571  6644 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-09 17:17:33.687  6571  6644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:17:33.687  6571  6644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:33.687  6571  6644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:17:33.687  6571  6644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:33.687  6571  6644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:17:33.687  6571  6644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:33.687  6571  6644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:17:33.687  6571  6644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:17:33.688  6571  6644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-09 17:17:33.688  6571  6644 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:17:33.689  6571  6644 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 17:17:33.694  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:33.697  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:33.736  6571  6571 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-09 17:17:34.472  6571  6647 W jxcore-log: Initializing JXcore engine
,09-09 17:17:34.472  6571  6647 W jxcore-log: JXcore engine is ready
,09-09 17:17:34.564  6647  6647 W Thread-757: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7438]" dev="sockfs" ino=7438 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,09-09 17:17:34.574  6647  6647 W Thread-757: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-09 17:17:34.574  6647  6647 W Thread-757: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8581]" dev="sockfs" ino=8581 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-09 17:17:34.574  6647  6647 W Thread-757: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-09 17:17:34.574  6647  6647 W Thread-757: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[29389]" dev="sockfs" ino=29389 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-09 17:17:34.600  6571  6647 W jxcore-log: Starting JXcore engine
,09-09 17:17:34.718  2784  2784 I MusicWidget: mDelayedStopHandler : unbind
,09-09 17:17:34.722  6571  6647 W jxcore-log: Platform android
09-09 17:17:34.722  6571  6647 W jxcore-log: 
09-09 17:17:34.722  6571  6647 W jxcore-log: Process ARCH arm
09-09 17:17:34.722  6571  6647 W jxcore-log: 
09-09 17:17:34.726  2210  2210 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
09-09 17:17:34.727  2210  2210 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
,09-09 17:17:34.736  2210  2210 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
09-09 17:17:34.747  2210  2210 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
09-09 17:17:34.748  2210  2210 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
09-09 17:17:34.748  2210  2210 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
09-09 17:17:34.752  2210  2210 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
09-09 17:17:34.752  2210  2210 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
09-09 17:17:34.753  1036  2081 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@2f5340bdcom.lge.music.MediaPlaybackService$5@135a56b2
09-09 17:17:34.754  2210  2210 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
09-09 17:17:34.754  2210  2210 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 17:17:34.755  2210  2210 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 17:17:34.755  2210  2210 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 17:17:34.756  2210  2210 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@b999c50
09-09 17:17:34.759  2210  2210 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 17:17:34.760  2210  2210 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
09-09 17:17:34.760  2210  2210 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 17:17:34.760  2210  2210 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
09-09 17:17:34.760  2210  2210 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
09-09 17:17:34.761  2210  2210 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 17:17:34.761  2210  2210 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 17:17:34.762  2210  2210 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 17:17:34.763  2210  2210 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 17:17:34.763  2210  2210 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,09-09 17:17:34.767  2210  2210 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
09-09 17:17:34.768  2210  2210 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
09-09 17:17:34.768  2210  2210 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
,09-09 17:17:34.768  2210  2210 V MediaPlayer[Native]: reset
09-09 17:17:34.772  2210  2210 V MediaPlayer[Native]: setListener
09-09 17:17:34.772  2210  2210 V MediaPlayer[Native]: disconnect
09-09 17:17:34.772  2210  2210 V MediaPlayer[Native]: destructor
09-09 17:17:34.772   323  2998 V AudioFlinger: releasing 18 from 2210 for -1
09-09 17:17:34.772   323  2998 V AudioFlinger:  decremented refcount to 0
09-09 17:17:34.772   323  2998 V AudioFlinger: purging stale effects
09-09 17:17:34.772  2210  2210 V MediaPlayer[Native]: disconnect
09-09 17:17:34.773  2210  2210 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
09-09 17:17:34.774  2210  2210 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
09-09 17:17:34.774  2210  2210 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
09-09 17:17:34.775  2210  2210 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
09-09 17:17:34.775  2210  2210 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
09-09 17:17:34.775  2210  2210 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
09-09 17:17:34.776  2210  2210 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 59594243
09-09 17:17:34.776  2210  2210 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 59594243
,09-09 17:17:34.779  2210  2210 I SmartShareClient: [SmartShareManagerClient] terminate service: 2210/MediaPlaybackService/642009974
09-09 17:17:34.781  2210  2210 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
09-09 17:17:34.781  2210  2210 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@1cb4b980
09-09 17:17:34.783  2210  2210 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
09-09 17:17:34.783  2210  2210 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
09-09 17:17:34.784  2210  2210 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
09-09 17:17:34.784  2210  2210 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
09-09 17:17:34.786  1036  1978 I ActivityManager: Killing 5699:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
09-09 17:17:34.793  2210  2210 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29991
,09-09 17:17:34.857  1036  1994 W libprocessgroup: failed to open /acct/uid_1000/pid_5699/cgroup.procs: No such file or directory
09-09 17:17:34.857  1036  1994 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-09 17:17:34.859  5673  5673 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-09 17:17:34.859  5673  5673 W System.err: android.os.DeadObjectException
09-09 17:17:34.859  5673  5673 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 17:17:34.859  5673  5673 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-09 17:17:34.859  5673  5673 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-09 17:17:34.859  5673  5673 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-09 17:17:34.859  5673  5673 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-09 17:17:34.859  5673  5673 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-09 17:17:34.859  5673  5673 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 17:17:34.859  5673  5673 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 17:17:34.859  5673  5673 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 17:17:34.859  5673  5673 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 17:17:34.859  5673  5673 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:17:34.860  5673  5673 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:17:34.860  5673  5673 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 17:17:34.860  5673  5673 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 17:17:34.860  5673  5673 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-09 17:17:34.860  5673  5673 W System.err: android.os.DeadObjectException
09-09 17:17:34.860  5673  5673 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 17:17:34.860  5673  5673 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-09 17:17:34.860  5673  5673 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-09 17:17:34.860  5673  5673 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-09 17:17:34.860  5673  5673 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-09 17:17:34.860  5673  5673 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-09 17:17:34.860  5673  5673 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 17:17:34.860  5673  5673 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 17:17:34.861  5673  5673 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 17:17:34.861  5673  5673 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 17:17:34.861  5673  5673 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:17:34.861  5673  5673 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:17:34.861  5673  5673 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 17:17:34.861  5673  5673 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 17:17:34.861  5673  5673 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-09 17:17:34.861  5673  5673 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
09-09 17:17:34.863  5673  5673 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-09 17:17:34.863  5673  5673 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-09 17:17:34.913  1036  2053 I ActivityManager: Start proc com.uei.lg.quicksetsdk.ma,xq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6652 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-09 17:17:34.914  5673  5673 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-09 17:17:34.979  6652  6652 D UEI.SmartControl: Quickset Services start...
,09-09 17:17:34.981  6652  6652 I UEI.SmartControl: Manufacture = LGE
09-09 17:17:34.981  6652  6652 D UEI.SmartControl: Id = LGNevo
09-09 17:17:34.983  6652  6652 D UEI.SmartControl: File observer start...
09-09 17:17:34.984  6652  6652 E UEI.SmartControl: IR Port is disabled: false
09-09 17:17:34.984  6652  6652 D UEI.SmartControl: Starting file observer...
09-09 17:17:34.985  6652  6652 D UEI.SmartControl: Extracting JNI libs...
09-09 17:17:34.985  6652  6652 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-09 17:17:35.055  6652  6652 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-09 17:17:35.055  6652  6652 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,09-09 17:17:35.055  6652  6652 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
09-09 17:17:35.074  6571  6647 I jxcore-log: JXcore Cordova bridge is ready!
09-09 17:17:35.074  6571  6647 I jxcore-log: 
09-09 17:17:35.075  6571  6647 W jxcore-log: JXcore engine is started
,09-09 17:17:35.083  6571  6644 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-09 17:17:35.085  6652  6652 I UEI.SmartControl: --- Selecting new region: 6
09-09 17:17:35.086  6652  6652 I UEI.SmartControl: Model = LG-D855
,09-09 17:17:35.088  6652  6652 D UEI.SmartControl: QS Service created
09-09 17:17:35.090  6571  6571 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
09-09 17:17:35.101  6652  6652 I UEI.SmartControl: Service initServices...
09-09 17:17:35.104  6652  6652 D UEI.SmartControl: QS start get config
,09-09 17:17:35.143  6652  6652 D UEI.SmartControl: Loading JNI Libs...
,09-09 17:17:35.464  6652  6652 I UEI.SmartControl: Supports setup maps: true
,09-09 17:17:35.469  6652  6652 D UEI.SmartControl: QS start statue = true Error code = 0
09-09 17:17:35.469  6652  6652 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-09 17:17:35.469  6652  6652 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-09 17:17:35.469  6652  6652 I UEI.SmartControl: ### init IR Blaster...
09-09 17:17:35.473  6652  6652 D serial_port: Configuring serial port
09-09 17:17:35.477  6652  6652 E UEI.SmartControl: UEIBLaster setting for 616
09-09 17:17:35.477  6652  6652 I UEI.SmartControl: Setting serial record hearder size = 2
09-09 17:17:35.477  6652  6652 I UEI.SmartControl: configuring settings for MAXQ616
09-09 17:17:35.477  6652  6652 I UEI.SmartControl: Get version...
,09-09 17:17:35.494  6652  6672 D UEI.SmartControl: serial port data available: 21
,09-09 17:17:35.523  6652  6652 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-09 17:17:35.523  6652  6652 I UEI.SmartControl: IR Blaster version: 256702256704300002
,09-09 17:17:35.523  6652  6652 I UEI.SmartControl: QS saving settings...
,09-09 17:17:35.525  6652  6652 D UEI.SmartControl: IR Blaster version: 25672567
,09-09 17:17:35.543  6652  6672 D UEI.SmartControl: serial port data available: 4
,09-09 17:17:35.580  6652  6675 I UEI.SmartControl: Device manager: loading config....
,09-09 17:17:35.582  6652  6675 D UEI.SmartControl: ----------- loading internal config...
,09-09 17:17:35.583  6652  6652 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-09 17:17:35.588  6652  6652 E UEI.SmartControl: Services init done
09-09 17:17:35.588  6652  6652 D UEI.SmartControl: QS Service init finished
09-09 17:17:35.589  6652  6652 D UEI.SmartControl: QS Service version name: 2.1.91
09-09 17:17:35.589  6652  6652 D UEI.SmartControl: QS Service version code: 201091
,09-09 17:17:35.590  6652  6652 D UEI.SmartControl: Service requested: Control
09-09 17:17:35.602  6652  6675 E UEI.SmartControl: Loading SETTINGS...
,09-09 17:17:35.606  6652  6652 D UEI.SmartControl: Request IControl service: devices are loaded...
09-09 17:17:35.609  1036  1978 I ActivityManager: Killing 5673:com.lge.qremote/u0a112 (adj 15): empty #17
09-09 17:17:35.609  5673  5673 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-09 17:17:35.615  6652  6675 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-09 17:17:35.638  6652  6674 I UEI.SmartControl: Notify AllClients services are ready: 0
09-09 17:17:35.638  6652  6674 D UEI.SmartControl: -----service ready thread exits
,09-09 17:17:35.679  1036  1990 W libprocessgroup: failed to open /acct/uid_10112/pid_5673/cgroup.procs: No such file or directory
,09-09 17:17:35.682  6652  6652 D UEI.SmartControl: Internal service binding...
09-09 17:17:36.610  6492  6492 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,09-09 17:17:36.612  1036  2099 I ActivityManager: Killing 5256:com.android.calendar/u0a13 (adj 15): empty #17
09-09 17:17:36.728  1036  1994 W libprocessgroup: failed to open /acct/uid_10013/pid_5256/cgroup.procs: No such file or directory
,09-09 17:17:37.421  6492  6528 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-09 17:17:40.132  1829  6402 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-09 17:17:40.139   319  6710 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-09 17:17:40.139   319  6710 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com, class = 1, type = 1
09-09 17:17:40.139   319  6710 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com succeed
09-09 17:17:40.332  1829  1829 I ConfigFetchService: fetch service done; releasing wakelock
,09-09 17:17:40.338  1829  1829 I ConfigFetchService: stopping self
09-09 17:17:40.348  2229  2229 I ConfigService: onDestroy
,09-09 17:17:40.582  6652  6676 D UEI.SmartControl: Internal timer expired: 1
,09-09 17:17:40.582  6652  6676 D UEI.SmartControl: unbind internal service
,09-09 17:17:40.594  6652  6652 D UEI.SmartControl: Service.onUnbind: IControl
09-09 17:17:40.598  6652  6652 D UEI.SmartControl: Service.onDestroy
09-09 17:17:40.598  6652  6652 D UEI.SmartControl: Lock is in USE false
09-09 17:17:40.598  6652  6652 D UEI.SmartControl: unbind internal service
09-09 17:17:40.599  6652  6652 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@b999c50
09-09 17:17:40.599  6652  6652 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
,09-09 17:17:40.599  6652  6652 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
09-09 17:17:40.599  6652  6652 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
,09-09 17:17:40.599  6652  6652 W System.err: 	at com.uei.control.Service.c(Unknown Source)
09-09 17:17:40.600  6652  6652 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
09-09 17:17:40.600  6652  6652 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
09-09 17:17:40.600  6652  6652 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
,09-09 17:17:40.600  6652  6652 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
09-09 17:17:40.600  6652  6652 W System.err: 	,at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:17:40.600  6652  6652 W System.err: 	at android.os.Looper.loop(Looper.java:135)
,09-09 17:17:40.600  6652  6652 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 17:17:40.600  6652  6652 W System.err: 	at java.lang.reflect.Method.invoke(Native Method),
09-09 17:17:40.600  6652  6652 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:17:40.600  6652  6652 W System.err: ,	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 17:17:40.600  6652  6652 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-09 17:17:40.600  6652  6652 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@b999c50
,09-09 17:17:40.615  6652  6652 D serial_port: close(fd = 25)
,09-09 17:17:40.629  6652  6652 I UEI.SmartControl: Serial port is closed.
09-09 17:17:40.629  6652  6652 I UEI.SmartControl: Serial port is closed.
09-09 17:17:40.629  6652  6652 D UEI.SmartControl: Blaster closed
09-09 17:17:40.629  6652  6652 D UEI.SmartControl: Shut down QS...
09-09 17:17:40.629  6652  6652 D UEI.SmartControl: Stopping QS lib
09-09 17:17:40.629  6652  6652 D UEI.SmartControl: QS lib stop result = true
09-09 17:17:40.629  6652  6652 D UEI.SmartControl: Stopped QS lib
,09-09 17:17:40.631  6652  6652 D UEI.SmartControl: Stopped file observer...
,09-09 17:17:40.631  6652  6652 D UEI.SmartControl: QS shutdown complete
,09-09 17:17:44.805  2210  2210 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19980
,09-09 17:17:45.130  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-09 17:17:45.130  6571  6647 I jxcore-log: 
,09-09 17:17:45.133  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-09 17:17:45.133  6571  6647 I jxcore-log: 
09-09 17:17:45.138  6571  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:17:45.138  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:45.138  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:17:45.138  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:45.138  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:17:45.138  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:45.138  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:17:45.138  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:17:45.141  6571  6647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:45.143  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 17:17:45.143  6571  6647 I jxcore-log: 
,09-09 17:17:45.144  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-09 17:17:45.144  6571  6647 I jxcore-log: 
09-09 17:17:45.257  1036  1103 I ActivityManager: Waited long enough for: ServiceRecord{3a1b4b1f u0 com.google.android.gms/.wearable.service.WearableService}
,09-09 17:17:45.641  6571  6647 D executeNativeTests: Running unit tests
,09-09 17:17:45.723  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 17:17:45.723  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ffccab2 added. We now have 2 listener(s)
,09-09 17:17:45.723  1036  2081 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-09 17:17:45.725  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 17:17:45.725  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 17:17:45.725  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:17:45.726  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-09 17:17:45.726  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 added. We now have 2 listener(s)
,09-09 17:17:45.726  6571  6647 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:17:45.726  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 17:17:45.728  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:17:45.732  6571  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:17:45.732  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:45.732  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:17:45.732  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:45.732  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:17:45.732  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:45.732  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:17:45.732  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:17:45.734  6571  6647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:45.734  6571  6647 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:17:45.736  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:45.737  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:45.739  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 17:17:45.740  6571  6647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 17:17:45.740  6571  6647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 17:17:45.742  6571  6647 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-09 17:17:45.743  6571  6647 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 17:17:45.743  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 17:17:45.743  6571  6647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 17:17:45.743  6571  6647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 17:17:45.744  6571  6647 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:45.744  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.744  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:45.745  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.745  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.745  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:17:45.745  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:17:45.745  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ffccab2 removed from the list
09-09 17:17:45.745  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.745  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 removed from the list
09-09 17:17:45.745  6571  6647 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.745  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.746  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.746  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.747  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:45.747  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.747  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.747  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
09-09 17:17:45.748  6571  6647 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-09 17:17:45.748  6571  6647 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:45.748  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.748  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operati,on, skipping...
09-09 17:17:45.749  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.749  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.749  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.749  6571  6647 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ffccab2 not in the list
09-09 17:17:45.749  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.749  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
09-09 17:17:45.749  6571  6647 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 17:17:45.749  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.749  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.749  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.749  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.750  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:45.750  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.750  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.750  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
,09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 17:17:45.754  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 17:17:45.754  6571  6647 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:17:45.755  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.755  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:45.755  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.755  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:45.755  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.755  6571  6647 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ffccab2 not in the list
09-09 17:17:45.755  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.755  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
09-09 17:17:45.755  6571  6647 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.755  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:45.755  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.755  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.755  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:45.755  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:45.756  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.756  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.756  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
09-09 17:17:45.756  6571  6647 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 17:17:45.758  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:17:45.760  6571  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-09 17:17:45.760  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:45.760  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:17:45.760  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:45.760  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:17:45.760  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:45.760  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:17:45.760  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:17:45.761  6571  6647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
09-09 17:17:45.761  6571  6647 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:17:45.763  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:45.764  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:45.764  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 17:17:45.764  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:17:45.764  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:17:45.764  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:17:45.764  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 17:17:45.768  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 17:17:45.768  1036  1952 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:17:45.771  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 17:17:45.775  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
09-09 17:17:45.777  6571  6647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-09 17:17:45.777  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 17:17:45.778  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:17:45.779  6571  6647 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-09 17:17:45.779  6571  6647 I io.jxcore.node.ConnectionHelper: start: OK
09-09 17:17:45.781  6571  6647 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:45.781  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.781  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:45.781  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-09 17:17:45.781  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.781  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:17:45.781  6571  6647 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ffccab2 not in the list
09-09 17:17:45.781  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.781  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
,09-09 17:17:45.781  6571  6647 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.781  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.782  6571  6647 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 17:17:45.783  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:17:45.785  6571  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-09 17:17:45.785  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:45.785  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:17:45.785  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:45.785  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:17:45.785  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:45.785  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:17:45.785  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:17:45.786  6571  6647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 17:17:45.786  6571  6647 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 17:17:45.787  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-09 17:17:45.788  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:45.788  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:17:45.788  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-09 17:17:45.788  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:17:45.788  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:17:45.788  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 17:17:45.791  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 17:17:45.791  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:17:45.792  6571  6647 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 17:17:45.792  6571  6647 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 17:17:45.793  6571  6647 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:45.793  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.794  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:45.794  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 17:17:45.794  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.794  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:17:45.794  6571  6647 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ffccab2 not in the list
09-09 17:17:45.794  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:17:45.794  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
09-09 17:17:45.794  6571  6647 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.794  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.794  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:45.794  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.795  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:45.795  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.796  6571  6647 D BluetoothLeScanner: could not find callback wrapper
,09-09 17:17:45.796  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:17:45.796  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.796  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
09-09 17:17:45.797  6571  6647 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false,
09-09 17:17:45.798  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:17:45.799  6571  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-09 17:17:45.799  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:45.799  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:17:45.799  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:45.799  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:17:45.799  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:45.799  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:17:45.799  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true,
09-09 17:17:45.800  6571  6647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:45.800  6571  6647 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:17:45.801  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:45.802  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:45.803  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:17:45.803  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:17:45.803  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
09-09 17:17:45.803  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:17:45.803  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 17:17:45.805  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 17:17:45.805  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:17:45.806  6571  6647 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 17:17:45.806  6571  6647 I io.jxcore.node.ConnectionHelper: start: OK
09-09 17:17:45.806  6571  6647 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:17:45.806  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.807  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:45.807  6571  6647 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:17:45.807  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.807  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:45.808  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.808  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:45.808  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:17:45.808  6571  6647 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ffccab2 not in the list
09-09 17:17:45.808  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:17:45.808  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
09-09 17:17:45.808  6571  6647 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.808  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.808  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-09 17:17:45.808  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.809  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:45.809  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 17:17:45.809  6571  6647 D BluetoothLeScanner: could not find callback wrapper
09-09 17:17:45.809  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
09-09 17:17:45.809  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.809  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
09-09 17:17:45.809  6571  6647 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-09 17:17:45.810  6571  6647 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:45.810  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.810  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 17:17:45.810  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.810  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.810  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-09 17:17:45.810  6571  6647 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ffccab2 not in the list
09-09 17:17:45.810  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.810  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
,09-09 17:17:45.810  6571  6647 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 17:17:45.810  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.810  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-09 17:17:45.810  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.810  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,09-09 17:17:45.811  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:45.811  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.811  6571  6647 D BluetoothLeScanner: could not find callback wrapper,
09-09 17:17:45.811  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:17:45.811  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.811  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
,09-09 17:17:45.812  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 17:17:45.812  6571  6647 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:45.812  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 17:17:45.812  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
09-09 17:17:45.812  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.812  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.812  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:45.813  6571  6647 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ffccab2 not in the list
09-09 17:17:45.813  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.813  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list,
,09-09 17:17:45.813  6571  6647 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 17:17:45.813  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-09 17:17:45.813  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.813  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-09 17:17:45.813  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.813  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 17:17:45.813  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.814  6571  6647 D BluetoothLeScanner: could not find callback wrapper
09-09 17:17:45.814  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 17:17:45.814  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.814  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
09-09 17:17:45.814  6571  6647 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-09 17:17:45.814  6571  6647 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:17:45.814  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.814  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:45.815  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 17:17:45.815  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:45.815  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.815  6571  6647 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ffccab2 not in the list
09-09 17:17:45.815  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:17:45.815  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
09-09 17:17:45.815  6571  6647 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.815  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-09 17:17:45.815  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.815  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.815  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.815  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 17:17:45.815  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.816  6571  6647 D BluetoothLeScanner: could not find callback wrapper
09-09 17:17:45.816  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:17:45.816  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.816  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
,09-09 17:17:45.816  6571  6647 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-09 17:17:45.817  6571  6647 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:45.817  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 17:17:45.817  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:45.817  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.817  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.817  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.817  6571  6647 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ffccab2 not in the list,
,09-09 17:17:45.817  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.817  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
09-09 17:17:45.817  6571  6647 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.817  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.817  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.817  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.817  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.818  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:45.818  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.818  6571  6647 D BluetoothLeScanner: could not find callback wrapper
09-09 17:17:45.818  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:17:45.818  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:17:45.818  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
,09-09 17:17:45.819  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 17:17:45.819  6571  6647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 17:17:45.819  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 17:17:45.819  6571  6647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 17:17:45.819  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-09 17:17:45.819  6571  6647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 17:17:45.819  6571  6647 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:17:45.819  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.819  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 17:17:45.819  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.819  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:45.819  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.819  6571  6647 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ffccab2 not in the list
09-09 17:17:45.819  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:17:45.819  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
09-09 17:17:45.819  6571  6647 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.819  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:45.819  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.819  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.819  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-09 17:17:45.820  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:45.820  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.821  6571  6647 D BluetoothLeScanner: could not find callback wrapper
,09-09 17:17:45.821  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:17:45.821  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.821  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
,09-09 17:17:45.821  6571  6647 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 17:17:45.821  6571  6647 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 17:17:45.821  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-09 17:17:45.824  6571  6647 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 17:17:45.824  6571  6647 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-09 17:17:45.824  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 17:17:45.824  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 17:17:45.824  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 17:17:45.824  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 17:17:45.824  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 17:17:45.824  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-09 17:17:45.824  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 17:17:45.824  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 17:17:45.824  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 17:17:45.824  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 17:17:45.824  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 17:17:45.824  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 17:17:45.824  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 17:17:45.824  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 17:17:45.824  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-09 17:17:45.824  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 17:17:45.825  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 17:17:45.825  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 17:17:45.825  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 17:17:45.825  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 17:17:45.825  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 17:17:45.825  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 17:17:45.825  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-09 17:17:45.825  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 17:17:45.825  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 17:17:45.825  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 17:17:45.825  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 17:17:45.825  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 17:17:45.825  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 17:17:45.825  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 17:17:45.825  6571  6647 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 17:17:45.825  6571  6647 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-09 17:17:45.825  6571  6647 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-09 17:17:45.825  6571  6647 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 17:17:45.825  6571  6647 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 17:17:45.825  6571  6647 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-09 17:17:45.825  6571  6647 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 17:17:45.825  6571  6647 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 17:17:45.825  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-09 17:17:45.827  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-09 17:17:45.828  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-09 17:17:45.828  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-09 17:17:45.828  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-09 17:17:45.828  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-09 17:17:45.828  6571  6647 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-09 17:17:45.829  6571  6647 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 17:17:45.829  6571  6647 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-09 17:17:45.829  6571  6647 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:45.829  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.829  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:45.830  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 17:17:45.830  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.830  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.830  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-09 17:17:45.834  6571  6711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 821)
09-09 17:17:45.837  6571  6647 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ffccab2 not in the list
09-09 17:17:45.837  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.837  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
09-09 17:17:45.837  6571  6647 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.838  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:45.838  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.838  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-09 17:17:45.838  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:45.838  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:45.838  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.839  6571  6647 D BluetoothLeScanner: could not find callback wrapper
09-09 17:17:45.839  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:17:45.839  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.839  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
09-09 17:17:45.839  6571  6647 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-09 17:17:45.840  6571  6647 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:17:45.840  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.840  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:45.840  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.840  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.840  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.840  6571  6647 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ffccab2 not in the list
09-09 17:17:45.840  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.840  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
,09-09 17:17:45.840  6571  6647 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.840  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.840  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.840  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.840  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.841  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:45.841  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.841  6571  6647 D BluetoothLeScanner: could not find callback wrapper
,09-09 17:17:45.841  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:17:45.842  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.842  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
09-09 17:17:45.842  6571  6647 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 17:17:45.843  6571  6647 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:45.843  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.843  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:45.844  6571  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 821
,09-09 17:17:45.844  6571  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 821)
09-09 17:17:45.844  6571  6712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 821)
09-09 17:17:45.847  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.847  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.847  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.847  6571  6647 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ffccab2 not in the list
09-09 17:17:45.847  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.847  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
,09-09 17:17:45.847  6571  6647 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.847  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.847  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.847  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.847  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.848  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:45.848  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.849  6571  6647 D BluetoothLeScanner: could not find callback wrapper
09-09 17:17:45.849  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 17:17:45.849  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.849  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
09-09 17:17:45.849  6571  6647 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 17:17:45.850  6571  6647 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 17:17:45.850  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 17:17:45.850  6571  6647 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 17:17:45.850  6571  6647 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 17:17:45.850  6571  6647 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,09-09 17:17:45.850  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 17:17:45.850  6571  6647 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 17:17:45.850  6571  6647 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 17:17:45.850  6571  6647 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 17:17:45.850  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 17:17:45.850  6571  6647 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-09 17:17:45.850  6571  6647 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:45.850  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 17:17:45.850  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:45.851  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.851  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.851  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.851  6571  6647 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ffccab2 not in the list
09-09 17:17:45.851  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.851  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
09-09 17:17:45.851  6571  6647 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 17:17:45.851  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.851  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.851  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.851  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.852  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:45.852  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.857  6571  6647 D BluetoothLeScanner: could not find callback wrapper
09-09 17:17:45.857  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:17:45.857  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:17:45.857  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
09-09 17:17:45.857  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.857  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.857  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.857  6571  6647 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ffccab2 not in the list
09-09 17:17:45.857  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.857  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
09-09 17:17:45.857  6571  6647 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 17:17:45.857  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.857  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.858  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.858  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
09-09 17:17:45.858  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.858  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.858  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.858  6571  6647 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ffccab2 not in the list
09-09 17:17:45.858  6571  6647 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:17:45.858  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.858  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:45.858  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.858  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.858  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.858  6571  6647 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ffccab2 not in the list
09-09 17:17:45.858  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.858  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
,09-09 17:17:45.858  6571  6647 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.858  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.858  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.859  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.859  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.859  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:45.859  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.860  6571  6647 D BluetoothLeScanner: could not find callback wrapper
09-09 17:17:45.860  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 17:17:45.860  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.861  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
09-09 17:17:45.862  6571  6647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 17:17:45.862  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:17:45.862  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 17:17:45.863  6571  6647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 17:17:45.863  6571  6647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 17:17:45.863  6571  6571 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-09 17:17:45.863  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 17:17:45.863  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 17:17:45.864  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.864  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 17:17:45.864  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 17:17:45.864  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 17:17:45.864  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.864  6571  6647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 17:17:45.867  6571  6571 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-09 17:17:45.867  6571  6647 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ffccab2 not in the list
09-09 17:17:45.867  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.867  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 17:17:45.867  6571  6647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 17:17:45.867  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 17:17:45.868  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 17:17:45.868  1036  2075 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:17:45.869  6571  6647 D BluetoothLeScanner: could not find callback wrapper
,09-09 17:17:45.869  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:17:45.869  6571  6647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 17:17:45.869  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.869  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.869  6571  6647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:17:45.870  6571  6571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:17:45.870  6571  6571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:17:45.870  6571  6571 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:17:45.870  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
,09-09 17:17:45.870  6571  6647 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:45.870  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.870  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:45.870  6571  6719 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 17:17:45.872  3866  3883 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
09-09 17:17:45.872  6571  6719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 17:17:45.872  6571  6719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 17:17:45.872  6571  6719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 17:17:45.873  6571  6571 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 17:17:45.873  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.873  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.873  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.873  6571  6647 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ffccab2 not in the list
09-09 17:17:45.873  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.873  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
09-09 17:17:45.873  6571  6647 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.873  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.873  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.873  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.873  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.874  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:45.874  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.874  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.874  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
09-09 17:17:45.875  6571  6647 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-09 17:17:45.878  6571  6647 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 17:17:45.878  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 17:17:45.879  6571  6647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 17:17:45.880  6571  6647 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:45.880  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.880  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:45.880  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManage,r: dispose
09-09 17:17:45.880  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.880  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.880  6571  6647 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ffccab2 not in the list
09-09 17:17:45.880  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.880  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
09-09 17:17:45.880  6571  6647 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.880  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.880  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.880  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.880  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.881  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:45.881  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.881  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.881  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
09-09 17:17:45.883  1036  2099 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:17:45.884  1036  1994 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:17:45.885  1036  1704 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:17:45.885  6571  6647 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:45.885  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.885  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:45.886  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.886  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.886  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.886  6571  6647 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ffccab2 not in the list
09-09 17:17:45.886  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.886  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
09-09 17:17:45.886  6571  6647 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.886  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.886  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.886  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.886  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.887  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:45.887  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.887  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.887  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
09-09 17:17:45.887  6571  6647 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:45.887  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:45.887  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:45.888  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:45.888  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.888  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.888  6571  6647 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ffccab2 not in the list
09-09 17:17:45.888  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.888  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
09-09 17:17:45.888  6571  6647 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:45.888  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.888  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.888  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:45.888  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.888  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:45.888  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.888  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.888  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c10ba03 not in the list
09-09 17:17:45.889  6571  6647 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-09 17:17:45.889  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 17:17:45.889  6571  6647 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-09 17:17:45.889  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 17:17:45.889  6571  6647 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-09 17:17:45.890  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 17:17:45.891  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 17:17:45.891  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-09 17:17:45.891  6571  6647 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-09 17:17:45.891  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 17:17:45.891  6571  6647 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-09 17:17:45.891  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 17:17:45.892  6571  6647 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-09 17:17:45.892  6571  6647 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-09 17:17:45.892  6571  6647 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-09 17:17:45.892  6571  6647 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-09 17:17:45.892  6571  6647 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-09 17:17:45.893  6571  6647 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-09 17:17:45.893  6571  6647 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-09 17:17:45.893  6571  6647 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-09 17:17:45.893  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:17:45.893  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b084c98 added. We now have 2 listener(s)
09-09 17:17:45.893  6571  6647 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:17:45.894  6571  6647 D BluetoothAdapter: enable(): BT is already enabled..!
09-09 17:17:45.895  1036  1051 D WifiServiceImplEx: setWifiEnabled: true pid=6571, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-09 17:17:45.895  1036  1051 D WifiService: setWifiEnabled: true pid=6571, uid=10118
09-09 17:17:45.895  1036  1051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 17:17:45.896  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:17:45.896  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f6f1cf1 added. We now have 3 listener(s)
09-09 17:17:45.896  6571  6647 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:17:45.899  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:17:45.899  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2086f0d6 added. We now have 4 listener(s)
09-09 17:17:45.899  6571  6647 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:17:45.900  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:17:45.900  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1259ef57 added. We now have 5 listener(s)
09-09 17:17:45.900  6571  6647 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:17:45.901  1036  1051 D WifiServiceImplEx: setWifiEnabled: false pid=6571, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-09 17:17:45.902  1036  1051 D WifiService: setWifiEnabled: false pid=6571, uid=10118
09-09 17:17:45.902  1036  1051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 17:17:45.913  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 17:17:45.914  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 17:17:45.914  1036  1036 D Ulp_jni : JNI:system_update. Event-4
09-09 17:17:45.914  1036  1525 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-09 17:17:45.914  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-09 17:17:45.915  1036  1525 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-09 17:17:45.915  1036  1525 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-09 17:17:45.915  1036  1525 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-09 17:17:45.915  1036  1525 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-09 17:17:45.915  1036  1525 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 17:17:45.915  1036  1525 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 17:17:45.916  1036  1910 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:17:45.916  1036  1910 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@27a63e66 mBinding = false
09-09 17:17:45.916  1036  1525 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 17:17:45.916  1036  1525 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-09 17:17:45.921  1036  1525 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-09 17:17:45.921  1036  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:45.922  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:45.922  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 17:17:45.922  2618  2618 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 17:17:45.922  1036  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 17:17:45.922  1036  1525 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 17:17:45.922  1036  1525 D WifiNative-wlan0: SET ps 1: returned true
09-09 17:17:45.922  1036  2782 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:45.922   319   880 D CommandListener: Clearing all IP addresses on wlan0
09-09 17:17:45.931  1036  1118 D BluetoothManagerService: Message: 2
09-09 17:17:45.935  1036  1118 D BluetoothManagerService: Sending off request.
09-09 17:17:45.936  3866  3883 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-09 17:17:45.936  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 17:17:45.937  3866  3948 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-09 17:17:45.937  1036  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 17:17:45.937  3866  3948 D BluetoothAdapterProperties: Setting state to 13
09-09 17:17:45.937  3866  3948 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 17:17:45.937  1036  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
09-09 17:17:45.937  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 17:17:45.937  1036  1036 D Ulp_jni : JNI:system_update. Event-4
09-09 17:17:45.937  3866  3948 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 17:17:45.938  3866  3948 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-09 17:17:45.941  1036  1118 D BluetoothManagerService: Message: 60
09-09 17:17:45.941  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-09 17:17:45.941  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,09-09 17:17:45.947  1959  1959 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-09 17:17:45.949  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:17:45.949  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:17:45.950  1036  1036 D WifiHS20: hidePasspointNotification off =false
09-09 17:17:45.950  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:45.950  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:45.950  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 17:17:45.958  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 17:17:45.964  6571  6711 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-09 17:17:45.966  1036  1525 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 17:17:45.966  1036  1522 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:45.966  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:45.966  1036  1522 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@d312d22
09-09 17:17:45.966  1036  1522 D LGWifiP2pService: P2pDisablingState
09-09 17:17:45.966  1036  1522 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:45.966  1036  1522 D LGWifiP2pService: p2p socket connection lost
09-09 17:17:45.966  1036  1522 D LGWifiP2pService: P2pDisabledState
09-09 17:17:45.967  3866  3952 D BluetoothAdapterProperties: Scan Mode:20
09-09 17:17:45.967  1036  1525 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-09 17:17:45.967  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 17:17:45.967  2618  2618 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 17:17:45.968  1036  1522 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:45.968  1036  1522 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:45.968  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:17:45.969  1036  1036 D WifiHS20: hidePasspointNotification off =false
09-09 17:17:45.969  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:45.969  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 17:17:45.969  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 17:17:45.969  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
09-09 17:17:45.969  1036  1036 D RttService: SCAN_AVAILABLE : 1
09-09 17:17:45.970  1036  1543 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:45.970  1036  1544 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:45.972  1959  1959 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-09 17:17:45.974  1959  1959 D WfdsService: WifiP2pState is changed : false
09-09 17:17:45.974  1959  2335 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-09 17:17:45.974  1959  2335 D WfdsService: Set the WFDS Monitor: false
09-09 17:17:45.975  3866  3948 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-09 17:17:45.975  3866  4250 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 17:17:45.975  3866  4212 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 17:17:45.976  3866  4209 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-09 17:17:45.976  3866  4209 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 17:17:45.976  3866  4209 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-09 17:17:45.976  3866  4209 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-09 17:17:45.976  3866  4209 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-09 17:17:45.976  3866  4209 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-09 17:17:45.976  3866  4209 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-09 17:17:45.976  3866  4209 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-09 17:17:45.976  1959  2335 D WfdsMonitor: WFDS Monitor is stopped
09-09 17:17:45.976  3866  3948 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-09 17:17:45.976  1959  2335 D WfdsService: STATE : WfdsDisabledState - enter
09-09 17:17:45.976  1959  2693 D CtrlSupplicant: Received on exit socket, terminate
09-09 17:17:45.976  1959  2693 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-09 17:17:45.976  1959  2693 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-09 17:17:45.976  3866  4269 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 17:17:45.976  1959  2693 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-09 17:17:45.977  3866  4272 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 17:17:45.977  1959  2335 W WfdsService: DefaultState - msg [9445378] is not handled
09-09 17:17:45.977  1959  2339 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-09 17:17:45.977  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:45.977  3866  4040 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-09 17:17:45.977  3866  4040 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-09 17:17:45.977  6571  6647, V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:17:45.977  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:45.977  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:17:45.977  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:45.977  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:45.977  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:45.977  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:45.977  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:17:45.978  1036  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 17:17:45.978  1036  1525 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 17:17:45.978  1036  1525 D WifiNative-wlan0: SET ps 1: returned true
09-09 17:17:45.978  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:45.978  6571  6647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:17:45.978  3866  4040 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 17:17:45.979  3866  4040 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 17:17:45.979  3866  4040 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 17:17:45.979  3866  4040 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 17:17:45.979  3866  4040 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:17:45.979  3866  4040 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 17:17:45.979  3866  4040 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 17:17:45.979  3866  4040 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 17:17:45.979  3866  4040 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 17:17:45.979  3866  4040 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-09 17:17:45.979  3866  4040 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-09 17:17:45.979  6571  6647 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:17:45.979  3866  4040 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-09 17:17:45.982  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:17:45.982  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 17:17:45.983  6571  6711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 821)
09-09 17:17:45.987  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:45.987  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:45.987  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:45.987  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:17:45.987  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:45.987  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:45.987  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:45.987  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:45.987  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:17:45.988   319   880 D CommandListener: Clearing all IP addresses on wlan0
09-09 17:17:45.989  1036  1532 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-09 17:17:45.989  1036  1532 D DSQN    : disableDataServiceNotify
09-09 17:17:45.989  1036  1532 D DSQN    : stop dsqn bin
09-09 17:17:45.989  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:45.989  6571  6571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:17:45.988  1036  1768 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
09-09 17:17:45.990  1036  2780 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:45.990  1036  2780 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:45.990  1036  2780 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-09 17:17:45.990  1036  2780 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:45.990  1036  2780 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
09-09 17:17:45.992  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:17:45.992  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:17:45.993  1036  1532 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-09 17:17:45.995  1036  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:17:45.995  1036  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 17:17:45.995  1036  1532 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 17:17:45.995  1036  1525 D WifiNative-p2p0: doBoolean: TERMINATE
09-09 17:17:45.995  1036  1532 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-09 17:17:45.996  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:45.996  1036  1532 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-09 17:17:45.996  1036  1532 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-09 17:17:45.996  1036  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 17:17:45.997  1036  1036 D WifiHS20: hidePasspointNotification off =false
09-09 17:17:45.997  1036  1525 D WifiNative-p2p0: TERMINATE: returned true
09-09 17:17:45.997  1036  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 17:17:45.997  1036  1525 E WifiStateMachine: useWiFiOffloading() : false
09-09 17:17:45.997  1036  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 17:17:45.997  1589  1795 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-09 17:17:45.998   319  6733 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-09 17:17:45.998  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-09 17:17:45.998  1036  2780 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-09 17:17:45.999  1036  2780 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:45.999  1036  2780 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:45.999  1036  2780 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-09 17:17:46.000  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:46.000  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:46.000  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 17:17:46.012  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-09 17:17:46.012  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, ,mWifiLevel = 0
,09-09 17:17:46.013  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:17:46.038  1036  1978 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6734 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-09 17:17:46.039  1036  1532 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:46.040  1036  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 17:17:46.040  1036  1532 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:46.040  1036  1532 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:17:46.040  1036  1532 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:17:46.041  1864  1864 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:17:46.041  1864  1864 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-09 17:17:46.042  3866  3866 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:46.042  3866  3866 D BluetoothMapService: STATE_TURNING_OFF
09-09 17:17:46.042  3866  3866 V BluetoothMapService: Handler(): got msg=4
09-09 17:17:46.042  3866  3866 D BluetoothMapService: MAP Service closeService in
09-09 17:17:46.042  3866  3866 D BluetoothMapMasInstance: MAP Service shutdown
09-09 17:17:46.043  3866  3866 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 17:17:46.043  3866  3866 V BluetoothMapService: MAP Service closeService out
09-09 17:17:46.043  3866  3866 V BtOppService: Receiver DISABLED_ACTION 
09-09 17:17:46.043  3866  3866 I BtOppRfcommListener: stopping Accept Thread
09-09 17:17:46.043  1036  1532 D NetworkManagementService: Removing idletimer
09-09 17:17:46.043  3866  3866 V BtOppRfcommListener: close mBtServerSocket
09-09 17:17:46.043  3866  3866 V BtOppRfcommListener: waiting for thread to terminate
09-09 17:17:46.043  3866  4250 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 17:17:46.044  1036  1532 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:46.044  3866  3866 V BtOppRfcommListener: done waiting for thread to terminate
09-09 17:17:46.044  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:46.044  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:46.044  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:46.044  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:17:46.044  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:17:46.044  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:46.044  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:46.044  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:46.044  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:17:46.045  1959  1959 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:46.045  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:1,7:46.045  6571  6571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:17:46.057  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 17:17:46.074  1036  1103 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6751 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-09 17:17:46.074  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 17:17:46.075  1959  1959 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-09 17:17:46.076  1036  1525 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:17:46.076  1036  1525 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 17:17:46.077  1036  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 17:17:46.077  1036  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 17:17:46.078  3866  3866 V BtOppService: onDestroy
09-09 17:17:46.079  3866  3866 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-09 17:17:46.080  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:46.082  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:46.082  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:46.082  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:46.082  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:17:46.082  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:17:46.082  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:46.082  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:46.082  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:46.082  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:17:46.083  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:46.083  6571  6571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:17:46.084  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:46.086  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:46.088  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:46.091  1036  1990 I art     : Explicit concurrent mark sweep GC freed 28678(1437KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.613ms total 146.170ms
09-09 17:17:46.092  1036  1532 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-09 17:17:46.093  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 17:17:46.093  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-09 17:17:46.093  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:17:46.093  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-09 17:17:46.093  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 17:17:46.093  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 17:17:46.094  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 17:17:46.094  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 17:17:46.094  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 17:17:46.094  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,09-09 17:17:46.109  2618  2618 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-09 17:17:46.109  2618  2618 I wpa_supplicant: monitor socket send errors count : 1
09-09 17:17:46.109  2618  2618 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1959-2\x00 that cannot receive messages
09-09 17:17:46.111  1036  2681 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-09 17:17:46.111  1036  2681 D WifiMonitor: Dropping event because (p2p0) is stopped
09-09 17:17:46.121  6751  6751 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 17:17:46.121  6751  6751 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-09 17:17:46.121  6751  6751 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 17:17:46.121  6751  6751 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-09 17:17:46.122  6751  6751 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 17:17:46.122  6751  6751 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 17:17:46.133  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 17:17:46.133  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:17:46.134  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:17:46.138  6734  6734 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 17:17:46.144  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 17:17:46.145  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:17:46.145  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:17:46.146  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 17:17:46.149  2618  2618 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 17:17:46.149  1036  2681 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-09 17:17:46.149  1036  2681 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 17:17:46.149  1036  2681 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 17:17:46.150  1036  2681 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-09 17:17:46.150  2618  2618 W wpa_supplicant: USIM:  scard_deinit function
09-09 17:17:46.150  1036  2681 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 17:17:46.150  1036  1118 D Tethering: InitialState.processMessage what=4
09-09 17:17:46.151  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 17:17:46.151  1036  1525 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=117468
09-09 17:17:46.151  1036  1525 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=117468
09-09 17:17:46.152  1036  1525 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:17:46.152  1036  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:17:46.152  1036  2681 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 17:17:46.153  1036  1525 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=117470  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-09 17:17:46.154  1036  1525 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=117470  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-09 17:17:46.155  6734  6734 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 17:17:46.155  6734  6734 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 17:17:46.157  1036  2099 I ActivityManager: Killing 5942:com.android.providers.calendar/u0a14 (adj 15): empty #17
09-09 17:17:46.166  1036  2782 D DhcpStateMachine: StoppedState
,09-09 17:17:46.166  1036  2782 D DhcpStateMachine: StoppedState{ when=-188ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:46.189  1036  2081 W libprocessgroup: failed to open /acct/uid_10014/pid_5942/cgroup.procs: No such file or directory
,09-09 17:17:46.191  1036  1525 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-09 17:17:46.192  1036  1525 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-09 17:17:46.230  6751  6751 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-09 17:17:46.234  3866  3866 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 17:17:46.235  3866  3866 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:46.235  3866  3866 V BluetoothPbapReceiver: ***********state = 13
09-09 17:17:46.236  3866  3866 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-09 17:17:46.237  3866  3866 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:46.237  3866  3866 V BluetoothPbapService: state: 13
09-09 17:17:46.237  3866  3866 V BluetoothPbapService: Pbap Service closeService in
09-09 17:17:46.239  2229  2229 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 17:17:46.239  2618  2618 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-09 17:17:46.240  3866  3866 V BluetoothPbapService: successfully stopped pbap service
09-09 17:17:46.240  1036  2681 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-09 17:17:46.240  3866  3866 V BluetoothPbapService: Pbap Service closeService out
09-09 17:17:46.240  1036  2681 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-09 17:17:46.240  3866  3866 V BluetoothPbapService: Pbap Service onDestroy
09-09 17:17:46.240  3866  3866 V BluetoothPbapService: Pbap Service closeService in
09-09 17:17:46.240  3866  3866 V BluetoothPbapService: Pbap Service closeService out
09-09 17:17:46.240  3866  3866 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-09 17:17:46.240  1036  2681 D WifiMonitor: Disconnecting from the supplicant, no more events
09-09 17:17:46.245  1036  1525 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,09-09 17:17:46.260  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:17:46.291  1036  1994 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6772 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-09 17:17:46.305  6751  6751 D LgDataFeature: LgDataFeature() Constructor: none
,09-09 17:17:46.305  6751  6751 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 17:17:46.314  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:17:46.322  1036  1118 D BluetoothManagerService: Message: 20
09-09 17:17:46.322  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1845acf9:true
09-09 17:17:46.333  1036  1118 D BluetoothManagerService: Message: 30
,09-09 17:17:46.338  1036  1118 D BluetoothManagerService: Message: 30
,09-09 17:17:46.341  6751  6751 D LocalBluetoothProfileManager: Adding local MAP profile
09-09 17:17:46.342  6751  6751 D BluetoothMap: Create BluetoothMap proxy object
09-09 17:17:46.343  1036  1118 D BluetoothManagerService: Message: 30
09-09 17:17:46.347  1036  1525 D WifiOffDelayIfNotUsed: stopMonitoring
09-09 17:17:46.347  1036  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 17:17:46.347  1036  1525 E WifiStateMachine: useWiFiOffloading() : false
09-09 17:17:46.347  1036  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 17:17:46.348  1959  1959 D WfdsService: Supplicant Connection state is changed : false
09-09 17:17:46.348  1959  2335 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-09 17:17:46.348  1959  2335 D WfdsService: Set the WFDS Monitor: false
09-09 17:17:46.348  1959  2335 D WfdsMonitor: WFDS Monitor is stopped
,09-09 17:17:46.350  1036  1118 D BluetoothManagerService: Message: 30
09-09 17:17:46.352  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:17:46.352  1959  1959 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-09 17:17:46.353  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-09 17:17:46.354  1036  1530 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-09 17:17:46.354  1036  1530 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-09 17:17:46.355  2491  2491 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:46.355  6751  6751 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-09 17:17:46.357  6751  6751 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
09-09 17:17:46.357  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:46.357  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:46.357  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:46.357  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:17:46.357  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:17:46.357  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:46.357  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:46.357  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:46.357  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:17:46.361  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:46.361  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:46.361  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:46.361  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:17:46.361  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:17:46.361  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:46.361  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:46.361  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:46.361  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:17:46.371  6571  6571 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-09 17:17:46.376  6751  6751 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,09-09 17:17:46.382  6751  6751 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-09 17:17:46.394  6751  6751 D DockEventReceiver: finishStartingService: stopping service
,09-09 17:17:46.406  6751  6751 D BluetoothInputDevice: Proxy object connected
09-09 17:17:46.407  6751  6751 D HidProfile: Bluetooth service connected
,09-09 17:17:46.410  6751  6751 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 17:17:46.410  6751  6751 D PanProfile: Bluetooth service connected
09-09 17:17:46.411  6751  6751 D BluetoothMap: Proxy object connected
09-09 17:17:46.412  6751  6751 D MapProfile: Bluetooth service connected
09-09 17:17:46.412  6751  6751 D BluetoothMap: getConnectedDevices()
09-09 17:17:46.412  6751  6751 D BluetoothMap: Bluetooth is Not enabled
09-09 17:17:46.413  6751  6751 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-09 17:17:46.437  1036  1768 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6794 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
09-09 17:17:46.439  1036  1768 I ActivityManager: Killing 6281:com.android.defcontainer/u0a4 (adj 15): empty #17
,09-09 17:17:46.529  1036  2310 W libprocessgroup: failed to open /acct/uid_10004/pid_6281/cgroup.procs: No such file or directory
,09-09 17:17:46.530  6772  6772 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-09 17:17:46.531  6772  6772 W LG Account v2.2: No ProfileInfo entries
09-09 17:17:46.531  6772  6772 I LG Account v2.2: isEnabled: false
,09-09 17:17:46.533  6772  6772 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-09 17:17:46.533  6772  6772 I Feature : [Lifetracker]Country: EU
09-09 17:17:46.534  6772  6772 I Feature : [Lifetracker]Operator: OPEN
09-09 17:17:46.534  6772  6772 I Feature : [Lifetracker]Ranking support: false
09-09 17:17:46.534  6772  6772 I Feature : [Lifetracker]Comfort support: false
09-09 17:17:46.535  6772  6772 I Feature : [Lifetracker]Accessory: true
09-09 17:17:46.535  6772  6772 I Feature : [Lifetracker]Health device: true
09-09 17:17:46.535  6772  6772 I Feature : [Lifetracker]Extra Pedometer: false
09-09 17:17:46.536  6772  6772 I Feature : [Lifetracker]Blood glucose device: false
09-09 17:17:46.536  6772  6772 I Feature : [Lifetracker]Device Number: 3
09-09 17:17:46.563  1036  1362 V AlarmManager: RTC_WAKEUP set : Alarm{1dfd9a1 type 0 when 1473434265676 com.android.vending} when 1473434265676
,09-09 17:17:46.585  6751  6751 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-09 17:17:46.596  6751  6751 D BluetoothPermissionRequest: onReceive
09-09 17:17:46.602  6751  6751 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-09 17:17:46.603  6794  6794 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 17:17:46.612  6751  6751 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-09 17:17:46.617  3866  3866 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-09 17:17:46.617  3866  3866 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-09 17:17:46.618  3866  3866 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,09-09 17:17:46.623  3866  3866 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:46.623  3866  3866 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-09 17:17:46.624  3866  3866 V BluetoothFtpService: Ftp Service onStartCommand
09-09 17:17:46.624  3866  3866 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:46.624  3866  3866 V BluetoothFtpService: Ftp Service closeService
09-09 17:17:46.624  3866  3866 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-09 17:17:46.628  3866  3866 V BluetoothFtpService: successfully stopped ftp service
09-09 17:17:46.628  3866  3866 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 17:17:46.629  3866  3866 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 17:17:46.629  3866  3866 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 17:17:46.629  3866  3866 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:46.629  3866  3866 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-09 17:17:46.629  3866  3866 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-09 17:17:46.630  3866  3866 V BluetoothFtpService: Ftp Service onDestroy
09-09 17:17:46.630  3866  3866 V BluetoothFtpService: Ftp Service closeService
09-09 17:17:46.654  1036  2053 V SIM_STK : Menu title from STK is T-Mobile
,09-09 17:17:46.680  1036  1704 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6815 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-09 17:17:46.682  3866  3866 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:46.682  3866  3866 V BluetoothSapService: state: 13
09-09 17:17:46.682  3866  3866 V BluetoothSapService: Stopping SAP server process
09-09 17:17:46.683  3866  3866 V BluetoothSapService: Sap Service closeSapService in
09-09 17:17:46.683  3866  3866 V BluetoothSapService: Close listen Socket : 
09-09 17:17:46.683  3866  3866 V BluetoothSapService: Close rfcomm Socket : 
09-09 17:17:46.684  3866  3866 V BluetoothSapService: Close sapd  Socket : 
09-09 17:17:46.685  3866  3866 V BluetoothSapService: Sap Service closeSapService out
09-09 17:17:46.685  3866  3866 V BluetoothSapService: Sap Service onDestroy
09-09 17:17:46.685  3866  3866 V BluetoothSapService: Sap Service closeSapService in
09-09 17:17:46.685  3866  3866 V BluetoothSapService: Close listen Socket : 
09-09 17:17:46.685  3866  3866 V BluetoothSapService: Close rfcomm Socket : 
09-09 17:17:46.685  3866  3866 V BluetoothSapService: Close sapd  Socket : 
09-09 17:17:46.685  3866  3866 V BluetoothSapService: Sap Service closeSapService out
09-09 17:17:46.689  6794  6794 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
09-09 17:17:46.699   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 390us total 19.127ms
,09-09 17:17:46.715   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 336us total 15.727ms
,09-09 17:17:46.729   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 272us total 13.332ms
09-09 17:17:46.740  6815  6815 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 17:17:46.744  6794  6794 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-09 17:17:46.744  6794  6794 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-09 17:17:46.745  6794  6794 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-09 17:17:46.745  6794  6794 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-09 17:17:46.745  6794  6794 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-09 17:17:46.746  6794  6794 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-09 17:17:46.750  6794  6794 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-09 17:17:46.754  1036  1934 I ActivityManager: Killing 6411:com.google.android.partnersetup/u0a8 (adj 15): empty #17
09-09 17:17:46.755  6794  6794 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 17:17:46.758  6794  6794 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:17:46.798  1036  1704 W libprocessgroup: failed to open /acct/uid_10008/pid_6411/cgroup.procs: No such file or directory
,09-09 17:17:46.801  6794  6794 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-09 17:17:46.803  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:17:46.804  6794  6794 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-09 17:17:46.807  6734  6734 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 17:17:46.807  6734  6734 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 17:17:46.807  6734  6734 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 17:17:46.809  6794  6794 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-09 17:17:46.813  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:17:46.819  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:17:46.827  6794  6794 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:17:46.827  6794  6794 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-09 17:17:46.829  6794  6794 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 17:17:46.834  6110  6110 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
09-09 17:17:46.836  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:17:46.843  6734  6734 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 17:17:46.843  6734  6734 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,09-09 17:17:46.843  6734  6734 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 17:17:46.849  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 17:17:46.855  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 17:17:46.861  1036  1052 I ActivityManager: Killing 6038:com.lge.appbox.client/u0a11 (adj 15): empty #17
09-09 17:17:46.902  6794  6794 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:17:46.903  6794  6794 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-09 17:17:46.905  1036  1910 W libprocessgroup: failed to open /acct/uid_10011/pid_6038/cgroup.procs: No such file or directory
09-09 17:17:46.906  6794  6794 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 17:17:46.972  1036  1952 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6836 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-09 17:17:46.982  3866  4040 W bt-btif : ag scb idx 1 not allocated
09-09 17:17:46.982  3866  4040 E bt-btif : BTA AG is already disabled, ignoring ...
09-09 17:17:46.982  3866  4040 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 17:17:46.982  3866  4040 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:17:46.982  3866  3952 D bt_hci_bdroid: cleanup
09-09 17:17:46.983  3866  4040 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,09-09 17:17:46.983  3866  4040 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 17:17:46.983  3866  4040 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 17:17:46.983  3866  4044 I bt_lpm  : LPM is already off!!!
09-09 17:17:46.983  3866  4040 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 17:17:46.983  3866  4040 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 17:17:46.983  3866  4040 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:17:46.983  3866  4040 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 17:17:46.983  3866  4040 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 17:17:46.983  3866  4040 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 17:17:46.983  3866  4040 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 17:17:46.983  3866  4040 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 17:17:46.983  3866  4040 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:17:46.983  3866  4040 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 17:17:46.983  3866  4040 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 17:17:46.983  3866  4040 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 17:17:46.983  3866  4040 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 17:17:46.983  3866  4040 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-09 17:17:46.983  3866  4175 I bt_userial_mct: exiting userial_read_thread
09-09 17:17:46.983  3866  4175 D bt_userial_mct: Leaving userial_evt_read_thread()
09-09 17:17:46.984  3866  3952 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-09 17:17:46.984  3866  4044 I bt_vendor: hw_epilog_process
09-09 17:17:46.985  3866  3952 D bt_hci_bdroid: cleanup Finalizing cleanup
09-09 17:17:46.985  3866  3952 D bt_userial_mct: userial_close
09-09 17:17:46.985  3866  3952 E bt_userial_mct: pthread_join() FAILED result:3
09-09 17:17:46.985  3866  3952 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-09 17:17:47.077  3866  3952 D bt_hci_bdroid: set_power 0
09-09 17:17:47.077  3866  3952 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-09 17:17:47.077  3866  3952 I bt_vendor: bluetooth satus is on
09-09 17:17:47.077  3866  3952 I bt_vendor: bt-vendor : resetting BT status
09-09 17:17:47.077  3866  3952 I bt_vendor: Starting hciattach daemon
09-09 17:17:47.077  3866  3952 I bt_vendor: try to set false
,09-09 17:17:47.083  3866  3952 I bt_vendor: Starting hciattach daemon
09-09 17:17:47.083  3866  3952 I bt_vendor: try to set false
09-09 17:17:47.083  6734  6734 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 17:17:47.085  3866  3952 I bt_vendor: cleanup
09-09 17:17:47.086  3866  4040 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-09 17:17:47.088  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-09 17:17:47.096  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 17:17:47.108  3866  3952 I GKI_LINUX: GKI_exit_task 0 done
09-09 17:17:47.108  3866  3952 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-09 17:17:47.110  3866  3948 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-09 17:17:47.113  3866  3866 D HeadsetService: Received stop request...Stopping profile...
09-09 17:17:47.117  3866  3866 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-09 17:17:47.117  3866  3866 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 17:17:47.117  3866  3866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35562a4d
09-09 17:17:47.117  3866  3971 D HeadsetStateMachine: Exit Disconnected: -1
09-09 17:17:47.120  3866  3866 D A2dpService: Received stop request...Stopping profile...
09-09 17:17:47.120  3866  4003 D A2dpStateMachine: Exit Disconnected: -1
09-09 17:17:47.121  3866  3866 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,09-09 17:17:47.122  1036  1036 D BluetoothHeadset: Proxy object disconnected
09-09 17:17:47.122  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-09 17:17:47.122  3866  3866 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-09 17:17:47.122  3866  3866 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 17:17:47.122  3866  3866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35562a4d
09-09 17:17:47.123  1864  1864 D BluetoothHeadset: Proxy object disconnected
09-09 17:17:47.123  1864  1864 D BluetoothHeadset: Proxy object disconnected
09-09 17:17:47.123  1864  1864 D BluetoothHeadset: Proxy object disconnected
09-09 17:17:47.124  1036  1036 D BluetoothA2dp: Proxy object disconnected
09-09 17:17:47.124  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-09 17:17:47.124  6751  6751 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-09 17:17:47.125  6751  6751 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 17:17:47.125  6751  6751 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 17:17:47.125  6751  6751 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-09 17:17:47.125  3866  3866 D HidService: Received stop request...Stopping profile...
09-09 17:17:47.125  3866  3866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35562a4d
09-09 17:17:47.126  3866  3948 D BluetoothAdapterState: Stopping profile services that were post enabled
09-09 17:17:47.127  6751  6751 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-09 17:17:47.128  3866  3866 D HealthService: Received stop request...Stopping profile...
09-09 17:17:47.128  3866  3866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35562a4d
09-09 17:17:47.129  3866  3866 D HeadsetStateMachine: Unbinding service...
09-09 17:17:47.130  3866  3866 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 17:17:47.130  3866  3866 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 17:17:47.130  3866  3866 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 17:17:47.130  3866  3866 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 17:17:47.130  3866  3866 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 17:17:47.130  3866  3866 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 17:17:47.130  3866  3866 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-09 17:17:47.131  3866  3866 D PanService: Received stop request...Stopping profile...
09-09 17:17:47.132  3866  3866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35562a4d
,09-09 17:17:47.136  3866  3866 I BluetoothA2dpServiceJni: cleanupNative
09-09 17:17:47.136  3866  4004 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-09 17:17:47.137  3866  3866 I GKI_LINUX: GKI_exit_task 2 done
09-09 17:17:47.137  3866  3866 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-09 17:17:47.137  3866  3866 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 17:17:47.138  3866  3866 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 17:17:47.138  3866  3866 D BtGatt.GattService: stop()
09-09 17:17:47.138  3866  3866 D BtGatt.AdvertiseManager: advertise clients cleared
09-09 17:17:47.140  3866  3866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35562a4d
09-09 17:17:47.141  6836  6859 W FormManager: Network not available. Please check & try again.
09-09 17:17:47.141  3866  3866 D BluetoothMapService: Received stop request...Stopping profile...
09-09 17:17:47.141  3866  3866 D BluetoothMapService: stop()
09-09 17:17:47.142  3866  3866 D BluetoothMapEmailAppObserver: deinitObservers()
09-09 17:17:47.142  3866  3866 D BluetoothMapEmailAppObserver: removeReceiver()
09-09 17:17:47.142  3866  3866 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35562a4d
09-09 17:17:47.143  3866  3866 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 17:17:47.143  3866  3866 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 17:17:47.144  3866  3866 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 17:17:47.144  3866  3866 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 17:17:47.144  3866  3866 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 17:17:47.144  3866  3866 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 17:17:47.144  3866  3866 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-09 17:17:47.145  3866  3866 V BluetoothMapService: Handler(): got msg=4
09-09 17:17:47.145  3866  3866 D BluetoothMapService: MAP Service closeService in
09-09 17:17:47.145  3866  3866 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 17:17:47.145  3866  3866 V BluetoothMapService: MAP Service closeService out
09-09 17:17:47.146  3866  3948 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-09 17:17:47.146  3866  3948 D BluetoothAdapterProperties: Setting state to 10
09-09 17:17:47.147  3866  3948 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-09 17:17:47.147  3866  3866 D BluetoothMapService: cleanup()
09-09 17:17:47.147  3866  3866 D BluetoothMapService: MAP Service closeService in
09-09 17:17:47.147  3866  3866 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 17:17:47.147  3866  3866 V BluetoothMapService: MAP Service closeService out
09-09 17:17:47.147  3866  3948 I BluetoothAdapterState: Entering OffState
09-09 17:17:47.147  1036  1118 D BluetoothManagerService: Message: 60
09-09 17:17:47.147  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-09 17:17:47.147  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-09 17:17:47.148  6751  6767 D BluetoothPan: onBluetoothStateChange on: false
09-09 17:17:47.149  6751  6766 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 17:17:47.149  6751  6767 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 17:17:47.150  1864  3461 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:17:47.150  6836  6860 V FormManager: Network unavailable.
09-09 17:17:47.150  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:17:47.151  1864  1879 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:17:47.151  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 17:17:47.152  6751  6751 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 17:17:47.152  1864  1880 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:17:47.153  6751  6766 D BluetoothMap: onBluetoothStateChange: up=false
09-09 17:17:47.153  6751  6751 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-09 17:17:47.153  6751  6751 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 17:17:47.153  6751  6751 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 17:17:47.153  6751  6751 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 17:17:47.153  6751  6751 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-09 17:17:47.154  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-09 17:17:47.154  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-09 17:17:47.157  4329  4329 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-09 17:17:47.157  4329  4329 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 17:17:47.159  6836  6860 V FormManager: Network unavailable.
09-09 17:17:47.159  4329  4329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 17:17:47.160  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-09 17:17:47.160  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-09 17:17:47.161  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@27a63e66 mBinding = false
09-09 17:17:47.161  1036  1118 D BluetoothManagerService: Sending unbind request.
09-09 17:17:47.162  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-09 17:17:47.165  4329  4329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 17:17:47.166  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:47.167  6751  6751 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-09 17:17:47.167  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 17:17:47.167  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:47.167  1959  1959 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:47.168  1959  2186 D LGBluetoothAPIService: Message: 2
09-09 17:17:47.168  1959  2186 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2de2f35d mBinding = false
09-09 17:17:47.168  1959  2186 D LGBluetoothAPIService: Sending unbind request.
09-09 17:17:47.176  6751  6751 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-09 17:17:47.176  6751  6751 D LGBluetoothEventManager: [BTUI] clear device connection state
,09-09 17:17:47.178  3866  3952 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-09 17:17:47.179  3866  3866 I GKI_LINUX: GKI_exit_task 1 done
09-09 17:17:47.179  3866  3866 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-09 17:17:47.179  1589  1589 D BluetoothAdapter: 955769583: getState() :  mService = null. Returning STATE_OFF
09-09 17:17:47.179  1589  1589 D BluetoothAdapter: 955769583: getState() :  mService = null. Returning STATE_OFF
09-09 17:17:47.179  3866  3866 I BluetoothServiceJni: cleanupNative: return from cleanup
09-09 17:17:47.180  3866  3866 I art     : --- WEIRD: removing null entry 246
09-09 17:17:47.180  3866  3866 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-09 17:17:47.180  3866  3866 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-09 17:17:47.180  3866  3866 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-09 17:17:47.182  6751  6751 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-09 17:17:47.185  3866  3866 I art     : System.exit called, status: 0
09-09 17:17:47.185  4329  6864 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 17:17:47.186  3866  3866 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-09 17:17:47.198  4329  6865 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 17:17:47.198  4329  6865 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-09 17:17:47.202  6751  6751 D DockEventReceiver: finishStartingService: stopping service
09-09 17:17:47.207  6734  6734 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-09 17:17:47.207  6734  6734 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 17:17:47.207  6734  6734 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 17:17:47.216  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 17:17:47.219   323  1369 V AudioFlinger: 3866 died, releasing its sessions
,09-09 17:17:47.219   323  1369 V AudioFlinger:  pid 1864 @ 0
09-09 17:17:47.220   323  1369 V AudioFlinger:  pid 3297 @ 1
09-09 17:17:47.220   323  1369 V AudioFlinger:  pid 3297 @ 2
09-09 17:17:47.224  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:17:47.224  6751  6751 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-09 17:17:47.287  1036  1052 I ActivityManager: Process com.android.bluetooth (pid 3866) has died
,09-09 17:17:47.292  1036  1052 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
09-09 17:17:47.309  2229  2229 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 17:17:47.309  6836  6868 W FormManager: Network not available. Please check & try again.
,09-09 17:17:47.311  6836  6869 V FormManager: Network unavailable.
09-09 17:17:47.354  6836  6869 V FormManager: Network unavailable.
,09-09 17:17:47.363  6751  6751 D BluetoothPermissionRequest: onReceive
,09-09 17:17:47.371  6751  6751 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-09 17:17:47.374  6751  6751 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,09-09 17:17:47.384  6751  6751 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-09 17:17:47.472  1036  2053 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6876 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-09 17:17:47.474  1036  2053 I ActivityManager: Killing 6061:com.android.contacts/u0a19 (adj 15): empty #17
,09-09 17:17:47.533  1036  1562 W libprocessgroup: failed to open /acct/uid_10019/pid_6061/cgroup.procs: No such file or directory
09-09 17:17:47.552  6794  6794 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-09 17:17:47.562  6876  6876 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-09 17:17:47.562  6876  6876 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 17:17:47.563  6876  6876 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-09 17:17:47.563  6794  6794 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-09 17:17:47.563  6876  6876 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-09 17:17:47.564  6794  6794 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,09-09 17:17:47.577  4493  6896 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,09-09 17:17:47.583  6876  6876 D BluetoothAdapterApp: Loading JNI Library
09-09 17:17:47.622  6876  6876 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@89deeaa Instance Count = 1
,09-09 17:17:47.627  6876  6876 D BluetoothAdapterApp: onCreate
09-09 17:17:47.640  6794  6794 D LgDataFeature: LgDataFeature() Constructor: none
,09-09 17:17:47.640  6794  6794 D LgDataFeature: LgDataFeature() Constructor Done, null
09-09 17:17:47.647  6794  6794 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-09 17:17:47.648  6794  6794 V SoundPool: load: fd=31, offset=10857164, length=17813, priority=1
09-09 17:17:47.648  6794  6794 V SoundPool: create sampleID=1, fd=30, offset=17813 length=10857164
09-09 17:17:47.648  6794  6794 V SoundPool: doLoad: loading sample sampleID=1
09-09 17:17:47.649  6794  6794 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-09 17:17:47.649  6876  6876 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-09 17:17:47.651  6876  6876 D ProfileConfigQcom: Adding HeadsetService
09-09 17:17:47.651  6652  6652 D UEI.SmartControl: QS Service created
09-09 17:17:47.651  6876  6876 D ProfileConfigQcom: [BTUI] A2dpService is supported
,09-09 17:17:47.652  6876  6876 D ProfileConfigQcom: Adding A2dpService
09-09 17:17:47.652  6876  6876 D ProfileConfigQcom: [BTUI] HidService is supported
09-09 17:17:47.652  6876  6876 D ProfileConfigQcom: Adding HidService
09-09 17:17:47.652  6876  6876 D ProfileConfigQcom: [BTUI] HealthService is supported
09-09 17:17:47.652  6876  6876 D ProfileConfigQcom: Adding HealthService
09-09 17:17:47.653  6876  6876 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-09 17:17:47.654  6876  6876 D ProfileConfigQcom: [BTUI] PanService is supported
09-09 17:17:47.655  6876  6876 D ProfileConfigQcom: Adding PanService
09-09 17:17:47.655  6876  6876 D ProfileConfigQcom: [BTUI] GattService is supported
09-09 17:17:47.655  6876  6876 D ProfileConfigQcom: Adding GattService
09-09 17:17:47.655  6876  6876 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-09 17:17:47.655  6876  6876 D ProfileConfigQcom: Adding BluetoothMapService
09-09 17:17:47.656  6876  6876 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-09 17:17:47.657  6794  6905 V SoundPool: Start decode
09-09 17:17:47.657  6794  6905 V MediaPlayer[Native]: decode(30, 10857164, 17813)
,09-09 17:17:47.657  6876  6876 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-09 17:17:47.658   323  2998 V MediaPlayerService: decode(22, 10857164, 17813)
09-09 17:17:47.658   323  2998 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-09 17:17:47.658   323  2998 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-09 17:17:47.658   323  2998 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-09 17:17:47.658   323  2998 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-09 17:17:47.658   323  2998 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-09 17:17:47.658   323  2998 V MediaPlayerService: player type = 3
09-09 17:17:47.658   323  2998 V AwesomePlayer: AwesomePlayer create()
09-09 17:17:47.659   323  2998 V AwesomePlayer: reset_l() 
09-09 17:17:47.659   323  2998 V AwesomePlayer: cancelPlayerEvents
09-09 17:17:47.659   323  2998 V AwesomePlayer: setAudioSink() 
09-09 17:17:47.659   323  2998 V AwesomePlayer: reset_l() 
09-09 17:17:47.659   323  2998 V AudioCache: notify(0xb5474a40, 8, 0, 0)
09-09 17:17:47.659   323  2998 V AudioCache: ignored
09-09 17:17:47.659   323  2998 V AwesomePlayer: cancelPlayerEvents
09-09 17:17:47.659   323  2998 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
09-09 17:17:47.659   323  2998 V AwesomePlayer: setDataSource_l dataSource
09-09 17:17:47.659   323  2998 V LGParserOSAL: SniffLGParser start
09-09 17:17:47.659   323  2998 V LGParserOSAL: MainType:5, SubType=0
09-09 17:17:47.659   323  2998 V LGParserOSAL: #### check Mime : application/ogg
09-09 17:17:47.659   323  2998 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-09 17:17:47.659   323  2998 E MediaExtractor: Use LGExtractor :application/ogg 
09-09 17:17:47.663  6794  6794 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-09 17:17:47.665  6794  6794 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-09 17:17:47.666  6794  6794 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-09 17:17:47.668  6876  6876 V LGMDMManagerInternal: Create singleton instance
,09-09 17:17:47.677  6751  6751 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-09 17:17:47.687  6794  6794 V LGMDMManager: Create singleton instance
09-09 17:17:47.718  6652  6652 I UEI.SmartControl: Service initServices...
09-09 17:17:47.719  6652  6652 D UEI.SmartControl: QS start get config
09-09 17:17:47.724   323  2998 V LGParserOSAL: supported mime: application/ogg
09-09 17:17:47.724   323  2998 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-09 17:17:47.724   323  2998 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-09 17:17:47.724   323  2998 V AwesomePlayer: mBitrate = -1 bits/sec
09-09 17:17:47.724   323  2998 V AwesomePlayer: AudioTrack Setting
09-09 17:17:47.724   323  2998 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-09 17:17:47.724   323  2998 V AwesomePlayer: setAudioSource() 
09-09 17:17:47.724   323  2998 V MediaPlayerService: prepare
09-09 17:17:47.724   323  2998 V AwesomePlayer: prepareAsync_l() 
09-09 17:17:47.724   323  2998 V MediaPlayerService: wait for prepare
09-09 17:17:47.724   323  6912 V AwesomePlayer: onPrepareAsyncEvent() 
09-09 17:17:47.724   323  6912 V AwesomePlayer: initAudioDecoder() 
09-09 17:17:47.724   323  6912 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-09 17:17:47.724   323  6912 V AudioSystem: isOffloadSupported()
09-09 17:17:47.724   323  6912 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-09 17:17:47.724   323  6912 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-09 17:17:47.724   323  6912 I AudioFlinger: isAudioPlaybackHookOn() false
09-09 17:17:47.724   323  6912 V AwesomePlayer: getUseOffload() = 0 
09-09 17:17:47.724   323  6912 V OMXCodec: OMXCodec::Create
09-09 17:17:47.724   323  6912 V OMXCodec: findMatchingCodecs()
09-09 17:17:47.724   323  6912 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-09 17:17:47.724   323  6912 V OMXCodec: matchingCodecs.size()=1
09-09 17:17:47.724   323  6912 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-09 17:17:47.726   323  6912 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-09 17:17:47.726   323  6912 V LGCodecAdapter: LG Codec Adapter start
09-09 17:17:47.726   323  6912 V OMXCodec: OMXCodec Createtor
09-09 17:17:47.726   323  6912 V OMXCodec: setComponentRole
09-09 17:17:47.726   323  6912 V OMXCodec: configureCodec protected=0
09-09 17:17:47.726   323  6912 V LGCodecAdapter: called getLGCodecSpecificData
09-09 17:17:47.726   323  6912 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-09 17:17:47.726   323  6912 V LGCodecOSAL: Called LGconfigureCodecMETA
09-09 17:17:47.726   323  6912 V LGCodecOSAL: Called LGconfigureCodecMSG
09-09 17:17:47.726   323  6912 V LGCodecOSAL: Not support LGCodec
09-09 17:17:47.726   323  6912 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-09 17:17:47.726   323  6912 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-09 17:17:47.726   323  6912 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-09 17:17:47.726   323  6912 I AwesomePlayer: Could not offload audio decode, try pcm offload
,09-09 17:17:47.726   323  6912 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-09 17:17:47.726   323  6912 V AudioSystem: isOffloadSupported()
09-09 17:17:47.726   323  6912 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-09 17:17:47.726   323  6912 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-09 17:17:47.726   323  6912 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-09 17:17:47.726   323  6912 V OMXCodec: init()
09-09 17:17:47.726   323  6912 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-09 17:17:47.726   323  6912 V OMXCodec: allocateBuffers
09-09 17:17:47.726   323  6912 V OMXCodec: allocateBuffersOnPort portIndex=0
09-09 17:17:47.726   323  6912 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-09 17:17:47.726   323  6912 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f1f0 on input port
09-09 17:17:47.726   323  6912 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f240 on input port
09-09 17:17:47.726   323  6912 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
09-09 17:17:47.726   323  6912 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on input port
09-09 17:17:47.726   323  6912 V OMXCodec: allocateBuffersOnPort portIndex=1
09-09 17:17:47.726   323  6912 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-09 17:17:47.727   323  6912 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on output port
09-09 17:17:47.727   323  6912 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
09-09 17:17:47.727   323  6912 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
09-09 17:17:47.727   323  6912 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fce0 on output port
09-09 17:17:47.727   323  6912 V OMXCodec: init() mAsyncCompletion wait!!! 
09-09 17:17:47.727   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-09 17:17:47.727   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
,09-09 17:17:47.727   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-09 17:17:47.727   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-09 17:17:47.727   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-09 17:17:47.727   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-09 17:17:47.727   323  6912 V OMXCodec: init() mAsyncCompletion wait free! 
09-09 17:17:47.727   323  6912 V AwesomePlayer: finishAsyncPrepare_l() 
09-09 17:17:47.727   323  6912 V AudioCache: notify(0xb5474a40, 5, 0, 0)
09-09 17:17:47.727   323  6912 V AudioCache: ignored
09-09 17:17:47.727   323  6912 V AudioCache: notify(0xb5474a40, 1, 0, 0)
09-09 17:17:47.727   323  6912 V AudioCache: prepared
09-09 17:17:47.727   323  2998 V AudioCache: wait - success
09-09 17:17:47.727   323  2998 V MediaPlayerService: start
09-09 17:17:47.727   323  2998 V AwesomePlayer: play_l() 
09-09 17:17:47.727   323  2998 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-09 17:17:47.727   323  2998 V AwesomePlayer: createAudioPlayer_l
09-09 17:17:47.727   323  2998 V AwesomePlayer: seekAudioIfNecessary_l() 
09-09 17:17:47.727   323  2998 V AwesomePlayer: startAudioPlayer_l() 
09-09 17:17:47.727   323  2998 D AudioPlayer: start of Playback, useOffload 0
09-09 17:17:47.727   323  2998 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-09 17:17:47.727   323  2998 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-09 17:17:47.731   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-09 17:17:47.731   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-09 17:17:47.731   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-09 17:17:47.731   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-09 17:17:47.731   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-09 17:17:47.731   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-09 17:17:47.731   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048256
09-09 17:17:47.731   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 17:17:47.731   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048416
09-09 17:17:47.731   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,09-09 17:17:47.731   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048496
,09-09 17:17:47.731   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 17:17:47.731   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957049056
09-09 17:17:47.731   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 17:17:47.731   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-09 17:17:47.731   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-09 17:17:47.731   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-09 17:17:47.731   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-09 17:17:47.731   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-09 17:17:47.731   323  6914 V OMXCodec: allocateBuffersOnPort portIndex=1
09-09 17:17:47.731   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-09 17:17:47.732   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
09-09 17:17:47.732   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
09-09 17:17:47.732   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on output port
09-09 17:17:47.732   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
09-09 17:17:47.732   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-09 17:17:47.732   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-09 17:17:47.733   323  2998 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-09 17:17:47.733   323  2998 V AudioCache: notify(0xb5474a40, 6, 0, 0)
09-09 17:17:47.733   323  2998 V AudioCache: ignored
09-09 17:17:47.733   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.733   323  6915 V AudioCache: memcpy(0xac300000, 0xb57ff000, 4096)
09-09 17:17:47.734   323  2998 V MediaPlayerService: wait for playback complete
09-09 17:17:47.735   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.735   323  6915 V AudioCache: memcpy(0xac301000, 0xb57ff000, 4096)
09-09 17:17:47.735   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.735   323  6915 V AudioCache: memcpy(0xac302000, 0xb57ff000, 4096)
09-09 17:17:47.735   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.735   323  6915 V AudioCache: memcpy(0xac303000, 0xb57ff000, 4096)
09-09 17:17:47.736   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.736   323  6915 V AudioCache: memcpy(0xac304000, 0xb57ff000, 4096)
09-09 17:17:47.736   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.736   323  6915 V AudioCache: memcpy(0xac305000, 0xb57ff000, 4096)
09-09 17:17:47.739   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.739   323  6915 V AudioCache: memcpy(0xac306000, 0xb57ff000, 4096)
09-09 17:17:47.740   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.740   323  6915 V AudioCache: memcpy(0xac307000, 0xb57ff000, 4096)
09-09 17:17:47.740   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.740   323  6915 V AudioCache: memcpy(0xac308000, 0xb57ff000, 4096)
09-09 17:17:47.741   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.741   323  6915 V AudioCache: memcpy(0xac309000, 0xb57ff000, 4096)
09-09 17:17:47.741   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.742   323  6915 V AudioCache: memcpy(0xac30a000, 0xb57ff000, 4096)
09-09 17:17:47.742   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.742   323  6915 V AudioCache: memcpy(0xac30b000, 0xb57ff000, 4096)
09-09 17:17:47.743   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.743   323  6915 V AudioCache: memcpy(0xac30c000, 0xb57ff000, 4096)
09-09 17:17:47.743   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.743   323  6915 V AudioCache: memcpy(0xac30d000, 0xb57ff000, 4,096)
09-09 17:17:47.744   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.744   323  6915 V AudioCache: memcpy(0xac30e000, 0xb57ff000, 4096)
09-09 17:17:47.744   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.744   323  6915 V AudioCache: memcpy(0xac30f000, 0xb57ff000, 4096)
09-09 17:17:47.745   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.745   323  6915 V AudioCache: memcpy(0xac310000, 0xb57ff000, 4096)
09-09 17:17:47.745   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.745   323  6915 V AudioCache: memcpy(0xac311000, 0xb57ff000, 4096)
09-09 17:17:47.746   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.746   323  6915 V AudioCache: memcpy(0xac312000, 0xb57ff000, 4096)
09-09 17:17:47.746   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.746   323  6915 V AudioCache: memcpy(0xac313000, 0xb57ff000, 4096)
09-09 17:17:47.747   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.747   323  6915 V AudioCache: memcpy(0xac314000, 0xb57ff000, 4096)
09-09 17:17:47.749   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.749   323  6915 V AudioCache: memcpy(0xac315000, 0xb57ff000, 4096)
09-09 17:17:47.749   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.749   323  6915 V AudioCache: memcpy(0xac316000, 0xb57ff000, 4096)
09-09 17:17:47.750   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.750   323  6915 V AudioCache: memcpy(0xac317000, 0xb57ff000, 4096)
09-09 17:17:47.750   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.750   323  6915 V AudioCache: memcpy(0xac318000, 0xb57ff000, 4096)
09-09 17:17:47.751   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.751   323  6915 V AudioCache: memcpy(0xac319000, 0xb57ff000, 4096)
09-09 17:17:47.751   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.751   323  6915 V AudioCache: memcpy(0xac31a000, 0xb57ff000, 4096)
09-09 17:17:47.752   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.752   323  6915 V AudioCache: memcpy(0xac31b000, 0xb57ff000, 4096)
09-09 17:17:47.752   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.752   323  6915 V AudioCache: memcpy(0xac31c000, 0xb57ff000, 4096)
09-09 17:17:47.753   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.753   323  6915 V AudioCache: memcpy(0xac31d000, 0xb57ff000, 4096)
09-09 17:17:47.754   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.754   323  6915 V AudioCache: memcpy(0xac31e000, 0xb57ff000, 4096)
09-09 17:17:47.754   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.754   323  6915 V AudioCache: memcpy(0xac31f000, 0xb57ff000, 4096)
09-09 17:17:47.754  6876  6876 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:47.755   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.755   323  6915 V AudioCache: memcpy(0xac320000, 0xb57ff000, 4096)
09-09 17:17:47.755   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.755   323  6915 V AudioCache: memcpy(0xac321000, 0xb57ff000, 4096)
09-09 17:17:47.756   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.756   323  6915 V AudioCache: memcpy(0xac322000, 0xb57ff000, 4096)
09-09 17:17:47.756  6876  6876 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 17:17:47.757  6876  6876 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 17:17:47.757   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.757   323  6915 V AudioCache: memcpy(0xac323000, 0xb57ff000, 4096)
09-09 17:17:47.757  6876  6876 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 17:17:47.757   323  6915 V AudioCache: write(0xb57ff000, 4096)
,09-09 17:17:47.757   323  6915 V AudioCache: memcpy(0xac324000, 0xb57ff000, 4096)
09-09 17:17:47.758  6876  6876 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:47.758  6876  6876 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-09 17:17:47.758   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.758   323  6915 V AudioCache: memcpy(0xac325000, 0xb57ff000, 4096)
09-09 17:17:47.759   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.759   323  6915 V AudioCache: memcpy(0xac326000, 0xb57ff000, 4096)
09-09 17:17:47.759   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.759   323  6915 V AudioCache: memcpy(0xac327000, 0xb57ff000, 4096)
09-09 17:17:47.760   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.760   323  6915 V AudioCache: memcpy(0xac328000, 0xb57ff000, 4096)
,09-09 17:17:47.760   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.760   323  6915 V AudioCache: memcpy(0xac329000, 0xb57ff000, 4096)
09-09 17:17:47.761   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.761   323  6915 V AudioCache: memcpy(0xac32a000, 0xb57ff000, 4096)
09-09 17:17:47.761   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.761   323  6915 V AudioCache: memcpy(0xac32b000, 0xb57ff000, 4096)
09-09 17:17:47.762   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.762   323  6915 V AudioCache: memcpy(0xac32c000, 0xb57ff000, 4096)
09-09 17:17:47.762   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.762   323  6915 V AudioCache: memcpy(0xac32d000, 0xb57ff000, 4096)
,09-09 17:17:47.763   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.763   323  6915 V AudioCache: memcpy(0xac32e000, 0xb57ff000, 4096)
09-09 17:17:47.763   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.763   323  6915 V AudioCache: memcpy(0xac32f000, 0xb57ff000, 4096)
09-09 17:17:47.763   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.763   323  6915 V AudioCache: memcpy(0xac330000, 0xb57ff000, 4096)
09-09 17:17:47.764   323  6915 V AudioCache: write(0xb57ff000, 4096)
09-09 17:17:47.764   323  6915 V AudioCache: memcpy(0xac331000, 0xb57ff000, 4096)
09-09 17:17:47.764   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-09 17:17:47.764   323  6915 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-09 17:17:47.764   323  6915 V AwesomePlayer: postAudioEOS() 
,09-09 17:17:47.764   323  6915 V AudioCache: write(0xb57ff000, 280)
09-09 17:17:47.764   323  6915 V AudioCache: memcpy(0xac332000, 0xb57ff000, 280)
09-09 17:17:47.766  6815  6815 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-09 17:17:47.766   323  6912 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-09 17:17:47.766   323  6912 V AwesomePlayer: onStreamDone
09-09 17:17:47.766   323  6912 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-09 17:17:47.766   323  6912 V AudioCache: notify(0xb5474a40, 2, 0, 0)
09-09 17:17:47.766   323  6912 V AudioCache: playback complete
09-09 17:17:47.766   323  6912 V AwesomePlayer: pause_l() 
09-09 17:17:47.766   323  6912 V AudioCache: notify(0xb5474a40, 7, 0, 0)
,09-09 17:17:47.766   323  6912 V AudioCache: ignored
09-09 17:17:47.766   323  6912 V AwesomePlayer: cancelPlayerEvents
09-09 17:17:47.766   323  2998 V AudioCache: wait - success
09-09 17:17:47.766   323  2998 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-09 17:17:47.767   323  6912 D AudioPlayer: Pause Playback at 1068125
09-09 17:17:47.767   323  2998 V AwesomePlayer: reset_l() 
09-09 17:17:47.767   323  2998 V AudioCache: notify(0xb5474a40, 8, 0, 0)
09-09 17:17:47.768   323  2998 V AudioCache: ignored
09-09 17:17:47.768   323  2998 V AwesomePlayer: cancelPlayerEvents
09-09 17:17:47.768   323  2998 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
,09-09 17:17:47.768   323  2998 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-09 17:17:47.768   323  2998 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-09 17:17:47.768   323  2998 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-09 17:17:47.768   323  2998 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-09 17:17:47.768   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-09 17:17:47.768   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-09 17:17:47.768   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-09 17:17:47.768   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 0
09-09 17:17:47.768   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-09 17:17:47.768   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
,09-09 17:17:47.768   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-09 17:17:47.768   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 0
09-09 17:17:47.768   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-09 17:17:47.768   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f1f0 on port 0
09-09 17:17:47.768   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-09 17:17:47.768   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-09 17:17:47.768   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
09-09 17:17:47.768   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-09 17:17:47.768   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 1
,09-09 17:17:47.768   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-09 17:17:47.768   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 1
09-09 17:17:47.768   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-09 17:17:47.768   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 1
09-09 17:17:47.768   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 17:17:47.768   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-09 17:17:47.769   323  2998 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-09 17:17:47.769   323  2998 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-09 17:17:47.769   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-09 17:17:47.769   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
,09-09 17:17:47.769   323  6914 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-09 17:17:47.769   323  2998 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-09 17:17:47.769   323  2998 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-09 17:17:47.769   323  2998 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
,09-09 17:17:47.770   323  2998 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
,09-09 17:17:47.770   323  2998 D AudioPlayer: AudioPlayer releasing audio source
09-09 17:17:47.770   323  2998 D AudioPlayer: AudioPlayer done releasing audio source
09-09 17:17:47.770   323  2998 V AwesomePlayer: reset_l() 
09-09 17:17:47.770   323  2998 V AwesomePlayer: cancelPlayerEvents
09-09 17:17:47.770   323  2998 V AwesomePlayer: ~AwesomePlayer call
09-09 17:17:47.770   323  2998 V AwesomePlayer: reset_l() 
09-09 17:17:47.770   323  2998 V AwesomePlayer: cancelPlayerEvents
09-09 17:17:47.771  6794  6905 V SoundPool: close(30)
09-09 17:17:47.771  6794  6905 V SoundPool: pointer = 0xa003a000, size = 205080, sampleRate = 48000, numChannels = 2
09-09 17:17:47.802  6794  6794 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,09-09 17:17:47.802  6794  6794 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-09 17:17:47.804  6794  6794 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1777
09-09 17:17:47.983  6652  6652 I UEI.SmartControl: Supports setup maps: true
,09-09 17:17:47.985  6652  6652 D UEI.SmartControl: QS start statue = true Error code = 0
,09-09 17:17:47.985  6652  6652 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-09 17:17:47.985  6652  6652 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-09 17:17:47.985  6652  6652 I UEI.SmartControl: ### init IR Blaster...
09-09 17:17:47.988  6652  6652 D serial_port: Configuring serial port
09-09 17:17:47.988  6652  6652 E UEI.SmartControl: UEIBLaster setting for 616
09-09 17:17:47.989  6652  6652 I UEI.SmartControl: Setting serial record hearder size = 2
09-09 17:17:47.989  6652  6652 I UEI.SmartControl: configuring settings for MAXQ616
09-09 17:17:47.989  6652  6652 I UEI.SmartControl: Get version...
09-09 17:17:48.007  6652  6917 D UEI.SmartControl: serial port data available: 21
,09-09 17:17:48.036  6652  6652 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-09 17:17:48.036  6652  6652 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-09 17:17:48.037  6652  6652 I UEI.SmartControl: QS saving settings...
,09-09 17:17:48.039  6652  6652 D UEI.SmartControl: IR Blaster version: 25672567,
,09-09 17:17:48.055  6652  6917 D UEI.SmartControl: serial port data available: 4,
,09-09 17:17:48.089  6652  6923 I UEI.SmartControl: Device manager: loading config....
,09-09 17:17:48.100  6652  6923 D UEI.SmartControl: ----------- loading internal config...
,09-09 17:17:48.101  6652  6652 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-09 17:17:48.107  6652  6652 E UEI.SmartControl: Services init done
09-09 17:17:48.107  6652  6652 D UEI.SmartControl: QS Service init finished
,09-09 17:17:48.112  6652  6652 D UEI.SmartControl: QS Service version name: 2.1.91
09-09 17:17:48.112  6652  6652 D UEI.SmartControl: QS Service version code: 201091
09-09 17:17:48.114  6652  6652 D UEI.SmartControl: Service requested: Control
09-09 17:17:48.119  6652  6923 E UEI.SmartControl: Loading SETTINGS...
09-09 17:17:48.119  6652  6652 D UEI.SmartControl: Request IControl service: devices are loaded...
09-09 17:17:48.121  6652  6652 D UEI.SmartControl: Internal service binding...
,09-09 17:17:48.122  6794  6794 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-09 17:17:48.123  6652  6677 I UEI.SmartControl: ------ IControl API: 11
09-09 17:17:48.124  6652  6677 D UEI.SmartControl: File observer start...
09-09 17:17:48.124  6652  6677 E UEI.SmartControl: IR Port is disabled: false
09-09 17:17:48.124  6652  6677 D UEI.SmartControl: Starting file observer...
09-09 17:17:48.125  6652  6677 I UEI.SmartControl: Registering callback...
09-09 17:17:48.126  6652  6669 I UEI.SmartControl: ------ IControl API: 19
09-09 17:17:48.127  6652  6669 I UEI.SmartControl: Registering Services Ready callback...
09-09 17:17:48.130  6652  6923 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-09 17:17:48.152  6652  6922 I UEI.SmartControl: Notify AllClients services are ready: 0
09-09 17:17:48.152  6652  6922 D UEI.SmartControl: -----service ready thread exits
09-09 17:17:48.152  6794  6811 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-09 17:17:48.153  6794  6902 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-09 17:17:48.153  6794  6902 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,09-09 17:17:48.154  6794  6794 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-09 17:17:48.154  6794  6794 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-09 17:17:48.154  6652  6668 I UEI.SmartControl: ------ IControl API: 8
09-09 17:17:48.156  6794  6794 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-09 17:17:48.156  6794  6794 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-09 17:17:48.157  6794  6794 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-09 17:17:48.157  6794  6794 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-09 17:17:48.158  6794  6794 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-09 17:17:48.159  6794  6794 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-09 17:17:48.160  6794  6794 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-09 17:17:48.162  6794  6794 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-09 17:17:48.163  6794  6794 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-09 17:17:48.164  6794  6794 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-09 17:17:48.164  6794  6794 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-09 17:17:48.165  6794  6794 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,09-09 17:17:48.166  6794  6794 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-09 17:17:48.167  6794  6794 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-09 17:17:48.169  6794  6794 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473434268168]
09-09 17:17:48.171  6794  6794 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-09 17:17:48.174  1036  2099 I ActivityManager: Killing 6089:com.android.gallery3d/u0a27 (adj 15): empty #17
09-09 17:17:48.194  6794  6928 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-09 17:17:48.231  1036  2099 I ActivityManager: Killing 6447:com.lge.email/u0a23 (adj 15): empty #18
,09-09 17:17:48.262  1036  1934 W libprocessgroup: failed to open /acct/uid_10027/pid_6089/cgroup.procs: No such file or directory
,09-09 17:17:48.273  1036  2081 W libprocessgroup: failed to open /acct/uid_10023/pid_6447/cgroup.procs: No such file or directory
,09-09 17:17:48.275  6794  6794 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,09-09 17:17:48.279  6794  6794 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-09 17:17:48.280  6794  6794 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-09 17:17:48.280  6794  6794 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-09 17:17:48.280  6794  6794 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-09 17:17:48.281  6794  6794 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-09 17:17:48.281  6794  6794 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-09 17:17:48.294  6794  6794 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-09 17:17:48.983  1036  1990 D WifiServiceImplEx: setWifiEnabled: true pid=6571, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-09 17:17:48.985  1036  1990 D WifiService: setWifiEnabled: true pid=6571, uid=10118
,09-09 17:17:48.985  1036  1990 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 17:17:49.008  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 17:17:49.009  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 17:17:49.009  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,09-09 17:17:49.012  1036  1525 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-09 17:17:49.013  1036  1525 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-09 17:17:49.015  1036  1525 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-09 17:17:49.015  1036  1525 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-09 17:17:49.015  1036  1525 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-09 17:17:49.015  1036  1525 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-09 17:17:49.016  1036  1525 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-09 17:17:49.016  1036  1525 E WifiHW  : unknown target_country: EU , set to default
09-09 17:17:49.016  1036  1525 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-09 17:17:49.016  1036  1525 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-09 17:17:49.016  1036  1525 I WifiUtil: gEnableBmps=1
09-09 17:17:49.043  1036  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:17:49.050  1036  1118 D Tethering: MasterInitialState.processMessage what=3
09-09 17:17:49.058  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:49.062  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:49.063  1036  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:49.071  1036  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:17:49.074  1036  1118 D Tethering: MasterInitialState.processMessage what=3
09-09 17:17:49.083  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:49.087  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:49.088  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-09 17:17:49.091  6363  6397 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-09 17:17:49.102  5804  5804 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-09 17:17:49.113  5804  5804 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-09 17:17:49.132  2229  2229 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:17:49.167  1036  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:17:49.219  1036  1952 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6945 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-09 17:17:49.225  1036  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:17:49.226  1036  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-09 17:17:49.310  6945  6945 I AppUp4:AppBoxCP: onCreate
09-09 17:17:49.311  6945  6945 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-09 17:17:49.321  6945  6945 I AppUp4:DB:  setFingerPrint start
,09-09 17:17:49.322  6945  6945 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-09 17:17:49.331  6945  6945 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,09-09 17:17:49.331  6945  6945 I AppUp4:DB:  SDK version = 21
,09-09 17:17:49.331  6945  6945 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-09 17:17:49.333  6945  6945 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-09 17:17:49.334  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 17:17:49.335  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:49.337  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 17:17:49.337  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-09 17:17:49.345  6945  6945 I AppUp4:CustModeStarterReceiver: onReceive
,09-09 17:17:49.402  6945  6945 D LgDataFeature: LgDataFeature() Constructor: none
09-09 17:17:49.402  6945  6945 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 17:17:49.412  6945  6945 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@7f005e4
09-09 17:17:49.412  6945  6945 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 17:17:49.412  6945  6945 D AppUp4:CustFacade: isPhone : true
09-09 17:17:49.413  6945  6945 D AppUp4:CustModeStarterReceiver: begin check event
09-09 17:17:49.413  6945  6945 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-09 17:17:49.414  6945  6945 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-09 17:17:49.415  6945  6966 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-09 17:17:49.415  6945  6966 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-09 17:17:49.415  6945  6966 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,09-09 17:17:49.418  1036  1978 I ActivityManager: Killing 6492:com.google.android.apps.docs/u0a61 (adj 15): empty #17
09-09 17:17:49.473  1036  1990 W libprocessgroup: failed to open /acct/uid_10061/pid_6492/cgroup.procs: No such file or directory
,09-09 17:17:49.477  4329  4329 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:49.478  4329  4329 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 17:17:49.483  4329  4329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 17:17:49.495  4329  4329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-09 17:17:49.506  4329  6972 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 17:17:49.509  4329  6974 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:49.509  4329  6974 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 17:17:49.548  1036  1934 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6975 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-09 17:17:49.658  6975  6975 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 17:17:49.658  6975  6975 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 17:17:49.660  6975  6975 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-09 17:17:49.661  6975  6975 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-09 17:17:49.759  6975  6975 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-09 17:17:49.777  6975  6975 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-09 17:17:49.831  6975  6975 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 17:17:49.871  6975  6975 D LgDataFeature: LgDataFeature() Constructor: none
09-09 17:17:49.872  6975  6975 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 17:17:49.910  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 17:17:49.910  1036  1118 D Tethering: InitialState.processMessage what=4
09-09 17:17:49.911  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 17:17:49.913   319   880 D SoftapController: Softap fwReload - Ok
,09-09 17:17:49.917  1036  1525 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (895ms)
09-09 17:17:49.925   319   880 D CommandListener: Setting iface cfg
09-09 17:17:49.925   319   880 D CommandListener: Trying to bring down wlan0
09-09 17:17:49.926   319   880 D CommandListener: Clearing all IP addresses on wlan0
09-09 17:17:49.928  1036  1525 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-09 17:17:49.924  7001  7001 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-09 17:17:49.924  7001  7001 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:17:49.957  7001  7001 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-09 17:17:49.991  7001  7001 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-09 17:17:49.991  7001  7001 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-09 17:17:50.026  6975  6975 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-09 17:17:50.029  1036  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 17:17:50.029  1036  1525 E WifiStateMachine: useWiFiOffloading() : false
09-09 17:17:50.029  1036  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 17:17:50.030  1036  1525 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-09 17:17:50.030  1036  1525 D WifiMonitor: connecting to supplicant
09-09 17:17:50.032  1959  1959 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-09 17:17:50.033  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-09 17:17:50.033  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:17:50.034  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:50.036  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:50.059  7001  7001 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 17:17:50.062  3297  3297 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 17:17:50.062  6975  6975 I HubEmail: JNI_OnLoad()
09-09 17:17:50.062  3297  3297 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:50.062  6975  6975 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 17:17:50.062  6975  6975 I HubEmail: registerNatives()
09-09 17:17:50.062  6975  6975 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 17:17:50.062  6975  6975 I HubEmail: registerNativeMethods()
09-09 17:17:50.062  6975  6975 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 17:17:50.062  6975  6975 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-09 17:17:50.062  3297  3297 I LgeMiscReceiver: networkInfo.isConnected() = false
09-09 17:17:50.080  7001  7001 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
09-09 17:17:50.086  1036  1525 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-09 17:17:50.086  1036  1525 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
,09-09 17:17:50.087  1036  1525 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-09 17:17:50.087  1036  1525 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-09 17:17:50.087  1036  1525 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:17:50.088  1036  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:17:50.089  1036  1525 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-09 17:17:50.089  1036  1525 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-09 17:17:50.089  1036  1525 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-09 17:17:50.089  1036  1525 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-09 17:17:50.089  1036  1525 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-09 17:17:50.108  7001  7001 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-09 17:17:50.108  1036  7009 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-09 17:17:50.108  1036  7009 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-09 17:17:50.108  1036  7009 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-09 17:17:50.108  1036  7009 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-09 17:17:50.108  1036  7009 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-09 17:17:50.108  1036  7009 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,09-09 17:17:50.113  7001  7001 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-09 17:17:50.113  1036  7009 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-09 17:17:50.113  1036  7009 D WifiMonitor: Dropping event because (p2p0) is stopped
09-09 17:17:50.117  1036  1910 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7010 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
09-09 17:17:50.120  1036  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 17:17:50.120  1036  1525 E WifiStateMachine: useWiFiOffloading() : false
09-09 17:17:50.120  1036  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-09 17:17:50.122  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:50.123  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:50.123  1036  1525 D WifiNative-wlan0: doBoolean: SET update_config 1
09-09 17:17:50.123  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:50.123  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:50.123  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 17:17:50.123  1036  1525 D WifiNative-wlan0: SET update_config 1: returned true
09-09 17:17:50.123  1036  1525 D WifiConfigStore: Loading config and enabling all networks 
09-09 17:17:50.123  1036  1525 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-09 17:17:50.124  6975  7008 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:50.125  1959  1959 D WfdService: Waiting for WifiP2p enabling
09-09 17:17:50.125  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:17:50.126  1036  1525 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-09 17:17:50.126  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-09 17:17:50.127  1036  1530 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-09 17:17:50.129  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:50.129  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:50.129  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:50.129  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:17:50.129  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:50.129  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:50.129  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:50.129  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:50.129  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:17:50.129  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:50.129  6571  6571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:17:50.130  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:50.130  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:50.130  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:50.130  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:17:50.130  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:50.130  6,571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:50.130  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:50.130  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:50.130  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:17:50.130  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:50.130  6571  6571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:17:50.133  6836  7006 W FormManager: Network not available. Please check & try again.
,09-09 17:17:50.139  1036  1525 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-09 17:17:50.136  6836  7007 V FormManager: Network unavailable.
09-09 17:17:50.148  6836  7007 V FormManager: Network unavailable.
,09-09 17:17:50.155  1036  1525 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-09 17:17:50.156  1036  1525 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-09 17:17:50.156  1036  1525 D WifiStateMachine: enableVerboseLogging : level 2
09-09 17:17:50.157  1036  1525 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-09 17:17:50.157  1036  1525 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-09 17:17:50.158  1036  1525 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-09 17:17:50.158  1036  1525 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-09 17:17:50.158  1036  1525 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-09 17:17:50.159  1036  1525 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-09 17:17:50.159  1036  1525 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-09 17:17:50.159  1036  1525 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-09 17:17:50.159  1036  1525 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-09 17:17:50.159  1036  1525 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-09 17:17:50.159  1036  1525 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-09 17:17:50.160  1036  1525 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-09 17:17:50.160  1036  1525 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-09 17:17:50.160  1036  1525 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-09 17:17:50.161  1036  1525 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 17:17:50.161  1036  1525 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-09 17:17:50.161  1036  1525 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-09 17:17:50.161  1036  1525 D WifiNative-HAL: Setting external_sim to 1
09-09 17:17:50.161  1036  1525 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-09 17:17:50.162  1036  1525 D WifiNative-wlan0: SET external_sim 1: returned true
09-09 17:17:50.162  1036  1525 I WifiNative-HAL: startHal
09-09 17:17:50.162  1036  1525 D wifi    : setting scan oui 0xaf6e4fe0
09-09 17:17:50.162  1036  1525 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 17:17:50.162  1036  1525 I WifiNative-HAL: startHal
09-09 17:17:50.162  1036  1525 D wifi    : setting scan oui 0xaf6e4fe0
09-09 17:17:50.163  1036  1525 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-09 17:17:50.163  1036  1525 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-09 17:17:50.163  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-09 17:17:50.163  7001  7001 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-09 17:17:50.164  1036  1525 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-09 17:17:50.164  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-09 17:17:50.164  7001  7001 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-09 17:17:50.164  1036  1525 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-09 17:17:50.164  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-09 17:17:50.165  7001  7001 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-09 17:17:50.165  1036  1525 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-09 17:17:50.165  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-09 17:17:50.165  7001  7001 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-09 17:17:50.166  1036  1525 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-09 17:17:50.166  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-09 17:17:50.166  7001  7001 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-09 17:17:50.166  1036  1525 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-09, 17:17:50.166  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-09 17:17:50.167  7001  7001 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-09 17:17:50.167  1036  1525 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-09 17:17:50.167  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-09 17:17:50.167  7001  7001 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,09-09 17:17:50.168  1036  1525 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-09 17:17:50.169  1036  1525 E WifiNative: : [121,485,551 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-09 17:17:50.169  1959  1959 D WfdsService: Supplicant Connection state is changed : true
09-09 17:17:50.169  1036  1525 D WifiNative-wlan0: doBoolean: RECONNECT
09-09 17:17:50.169  1959  2335 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-09 17:17:50.169  1959  2335 D WfdsService: Set the WFDS Monitor: true
09-09 17:17:50.170  1959  2335 D WfdsMonitor: WfdsMonitorThread create
09-09 17:17:50.170  1959  2335 D WfdsMonitor: WFDS Monitor is created and started
09-09 17:17:50.170  1959  2335 D WfdsService: WiFi: Supplicant connection re-established
09-09 17:17:50.170  1036  1525 D WifiNative-wlan0: RECONNECT: returned true
09-09 17:17:50.171  1036  1525 D WifiNative-wlan0: doString: [STATUS]
09-09 17:17:50.171  1959  7033 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-09 17:17:50.171  1036  1051 I ActivityManager: Killing 6157:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
09-09 17:17:50.171  1959  7033 E CtrlSupplicant: Succeed to open control connection
09-09 17:17:50.171  1036  7009 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-09 17:17:50.171  1959  7033 E CtrlSupplicant: Succeed to open monitor connection
09-09 17:17:50.172  1036  7009 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-09 17:17:50.172  1959  7033 D WfdsMonitor: Supplicant connection established
09-09 17:17:50.172  1959  2335 D WfdsService: Connected to the supplicant for wfds
09-09 17:17:50.172  1036  1525 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-09 17:17:50.172  1036  1525 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 17:17:50.172  1036  1525 D WifiNative-wlan0: SET ps 1: returned true
09-09 17:17:50.172  1036  1522 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:50.174   319   880 D CommandListener: Setting iface cfg
09-09 17:17:50.174   319   880 D CommandListener: Trying to bring up p2p0
09-09 17:17:50.174  1036  1522 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-09 17:17:50.174  1036  1522 D LGWifiP2pService: P2pEnablingState
09-09 17:17:50.174  1036  1522 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:50.174  1036  1522 D LGWifiP2pService: P2p socket connection successful
09-09 17:17:50.174  1036  1522 D LGWifiP2pService: P2pEnabledState
,09-09 17:17:50.220  1036  1522 D LGWifiP2pService: sending p2p connection changed broadcast
09-09 17:17:50.220  1036  1522 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-09 17:17:50.220  1036  2310 W libprocessgroup: failed to open /acct/uid_10080/pid_6157/cgroup.procs: No such file or directory
09-09 17:17:50.221  1036  1525 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-09 17:17:50.221  1036  1525 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-09 17:17:50.222  1036  1522 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-09 17:17:50.222  1036  1522 D WifiNative-p2p0: doBoolean: SET device_name G3
09-09 17:17:50.222  1036  1525 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-09 17:17:50.222  1036  1525 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-09 17:17:50.222  1036  1522 D WifiNative-p2p0: SET device_name G3: returned true
09-09 17:17:50.222  1036  1522 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-09 17:17:50.222  1036  1522 D LGWifiP2pService: before postfix = G3
09-09 17:17:50.222  1036  1522 D WifiServerServiceExt: postfix byte check : 2
09-09 17:17:50.222  1036  1522 D LGWifiP2pService: after postfix = G3
09-09 17:17:50.223  1036  1522 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-09 17:17:50.223  1036  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=121540  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,09-09 17:17:50.223  1036  1522 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-09 17:17:50.223  1036  1522 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-09 17:17:50.224  1036  1522 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-09 17:17:50.224  1036  1522 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-09 17:17:50.224  1036  1522 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-09 17:17:50.224  1036  1522 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-09 17:17:50.225  1036  1522 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-09 17:17:50.225  1036  1522 D WifiNative-HAL: p2pGetDeviceAddress
09-09 17:17:50.225  1036  1522 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-09 17:17:50.225  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
09-09 17:17:50.225  1036  1036 D RttService: SCAN_AVAILABLE : 3
09-09 17:17:50.225  1036  1543 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:50.225  1036  1543 I WifiNative-HAL: startHal
09-09 17:17:50.225  1036  1543 D wifi    : getting scan capabilities on interface[1] = 0xaf6e4fe0
09-09 17:17:50.226  1036  1543 D wifi    : failed to get capabilities : -3
09-09 17:17:50.226  1036  1543 E WifiScanningService: could not get scan capabilities
09-09 17:17:50.226  1036  1544 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:50.226  1959  1959 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-09 17:17:50.227  1959  1959 D WfdsService: WifiP2pState is changed : true
09-09 17:17:50.227  1959  2335 D WfdsService: Receive the WFDS_ENABLE Method
09-09 17:17:50.227  1959  2335 D WfdsService: Set the WFDS Monitor: true
09-09 17:17:50.227  1959  2335 D WfdsService: Connected to the supplicant for wfds
09-09 17:17:50.227  1959  2335 D WfdsJNI : doCommand: WFDS_SET TRUE
09-09 17:17:50.227  7001  7001 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-09 17:17:50.227  1959  2335 D WfdsService: selectPreferredScanChannel [36]
09-09 17:17:50.227  1959  2335 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-09 17:17:50.227  1959  1959 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-09 17:17:50.228  1959  1959 D WfdsService: isConnected: false
,09-09 17:17:50.228  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:17:50.228  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:17:50.229  1036  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=121546  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 17:17:50.229  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:17:50.230  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 17:17:50.230  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:50.230  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-09 17:17:50.230  1036  1522 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-09 17:17:50.230  1036  1522 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-09 17:17:50.231  1036  1522 D WifiNative-p2p0: P2P_FLUSH: returned true
,09-09 17:17:50.231  1036  1522 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-09 17:17:50.231  1036  1522 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-09 17:17:50.231  1036  1522 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-09 17:17:50.231  1036  1525 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-09 17:17:50.231  1036  1522 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-09 17:17:50.231  1036  1522 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
,09-09 17:17:50.233  1036  1525 E WifiStateMachine:  ConnectModeState what:132106 1 0
,09-09 17:17:50.234  1036  1525 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-09 17:17:50.235  1036  1525 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-09 17:17:50.236  1959  1959 I WfdStateTracker: handleP2pThisDeviceChanged
09-09 17:17:50.236  1959  1959 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-09 17:17:50.236  1959  1959 D WfdsService: Update P2p Interface State: 3
09-09 17:17:50.243  7001  7001 E wpa_supplicant: nWIFIDualbandAPConnection: 1
,09-09 17:17:50.243  1036  1522 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-09 17:17:50.243  1036  1522 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-09 17:17:50.244  1036  1522 D LGWifiP2pService: InactiveState
09-09 17:17:50.244  1036  1522 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:50.244  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:50.244  1036  1522 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-09 17:17:50.245  7001  7001 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-09 17:17:50.246  7001  7001 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 17:17:50.247  7001  7001 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-09 17:17:50.247  7001  7001 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:17:50.248  7001  7001 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:17:50.248  1036  1525 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-09 17:17:50.248  1959  7033 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 17:17:50.249  1959  7033 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:17:50.249  1959  7033 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:17:50.249  1036  7009 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 17:17:50.249  1036  7009 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 17:17:50.249  1036  7009 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 17:17:50.249  1036  7009 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 17:17:50.249  1036  7009 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:17:50.249  1036  7009 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:17:50.249  1036  7009 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:17:50.249  1036  7009 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:17:50.249  1036  7009 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:17:50.249  1036  7009 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:17:50.249  1036  7009 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:17:50.249  1036  7009 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:17:50.249  1036  1525 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-09 17:17:50.251  1036  1525 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-09 17:17:50.251  1036  1525 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-09 17:17:50.251  7001  7001 E wpa_supplicant: disconnect_rssi_lvl: -100
09-09 17:17:50.251  1036  1522 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-09 17:17:50.251  1036  1522 D LGWifiP2pService: InactiveState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:50.251  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:50.251  1036  1522 D LGWifiP2pService: DefaultState{ when=-8ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:50.252  1036  1522 D LGWifiP2pService: InactiveState{ when=-8ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:50.252  ,1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:50.252  1036  1522 D LGWifiP2pService: DefaultState{ when=-8ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:50.252  1036  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:50.252  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:50.252  1036  1522 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:50.252  1036  1525 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-09 17:17:50.252  1959  2335 W WfdsService: DefaultState - msg [9441285] is not handled
09-09 17:17:50.252  1036  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:50.252  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:50.252  1036  1522 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:50.253  1036  1036 E WifiServerServiceExt: No p2p device connected
09-09 17:17:50.253  1036  1525 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-09 17:17:50.254  1036  1525 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-09 17:17:50.254  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-09 17:17:50.255  7001  7001 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-09 17:17:50.255  7001  7001 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 17:17:50.256  7001  7001 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-09 17:17:50.256  7001  7001 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-09 17:17:50.256  7001  7001 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:17:50.257  1959  7033 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:17:50.257  1959  7033 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:17:50.257  1036  7009 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 17:17:50.257  1036  7009 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 17:17:50.257  1036  7009 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ,
09-09 17:17:50.257  1036  7009 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 17:17:50.257  1036  7009 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD],
09-09 17:17:50.257  1036  7009 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:17:50.257  1036  7009 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:17:50.257  1036  7009 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-09 17:17:50.257  1036  7009 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:17:50.257  1036  7009 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:17:50.257  1036  7009 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:17:50.257  1036  7009 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:17:50.258  1036  1525 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-09 17:17:50.258  1036  1522 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:50.258  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
,09-09 17:17:50.258  1036  1525 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-09 17:17:50.259  1036  1525 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-09 17:17:50.259  1036  1525 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-09 17:17:50.259  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-09 17:17:50.259  7001  7001 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-09 17:17:50.259  7001  7001 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,09-09 17:17:50.260  1036  7009 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-09 17:17:50.260  1036  7009 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 17:17:50.260  1036  7009 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 17:17:50.260  1036  7009 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 17:17:50.260  1036  1525 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-09 17:17:50.260  1036  1525 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-09 17:17:50.261  1036  1525 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-09 17:17:50.261  1036  1525 D WifiNative-wlan0: doBoolean: SCAN
,09-09 17:17:50.261  1036  1525 D WifiNative-wlan0: SCAN: returned false
09-09 17:17:50.261  1036  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=121578  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 17:17:50.262  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:17:50.262  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:17:50.264  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:17:50.264  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:50.265  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 17:17:50.265  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,09-09 17:17:50.266  1036  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=121583  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 17:17:50.266  1036  1525 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 17:17:50.267  1036  1525 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 17:17:50.267  1036  1525 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 17:17:50.267  1036  1525 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 17:17:50.267  1036  1525 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 17:17:50.268  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:17:50.268  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
09-09 17:17:50.269  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:17:50.269  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
09-09 17:17:50.310  7010  7010 D LgDataFeature: LgDataFeature() Constructor: none
09-09 17:17:50.310  7010  7010 D LgDataFeature: LgDataFeature() Constructor Done, null
09-09 17:17:50.313  7010  7010 D PhoneMonitor: Register our PhoneStateListener
,09-09 17:17:50.329  7010  7010 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-09 17:17:50.331  7010  7010 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-09 17:17:50.346  7010  7010 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,09-09 17:17:50.347  7010  7010 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-09 17:17:50.349  7010  7010 D TelephonyAutoProfiling: [parse] Load xml
09-09 17:17:50.355  7010  7010 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-09 17:17:50.355  7010  7010 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-09 17:17:50.355  7010  7010 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-09 17:17:50.355  7010  7010 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-09 17:17:50.355  7010  7010 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-09 17:17:50.356  7010  7010 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-09 17:17:50.356  7010  7010 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
,09-09 17:17:50.356  7010  7010 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-09 17:17:50.356  7010  7010 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-09 17:17:50.356  7010  7010 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-09 17:17:50.356  7010  7010 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-09 17:17:50.356  7010  7010 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-09 17:17:50.356  7010  7010 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-09 17:17:50.356  7010  7010 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-09 17:17:50.358  7010  7010 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-09 17:17:50.358  7010  7010 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-09 17:17:50.358  7010  7010 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,09-09 17:17:50.372  7010  7010 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,09-09 17:17:50.394  1036  1990 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7036 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 17:17:50.395  1036  1990 I ActivityManager: Killing 6188:com.google.android.apps.plus/u0a97 (adj 15): empty #17
09-09 17:17:50.519  1036  2099 W libprocessgroup: failed to open /acct/uid_10097/pid_6188/cgroup.procs: No such file or directory
,09-09 17:17:50.771  1036  1990 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7060 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-09 17:17:50.774  1036  1990 I ActivityManager: Killing 6553:com.lge.eula/1000 (adj 15): empty #17
,09-09 17:17:50.781  7001  7001 E wpa_supplicant: USIM:  scard_init function
09-09 17:17:50.781  7001  7001 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-09 17:17:50.787  1036  7009 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-09 17:17:50.787  1036  7009 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-09 17:17:50.787  1036  7009 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-09 17:17:50.787  1036  7009 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
09-09 17:17:50.787  1036  7009 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-09 17:17:50.787  1036  7009 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-09 17:17:50.787  1036  7009 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,09-09 17:17:50.790  1036  1525 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-09 17:17:50.791  1036  1525 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-09 17:17:50.791  1036  1525 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-09 17:17:50.792  1036  1525 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-09 17:17:50.792  1036  1525 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-09 17:17:50.830  1036  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=122146  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-09 17:17:50.831  1036  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=122147  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-09 17:17:50.832  1036  2099 W libprocessgroup: failed to open /acct/uid_1000/pid_6553/cgroup.procs: No such file or directory
09-09 17:17:50.842  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:50.842  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:50.842  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-09 17:17:50.843  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:17:50.843  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,09-09 17:17:50.846  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:17:50.846  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:17:50.848  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:17:50.924  7001  7001 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 17:17:50.927  1036  7009 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-09 17:17:50.927  1036  7009 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-09 17:17:50.927  1036  7009 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-09 17:17:50.927  1036  7009 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-09 17:17:50.928  1036  7009 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 17:17:50.928  1036  7009 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 17:17:50.931  1036  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=122248  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-09 17:17:50.932  1036  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=122249  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-09 17:17:50.934  1036  1525 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122251
09-09 17:17:50.935  1036  1525 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122252
09-09 17:17:50.936  1036  1525 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122253
09-09 17:17:50.940  1036  1525 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122257
09-09 17:17:50.940  1036  1525 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122257
09-09 17:17:50.941  1036  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=122258  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-09 17:17:50.942  1036  1562 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7083 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 17:17:50.943  1036  1562 I ActivityManager: Killing 6589:com.lge.bnr/1000 (adj 15): empty #17
09-09 17:17:50.944  7001  7001 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 17:17:50.944  7001  7001 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-09 17:17:50.948  1036  7009 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 17:17:50.948  1036  7009 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 17:17:50.948  1036  7009 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-09 17:17:50.948  1036  7009 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 17:17:50.948  1036  7009 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 17:17:50.949  1036  7009 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-09 17:17:50.949  1036  7009 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 17:17:50.949  1036  7009 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 17:17:50.949  1036  7009 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 17:17:50.949  1036  7009 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 17:17:50.967  1036  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:50.967  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:50.967  1036  1522 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 17:17:50.998  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 17:17:50.998  1036  1051 W libprocessgroup: failed to open /acct/uid_1000/pid_6589/cgroup.procs: No such file or directory
,09-09 17:17:51.005  1036  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=122322  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-09 17:17:51.007  1036  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=122323  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-09 17:17:51.008  1036  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=122324  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-09 17:17:51.008  1036  1525 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=122325
09-09 17:17:51.009  1036  1525 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=122326
,09-09 17:17:51.009  1036  1525 D WifiNative-wlan0: doString: [STATUS]
09-09 17:17:51.010  1036  7009 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 17:17:51.010  1036  7009 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 17:17:51.011  1036  1525 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-09 17:17:51.013  1036  1525 I WifiServiceExtension: setVHTCapabilityType  : false
09-09 17:17:51.016  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:17:51.016  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:17:51.019  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:17:51.021  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:51.021  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:51.022  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,09-09 17:17:51.035  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:51.035  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:51.035  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-09 17:17:51.035  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:17:51.035  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-09 17:17:51.036  1036  1525 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-09 17:17:51.036  1036  1525 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-09 17:17:51.043  7083  7083 I art     : Almond Protected OAT
09-09 17:17:51.043  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:51.043  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 17:17:51.043  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-09 17:17:51.043  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:17:51.043  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:17:51.044  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:17:51.046  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:17:51.046  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:17:51.048  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:17:51.058  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:51.058  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:51.058  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-09 17:17:51.062  1036  1525 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-09 17:17:51.063  1036  1525 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 17:17:51.063  1036  1525 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 17:17:51.063  1036  1532 D ConnectivityService: Got NetworkAgent Messenger
,09-09 17:17:51.063  1036  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-09 17:17:51.063  1036  1532 D ConnectivityService: NetworkAgent connected
09-09 17:17:51.063  1036  1525 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 17:17:51.063  1036  1525 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-09 17:17:51.064  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:17:51.064  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:17:51.065  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 17:17:51.068  1036  1525 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-09 17:17:51.068  1036  1525 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 17:17:51.068  1036  1525 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 17:17:51.069  1036  1525 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 17:17:51.069  1036  1525 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-09 17:17:51.073  1036  1525 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-09 17:17:51.074   319   880 D CommandListener: Setting iface cfg
09-09 17:17:51.076  1036  1525 E WifiStateMachine: Start Dhcp Watchdog 2
09-09 17:17:51.076  1036  7101 D DhcpStateMachine: StoppedState
09-09 17:17:51.076  1036  7101 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:51.076  1036  7101 D DhcpStateMachine: WaitBeforeStartState
09-09 17:17:51.077  1036  1525 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=122394  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 17:17:51.078  1036  1525 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=122394  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 17:17:51.078  1036  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=122395  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 17:17:51.078  1036  1525 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 17:17:51.079  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 17:17:51.079  1036  1525 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 17:17:51.079  1036  1525 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 17:17:51.079  1036  1525 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 17:17:51.080  1036  1525 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 17:17:51.080  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:17:51.080  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,09-09 17:17:51.084  1036  1525 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=122401  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 17:17:51.084  1036  1525 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=122401  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 17:17:51.085  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:17:51.085  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-09 17:17:51.085  1036  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=122401  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 17:17:51.085  1036  1525 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:17:51.086  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:17:51.086  1036  1525 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:17:51.086  1036  1525 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:17:51.087  1036  1525 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:17:51.087  1036  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:17:51.088  1036  1525 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:76519] from screen [on:0 period:260488560] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 17:17:51.089  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:260488561] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 17:17:51.089  1036  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-09 17:17:51.092  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 17:17:51.095  1036  1525 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:17:51.095  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:17:51.095  1036  1532 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-09 17:17:51.096  1036  1525 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:17:51.097  1036  1525 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:17:51.097  1036  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:17:51.098  1036  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:17:51.098  1036  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-09 17:17:51.099  1036  1525 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=129,0,0
09-09 17:17:51.100  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=129,0,0
09-09 17:17:51.100  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-09 17:17:51.101  7001  7001 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-09 17:17:51.101  1036  1525 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-09 17:17:51.101  1036  1525 D WifiNative-wlan0: doBoolean: SET ps 0
09-09 17:17:51.101  1036  1525 D WifiNative-wlan0: SET ps 0: returned true
09-09 17:17:51.101  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-09 17:17:51.102  7001  7001 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-09 17:17:51.102  1036  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-09 17:17:51.102  1036  1525 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-09 17:17:51.102  1036  1525 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 17:17:51.103  1036  1525 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-09 17:17:51.103  1036  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@f9ef1a4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:51.103  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@f9ef1a4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:51.103   319   880 D CommandListener: Setting iface cfg
09-09 17:17:51.104   319   880 D CommandListener: Trying to bring up wlan0
09-09 17:17:51.104  1036  7101 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:51.104  1036  7101 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-09 17:17:51.105  1036  1525 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
,09-09 17:17:51.107  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:17:51.107  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-09 17:17:51.108  1036  1525 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:17:51.108  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:17:51.108  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-09 17:17:51.109  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:17:51.109  1036  1525 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:17:51.109  1036  1525 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:17:51.110  1036  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:17:51.110  1036  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:17:51.111  1036  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-09 17:17:51.111  1036  1525 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-09 17:17:51.111  7083  7083 D WeatherApplication: removeAccount
09-09 17:17:51.111  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-09 17:17:51.111  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 17:17:51.112  7001  7001 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 17:17:51.112  1036  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:51.112  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:51.113  1036  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 17:17:51.113  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-09 17:17:51.113  7001  7001 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-09 17:17:51.114  1036  1525 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-09 17:17:51.114  1036  1525 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 17:17:51.116  7083  7083 D WeatherApplication: Account.length = 0
09-09 17:17:51.116  7083  7083 E WeatherApplication: OPERATOR:OPEN
09-09 17:17:51.122  7083  7083 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:17:51
,09-09 17:17:51.127  7083  7083 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-09 17:17:51.127  7083  7083 D Weather.Utils: 2 : All the weather widget is gone.
09-09 17:17:51.128  7083  7083 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 17:17:51.129  1036  1525 D WifiNative-wlan0: SET ps 1: returned true
09-09 17:17:51.129  1036  1525 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-09 17:17:51.130  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-09 17:17:51.130  1036  1525 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-09 17:17:51.131  1036  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-09 17:17:51.131  1036  1532 D ConnectivityService: ignoring duplicate network state non-change
09-09 17:17:51.132  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:17:51.132  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:17:51.133  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:17:51.134  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:51.134  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:51.134  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-09 17:17:51.137  1036  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-09 17:17:51.137  1036  1532 D ConnectivityService: Adding iface wlan0 to network 101
09-09 17:17:51.139  1036  1525 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-09 17:17:51.145  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:51.145  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:51.145  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-09 17:17:51.148  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,09-09 17:17:51.152  1959  1959 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-09 17:17:51.152  7083  7083 D WeatherAncestor: connectivity changed - connection : true
09-09 17:17:51.154  7083  7083 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-09 17:17:51.156  1036  1532 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 17:17:51.157  1036  1532 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-09 17:17:51.157  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:17:51.157  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:17:51.157  1036  1532 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-09 17:17:51.158   319   880 E Netd    : netlink response contains error (File exists)
09-09 17:17:51.158  1036  1532 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-09 17:17:51.159  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:51.159  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:51.159  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-09 17:17:51.159  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-09 17:17:51.159  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 17:17:51.161  1036  1532 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-09 17:17:51.161  1036  1532 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-09 17:17:51.161  1036  1532 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-09 17:17:51.161  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:51.162  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:51.162  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-09 17:17:51.162  1036  1532 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-09 17:17:51.162  1036  1532 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-09 17:17:51.162  1036  1532 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-09 17:17:51.162  1036  1532 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-09 17:17:51.162  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:17:51.162  1036  1532 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 17:17:51.163  1036  1532 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 17:17:51.163  1036  1532 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 17:17:51.163  1036  7100 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:51.163  1036  7100 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-09 17:17:51.163  1036  1532 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:17:51.163  1036  7100 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:51.163  1036  1532 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-09 17:17:51.163  1036  1532 D ConnectivityService: currentScore = 0, newScore = 20
09-09 17:17:51.163  1036  1532 D ConnectivityService:    accepting network in place of null
09-09 17:17:51.163  1036  7100 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-09 17:17:51.163  1036  1532 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:17:51.165  1036  1532 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for l,egacy network type 1
09-09 17:17:51.165  1036  1532 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-09 17:17:51.165  1036  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 17:17:51.165  1864  1864 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:17:51.165  1864  1864 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-09 17:17:51.165  1036  1532 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:51.165  1036  1532 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-09 17:17:51.165  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-09 17:17:51.166  1036  1525 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:17:51.166  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:17:51.166  1036  1525 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 17:17:51.166   319  7110 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-09 17:17:51.167  1036  1532 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-09 17:17:51.168  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-09 17:17:51.168  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 17:17:51.168  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 17:17:51.168  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 17:17:51.169  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:17:51.169  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-09 17:17:51.169  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:17:51.173  1036  1532 D ConnectivityService: validation of new default Network = false
09-09 17:17:51.173  1036  1532 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-09 17:17:51.173  1036  1532 D DSQN    : enableDataServiceNotify 
09-09 17:17:51.173  1036  1532 D DSQN    : start dsqn bin
09-09 17:17:51.173  7083  7083 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,09-09 17:17:51.173  7083  7083 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-09 17:17:51.173  7083  7083 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
09-09 17:17:51.178  1036  1532 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-09 17:17:51.178  1036  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:17:51.178  1036  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 17:17:51.178  1036  1532 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 17:17:51.174  7112  7112 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:17:51.174  7112  7112 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:17:51.181  1589  1795 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 17:17:51.189  1036  1521 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-09 17:17:51.192  7112  7112 E DSQN    : DSQN ssw
09-09 17:17:51.198  1829  7113 I CheckinService: active receiver: enabled
,09-09 17:17:51.207  1829  7113 I CheckinService: Preparing to send checkin request
09-09 17:17:51.207  1829  7113 I EventLogService: Accumulating logs since 1473434206783
09-09 17:17:51.208  7083  7083 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 17:17:51.208  7083  7083 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:17:51
,09-09 17:17:51.212  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 17:17:51.213  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:17:51.213  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 17:17:51.243  1036  1934 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7119 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 17:17:51.244  1829  7113 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
09-09 17:17:51.244  1036  1934 I ActivityManager: Killing 2210:com.lge.music/u0a34 (adj 15): empty #17
09-09 17:17:51.264   323   323 V AudioFlinger: 2210 died, releasing its sessions
09-09 17:17:51.264   323   323 V AudioFlinger:  pid 1864 @ 0
09-09 17:17:51.264   323   323 V AudioFlinger:  pid 3297 @ 1
09-09 17:17:51.264   323   323 V AudioFlinger:  pid 3297 @ 2
,09-09 17:17:51.275  1036  1562 W libprocessgroup: failed to open /acct/uid_10034/pid_2210/cgroup.procs: No such file or directory
,09-09 17:17:51.306  1036  7101 D DhcpStateMachine: DHCPV4 request on wlan0
,09-09 17:17:51.308  1036  7101 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,09-09 17:17:51.308  1036  7101 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,09-09 17:17:51.304  7137  7137 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:17:51.304  7137  7137 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:17:51.320  7137  7137 I dhcpcd  : version 5.5.6 starting
09-09 17:17:51.323  7137  7137 E dhcpcd  : get_duid: m
,09-09 17:17:51.323  7137  7137 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-09 17:17:51.323  7137  7137 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-09 17:17:51.373  7137  7137 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,09-09 17:17:51.374  7137  7137 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-09 17:17:51.374  7137  7137 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,09-09 17:17:51.374  7137  7137 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-09 17:17:51.374  7137  7137 D dhcpcd  : wlan0: sending REQUEST (xid 0xc04e3a89), next in 3.24 seconds
09-09 17:17:51.386  1036  1562 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7144 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,09-09 17:17:51.416  7137  7137 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-09 17:17:51.424  7144  7144 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-09 17:17:51.424  7144  7144 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-09 17:17:51.430   278   360 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 17:17:51.430   278   360 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-09 17:17:51.430   278   360 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 17:17:51.431  7119  7162 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-09 17:17:51.433   278   360 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 17:17:51.433   278   360 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-09 17:17:51.433   278   360 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 17:17:51.433  7119  7162 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-09 17:17:51.442   278   360 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 17:17:51.442   278   360 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-09 17:17:51.442   278   360 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 17:17:51.443  7119  7164 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-09 17:17:51.445  7144  7144 I MultiDex: VM with version 2.1.0 has multidex support
09-09 17:17:51.445  7144  7144 I MultiDex: install
09-09 17:17:51.445  7144  7144 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-09 17:17:51.448   278   360 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 17:17:51.448   278   360 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-09 17:17:51.448   278   360 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 17:17:51.448  7119  7164 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-09 17:17:51.453  7144  7144 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
09-09 17:17:51.457  7137  7137 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-09 17:17:51.457  7137  7137 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,09-09 17:17:51.457  7137  7137 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
,09-09 17:17:51.457  7137  7137 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-09 17:17:51.457  7137  7137 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-09 17:17:51.458  7137  7137 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-09 17:17:51.458  7137  7137 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-09 17:17:51.458  7137  7137 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-09 17:17:51.643  7119  7119 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-09 17:17:51.661  7119  7119 I LibraryLoader: Loading: webviewchromium
,09-09 17:17:51.664  7119  7119 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 2993-2997)
09-09 17:17:51.664  7119  7119 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 17:17:51.671  7119  7119 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3e854f5f}
09-09 17:17:51.674  7119  7119 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 17:17:51.675  7119  7119 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 17:17:51.693  7119  7119 I BrowserStartupController: Initializing chromium process, renderers=0
,09-09 17:17:51.694  7119  7119 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 17:17:51.712  1036  7101 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-09 17:17:51.714  1036  7101 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-09 17:17:51.714  1036  7101 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-09 17:17:51.714  1036  7101 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-09 17:17:51.714  1036  7101 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-09 17:17:51.714  1036  7101 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 17:17:51.714  1036  7101 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-09 17:17:51.714  1036  7101 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-09 17:17:51.715  1036  7101 D DhcpStateMachine: RunningState
09-09 17:17:51.716   323  1368 V AudioPolicyService: registerClient() client 0xb04103c0, uid 10093
09-09 17:17:51.718  7119  7208 W AudioManagerAndroid: Requires BLUETOOTH permission
09-09 17:17:51.722  7119  7119 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-09 17:17:51.724  7119  7119 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-09 17:17:51.725  7119  7119 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,09-09 17:17:51.759  7119  7119 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 17:17:51.759  7119  7119 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 17:17:51.759  7119  7119 I Adreno-EGL: Build Date: 12/12/14 금
09-09 17:17:51.759  7119  7119 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 17:17:51.759  7119  7119 I Adreno-EGL: Remote Branch: 
09-09 17:17:51.759  7119  7119 I Adreno-EGL: Local Patches: 
09-09 17:17:51.759  7119  7119 I Adreno-EGL: Reconstruct Branch: 
,09-09 17:17:51.763  7144  7159 D LgDataFeature: LgDataFeature() Constructor: none
09-09 17:17:51.764  7144  7159 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 17:17:51.796  1036  1362 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3f8b335 type 2 when 123112 com.google.android.gms} when 123112
,09-09 17:17:51.840  7119  7119 I NSApplication: Starting up...
,09-09 17:17:51.848  7216  7216 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
09-09 17:17:51.914  1036  1704 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7229 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-09 17:17:51.916  1036  1562 I ActivityManager: Killing 6110:com.android.vending/u0a44 (adj 15): empty #17
09-09 17:17:51.947   347   347 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 426us total 34.712ms
,09-09 17:17:51.948  7216  7216 I dex2oat : dex2oat took 99.860ms (threads: 4)
09-09 17:17:51.965  7144  7159 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 17:17:51.965  7144  7159 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 17:17:51.965  7144  7159 I Adreno-EGL: Build Date: 12/12/14 금
09-09 17:17:51.965  7144  7159 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 17:17:51.965  7144  7159 I Adreno-EGL: Remote Branch: 
09-09 17:17:51.965  7144  7159 I Adreno-EGL: Local Patches: 
09-09 17:17:51.965  7144  7159 I Adreno-EGL: Reconstruct Branch: 
09-09 17:17:51.967   347   347 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 375us total 18.118ms
,09-09 17:17:51.985   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 378us total 18.005ms
,09-09 17:17:52.070  1036  1952 W libprocessgroup: failed to open /acct/uid_10044/pid_6110/cgroup.procs: No such file or directory
09-09 17:17:52.077  1036  1051 D WifiServiceImplEx: setWifiEnabled: false pid=6571, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-09 17:17:52.077  1036  1051 D WifiService: setWifiEnabled: false pid=6571, uid=10118
09-09 17:17:52.077  1036  1051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 17:17:52.091  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 17:17:52.091  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 17:17:52.091  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,09-09 17:17:52.092  1036  1525 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-09 17:17:52.093  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-09 17:17:52.093  1036  1525 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-09 17:17:52.093  1036  1525 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-09 17:17:52.094  1036  1525 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-09 17:17:52.094  1036  1525 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-09 17:17:52.094  1036  1525 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 17:17:52.094  1036  1525 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 17:17:52.095  1036  1525 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 17:17:52.095  1036  1525 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-09 17:17:52.103  1036  1525 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-09 17:17:52.103  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 17:17:52.103  1036  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:52.103  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:52.103  7001  7001 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 17:17:52.103  1036  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 17:17:52.103  1036  1525 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 17:17:52.104  1036  1525 D WifiNative-wlan0: SET ps 1: returned true
09-09 17:17:52.104  1036  7101 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:52.104   319   880 D CommandListener: Clearing all IP addresses on wlan0
,09-09 17:17:52.115  7229  7229 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 17:17:52.120  7144  7159 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 17:17:52.120  7144  7159 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 17:17:52.120  7144  7159 I Adreno-EGL: Build Date: 12/12/14 금
09-09 17:17:52.120  7144  7159 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 17:17:52.120  7144  7159 I Adreno-EGL: Remote Branch: 
09-09 17:17:52.120  7144  7159 I Adreno-EGL: Local Patches: 
09-09 17:17:52.120  7144  7159 I Adreno-EGL: Reconstruct Branch: 
09-09 17:17:52.134  1036  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 17:17:52.134  1036  1532 D ConnectivityService: ignoring duplicate network state non-change
09-09 17:17:52.134  1036  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,09-09 17:17:52.137  1036  1036 D WifiHS20: hidePasspointNotification off =false
09-09 17:17:52.137  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:52.137  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:52.138  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 17:17:52.140  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:17:52.140  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:17:52.140  1036  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:52.140  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:52.141  1036  1522 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@d312d22
09-09 17:17:52.141  1036  1522 D LGWifiP2pService: P2pDisablingState
09-09 17:17:52.141  1036  1522 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:52.141  1036  1522 D LGWifiP2pService: p2p socket connection lost
09-09 17:17:52.141  1036  1522 D LGWifiP2pService: P2pDisabledState
09-09 17:17:52.142  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:17:52.145  1036  1525 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:17:52.145  1036  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:17:52.146  1036  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:17:52.146  1036  1525 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:17:52.147  1036  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:17:52.147  1959  1959 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-09 17:17:52.149  1036  1036 D WifiHS20: hidePasspointNotification off =false
09-09 17:17:52.150  1036  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:17:52.151  1036  1525 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 17:17:52.151  1036  1525 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-09 17:17:52.152  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 17:17:52.152  7001  7001 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,09-09 17:17:52.153  1036  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 17:17:52.153  1036  1525 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 17:17:52.153  1036  1525 D WifiNative-wlan0: SET ps 1: returned true
09-09 17:17:52.155  1036  1522 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:52.155  1036  1522 D LGWifiP2pService: DefaultState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:52.163  1959  1959 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-09 17:17:52.163  1959  1959 D WfdsService: WifiP2pState is changed : false
09-09 17:17:52.163  1959  2335 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-09 17:17:52.163  1959  2335 D WfdsService: Set the WFDS Monitor: false
09-09 17:17:52.164  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:52.164  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:52.164  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 17:17:52.164  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
09-09 17:17:52.164  1959  2335 D WfdsMonitor: WFDS Monitor is stopped
09-09 17:17:52.164  1959  2335 D WfdsService: STATE : WfdsDisabledState - enter
09-09 17:17:52.165  1959  7033 D CtrlSupplicant: Received on exit socket, terminate
09-09 17:17:52.165  1959  7033 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-09 17:17:52.165  1959  7033 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-09 17:17:52.165  1959  7033 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
,09-09 17:17:52.165  1959  2339 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-09 17:17:52.165  1959  2335 W WfdsService: DefaultState - msg [9445378] is not handled
09-09 17:17:52.167  1036  1036 D RttService: SCAN_AVAILABLE : 1
09-09 17:17:52.167  1036  1543 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:52.167  1036  1544 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:52.170  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:17:52.170  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 17:17:52.177  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:17:52.188   319   880 D CommandListener: Clearing all IP addresses on wlan0
09-09 17:17:52.188  1036  1532 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-09 17:17:52.188  1036  1532 D DSQN    : disableDataServiceNotify
09-09 17:17:52.188  1036  1532 D DSQN    : stop dsqn bin
,09-09 17:17:52.189  1036  1525 D WifiNative-p2p0: doBoolean: TERMINATE
09-09 17:17:52.190  1036  1036 D WifiHS20: hidePasspointNotification off =false
09-09 17:17:52.190  1036  1525 D WifiNative-p2p0: TERMINATE: returned true
09-09 17:17:52.190  1036  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 17:17:52.190  1036  1525 E WifiStateMachine: useWiFiOffloading() : false
09-09 17:17:52.190  1036  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 17:17:52.191  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:52.191  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:52.191  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 17:17:52.192  1959  1959 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-09 17:17:52.193  1036  1532 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-09 17:17:52.193  1036  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:17:52.193  1036  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 17:17:52.193  1036  1532 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 17:17:52.194  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-09 17:17:52.194  1036  1532 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-09 17:17:52.194  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:17:52.194  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-09 17:17:52.194  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:52.194  1036  1532 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-09 17:17:52.194  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:52.194  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:52.194  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:17:52.194  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:17:52.194  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:52.194  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:52.194  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:52.194  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:17:52.194  1036  1532 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-09 17:17:52.194  6571 , 6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:52.194  6571  6571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:17:52.194  1036  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 17:17:52.194  1036  1532 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:52.194  1036  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 17:17:52.195  1589  1795 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-09 17:17:52.197  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-09 17:17:52.197  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:17:52.197  1036  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 17:17:52.197  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 17:17:52.197  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 17:17:52.198  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 17:17:52.198  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 17:17:52.198  1036  1532 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:52.198  1036  1532 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:17:52.198  1036  1532 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:17:52.198  1036  1532 D NetworkManagementService: Removing idletimer
09-09 17:17:52.198  1036  1532 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:52.199  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 17:17:52.199  1036  1532 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
09-09 17:17:52.199  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 17:17:52.199  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 17:17:52.199  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 17:17:52.199  1036  1525 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:17:52.199  1036  1525 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 17:17:52.199  1036  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 17:17:52.199  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored, value
09-09 17:17:52.199  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:52.199  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:52.199  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:17:52.199  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:17:52.199  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:52.199  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:52.199  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:52.199  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:17:52.199  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:52.199  6571  6571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:17:52.200  1864  1864 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:17:52.200  1864  1864 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-09 17:17:52.200  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:17:52.203  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:17:52.214  7144  7159 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 17:17:52.214  7144  7159 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 17:17:52.214  7144  7159 I Adreno-EGL: Build Date: 12/12/14 금
09-09 17:17:52.214  7144  7159 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 17:17:52.214  7144  7159 I Adreno-EGL: Remote Branch: 
09-09 17:17:52.214  7144  7159 I Adreno-EGL: Local Patches: 
09-09 17:17:52.214  7144  7159 I Adreno-EGL: Reconstruct Branch: 
09-09 17:17:52.225  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 17:17:52.226  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:17:52.226  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:17:52.236  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 17:17:52.237  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 17:17:52.237  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:17:52.311  1036  7101 D DhcpStateMachine: StoppedState
,09-09 17:17:52.314  1036  7101 D DhcpStateMachine: StoppedState{ when=-158ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:52.315  1036  1525 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-09 17:17:52.315  1036  1525 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-09 17:17:52.332  1036  1562 I art     : Explicit concurrent mark sweep GC freed 116398(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 2.237ms total 118.317ms
,09-09 17:17:52.350  7001  7001 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-09 17:17:52.350  7001  7001 I wpa_supplicant: monitor socket send errors count : 1
09-09 17:17:52.350  7001  7001 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1959-4\x00 that cannot receive messages
09-09 17:17:52.352  1036  7009 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-09 17:17:52.352  1036  7009 D WifiMonitor: Dropping event because (p2p0) is stopped
09-09 17:17:52.375  7001  7001 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 17:17:52.375  1036  7009 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
,09-09 17:17:52.375  1036  7009 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1,
09-09 17:17:52.375  1036  7009 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-09 17:17:52.375  1036  7009 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-09 17:17:52.375  1036  1118 D Tethering: InitialState.processMessage what=4
09-09 17:17:52.376  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 17:17:52.378  1036  1525 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=123694
09-09 17:17:52.378  1036  1525 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=123695
09-09 17:17:52.379  7001  7001 W wpa_supplicant: USIM:  scard_deinit function
09-09 17:17:52.379  1036  7009 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 17:17:52.379  1036  1525 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:17:52.379  1036  7009 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 17:17:52.380  1036  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:17:52.380  1036  1525 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=123697  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-09 17:17:52.381  1036  1525 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=123697  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-09 17:17:52.532  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-09 17:17:52.533  6363  6397 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-09 17:17:52.548  7001  7001 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-09 17:17:52.548  1036  7009 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-09 17:17:52.548  1036  7009 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
09-09 17:17:52.548  1036  7009 D WifiMonitor: Disconnecting from the supplicant, no more events
09-09 17:17:52.549  1036  1525 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
,09-09 17:17:52.557  2229  2229 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:52.572  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 17:17:52.572  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:52.572  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 17:17:52.572  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-09 17:17:52.574   319  7269 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,09-09 17:17:52.574  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-09 17:17:52.574  6945  6945 I AppUp4:CustModeStarterReceiver: onReceive
09-09 17:17:52.574  1829  7113 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
09-09 17:17:52.578  6945  6945 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@7f005e4
09-09 17:17:52.579  6945  6945 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 17:17:52.579  6945  6945 D AppUp4:CustFacade: isPhone : true
09-09 17:17:52.579  6945  6945 D AppUp4:CustModeStarterReceiver: begin check event
09-09 17:17:52.579  6945  6945 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-09 17:17:52.581  4329  4329 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:52.582  4329  4329 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 17:17:52.583  4329  4329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 17:17:52.588  4329  4329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 17:17:52.588  1829  7113 I CheckinService: active receiver: disabled
,09-09 17:17:52.598  4329  7273 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-09 17:17:52.601  4329  7274 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:17:52.601  4329  7274 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 17:17:52.607  6975  6975 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-09 17:17:52.625  6975  7276 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 17:17:52.627  3297  3297 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 17:17:52.628  3297  3297 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:52.628  3297  3297 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-09 17:17:52.633  7010  7010 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-09 17:17:52.633  7010  7010 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-09 17:17:52.635  6836  7279 W FormManager: Network not available. Please check & try again.
09-09 17:17:52.645  7083  7083 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:17:52
09-09 17:17:52.646  6836  7280 V FormManager: Network unavailable.
,09-09 17:17:52.647  7083  7083 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,09-09 17:17:52.647  7083  7083 D Weather.Utils: 2 : All the weather widget is gone.
09-09 17:17:52.648  7083  7083 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 17:17:52.648  7083  7083 D WeatherAncestor: connectivity changed - connection : true
09-09 17:17:52.648  7083  7083 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3b21a902
09-09 17:17:52.649  7083  7083 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-09 17:17:52.649  7083  7083 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-09 17:17:52.649  7083  7083 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-09 17:17:52.649  7083  7083 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 17:17:52.649  7083  7083 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:17:52
09-09 17:17:52.652  6836  7280 V FormManager: Network unavailable.
09-09 17:17:52.654  1036  1525 D WifiOffDelayIfNotUsed: stopMonitoring
09-09 17:17:52.654  1036  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 17:17:52.654  1036  1525 E WifiStateMachine: useWiFiOffloading() : false
09-09 17:17:52.654  1036  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 17:17:52.655  1959  1959 D WfdsService: Supplicant Connection state is changed : false
09-09 17:17:52.655  1959  2335 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-09 17:17:52.655  1959  2335 D WfdsService: Set the WFDS Monitor: false
09-09 17:17:52.655  1959  2335 D WfdsMonitor: WFDS Monitor is stopped
09-09 17:17:52.656  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:17:52.657  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-09 17:17:52.657  1036  1530 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-09 17:17:52.657  1036  1530 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
,09-09 17:17:52.659  1959  1959 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,09-09 17:17:52.659  2491  2491 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:52.660  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:52.660  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:52.660  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:52.660  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:17:52.660  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:17:52.660  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:52.660  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:52.660  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:52.660  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:17:52.660  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:52.661  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:52.661  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:52.661  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:17:52.661  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:17:52.661  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:52.661  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:52.661  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:52.661  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:17:52.681  6751  6751 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,09-09 17:17:52.681  6751  6751 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 17:17:52.681  6751  6751 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 17:17:52.681  6751  6751 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-09 17:17:52.682  6751  6751 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-09 17:17:52.682  6751  6751 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 17:17:52.682  6751  6751 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-09 17:17:52.682  6751  6751 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 17:17:52.682  6751  6751 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
,09-09 17:17:52.682  6751  6751 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 17:17:52.683  6751  6751 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-09 17:17:52.689  6734  6734 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 17:17:52.692  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 17:17:52.695  6836  7282 W FormManager: Network not available. Please check & try again.
09-09 17:17:52.698  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:17:52.698  6836  7283 V FormManager: Network unavailable.
09-09 17:17:52.704  6836  7283 V FormManager: Network unavailable.
,09-09 17:17:52.716  6734  6734 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 17:17:52.720  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 17:17:52.723  6836  7284 W FormManager: Network not available. Please check & try again.
09-09 17:17:52.726  6836  7285 V FormManager: Network unavailable.
09-09 17:17:52.727  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:17:52.731  6836  7285 V FormManager: Network unavailable.
09-09 17:17:52.744  4329  4329 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 17:17:52.744  4329  4329 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 17:17:52.746  4329  4329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-09 17:17:52.748  4329  4329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 17:17:52.755  4329  7286 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-09 17:17:52.757  4329  7287 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 17:17:52.757  4329  7287 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 17:17:52.807  1036  1704 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7288 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-09 17:17:52.947  7288  7288 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 17:17:52.947  7288  7288 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-09 17:17:52.956  7288  7288 V [BNRBootReceiver]: Boot Receiver Return
09-09 17:17:52.956  7288  7288 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-09 17:17:52.964  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 17:17:52.981  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:17:52.987  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:17:53.001  6794  6794 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:17:53.002  6794  6794 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:17:53.005  6794  6794 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-09 17:17:53.013  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 17:17:53.029  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:17:53.039  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 17:17:53.052  6794  6794 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:17:53.052  6794  6794 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:17:53.054  6794  6794 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-09 17:17:53.059  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-09 17:17:53.062  6751  6751 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-09 17:17:53.066  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:17:53.074  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:17:53.082  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 17:17:53.088  6794  6794 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:17:53.088  6794  6794 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:17:53.090  6794  6794 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 17:17:53.095  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:17:53.099  6652  6927 D UEI.SmartControl: Internal timer expired: 2
09-09 17:17:53.099  6652  6927 D UEI.SmartControl: unbind internal service
09-09 17:17:53.103  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:17:53.109  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 17:17:53.116  6794  6794 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:17:53.116  6794  6794 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:17:53.118  6794  6794 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 17:17:53.121  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 17:17:53.128  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:17:53.136  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 17:17:53.143  6794  6794 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:17:53.143  6794  6794 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:17:53.144  6794  6794 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 17:17:53.149  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:17:53.156  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:17:53.160  6652  6921 D serial_port: close(fd = 24)
09-09 17:17:53.163  6652  6921 I UEI.SmartControl: Serial port is closed.
09-09 17:17:53.165  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:17:53.174  6794  6794 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:17:53.174  6794  6794 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:17:53.175  6794  6794 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 17:17:53.181  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:17:53.190  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:17:53.196  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:17:53.203  6794  6794 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:17:53.204  6794  6794 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:17:53.204  6794  6794 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 17:17:53.213  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 17:17:53.232  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:17:53.245  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 17:17:53.258  6794  6794 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 17:17:53.258  6794  6794 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-09 17:17:53.266  6794  6794 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 17:17:53.275  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 17:17:53.290  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:17:53.300  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:17:53.313  6794  6794 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:17:53.314  6794  6794 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-09 17:17:53.316  6794  6794 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 17:17:53.325  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 17:17:53.334  6734  6734 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-09 17:17:53.344  1036  1531 D WifiService: New client listening to asynchronous messages
09-09 17:17:53.345  6734  6734 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 17:17:53.350  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:17:53.358  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:17:53.369  6794  6794 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:17:53.369  6794  6794 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:17:53.371  6794  6794 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-09 17:17:53.372  6794  6794 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-09 17:17:53.373  6794  6794 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-09 17:17:53.380  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:17:53.386  6734  6734 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-09 17:17:53.389  6734  6734 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 17:17:53.394  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:17:53.404  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:17:53.416  6794  6794 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:17:53.417  6794  6794 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-09 17:17:53.419  6794  6794 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-09 17:17:53.420  6794  6794 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-09 17:17:53.421  6794  6794 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-09 17:17:53.425  1036  2081 I ActivityManager: Killing 6772:com.lge.lifetracker/u0a37 (adj 15): empty #17
09-09 17:17:53.460  1036  2053 W libprocessgroup: failed to open /acct/uid_10037/pid_6772/cgroup.procs: No such file or directory
,09-09 17:17:53.465  2229  2229 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
09-09 17:17:53.484  2229  2229 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-09 17:17:53.487  2229  2229 D c       : Getting all permits...
,09-09 17:17:53.487  2229  2229 D a       : Opening database...
09-09 17:17:53.492  2229  2229 D a       : Opening database auth.proximity.permit_store...
09-09 17:17:53.493  2229  2229 D a       : Closing database...
09-09 17:17:53.511  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 17:17:53.516   319  7322 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,09-09 17:17:53.517  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-09 17:17:53.520  6734  6734 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 17:17:53.521  6734  6734 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 17:17:53.521  6734  6734 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 17:17:53.534  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:17:53.543  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:17:53.555  6794  6794 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:17:53.555  6794  6794 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:17:53.558  6794  6794 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-09 17:17:53.562  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:17:53.565  6734  6734 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 17:17:53.565  6734  6734 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 17:17:53.565  6734  6734 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 17:17:53.570  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:17:53.578  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:17:53.587  6794  6794 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:17:53.587  6794  6794 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-09 17:17:53.592  6794  6794 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 17:17:53.598  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:17:53.607  6734  6734 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 17:17:53.607  6734  6734 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 17:17:53.607  6734  6734 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 17:17:53.616  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:17:53.628  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:17:53.640  6794  6794 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:17:53.641  6794  6794 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-09 17:17:53.644  6794  6794 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-09 17:17:53.661  6734  6734 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 17:17:53.671  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 17:17:53.679  6836  7324 W FormManager: Network not available. Please check & try again.
09-09 17:17:53.681  6836  7325 V FormManager: Network unavailable.
09-09 17:17:53.682  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:17:53.683  6836  7325 V FormManager: Network unavailable.
,09-09 17:17:53.707  2229  2229 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-09 17:17:53.727  4329  4329 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 17:17:53.727  4329  4329 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 17:17:53.729  4329  4329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-09 17:17:53.733  4329  4329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-09 17:17:53.738  4329  7326 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-09 17:17:53.745  4329  7327 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 17:17:53.745  4329  7327 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-09 17:17:53.751  6734  6734 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-09 17:17:53.751  6734  6734 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 17:17:53.751  6734  6734 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 17:17:53.757  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 17:17:53.761  6836  7329 W FormManager: Network not available. Please check & try again.
,09-09 17:17:53.764  6836  7330 V FormManager: Network unavailable.
,09-09 17:17:53.767  6836  7330 V FormManager: Network unavailable.
,09-09 17:17:53.768  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 17:17:54.097  1036  1525 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:260491568] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 17:17:54.099  1036  1525 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:260491571] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-09 17:17:54.168  1036  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:17:54.182  1036  1118 D Tethering: MasterInitialState.processMessage what=3
09-09 17:17:54.194  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:54.198  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:54.201  1036  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:54.204  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-09 17:17:54.205  6363  6397 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-09 17:17:54.210  5804  5804 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-09 17:17:54.236  2229  2229 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:17:54.255  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 17:17:54.256  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:54.256  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 17:17:54.256  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-09 17:17:54.261  6945  6945 I AppUp4:CustModeStarterReceiver: onReceive
09-09 17:17:54.265  6945  6945 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@7f005e4
09-09 17:17:54.265  6945  6945 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 17:17:54.265  6945  6945 D AppUp4:CustFacade: isPhone : true
09-09 17:17:54.265  6945  6945 D AppUp4:CustModeStarterReceiver: begin check event
09-09 17:17:54.266  6945  6945 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-09 17:17:54.270  4329  4329 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:54.271  4329  4329 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 17:17:54.272  4329  4329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-09 17:17:54.289  4329  4329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-09 17:17:54.298  6975  6975 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-09 17:17:54.322  6975  7338 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 17:17:54.325  4329  7339 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 17:17:54.346  4329  7342 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:17:54.348  4329  7342 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 17:17:54.355  6836  7340 W FormManager: Network not available. Please check & try again.
09-09 17:17:54.360  1036  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-09 17:17:54.375  6836  7341 V FormManager: Network unavailable.
,09-09 17:17:54.375  3297  3297 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 17:17:54.375  3297  3297 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:54.376  3297  3297 I LgeMiscReceiver: networkInfo.isConnected() = true
09-09 17:17:54.376  3297  3297 D PhoneState: setPdpRejectCasuse : false
09-09 17:17:54.381  7010  7010 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-09 17:17:54.381  7010  7010 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-09 17:17:54.382  6836  7341 V FormManager: Network unavailable.
09-09 17:17:54.402  7083  7083 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:17:54
,09-09 17:17:54.404  7083  7083 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,09-09 17:17:54.404  7083  7083 D Weather.Utils: 2 : All the weather widget is gone.
,09-09 17:17:54.404  7083  7083 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,09-09 17:17:54.405  7083  7083 D WeatherAncestor: connectivity changed - connection : true
,09-09 17:17:54.405  7083  7083 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3b21a902
09-09 17:17:54.406  7083  7083 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-09 17:17:54.406  7083  7083 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-09 17:17:54.406  7083  7083 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-09 17:17:54.406  7083  7083 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 17:17:54.406  7083  7083 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:17:54
09-09 17:17:55.094  1036  1990 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:17:55.095  1036  1990 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-09 17:17:55.126  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-09 17:17:55.129  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 17:17:55.129  1036  1036 D Ulp_jni : JNI:system_update. Event-4
09-09 17:17:55.130  1036  1118 D BluetoothManagerService: Message: 1
09-09 17:17:55.130  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-09 17:17:55.157  1036  1118 D BluetoothManagerService: Message: 20
09-09 17:17:55.157  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25e30ccd:true
,09-09 17:17:55.161  6876  6876 D BluetoothAdapterState: make
09-09 17:17:55.166  6876  6876 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-09 17:17:55.166  6876  6876 I bluedroid-qcom: init
09-09 17:17:55.167  6876  7369 I BluetoothAdapterState: Entering OffState
09-09 17:17:55.168  6876  6876 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-09 17:17:55.168  6876  6876 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-09 17:17:55.168  6876  6876 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-09 17:17:55.168  6876  6876 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-09 17:17:55.168  6876  6876 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-09 17:17:55.172  6876  6876 I bluedroid-qcom: get_profile_interface socket
09-09 17:17:55.172  6876  6876 I bluedroid-qcom: get_profile_interface map_client
,09-09 17:17:55.176  6876  7373 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-09 17:17:55.174  7372  7372 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:17:55.181  6876  7373 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-09 17:17:55.174  7372  7372 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:17:55.188  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-09 17:17:55.189  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
,09-09 17:17:55.195  1036  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:55.197  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-09 17:17:55.197  1036  1118 D BluetoothManagerService: Message: 40
09-09 17:17:55.197  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-09 17:17:55.201  7372  7372 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-09 17:17:55.201  7372  7372 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-09 17:17:55.201  7372  7372 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,09-09 17:17:55.204  7372  7372 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-09 17:17:55.209  7372  7372 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-09 17:17:55.209  7372  7372 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-09 17:17:55.212  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:55.213  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:55.217  6876  6895 I bluedroid-qcom: config_hci_snoop_log
09-09 17:17:55.219  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-09 17:17:55.219  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-09 17:17:55.223  1036  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:55.234  6876  7369 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,09-09 17:17:55.236  1036  1118 D Tethering: MasterInitialState.processMessage what=3
09-09 17:17:55.237  1036  1118 D Tethering: MasterInitialState.processMessage what=3
09-09 17:17:55.237  6876  7373 D BluetoothAdapterProperties: Name is: G3
09-09 17:17:55.238  1036  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:55.238  6876  7369 D BluetoothAdapterProperties: Setting state to 11
09-09 17:17:55.239  6876  7369 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-09 17:17:55.240  6876  7369 I LGBluetoothServiceJni: classInitNative: succeeds
09-09 17:17:55.243  1036  1118 D BluetoothManagerService: Message: 60
09-09 17:17:55.243  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-09 17:17:55.243  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-09 17:17:55.245  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:55.253  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:55.260  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-09 17:17:55.267  1959  1959 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:55.268  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 17:17:55.272  6363  6397 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-09 17:17:55.275  6876  7369 D BluetoothBondStateMachine: make
,09-09 17:17:55.279  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:55.280  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:55.281  6751  6751 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-09 17:17:55.285  5804  5804 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-09 17:17:55.286  6876  7369 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b21a902
09-09 17:17:55.291  6876  7369 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-09 17:17:55.291  6876  7369 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b21a902
09-09 17:17:55.291  6876  7369 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
,09-09 17:17:55.292  6876  7369 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-09 17:17:55.294  6876  7387 I BluetoothBondStateMachine: StableState(): Entering Off State
09-09 17:17:55.298  5804  5804 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-09 17:17:55.298  6876  6876 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 17:17:55.299  6876  6876 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:55.299  6876  6876 V BluetoothPbapReceiver: ***********state = 11
09-09 17:17:55.300  1036  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:55.303  6876  7369 E BluetoothAdapterService: File transfer profiles supported!!
,09-09 17:17:55.305  2229  2229 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 17:17:55.311  6876  7369 E BluetoothAdapterService: File transfer profiles supported!!
09-09 17:17:55.314  6876  6876 D HeadsetService: Received start request. Starting profile...
09-09 17:17:55.314  6876  6876 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 17:17:55.314  6876  6876 D LGBluetoothHfpAdapter: Version 1.6
,09-09 17:17:55.317  6876  6876 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-09 17:17:55.319  6876  6876 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 17:17:55.319  6876  6876 D HeadsetStateMachine: make
09-09 17:17:55.346  6876  6876 D LgDataFeature: LgDataFeature() Constructor: none
,09-09 17:17:55.348  6876  6876 D LgDataFeature: LgDataFeature() Constructor Done, null
09-09 17:17:55.350  1036  1978 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7393 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
09-09 17:17:55.354  6876  7369 E BluetoothAdapterService: File transfer profiles supported!!
09-09 17:17:55.357  6876  6876 D HeadsetStateMachine: max_hf_connections = 1
,09-09 17:17:55.357  6876  6876 I bluedroid-qcom: get_profile_interface handsfree
09-09 17:17:55.359  6876  6876 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-09 17:17:55.359   323   323 V AudioPolicyService: registerClient() client 0xb04104e0, uid 1002
09-09 17:17:55.360   323  1368 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-09 17:17:55.360   323  1368 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-09 17:17:55.360   323  1368 V AudioPolicyManagerEx: getOutput() returns output 2
09-09 17:17:55.360  6876  6876 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-09 17:17:55.361   323  1369 V AudioFlinger: registerClient() client 0xb55815c8, pid 6876
09-09 17:17:55.361   323  1364 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 17:17:55.361   323  1364 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 17:17:55.361  1036  1052 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 17:17:55.361  1036  1052 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 17:17:55.361  1864  3461 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 17:17:55.361  3297  3317 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 17:17:55.361  1864  3461 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 17:17:55.361  3297  3317 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 17:17:55.361  1589  1925 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 17:17:55.361  1589  1925 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 17:17:55.362  6876  6895 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 17:17:55.362  6876  6895 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-09 17:17:55.362   323  1363 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 17:17:55.362   323  1363 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 17:17:55.362  1036  2081 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 17:17:55.362  1036  2081 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 17:17:55.362  6876  7406 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 17:17:55.362  1864  1880 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 17:17:55.362  1589  1606 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 17:17:55.362  1589  1606 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 17:17:55.362  1864  1880 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 17:17:55.362  6876  7406 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-09 17:17:55.362  3297  3318 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 17:17:55.362  3297  3318 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 17:17:55.362  6876  6876 V ToneGenerator: Create Track: 0xb4928080
09-09 17:17:55.362  6876  6876 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-09 17:17:55.362  6876  6876 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-09 17:17:55.362   323   323 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-09 17:17:55.362   323   323 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-09 17:17:55.362   323   323 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-09 17:17:55.362   323   323 V AudioPolicyManagerEx: getOutput() returns output 2
09-09 17:17:55.363   323  1368 I AudioFlinger: isAudioPlaybackHookOn() false
09-09 17:17:55.363   323  1369 V AudioPolicyManager: getOutputForAttr() usage=3, con,tent=4, tag= flags=00000000
09-09 17:17:55.363   323  1369 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-09 17:17:55.363   323  1369 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-09 17:17:55.363   323  1369 V AudioPolicyManagerEx: getOutput() returns output 2
09-09 17:17:55.363  1036  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:17:55.363  6876  6876 V AudioSystem: getLatency() output 2, latency 50
09-09 17:17:55.363  6876  6876 V AudioSystem: getFrameCount() output 2, frameCount 960
09-09 17:17:55.363  6876  6876 V AudioTrack: createTrack_l() output 2 afLatency 50
09-09 17:17:55.364  6876  7369 E BluetoothAdapterService: File transfer profiles supported!!
09-09 17:17:55.364   323  2998 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-09 17:17:55.364   323  2998 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-09 17:17:55.364   323  2998 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-09 17:17:55.364   323  2998 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-09 17:17:55.364   323  2998 V AudioFlinger: createTrack() lSessionId: 22
09-09 17:17:55.364  1036  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:17:55.365  2229  2229 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:55.366  6876  6876 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-09 17:17:55.366   323   323 V AudioFlinger: acquiring 22 from 6876, for 6876
09-09 17:17:55.366   323   323 V AudioFlinger:  added new entry for 22
09-09 17:17:55.367  6876  6876 V ToneGenerator: ToneGenerator INIT OK, time: 126700
09-09 17:17:55.367  6876  6876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b21a902
09-09 17:17:55.367  6876  7392 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-09 17:17:55.368  6876  7392 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 17:17:55.368  6876  7392 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 17:17:55.368  6876  7392 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-09 17:17:55.368   323  1368 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6876
09-09 17:17:55.368   323  1368 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-09 17:17:55.368   323  1368 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-09 17:17:55.368   323  1368 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-09 17:17:55.368   323  1368 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-09 17:17:55.368   323  1368 V voice   : voice_set_parameters: exit with code(0)
09-09 17:17:55.368   323  1368 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-09 17:17:55.368   323  1368 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-09 17:17:55.368   323  1368 V msm8974_platform: platform_set_parameters: exit with code(0)
09-09 17:17:55.368   323  1368 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-09 17:17:55.368   323  1368 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-09 17:17:55.369   323  1368 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-09 17:17:55.369  6876  6876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b21a902
09-09 17:17:55.370  6876  7392 V ToneGenerator: ToneGenerator destructor
09-09 17:17:55.370  6876  7392 V ToneGenerator: stopTone
09-09 17:17:55.370  6876  7392 V ToneGenerator: Delete Track: 0xb4928080
09-09 17:17:55.371  6876  6876 D A2dpService: Received start request. Starting profile...
09-09 17:17:55.371  6876  7392 V AudioTrack: ~AudioTrack, releasing session id from 6876 on behalf of 6876
09-09 17:17:55.371   323  2998 V AudioFlinger: releasing 22 from 6876 for 6876
09-09 17:17:55.371   323  2998 V AudioFlinger:  decremented refcount to 0
09-09 17:17:55.371   323  2998 V AudioFlinger: purging stale effects
09-09 17:17:55.371  6876  6876 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-09 17:17:55.371   323  2998 V AudioPolicyService: AudioCommandThread() adding release output 2
09-09 17:17:55.371   323  2998 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-09 17:17:55.371   323  2998 V AudioFlinger: PlaybackThread::Track destructor
09-09 17:17:55.371   323  1273 V AudioPolicyService: AudioCommandThread() waking up
09-09 17:17:55.371   323  2998 V AudioFlinger: removeClient_l() pid 6876, calling pid 323
09-09 17:17:55.371   323  1273 V AudioPolicyService: AudioCommandThread() processing release output 2
09-09 17:17:55.371   323  1273 V AudioPolicyManager: releaseOutput() 2
09-09 17:17:55.371   323  1273 V AudioPolicyService: AudioCommandThread() going to sleep
09-09 17:17:55.372  6876  6876 V Avrcp   : make
09-09 17:17:55.372  6876  6876 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-09 17:17:55.372  6876  6876 I bluedroid-qcom: get_profile_interface avrcp
09-09 17:17:55.372  1036  1910 W Process : Unable to open /proc/7409/status
09-09 17:17:55.374  6876  7369 E BluetoothAdapterService: File transfer profiles supported!!
09-09 17:17:55.381  6876  7369 E BluetoothAdapterService: File transfer profiles supported!!
09-09 17:17:55.382  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 17:17:55.383  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:55.383  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 17:17:55.383  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-09 17:17:55.383  6876  6876 V AudioManager: registerRemoteController: size of Media player list: 0
09-09 17:17:55.384  6876  6876 E AudioManager: No RCC entry present to update
09-09 17:17:55.384  6876  6876 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-09 17:17:55.385  6945  6945 I AppUp4:CustModeStarterReceiver: onReceive
09-09 17:17:55.388  6876  6876 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-09 17:17:55.388  6876  6876 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-09 17:17:55.388  6876  6876 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-09 17:17:55.390  6876  7369 E BluetoothAdapterService: File transfer profiles supported!!
09-09 17:17:55.394  6876  6876 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-09 17:17:55.392  6945  6945 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@7f005e4
09-09 17:17:55.396  6945  6945 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 17:17:55.396  6945  6945 D AppUp4:CustFacade: isPhone : true
,09-09 17:17:55.403  6876  7369 V LGMDMManager: Create singleton instance
09-09 17:17:55.404  6876  7369 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-09 17:17:55.438  6945  6945 D AppUp4:CustModeStarterReceiver: begin check event
09-09 17:17:55.438  6945  6945 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,09-09 17:17:55.457  4329  4329 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:55.458  4329  4329 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 17:17:55.460  4329  4329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-09 17:17:55.469  4329  4329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 17:17:55.481  6975  6975 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-09 17:17:55.488  4329  7415 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 17:17:55.492  1036  1994 V SIM_STK : Menu title from STK is T-Mobile
09-09 17:17:55.493  1036  1994 V SIM_STK : Menu title from STK is T-Mobile
09-09 17:17:55.501  4329  7416 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:55.501  4329  7416 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-09 17:17:55.515  6975  7417 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:55.521  3297  3297 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 17:17:55.521  3297  3297 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:55.522  3297  3297 I LgeMiscReceiver: networkInfo.isConnected() = false
,09-09 17:17:55.528  7010  7010 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-09 17:17:55.528  7010  7010 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-09 17:17:55.529  6836  7420 V FormManager: Network unavailable.
09-09 17:17:55.532  6836  7419 W FormManager: Network not available. Please check & try again.
09-09 17:17:55.539  7083  7083 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:17:55
,09-09 17:17:55.540  6836  7420 V FormManager: Network unavailable.
09-09 17:17:55.543  7393  7393 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-09 17:17:55.544  7393  7393 W LG Account v2.2: No ProfileInfo entries
09-09 17:17:55.544  7393  7393 I LG Account v2.2: isEnabled: false
09-09 17:17:55.544  7393  7393 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-09 17:17:55.544  7393  7393 I Feature : [Lifetracker]Country: EU
09-09 17:17:55.544  7393  7393 I Feature : [Lifetracker]Operator: OPEN
09-09 17:17:55.544  7393  7393 I Feature : [Lifetracker]Ranking support: false
09-09 17:17:55.544  7393  7393 I Feature : [Lifetracker]Comfort support: false
09-09 17:17:55.544  7393  7393 I Feature : [Lifetracker]Accessory: true
09-09 17:17:55.544  7393  7393 I Feature : [Lifetracker]Health device: true
09-09 17:17:55.544  7393  7393 I Feature : [Lifetracker]Extra Pedometer: false
09-09 17:17:55.544  7393  7393 I Feature : [Lifetracker]Blood glucose device: false
09-09 17:17:55.544  7393  7393 I Feature : [Lifetracker]Device Number: 3
09-09 17:17:55.548  7083  7083 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-09 17:17:55.548  7083  7083 D Weather.Utils: 2 : All the weather widget is gone.
09-09 17:17:55.548  7083  7083 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 17:17:55.549  7083  7083 D WeatherAncestor: connectivity changed - connection : true
09-09 17:17:55.549  7083  7083 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3b21a902
09-09 17:17:55.549  7083  7083 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-09 17:17:55.549  7083  7083 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-09 17:17:55.549  7083  7083 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-09 17:17:55.549  7083  7083 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 17:17:55.550  6751  6751 D BluetoothPermissionRequest: onReceive
09-09 17:17:55.551  7083  7083 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:17:55
,09-09 17:17:55.553  6751  6751 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-09 17:17:55.567  1036  1051 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-09 17:17:55.572  6363  6363 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-09 17:17:55.573  6876  6876 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-09 17:17:55.576  6363  6397 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-09 17:17:55.577  6876  6876 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-09 17:17:55.577  6876  6876 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-09 17:17:55.578  6876  6876 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-09 17:17:55.578  6876  6876 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-09 17:17:55.578  6876  6876 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 17:17:55.578  6876  6876 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-09 17:17:55.578  6876  6876 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-09 17:17:55.578  6876  6876 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-09 17:17:55.578  6876  6876 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 17:17:55.578  6876  6876 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-09 17:17:55.578  6876  6876 I BluetoothA2dpServiceJni: classInitNative
09-09 17:17:55.578  6876  6876 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 17:17:55.578  6876  6876 D A2dpStateMachine: make
09-09 17:17:55.579  6876  6876 I bluedroid-qcom: get_profile_interface a2dp
09-09 17:17:55.579  6876  7425 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-09 17:17:55.581  6876  6876 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-09 17:17:55.581  6876  6876 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-09 17:17:55.581  2229  2229 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:55.582  6876  6876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b21a902
09-09 17:17:55.582  6876  6876 D HeadsetStateMachine: Proxy object connected
09-09 17:17:55.582  6876  6876 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-09 17:17:55.582  6876  6876 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-09 17:17:55.582  6876  7424 D A2dpStateMachine: Enter Disconnected: -2
,09-09 17:17:55.584  6876  6876 I BluetoothHidServiceJni: classInitNative: succeeds
09-09 17:17:55.585  6876  6876 D HidService: Received start request. Starting profile...
09-09 17:17:55.585  6876  6876 I bluedroid-qcom: get_profile_interface hidhost
09-09 17:17:55.586  6876  6876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b21a902
09-09 17:17:55.586  6876  6876 I BluetoothHealthServiceJni: classInitNative: succeeds
09-09 17:17:55.587  6876  6876 D HealthService: Received start request. Starting profile...
09-09 17:17:55.589  6876  6876 I bluedroid-qcom: get_profile_interface health
09-09 17:17:55.589  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 17:17:55.589  6876  6876 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-09 17:17:55.589  6876  6876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b21a902
09-09 17:17:55.589  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:55.589  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 17:17:55.589  6945  6945 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-09 17:17:55.590  6945  6945 I AppUp4:CustModeStarterReceiver: onReceive
09-09 17:17:55.591  6876  6876 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 17:17:55.592  6876  7392 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-09 17:17:55.592  6876  6876 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-09 17:17:55.592  6876  7392 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
09-09 17:17:55.592  6876  7392 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-09 17:17:55.593  6876  6876 D PanService: Received start request. Starting profile...
,09-09 17:17:55.593  6876  6876 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 17:17:55.593  6876  6876 I bluedroid-qcom: get_profile_interface pan
09-09 17:17:55.593  6945  6945 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@7f005e4
09-09 17:17:55.593  6945  6945 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 17:17:55.593  6945  6945 D AppUp4:CustFacade: isPhone : true
09-09 17:17:55.593  6945  6945 D AppUp4:CustModeStarterReceiver: begin check event
09-09 17:17:55.593  6945  6945 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-09 17:17:55.596  4329  4329 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:55.596  4329  4329 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 17:17:55.597  6876  6876 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-09 17:17:55.597  6876  6876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b21a902
09-09 17:17:55.597  6876  6876 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-09 17:17:55.597  4329  4329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 17:17:55.599  4329  4329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 17:17:55.600  6876  6876 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 17:17:55.601  6876  6876 D BtGatt.GattService: Received start request. Starting profile...
09-09 17:17:55.601  6876  6876 D BtGatt.GattService: start()
09-09 17:17:55.601  6876  6876 I bluedroid-qcom: get_profile_interface gatt
09-09 17:17:55.601  6876  6876 D BtGatt.AdvertiseManager: advertise manager created
09-09 17:17:55.603  4329  7431 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 17:17:55.604  4329  7432 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:55.604  4329  7432 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 17:17:55.605  6975  6975 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-09 17:17:55.605  6876  6876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b21a902
,09-09 17:17:55.607  6876  6876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b21a902
09-09 17:17:55.608  6876  6876 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-09 17:17:55.608  6876  6876 V BluetoothMapService: BluetoothMapBinder()
09-09 17:17:55.608  6876  6876 D BluetoothMapService: Received start request. Starting profile...
09-09 17:17:55.608  6876  6876 D BluetoothMapService: start()
09-09 17:17:55.611  6876  6876 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-09 17:17:55.611  6876  6876 D BluetoothMapEmailAppObserver: createReceiver()
09-09 17:17:55.612  6876  6876 D BluetoothMapEmailAppObserver: initObservers()
09-09 17:17:55.612  6876  6876 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-09 17:17:55.617  6876  6876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b21a902
,09-09 17:17:55.621  6876  6876 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 17:17:55.624  6975  7434 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:55.624  6876  6876 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 17:17:55.624  3297  3297 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 17:17:55.624  3297  3297 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 17:17:55.624  3297  3297 I LgeMiscReceiver: networkInfo.isConnected() = false
09-09 17:17:55.626  6876  6876 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 17:17:55.626  6876  6876 V PanService: [BTUI] SIM Extra State :ABSENT
09-09 17:17:55.628  7010  7010 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-09 17:17:55.628  7010  7010 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-09 17:17:55.629  6876  6876 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-09 17:17:55.632  6876  6876 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-09 17:17:55.632  6876  6876 V BluetoothMapService: Handler(): got msg=1
09-09 17:17:55.632  6876  7369 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-09 17:17:55.632  6876  7369 I bluedroid-qcom: enable
09-09 17:17:55.633  6876  7439 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-09 17:17:55.633  6876  7439 I bt-btu  : btu_task pending for preload complete event
09-09 17:17:55.633  6876  7369 I bt_hci_bdroid: init
09-09 17:17:55.634  6876  7369 I bt_vendor: bt-vendor : init
09-09 17:17:55.634  6876  7369 I bt_vendor: bt-vendor : get_bt_soc_type
09-09 17:17:55.634  6876  7369 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-09 17:17:55.634  6876  7369 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-09 17:17:55.634  6876  7369 D bt_userial_mct: userial_init
09-09 17:17:55.634  6876  7369 D bt_hci_bdroid: set_power 1
09-09 17:17:55.634  6876  7369 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-09 17:17:55.634  6876  7369 I bt_vendor: Starting hciattach daemon
09-09 17:17:55.634  6876  7369 I bt_vendor: try to set true
09-09 17:17:55.636  6876  6876 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:55.636  6836  7436 W FormManager: Network not available. Please check & try again.
09-09 17:17:55.624  7442  7442 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:17:55.624  7442  7442 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:17:55.639  6836  7437 V FormManager: Network unavailable.
09-09 17:17:55.640  6876  6876 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-09 17:17:55.640  6876  6876 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 17:17:55.640  6876  6876 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 17:17:55.640  6876  6876 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:55.640  6876  6876 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-09 17:17:55.642  7083  7083 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:17:55
,09-09 17:17:55.644  7083  7083 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,09-09 17:17:55.644  7083  7083 D Weather.Utils: 2 : All the weather widget is gone.
09-09 17:17:55.645  7083  7083 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 17:17:55.645  6836  7437 V FormManager: Network unavailable.
09-09 17:17:55.645  7083  7083 D WeatherAncestor: connectivity changed - connection : true
09-09 17:17:55.645  7083  7083 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3b21a902
09-09 17:17:55.646  7083  7083 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-09 17:17:55.646  7083  7083 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-09 17:17:55.646  7083  7083 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-09 17:17:55.646  7083  7083 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 17:17:55.646  7083  7083 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:17:55
09-09 17:17:55.650  7443  7443 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
09-09 17:17:55.692  7450  7450 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-09 17:17:55.698  7451  7451 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-09 17:17:55.723  7453  7453 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-09 17:17:55.734  7454  7454 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
09-09 17:17:55.744  7455  7455 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-09 17:17:55.751  7456  7456 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-09 17:17:55.792  7458  7458 I libmdmdetect: ESOC framework not supported
09-09 17:17:55.793  7458  7458 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-09 17:17:55.801  7458  7458 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-09 17:17:55.801  7458  7458 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-09 17:17:55.801  7458  7458 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-09 17:17:55.801  7458  7458 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-09 17:17:55.801  7458  7458 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-09 17:17:55.801  7458  7458 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-09 17:17:55.801  7458  7458 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-09 17:17:55.846  7458  7459 E QC-QMI  : qmi_client [7458] 14: failed to locate client data
09-09 17:17:55.847   469   469 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-09 17:17:55.848   469   469 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,09-09 17:17:55.899  7460  7460 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-09 17:17:55.924  7464  7464 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-09 17:17:55.985  6876  7369 I bt_vendor: bluetooth satus is on
,09-09 17:17:55.986  6876  7369 D bt_hci_bdroid: preload
,09-09 17:17:55.988  6876  7441 D bt_userial_mct: userial_open(port:0)
09-09 17:17:55.988  6876  7441 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-09 17:17:55.993  6876  7441 I bt_vendor: Done intiailizing UART
,09-09 17:17:55.996  6876  7441 I bt_vendor: Done intiailizing UART
09-09 17:17:55.997  6876  7441 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-09 17:17:55.997  6876  7441 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-09 17:17:55.998  6876  7469 D bt_userial_mct: Entering userial_read_thread()
09-09 17:17:55.998  6876  7439 I bt-btu  : btu_task received preload complete event
09-09 17:17:55.999  6876  7439 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-09 17:17:55.999  6876  7439 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-09 17:17:56.004  6876  7439 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,09-09 17:17:56.039  6876  7439 I         : BTE_InitTraceLevels -- TRC_HCI
09-09 17:17:56.039  6876  7439 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 17:17:56.039  6876  7439 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-09 17:17:56.039  6876  7439 I         : BTE_InitTraceLevels -- TRC_AVDT
09-09 17:17:56.039  6876  7439 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 17:17:56.039  6876  7439 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 17:17:56.039  6876  7439 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 17:17:56.039  6876  7439 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 17:17:56.039  6876  7439 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-09 17:17:56.039  6876  7439 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 17:17:56.039  6876  7439 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 17:17:56.039  6876  7439 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 17:17:56.039  6876  7439 I         : BTE_InitTraceLevels -- TRC_GATT
09-09 17:17:56.039  6876  7439 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 17:17:56.039  6876  7439 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 17:17:56.039  6876  7439 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 17:17:56.073  1036  1103 W ProcessCpuTracker: Skipping unknown process pid 7379
,09-09 17:17:56.076  1036  1103 W ProcessCpuTracker: Skipping unknown process pid 7380
09-09 17:17:56.078  1036  1103 W ProcessCpuTracker: Skipping unknown process pid 7389
09-09 17:17:56.080  1036  1103 W ProcessCpuTracker: Skipping unknown process pid 7414
09-09 17:17:56.081  1036  1103 W ProcessCpuTracker: Skipping unknown process pid 7466
09-09 17:17:56.097  6876  7439 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-09 17:17:56.097  6876  7439 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0248061 
09-09 17:17:56.097  6876  7439 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0248061 
,09-09 17:17:56.118  6876  7373 E bt-btif : Calling BTA_HhEnable
09-09 17:17:56.118  6876  7373 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-09 17:17:56.118  6876  7373 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-09 17:17:56.121  6876  7439 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-09 17:17:56.121  6876  7439 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-09 17:17:56.121  6876  7439 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-09 17:17:56.122  6876  7439 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-09 17:17:56.122  6876  7439 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-09 17:17:56.123  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-09 17:17:56.123  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
09-09 17:17:56.123  6876  7373 D BluetoothAdapterProperties: Name is: G3
09-09 17:17:56.124  6876  7373 D BluetoothAdapterProperties: Scan Mode:20
09-09 17:17:56.124  6876  7373 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 17:17:56.125  6876  7373 D bt_hci_bdroid: postload
09-09 17:17:56.125  6876  7441 D bt_hci_bdroid: Used up Tx Cmd credits
09-09 17:17:56.125  6876  7441 D bt_hci_bdroid: Used up Tx Cmd credits
09-09 17:17:56.126  6876  7441 D bt_hci_bdroid: Used up Tx Cmd credits
09-09 17:17:56.126  6876  7441 D bt_hci_bdroid: Used up Tx Cmd credits
09-09 17:17:56.127  6876  7439 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-09 17:17:56.127  6876  7373 D bte_conf: Device ID record 1 : primary
09-09 17:17:56.127  6876  7373 D bte_conf:   vendorId            = 00c4
09-09 17:17:56.127  6876  7373 D bte_conf:   vendorIdSource      = 0001
09-09 17:17:56.127  6876  7373 D bte_conf:   product             = 13a1
09-09 17:17:56.127  6876  7373 D bte_conf:   version             = 1000
09-09 17:17:56.127  6876  7373 D bte_conf:   clientExecutableURL = 
09-09 17:17:56.127  6876  7373 D bte_conf:   serviceDescription  = 
09-09 17:17:56.127  6876  7373 D bte_conf:   documentationURL    = 
09-09 17:17:56.127  6876  7373 D bte_conf: bte_load_did_conf no section named DID2.
09-09 17:17:56.128  6876  7441 D bt_hci_bdroid: Used up Tx Cmd credits
09-09 17:17:56.130  6876  7469 E bt_mct  : hci lib postload completed
,09-09 17:17:56.135  6876  7369 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-09 17:17:56.135  6876  7369 D BluetoothAdapterProperties: ScanMode =  20
09-09 17:17:56.135  6876  7369 D BluetoothAdapterProperties: State =  11
09-09 17:17:56.135  6876  7369 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-09 17:17:56.135  6876  7369 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-09 17:17:56.135  6876  7369 D BluetoothAdapterProperties: Setting state to 12
09-09 17:17:56.135  6876  7369 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 17:17:56.136  6876  7373 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-09 17:17:56.136  6876  7373 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-09 17:17:56.134  7474  7474 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:17:56.134  7474  7474 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:17:56.143  1036  1118 D BluetoothManagerService: Message: 60
09-09 17:17:56.143  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-09 17:17:56.143  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
,09-09 17:17:56.146  6876  7439 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 17:17:56.146  6876  7439 W bt-smp  : Plain text(LSB ~ MSB) = b9 aa 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 17:17:56.146  6876  7439 W bt-smp  : Encrypted text(LSB ~ MSB) = 2b fe 98 69 5f e7 3d 29 31 90 0d ac 49 08 94 78 
09-09 17:17:56.147  6876  7439 W bt-btm  : Stopping oneshot timer
09-09 17:17:56.159  6876  7369 I BluetoothAdapterState: Entering On State
,09-09 17:17:56.168  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:56.168  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:56.168  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:17:56.168  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:17:56.168  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:17:56.168  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:56.168  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:56.168  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:17:56.171   319  7110 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-09 17:17:56.171   319  7110 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 28
09-09 17:17:56.172   319  7110 D libc-netbsd: res_queryN name = clients3.google.com., class = 1, type = 1
,09-09 17:17:56.177  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-09 17:17:56.184  6876  7439 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 17:17:56.184  6876  7439 W bt-smp  : Plain text(LSB ~ MSB) = 5e 3d 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 17:17:56.184  6876  7439 W bt-smp  : Encrypted text(LSB ~ MSB) = 0a 56 ae 4c 04 f3 1f 79 b9 ab e5 51 c5 a6 3a 6c 
,09-09 17:17:56.187  6876  7439 W bt-btm  : Stopping oneshot timer
09-09 17:17:56.191  6571  6571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:17:56.191  1036  7100 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-09 17:17:56.202  1036  7100 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-3s998ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:56.202  1036  7100 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-4s8ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:56.202  1036  7100 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,09-09 17:17:56.207  6751  6766 D BluetoothPan: onBluetoothStateChange on: true
09-09 17:17:56.207  6751  6766 D BluetoothPan: onBluetoothStateChange call bindService
09-09 17:17:56.208  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:56.208  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:56.208  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:17:56.208  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:17:56.208  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:17:56.208  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:56.208  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:56.208  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:17:56.210  6876  7439 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 17:17:56.210  6876  7439 W bt-smp  : Plain text(LSB ~ MSB) = be 35 47 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 17:17:56.210  6876  7439 W bt-smp  : Encrypted text(LSB ~ MSB) = 4b ed 30 3e c4 71 32 f0 07 c9 d0 e0 c0 4d b3 90 
09-09 17:17:56.210  6876  7439 W bt-btm  : Stopping oneshot timer
09-09 17:17:56.213  6876  7369 D LGBluetoothServiceAdapter: [BTUI] OnState
09-09 17:17:56.213  6876  7369 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-09 17:17:56.213  6876  7369 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-09 17:17:56.214  6876  7369 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-09 17:17:56.215  6876  7369 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-09 17:17:56.215  6571  6571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:17:56.225  6751  6767 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 17:17:56.228  6751  6766 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 17:17:56.231  1864  2439 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:17:56.233  6876  7439 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 17:17:56.233  6876  7439 W bt-smp  : Plain text(LSB ~ MSB) = b9 d9 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 17:17:56.233  6876  7439 W bt-smp  : Encrypted text(LSB ~ MSB) = 0e 34 3b e1 08 41 ec ed fd ba 5b 4b ee 3c 3b 2f 
09-09 17:17:56.233  6876  7439 W bt-btm  : Stopping oneshot timer
09-09 17:17:56.237  6751  6751 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 17:17:56.237  6751  6751 D PanProfile: Bluetooth service connected
09-09 17:17:56.239  6876  7373 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 17:17:56.239  6876  7373 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-09 17:17:56.245  6876  7439 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 17:17:56.245  6876  7439 W bt-smp  : Plain text(LSB ~ MSB) = f7 55 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 17:17:56.245  6876  7439 W bt-smp  : Encrypted text(LSB ~ MSB) = bc 15 4c b4 ae 64 0d f5 b5 04 d2 21 f1 94 18 74 
09-09 17:17:56.245  6876  7439 W bt-btm  : Stopping oneshot timer
09-09 17:17:56.245  7489  7489 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-09 17:17:56.249  1864  1864 D BluetoothHeadset: Proxy object connected
,09-09 17:17:56.249  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:17:56.250  1036  1036 D BluetoothHeadset: Proxy object connected
09-09 17:17:56.251  1864  1879 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:17:56.251  6751  6751 D BluetoothInputDevice: Proxy object connected
09-09 17:17:56.251  6751  6751 D HidProfile: Bluetooth service connected
09-09 17:17:56.253  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 17:17:56.253  1864  1864 D BluetoothHeadset: Proxy object connected
09-09 17:17:56.253  1864  2439 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:17:56.255  1036  1036 D BluetoothA2dp: Proxy object connected
09-09 17:17:56.255  1864  1864 D BluetoothHeadset: Proxy object connected
09-09 17:17:56.256  6751  6767 D BluetoothMap: onBluetoothStateChange: up=true
09-09 17:17:56.258  6751  6751 D BluetoothMap: Proxy object connected
09-09 17:17:56.258  6751  6751 D MapProfile: Bluetooth service connected
,09-09 17:17:56.258  6751  6751 D BluetoothMap: getConnectedDevices()
09-09 17:17:56.260  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-09 17:17:56.260  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-09 17:17:56.260  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-09 17:17:56.260  6876  6895 V BluetoothMapService: getConnectedDevices()
09-09 17:17:56.262  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 17:17:56.262  1959  1959 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:56.263  1959  2186 D LGBluetoothAPIService: Message: 1
09-09 17:17:56.263  1959  2186 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-09 17:17:56.266  6571  6571 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-09 17:17:56.268  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:56.271  1036  1118 D BluetoothManagerService: Message: 40
,09-09 17:17:56.271  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:56.272  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-09 17:17:56.274  1959  2186 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-09 17:17:56.279  6876  6876 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:56.279  6751  6751 D LocalBluetoothProfileManager: Adding local A2DP profile
09-09 17:17:56.279  6876  6876 D BluetoothMapService: STATE_ON
09-09 17:17:56.281  1036  1118 D BluetoothManagerService: Message: 30
09-09 17:17:56.283  6751  6751 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-09 17:17:56.284  6876  6876 D LGBluetoothAPIServer: [BTUI] onCreate()
09-09 17:17:56.284  6876  6876 D LGBluetoothAPIServer: [BTUI] onBind()
,09-09 17:17:56.285  1036  1118 D BluetoothManagerService: Message: 30
09-09 17:17:56.288  1959  1959 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-09 17:17:56.288  1959  2186 D LGBluetoothAPIService: Message: 100
09-09 17:17:56.288  1959  2186 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-09 17:17:56.293  6751  6751 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-09 17:17:56.294  6751  6751 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-09 17:17:56.296  6751  6751 D BluetoothA2dp: Proxy object connected
09-09 17:17:56.297  6751  6751 D A2dpProfile: Bluetooth service connected
09-09 17:17:56.299  6751  6751 D BluetoothHeadset: Proxy object connected
09-09 17:17:56.300  6751  6751 D HeadsetProfile: Bluetooth service connected
,09-09 17:17:56.303  6876  6876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b21a902
09-09 17:17:56.303  6876  6876 V BluetoothPbapService: Pbap Service onCreate
09-09 17:17:56.303  6876  6876 V BluetoothPbapService: Starting PBAP service
09-09 17:17:56.303  6751  6751 D DockEventReceiver: finishStartingService: stopping service
09-09 17:17:56.304  6876  6876 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-09 17:17:56.304  6876  6876 V BluetoothPbapService: Pbap Service onBind
09-09 17:17:56.305  6751  6751 D BluetoothPbap: Proxy object connected
09-09 17:17:56.305  6876  6876 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:56.305  6876  6876 V BluetoothPbapService: state: 12
09-09 17:17:56.305  6751  6751 D PbapServerProfile: Bluetooth service connected
09-09 17:17:56.306  6876  6876 V BluetoothMapService: Handler(): got msg=1
09-09 17:17:56.306  6876  6876 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-09 17:17:56.306  6876  6876 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 17:17:56.306  6876  6876 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:56.307  6876  6876 V BluetoothPbapReceiver: ***********state = 12
09-09 17:17:56.307  6876  7498 D BluetoothMapMasInstance: MAS initSocket()
09-09 17:17:56.308  6876  7498 D BluetoothMapMasInstance:   masId = 00
09-09 17:17:56.308  6876  7498 D BluetoothMapMasInstance:   msgTypes = 0e
09-09 17:17:56.308  6876  7498 D BluetoothMapMasInstance:   masName = SMS/MMS
09-09 17:17:56.308  6876  7498 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-09 17:17:56.308  6876  6876 V BluetoothPbapService: Handler(): got msg=1
09-09 17:17:56.308  6876  6876 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-09 17:17:56.309  6876  7499 V BluetoothPbapService: Pbap Service initSocket
09-09 17:17:56.309  2229  2229 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 17:17:56.310  2229  2229 D c       : Getting all permits...
09-09 17:17:56.310  2229  2229 D a       : Opening database...
09-09 17:17:56.310  1036  2081 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:17:56.310  1036  1952 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:17:56.311  6876  7498 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:17:56.311  6876  7499 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 17:17:56.313  6876  7373 D BluetoothAdapterProperties: Scan Mode:21
09-09 17:17:56.314  6876  7498 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-09 17:17:56.314  6876  7373 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-09 17:17:56.314  6876  7499 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-09 17:17:56.315  6876  7498 V BluetoothMapMasInstance: Succeed to create listening socket 
09-09 17:17:56.315  6876  7499 V BluetoothPbapService: Succeed to create listening socket 
09-09 17:17:56.315  6876  7498 D BluetoothMapMasInstance: Accepting socket connection...
09-09 17:17:56.315  6876  7499 V BluetoothPbapService: Accepting socket connection...
09-09 17:17:56.315  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:56.316  6876  7373 D BluetoothAdapterProperties: Scan Mode:21
09-09 17:17:56.316  6876  7373 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-09 17:17:56.316  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:56.317  2229  2229 D a       : Opening database auth.proximity.permit_store...
09-09 17:17:56.317  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:56.318  2229  2229 D a       : Closing database...
09-09 17:17:56.319  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:56.327  6751  6751 D BluetoothPermissionRequest: onReceive
,09-09 17:17:56.329  6751  6751 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-09 17:17:56.330  6751  6751 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-09 17:17:56.333  6876  6876 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-09 17:17:56.335  6876  6876 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-09 17:17:56.339  6876  6876 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-09 17:17:56.355  6876  6876 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-09 17:17:56.355  6876  6876 V BtOppService: onCreate
,09-09 17:17:56.358  6876  6876 V BluetoothOppNotification: send message
09-09 17:17:56.361  6876  6876 V BtOppService: Starting RfcommListener
09-09 17:17:56.363  6876  6876 D BluetoothOppPreference: Dumping Names:  
09-09 17:17:56.363  6876  6876 D BluetoothOppPreference: {}
09-09 17:17:56.363  6876  6876 D BluetoothOppPreference: Dumping Channels:  
09-09 17:17:56.363  6876  6876 D BluetoothOppPreference: {}
09-09 17:17:56.364  6876  6876 V BtOppService: onStartCommand
09-09 17:17:56.365  6876  7506 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-09 17:17:56.366  6876  6876 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:56.366  6876  6876 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,09-09 17:17:56.368  6876  6876 V BluetoothOppNotification: new notify threadi!
,09-09 17:17:56.369  6876  6876 V BluetoothOppNotification: send delay message
09-09 17:17:56.369  6876  6876 V BtOppService: start RfcommListener
09-09 17:17:56.370  6876  7503 V BtOppService: Deleted complete outbound shares, number =  0
09-09 17:17:56.370  6876  7507 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-09 17:17:56.372  6876  6876 V BtOppService: RfcommListener started
09-09 17:17:56.373  6876  7503 V BtOppService: Deleted complete inbound failed shares, number = 0
09-09 17:17:56.374  6876  7508 V BtOppRfcommListener: Starting RFCOMM listener....
09-09 17:17:56.374  1036  1704 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:17:56.375  6876  7508 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:17:56.375  6876  7503 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-09 17:17:56.375  6876  7506 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-09 17:17:56.376  6876  7507 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@279de93f on behalf of 
09-09 17:17:56.376  6876  7508 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
09-09 17:17:56.376  6876  7508 V BtOppRfcommListener: Started RFCOMM listener....
09-09 17:17:56.376  6876  7508 I BtOppRfcommListener: Accept thread started.
09-09 17:17:56.376  6876  7508 V BtOppRfcommListener: Accepting connection...
09-09 17:17:56.377  6876  7503 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2107b20c on behalf of 
09-09 17:17:56.378  6876  7506 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@29cea755 on behalf of 
,09-09 17:17:56.383  6876  7507 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-09 17:17:56.384  6876  7506 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,09-09 17:17:56.384  6876  7506 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-09 17:17:56.385  6876  6876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b21a902
,09-09 17:17:56.385  6876  6876 V BluetoothFtpService: Ftp Service onCreate
09-09 17:17:56.385  6876  6876 I BluetoothFtpService: Ftp Service onCreate
09-09 17:17:56.385  6876  7507 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-09 17:17:56.386  6876  6876 V BluetoothFtpService: Ftp Service onStartCommand
09-09 17:17:56.386  6876  6876 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:56.386  6876  6876 V BluetoothFtpService: Starting Listening on sockets
09-09 17:17:56.387  6876  6876 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 17:17:56.387  6876  6876 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 17:17:56.387  6876  6876 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 17:17:56.387  6876  6876 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:56.387  6876  7506 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1811da5b on behalf of 
09-09 17:17:56.387  6876  6876 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-09 17:17:56.387  6876  6876 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-09 17:17:56.388  6876  7506 V BluetoothOppNotification: update too frequent, put in queue
09-09 17:17:56.390  6876  7506 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-09 17:17:56.390  6876  6876 V BtOppService: ContentObserver received notification
09-09 17:17:56.391  6876  6876 V BtOppService: ContentObserver received notification
09-09 17:17:56.391  6876  6876 V BluetoothFtpService: Handler(): got msg=1
09-09 17:17:56.392  6876  6876 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-09 17:17:56.392  6876  6876 V BluetoothFtpService: Ftp Service initSocket
,09-09 17:17:56.395  1036  1990 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:17:56.395  6876  7509 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-09 17:17:56.395  6876  7509 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-09 17:17:56.396  6876  6876 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:17:56.396  6876  7507 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d83e2f8 on behalf of 
09-09 17:17:56.397  6876  6876 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=78
09-09 17:17:56.397  6876  6876 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-09 17:17:56.397  6876  7509 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@141f63d1 on behalf of 
09-09 17:17:56.398  6876  7509 V BluetoothOppNotification: update too frequent, put in queue
09-09 17:17:56.399  6876  7510 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-09 17:17:56.400  6876  7509 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-09 17:17:56.403  6876  7507 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-09 17:17:56.406  6876  7507 V BluetoothOppNotification: outbound notification was removed.
09-09 17:17:56.407  6876  7507 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-09 17:17:56.408  6876  7507 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@266d5e36 on behalf of 
09-09 17:17:56.409  6876  7507 V BluetoothOppNotification: inbound: succ-0  fail-0
09-09 17:17:56.410  6876  6876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b21a902
09-09 17:17:56.410  6876  6876 V BluetoothSapService: Sap Service onCreate
09-09 17:17:56.410  6876  7507 V BluetoothOppNotification: inbound notification was removed.
09-09 17:17:56.410  6876  7507 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-09 17:17:56.411  6876  7507 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ea927c2 on behalf of 
09-09 17:17:56.411  6876  6876 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:56.411  6876  6876 V BluetoothSapService: state: 12
09-09 17:17:56.412  6876  6876 V BluetoothSapService: Starting SAP server process
09-09 17:17:56.414  6876  6876 V BluetoothSapService: SAP Service startRfcommListenerThread
09-09 17:17:56.404  7511  7511 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-09 17:17:56.404  7511  7511 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:17:56.417  6876  7512 V BluetoothSapService: Sap Service initRfcommSocket
09-09 17:17:56.418  1036  2310 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:17:56.418  6876  7512 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:17:56.419  6876  7512 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
09-09 17:17:56.419  6876  7512 V BluetoothSapService: Succeed to create listening socket 
09-09 17:17:56.419  6876  7512 V BluetoothSapService: Accepting socket connection...
09-09 17:17:56.427  7511  7511 V BT_SAP  : Event pipe created
09-09 17:17:56.427  7511  7511 V BT_SAP  : create_server_socket qcom.sap.server
09-09 17:17:56.427  7511  7511 V BT_SAP  : created socket fd 6
,09-09 17:17:56.448  7119  7165 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-09 17:17:57.146  1036  1522 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:57.146  1036  1522 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 17:17:57.195  1036  1525 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-09 17:17:57.196  1036  1525 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-09 17:17:57.371  6876  6876 V BluetoothOppNotification: new notify threadi!
,09-09 17:17:57.372  6876  6876 V BluetoothOppNotification: send delay message
,09-09 17:17:57.384  6876  7524 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-09 17:17:57.389  6876  7524 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a2f39d3 on behalf of 
09-09 17:17:57.393  6876  7524 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-09 17:17:57.398  6876  7524 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-09 17:17:57.400  6876  7524 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5ec1910 on behalf of 
09-09 17:17:57.402  6876  7524 V BluetoothOppNotification: outbound: succ-0  fail-0
09-09 17:17:57.407  6876  7524 V BluetoothOppNotification: outbound notification was removed.
09-09 17:17:57.407  6876  7524 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,09-09 17:17:57.410  6876  7524 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2789bc09 on behalf of 
,09-09 17:17:57.411  6876  7524 V BluetoothOppNotification: inbound: succ-0  fail-0
09-09 17:17:57.413  6876  7524 V BluetoothOppNotification: inbound notification was removed.
09-09 17:17:57.413  6876  7524 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-09 17:17:57.414  6876  7524 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@4e5fe0e on behalf of 
09-09 17:17:57.550  1036  1704 I ActivityManager: Killing 7288:com.lge.bnr/1000 (adj 15): empty #17
,09-09 17:17:57.585  1036  1934 W libprocessgroup: failed to open /acct/uid_1000/pid_7288/cgroup.procs: No such file or directory
,09-09 17:17:57.594  1036  2053 I ActivityManager: Killing 6652:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
09-09 17:17:57.612  6794  6794 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-09 17:17:57.613  6794  6794 W System.err: android.os.DeadObjectException
09-09 17:17:57.613  6794  6794 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 17:17:57.613  6794  6794 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-09 17:17:57.613  6794  6794 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-09 17:17:57.613  6794  6794 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-09 17:17:57.613  6794  6794 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-09 17:17:57.613  6794  6794 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-09 17:17:57.613  6794  6794 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 17:17:57.613  6794  6794 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 17:17:57.613  6794  6794 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 17:17:57.613  6794  6794 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 17:17:57.613  6794  6794 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:17:57.613  6794  6794 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:17:57.613  6794  6794 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 17:17:57.613  6794  6794 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 17:17:57.614  6794  6794 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-09 17:17:57.614  6794  6794 W System.err: android.os.DeadObjectException
09-09 17:17:57.614  6794  6794 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 17:17:57.614  6794  6794 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-09 17:17:57.614  6794  6794 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-09 17:17:57.614  6794  6794 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-09 17:17:57.614  6794  6794 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-09 17:17:57.614  6794  6794 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-09 17:17:57.614  6794  6794 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 17:17:57.614  6794  6794 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 17:17:57.614  6794  6794 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 17:17:57.615  6794  6794 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 17:17:57.615  6794  6794 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:17:57.615  6794  6794 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:17:57.615  6794  6794 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 17:17:57.615  6794  6794 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 17:17:57.615  6794  6794 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-09 17:17:57.615  6794  6794 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,09-09 17:17:57.652  1036  1768 W libprocessgroup: failed to open /acct/uid_1000/pid_6652/cgroup.procs: No such file or directory
,09-09 17:17:57.658  1036  1768 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
09-09 17:17:57.670  6794  6794 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-09 17:17:57.670  6794  6794 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,09-09 17:17:57.727  1036  1562 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7525 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-09 17:17:57.753  6794  6794 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-09 17:17:57.805  7525  7525 D UEI.SmartControl: Quickset Services start...
,09-09 17:17:57.810  7525  7525 I UEI.SmartControl: Manufacture = LGE
09-09 17:17:57.810  7525  7525 D UEI.SmartControl: Id = LGNevo
09-09 17:17:57.811  7525  7525 D UEI.SmartControl: File observer start...
09-09 17:17:57.812  7525  7525 E UEI.SmartControl: IR Port is disabled: false
09-09 17:17:57.812  7525  7525 D UEI.SmartControl: Starting file observer...
09-09 17:17:57.812  7525  7525 D UEI.SmartControl: Extracting JNI libs...
09-09 17:17:57.812  7525  7525 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-09 17:17:57.883  7525  7525 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-09 17:17:57.883  7525  7525 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-09 17:17:57.883  7525  7525 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-09 17:17:57.911  7525  7525 I UEI.SmartControl: --- Selecting new region: 6
,09-09 17:17:57.913  7525  7525 I UEI.SmartControl: Model = LG-D855
09-09 17:17:57.914  7525  7525 D UEI.SmartControl: QS Service created
,09-09 17:17:57.928  7525  7525 I UEI.SmartControl: Service initServices...
,09-09 17:17:57.935  7525  7525 D UEI.SmartControl: QS start get config
,09-09 17:17:57.971  7525  7525 D UEI.SmartControl: Loading JNI Libs...
,09-09 17:17:58.151  1036  1562 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-09 17:17:58.151  1036  1562 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@284daf1c mBinding = false
,09-09 17:17:58.174  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 17:17:58.174  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 17:17:58.174  1036  1036 D Ulp_jni : JNI:system_update. Event-4
09-09 17:17:58.176  1036  1118 D BluetoothManagerService: Message: 2
,09-09 17:17:58.177  1036  1118 D BluetoothManagerService: Sending off request.
09-09 17:17:58.178  6876  6895 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-09 17:17:58.179  6876  7369 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-09 17:17:58.179  6876  7369 D BluetoothAdapterProperties: Setting state to 13
09-09 17:17:58.179  6876  7369 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 17:17:58.180  1036  1118 D BluetoothManagerService: Message: 60
09-09 17:17:58.180  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-09 17:17:58.180  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-09 17:17:58.180  6876  7369 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 17:17:58.180  6876  7369 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-09 17:17:58.182  6876  6876 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:58.182  6876  6876 D BluetoothMapService: STATE_TURNING_OFF
09-09 17:17:58.183  6876  6876 V BluetoothMapService: Handler(): got msg=4
09-09 17:17:58.183  6876  6876 D BluetoothMapService: MAP Service closeService in
09-09 17:17:58.183  6876  6876 D BluetoothMapMasInstance: MAP Service shutdown
,09-09 17:17:58.186  1959  1959 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:58.188  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 17:17:58.185  6876  7498 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-09 17:17:58.185  6876  7498 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 17:17:58.185  6876  7498 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-09 17:17:58.185  6876  7498 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-09 17:17:58.185  6876  7498 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-09 17:17:58.185  6876  7498 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-09 17:17:58.185  6876  7498 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-09 17:17:58.185  6876  7498 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-09 17:17:58.193  6876  6876 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 17:17:58.193  6876  6876 V BluetoothMapService: MAP Service closeService out
09-09 17:17:58.193  6876  6876 V BtOppService: Receiver DISABLED_ACTION 
09-09 17:17:58.193  6876  6876 I BtOppRfcommListener: stopping Accept Thread
,09-09 17:17:58.194  6876  6876 V BtOppRfcommListener: close mBtServerSocket
09-09 17:17:58.194  6876  7508 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 17:17:58.194  6876  7508 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 17:17:58.195  6876  6876 V BtOppRfcommListener: waiting for thread to terminate
09-09 17:17:58.195  6876  6876 V BtOppRfcommListener: done waiting for thread to terminate
09-09 17:17:58.201  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:58.201  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:58.201  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:58.201  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:17:58.201  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:17:58.201  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:58.201  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:58.201  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:58.201  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:17:58.201  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:58.202  6571  6571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:17:58.203  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:58.203  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:58.203  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:58.203  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:17:58.203  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:17:58.203  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:58.203  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:58.203  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:58.203  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:17:58.204  6571  6571 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:58.204  6571  6571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:17:58.214  6751  6751 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,09-09 17:17:58.216  6751  6751 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-09 17:17:58.221  6876  7373 D BluetoothAdapterProperties: Scan Mode:20
09-09 17:17:58.221  6876  7369 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-09 17:17:58.222  6876  7369 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-09 17:17:58.227  6876  7499 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 17:17:58.228  6876  7510 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 17:17:58.228  6876  7512 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 17:17:58.229  6876  7439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-09 17:17:58.229  6876  7439 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
,09-09 17:17:58.234  6876  7439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 17:17:58.234  6876  7439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 17:17:58.234  6876  7439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 17:17:58.234  6876  7439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 17:17:58.234  6876  7439 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:17:58.234  6876  7439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 17:17:58.234  6876  7439 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 17:17:58.234  6876  7439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,09-09 17:17:58.234  6876  7439 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 17:17:58.234  6876  7439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-09 17:17:58.234  6876  7439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-09 17:17:58.234  6876  7439 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-09 17:17:58.234  6876  6876 V BtOppService: onDestroy
09-09 17:17:58.236  6876  6876 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-09 17:17:58.253  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:58.256  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:58.261  6876  6876 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 17:17:58.261  6876  6876 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:58.261  6876  6876 V BluetoothPbapReceiver: ***********state = 13
09-09 17:17:58.263  6876  6876 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-09 17:17:58.265  6876  6876 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:58.265  6876  6876 V BluetoothPbapService: state: 13
09-09 17:17:58.265  6876  6876 V BluetoothPbapService: Pbap Service closeService in
09-09 17:17:58.266  6876  6876 V BluetoothPbapService: successfully stopped pbap service
09-09 17:17:58.266  6876  6876 V BluetoothPbapService: Pbap Service closeService out
09-09 17:17:58.267  6876  6876 V BluetoothPbapService: Pbap Service onDestroy
09-09 17:17:58.267  6876  6876 V BluetoothPbapService: Pbap Service closeService in
09-09 17:17:58.267  6876  6876 V BluetoothPbapService: Pbap Service closeService out
09-09 17:17:58.267  6876  6876 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-09 17:17:58.269  2229  2229 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 17:17:58.270  6751  6751 D DockEventReceiver: finishStartingService: stopping service
,09-09 17:17:58.276  6751  6751 D BluetoothPbap: Proxy object disconnected
09-09 17:17:58.276  6751  6751 D PbapServerProfile: Bluetooth service disconnected
09-09 17:17:58.280  6751  6751 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-09 17:17:58.287  6751  6751 D BluetoothPermissionRequest: onReceive
09-09 17:17:58.287  6751  6751 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-09 17:17:58.292  6751  6751 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-09 17:17:58.293  7525  7525 I UEI.SmartControl: Supports setup maps: true
09-09 17:17:58.295  6876  6876 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-09 17:17:58.295  6876  6876 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,09-09 17:17:58.296  6876  6876 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-09 17:17:58.297  7525  7525 D UEI.SmartControl: QS start statue = true Error code = 0
09-09 17:17:58.297  7525  7525 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-09 17:17:58.297  7525  7525 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-09 17:17:58.298  7525  7525 I UEI.SmartControl: ### init IR Blaster...
09-09 17:17:58.302  7525  7525 D serial_port: Configuring serial port
09-09 17:17:58.303  6876  6876 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:58.303  6876  6876 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-09 17:17:58.304  6876  6876 V BluetoothFtpService: Ftp Service onStartCommand
09-09 17:17:58.304  6876  6876 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:58.305  6876  6876 V BluetoothFtpService: Ftp Service closeService
09-09 17:17:58.305  6876  6876 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-09 17:17:58.305  7525  7525 E UEI.SmartControl: UEIBLaster setting for 616
09-09 17:17:58.305  7525  7525 I UEI.SmartControl: Setting serial record hearder size = 2
09-09 17:17:58.305  7525  7525 I UEI.SmartControl: configuring settings for MAXQ616
09-09 17:17:58.305  7525  7525 I UEI.SmartControl: Get version...
09-09 17:17:58.306  6876  6876 V BluetoothFtpService: successfully stopped ftp service
09-09 17:17:58.306  6876  6876 V BluetoothFtpService: Ftp Service onDestroy
09-09 17:17:58.306  6876  6876 V BluetoothFtpService: Ftp Service closeService
09-09 17:17:58.309  6876  6876 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 17:17:58.309  6876  6876 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 17:17:58.309  6876  6876 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 17:17:58.309  6876  6876 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:58.309  6876  6876 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
,09-09 17:17:58.309  6876  6876 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-09 17:17:58.311  6876  6876 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:58.311  6876  6876 V BluetoothSapService: state: 13
09-09 17:17:58.311  6876  6876 V BluetoothSapService: Stopping SAP server process
09-09 17:17:58.313  6876  6876 V BluetoothSapService: Sap Service closeSapService in
09-09 17:17:58.313  6876  6876 V BluetoothSapService: Close listen Socket : 
09-09 17:17:58.313  6876  6876 V BluetoothSapService: Close rfcomm Socket : 
09-09 17:17:58.313  6876  6876 V BluetoothSapService: Close sapd  Socket : 
09-09 17:17:58.315  6876  6876 V BluetoothSapService: Sap Service closeSapService out
09-09 17:17:58.315  6876  6876 V BluetoothSapService: Sap Service onDestroy
09-09 17:17:58.315  6876  6876 V BluetoothSapService: Sap Service closeSapService in
09-09 17:17:58.315  6876  6876 V BluetoothSapService: Close listen Socket : 
09-09 17:17:58.316  6876  6876 V BluetoothSapService: Close rfcomm Socket : 
09-09 17:17:58.316  6876  6876 V BluetoothSapService: Close sapd  Socket : 
09-09 17:17:58.318  6876  6876 V BluetoothSapService: Sap Service closeSapService out
09-09 17:17:58.323  7525  7561 D UEI.SmartControl: serial port data available: 21
,09-09 17:17:58.351  7525  7525 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-09 17:17:58.351  7525  7525 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-09 17:17:58.351  7525  7525 I UEI.SmartControl: QS saving settings...
09-09 17:17:58.353  7525  7525 D UEI.SmartControl: IR Blaster version: 25672567
,09-09 17:17:58.370  7525  7561 D UEI.SmartControl: serial port data available: 4
,09-09 17:17:58.408  7525  7565 I UEI.SmartControl: Device manager: loading config....
09-09 17:17:58.409  7525  7565 D UEI.SmartControl: ----------- loading internal config...
,09-09 17:17:58.411  7525  7525 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-09 17:17:58.415  7525  7525 E UEI.SmartControl: Services init done
09-09 17:17:58.415  7525  7525 D UEI.SmartControl: QS Service init finished
09-09 17:17:58.418  7525  7525 D UEI.SmartControl: QS Service version name: 2.1.91
09-09 17:17:58.418  7525  7525 D UEI.SmartControl: QS Service version code: 201091
09-09 17:17:58.419  7525  7525 D UEI.SmartControl: Service requested: Control
09-09 17:17:58.423  7525  7565 E UEI.SmartControl: Loading SETTINGS...
,09-09 17:17:58.425  7525  7525 D UEI.SmartControl: Request IControl service: devices are loaded...
09-09 17:17:58.433  7525  7565 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-09 17:17:58.446  7525  7564 I UEI.SmartControl: Notify AllClients services are ready: 0
09-09 17:17:58.446  7525  7564 D UEI.SmartControl: -----service ready thread exits
,09-09 17:17:58.565  1036  1052 I art     : Explicit concurrent mark sweep GC freed 72586(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 3.535ms total 137.518ms
,09-09 17:17:58.566  6794  6794 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-09 17:17:58.566  7525  7540 I UEI.SmartControl: ------ IControl API: 11
09-09 17:17:58.567  1036  1052 I ActivityManager: Killing 6794:com.lge.qremote/u0a112 (adj 15): empty #17
,09-09 17:17:58.568  7525  7540 I UEI.SmartControl: Registering callback...
09-09 17:17:58.663  1036  1562 W libprocessgroup: failed to open /acct/uid_10112/pid_6794/cgroup.procs: No such file or directory
09-09 17:17:58.664  7525  7525 D UEI.SmartControl: Internal service binding...
,09-09 17:17:59.134  6876  7373 D bt_hci_bdroid: cleanup
,09-09 17:17:59.142  6876  7441 I bt_lpm  : LPM is already off!!!
09-09 17:17:59.143  6876  7469 I bt_userial_mct: exiting userial_read_thread
09-09 17:17:59.143  6876  7469 D bt_userial_mct: Leaving userial_evt_read_thread()
09-09 17:17:59.144  6876  7439 W bt-btif : ag scb idx 1 not allocated
09-09 17:17:59.144  6876  7439 E bt-btif : BTA AG is already disabled, ignoring ...
09-09 17:17:59.144  6876  7439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 17:17:59.144  6876  7439 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:17:59.144  6876  7439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 17:17:59.144  6876  7439 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 17:17:59.144  6876  7439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 17:17:59.144  6876  7439 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 17:17:59.144  6876  7439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 17:17:59.144  6876  7439 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:17:59.144  6876  7439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 17:17:59.144  6876  7439 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 17:17:59.144  6876  7439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 17:17:59.144  6876  7439 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 17:17:59.144  6876  7439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 17:17:59.144  6876  7439 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:17:59.145  6876  7439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 17:17:59.145  6876  7439 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 17:17:59.145  6876  7439 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 17:17:59.145  6876  7439 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 17:17:59.145  6876  7439 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-09 17:17:59.149  6876  7373 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-09 17:17:59.149  6876  7441 I bt_vendor: hw_epilog_process
09-09 17:17:59.150  6876  7373 D bt_hci_bdroid: cleanup Finalizing cleanup
09-09 17:17:59.150  6876  7373 D bt_userial_mct: userial_close
09-09 17:17:59.150  6876  7373 E bt_userial_mct: pthread_join() FAILED result:3
09-09 17:17:59.150  6876  7373 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-09 17:17:59.157  6876  7373 D bt_hci_bdroid: set_power 0
09-09 17:17:59.157  6876  7373 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-09 17:17:59.157  6876  7373 I bt_vendor: bluetooth satus is on
09-09 17:17:59.157  6876  7373 I bt_vendor: bt-vendor : resetting BT status
09-09 17:17:59.157  6876  7373 I bt_vendor: Starting hciattach daemon
09-09 17:17:59.157  6876  7373 I bt_vendor: try to set false
,09-09 17:17:59.164  6876  7373 I bt_vendor: Starting hciattach daemon
09-09 17:17:59.164  6876  7373 I bt_vendor: try to set false
09-09 17:17:59.166  6876  7373 I bt_vendor: cleanup
09-09 17:17:59.167  6876  7439 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-09 17:17:59.167  6876  7373 I GKI_LINUX: GKI_exit_task 0 done
09-09 17:17:59.167  6876  7373 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-09 17:17:59.169  6876  7369 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-09 17:17:59.173  6876  6876 D HeadsetService: Received stop request...Stopping profile...
,09-09 17:17:59.178  6876  6876 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-09 17:17:59.178  6876  6876 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 17:17:59.179  6876  6876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b21a902
09-09 17:17:59.181  1864  1864 D BluetoothHeadset: Proxy object disconnected
09-09 17:17:59.181  1864  1864 D BluetoothHeadset: Proxy object disconnected
09-09 17:17:59.181  1864  1864 D BluetoothHeadset: Proxy object disconnected
09-09 17:17:59.185  1036  1036 D BluetoothHeadset: Proxy object disconnected
09-09 17:17:59.185  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-09 17:17:59.186  6876  7369 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-09 17:17:59.189  6876  7392 D HeadsetStateMachine: Exit Disconnected: -1
09-09 17:17:59.190  6876  6876 D A2dpService: Received stop request...Stopping profile...
09-09 17:17:59.190  6876  7424 D A2dpStateMachine: Exit Disconnected: -1
09-09 17:17:59.192  6876  6876 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-09 17:17:59.193  6876  6876 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-09 17:17:59.193  6876  6876 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 17:17:59.193  6876  6876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b21a902
09-09 17:17:59.195  1036  1036 D BluetoothA2dp: Proxy object disconnected
09-09 17:17:59.195  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-09 17:17:59.196  6876  6876 D HidService: Received stop request...Stopping profile...
09-09 17:17:59.196  6876  6876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b21a902
09-09 17:17:59.198  6876  6876 D HealthService: Received stop request...Stopping profile...
09-09 17:17:59.198  6876  6876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b21a902
,09-09 17:17:59.202  6876  6876 D HeadsetStateMachine: Unbinding service...
09-09 17:17:59.204  6876  6876 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 17:17:59.204  6876  6876 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 17:17:59.204  6876  6876 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 17:17:59.204  6876  6876 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 17:17:59.204  6876  6876 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 17:17:59.204  6876  6876 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 17:17:59.204  6876  6876 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-09 17:17:59.205  6876  6876 D PanService: Received stop request...Stopping profile...
09-09 17:17:59.206  6876  6876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b21a902
09-09 17:17:59.207  6876  6876 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 17:17:59.208  6876  6876 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 17:17:59.208  6876  6876 D BtGatt.GattService: stop()
09-09 17:17:59.208  6876  6876 D BtGatt.AdvertiseManager: advertise clients cleared
09-09 17:17:59.209  6876  6876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b21a902
09-09 17:17:59.211  6876  6876 D BluetoothMapService: Received stop request...Stopping profile...
09-09 17:17:59.211  6876  6876 D BluetoothMapService: stop()
,09-09 17:17:59.215  6876  6876 D BluetoothMapEmailAppObserver: deinitObservers()
09-09 17:17:59.215  6876  6876 D BluetoothMapEmailAppObserver: removeReceiver()
09-09 17:17:59.215  6876  6876 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b21a902
09-09 17:17:59.217  6876  6876 I BluetoothA2dpServiceJni: cleanupNative
09-09 17:17:59.217  6876  7425 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-09 17:17:59.217  6876  6876 I GKI_LINUX: GKI_exit_task 2 done
09-09 17:17:59.217  6876  6876 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-09 17:17:59.218  6876  6876 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 17:17:59.218  6876  6876 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 17:17:59.218  6876  6876 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 17:17:59.219  6876  6876 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 17:17:59.219  6876  6876 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 17:17:59.219  6876  6876 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-09 17:17:59.219  6876  6876 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 17:17:59.223  6876  6876 V BluetoothMapService: Handler(): got msg=4
09-09 17:17:59.223  6876  6876 D BluetoothMapService: MAP Service closeService in
09-09 17:17:59.223  6876  6876 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 17:17:59.224  6876  6876 V BluetoothMapService: MAP Service closeService out
,09-09 17:17:59.228  6876  7369 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-09 17:17:59.228  6876  7369 D BluetoothAdapterProperties: Setting state to 10
09-09 17:17:59.228  6876  7369 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-09 17:17:59.229  6876  6876 D BluetoothMapService: cleanup()
09-09 17:17:59.229  6876  6876 D BluetoothMapService: MAP Service closeService in
09-09 17:17:59.229  6876  6876 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 17:17:59.229  6876  6876 V BluetoothMapService: MAP Service closeService out
09-09 17:17:59.230  1036  1118 D BluetoothManagerService: Message: 60
09-09 17:17:59.230  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-09 17:17:59.230  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-09 17:17:59.231  6876  7369 I BluetoothAdapterState: Entering OffState
09-09 17:17:59.232  6751  6767 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:17:59.234  6751  6766 D BluetoothPan: onBluetoothStateChange on: false
09-09 17:17:59.234  6751  6767 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 17:17:59.235  6751  6766 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 17:17:59.235  1864  1880 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 17:17:59.239  6751  6767 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 17:17:59.240  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:17:59.241  1864  3461 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:17:59.241  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 17:17:59.241  1864  1879 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 17:17:59.242  6751  6766 D BluetoothMap: onBluetoothStateChange: up=false
09-09 17:17:59.243  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-09 17:17:59.243  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-09 17:17:59.245  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-09 17:17:59.245  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-09 17:17:59.245  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@284daf1c mBinding = false
09-09 17:17:59.245  1036  1118 D BluetoothManagerService: Sending unbind request.
09-09 17:17:59.250  6876  7373 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-09 17:17:59.254  6876  6876 I GKI_LINUX: GKI_exit_task 1 done
09-09 17:17:59.254  6876  6876 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-09 17:17:59.254  6876  6876 I BluetoothServiceJni: cleanupNative: return from cleanup
09-09 17:17:59.254  6876  6876 I art     : --- WEIRD: removing null entry 248
09-09 17:17:59.254  6876  6876 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
09-09 17:17:59.254  6876  6876 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-09 17:17:59.255  6876  6876 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-09 17:17:59.257  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-09 17:17:59.259  6876  6876 I art     : System.exit called, status: 0
09-09 17:17:59.259  6876  6876 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-09 17:17:59.280   323  1369 V AudioFlinger: 6876 died, releasing its sessions
09-09 17:17:59.280   323  1369 V AudioFlinger:  pid 1864 @ 0
09-09 17:17:59.280   323  1369 V AudioFlinger:  pid 3297 @ 1
09-09 17:17:59.280   323  1369 V AudioFlinger:  pid 3297 @ 2
,09-09 17:17:59.284  1959  1959 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
09-09 17:17:59.284  1959  2186 D LGBluetoothAPIService: Message: 101
09-09 17:17:59.284  1959  2186 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
09-09 17:17:59.285  1959  2186 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
09-09 17:17:59.285  1959  2186 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
09-09 17:17:59.292  6751  6751 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,09-09 17:17:59.337  1036  1704 I ActivityManager: Process com.android.bluetooth (pid 6876) has died
,09-09 17:17:59.337  1036  1704 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
09-09 17:17:59.337  1036  1704 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
09-09 17:17:59.343  1959  1959 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:59.344  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 17:17:59.344  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:59.345  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:59.347  1959  2186 D LGBluetoothAPIService: Message: 2
09-09 17:17:59.347  1959  2186 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
09-09 17:17:59.350  1589  1589 D BluetoothAdapter: 955769583: getState() :  mService = null. Returning STATE_OFF
09-09 17:17:59.350  1589  1589 D BluetoothAdapter: 955769583: getState() :  mService = null. Returning STATE_OFF
09-09 17:17:59.351  6751  6751 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-09 17:17:59.352  6751  6751 D LGBluetoothEventManager: [BTUI] clear device connection state
,09-09 17:17:59.360  6751  6751 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-09 17:17:59.411  1036  1052 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7596 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-09 17:17:59.413  6751  6751 D DockEventReceiver: finishStartingService: stopping service
,09-09 17:17:59.511  7596  7596 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-09 17:17:59.512  7596  7596 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 17:17:59.512  7596  7596 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-09 17:17:59.513  7596  7596 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 17:17:59.536  7596  7596 D BluetoothAdapterApp: Loading JNI Library
,09-09 17:17:59.577  7596  7596 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@89deeaa Instance Count = 1
,09-09 17:17:59.584  7596  7596 D BluetoothAdapterApp: onCreate
09-09 17:17:59.612  7596  7596 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-09 17:17:59.612  7596  7596 D ProfileConfigQcom: Adding HeadsetService
,09-09 17:17:59.612  7596  7596 D ProfileConfigQcom: [BTUI] A2dpService is supported
,09-09 17:17:59.612  7596  7596 D ProfileConfigQcom: Adding A2dpService
09-09 17:17:59.613  7596  7596 D ProfileConfigQcom: [BTUI] HidService is supported
,09-09 17:17:59.613  7596  7596 D ProfileConfigQcom: Adding HidService
09-09 17:17:59.613  7596  7596 D ProfileConfigQcom: [BTUI] HealthService is supported
,09-09 17:17:59.613  7596  7596 D ProfileConfigQcom: Adding HealthService
09-09 17:17:59.614  7596  7596 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-09 17:17:59.615  7596  7596 D ProfileConfigQcom: [BTUI] PanService is supported
,09-09 17:17:59.615  7596  7596 D ProfileConfigQcom: Adding PanService
,09-09 17:17:59.615  7596  7596 D ProfileConfigQcom: [BTUI] GattService is supported
09-09 17:17:59.616  7596  7596 D ProfileConfigQcom: Adding GattService
09-09 17:17:59.616  7596  7596 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
,09-09 17:17:59.616  7596  7596 D ProfileConfigQcom: Adding BluetoothMapService
09-09 17:17:59.617  7596  7596 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-09 17:17:59.618  7596  7596 V BluetoothPbapReceiver: PbapReceiver onReceive 
,09-09 17:17:59.619  7596  7596 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:59.620  7596  7596 V BluetoothPbapReceiver: ***********state = 10
09-09 17:17:59.622  7596  7596 V LGMDMManagerInternal: Create singleton instance
,09-09 17:17:59.735  7596  7596 D LGBluetoothAPIServer: [BTUI] onCreate(),
09-09 17:17:59.735  2229  2229 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 17:17:59.735  7596  7596 D LGBluetoothAPIServer: [BTUI] onBind()
,09-09 17:17:59.743  1959  1959 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-09 17:17:59.744  1959  2186 D LGBluetoothAPIService: Message: 100
09-09 17:17:59.744  1959  2186 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-09 17:17:59.751  6751  6751 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,09-09 17:17:59.758  6751  6751 D BluetoothPermissionRequest: onReceive
09-09 17:17:59.761  6751  6751 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-09 17:17:59.761  6751  6751 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-09 17:17:59.764  6751  6751 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-09 17:17:59.774  7596  7596 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-09 17:17:59.778  7596  7596 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:59.781  7596  7596 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-09 17:17:59.782  7596  7596 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,09-09 17:17:59.782  7596  7596 V BluetoothSapReceiver: SapReceiver onReceive 
,09-09 17:17:59.783  7596  7596 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:59.784  7596  7596 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,09-09 17:17:59.787  6815  6815 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings,
09-09 17:18:00.003  1036  1362 D PowerManagerServiceEx: acquireWakeLockInternal: lock=438390959, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,09-09 17:18:00.047  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,09-09 17:18:00.047  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
09-09 17:18:00.047  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,09-09 17:18:00.052  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
09-09 17:18:00.054  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
09-09 17:18:00.054  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
09-09 17:18:00.055  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
09-09 17:18:00.055  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
09-09 17:18:00.080  1036  1103 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7624 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-09 17:18:00.141  2642  2642 D [Concierge]Service: onStartCommand(). Type : 9
,09-09 17:18:00.197  7624  7624 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 17:18:00.214  7624  7624 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-09 17:18:00.236  7624  7624 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,09-09 17:18:00.236  7624  7624 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,09-09 17:18:00.237  7624  7624 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,09-09 17:18:00.238  7624  7624 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-09 17:18:00.238  7624  7624 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-09 17:18:00.240  7624  7624 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-09 17:18:00.243  7624  7624 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-09 17:18:00.248  7624  7624 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
09-09 17:18:00.248  7624  7624 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:1777
,09-09 17:18:00.251  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=438390959 [*alarm*], flags=0x0
09-09 17:18:00.253  7624  7624 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-09 17:18:00.257  7624  7624 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-09 17:18:00.257  7624  7624 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-09 17:18:00.258  7624  7624 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-09 17:18:00.258  7624  7624 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,09-09 17:18:00.282  7624  7624 D LgDataFeature: LgDataFeature() Constructor: none
09-09 17:18:00.282  7624  7624 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 17:18:00.289  7624  7624 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-09 17:18:00.290  7624  7624 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-09 17:18:00.290  7624  7624 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-09 17:18:00.290  7624  7624 V SoundPool: doLoad: loading sample sampleID=1
09-09 17:18:00.292  7624  7661 V SoundPool: Start decode
09-09 17:18:00.292  7624  7661 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-09 17:18:00.292  7624  7624 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-09 17:18:00.293   323  1369 V MediaPlayerService: decode(22, 10857164, 17813)
09-09 17:18:00.293   323  1369 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-09 17:18:00.293   323  1369 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-09 17:18:00.293   323  1369 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-09 17:18:00.293   323  1369 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-09 17:18:00.293   323  1369 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-09 17:18:00.293   323  1369 V MediaPlayerService: player type = 3
09-09 17:18:00.293   323  1369 V AwesomePlayer: AwesomePlayer create()
09-09 17:18:00.294   323  1369 V AwesomePlayer: reset_l() 
09-09 17:18:00.294   323  1369 V AwesomePlayer: cancelPlayerEvents
09-09 17:18:00.294   323  1369 V AwesomePlayer: setAudioSink() 
09-09 17:18:00.294   323  1369 V AwesomePlayer: reset_l() 
,09-09 17:18:00.294   323  1369 V AudioCache: notify(0xb1432300, 8, 0, 0)
09-09 17:18:00.294   323  1369 V AudioCache: ignored
09-09 17:18:00.294   323  1369 V AwesomePlayer: cancelPlayerEvents
09-09 17:18:00.294   323  1369 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
,09-09 17:18:00.294   323  1369 V AwesomePlayer: setDataSource_l dataSource
09-09 17:18:00.294   323  1369 V LGParserOSAL: SniffLGParser start
09-09 17:18:00.294   323  1369 V LGParserOSAL: MainType:5, SubType=0
,09-09 17:18:00.294   323  1369 V LGParserOSAL: #### check Mime : application/ogg
09-09 17:18:00.294   323  1369 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-09 17:18:00.294   323  1369 E MediaExtractor: Use LGExtractor :application/ogg 
,09-09 17:18:00.299  7624  7624 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-09 17:18:00.314  7624  7624 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-09 17:18:00.315  7624  7624 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,09-09 17:18:00.322   323  1369 V LGParserOSAL: supported mime: application/ogg
09-09 17:18:00.322   323  1369 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-09 17:18:00.322   323  1369 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-09 17:18:00.322   323  1369 V AwesomePlayer: mBitrate = -1 bits/sec
09-09 17:18:00.322   323  1369 V AwesomePlayer: AudioTrack Setting
09-09 17:18:00.322   323  1369 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-09 17:18:00.322   323  1369 V AwesomePlayer: setAudioSource() 
09-09 17:18:00.322   323  1369 V MediaPlayerService: prepare
09-09 17:18:00.322   323  1369 V AwesomePlayer: prepareAsync_l() 
09-09 17:18:00.322   323  1369 V MediaPlayerService: wait for prepare
09-09 17:18:00.322   323  7663 V AwesomePlayer: onPrepareAsyncEvent() 
09-09 17:18:00.322   323  7663 V AwesomePlayer: initAudioDecoder() 
09-09 17:18:00.322   323  7663 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-09 17:18:00.322   323  7663 V AudioSystem: isOffloadSupported()
09-09 17:18:00.322   323  7663 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-09 17:18:00.322   323  7663 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-09 17:18:00.323   323  7663 I AudioFlinger: isAudioPlaybackHookOn() false
09-09 17:18:00.323   323  7663 V AwesomePlayer: getUseOffload() = 0 
09-09 17:18:00.323   323  7663 V OMXCodec: OMXCodec::Create
09-09 17:18:00.323   323  7663 V OMXCodec: findMatchingCodecs()
09-09 17:18:00.323   323  7663 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-09 17:18:00.323   323  7663 V OMXCodec: matchingCodecs.size()=1
09-09 17:18:00.323   323  7663 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-09 17:18:00.326   323  7663 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-09 17:18:00.326   323  7663 V LGCodecAdapter: LG Codec Adapter start
09-09 17:18:00.326   323  7663 V OMXCodec: OMXCodec Createtor
09-09 17:18:00.326   323  7663 V OMXCodec: setComponentRole
09-09 17:18:00.326   323  7663 V OMXCodec: configureCodec protected=0
09-09 17:18:00.326   323  7663 V LGCodecAdapter: called getLGCodecSpecificData
09-09 17:18:00.326   323  7663 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-09 17:18:00.326   323  7663 V LGCodecOSAL: Called LGconfigureCodecMETA
09-09 17:18:00.326   323  7663 V LGCodecOSAL: Called LGconfigureCodecMSG
09-09 17:18:00.326   323  7663 V LGCodecOSAL: Not support LGCodec
09-09 17:18:00.326   323  7663 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-09 17:18:00.327   323  7663 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-09 17:18:00.327   323  7663 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-09 17:18:00.327   323  7663 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-09 17:18:00.327   323  7663 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-09 17:18:00.327   323  7663 V AudioSystem: isOffloadSupported()
09-09 17:18:00.327   323  7663 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-09 17:18:00.327   323  7663 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-09 17:18:00.327   323  7663 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-09 17:18:00.327   323  7663 V OMXCodec: init()
09-09 17:18:00.327   323  7663 V OMXCodec: [OMX.google.vorbis.decoder] set,State mState=1 , newState=2
09-09 17:18:00.327   323  7663 V OMXCodec: allocateBuffers
09-09 17:18:00.327   323  7663 V OMXCodec: allocateBuffersOnPort portIndex=0
09-09 17:18:00.327   323  7663 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-09 17:18:00.327   323  7663 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f1f0 on input port
09-09 17:18:00.327   323  7663 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f240 on input port
09-09 17:18:00.327   323  7663 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
09-09 17:18:00.327   323  7663 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on input port
09-09 17:18:00.327   323  7663 V OMXCodec: allocateBuffersOnPort portIndex=1
09-09 17:18:00.327   323  7663 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-09 17:18:00.328   323  7663 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on output port
09-09 17:18:00.328   323  7663 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
09-09 17:18:00.328   323  7663 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
09-09 17:18:00.328   323  7663 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on output port
09-09 17:18:00.328   323  7663 V OMXCodec: init() mAsyncCompletion wait!!! 
09-09 17:18:00.328   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-09 17:18:00.328   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-09 17:18:00.328   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-09 17:18:00.328   323  7663 V OMXCodec: init() mAsyncCompletion wait!!! 
09-09 17:18:00.328   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-09 17:18:00.328   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-09 17:18:00.328   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-09 17:18:00.328   323  7663 V OMXCodec: init() mAsyncCompletion wait free! 
09-09 17:18:00.328   323  7663 V AwesomePlayer: finishAsyncPrepare_l() 
09-09 17:18:00.328   323  7663 V AudioCache: notify(0xb1432300, 5, 0, 0)
09-09 17:18:00.328   323  7663 V AudioCache: ignored
09-09 17:18:00.328   323  7663 V AudioCache: notify(0xb1432300, 1, 0, 0)
09-09 17:18:00.328   323  7663 V AudioCache: prepared
09-09 17:18:00.329   323  1369 V AudioCache: wait - success
09-09 17:18:00.329   323  1369 V MediaPlayerService: start
09-09 17:18:00.329   323  1369 V AwesomePlayer: play_l() 
09-09 17:18:00.329   323  1369 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-09 17:18:00.329   323  1369 V AwesomePlayer: createAudioPlayer_l
09-09 17:18:00.329   323  1369 V AwesomePlayer: seekAudioIfNecessary_l() 
09-09 17:18:00.329   323  1369 V AwesomePlayer: startAudioPlayer_l() 
09-09 17:18:00.329   323  1369 D AudioPlayer: start of Playback, useOffload 0
09-09 17:18:00.329   323  1369 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-09 17:18:00.329   323  1369 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
,09-09 17:18:00.334   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
,09-09 17:18:00.334   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-09 17:18:00.334   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-09 17:18:00.334   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-09 17:18:00.334   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-09 17:18:00.334   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-09 17:18:00.335   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048256
09-09 17:18:00.335   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 17:18:00.335   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048416
09-09 17:18:00.335   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 17:18:00.335   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048496
09-09 17:18:00.335   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 17:18:00.335   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048656
09-09 17:18:00.335   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 17:18:00.335   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-09 17:18:00.335   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-09 17:18:00.335   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-09 17:18:00.335   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-09 17:18:00.335   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-09 17:18:00.335   323  7665 V OMXCodec: allocateBuffersOnPort portIndex=1
09-09 17:18:00.335   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-09 17:18:00.336   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
09-09 17:18:00.336   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
09-09 17:18:00.336   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on output port
09-09 17:18:00.336   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
09-09 17:18:00.336   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-09 17:18:00.336   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-09 17:18:00.337   323  1369 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-09 17:18:00.338   323  1369 V AudioCache: notify(0xb1432300, 6, 0, 0)
09-09 17:18:00.338   323  1369 V AudioCache: ignored
09-09 17:18:00.338   323  1369 V MediaPlayerService: wait for playback complete
09-09 17:18:00.340   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.340   323  7666 V AudioCache: memcpy(0xac300000, 0xb100f000, 4096)
09-09 17:18:00.342  7624  7624 V LGMDMManager: Create singleton instance
09-09 17:18:00.342   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.342   323  7666 V AudioCache: memcpy(0xac301000, 0xb100f000, 4096)
,09-09 17:18:00.344   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.344   323  7666 V AudioCache: memcpy(0xac302000, 0xb100f000, 4096)
09-09 17:18:00.345   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.345   323  7666 V AudioCache: memcpy(0xac303000, 0xb100f000, 4096)
09-09 17:18:00.346   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.346   323  7666 V AudioCache: memcpy(0xac304000, 0xb100f000, 4096)
09-09 17:18:00.348   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.348   323  7666 V AudioCache: memcpy(0xac305000, 0xb100f000, 4096)
09-09 17:18:00.349   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.349   323  7666 V AudioCache: memcpy(0xac306000, 0xb100f000, 4096)
09-09 17:18:00.350   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.351   323  7666 V AudioCache: memcpy(0xac307000, 0xb100f000, 4096)
09-09 17:18:00.352   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.352   323  7666 V AudioCache: memcpy(0xac308000, 0xb100f000, 4096)
09-09 17:18:00.353   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.353   323  7666 V AudioCache: memcpy(0xac309000, 0xb100f000, 4096)
09-09 17:18:00.355   323  7666 V AudioCache: write(0xb100f000, 4096)
,09-09 17:18:00.355   323  7666 V AudioCache: memcpy(0xac30a000, 0xb100f000, 4096)
09-09 17:18:00.356   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.356   323  7666 V AudioCache: memcpy(0xac30b000, 0xb100f000, 4096)
09-09 17:18:00.358   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.358   323  7666 V AudioCache: memcpy(0xac30c000, 0xb100f000, 4096)
09-09 17:18:00.359   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.359   323  7666 V AudioCache: memcpy(0xac30d000, 0xb100f000, 4096)
09-09 17:18:00.360   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.360   323  7666 V AudioCache: memcpy(0xac30e000, 0xb100f000, 4096)
09-09 17:18:00.360   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.360   323  7666 V AudioCache: memcpy(0xac30f000, 0xb100f000, 4096)
09-09 17:18:00.361   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.361   323  7666 V AudioCache: memcpy(0xac310000, 0xb100f000, 4096)
09-09 17:18:00.362   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.362   323  7666 V AudioCache: memcpy(0xac311000, 0xb100f000, 4096)
09-09 17:18:00.362   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.362   323  7666 V AudioCache: memcpy(0xac312000, 0xb100f000, 4096)
09-09 17:18:00.363   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.363   323  7666 V AudioCache: memcpy(0xac313000, 0xb100f000, 4096)
09-09 17:18:00.364   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.364   323  7666 V AudioCache: memcpy(0xac314000, 0xb100f000, 4096)
09-09 17:18:00.364   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.364   323  7666 V AudioCache: memcpy(0xac315000, 0xb100f000, 4096)
09-09 17:18:00.365   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.365   323  7666 V AudioCache: memcpy(0xac316000, 0xb100f000, 4096)
09-09 17:18:00.366   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.366   323  7666 V AudioCache: memcpy(0xac317000, 0xb100f000, 4096)
09-09 17:18:00.367   323  7666 V AudioCache: write(0xb100f000, 4096)
,09-09 17:18:00.367   323  7666 V AudioCache: memcpy(0xac318000, 0xb100f000, 4096)
09-09 17:18:00.367   323  7666 V AudioCache: write(0xb100f000, 4096)
,09-09 17:18:00.367   323  7666 V AudioCache: memcpy(0xac319000, 0xb100f000, 4096)
09-09 17:18:00.368   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.368   323  7666 V AudioCache: memcpy(0xac31a000, 0xb100f000, 4096)
09-09 17:18:00.368   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.368   323  7666 V AudioCache: memcpy(0xac31b000, 0xb100f000, 4096)
09-09 17:18:00.369   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.369   323  7666 V AudioCache: memcpy(0xac31c000, 0xb100f000, 4096)
09-09 17:18:00.369   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.370   323  7666 V AudioCache: memcpy(0xac31d000, 0xb100f000, 4096)
09-09 17:18:00.370   323  7666 V AudioCache: write(0xb100f000, 4096)
,09-09 17:18:00.370   323  7666 V AudioCache: memcpy(0xac31e000, 0xb100f000, 4096)
09-09 17:18:00.371   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.371   323  7666 V AudioCache: memcpy(0xac31f000, 0xb100f000, 4096)
09-09 17:18:00.372   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.372   323  7666 V AudioCache: memcpy(0xac320000, 0xb100f000, 4096)
09-09 17:18:00.372   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.372   323  7666 V AudioCache: memcpy(0xac321000, 0xb100f000, 4096)
,09-09 17:18:00.373   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.373   323  7666 V AudioCache: memcpy(0xac322000, 0xb100f000, 4096)
09-09 17:18:00.374   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.374   323  7666 V AudioCache: memcpy(0xac323000, 0xb100f000, 4096)
09-09 17:18:00.374   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.374   323  7666 V AudioCache: memcpy(0xac324000, 0xb100f000, 4096)
09-09 17:18:00.375   323  7666 V AudioCache: write(0xb100f000, 4096)
,09-09 17:18:00.375   323  7666 V AudioCache: memcpy(0xac325000, 0xb100f000, 4096)
09-09 17:18:00.376   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.376   323  7666 V AudioCache: memcpy(0xac326000, 0xb100f000, 4096)
,09-09 17:18:00.377   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.377   323  7666 V AudioCache: memcpy(0xac327000, 0xb100f000, 4096)
09-09 17:18:00.377   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.377   323  7666 V AudioCache: memcpy(0xac328000, 0xb100f000, 4096)
,09-09 17:18:00.378   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.378   323  7666 V AudioCache: memcpy(0xac329000, 0xb100f000, 4096)
,09-09 17:18:00.379   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.379   323  7666 V AudioCache: memcpy(0xac32a000, 0xb100f000, 4096)
09-09 17:18:00.380   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.380   323  7666 V AudioCache: memcpy(0xac32b000, 0xb100f000, 4096)
,09-09 17:18:00.380   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.380   323  7666 V AudioCache: memcpy(0xac32c000, 0xb100f000, 4096)
,09-09 17:18:00.381   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.381   323  7666 V AudioCache: memcpy(0xac32d000, 0xb100f000, 4096)
09-09 17:18:00.382   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.382   323  7666 V AudioCache: memcpy(0xac32e000, 0xb100f000, 4096)
09-09 17:18:00.382   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.382   323  7666 V AudioCache: memcpy(0xac32f000, 0xb100f000, 4096)
09-09 17:18:00.383   323  7666 V AudioCache: write(0xb100f000, 4096)
,09-09 17:18:00.383   323  7666 V AudioCache: memcpy(0xac330000, 0xb100f000, 4096)
09-09 17:18:00.384   323  7666 V AudioCache: write(0xb100f000, 4096)
09-09 17:18:00.384   323  7666 V AudioCache: memcpy(0xac331000, 0xb100f000, 4096)
09-09 17:18:00.384   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-09 17:18:00.384   323  7666 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-09 17:18:00.384   323  7666 V AwesomePlayer: postAudioEOS() 
09-09 17:18:00.384   323  7666 V AudioCache: write(0xb100f000, 280)
,09-09 17:18:00.384   323  7666 V AudioCache: memcpy(0xac332000, 0xb100f000, 280)
09-09 17:18:00.386   323  7663 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-09 17:18:00.387   323  7663 V AwesomePlayer: onStreamDone
09-09 17:18:00.387   323  7663 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
,09-09 17:18:00.387   323  7663 V AudioCache: notify(0xb1432300, 2, 0, 0)
09-09 17:18:00.387   323  7663 V AudioCache: playback complete
09-09 17:18:00.387   323  7663 V AwesomePlayer: pause_l() 
09-09 17:18:00.387   323  1369 V AudioCache: wait - success,
09-09 17:18:00.387   323  7663 V AudioCache: notify(0xb1432300, 7, 0, 0)
09-09 17:18:00.387   323  7663 V AudioCache: ignored
09-09 17:18:00.387   323  1369 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
,09-09 17:18:00.387   323  7663 V AwesomePlayer: cancelPlayerEvents
09-09 17:18:00.387   323  7663 D AudioPlayer: Pause Playback at 1068125
09-09 17:18:00.388   323  1369 V AwesomePlayer: reset_l() 
,09-09 17:18:00.388   323  1369 V AudioCache: notify(0xb1432300, 8, 0, 0)
09-09 17:18:00.388   323  1369 V AudioCache: ignored
09-09 17:18:00.388   323  1369 V AwesomePlayer: cancelPlayerEvents
,09-09 17:18:00.388   323  1369 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-09 17:18:00.388   323  1369 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-09 17:18:00.388   323  1369 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
,09-09 17:18:00.388   323  1369 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-09 17:18:00.388   323  1369 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-09 17:18:00.388   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
,09-09 17:18:00.388   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-09 17:18:00.388   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-09 17:18:00.388   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 0
,09-09 17:18:00.388   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-09 17:18:00.388   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
09-09 17:18:00.388   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-09 17:18:00.388   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 0
09-09 17:18:00.388   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-09 17:18:00.388   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f1f0 on port 0
,09-09 17:18:00.389   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-09 17:18:00.389   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-09 17:18:00.389   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 1
,09-09 17:18:00.389   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-09 17:18:00.389   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 1
09-09 17:18:00.389   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-09 17:18:00.389   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 1
,09-09 17:18:00.389   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-09 17:18:00.389   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 1
09-09 17:18:00.389   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 17:18:00.389   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-09 17:18:00.390   323  1369 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
,09-09 17:18:00.390   323  1369 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-09 17:18:00.390   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-09 17:18:00.390   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-09 17:18:00.390   323  7665 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-09 17:18:00.391   323  1369 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
,09-09 17:18:00.391   323  1369 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-09 17:18:00.391   323  1369 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-09 17:18:00.394   323  1369 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-09 17:18:00.395   323  1369 D AudioPlayer: AudioPlayer releasing audio source
09-09 17:18:00.395   323  1369 D AudioPlayer: AudioPlayer done releasing audio source
,09-09 17:18:00.395   323  1369 V AwesomePlayer: reset_l() 
09-09 17:18:00.396   323  1369 V AwesomePlayer: cancelPlayerEvents
09-09 17:18:00.396   323  1369 V AwesomePlayer: ~AwesomePlayer call
09-09 17:18:00.396   323  1369 V AwesomePlayer: reset_l() 
09-09 17:18:00.396   323  1369 V AwesomePlayer: cancelPlayerEvents
,09-09 17:18:00.396  7624  7661 V SoundPool: close(31)
09-09 17:18:00.396  7624  7661 V SoundPool: pointer = 0xa003a000, size = 205080, sampleRate = 48000, numChannels = 2
,09-09 17:18:00.417  7624  7624 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view,
09-09 17:18:00.418  7624  7624 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,09-09 17:18:00.421  7624  7624 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:8614
09-09 17:18:00.423  7624  7624 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-09 17:18:00.424  7525  7571 I UEI.SmartControl: ------ IControl API: 11
09-09 17:18:00.424  7525  7571 I UEI.SmartControl: Registering callback...
09-09 17:18:00.425  7525  7541 I UEI.SmartControl: ------ IControl API: 19
09-09 17:18:00.426  7525  7541 I UEI.SmartControl: Registering Services Ready callback...
,09-09 17:18:00.426  7525  7541 I UEI.SmartControl: Notify client services are ready...
09-09 17:18:00.426  7624  7640 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-09 17:18:00.427  7624  7659 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-09 17:18:00.428  7624  7659 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-09 17:18:00.428  7624  7624 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-09 17:18:00.429  7624  7624 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-09 17:18:00.429  7525  7540 I UEI.SmartControl: ------ IControl API: 8
09-09 17:18:00.431  7624  7624 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
,09-09 17:18:00.431  7624  7624 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true,
09-09 17:18:00.431  7624  7624 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-09 17:18:00.431  7624  7624 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-09 17:18:00.432  7624  7624 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-09 17:18:00.433  7624  7624 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-09 17:18:00.435  7624  7624 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-09 17:18:00.436  7624  7624 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-09 17:18:00.437  7624  7624 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-09 17:18:00.438  7624  7624 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-09 17:18:00.438  7624  7624 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-09 17:18:00.439  7624  7624 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-09 17:18:00.440  7624  7624 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-09 17:18:00.441  7624  7624 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
,09-09 17:18:00.442  7624  7624 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473434280441]
09-09 17:18:00.443  7624  7624 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,09-09 17:18:00.452  1036  2075 I ActivityManager: Killing 6734:com.lge.sync/1000 (adj 15): empty #17
09-09 17:18:00.479  1036  1531 D WifiService: Client connection lost with reason: 4
,09-09 17:18:00.487  7624  7667 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
09-09 17:18:00.498  1036  1768 W libprocessgroup: failed to open /acct/uid_1000/pid_6734/cgroup.procs: No such file or directory
,09-09 17:18:00.504  7624  7624 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,09-09 17:18:00.505  7624  7624 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-09 17:18:00.506  7624  7624 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-09 17:18:00.507  7624  7624 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-09 17:18:00.507  7624  7624 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-09 17:18:00.508  7624  7624 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-09 17:18:00.508  7624  7624 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-09 17:18:00.522  7624  7624 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-09 17:18:01.178  6571  6647 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 17:18:01.179  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:18:01.272  1589  1589 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-09 17:18:01.337  1036  1412 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-09 17:18:01.385  1036  1103 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7677 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-09 17:18:01.391  1589  1589 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-09 17:18:01.392  1589  1589 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
09-09 17:18:01.403  1036  1036 D administrator: Handling package changes for user 0
,09-09 17:18:01.423  2082  2082 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-09 17:18:01.452  2082  2082 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-09 17:18:01.481  7677  7677 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-09 17:18:01.538  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-09 17:18:01.538  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-09 17:18:01.542  7677  7677 D LgDataFeature: LgDataFeature() Constructor: none
09-09 17:18:01.542  7677  7677 D LgDataFeature: LgDataFeature() Constructor Done, null
09-09 17:18:01.593  1036  1101 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 17:18:01.598  1036  1101 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,09-09 17:18:01.605  2082  2082 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-09 17:18:01.606  2491  2491 V GmsNetworkLocationProvi: DISABLE
,09-09 17:18:01.638  1036  1101 D LocationProviderProxy: applying state to connected service
09-09 17:18:01.639  2491  2491 E GCoreFlp: Bound FusedProviderService with LocationManager
,09-09 17:18:01.670  7677  7722 I Babel   : MmsConfig: mnc/mcc: 0/0
09-09 17:18:01.670  7677  7722 I Babel   : MmsConfig.loadMmsSettings
09-09 17:18:01.674  7677  7722 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-09 17:18:01.675  7677  7722 I Babel   : MmsConfig.loadFromDatabase
,09-09 17:18:01.685  7677  7677 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 17:18:01.695  7677  7722 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-09 17:18:01.695  7677  7722 I Babel   : MmsConfig.loadFromResources
09-09 17:18:01.696  7677  7722 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-09 17:18:01.697  7677  7722 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-09 17:18:01.699  7677  7720 W AudioCapabilities: Unsupported mime audio/evrc
09-09 17:18:01.702  7677  7720 W AudioCapabilities: Unsupported mime audio/qcelp
09-09 17:18:01.704  7677  7720 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 17:18:01.711  1829  7725 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-09 17:18:01.712  1829  7725 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
09-09 17:18:01.712  6945  6945 I AppUp4:CustModeStarterReceiver: onReceive
,09-09 17:18:01.720  6945  6945 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@7f005e4
09-09 17:18:01.721  6945  6945 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 17:18:01.721  6945  6945 D AppUp4:CustFacade: isPhone : true
09-09 17:18:01.722  6945  6945 D AppUp4:CustModeStarterReceiver: begin check event
09-09 17:18:01.722  6945  6945 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-09 17:18:01.731  7677  7720 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,09-09 17:18:01.733  7677  7720 W AudioCapabilities: Unsupported mime audio/qcelp
09-09 17:18:01.733  7677  7720 W AudioCapabilities: Unsupported mime audio/evrc
09-09 17:18:01.739  7677  7720 W VideoCapabilities: Unsupported mime video/x-ms-wmv
09-09 17:18:01.741  7677  7720 W VideoCapabilities: Unsupported mime video/divx
09-09 17:18:01.742  7677  7720 W VideoCapabilities: Unsupported mime video/divx311
09-09 17:18:01.743  7677  7720 W VideoCapabilities: Unsupported mime video/divx4
,09-09 17:18:01.747  7677  7720 W VideoCapabilities: Unsupported mime video/mp4v-esdp
09-09 17:18:01.756  7677  7720 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-09 17:18:01.760  7677  7720 W AudioCapabilities: Unsupported mime audio/eac3
09-09 17:18:01.760  1036  2310 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7729 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-09 17:18:01.762  7677  7720 W AudioCapabilities: Unsupported mime audio/ac3
09-09 17:18:01.764  7677  7720 W AudioCapabilities: Unsupported mime audio/g726
09-09 17:18:01.765  1036  1994 I ActivityManager: Killing 6975:com.lge.email/u0a23 (adj 15): empty #17
09-09 17:18:01.766  1829  4790 I Icing   : updateResources: need to parse e{com.google.android.gms}
09-09 17:18:01.767  7677  7720 W AudioCapabilities: Unsupported mime audio/wma-voice
09-09 17:18:01.767  7677  7720 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-09 17:18:01.768  7677  7720 W AudioCapabilities: Unsupported mime audio/adpcm
,09-09 17:18:01.770  7677  7720 W VideoCapabilities: Unsupported mime video/theora
09-09 17:18:01.771  7677  7720 W VideoCapabilities: Unsupported mime video/mjpg
09-09 17:18:01.981  1036  1978 W libprocessgroup: failed to open /acct/uid_10023/pid_6975/cgroup.procs: No such file or directory
,09-09 17:18:02.015  7729  7729 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 17:18:02.016  7729  7729 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 17:18:02.016  7729  7729 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,09-09 17:18:02.017  7729  7729 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-09 17:18:02.017  7729  7729 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 17:18:02.081  7729  7729 I SystemConfig: BUILD Country: EU
09-09 17:18:02.081  7729  7729 I SystemConfig: BUILD Operator: OPEN
,09-09 17:18:02.136  1036  1768 I ActivityManager: Killing 6836:com.lge.formmanager/u0a26 (adj 15): empty #17
,09-09 17:18:02.220  1036  2310 W libprocessgroup: failed to open /acct/uid_10026/pid_6836/cgroup.procs: No such file or directory
,09-09 17:18:02.287  1036  1768 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7752 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-09 17:18:02.295  7729  7750 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-09 17:18:02.295  7729  7750 I SystemConfig: existFile = false
09-09 17:18:02.295  7729  7750 I SystemConfig: canReadFile = false
09-09 17:18:02.295  7729  7750 I SystemConfig: systemFeature RCS result false
09-09 17:18:02.295  7729  7750 D SystemConfig: refreshRcsSupport() :false
,09-09 17:18:02.370  7752  7752 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 17:18:02.370  7752  7752 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-09 17:18:02.370  7752  7752 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,09-09 17:18:02.371  7752  7752 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-09 17:18:02.492  7752  7752 I AppConfig: Total System Memory = 2995761152
,09-09 17:18:02.505  7752  7752 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-09 17:18:02.587  1036  1952 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7774 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 17:18:02.589  1036  1952 I ActivityManager: Killing 6363:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,09-09 17:18:02.715  1036  1052 W libprocessgroup: failed to open /acct/uid_1000/pid_6363/cgroup.procs: No such file or directory
09-09 17:18:02.885  7774  7774 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-09 17:18:02.942  7774  7774 D LgDataFeature: LgDataFeature() Constructor: none
09-09 17:18:02.942  7774  7774 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 17:18:02.978  7774  7774 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-09 17:18:02.993  7774  7774 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-09 17:18:02.993  7774  7774 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-09 17:18:03.018  7774  7774 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-09 17:18:03.019  7774  7774 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
09-09 17:18:03.032  1036  1051 I ActivityManager: Killing 7010:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,09-09 17:18:03.050  1036  2075 W libprocessgroup: failed to open /acct/uid_10046/pid_7010/cgroup.procs: No such file or directory
,09-09 17:18:03.052  3413  3432 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-09 17:18:03.053  3413  3432 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3ef7c8 on behalf of 7774
09-09 17:18:03.058  4596  7811 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
09-09 17:18:03.091  1036  1052 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7813 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-09 17:18:03.103  7774  7774 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
09-09 17:18:03.122  7774  7774 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-09 17:18:03.167  7813  7813 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-09 17:18:03.200  7813  7813 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,09-09 17:18:03.200  7813  7813 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-09 17:18:03.200  7813  7813 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-09 17:18:03.200  7813  7813 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-09 17:18:03.200  7813  7813 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-09 17:18:03.200  7813  7813 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
09-09 17:18:03.218  1036  1990 I ActivityManager: Killing 7036:com.android.chrome/u0a57 (adj 15): empty #17
,09-09 17:18:03.249  1036  1562 W libprocessgroup: failed to open /acct/uid_10057/pid_7036/cgroup.procs: No such file or directory
,09-09 17:18:03.409  7525  7566 D UEI.SmartControl: Internal timer expired: 1
09-09 17:18:03.409  7525  7566 D UEI.SmartControl: unbind internal service
,09-09 17:18:03.463  1036  1704 V SIM_STK : Menu title from STK is T-Mobile
,09-09 17:18:03.506  4596  7811 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 448 ms] updated apps [took 448 ms] 
,09-09 17:18:03.671  7525  7563 D serial_port: close(fd = 25)
,09-09 17:18:03.682  7525  7563 I UEI.SmartControl: Serial port is closed.
,09-09 17:18:04.202  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 17:18:04.202  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@17c7972d added. We now have 6 listener(s)
09-09 17:18:04.203  6571  6647 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:18:04.228  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:04.228  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9d94462 added. We now have 7 listener(s)
09-09 17:18:04.228  6571  6647 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:18:04.232  6571  6647 I System.out: IsBluetoothEnabled
,09-09 17:18:04.233  1036  1768 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:18:04.233  1036  1768 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
09-09 17:18:04.234  1036  1118 D BluetoothManagerService: Message: 2
09-09 17:18:04.250  6571  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:04.254  1036  2081 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:18:04.254  1036  2081 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-09 17:18:04.272  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 17:18:04.272  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 17:18:04.273  1036  1036 D Ulp_jni : JNI:system_update. Event-4
09-09 17:18:04.273  1036  1118 D BluetoothManagerService: Message: 1
09-09 17:18:04.273  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-09 17:18:04.304  1036  1118 D BluetoothManagerService: Message: 20
09-09 17:18:04.304  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b3e8734:true
,09-09 17:18:04.307  7596  7596 D BluetoothAdapterState: make
09-09 17:18:04.312  7596  7596 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-09 17:18:04.312  7596  7596 I bluedroid-qcom: init
09-09 17:18:04.313  7596  7847 I BluetoothAdapterState: Entering OffState
09-09 17:18:04.313  7596  7596 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-09 17:18:04.314  7596  7596 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-09 17:18:04.314  7596  7596 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-09 17:18:04.314  7596  7596 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-09 17:18:04.314  7596  7596 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-09 17:18:04.316  7596  7596 I bluedroid-qcom: get_profile_interface socket
09-09 17:18:04.316  7596  7596 I bluedroid-qcom: get_profile_interface map_client
,09-09 17:18:04.319  7596  7851 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-09 17:18:04.322  7596  7851 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-09 17:18:04.314  7850  7850 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:18:04.314  7850  7850 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:18:04.330  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-09 17:18:04.330  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
,09-09 17:18:04.338  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-09 17:18:04.339  1036  1118 D BluetoothManagerService: Message: 40
09-09 17:18:04.339  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-09 17:18:04.340  7596  7612 I bluedroid-qcom: config_hci_snoop_log
09-09 17:18:04.342  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-09 17:18:04.342  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,09-09 17:18:04.344  7850  7850 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
,09-09 17:18:04.344  7850  7850 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-09 17:18:04.344  7850  7850 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-09 17:18:04.345  7596  7851 D BluetoothAdapterProperties: Name is: G3
09-09 17:18:04.357  7850  7850 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-09 17:18:04.358  7596  7847 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-09 17:18:04.358  7596  7847 D BluetoothAdapterProperties: Setting state to 11
,09-09 17:18:04.363  7596  7847 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-09 17:18:04.365  1036  1118 D BluetoothManagerService: Message: 60
09-09 17:18:04.365  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-09 17:18:04.365  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-09 17:18:04.367  7850  7850 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-09 17:18:04.367  7850  7850 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-09 17:18:04.367  1959  1959 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:18:04.368  7596  7847 I LGBluetoothServiceJni: classInitNative: succeeds
09-09 17:18:04.370  6751  6751 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-09 17:18:04.372  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-09 17:18:04.372  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:04.379  7596  7847 D BluetoothBondStateMachine: make
09-09 17:18:04.381  7596  7596 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 17:18:04.381  7596  7596 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:18:04.382  7596  7596 V BluetoothPbapReceiver: ***********state = 11
09-09 17:18:04.383  7596  7847 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285fc213
09-09 17:18:04.384  7596  7867 I BluetoothBondStateMachine: StableState(): Entering Off State
09-09 17:18:04.384  7596  7847 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-09 17:18:04.384  7596  7847 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285fc213
09-09 17:18:04.384  7596  7847 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-09 17:18:04.384  7596  7847 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-09 17:18:04.385  2229  2229 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 17:18:04.390  7596  7847 E BluetoothAdapterService: File transfer profiles supported!!
09-09 17:18:04.397  6751  6751 D BluetoothPermissionRequest: onReceive
,09-09 17:18:04.401  6751  6751 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-09 17:18:04.401  7596  7596 D HeadsetService: Received start request. Starting profile...
09-09 17:18:04.402  7596  7596 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 17:18:04.402  7596  7847 E BluetoothAdapterService: File transfer profiles supported!!
09-09 17:18:04.402  7596  7596 D LGBluetoothHfpAdapter: Version 1.6
09-09 17:18:04.405  7596  7596 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-09 17:18:04.405  7596  7596 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 17:18:04.406  7596  7596 D HeadsetStateMachine: make
09-09 17:18:04.409  7596  7847 E BluetoothAdapterService: File transfer profiles supported!!
,09-09 17:18:04.417  7596  7847 E BluetoothAdapterService: File transfer profiles supported!!
09-09 17:18:04.422  7596  7847 E BluetoothAdapterService: File transfer profiles supported!!
,09-09 17:18:04.426  7596  7596 D LgDataFeature: LgDataFeature() Constructor: none
09-09 17:18:04.426  7596  7596 D LgDataFeature: LgDataFeature() Constructor Done, null
09-09 17:18:04.427  7596  7847 E BluetoothAdapterService: File transfer profiles supported!!
09-09 17:18:04.434  7596  7596 D HeadsetStateMachine: max_hf_connections = 1
09-09 17:18:04.434  7596  7596 I bluedroid-qcom: get_profile_interface handsfree
,09-09 17:18:04.435  7596  7596 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-09 17:18:04.436  7596  7847 E BluetoothAdapterService: File transfer profiles supported!!
09-09 17:18:04.436   323  1369 V AudioPolicyService: registerClient() client 0xb0410340, uid 1002
09-09 17:18:04.436   323   323 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-09 17:18:04.436   323   323 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-09 17:18:04.436   323   323 V AudioPolicyManagerEx: getOutput() returns output 2
09-09 17:18:04.436  7596  7596 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-09 17:18:04.437   323  1368 V AudioFlinger: registerClient() client 0xb5581568, pid 7596
09-09 17:18:04.438   323  1363 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 17:18:04.438   323  1363 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 17:18:04.439   323  1364 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 17:18:04.439  1589  1607 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 17:18:04.439  1589  1607 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 17:18:04.439   323  1364 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 17:18:04.439  1864  3461 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 17:18:04.439  1864  3461 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 17:18:04.439  1036  2075 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 17:18:04.439  1036  2075 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 17:18:04.439  3297  3317 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 17:18:04.439  3297  3317 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 17:18:04.439  7596  7612 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 17:18:04.439  7596  7612 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
,09-09 17:18:04.439  1036  1768 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 17:18:04.439  1036  1768 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 17:18:04.439  1589  3154 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 17:18:04.439  1589  3154 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 17:18:04.439  1864  2439 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 17:18:04.439  1864  2439 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 17:18:04.440  3297  3318 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 17:18:04.440  3297  3318 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 17:18:04.440  7596  7612 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 17:18:04.440  7596  7612 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-09 17:18:04.440  7596  7596 V ToneGenerator: Create Track: 0xb4928a80
09-09 17:18:04.440  7596  7596 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-09 17:18:04.440  7596  7596 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-09 17:18:04.440   323  1369 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-09 17:18:04.440   323  1369 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-09 17:18:04.440   323  1369 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-09 17:18:04.440   323  1369 V AudioPolicyManagerEx: getOutput() returns output 2
09-09 17:18:04.440   323   323 I AudioFlinger: isAudioPlaybackHookOn() false
09-09 17:18:04.440   323  1368 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-09 17:18:04.440   323  1368 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-09 17:18:04.440   323  1368 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-09 17:18:04.440   323  1368 V AudioPolicyManagerEx: getOutput() returns output 2
09-09 17:18:04.440  7596  7596 V AudioSystem: getLatency() output 2, latency 50
09-09 17:18:04.440  7596  7596 V AudioSystem: getFrameCount() output 2, frameCount 960
09-09 17:18:04.440  7596  7596 V AudioTrack: createTrack_l() output 2 afLatency 50
09-09 17:18:04.441   323  2998 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-09 17:18:04.441   323  2998 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-09 17:18:04.441   323  2998 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-09 17:18:04.441   323  2998 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-09 17:18:04.441   323  2998 V AudioFlinger: createTrack() lSessionId: 23
09-09 17:18:04.441  7596  7596 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-09 17:18:04.441   323  1369 V AudioFlinger: acquiring 23 from 7596, for 7596
09-09 17:18:04.441   323  1369 V AudioFlinger:  added new entry for 23
09-09 17:18:04.441  7596  7596 V ToneGenerator: ToneGenerator INIT OK, time: 135775
09-09 17:18:04.441  7596  7596 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285fc213
09-09 17:18:04.442  7596  7868 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-09 17:18:04.442  7596  7868 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 17:18:04.443  7596  7868 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 17:18:04.443  7596  7596 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285fc213
09-09 17:18:04.443  7596  7868 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is di,sconnected
09-09 17:18:04.443   323   323 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7596
09-09 17:18:04.444   323   323 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-09 17:18:04.444   323   323 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-09 17:18:04.444   323   323 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-09 17:18:04.444   323   323 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-09 17:18:04.444   323   323 V voice   : voice_set_parameters: exit with code(0)
09-09 17:18:04.444   323   323 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-09 17:18:04.444   323   323 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-09 17:18:04.445   323   323 V msm8974_platform: platform_set_parameters: exit with code(0)
09-09 17:18:04.445   323   323 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-09 17:18:04.445   323   323 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-09 17:18:04.445   323   323 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-09 17:18:04.445  7596  7868 V ToneGenerator: ToneGenerator destructor
09-09 17:18:04.445  7596  7868 V ToneGenerator: stopTone
09-09 17:18:04.445  7596  7868 V ToneGenerator: Delete Track: 0xb4928a80
,09-09 17:18:04.446  7596  7596 D A2dpService: Received start request. Starting profile...
09-09 17:18:04.446  7596  7596 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-09 17:18:04.447  7596  7596 V Avrcp   : make
09-09 17:18:04.448  7596  7596 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-09 17:18:04.448  7596  7596 I bluedroid-qcom: get_profile_interface avrcp
09-09 17:18:04.450  1036  1910 W Process : Unable to open /proc/7870/status
09-09 17:18:04.450   323  1368 V AudioPolicyService: AudioCommandThread() adding release output 2
09-09 17:18:04.450   323  1368 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-09 17:18:04.450   323  1273 V AudioPolicyService: AudioCommandThread() waking up
09-09 17:18:04.450   323  1273 V AudioPolicyService: AudioCommandThread() processing release output 2
09-09 17:18:04.450   323  1273 V AudioPolicyManager: releaseOutput() 2
09-09 17:18:04.450   323  1273 V AudioPolicyService: AudioCommandThread() going to sleep
09-09 17:18:04.450   323  1368 V AudioFlinger: PlaybackThread::Track destructor
09-09 17:18:04.450   323  1368 V AudioFlinger: removeClient_l() pid 7596, calling pid 323
09-09 17:18:04.451  7596  7868 V AudioTrack: ~AudioTrack, releasing session id from 7596 on behalf of 7596
09-09 17:18:04.452   323  1369 V AudioFlinger: releasing 23 from 7596 for 7596
09-09 17:18:04.452   323  1369 V AudioFlinger:  decremented refcount to 0
09-09 17:18:04.452   323  1369 V AudioFlinger: purging stale effects
09-09 17:18:04.455  7596  7847 V LGMDMManager: Create singleton instance
09-09 17:18:04.456  7596  7847 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-09 17:18:04.464  7596  7596 V AudioManager: registerRemoteController: size of Media player list: 0
,09-09 17:18:04.466  7596  7596 E AudioManager: No RCC entry present to update
09-09 17:18:04.466  7596  7596 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-09 17:18:04.470  7596  7596 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-09 17:18:04.472  7596  7596 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-09 17:18:04.472  7596  7596 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-09 17:18:04.476  7596  7596 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-09 17:18:04.606  1036  2081 V SIM_STK : Menu title from STK is T-Mobile
09-09 17:18:04.606  1036  2081 V SIM_STK : Menu title from STK is T-Mobile
,09-09 17:18:04.752  1036  2075 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-09 17:18:04.774  7596  7596 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,09-09 17:18:04.792  7596  7596 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-09 17:18:04.793  7596  7596 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-09 17:18:04.793  7596  7596 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-09 17:18:04.793  7596  7596 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-09 17:18:04.793  7596  7596 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 17:18:04.793  7596  7596 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-09 17:18:04.793  7596  7596 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-09 17:18:04.793  7596  7596 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-09 17:18:04.793  7596  7596 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 17:18:04.794  7596  7596 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-09 17:18:04.794  7596  7596 I BluetoothA2dpServiceJni: classInitNative
09-09 17:18:04.794  7596  7596 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 17:18:04.794  7596  7596 D A2dpStateMachine: make
,09-09 17:18:04.798  7596  7596 I bluedroid-qcom: get_profile_interface a2dp
09-09 17:18:04.798  7596  7882 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-09 17:18:04.801  7596  7596 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-09 17:18:04.801  7596  7596 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-09 17:18:04.803  7596  7596 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285fc213
09-09 17:18:04.803  7596  7881 D A2dpStateMachine: Enter Disconnected: -2
09-09 17:18:04.804  7596  7596 I BluetoothHidServiceJni: classInitNative: succeeds
09-09 17:18:04.807  7596  7596 D HidService: Received start request. Starting profile...
09-09 17:18:04.807  7596  7596 I bluedroid-qcom: get_profile_interface hidhost
09-09 17:18:04.807  7596  7596 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285fc213
09-09 17:18:04.808  7596  7596 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-09 17:18:04.814  7596  7596 D HealthService: Received start request. Starting profile...
09-09 17:18:04.817  7596  7596 I bluedroid-qcom: get_profile_interface health
09-09 17:18:04.817  7596  7596 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-09 17:18:04.817  7596  7596 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285fc213
09-09 17:18:04.819  7596  7596 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-09 17:18:04.821  7596  7596 D PanService: Received start request. Starting profile...
09-09 17:18:04.821  7596  7596 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 17:18:04.821  7596  7596 I bluedroid-qcom: get_profile_interface pan
,09-09 17:18:04.829  7596  7596 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,09-09 17:18:04.829  7596  7596 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285fc213
09-09 17:18:04.831  7596  7596 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-09 17:18:04.838  7596  7596 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 17:18:04.838  7596  7596 D BtGatt.GattService: Received start request. Starting profile...
09-09 17:18:04.838  7596  7596 D BtGatt.GattService: start()
09-09 17:18:04.838  7596  7596 I bluedroid-qcom: get_profile_interface gatt
09-09 17:18:04.839  7596  7596 D BtGatt.AdvertiseManager: advertise manager created
,09-09 17:18:04.848  7596  7596 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285fc213
,09-09 17:18:04.849  7596  7596 D HeadsetStateMachine: Proxy object connected
09-09 17:18:04.850  7596  7596 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-09 17:18:04.850  7596  7596 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-09 17:18:04.856  7596  7596 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 17:18:04.858  7596  7596 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285fc213
09-09 17:18:04.858  7596  7596 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
,09-09 17:18:04.860  7596  7596 V BluetoothMapService: BluetoothMapBinder()
,09-09 17:18:04.861  7596  7596 D BluetoothMapService: Received start request. Starting profile...
09-09 17:18:04.861  7596  7596 D BluetoothMapService: start()
09-09 17:18:04.866  7596  7596 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-09 17:18:04.866  7596  7596 D BluetoothMapEmailAppObserver: createReceiver()
09-09 17:18:04.867  7596  7596 D BluetoothMapEmailAppObserver: initObservers()
09-09 17:18:04.868  7596  7596 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-09 17:18:04.877  7596  7596 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285fc213
09-09 17:18:04.878  7596  7868 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-09 17:18:04.879  7596  7868 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
09-09 17:18:04.879  7596  7868 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,09-09 17:18:04.881  7596  7596 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:18:04.888  7596  7596 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 17:18:04.893  7596  7596 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-09 17:18:04.898  7596  7596 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 17:18:04.898  7596  7596 V PanService: [BTUI] SIM Extra State :ABSENT
09-09 17:18:04.902  7596  7596 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 17:18:04.906  7596  7596 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-09 17:18:04.906  7596  7596 V BluetoothMapService: Handler(): got msg=1
,09-09 17:18:04.909  7596  7847 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-09 17:18:04.909  7596  7847 I bluedroid-qcom: enable
09-09 17:18:04.909  7596  7847 I bt_hci_bdroid: init
09-09 17:18:04.909  7596  7596 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 17:18:04.910  7596  7596 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 17:18:04.910  7596  7596 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 17:18:04.910  7596  7596 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:18:04.910  7596  7596 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-09 17:18:04.911  7596  7889 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-09 17:18:04.912  7596  7889 I bt-btu  : btu_task pending for preload complete event
09-09 17:18:04.913  7596  7847 I bt_vendor: bt-vendor : init
09-09 17:18:04.913  7596  7847 I bt_vendor: bt-vendor : get_bt_soc_type
09-09 17:18:04.913  7596  7847 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-09 17:18:04.913  7596  7847 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-09 17:18:04.914  7596  7847 D bt_userial_mct: userial_init
09-09 17:18:04.915  7596  7847 D bt_hci_bdroid: set_power 1
09-09 17:18:04.915  7596  7847 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-09 17:18:04.915  7596  7847 I bt_vendor: Starting hciattach daemon
09-09 17:18:04.915  7596  7847 I bt_vendor: try to set true
09-09 17:18:04.914  7892  7892 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-09 17:18:04.914  7892  7892 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-09 17:18:04.946  7893  7893 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-09 17:18:05.023  7899  7899 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-09 17:18:05.036  7900  7900 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-09 17:18:05.062  7902  7902 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-09 17:18:05.075  7903  7903 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-09 17:18:05.087  7904  7904 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-09 17:18:05.099  7905  7905 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-09 17:18:05.120  7907  7907 I libmdmdetect: ESOC framework not supported
,09-09 17:18:05.121  7907  7907 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-09 17:18:05.130  7907  7907 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,09-09 17:18:05.130  7907  7907 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-09 17:18:05.130  7907  7907 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-09 17:18:05.130  7907  7907 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-09 17:18:05.130  7907  7907 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-09 17:18:05.130  7907  7907 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-09 17:18:05.130  7907  7907 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-09 17:18:05.166  7907  7908 E QC-QMI  : qmi_client [7907] 15: failed to locate client data
09-09 17:18:05.167   469   469 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-09 17:18:05.167   469   469 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,09-09 17:18:05.202  7909  7909 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-09 17:18:05.214  7910  7910 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-09 17:18:05.269  7596  7847 I bt_vendor: bluetooth satus is on
09-09 17:18:05.270  7596  7847 D bt_hci_bdroid: preload
09-09 17:18:05.270  7596  7891 D bt_userial_mct: userial_open(port:0)
09-09 17:18:05.270  7596  7891 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-09 17:18:05.274  7596  7891 I bt_vendor: Done intiailizing UART
,09-09 17:18:05.279  7596  7891 I bt_vendor: Done intiailizing UART
,09-09 17:18:05.279  7596  7891 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,09-09 17:18:05.280  7596  7891 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-09 17:18:05.280  7596  7889 I bt-btu  : btu_task received preload complete event
,09-09 17:18:05.282  7596  7889 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-09 17:18:05.282  7596  7889 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-09 17:18:05.287  7596  7912 D bt_userial_mct: Entering userial_read_thread()
09-09 17:18:05.289  7596  7889 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,09-09 17:18:05.301  7596  7889 I         : BTE_InitTraceLevels -- TRC_HCI
,09-09 17:18:05.301  7596  7889 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 17:18:05.301  7596  7889 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-09 17:18:05.301  7596  7889 I         : BTE_InitTraceLevels -- TRC_AVDT
09-09 17:18:05.301  7596  7889 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 17:18:05.301  7596  7889 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 17:18:05.301  7596  7889 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 17:18:05.301  7596  7889 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 17:18:05.301  7596  7889 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-09 17:18:05.301  7596  7889 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 17:18:05.301  7596  7889 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 17:18:05.302  7596  7889 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 17:18:05.302  7596  7889 I         : BTE_InitTraceLevels -- TRC_GATT
09-09 17:18:05.302  7596  7889 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 17:18:05.302  7596  7889 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 17:18:05.302  7596  7889 I         : BTE_InitTraceLevels -- TRC_BTIF
09-09 17:18:05.359  7596  7889 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-09 17:18:05.359  7596  7889 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0248061 
09-09 17:18:05.359  7596  7889 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0248061 
,09-09 17:18:05.392  7596  7851 E bt-btif : Calling BTA_HhEnable
09-09 17:18:05.392  7596  7851 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,09-09 17:18:05.393  7596  7851 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-09 17:18:05.396  7596  7851 D BluetoothAdapterProperties: Name is: G3
,09-09 17:18:05.396  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-09 17:18:05.397  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
09-09 17:18:05.398  7596  7851 D BluetoothAdapterProperties: Scan Mode:20
,09-09 17:18:05.398  7596  7851 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 17:18:05.398  7596  7851 D bt_hci_bdroid: postload
09-09 17:18:05.399  7596  7851 D bte_conf: Device ID record 1 : primary
09-09 17:18:05.400  7596  7851 D bte_conf:   vendorId            = 00c4
09-09 17:18:05.400  7596  7851 D bte_conf:   vendorIdSource      = 0001
09-09 17:18:05.400  7596  7851 D bte_conf:   product             = 13a1
09-09 17:18:05.400  7596  7851 D bte_conf:   version             = 1000
09-09 17:18:05.400  7596  7851 D bte_conf:   clientExecutableURL = 
09-09 17:18:05.400  7596  7851 D bte_conf:   serviceDescription  = 
09-09 17:18:05.400  7596  7851 D bte_conf:   documentationURL    = 
09-09 17:18:05.400  7596  7891 D bt_hci_bdroid: Used up Tx Cmd credits
09-09 17:18:05.400  7596  7851 D bte_conf: bte_load_did_conf no section named DID2.
09-09 17:18:05.403  7596  7891 D bt_hci_bdroid: Used up Tx Cmd credits
09-09 17:18:05.411  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:05.404  7914  7914 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:18:05.404  7914  7914 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-09 17:18:05.424  7596  7912 E bt_mct  : hci lib postload completed
09-09 17:18:05.425  7596  7847 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-09 17:18:05.426  7596  7847 D BluetoothAdapterProperties: ScanMode =  20
09-09 17:18:05.429  7596  7847 D BluetoothAdapterProperties: State =  11
09-09 17:18:05.429  7596  7847 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-09 17:18:05.429  7596  7847 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-09 17:18:05.430  7596  7847 D BluetoothAdapterProperties: Setting state to 12
09-09 17:18:05.430  7596  7847 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 17:18:05.430  7596  7851 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-09 17:18:05.432  1036  1118 D BluetoothManagerService: Message: 60
09-09 17:18:05.432  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-09 17:18:05.432  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,09-09 17:18:05.435  7596  7847 I BluetoothAdapterState: Entering On State
09-09 17:18:05.440  7596  7847 D LGBluetoothServiceAdapter: [BTUI] OnState
09-09 17:18:05.440  7596  7847 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-09 17:18:05.440  7596  7847 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-09 17:18:05.442  7596  7847 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-09 17:18:05.442  6751  6767 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:18:05.444  7596  7851 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 17:18:05.444  7596  7851 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-09 17:18:05.448  6751  6767 D BluetoothPan: onBluetoothStateChange on: true
,09-09 17:18:05.448  6751  6767 D BluetoothPan: onBluetoothStateChange call bindService
09-09 17:18:05.453  6751  7260 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 17:18:05.454  7596  7889 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-09 17:18:05.454  7596  7889 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-09 17:18:05.454  7596  7889 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-09 17:18:05.454  7596  7889 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-09 17:18:05.454  7596  7889 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-09 17:18:05.454  7596  7889 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-09 17:18:05.457  7596  7851 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-09 17:18:05.460  6751  6767 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 17:18:05.464  1864  1880 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 17:18:05.469  7596  7889 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 17:18:05.469  7596  7889 W bt-smp  : Plain text(LSB ~ MSB) = 22 59 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 17:18:05.469  7596  7889 W bt-smp  : Encrypted text(LSB ~ MSB) = 77 41 43 79 da 3a 34 68 e2 8f 9c 1b e9 73 5a 12 
09-09 17:18:05.469  7596  7889 W bt-btm  : Stopping oneshot timer
09-09 17:18:05.459  6751  6751 D BluetoothHeadset: Proxy object connected
09-09 17:18:05.469  6751  6751 D HeadsetProfile: Bluetooth service connected
09-09 17:18:05.477  1864  1864 D BluetoothHeadset: Proxy object connected
09-09 17:18:05.478  6751  7260 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 17:18:05.481  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:18:05.482  6751  6751 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 17:18:05.482  6751  6751 D PanProfile: Bluetooth service connected
09-09 17:18:05.482  1036  1036 D BluetoothHeadset: Proxy object connected
09-09 17:18:05.485  7596  7847 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-09 17:18:05.486  1864  2439 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:18:05.488  1864  1864 D BluetoothHeadset: Proxy object connected
09-09 17:18:05.488  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 17:18:05.489  6751  6751 D BluetoothInputDevice: Proxy object connected
09-09 17:18:05.489  6751  6751 D HidProfile: Bluetooth service connected
09-09 17:18:05.489  1036  1036 D BluetoothA2dp: Proxy object connected
,09-09 17:18:05.491  7928  7928 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-09 17:18:05.491  1864  3461 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 17:18:05.494  1864  1864 D BluetoothHeadset: Proxy object connected
09-09 17:18:05.494  6751  6767 D BluetoothMap: onBluetoothStateChange: up=true
09-09 17:18:05.495  7596  7889 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 17:18:05.495  7596  7889 W bt-smp  : Plain text(LSB ~ MSB) = 86 16 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 17:18:05.495  7596  7889 W bt-smp  : Encrypted text(LSB ~ MSB) = f6 9b 5b 2e 30 b9 67 81 61 cc cd a2 3c 24 04 da 
09-09 17:18:05.495  7596  7889 W bt-btm  : Stopping oneshot timer
09-09 17:18:05.495  6751  6751 D BluetoothA2dp: Proxy object connected
09-09 17:18:05.495  6751  6751 D A2dpProfile: Bluetooth service connected
09-09 17:18:05.497  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-09 17:18:05.497  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,09-09 17:18:05.498  6751  6751 D BluetoothMap: Proxy object connected
09-09 17:18:05.498  6751  6751 D MapProfile: Bluetooth service connected
09-09 17:18:05.498  6751  6751 D BluetoothMap: getConnectedDevices()
09-09 17:18:05.499  1959  1959 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:18:05.499  1959  2186 D LGBluetoothAPIService: Message: 1
09-09 17:18:05.499  1959  2186 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-09 17:18:05.499  1959  2186 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
09-09 17:18:05.499  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 17:18:05.499  1959  2186 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-09 17:18:05.500  7596  7612 V BluetoothMapService: getConnectedDevices()
09-09 17:18:05.504  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-09 17:18:05.505  1036  1118 D BluetoothManagerService: Message: 40
09-09 17:18:05.505  7596  7889 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 17:18:05.505  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-09 17:18:05.505  7596  7889 W bt-smp  : Plain text(LSB ~ MSB) = 77 5e 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 17:18:05.505  7596  7889 W bt-smp  : Encrypted text(LSB ~ MSB) = 77 b7 d6 13 d0 c6 32 85 ed ba 02 03 c1 1f 8d 6a 
09-09 17:18:05.505  7596  7889 W bt-btm  : Stopping oneshot timer
,09-09 17:18:05.510  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:05.510  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:05.510  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:18:05.510  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:18:05.510  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:05.510  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:05.510  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:05.510  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:18:05.510  7596  7596 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:18:05.510  7596  7596 D BluetoothMapService: STATE_ON
09-09 17:18:05.512  6571  6571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:18:05.513  6751  6751 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-09 17:18:05.514  7596  7889 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 17:18:05.514  7596  7889 W bt-smp  : Plain text(LSB ~ MSB) = d1 b0 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 17:18:05.514  7596  7889 W bt-smp  : Encrypted text(LSB ~ MSB) = 8e 2d 1c a3 31 43 d5 9b 16 d2 22 97 67 9d f8 db 
09-09 17:18:05.514  7596  7889 W bt-btm  : Stopping oneshot timer
09-09 17:18:05.523  7596  7889 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 17:18:05.523  7596  7889 W bt-smp  : Plain text(LSB ~ MSB) = 23 ee 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 17:18:05.523  7596  7889 W bt-smp  : Encrypted text(LSB ~ MSB) = 1e f6 6d 81 37 31 3b 55 38 0f 7e 99 2a d9 e8 49 
09-09 17:18:05.523  7596  7889 W bt-btm  : Stopping oneshot timer
,09-09 17:18:05.525  7596  7596 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285fc213
09-09 17:18:05.525  7596  7596 V BluetoothPbapService: Pbap Service onCreate
09-09 17:18:05.525  7596  7596 V BluetoothPbapService: Starting PBAP service
09-09 17:18:05.527  7596  7596 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-09 17:18:05.528  7596  7596 V BluetoothMapService: Handler(): got msg=1
09-09 17:18:05.528  7596  7596 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-09 17:18:05.529  7596  7596 V BluetoothPbapService: Pbap Service onBind
09-09 17:18:05.529  7596  7596 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:18:05.530  7596  7596 V BluetoothPbapService: state: 12
09-09 17:18:05.530  7596  7596 V BluetoothPbapService: Handler(): got msg=1
09-09 17:18:05.530  7596  7596 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-09 17:18:05.532  7596  7933 D BluetoothMapMasInstance: MAS initSocket()
09-09 17:18:05.533  7596  7934 V BluetoothPbapService: Pbap Service initSocket
09-09 17:18:05.533  7596  7933 D BluetoothMapMasInstance:   masId = 00
09-09 17:18:05.533  7596  7933 D BluetoothMapMasInstance:   msgTypes = 0e
09-09 17:18:05.533  7596  7933 D BluetoothMapMasInstance:   masName = SMS/MMS
09-09 17:18:05.533  7596  7933 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-09 17:18:05.534  1036  2099 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:18:05.534  1036  2053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-09 17:18:05.536  7596  7933 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:18:05.537  7596  7933 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-09 17:18:05.538  7596  7934 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:18:05.538  7596  7933 V BluetoothMapMasInstance: Succeed to create listening socket 
09-09 17:18:05.538  7596  7933 D BluetoothMapMasInstance: Accepting socket connection...
09-09 17:18:05.538  7596  7851 D BluetoothAdapterProperties: Scan Mode:21
09-09 17:18:05.539  7596  7851 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-09 17:18:05.541  7596  7934 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-09 17:18:05.541  7596  7934 V BluetoothPbapService: Succeed to create listening socket 
09-09 17:18:05.541  7596  7934 V BluetoothPbapService: Accepting socket connection...
09-09 17:18:05.541  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:05.603  1036  1562 I art     : Explicit concurrent mark sweep GC freed 25530(1251KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.486ms total 89.027ms
09-09 17:18:05.605  6751  6751 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-09 17:18:05.614  6751  6751 D BluetoothPbap: Proxy object connected
09-09 17:18:05.614  6751  6751 D PbapServerProfile: Bluetooth service connected
,09-09 17:18:05.618  7596  7596 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 17:18:05.618  7596  7596 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:18:05.618  7596  7596 V BluetoothPbapReceiver: ***********state = 12
09-09 17:18:05.626  2229  2229 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 17:18:05.627  2229  2229 D c       : Getting all permits...
09-09 17:18:05.627  2229  2229 D a       : Opening database...
09-09 17:18:05.627  6751  6751 D DockEventReceiver: finishStartingService: stopping service
09-09 17:18:05.629  2229  2229 D a       : Opening database auth.proximity.permit_store...
09-09 17:18:05.629  2229  2229 D a       : Closing database...
09-09 17:18:05.659  6751  6751 D BluetoothPermissionRequest: onReceive
,09-09 17:18:05.662  6751  6751 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-09 17:18:05.667  6751  6751 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-09 17:18:05.674  7596  7596 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,09-09 17:18:05.678  7596  7596 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-09 17:18:05.688  7596  7596 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-09 17:18:05.720  7596  7596 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-09 17:18:05.720  7596  7596 V BtOppService: onCreate
09-09 17:18:05.726  7596  7596 V BluetoothOppNotification: send message
09-09 17:18:05.731  7596  7596 V BtOppService: Starting RfcommListener
09-09 17:18:05.742  7596  7596 D BluetoothOppPreference: Dumping Names:  
09-09 17:18:05.742  7596  7596 D BluetoothOppPreference: {}
09-09 17:18:05.742  7596  7596 D BluetoothOppPreference: Dumping Channels:  
,09-09 17:18:05.742  7596  7596 D BluetoothOppPreference: {}
09-09 17:18:05.744  7596  7596 V BtOppService: onStartCommand
09-09 17:18:05.748  7596  7596 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:18:05.749  7596  7596 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-09 17:18:05.752  7596  7596 V BluetoothOppNotification: new notify threadi!
09-09 17:18:05.758  7596  7596 V BluetoothOppNotification: send delay message
,09-09 17:18:05.759  7596  7596 V BtOppService: start RfcommListener
09-09 17:18:05.761  7596  7939 V BtOppService: Deleted complete outbound shares, number =  0
09-09 17:18:05.763  7596  7942 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-09 17:18:05.763  7596  7939 V BtOppService: Deleted complete inbound failed shares, number = 0
09-09 17:18:05.765  7596  7939 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-09 17:18:05.765  7596  7942 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-09 17:18:05.767  7596  7943 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-09 17:18:05.767  7596  7596 V BtOppService: RfcommListener started
09-09 17:18:05.768  7596  7939 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@279de93f on behalf of 
09-09 17:18:05.768  7596  7942 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2107b20c on behalf of 
09-09 17:18:05.769  7596  7944 V BtOppRfcommListener: Starting RFCOMM listener....
09-09 17:18:05.770  1036  2075 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-09 17:18:05.773  7596  7943 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@29cea755 on behalf of 
09-09 17:18:05.774  7596  7943 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-09 17:18:05.775  7596  7942 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-09 17:18:05.775  7596  7944 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:18:05.776  7596  7943 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-09 17:18:05.777  7596  7943 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@4b7556a on behalf of 
09-09 17:18:05.778  7596  7943 V BluetoothOppNotification: outbound: succ-0  fail-0
09-09 17:18:05.779  7596  7944 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
09-09 17:18:05.779  7596  7944 V BtOppRfcommListener: Started RFCOMM listener....
09-09 17:18:05.779  7596  7944 I BtOppRfcommListener: Accept thread started.
09-09 17:18:05.780  7596  7944 V BtOppRfcommListener: Accepting connection...
09-09 17:18:05.780  7596  7943 V BluetoothOppNotification: outbound notification was removed.
09-09 17:18:05.780  7596  7943 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-09 17:18:05.781  7596  7943 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1811da5b on behalf of 
09-09 17:18:05.782  7596  7943 V BluetoothOppNotification: inbound: succ-0  fail-0
09-09 17:18:05.783  7596  7943 V BluetoothOppNotification: inbound notification was removed.
09-09 17:18:05.783  7596  7943 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,09-09 17:18:05.785  7596  7943 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d83e2f8 on behalf of 
09-09 17:18:05.789  7596  7596 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285fc213
09-09 17:18:05.789  7596  7596 V BluetoothFtpService: Ftp Service onCreate
09-09 17:18:05.789  7596  7596 I BluetoothFtpService: Ftp Service onCreate
09-09 17:18:05.790  7596  7596 V BluetoothFtpService: Ftp Service onStartCommand
09-09 17:18:05.790  7596  7596 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:18:05.790  7596  7596 V BluetoothFtpService: Starting Listening on sockets
09-09 17:18:05.790  7596  7596 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 17:18:05.790  7596  7596 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 17:18:05.790  7596  7596 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 17:18:05.790  7596  7596 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:18:05.790  7596  7596 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-09 17:18:05.791  7596  7596 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-09 17:18:05.793  7596  7596 V BtOppService: ContentObserver received notification
09-09 17:18:05.793  7596  7596 V BtOppService: ContentObserver received notification
09-09 17:18:05.793  7596  7596 V BluetoothFtpService: Handler(): got msg=1
09-09 17:18:05.794  7596  7596 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-09 17:18:05.794  7596  7596 V BluetoothFtpService: Ftp Service initSocket
09-09 17:18:05.796  1036  2075 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:18:05.797  7596  7596 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 17:18:05.797  7596  7945 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-09 17:18:05.797  7596  7945 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-09 17:18:05.798  7596  7945 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@266d5e36 on behalf of 
09-09 17:18:05.799  7596  7945 V BluetoothOppNotification: update too frequent, put in queue
09-09 17:18:05.800  7596  7945 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-09 17:18:05.806  7596  7596 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
09-09 17:18:05.806  7596  7596 V BluetoothFtpService: Succeed to create listening socket on channel 20
,09-09 17:18:05.809  7596  7946 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-09 17:18:05.822  7596  7596 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285fc213
,09-09 17:18:05.822  7596  7596 V BluetoothSapService: Sap Service onCreate
,09-09 17:18:05.824  7596  7596 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:18:05.824  7596  7596 V BluetoothSapService: state: 12
09-09 17:18:05.824  7596  7596 V BluetoothSapService: Starting SAP server process
09-09 17:18:05.824  7950  7950 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:18:05.824  7950  7950 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:18:05.832  7596  7596 V BluetoothSapService: SAP Service startRfcommListenerThread
09-09 17:18:05.834  7596  7951 V BluetoothSapService: Sap Service initRfcommSocket
09-09 17:18:05.834  1036  1562 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:18:05.835  7596  7951 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:18:05.836  7596  7951 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-09 17:18:05.837  7596  7951 V BluetoothSapService: Succeed to create listening socket 
09-09 17:18:05.837  7596  7951 V BluetoothSapService: Accepting socket connection...
,09-09 17:18:05.843  7950  7950 V BT_SAP  : Event pipe created
,09-09 17:18:05.843  7950  7950 V BT_SAP  : create_server_socket qcom.sap.server
,09-09 17:18:05.843  7950  7950 V BT_SAP  : created socket fd 6
09-09 17:18:06.319  6571  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:06.319  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:06.319  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:18:06.319  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:18:06.319  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:06.319  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:06.319  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:06.319  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:18:06.331  6571  6647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:18:06.332  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:06.333  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2a2429f3 added. We now have 8 listener(s)
09-09 17:18:06.333  6571  6647 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:06.336  1036  1562 D WifiServiceImplEx: setWifiEnabled: false pid=6571, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-09 17:18:06.336  1036  1562 D WifiService: setWifiEnabled: false pid=6571, uid=10118
09-09 17:18:06.336  1036  1562 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 17:18:06.342  6571  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:06.347  1036  1704 D WifiServiceImplEx: setWifiEnabled: true pid=6571, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-09 17:18:06.348  1036  1704 D WifiService: setWifiEnabled: true pid=6571, uid=10118
09-09 17:18:06.348  1036  1704 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 17:18:06.368  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-09 17:18:06.368  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 17:18:06.368  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,09-09 17:18:06.369  1036  1525 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-09 17:18:06.369  1036  1525 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,09-09 17:18:06.372  1036  1525 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,09-09 17:18:06.372  1036  1525 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-09 17:18:06.372  1036  1525 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
,09-09 17:18:06.372  1036  1525 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-09 17:18:06.372  1036  1525 I WifiUtil: Intf0MacAddress=C49A027FFB5D
,09-09 17:18:06.372  1036  1525 E WifiHW  : unknown target_country: EU , set to default
09-09 17:18:06.372  1036  1525 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
,09-09 17:18:06.372  1036  1525 E WifiHW  : [wifi_ensure_config_files] default country2 = GB,
09-09 17:18:06.372  1036  1525 I WifiUtil: gEnableBmps=1
09-09 17:18:06.760  7596  7596 V BluetoothOppNotification: new notify threadi!,
09-09 17:18:06.761  7596  7596 V BluetoothOppNotification: send delay message,
,09-09 17:18:06.788  7596  7961 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-09 17:18:06.791  7596  7961 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ea927c2 on behalf of 
09-09 17:18:06.792  7596  7961 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-09 17:18:06.794  7596  7961 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-09 17:18:06.795  7596  7961 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a2f39d3 on behalf of 
09-09 17:18:06.795  7596  7961 V BluetoothOppNotification: outbound: succ-0  fail-0
09-09 17:18:06.797  7596  7961 V BluetoothOppNotification: outbound notification was removed.
09-09 17:18:06.798  7596  7961 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-09 17:18:06.799  7596  7961 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5ec1910 on behalf of 
09-09 17:18:06.799  7596  7961 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-09 17:18:06.804  7596  7961 V BluetoothOppNotification: inbound notification was removed.
,09-09 17:18:06.804  7596  7961 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-09 17:18:06.805  7596  7961 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2789bc09 on behalf of 
09-09 17:18:07.044   319   880 D SoftapController: Softap fwReload - Ok
,09-09 17:18:07.168  1036  1525 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (790ms)
,09-09 17:18:07.175   319   880 D CommandListener: Setting iface cfg
09-09 17:18:07.175   319   880 D CommandListener: Trying to bring down wlan0
09-09 17:18:07.176   319   880 D CommandListener: Clearing all IP addresses on wlan0
09-09 17:18:07.177  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 17:18:07.178  6751  6751 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-09 17:18:07.178  6751  6751 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 17:18:07.178  6751  6751 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 17:18:07.178  6751  6751 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-09 17:18:07.179  6751  6751 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-09 17:18:07.179  6751  6751 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 17:18:07.180  6751  6751 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-09 17:18:07.180  6751  6751 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 17:18:07.180  6751  6751 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 17:18:07.180  6751  6751 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 17:18:07.180  6751  6751 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-09 17:18:07.180  6751  6751 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-09 17:18:07.182  1036  1525 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-09 17:18:07.184  1036  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 17:18:07.184  1036  1525 E WifiStateMachine: useWiFiOffloading() : false
09-09 17:18:07.184  1036  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-09 17:18:07.185  1036  1525 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-09 17:18:07.185  1036  1525 D WifiMonitor: connecting to supplicant
09-09 17:18:07.174  7983  7983 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:18:07.174  7983  7983 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:18:07.194  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:18:07.194  1959  1959 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,09-09 17:18:07.199  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:07.210  7983  7983 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-09 17:18:07.227  1036  1103 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7985 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
09-09 17:18:07.227  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-09 17:18:07.245  7983  7983 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-09 17:18:07.245  7983  7983 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-09 17:18:07.248  1036  1118 D Tethering: InitialState.processMessage what=4
09-09 17:18:07.249  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 17:18:07.259   347   347 I art     : Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 457us total 21.287ms
,09-09 17:18:07.276   347   347 I art     : Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 364us total 16.296ms
,09-09 17:18:07.290   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 288us total 13.068ms
,09-09 17:18:07.314  1036  1952 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8007 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-09 17:18:07.318  7985  8005 W FormManager: Network not available. Please check & try again.
09-09 17:18:07.325  7983  7983 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 17:18:07.327  7985  8006 V FormManager: Network unavailable.
09-09 17:18:07.328  7985  8006 V FormManager: Network unavailable.
09-09 17:18:07.338  1036  1562 I ActivityManager: Killing 7060:com.lge.drmservice/u0a62 (adj 15): empty #17
,09-09 17:18:07.349  7983  7983 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
09-09 17:18:07.353  1036  1525 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-09 17:18:07.353  1036  1525 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
,09-09 17:18:07.353  1036  1525 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
,09-09 17:18:07.354  1036  1525 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-09 17:18:07.354  1036  1525 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:18:07.355  1036  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:18:07.355  1036  1525 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:18:07.355  1036  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:18:07.356  1036  1525 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-09 17:18:07.356  1036  1525 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-09 17:18:07.356  1036  1525 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-09 17:18:07.356  1036  1525 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-09 17:18:07.356  1036  1525 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,09-09 17:18:07.370  1036  2075 W libprocessgroup: failed to open /acct/uid_10062/pid_7060/cgroup.procs: No such file or directory
09-09 17:18:07.372  1036  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 17:18:07.372  1036  1525 E WifiStateMachine: useWiFiOffloading() : false
09-09 17:18:07.372  1036  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 17:18:07.372  1036  1525 D WifiNative-wlan0: doBoolean: SET update_config 1
09-09 17:18:07.372  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:18:07.372  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:18:07.372  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:18:07.372  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:18:07.372  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 17:18:07.372  1036  1525 D WifiNative-wlan0: SET update_config 1: returned true
09-09 17:18:07.372  1036  1525 D WifiConfigStore: Loading config and enabling all networks 
09-09 17:18:07.372  1036  1525 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-09 17:18:07.373  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-09 17:18:07.373  1036  1525 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-09 17:18:07.373  1959  1959 D WfdService: Waiting for WifiP2p enabling
09-09 17:18:07.374  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:18:07.374  1036  1530 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-09 17:18:07.376  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:07.376  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:07.376  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:18:07.376  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:07.376  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:07.376  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:07.376  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:07.376  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:18:07.377  6571  6571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:18:07.379  6571  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:07.379  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:07.379  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:18:07.379  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:07.379  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:07.379  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:07.379  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:07.379  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:18:07.384  6571  6647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:18:07.384  1036  1525 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-09 17:18:07.387  1036  8026 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,09-09 17:18:07.387  1036  8026 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-09 17:18:07.388  7983  7983 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-09 17:18:07.388  1036  8026 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-09 17:18:07.388  1036  8026 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-09 17:18:07.388  1036  8026 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-09 17:18:07.388  1036  8026 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-09 17:18:07.389  6571  6647 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-09 17:18:07.390  6571  6647 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-09 17:18:07.393  6571  6647 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6347e26 Bundle[{}]
09-09 17:18:07.394  1036  1525 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-09 17:18:07.394  1036  1525 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-09 17:18:07.394  6571  6647 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 17:18:07.394  6571  6647 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-09 17:18:07.395  1036  1525 D WifiStateMachine: enableVerboseLogging : level 2
09-09 17:18:07.395  6571  6647 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-09 17:18:07.395  1036  1525 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-09 17:18:07.395  1036  1525 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-09 17:18:07.395  1036  1525 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-09 17:18:07.396  6571  6647 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 17:18:07.396  1036  1525 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-09 17:18:07.396  1036  1525 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-09 17:18:07.396  1036  1525 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-09 17:18:07.396  1036  1525 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-09 17:18:07.397  6571  6647 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-09 17:18:07.397  1036  1525 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-09 17:18:07.397  1036  1525 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-09 17:18:07.397  1036  1525 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-09 17:18:07.397  1036  1525 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-09 17:18:07.398  1036  1525 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-09 17:18:07.398  1036  1525 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-09 17:18:07.398  1036  1525 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-09 17:18:07.399  6571  6647 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-09 17:18:07.399  1959  1959 D WfdsService: Supplicant Connection state is changed : true
09-09 17:18:07.399  1959  2335 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-09 17:18:07.399  1959  2335 D WfdsService: Set the WFDS Monitor: true
09-09 17:18:07.399  1959  2335 D WfdsMonitor: WfdsMonitorThread create
09-09 17:18:07.399  1959  2335 D WfdsMonitor: WFDS Monitor is created and started
09-09 17:18:07.399  1959  2335 D WfdsService: WiFi: Supplicant connection re-established
09-09 17:18:07.399  7677  7677 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:18:07.399  1036  1525 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 17:18:07.399  1036  1525 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-09 17:18:07.400  1036  1525 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-09 17:18:07.400  1036  1525 D WifiNative-HAL: Setting external_sim to 1
09-09 17:18:07.400  1036  1525 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-09 17:18:07.400  1959  8028 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-09 17:18:07.400  1036  1525 D WifiNative-wlan0: SET external_sim 1: returned true
09-09 17:18:07.400  1036  1525 I WifiNative-HAL: startHal
09-09 17:18:07.400  1036  1525 D wifi    : setting scan oui 0xaf6e4fe0
09-09 17:18:07.400  1959  8028 E CtrlSupplicant: Succeed to open control connection
09-09 17:18:07.401  1959  8028 E CtrlSupplicant: Succeed to open monitor connection
09-09 17:18:07.401  1036  1525 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 17:18:07.401  1036  1525 I WifiNative-HAL: startHal
09-09 17:18:07.401  1036  1525 D wifi    : setting scan oui 0xaf6e4fe0
09-09 17:18:07.401  1959  8028 D WfdsMonitor: Supplicant connection established
09-09 17:18:07.401  1036  1525 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-09 17:18:07.401  1959  2335 D WfdsService: Connected to the supplicant for wfds
09-09 17:18:07.401  1036  1525 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-09 17:18:07.401  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-09 17:18:07.401  7983  7983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-09 17:18:07.402  1036  1525 D WifiNative-wlan0: DR,IVER BTCOEXSCAN-STOP: returned true
09-09 17:18:07.402  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-09 17:18:07.402  7983  7983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-09 17:18:07.402  1036  1525 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-09 17:18:07.402  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-09 17:18:07.402  7983  7983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-09 17:18:07.402  1036  1525 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-09 17:18:07.402  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-09 17:18:07.402  7983  7983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-09 17:18:07.403  1036  1525 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-09 17:18:07.403  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-09 17:18:07.403  7983  7983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-09 17:18:07.403  1036  1525 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-09 17:18:07.403  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-09 17:18:07.403  7983  7983 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-09 17:18:07.403  1036  1525 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-09 17:18:07.403  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-09 17:18:07.403  7983  7983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-09 17:18:07.404  1036  1525 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-09 17:18:07.404  1036  1525 E WifiNative: : [138,721,044 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-09 17:18:07.404  1036  1525 D WifiNative-wlan0: doBoolean: RECONNECT
09-09 17:18:07.404  1036  1525 D WifiNative-wlan0: RECONNECT: returned true
09-09 17:18:07.404  1036  1525 D WifiNative-wlan0: doString: [STATUS]
09-09 17:18:07.405  1036  8026 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-09 17:18:07.405  1036  8026 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-09 17:18:07.405  1036  1525 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-09 17:18:07.405  1036  1525 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 17:18:07.405  6571  6647 I System.out: Running OutgoingSocketThread
09-09 17:18:07.405  1036  1525 D WifiNative-wlan0: SET ps 1: returned true
,09-09 17:18:07.407  6571  8029 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 851)
09-09 17:18:07.407  1036  1522 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:07.408  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
09-09 17:18:07.408  1036  1036 D RttService: SCAN_AVAILABLE : 3
09-09 17:18:07.408  1036  1543 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:07.408  1036  1543 I WifiNative-HAL: startHal
09-09 17:18:07.409  1036  1543 D wifi    : getting scan capabilities on interface[1] = 0xaf6e4fe0
09-09 17:18:07.409  1036  1543 D wifi    : failed to get capabilities : -3
09-09 17:18:07.409  1036  1543 E WifiScanningService: could not get scan capabilities
09-09 17:18:07.409   319   880 D CommandListener: Setting iface cfg
09-09 17:18:07.409  1036  1544 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:07.409   319   880 D CommandListener: Trying to bring up p2p0
09-09 17:18:07.409  1036  1522 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-09 17:18:07.409  1036  1522 D LGWifiP2pService: P2pEnablingState
09-09 17:18:07.409  1036  1522 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:07.409  1036  1522 D LGWifiP2pService: P2p socket connection successful
09-09 17:18:07.409  1036  1522 D LGWifiP2pService: P2pEnabledState
09-09 17:18:07.409  1036  1522 D LGWifiP2pService: sending p2p connection changed broadcast
09-09 17:18:07.410  1036  1522 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-09 17:18:07.410  1959  1959 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-09 17:18:07.410  1959  1959 D WfdsService: WifiP2pState is changed : true
09-09 17:18:07.410  1959  2335 D WfdsService: Receive the WFDS_ENABLE Method
09-09 17:18:07.410  1036  1522 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-09 17:18:07.410  1959  2335 D WfdsService: Set the WFDS Monitor: true
09-09 17:18:07.410  1959  2335 D WfdsService: Connected to the supplicant for wfds
09-09 17:18:07.410  1959  2335 D WfdsJNI : doCommand: WFDS_SET TRUE
09-09 17:18:07.411  1036  1522 D WifiNative-p2p0: doBoolean: SET device_name G3
09-09 17:18:07.411  7983  7983 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-09 17:18:07.411  1959  2335 D WfdsService: selectPreferredScanChannel [36]
09-09 17:18:07.411  1959  2335 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-09 17:18:07.411  6571  8029 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 49375
09-09 17:18:07.411  6571  8029 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-09 17:18:07.412  1036  1525 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-09 17:18:07.412  1036  1525 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-09 17:18:07.412  1036  1525 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-09 17:18:07.413  1036  1525 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-09 17:18:07.413  1036  1525 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-09 17:18:07.413  1959  1959 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-09 17:18:07.413  1036  1525 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-09 17:18:07.414  1959  1959 D WfdsService: isConnected: false
09-09 17:18:07.414  1036  1522 D WifiNative-p2p0: SET device_name G3: returned true
09-09 17:18:07.414  1036  1522 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-09 17:18:07.414  1036  1525 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-09 17:18:07.414  1036  1522 D LGWifiP2pService: before postfix = G3
09-09 17:18:07.414  1036  1525 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-09 17:18:07.414 , 1036  1522 D WifiServerServiceExt: postfix byte check : 2
09-09 17:18:07.414  7983  7983 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-09 17:18:07.414  1036  1522 D LGWifiP2pService: after postfix = G3
09-09 17:18:07.414  1036  1522 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-09 17:18:07.415  1036  1522 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-09 17:18:07.415  1036  1522 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-09 17:18:07.415  1036  1525 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-09 17:18:07.415  1036  1522 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-09 17:18:07.415  1036  1522 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-09 17:18:07.415  1036  1522 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-09 17:18:07.415  1036  1522 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-09 17:18:07.415  1036  1525 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-09 17:18:07.415  1036  1522 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-09 17:18:07.415  1036  1522 D WifiNative-HAL: p2pGetDeviceAddress
09-09 17:18:07.416  1036  1525 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-09 17:18:07.416  1036  1525 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-09 17:18:07.416  7983  7983 E wpa_supplicant: disconnect_rssi_lvl: -100
09-09 17:18:07.416  1036  1522 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-09 17:18:07.417  1036  1522 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-09 17:18:07.417  1036  1522 D WifiNative-p2p0: doBoolean: P2P_FLUSH
,09-09 17:18:07.417  1036  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=138734  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 17:18:07.417  1959  1959 I WfdStateTracker: handleP2pThisDeviceChanged
09-09 17:18:07.417  1036  1522 D WifiNative-p2p0: P2P_FLUSH: returned true
09-09 17:18:07.417  1959  1959 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-09 17:18:07.417  1036  1522 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-09 17:18:07.417  1959  1959 D WfdsService: Update P2p Interface State: 3
09-09 17:18:07.417  1036  1522 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-09 17:18:07.418  1036  1522 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-09 17:18:07.418  1036  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=138735  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 17:18:07.418  1036  1525 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-09 17:18:07.419  1036  1525 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-09 17:18:07.419  1036  1522 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-09 17:18:07.419  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:18:07.419  1036  1522 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-09 17:18:07.419  1036  1525 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-09 17:18:07.419  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-09 17:18:07.419  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:18:07.419  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-09 17:18:07.421  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:18:07.421  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:18:07.422  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:18:07.425  8007  8007 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 17:18:07.428  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 17:18:07.433  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:18:07.434  1036  2053 I ActivityManager: Killing 7083:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
09-09 17:18:07.439  1036  1522 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-09 17:18:07.439  1036  1522 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-09 17:18:07.440  7983  7983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,09-09 17:18:07.441  7983  7983 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 17:18:07.441  1036  8026 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 17:18:07.441  1036  8026 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 17:18:07.442  1036  8026 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 17:18:07.442  1036  8026 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 17:18:07.442  7983  7983 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-09 17:18:07.442  7983  7983 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:18:07.442  1959  8028 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:18:07.442  1036  8026 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:18:07.442  1036  8026 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:18:07.442  1036  8026 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:18:07.442  1036  8026 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:18:07.442  1036  1525 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-09 17:18:07.443  7983  7983 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:18:07.443  1959  8028 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:18:07.443  1036  8026 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:18:07.443  1036  8026 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:18:07.443  1036  1525 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-09 17:18:07.443  1036  8026 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:18:07.443  1036  8026 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:18:07.443  1036  1525 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-09 17:18:07.444  1036  1525 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-09 17:18:07.444  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-09 17:18:07.444  7983  7983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-09 17:18:07.444  7983  7983 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 17:18:07.444  1036  8026 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-09 17:18:07.444  1036  8026 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 17:18:07.444  1036  8026 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 17:18:07.445  1036  8026 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 17:18:07.445  1036  1525 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-09 17:18:07.445  1036  1525 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-09 17:18:07.445  1036  1525 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-09 17:18:07.446  1036  1525 D WifiNative-wlan0: doBoolean: SCAN
09-09 17:18:07.446  1036  1525 D WifiNative-wlan0: SCAN: returned false
09-09 17:18:07.447  1036  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=138764  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 17:18:07.468  1036  1522 D LGWifiP2pService: InactiveState
09-09 17:18:07.468  1036  1934 W libprocessgroup: failed to open /acct/uid_10085/pid_7083/cgroup.procs: No such file or directory
09-09 17:18:07.468  1036  1522 D LGWifiP2pService: InactiveState{ when=-50ms what=14337,6 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:07.468  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-50ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:07.468  1036  1522 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,09-09 17:18:07.469  7983  7983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-09 17:18:07.469  7983  7983 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 17:18:07.469  1959  8028 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 17:18:07.470  7983  7983 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-09 17:18:07.470  1036  8026 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 17:18:07.470  1036  8026 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 17:18:07.470  7983  7983 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:18:07.470  1036  8026 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 17:18:07.470  1036  8026 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 17:18:07.470  1036  1522 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-09 17:18:07.470  1036  1522 D LGWifiP2pService: InactiveState{ when=-28ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:07.470  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-28ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:07.471  1036  1522 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:07.471  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:07.471  1036  1522 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:07.471  1036  1522 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:07.471  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:07.471  1036  1522 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:07.471  1036  1522 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:07.471  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:07.471  1036  1522 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:07.471  1036  1522 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:07.471  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:07.471  7983  7983 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:18:07.471  1036  1522 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:07.471  1036  1036 E WifiServerServiceExt: No p2p device connected
09-09 17:18:07.471  1036  8026 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:18:07.471  1036  8026 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:18:07.471  1036  8026 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:18:07.471  1036  8026 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:18:07.471  1036  8026 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:18:07.471  1036  8026 E Wifi,Monitor: WifiMonitor:p2p0 cnt=54 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:18:07.471  1036  8026 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:18:07.471  1036  8026 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 17:18:07.472  1959  8028 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:18:07.472  1959  8028 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 17:18:07.472  1959  2335 W WfdsService: DefaultState - msg [9441285] is not handled
09-09 17:18:07.472  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:18:07.473  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:18:07.473  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:18:07.473  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:18:07.473  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-09 17:18:07.473  1036  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=138790  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 17:18:07.474  1036  1525 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 17:18:07.474  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:18:07.474  1036  1525 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 17:18:07.475  1036  1525 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 17:18:07.475  1036  1525 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 17:18:07.476  1036  1525 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 17:18:07.477  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:18:07.477  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
09-09 17:18:07.477  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:18:07.477  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
09-09 17:18:07.480  6751  6751 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-09 17:18:07.480  6751  6751 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 17:18:07.480  6751  6751 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 17:18:07.480  6751  6751 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-09 17:18:07.480  6751  6751 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-09 17:18:07.481  6751  6751 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 17:18:07.481  6751  6751 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-09 17:18:07.481  6751  6751 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 17:18:07.481  6751  6751 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 17:18:07.481  6751  6751 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 17:18:07.481  6751  6751 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-09 17:18:07.487  8007  8007 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 17:18:07.490  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-09 17:18:07.493  7985  8033 W FormManager: Network not available. Please check & try again.
,09-09 17:18:07.496  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:18:07.499  7985  8034 V FormManager: Network unavailable.
09-09 17:18:07.501  7985  8034 V FormManager: Network unavailable.
09-09 17:18:07.509  4329  4329 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 17:18:07.510  4329  4329 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,09-09 17:18:07.511  4329  4329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 17:18:07.513  4329  4329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 17:18:07.519  4329  8036 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 17:18:07.519  4329  8036 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 17:18:07.520  4329  8035 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 17:18:07.571  1036  2075 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8037 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-09 17:18:07.725  8037  8037 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 17:18:07.725  8037  8037 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-09 17:18:07.734  8037  8037 V [BNRBootReceiver]: Boot Receiver Return
09-09 17:18:07.734  8037  8037 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-09 17:18:07.785  1036  2310 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8058 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-09 17:18:07.786  1036  2310 I ActivityManager: Killing 7119:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,09-09 17:18:07.896  1036  1994 W libprocessgroup: failed to open /acct/uid_10093/pid_7119/cgroup.procs: No such file or directory
,09-09 17:18:07.967  8058  8058 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 17:18:07.994  8058  8058 D PluginManager: init()
,09-09 17:18:08.065  7983  7983 E wpa_supplicant: USIM:  scard_init function
,09-09 17:18:08.067  7983  7983 I wpa_supplicant: Trying to associate with SSID 'NG700'
,09-09 17:18:08.067  1036  8026 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-09 17:18:08.068  1036  8026 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-09 17:18:08.068  1036  8026 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
,09-09 17:18:08.068  1036  8026 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: WPS-AP-AVAILABLE 
09-09 17:18:08.068  1036  8026 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-09 17:18:08.070  1036  1525 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
09-09 17:18:08.070  1036  1525 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
09-09 17:18:08.070  1036  1525 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
09-09 17:18:08.071  1036  1525 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
09-09 17:18:08.071  1036  1525 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-09 17:18:08.072  1036  8026 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-09 17:18:08.072  1036  8026 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,09-09 17:18:08.090  1036  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=139406  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-09 17:18:08.094  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:18:08.094  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:18:08.095  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:18:08.095  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:18:08.095  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-09 17:18:08.096  1036  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=139412  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-09 17:18:08.097  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:18:08.097  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-09 17:18:08.099  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:18:08.261  7983  7983 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-09 17:18:08.261  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 17:18:08.262  1036  8026 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-09 17:18:08.262  1036  8026 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-09 17:18:08.262  1036  8026 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-09 17:18:08.262  1036  8026 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-09 17:18:08.262  1036  8026 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 17:18:08.262  1036  8026 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 17:18:08.263  1036  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=139580  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,09-09 17:18:08.264  1036  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=139580  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-09 17:18:08.264  1036  1525 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139581
09-09 17:18:08.264  1036  1525 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139581
09-09 17:18:08.265  1036  1525 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139582
09-09 17:18:08.265  1036  1525 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139582
09-09 17:18:08.265  1036  1525 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139582
09-09 17:18:08.266  1036  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=139582  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-09 17:18:08.273  1036  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=139589  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-09 17:18:08.275  1036  1525 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:18:08.276  1036  1525 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:18:08.277  1036  1525 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:18:08.278  1036  1525 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-09 17:18:08.279  1036  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-09 17:18:08.286  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:18:08.286  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:18:08.287  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:18:08.288  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:18:08.288  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,09-09 17:18:08.288  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:18:08.289  1036  8026 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 17:18:08.289  1036  8026 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 17:18:08.290  7983  7983 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 17:18:08.290  1036  8026 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-09 17:18:08.290  1036  8026 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 17:18:08.290  7983  7983 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 17:18:08.290  1036  8026 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 17:18:08.290  1036  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=139607  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-09 17:18:08.291  1036  8026 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-09 17:18:08.291  1036  8026 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 17:18:08.291  1036  8026 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 17:18:08.291  1036  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=139608  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-09 17:18:08.291  1036  8026 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 17:18:08.291  1036  8026 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 17:18:08.292  1036  1525 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=139608
09-09 17:18:08.292  1036  1525 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=139609
09-09 17:18:08.292  1036  1525 D WifiNative-wlan0: doString: [STATUS]
09-09 17:18:08.293  1036  8026 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,09-09 17:18:08.293  1036  8026 E WifiMonitor: WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 17:18:08.293  1036  1525 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-09 17:18:08.294  1036  1525 I WifiServiceExtension: setVHTCapabilityType  : false
09-09 17:18:08.298  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:18:08.299  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:18:08.299  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-09 17:18:08.299  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:18:08.299  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,09-09 17:18:08.307  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:18:08.307  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:18:08.308  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:18:08.315  1036  1525 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-09 17:18:08.315  1036  1525 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-09 17:18:08.320  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:18:08.320  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:18:08.320  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-09 17:18:08.320  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:18:08.320  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:18:08.320  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-09 17:18:08.329  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:18:08.329  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 17:18:08.330  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:18:08.330  1036  1525 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-09 17:18:08.330  1036  1525 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 17:18:08.330  1036  1525 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 17:18:08.331  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:18:08.331  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:18:08.331  1036  1532 D ConnectivityService: Got NetworkAgent Messenger
09-09 17:18:08.331  1036  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-09 17:18:08.331  1036  1532 D ConnectivityService: NetworkAgent connected
09-09 17:18:08.331  1036  1525 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 17:18:08.331  1036  1525 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-09 17:18:08.337  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:18:08.344  1036  1525 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-09 17:18:08.344  1036  1525 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 17:18:08.344  1036  1525 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 17:18:08.345  1036  1525 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 17:18:08.345  1036  1525 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-09 17:18:08.353  1036  1525 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-09 17:18:08.353   319   880 D CommandListener: Setting iface cfg
09-09 17:18:08.356  1036  1525 E WifiStateMachine: Start Dhcp Watchdog 3
09-09 17:18:08.356  1036  8080 D DhcpStateMachine: StoppedState
09-09 17:18:08.356  1036  8080 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:08.356  1036  8080 D DhcpStateMachine: WaitBeforeStartState
09-09 17:18:08.356  1036  1525 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=139673  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-09 17:18:08.356  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:18:08.356  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,09-09 17:18:08.357  1036  1525 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=139673  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 17:18:08.357  1036  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=139674  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 17:18:08.358  1036  1525 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=139675  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 17:18:08.358  1036  1525 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=139675  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 17:18:08.359  1036  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=139676  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 17:18:08.360  1036  1525 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14260] from screen [on:0 period:260505832] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 17:18:08.361  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:260505833] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 17:18:08.361  1036  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-09 17:18:08.364  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:18:08.365  1036  1532 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-09 17:18:08.365  1036  1525 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:18:08.365  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:18:08.366  1036  1525 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:18:08.366  1036  1525 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:18:08.367  1036  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:18:08.367  1036  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 17:18:08.367  1036  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-09 17:18:08.368  1036  1525 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=132,0,0
09-09 17:18:08.368  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=132,0,0
09-09 17:18:08.368  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-09 17:18:08.368  7983  7983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-09 17:18:08.369  1036  1525 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-09 17:18:08.369  1036  1525 D WifiNative-wlan0: doBoolean: SET ps 0
,09-09 17:18:08.370  1036  1525 D WifiNative-wlan0: SET ps 0: returned true
,09-09 17:18:08.370  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-09 17:18:08.371  7983  7983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-09 17:18:08.371  1036  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-09 17:18:08.372  1036  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1a842e25 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:08.372  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1a842e25 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:08.372  1036  1525 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-09 17:18:08.372  1036  8080 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:08.372  1036  8080 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-09 17:18:08.373  1036  1525 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 17:18:08.373  1036  1525 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-09 17:18:08.373   319   880 D CommandListener: Setting iface cfg
09-09 17:18:08.374   319   880 D CommandListener: Trying to bring up wlan0
09-09 17:18:08.374  1036  1525 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-09 17:18:08.375  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:18:08.375  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-09 17:18:08.376  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 17:18:08.376  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-09 17:18:08.377  1036  1525 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
09-09 17:18:08.378  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
09-09 17:18:08.378  1036  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:08.378  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:08.379  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 17:18:08.379  7983  7983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 17:18:08.379  1036  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 17:18:08.379  1036  1525 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-09 17:18:08.380  7983  7983 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-09 17:18:08.380  1036  1525 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-09 17:18:08.380  1036  1525 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 17:18:08.396  1036  1525 D WifiNative-wlan0: SET ps 1: returned true
09-09 17:18:08.397  1036  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-09 17:18:08.397  1036  1525 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 17:18:08.398  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-09 17:18:08.398  1036  1525 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 17:18:08.399  1036  1525 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 17:18:08.399  1036  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 17:18:08.400  1036  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 17:18:08.400  1036  1532 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-09 17:18:08.401  1036  1525 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-09 17:18:08.401  1036  1525 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-09 17:18:08.401  1036  1525 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-09 17:18:08.402  1036  1532 D ConnectivityService: ignoring duplicate network state non-change
09-09 17:18:08.404  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:18:08.404  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:18:08.405  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:18:08.405  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:18:08.406  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-09 17:18:08.406  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:18:08.407  6571  6647 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 852)
09-09 17:18:08.407  6571  6647 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 852)
09-09 17:18:08.409  1036  1532 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-09 17:18:08.410  1036  1532 D ConnectivityService: Adding iface wlan0 to network 102
09-09 17:18:08.413  6571  6647 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 857)
09-09 17:18:08.414  6571  6647 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-09 17:18:08.414  6571  6647 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 858)
09-09 17:18:08.417  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:18:08.417  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:18:08.417  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-09 17:18:08.419  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:08.419  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b2016b0 added. We now have 2 listener(s)
09-09 17:18:08.421  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,09-09 17:18:08.425  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:18:08.425  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 17:18:08.426  1959  1959 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-09 17:18:08.426  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:18:08.427  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:18:08.428  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:18:08.428  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-09 17:18:08.428  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:18:08.430  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:18:08.430  1036  1532 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 17:18:08.430  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-09 17:18:08.430  1036  1532 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-09 17:18:08.431  1036  1532 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-09 17:18:08.431  1036  1952 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:18:08.432   319   880 E Netd    : netlink response contains error (File exists)
09-09 17:18:08.432  1036  1532 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-09 17:18:08.434  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,09-09 17:18:08.434  1036  1532 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-09 17:18:08.434  1036  1532 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-09 17:18:08.434  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-09 17:18:08.434  1036  1532 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-09 17:18:08.434  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:08.434  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:08.434  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:08.435  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb37929 added. We now have 9 listener(s)
09-09 17:18:08.435  6571  6647 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:08.435  1036  1525 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-09 17:18:08.435  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 17:18:08.438  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:18:08.438  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:18:08.438  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-09 17:18:08.438  1036  1532 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-09 17:18:08.438  1036  1532 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-09 17:18:08.438  1036  1532 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-09 17:18:08.438  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:18:08.439  1036  8079 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:08.439  1036  8079 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-09 17:18:08.439  1036  8079 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:08.439  1036  8079 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-09 17:18:08.442  1036  1532 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-09 17:18:08.443  1036  1532 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 17:18:08.443  1036  1532 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 17:18:08.443  1036  1532 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 17:18:08.443  1036  1532 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:18:08.443  1036  1532 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-09 17:18:08.443  1036  1532 D ConnectivityService: currentScore = 0, newScore = 20
09-09 17:18:08.443  1036  1532 D ConnectivityService:    accepting network in place of null
09-09 17:18:08.443  1036  1532 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:18:08.443   319  8085, D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-09 17:18:08.445  1036  1525 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:18:08.445  1036  1525 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 17:18:08.446  6571  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:18:08.446  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:08.446  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:18:08.446  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:08.446  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:08.446  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:08.446  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:08.446  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:18:08.446  1864  1864 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:18:08.446  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:18:08.446  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
,09-09 17:18:08.447  1036  1532 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-09 17:18:08.447  1036  1532 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-09 17:18:08.447  1864  1864 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-09 17:18:08.447  1036  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 17:18:08.446  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:18:08.448  6571  6647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:18:08.448  6571  6647 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:18:08.449  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:08.449  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@394d724f added. We now have 3 listener(s)
09-09 17:18:08.450  1036  1768 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:18:08.451  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-09 17:18:08.451  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 17:18:08.451  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 17:18:08.451  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 17:18:08.452  1036  1532 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 17:18:08.452  1036  1532 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-09 17:18:08.452  1036  1532 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-09 17:18:08.453  1036  1532 D ConnectivityService: validation of new default Network = false
09-09 17:18:08.453  1036  1532 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-09 17:18:08.453  1036  1532 D DSQN    : enableDataServiceNotify 
09-09 17:18:08.453  1036  1532 D DSQN    : start dsqn bin
09-09 17:18:08.454  6571  6571 V io.jxcore.no,de.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:08.454  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:08.454  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:18:08.454  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:08.454  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:08.454  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:18:08.454  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:18:08.454  6571  6571 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:18:08.454  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 17:18:08.454  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:08.454  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:08.454  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:08.455  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36e7eddc added. We now have 10 listener(s)
09-09 17:18:08.455  6571  6571 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:18:08.455  6571  6647 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:08.455  6571  6647 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:18:08.456  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:18:08.456  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:18:08.456  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:08.456  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.456  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:18:08.456  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:08.456  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b2016b0 removed from the list
09-09 17:18:08.456  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:08.456  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb37929 removed from the list
09-09 17:18:08.457  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:08.457  6571  6647 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:18:08.457  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:08.457  1036  1521 V Networ,kPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-09 17:18:08.458  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.458  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:08.461  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:18:08.461  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:18:08.461  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:08.461  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb37929 not in the list
09-09 17:18:08.461  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.461  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:08.461  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:18:08.461  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:18:08.461  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:08.462  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36e7eddc removed from the list
09-09 17:18:08.462  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:08.462  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.462  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:08.462  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:08.462  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@394d724f removed from the list
09-09 17:18:08.462  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:08.462  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f617ee5 added. We now have 2 listener(s)
09-09 17:18:08.463  1036  2081 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:18:08.465  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 17:18:08.466  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:08.466  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:08.466  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:08.466  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b4afdba added. We now have 9 listener(s)
09-09 17:18:08.466  6571  6647 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:08.466  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 17:18:08.469  1036  1532 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-09 17:18:08.469  1036  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:18:08.469  1036  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 17:18:08.469  1036  1532 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 17:18:08.464  8086  8086 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:18:08.464  8086  8086 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:18:08.470  1589  1795 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 17:18:08.470  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:18:08.474  6571  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:18:08.474  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:08.474  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:18:08.474  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:08.474  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:08.474  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:18:08.474  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:18:08.474  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:18:08.476  6571  6647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:18:08.476  6571  6647 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:18:08.477  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:08.478  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:08.478  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25f40bc8 added. We now have 3 listener(s)
09-09 17:18:08.479  1036  2075 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:18:08.480  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:08.482  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 17:18:08.482  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:08.482  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:08.483  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:08.483  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29302461 added. We now have 10 listener(s)
09-09 17:18:08.483  6571  6647 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:08.483  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:18:08.483  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:18:08.483  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:18:08.483  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:18:08.483  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 17:18:08.485  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 17:18:08.486  8086  8086 E DSQN    : DSQN ssw
09-09 17:18:08.486  8058  8058 W ExternalStrings: load override strings
09-09 17:18:08.486  8058  8058 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
09-09 17:18:08.486  8058  8058 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
09-09 17:18:08.486  8058  8058 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
09-09 17:18:08.486  8058  8058 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
09-09 17:18:08.486  8058  8058 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
09-09 17:18:08.486  8058  8058 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
09-09 17:18:08.486  8058  8058 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
09-09 17:18:08.486  8058  8058 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-09 17:18:08.486  8058  8058 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-09 17:18:08.486  8058  8058 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-09 17:18:08.486  8058  8058 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-09 17:18:08.486  8058  8058 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:08.486  8058  8058 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
09-09 17:18:08.486  8058  8058 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 17:18:08.486  8058  8058 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:18:08.486  8058  8058 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:18:08.486  8058  8058 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 17:18:08.486  8058  8058 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 17:18:08.486  1036  2053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:18:08.489  8058  8058 D StatusProvider: onCreate
,09-09 17:18:08.493  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 17:18:08.494  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 17:18:08.496  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 17:18:08.496  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:18:08.496  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 17:18:08.497  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:18:08.497  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:18:08.497  6571  6647 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 17:18:08.497  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:18:08.497  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:18:08.499  6571  6647 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:18:08.499  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:18:08.499  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:18:08.499  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:08.499  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.499  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:18:08.499  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:08.499  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f617ee5 removed from the list
09-09 17:18:08.499  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:08.499  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b4afdba removed from the list
09-09 17:18:08.499  6571  6647 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:18:08.499  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:08.500  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.500  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:08.500  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:18:08.500  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:18:08.500  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:08.500  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b4afdba not in the list
09-09 17:18:08.500  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.500  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:08.501  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:18:08.502   319  8085 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-09 17:18:08.502  6571  6647 D BluetoothLeScanner: could not find callback wrapper
09-09 17:18:08.502  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:18:08.502  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:18:08.502  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:08.502  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29302461 removed from the list
09-09 17:18:08.502  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:08.502  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.502  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:08.502  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:08.502  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25f40bc8 removed from the list
09-09 17:18:08.502  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:08.502  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24221c74 added. We now have 2 listener(s)
09-09 17:18:08.502  1036  2099 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:18:08.504  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 17:18:08.504  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:08.504  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:08.504  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:08.504  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ce9a59d added. We now have 9 listener(s)
09-09 17:18:08.504  6571  6647 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:08.504  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 17:18:08.506  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:18:08.508  6571  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:18:08.508  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:08.508  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:18:08.508  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:08.508  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:08.508  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:18:08.508  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:18:08.508  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:18:08.509  6571  6647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:18:08.509  6571  6647 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:18:08.509  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:08.509  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ab75e3 added. We now have 3 listener(s)
09-09 17:18:08.509  1036  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:18:08.511  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 17:18:08.511  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:08.511  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:08.511  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:08.511  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b7e8be0 added. We now have 10 listener(s)
09-09 17:18:08.511  6571  6647 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:08.511  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:18:08.511  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:08.512  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:18:08.512  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:18:08.512  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:08.512  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:18:08.512  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:18:08.512  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 17:18:08.514  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 17:18:08.514  1036  1768 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:18:08.516  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 17:18:08.517  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 17:18:08.518  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 17:18:08.518  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:18:08.519  6571  6647 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 17:18:08.519  6571  6647 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:18:08.519  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:18:08.519  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:18:08.519  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:08.519  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.519  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:18:08.519  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:08.519  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24221c74 removed from the list
09-09 17:18:08.519  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:08.519  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ce9a59d removed from the list
09-09 17:18:08.519  6571  6647 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:18:08.519  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:08.519  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.519  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:08.520  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:18:08.520  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:18:08.520  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:08.520  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ce9a59d not in the list
09-09 17:18:08.520  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.520  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:08.520  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:18:08.521  6571  6647 D BluetoothLeScanner: could not find callback wrapper
09-09 17:18:08.521  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:18:08.521  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:18:08.521  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:08.521  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b7e8be0 removed from the list
09-09 17:18:08.521  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:08.521  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.521  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:08.521  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:08.521  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ab75e3 removed from the list
09-09 17:18:08.521  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:08.521  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22958d3f added. We now have 2 listener(s)
09-09 17:18:08.522  1036  2075 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:18:08.523  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 17:18:08.523  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:08.523  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:08.523  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:08.523  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@870860c added. We now have 9 listener(s)
09-09 17:18:08.523  6571  6647 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:08.523  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 17:18:08.525  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:18:08.527  6571  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:18:08.527  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
09-09 17:18:08.527  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:18:08.527  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:08.527  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:08.527  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:18:08.527  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:18:08.527  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:18:08.528  6571  6647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:18:08.528  6571  6647 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:18:08.528  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:08.528  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@263e496a added. We now have 3 listener(s)
09-09 17:18:08.528  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:18:08.529  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:08.530  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:08.530  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 17:18:08.530  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:08.530  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:08.530  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:08.530  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34dfbe5b added. We now have 10 listener(s)
09-09 17:18:08.530  6571  6647 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:08.530  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:18:08.530  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:18:08.530  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:18:08.530  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:18:08.530  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 17:18:08.532  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 17:18:08.532  1036  2099 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:18:08.534  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 17:18:08.534  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 17:18:08.535  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 17:18:08.535  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:18:08.536   319  8085 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-09 17:18:08.536  6571  6647 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 17:18:08.537  6571  6647 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:18:08.537  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:18:08.538  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:18:08.538  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:08.538  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.538  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:18:08.538  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:08.538  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22958d3f removed from the list
09-09 17:18:08.538  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:08.538  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@870860c removed from the list
09-09 17:18:08.538  6571  6647 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:18:08.538  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:08.538  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.538  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:08.539  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:18:08.539  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:18:08.539  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:08.539  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@870860c not in the list
09-09 17:18:08.539  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.539  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:08.540  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:18:08.540  6571  6647 D BluetoothLeScanner: could not find callback wrapper
09-09 17:18:08.540  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:18:08.540  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:18:08.540  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:08.540  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34dfbe5b removed from the list
09-09 17:18:08.540  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:08.540  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.540  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:08.540  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:08.540  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@263e496a removed from the list
09-09 17:18:08.541  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:08.541  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6f9236 added. We now have 2 listener(s)
09-09 17:18:08.541  1036  2310 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:18:08.543  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 17:18:08.543  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:08.543  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:08.543  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:08.543  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28d1e537 added. We now have 9 listener(s)
09-09 17:18:08.543  6571  6647 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:08.543  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 17:18:08.544  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:18:08.546  6571  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:18:08.546  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:08.546  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 17:18:08.546  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:08.546  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:08.546  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:18:08.546  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:18:08.546  6571  6647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:18:08.547  6571  6647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:18:08.547  6571  6647 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:18:08.548  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:08.548  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a4300d added. We now have 3 listener(s)
09-09 17:18:08.548  1036  2075 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 17:18:08.549  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:08.549  6571  6571 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:08.550  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 17:18:08.550  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:08.550  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:08.550  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:08.550  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@139a9bc2 added. We now have 10 listener(s)
09-09 17:18:08.550  6571  6647 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:08.551  6571  6647 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:18:08.551  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:18:08.551  6571  6647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:18:08.551  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:08.551  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.551  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:18:08.551  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:08.551  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6f9236 removed from the list
09-09 17:18:08.551  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:08.551  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28d1e537 removed from the list
09-09 17:18:08.551  6571  6647 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:18:08.551  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:08.552  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.552  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:08.552  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:18:08.552  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:18:08.552  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:08.552  6571  6647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28d1e537 not in the list
09-09 17:18:08.552  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.552  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:08.553  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:18:08.553  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:18:08.553  6571  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:08.553  6571  6647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@139a9bc2 removed from the list
09-09 17:18:08.553  6571  6647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:08.553  6571  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:08.553  6571  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:08.553  6571  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:08.553  6571  6647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a4300d removed from the list
09-09 17:18:08.555  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-09 17:18:08.555  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 17:18:08.555  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-09 17:18:08.555  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:18:08.555  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 17:18:08.555  6571  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 17:18:08.557  8058  8058 V Signer  : override build config not found
09-09 17:18:08.557  8058  8058 D Signer  : value of property debug is false
09-09 17:18:08.566   319   879 D LGDataListener: argv[0]=dsqncommand
09-09 17:18:08.566   319   879 D LGDataListener: argv[1]=wlan0
09-09 17:18:08.566   319   879 D LGDataListener: argv[2]=1
09-09 17:18:08.566   319   879 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-09 17:18:08.566  1036  1116 D DSQN    : DSQM DsqnNotification wlan0  1
09-09 17:18:08.566  1036  1116 D DSQN    : start to monitor internet connection
,09-09 17:18:08.569  6571  8093 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 865, name: My test thread name)
09-09 17:18:08.569  6571  8093 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 865, thread name: My test thread name)
09-09 17:18:08.569  6571  8093 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 865, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-09 17:18:08.571  6571  8094 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 867, name: My test thread name)
09-09 17:18:08.571  6571  8094 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 867, thread name: My test thread name)
09-09 17:18:08.571  6571  8094 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 867, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-09 17:18:08.572  6571  6647 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-09 17:18:08.572  6571  6647 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-09 17:18:08.572  6571  6647 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-09 17:18:08.572  6571  6647 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-09 17:18:08.572  6571  6647 D com.test.thalitest.ThaliTestRunner: Total duration: 22852 ms
09-09 17:18:08.573  6571  6647 I jxcore-log: *Native tests were executed*
09-09 17:18:08.573  6571  6647 I jxcore-log: 
09-09 17:18:08.573  6571  6647 I jxcore-log: Total number of executed tests:  80
09-09 17:18:08.573  6571  6647 I jxcore-log: 
09-09 17:18:08.573  6571  6647 I jxcore-log: Number of passed tests:  80
09-09 17:18:08.573  6571  6647 I jxcore-log: 
09-09 17:18:08.573  1036  8080 D DhcpStateMachine: DHCPV4 request on wlan0
09-09 17:18:08.573  6571  6647 I jxcore-log: Number of failed tests:  0
09-09 17:18:08.573  6571  6647 I jxcore-log: 
09-09 17:18:08.573  6571  6647 I jxcore-log: Number of ignored tests:  0
09-09 17:18:08.573  6571  6647 I jxcore-log: 
09-09 17:18:08.574  6571  6647 I jxcore-log: Total duration:  22852
09-09 17:18:08.574  6571  6647 I jxcore-log: 
09-09 17:18:08.574  6571  6647 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-09 17:18:08.574  6571  6647 I jxcore-log: 
09-09 17:18:08.574  1036  8080 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-09 17:18:08.574  1036  8080 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-09 17:18:08.574  8095  8095 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:18:08.582  6571  6571 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-09 17:18:08.574  8095  8095 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 17:18:08.576  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:08.576  6571  6647 I jxcore-log: 
09-09 17:18:08.584  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:08.584  6571  6647 I jxcore-log: 
09-09 17:18:08.585  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:08.585  6571  6647 I jxcore-log: 
09-09 17:18:08.585  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:08.585  6571  6647 I jxcore-log: 
09-09 17:18:08.586  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:08.586  6571  6647 I jxcore-log: 
09-09 17:18:08.586  8095  8095 I dhcpcd  : version 5.5.6 starting
09-09 17:18:08.587  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 17:18:08.587  6571  6647 I jxcore-log: 
09-09 17:18:08.588  8095  8095 E dhcpcd  : get_duid: m
09-09 17:18:08.588  8095  8095 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-09 17:18:08.588  8095  8095 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-09 17:18:08.588  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:18:08.588  6571  6647 I jxcore-log: 
09-09 17:18:08.590  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 17:18:08.590  6571  6647 I jxcore-log: 
09-09 17:18:08.590  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:18:08.590  6571  6647 I jxcore-log: 
09-09 17:18:08.591  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 17:18:08.591  6571  6647 I jxcore-log: 
09-09 17:18:08.591  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 17:18:08.591  6571  6647 I jxcore-log: 
09-09 17:18:08.592  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 17:18:08.592  6571  6647 I jxcore-log: 
09-09 17:18:08.593  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:18:08.593  6571  6647 I jxcore-log: 
09-09 17:18:08.593  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:18:08.593  6571  6647 I jxcore-log: 
09-09 17:18:08.593  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 17:18:08.593  6571  6647 I jxcore-log: 
09-09 17:18:08.594  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 17:18:08.594  6571  6647 I jxcore-log: 
09-09 17:18:08.594  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:18:08.594  6571  6647 I jxcore-log: 
09-09 17:18:08.595  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:18:08.595  6571  6647 I jxcore-log: 
09-09 17:18:08.595  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 17:18:08.595  6571  6647 I jxcore-log: 
09-09 17:18:08.596  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 17:18:08.596  6571  6647 I jxcore-log: 
09-09 17:18:08.596  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 17:18:08.596  6571  6647 I jxcore-log: 
09-09 17:18:08.597  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 17:18:08.597  6571  6647 I jxcore-log: 
09-09 17:18:08.597  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:08.597  6571  6647 I jxcore-log: 
09-09 17:18:08.598  1036  8079 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 15:18:08 GMT], X-Android-Received-Millis=[1473434288597], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473434288565]}
09-09 17:18:08.598  1036  8079 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-09 17:18:08.598  1036  8079 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-09 17:18:08.598  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 17:18:08.598  6571  6647 I jxcore-log: 
09-09 17:18:08.598  1036  1532 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-09 17:18:08.598  1036  1532 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-09 17:18:08.598  1036  1532 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 17:18:08.598  1036  1532 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 17:18:08.598  1036  1532 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 17:18:08.598  1036  1532 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-09 17:18:08.598  1036  1532 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-09 17:18:08.598  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:08.598  6571  6647 I jxcore-log: 
09-09 17:18:08.598  1036  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:18:08.598  1036  1532 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 17:18:08.599  1036  1532 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 17:18:08.599  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:08.599  6571  6647 I jxcore-log: 
09-09 17:18:08.599  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:08.599  6571  6647 I jxcore-log: 
09-09 17:18:08.600  6571  6647 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:08.600  6571  6647 I jxcore-log: 
09-09 17:18:08.603  1036  1532 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:18:08.604  1036  1532 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-09 17:18:08.604  1036  1525 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:18:08.604  1036  1525 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 17:18:08.604  1864  1864 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:18:08.604  1864  1864 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-09 17:18:08.605  1589  1795 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 17:18:08.606  8058  8058 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
09-09 17:18:08.606  8058  8058 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
09-09 17:18:08.606  8058  8058 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
09-09 17:18:08.607  8058  8058 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
09-09 17:18:08.607  8058  8058 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
09-09 17:18:08.607  8058  8058 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
09-09 17:18:08.607  8058  8058 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
09-09 17:18:08.607  8058  8058 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
,09-09 17:18:08.607  8058  8058 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
09-09 17:18:08.607  8058  8058 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
09-09 17:18:08.608  8058  8058 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
09-09 17:18:08.608  8058  8058 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
09-09 17:18:08.608  8058  8058 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
09-09 17:18:08.618  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 17:18:08.618  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:18:08.619  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 17:18:08.628  8058  8058 V LGMDMManager: Create singleton instance
,09-09 17:18:08.645  8095  8095 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,09-09 17:18:08.645  8095  8095 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-09 17:18:08.645  8095  8095 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-09 17:18:08.646  8095  8095 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-09 17:18:08.646  8095  8095 D dhcpcd  : wlan0: sending REQUEST (xid 0xf9203b5e), next in 3.71 seconds
,09-09 17:18:08.666  8058  8058 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,09-09 17:18:08.678  8095  8095 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-09 17:18:08.704  8058  8058 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:18:08.705  8058  8106 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-09 17:18:08.712  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 17:18:08.718  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:18:08.724  7624  7624 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 17:18:08.727  8095  8095 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-09 17:18:08.727  8095  8095 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-09 17:18:08.728  8095  8095 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-09 17:18:08.728  8095  8095 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-09 17:18:08.728  7624  7624 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:18:08.728  8095  8095 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-09 17:18:08.729  8095  8095 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-09 17:18:08.729  8095  8095 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-09 17:18:08.729  8095  8095 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-09 17:18:08.747  7624  7624 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-09 17:18:08.756  8058  8058 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:18:08.756  8058  8106 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 17:18:08.763  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:18:08.767  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:18:08.771  7624  7624 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:18:08.771  7624  7624 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:18:08.772  7624  7624 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 17:18:08.774  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,09-09 17:18:08.827  6751  6751 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-09 17:18:08.878  8058  8058 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 17:18:08.878  8058  8106 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 17:18:08.879  8103  8103 D AndroidRuntime: 
09-09 17:18:08.879  8103  8103 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-09 17:18:08.879  8058  8105 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-09 17:18:08.881  8103  8103 D AndroidRuntime: CheckJNI is OFF
09-09 17:18:08.881  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 17:18:08.885  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:18:08.889  7624  7624 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:18:08.889  7624  7624 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:18:08.889  7624  7624 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 17:18:08.891  6751  6751 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-09 17:18:08.891  6751  6751 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 17:18:08.891  6751  6751 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 17:18:08.891  6751  6751 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-09 17:18:08.891  6751  6751 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-09 17:18:08.892  6751  6751 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,09-09 17:18:08.892  6751  6751 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-09 17:18:08.892  6751  6751 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 17:18:08.892  6751  6751 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 17:18:08.892  6751  6751 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 17:18:08.892  6751  6751 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-09 17:18:08.892  6751  6751 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-09 17:18:08.900  8058  8058 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:18:08.900  8058  8106 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 17:18:08.905  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 17:18:08.908  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:18:08.912  7624  7624 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:18:08.912  7624  7624 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:18:08.912  7624  7624 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 17:18:08.915  8058  8058 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:18:08.916  8058  8106 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 17:18:08.919  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:18:08.927  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:18:08.930  7624  7624 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 17:18:08.930  7624  7624 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:18:08.930  7624  7624 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 17:18:08.932  8058  8058 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:18:08.932  8058  8106 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 17:18:08.935  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:18:08.939  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:18:08.943  7624  7624 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:18:08.944  7624  7624 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:18:08.944  7624  7624 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 17:18:08.946  8058  8058 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:18:08.947  8058  8106 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-09 17:18:08.953  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:18:08.960  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:18:08.963  7624  7624 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:18:08.964  7624  7624 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:18:08.964  7624  7624 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 17:18:08.970  8058  8058 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 17:18:08.973  8058  8106 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 17:18:08.976  1036  8080 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-09 17:18:08.977  1036  8080 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-09 17:18:08.977  1036  8080 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-09 17:18:08.977  1036  8080 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-09 17:18:08.977  1036  8080 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-09 17:18:08.977  1036  8080 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 17:18:08.977  1036  8080 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-09 17:18:08.977  1036  8080 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-09 17:18:08.977  1036  8080 D DhcpStateMachine: RunningState
09-09 17:18:08.979  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 17:18:08.983  8103  8103 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-09 17:18:08.986  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:18:08.990  1036  1103 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
09-09 17:18:08.990  1036  1103 I ActivityManager: Killing 6571:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
09-09 17:18:08.992  7624  7624 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:18:08.992  7624  7624 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:18:08.996  7624  7624 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 17:18:09.022  1036  2310 I WindowState: WIN DEATH: Window{af1eead u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-09 17:18:09.022  1036  1531 D WifiService: Client connection lost with reason: 4
,09-09 17:18:09.028  1036  2310 D InputDispatcher: Window went away: Window{af1eead u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-09 17:18:09.204  1036  1103 I ActivityManager:   Force finishing activity ActivityRecord{192b4993 u0 com.test.thalitest/.MainActivity t6}
,09-09 17:18:09.238   339   377 E GBMv2   : DFP En is all cleared set to be enabled
,09-09 17:18:09.244  1036  1910 W ActivityManager: Spurious death for ProcessRecord{3607a305 6571:com.test.thalitest/u0a118}, curProc for 6571: null
09-09 17:18:09.245  1036  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-09 17:18:09.247  1036  1124 I ActivityManager:   Force finishing activity ActivityRecord{192b4993 u0 com.test.thalitest/.MainActivity t6 f}
09-09 17:18:09.247  1036  1124 W ActivityManager: Duplicate finish request for ActivityRecord{192b4993 u0 com.test.thalitest/.MainActivity t6 f}
,09-09 17:18:09.271  2082  2082 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-09 17:18:09.272  1959  1979 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-09 17:18:09.273  1959  1979 D SplitWindowPolicy: topRunningActivity=ActivityInfo{179b84a0 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,09-09 17:18:09.275  2082  2082 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-09 17:18:09.280  1959  3957 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-09 17:18:09.280  1959  3957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{23606859 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-09 17:18:09.282  2026  2026 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-09 17:18:09.283  1036  1412 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-09 17:18:09.283  3798  3798 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
09-09 17:18:09.285  2491  2612 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-09 17:18:09.285  4493  4493 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-09 17:18:09.286  4493  4493 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
,09-09 17:18:09.286  4493  4493 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-09 17:18:09.286  4493  4493 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-09 17:18:09.286  4493  4493 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 17:18:09.286  4493  4493 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 17:18:09.286  4493  4493 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 17:18:09.286  4493  4493 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 17:18:09.286  4493  4493 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:18:09.286  4493  4493 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:18:09.286  4493  4493 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 17:18:09.286  1589  1589 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-09 17:18:09.286  4493  4493 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-09 17:18:09.289  7596  7596 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-09 17:18:09.289  7596  7596 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-09 17:18:09.303  8058  8058 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 17:18:09.303  2082  2082 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-09 17:18:09.304  8058  8106 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 17:18:09.304  2082  2164 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
09-09 17:18:09.328  4596  4596 I art     : Explicit concurrent mark sweep GC freed 8186(467KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 533us total 66.149ms
,09-09 17:18:09.340  1036  2075 V SIM_STK : Menu title from STK is T-Mobile
,09-09 17:18:09.352  1036  1101 W InputMethodInfo: Duplicated subtype definition found: , voice
,09-09 17:18:09.368  1036  1036 D administrator: Handling package changes for user 0
,09-09 17:18:09.375  2082  2082 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
09-09 17:18:09.377  1916  1916 D ActionManagerService: notifyUserLog: 1000003
09-09 17:18:09.377  3798  4482 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-09 17:18:09.379  1589  1589 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-09 17:18:09.381  2082  2082 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,09-09 17:18:09.388  2082  2082 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-09 17:18:09.388  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 17:18:09.393  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 17:18:09.408  2082  2082 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,09-09 17:18:09.421  2082  2082 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,09-09 17:18:09.421  1916  1916 D ActionManagerService: notifyUserLog: 1000004
09-09 17:18:09.423  3798  4482 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-09 17:18:09.423  3798  4478 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-09 17:18:09.423  1589  1589 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-09 17:18:09.423  1589  1589 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-09 17:18:09.426  2082  2082 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-09 17:18:09.426  2082  2082 I GBoardWebViewUtils: , create_time: 1430832262123
09-09 17:18:09.426  2082  2082 I GBoardWebViewUtils: , expire_time: 0
09-09 17:18:09.426  2082  2082 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-09 17:18:09.426  2082  2082 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-09 17:18:09.426  2082  2082 I GBoardWebViewUtils: , display: false
09-09 17:18:09.426  2082  2082 I GBoardWebViewUtils: , animation: false }
09-09 17:18:09.426  2082  2082 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-09 17:18:09.426  2082  2082 I GBoardWebViewUtils: , create_time: 1430832262287
09-09 17:18:09.426  2082  2082 I GBoardWebViewUtils: , expire_time: 0
09-09 17:18:09.426  2082  2082 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-09 17:18:09.426  2082  2082 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-09 17:18:09.426  2082  2082 I GBoardWebViewUtils: , display: false
09-09 17:18:09.426  2082  2082 I GBoardWebViewUtils: , animation: false }
09-09 17:18:09.426  2082  2082 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1473420112499
09-09 17:18:09.426  2082  2082 I GBoardWebViewUtils: , create_time: 1473420113195
09-09 17:18:09.426  2082  2082 I GBoardWebViewUtils: , expire_time: 0
09-09 17:18:09.426  2082  2082 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-09 17:18:09.426  2082  2082 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-09 17:18:09.426  2082  2082 I GBoardWebViewUtils: , display: false
09-09 17:18:09.426  2082  2082 I GBoardWebViewUtils: , animation: false }
,09-09 17:18:09.430  1589  1637 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-09 17:18:09.430  1589  1637 D KeyguardModel: createShortcutInfo...
09-09 17:18:09.437  1589  1637 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-09 17:18:09.437  1589  1637 D KeyguardModel: createShortcutInfo...
09-09 17:18:09.446  1036  2310 V SIM_STK : Menu title from STK is T-Mobile
09-09 17:18:09.446  1036  2310 V SIM_STK : Menu title from STK is T-Mobile
09-09 17:18:09.450  2082  2082 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-09 17:18:09.450  2082  2082 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-09 17:18:09.452  2082  8150 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-09 17:18:09.455  1589  1637 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-09 17:18:09.455  1589  1637 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 17:18:09.456  1589  1637 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-09 17:18:09.458  1589  1637 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-09 17:18:09.458  1589  1637 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 17:18:09.458  1589  1637 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-09 17:18:09.460  1589  1637 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-09 17:18:09.460  1589  1637 D KeyguardModel: createShortcutInfo...
09-09 17:18:09.463  1589  1637 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-09 17:18:09.463  1589  1637 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 17:18:09.465  7624  7624 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:18:09.465  7624  7624 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:18:09.465  7624  7624 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 17:18:09.472  1589  1637 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 17:18:09.472  1589  1637 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-09 17:18:09.481  1589  1637 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-09 17:18:09.481  1589  1637 D KeyguardModel: createShortcutInfo...
09-09 17:18:09.482  1881  1881 D SplitUIManager: split_name #11 / not available #0
09-09 17:18:09.482  1881  1881 D SplitUIService: removed split : 
09-09 17:18:09.496  1589  1637 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 17:18:09.496  1589  1637 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-09 17:18:09.497  1589  1637 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-09 17:18:09.497  1589  1637 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-09 17:18:09.499  1036  1562 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-09 17:18:09.500  1589  1637 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 17:18:09.500  7596  7596 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-09 17:18:09.500  1589  1637 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-09 17:18:09.500  7596  7596 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-09 17:18:09.500  7596  7596 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-09 17:18:09.500  7596  7596 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-09 17:18:09.500  7596  7596 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-09 17:18:09.500  7596  7596 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 17:18:09.500  7596  7596 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-09 17:18:09.500  7596  7596 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-09 17:18:09.500  7596  7596 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-09 17:18:09.500  7596  7596 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 17:18:09.500  7596  7596 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-09 17:18:09.500  8058  8058 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:18:09.500  8058  8106 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 17:18:09.509  8007  8007 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-09 17:18:09.514  1589  1637 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-09 17:18:09.514  1589  1637 D KeyguardModel: createShortcutInfo...
,09-09 17:18:09.516  8007  8007 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-09 17:18:09.522  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 17:18:09.524  1589  1589 D KeyguardModel: handleShortcutListChanged...
09-09 17:18:09.524  1589  1589 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-09 17:18:09.528  1881  1881 D SplitUIManager: split_name #11 / not available #0
09-09 17:18:09.529  1881  1881 I SplitUIService: split app #11
,09-09 17:18:09.531  1589  1637 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-09 17:18:09.531  1589  1637 D KeyguardModel: createShortcutInfo...
09-09 17:18:09.533  1589  1637 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-09 17:18:09.533  1589  1637 D KeyguardModel: createShortcutInfo...
09-09 17:18:09.534  1589  1637 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 17:18:09.534  1589  1637 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-09 17:18:09.535  1589  1637 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-09 17:18:09.535  1589  1637 D KeyguardModel: createShortcutInfo...
09-09 17:18:09.535  1036  1952 V SIM_STK : Menu title from STK is T-Mobile
09-09 17:18:09.536  1589  1637 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 17:18:09.536  1589  1637 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-09 17:18:09.545  8058  8105 D LgDataFeature: LgDataFeature() Constructor: none
09-09 17:18:09.545  8058  8105 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 17:18:09.550  1589  1637 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-09 17:18:09.550  1589  1637 D KeyguardModel: createShortcutInfo...
09-09 17:18:09.551  1589  1637 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 17:18:09.551  1589  1637 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-09 17:18:09.551  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:18:09.552  1589  1637 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-09 17:18:09.552  1589  1637 D KeyguardModel: createShortcutInfo...
09-09 17:18:09.558  1036  1124 I art     : Explicit concurrent mark sweep GC freed 76611(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 3.104ms total 143.545ms
,09-09 17:18:09.560  7624  7624 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:18:09.560  7624  7624 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:18:09.561  7624  7624 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-09 17:18:09.561  7624  7624 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-09 17:18:09.562  7624  7624 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-09 17:18:09.567  8058  8058 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 17:18:09.568  8058  8106 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-09 17:18:09.577   333   421 I ThermalEngine: Thermal-Server: Thermal received msg from  override
09-09 17:18:09.578  3233  8154 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-09 17:18:09.579  8007  8007 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-09 17:18:09.579  8007  8007 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-09 17:18:09.580  1589  1589 D KeyguardModel: handleShortcutListChanged...
09-09 17:18:09.580  1589  1589 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,09-09 17:18:09.582  6751  6751 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 17:18:09.589  6751  6751 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 17:18:09.593  7624  7624 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 17:18:09.593  7624  7624 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 17:18:09.593  7624  7624 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-09 17:18:09.594  7624  7624 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-09 17:18:09.594  7624  7624 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-09 17:18:09.596  8058  8058 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,09-09 17:18:09.607  8058  8058 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-09 17:18:09.608  8058  8058 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-09 17:18:09.610  8058  8058 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-09 17:18:09.612  8058  8058 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,09-09 17:18:09.613  8058  8058 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-09 17:18:09.616  8058  8058 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-09 17:18:09.619  8058  8058 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-09 17:18:09.621  8058  8058 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-09 17:18:09.621  8058  8106 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-09 17:18:09.622  1036  1952 I ActivityManager: Killing 7144:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,09-09 17:18:09.628  2082  2082 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
09-09 17:18:09.630  2082  2082 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 17:18:09.630  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-09 17:18:09.630  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-09 17:18:09.630  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-09 17:18:09.631  2082  2082 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-09 17:18:09.632  2082  2082 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-09 17:18:09.633  2082  2082 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-09 17:18:09.634  2082  2082 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,09-09 17:18:09.652  2082  2082 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-09 17:18:09.654  2082  2082 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-09 17:18:09.654  2082  2082 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 17:18:09.656  2082  2270 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-09 17:18:09.656  2082  2270 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-09 17:18:09.669  2082  2082 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,09-09 17:18:09.669  8103  8103 D AndroidRuntime: Shutting down VM
09-09 17:18:09.671  2082  2082 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-09 17:18:09.671  2082  2082 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 17:18:09.679  2082  2082 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-09 17:18:09.687  8058  8105 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,09-09 17:18:09.720  1036  1101 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 17:18:09.724  1036  1101 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-09 17:18:09.728  1829  1829 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-09 17:18:09.729  1036  1562 W libprocessgroup: failed to open /acct/uid_10005/pid_7144/cgroup.procs: No such file or directory
,09-09 17:18:09.758  1036  1124 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8158 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-09 17:18:09.759  2642  2642 D [Concierge]Service: onStartCommand(). Type : 8
09-09 17:18:09.759  2642  2642 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-09 17:18:09.760  1036  1564 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-09 17:18:09.761  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{15e65773 u0 com.lge.launcher2/.Launcher t5} time:141094
09-09 17:18:09.761  2082  2082 D [Concierge]WidgetView: change position of spinner
09-09 17:18:09.764  2642  2642 D [Concierge]Service: Update widget ID : 11
09-09 17:18:09.765  2082  2082 I [Concierge]WidgetView: initWebView(). Time : 1473434289765
09-09 17:18:09.765  2642  2642 D [Concierge]Service: onStartCommand(). Type : 0
09-09 17:18:09.766  2229  2229 I ConfigService: onCreate
09-09 17:18:09.768  2229  2229 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-09 17:18:09.769  1829  1829 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,09-09 17:18:09.772  2229  2229 I ConfigService: onBind returning update interface
09-09 17:18:09.773  2229  2229 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-09 17:18:09.773  2229  2229 I ConfigService: onBind returning config service
09-09 17:18:09.779  8058  8105 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,09-09 17:18:09.786  8058  8105 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
09-09 17:18:09.787  8058  8105 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-09 17:18:09.790  8058  8105 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-09 17:18:09.791  2229  2229 I ConfigService: onDestroy
09-09 17:18:09.792  8058  8105 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
09-09 17:18:09.792  8058  8105 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
09-09 17:18:09.792  1829  8176 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-09 17:18:09.793  2082  2082 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 332536219
09-09 17:18:09.794  2082  2082 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-09 17:18:09.794  2082  2082 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-09 17:18:09.794  8058  8105 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,09-09 17:18:09.795  8058  8105 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
09-09 17:18:09.796  2082  2082 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1f81d815
09-09 17:18:09.797  2082  2082 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-09 17:18:09.797  2082  2082 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-09 17:18:09.798  2082  2082 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 17:18:09.804  2082  2082 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-09 17:18:09.804  2082  2082 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-09 17:18:09.804  2082  2082 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-09 17:18:09.805  2082  2082 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,09-09 17:18:09.806  2082  2082 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473434176735, New one : 1473434289765
,09-09 17:18:09.806  2082  2082 D [Concierge]WidgetView: Unregister all receivers
09-09 17:18:09.806  2082  2082 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-09 17:18:09.806  2082  2082 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 17:18:09.808  2082  2082 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-09 17:18:09.809  2082  2082 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-09 17:18:09.810  2082  2082 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-09 17:18:09.811  2082  2082 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-09 17:18:09.812  2082  2082 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
09-09 17:18:09.814  2082  2082 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 17:18:09.814  2082  2082 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 17:18:09.830  5977  8185 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,09-09 17:18:09.836  1829  8186 I PeopleContactsSync: CP2 sync disabled
,09-09 17:18:09.845  1829  4790 I Icing   : doRemovePackageData com.test.thalitest
09-09 17:18:09.855  1829  8184 W GmsApplication: Using Auth Proxy for data requests.
,09-09 17:18:09.859  1829  8184 W GmsApplication: Using Auth Proxy for data requests.
09-09 17:18:09.860  2082  2082 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-09 17:18:09.860  6945  6945 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
09-09 17:18:09.868  2082  2082 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,09-09 17:18:09.868  2082  2082 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,09-09 17:18:09.869  1036  1978 I ActivityManager: Killing 7677:com.google.android.talk/u0a72 (adj 15): empty #17
09-09 17:18:09.869  2082  2082 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 17:18:09.888  2082  2082 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@ec090d4 time:141221
,09-09 17:18:09.959  1036  1768 W libprocessgroup: failed to open /acct/uid_10072/pid_7677/cgroup.procs: No such file or directory
,09-09 17:18:09.966  2173  8190 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-09 17:18:09.984  2173  8190 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM voicemail_status WHERE (((source_package = 'com.test.thalitest')))] disk I/O error
--------- beginning of crash
09-09 17:18:09.985  2173  8190 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-09 17:18:09.985  2173  8190 E AndroidRuntime: Process: android.process.acore, PID: 2173
09-09 17:18:09.985  2173  8190 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 17:18:09.985  2173  8190 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 17:18:09.985  2173  8190 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
09-09 17:18:09.985  2173  8190 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
09-09 17:18:09.985  2173  8190 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 17:18:09.985  2173  8190 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
09-09 17:18:09.985  2173  8190 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
09-09 17:18:09.985  2173  8190 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailStatusTable.delete(VoicemailStatusTable.java:100)
09-09 17:18:09.985  2173  8190 E AndroidRuntime: ,	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
09-09 17:18:09.985  2173  8190 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
09-09 17:18:09.985  2173  8190 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
09-09 17:18:09.985  2173  8190 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:52)
09-09 17:18:09.985  2173  8190 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-09 17:18:09.985  2173  8190 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-09 17:18:09.985  2173  8190 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:09.985  2173  8190 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
09-09 17:18:09.985  2173  8190 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 17:18:09.998  1036  1952 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8191 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-09 17:18:10.002  2173  8190 I Process : Sending signal. PID: 2173 SIG: 9
09-09 17:18:10.010  2082  2082 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,09-09 17:18:10.012  1036  8208 E DropBoxManagerService: Can't write: system_app_crash
09-09 17:18:10.012  1036  8208 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-09 17:18:10.012  1036  8208 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-09 17:18:10.012  1036  8208 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 17:18:10.012  1036  8208 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 17:18:10.012  1036  8208 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 17:18:10.012  1036  8208 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-09 17:18:10.012  1036  8208 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
09-09 17:18:10.012  1036  8208 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 17:18:10.012  1036  8208 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 17:18:10.012  1036  8208 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 17:18:10.012  1036  8208 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-09 17:18:10.012  1036  8208 E DropBoxManagerService: 	... 5 more
09-09 17:18:10.029  8058  8180 W BulkCursor: Remote process exception when closing
,09-09 17:18:10.030  8191  8191 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 17:18:10.030  8191  8191 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 17:18:10.031  8191  8191 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 17:18:10.031  8191  8191 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-09 17:18:10.053  2082  2901 I GBoardtInterface: onReloaded()
,09-09 17:18:10.055  2082  2082 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
09-09 17:18:10.067  1036  2075 I ActivityManager: Process android.process.acore (pid 2173) has died
,09-09 17:18:10.068  8191  8191 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/Downloads.db'.
09-09 17:18:10.068  8191  8191 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:10.068  8191  8191 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:18:10.068  8191  8191 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-09 17:18:10.068  8191  8191 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-09 17:18:10.068  8191  8191 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 17:18:10.068  8191  8191 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 17:18:10.068  8191  8191 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 17:18:10.068  8191  8191 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-09 17:18:10.068  8191  8191 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-09 17:18:10.068  8191  8191 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-09 17:18:10.068  8191  8191 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-09 17:18:10.068  8191  8191 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-09 17:18:10.068  8191  8191 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:18:10.068  8191  8191 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 17:18:10.068  8191  8191 E SQLiteDatabase: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
09-09 17:18:10.068  8191  8191 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
09-09 17:18:10.068  8191  8191 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
09-09 17:18:10.068  8191  8191 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
09-09 17:18:10.068  8191  8191 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-09 17:18:10.068  8191  8191 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-09 17:18:10.068  8191  8191 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-09 17:18:10.068  8191  8191 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-09 17:18:10.068  8191  8191 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:10.068  8191  8191 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-09 17:18:10.068  8191  8191 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 17:18:10.068  8191  8191 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:18:10.068  8191  8191 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:18:10.068  8191  8191 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 17:18:10.068  8191  8191 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 17:18:10.068  8191  8191 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:10.068  8191  8191 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:18:10.068  8191  8191 W System.err: 	at a,ndroid.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-09 17:18:10.068  1036  2075 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/com.lge.providers.contacts.AliveAcoreService in 1000ms
09-09 17:18:10.068  8191  8191 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-09 17:18:10.068  8191  8191 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 17:18:10.068  8191  8191 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 17:18:10.068  1036  2075 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.voicemail.VoicemailCleanupService in 11000ms
09-09 17:18:10.068  8191  8191 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 17:18:10.068  8191  8191 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-09 17:18:10.068  8191  8191 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-09 17:18:10.068  8191  8191 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-09 17:18:10.068  8191  8191 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-09 17:18:10.068  8191  8191 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-09 17:18:10.068  8191  8191 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:18:10.068  8191  8191 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 17:18:10.068  8191  8191 W System.err: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
09-09 17:18:10.069  8191  8191 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
09-09 17:18:10.069  1036  2075 I ActivityManager: Killing 8058:com.wsandroid.suite.lge/1000 (adj 11): depends on provider com.android.providers.contacts/.ContactsProvider2ForLG in dying proc android.process.acore
09-09 17:18:10.069  8191  8191 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
09-09 17:18:10.069  8191  8191 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
09-09 17:18:10.069  8191  8191 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-09 17:18:10.069  8191  8191 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-09 17:18:10.069  8191  8191 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-09 17:18:10.069  8191  8191 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-09 17:18:10.069  8191  8191 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:10.069  8191  8191 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 17:18:10.069  8191  8191 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 17:18:10.069  8191  8191 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:18:10.069  8191  8191 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:18:10.069  8191  8191 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 17:18:10.069  8191  8191 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 17:18:10.073  8191  8191 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/sqt.db'.
09-09 17:18:10.073  8191  8191 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:10.073  8191  8191 E SQLiteDatabase: 	at an,droid.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:18:10.073  8191  8191 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-09 17:18:10.073  8191  8191 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-09 17:18:10.073  8191  8191 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 17:18:10.073  8191  8191 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 17:18:10.073  8191  8191 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 17:18:10.073  8191  8191 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-09 17:18:10.073  8191  8191 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-09 17:18:10.073  8191  8191 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-09 17:18:10.073  8191  8191 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-09 17:18:10.073  8191  8191 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-09 17:18:10.073  8191  8191 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:18:10.073  8191  8191 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 17:18:10.073  8191  8191 E SQLiteDatabase: 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
09-09 17:18:10.073  8191  8191 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
09-09 17:18:10.073  8191  8191 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
09-09 17:18:10.073  8191  8191 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
09-09 17:18:10.073  8191  8191 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-09 17:18:10.073  8191  8191 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-09 17:18:10.073  8191  8191 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-09 17:18:10.073  8191  8191 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-09 17:18:10.073  8191  8191 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:10.073  8191  8191 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-09 17:18:10.073  8191  8191 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 17:18:10.073  8191  8191 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:18:10.073  8191  8191 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:18:10.073  8191  8191 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 17:18:10.073  8191  8191 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 17:18:10.073  8191  8191 D AndroidRuntime: Shutting down VM
09-09 17:18:10.074  8191  8191 E AndroidRuntime: FATAL EXCEPTION: main
09-09 17:18:10.074  8191  8191 E AndroidRuntime: Process: com.lge.email, PID: 8191
09-09 17:18:10.074  8191  8191 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.lge.email.providers.sqt.SqtProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:10.074  8191  8191 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5017)
09-09 17:18:10.074  8191  8191 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-09 17:18:10.074  8191  8191 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-09 17:18:10.074  8191  8191 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-09 17:18:10.074  8191  8191 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-09 17:18:10.074  8191  8191 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:10.074  8191  8191 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
09-09 17:18:10.074  8191  8191 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 17:18:10.074  8191  8191 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:18:10.074  8191  8191 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:18:10.074  8191  8191 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 17:18:10.074  8191  8191 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 17:18:10.074  8191  8191 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:10.074  8191  8191 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:18:10.074  8191  8191 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-09 17:18:10.074  8191  8191 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-09 17:18:10.074  8191  8191 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 17:18:10.074  8191  8191 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 17:18:10.074  8191  8191 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 17:18:10.074  8191  8191 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-09 17:18:10.074  8191  8191 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-09 17:18:10.074  8191  8191 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-09 17:18:10.074  8191  8191 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-09 17:18:10.074  8191  8191 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-09 17:18:10.074  8191  8191 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:18:10.074  8191  8191 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 17:18:10.074  8191  8191 E AndroidRuntime: 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
09-09 17:18:10.074  8191  8191 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
09-09 17:18:10.074  8191  8191 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
09-09 17:18:10.074  8191  8191 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
09-09 17:18:10.074  8191  8191 E AndroidRuntime: 	... 11 more
09-09 17:18:10.099  3798  3813 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-09 17:18:10.101  1036  1952 W libprocessgroup: failed to open /acct/uid_1000/pid_8058/cgroup.procs: No such file or directory
09-09 17:18:10.102  1036  8212 E DropBoxManagerService: Can't write: system_app_crash
09-09 17:18:10.102  1036  8212 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-09 17:18:10.102  1036  8212 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-09 17:18:10.102  1036  8212 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 17:18:10.102  1036  8212 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 17:18:10.102  1036  8212 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 17:18:10.102  1036  8212 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-09 17:18:10.102  1036  8212 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
09-09 17:18:10.102  1036  8212 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 17:18:10.102  1036  8212 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 17:18:10.102  1036  8212 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 17:18:10.102  1036  8212 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-09 17:18:10.102  1036  8212 E DropBoxManagerService: 	... 5 more
09-09 17:18:10.105  8191  8191 I Process : Sending signal. PID: 8191 SIG: 9
09-09 17:18:10.105  3798  4478 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-09 17:18:10.111  1916  1916 D ActionManagerService: notifyUserLog: 1000001
,09-09 17:18:10.114  3798  4482 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-09 17:18:10.114  3798  4482 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-09 17:18:10.114  7752  7752 E SharedPreferencesImpl: Couldn't rename file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml to backup file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml.bak
09-09 17:18:10.116  2026  2026 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-09 17:18:10.116  2026  2026 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
09-09 17:18:10.117  2026  2026 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
09-09 17:18:10.145  1036  1994 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.mcafee.cloudscan.mc20.CloudScanReceiver: pid=8213 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-09 17:18:10.157  1036  1978 I ActivityManager: Process com.lge.email (pid 8191) has died
09-09 17:18:10.158  1916  1916 D ActionManagerService: notifyUserLog: 1000001
09-09 17:18:10.160  3798  4482 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-09 17:18:10.160  3798  4482 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-09 17:18:10.160  3798  4482 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-09 17:18:10.160  3798  4482 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-09 17:18:10.161  3798  3813 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-09 17:18:10.161  1829  8179 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
09-09 17:18:10.162  1829  8179 E DriveAsyncService: disk I/O error (code 3850)
09-09 17:18:10.162  1829  8179 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 17:18:10.162  1829  8179 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-09 17:18:10.162  1829  8179 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
09-09 17:18:10.162  1829  8179 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-09 17:18:10.162  1829  8179 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-09 17:18:10.162  1829  8179 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-09 17:18:10.162  1829  8179 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
09-09 17:18:10.162  1829  8179 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.c(SourceFile:438)
09-09 17:18:10.162  1829  8179 E DriveAsyncService: 	at com.google.android.gms.drive.database.d.g(SourceFile:1384)
09-09 17:18:10.162  1829  8179 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.al.a(SourceFile:15)
09-09 17:18:10.162  1829  8179 E DriveAsyncService: 	at com.google.android.gms.common.service.c.onHandleIntent(SourceFile:60)
09-09 17:18:10.162  1829  8179 E DriveAsyncService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-09 17:18:10.162  1829  8179 E DriveAsyncService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:10.162  1829  8179 E DriveAsyncService: 	at android.os.Looper.loop(Looper.java:135)
09-09 17:18:10.162  1829  8179 E DriveAsyncService: 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
