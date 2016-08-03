#### Test 79689775e33639d_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main,
08-03 17:29:25.956   873  1981 D NetlinkSocketObserver: NeighborEvent{elapsedMs=392372, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
08-03 17:29:26.671  3803  3803 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-03 17:29:26.675  3803  3803 D AndroidRuntime: CheckJNI is OFF
08-03 17:29:26.710  3803  3803 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-03 17:29:26.752  3803  3803 I Radio-JNI: register_android_hardware_Radio DONE
08-03 17:29:26.772  3803  3803 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-03 17:29:26.776   873  3016 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-03 17:29:26.837   873  3016 I ActivityManager: Start proc 3812:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-03 17:29:26.841  3803  3803 D AndroidRuntime: Shutting down VM
08-03 17:29:26.961  3812  3812 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-03 17:29:26.985  3812  3812 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-03 17:29:26.992  3812  3812 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3407-3410)
08-03 17:29:26.992  3812  3812 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 17:29:27.007  3812  3812 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6c2d530}
08-03 17:29:27.007  3812  3812 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 17:29:27.007  3812  3812 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-03 17:29:27.016  3812  3812 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-03 17:29:27.018  3812  3812 E SysUtils: ApplicationContext is null in ApplicationStatus
08-03 17:29:27.036  3812  3812 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-03 17:29:27.046  3812  3812 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-03 17:29:27.046  3812  3812 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-03 17:29:27.047  3812  3812 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-03 17:29:27.047  3812  3812 I Adreno  : Build Date                       : 10/20/15
08-03 17:29:27.047  3812  3812 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-03 17:29:27.047  3812  3812 I Adreno  : Local Branch                     : M14
08-03 17:29:27.047  3812  3812 I Adreno  : Remote Branch                    : 
08-03 17:29:27.047  3812  3812 I Adreno  : Remote Branch                    : 
08-03 17:29:27.047  3812  3812 I Adreno  : Reconstruct Branch               : 
,08-03 17:29:27.096   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@493f90:true
,08-03 17:29:27.140  3812  3812 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-03 17:29:27.155  3812  3812 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-03 17:29:27.199  3812  3849 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-03 17:29:27.215  3812  3836 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-03 17:29:27.250  3812  3849 I OpenGLRenderer: Initialized EGL, version 1.4
,08-03 17:29:27.270  1644  1644 I Keyboard.Facilitator: onFinishInput()
,08-03 17:29:27.326   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +418ms (total +514ms)
,08-03 17:29:27.373  3812  3812 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3812
,08-03 17:29:27.521  3812  3812 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-03 17:29:27.703  3812  3850 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1656837840
,08-03 17:29:27.712  3812  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-03 17:29:27.712  3812  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-03 17:29:27.712  3812  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-03 17:29:27.712  3812  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-03 17:29:27.712  3812  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-03 17:29:27.712  3812  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@feee887 added. We now have 1 listener(s)
,08-03 17:29:27.716  3812  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-03 17:29:27.716  3812  3850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-03 17:29:27.717  3812  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 17:29:27.717  3812  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-03 17:29:27.722  3812  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-03 17:29:27.722  3812  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-03 17:29:27.722  3812  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-03 17:29:27.722  3812  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-03 17:29:27.722  3812  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-03 17:29:27.722  3812  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-03 17:29:27.722  3812  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-03 17:29:27.722  3812  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-03 17:29:27.722  3812  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-03 17:29:27.722  3812  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-03 17:29:27.722  3812  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-03 17:29:27.722  3812  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-03 17:29:27.722  3812  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-03 17:29:27.722  3812  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-03 17:29:27.722  3812  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79cb352 added. We now have 1 listener(s)
,08-03 17:29:27.722  3812  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 17:29:27.728   873  1308 D WifiService: New client listening to asynchronous messages
,08-03 17:29:27.731  3812  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-03 17:29:27.732  3812  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-03 17:29:27.733  3812  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-03 17:29:27.733  3812  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-03 17:29:27.734  3812  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-03 17:29:27.741  3812  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 17:29:27.742  3812  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-03 17:29:27.751  3812  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-03 17:29:27.751  3812  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 17:29:27.751  3812  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 17:29:27.751  3812  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 17:29:27.751  3812  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 17:29:27.751  3812  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 17:29:27.751  3812  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 17:29:27.751  3812  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 17:29:27.751  3812  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 17:29:27.752  3812  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-03 17:29:27.752  3812  3850 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 17:29:27.753  3812  3850 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-03 17:29:27.755  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 17:29:27.757  3812  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 17:29:27.807  3812  3812 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-03 17:29:28.799  3812  3859 W jxcore-log: Initializing JXcore engine
,08-03 17:29:28.799  3812  3859 W jxcore-log: JXcore engine is ready
,08-03 17:29:28.835  3859  3859 W Thread-346: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8942 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-03 17:29:28.838  3859  3859 W Thread-346: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12107]" dev="sockfs" ino=12107 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-03 17:29:28.838  3859  3859 W Thread-346: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-03 17:29:28.838  3859  3859 W Thread-346: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27928]" dev="sockfs" ino=27928 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-03 17:29:28.849  3812  3859 W jxcore-log: Starting JXcore engine
,08-03 17:29:28.929  3812  3859 W jxcore-log: Platform android
08-03 17:29:28.929  3812  3859 W jxcore-log: 
,08-03 17:29:28.929  3812  3859 W jxcore-log: Process ARCH arm
08-03 17:29:28.929  3812  3859 W jxcore-log: 
,08-03 17:29:29.145  3812  3859 I jxcore-log: JXcore Cordova bridge is ready!
08-03 17:29:29.145  3812  3859 I jxcore-log: 
,08-03 17:29:29.145  3812  3859 W jxcore-log: JXcore engine is started
,08-03 17:29:29.157  3812  3850 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-03 17:29:29.165  3812  3812 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-03 17:29:29.194  3812  3859 E jxcore  : Error!: syntax error
08-03 17:29:29.194  3812  3859 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"591","_columnNumber":"9","_msg":"    at $w.prototype._compile@module.js:591:9"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"407","_columnNumber":"1","_msg":"    at $w._load@module.js:407:1"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:260:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,08-03 17:29:29.203  3812  3812 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "syntax error\nSyntaxError: syntax error\n    at $w.prototype._compile@module.js:591:9\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1\n    at $w._load@module.js:407:1\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at internal_methods.loadMainFile@main.js:260:5\n    at JXMobile.executeJSON@main.js:279:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (57)
,08-03 17:29:29.204  3812  3812 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,08-03 17:29:29.210   873  1813 I ActivityManager: Killing 2911:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-03 17:29:29.255  3812  3812 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-03 17:29:29.256  3812  3812 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,08-03 17:29:29.257  3812  3812 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-03 17:29:29.257  3812  3812 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 17:29:29.257  3812  3812 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 17:29:29.258  3812  3812 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 17:29:29.258  3812  3812 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@feee887 removed from the list
08-03 17:29:29.258  3812  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 17:29:29.259  3812  3812 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79cb352 removed from the list
,08-03 17:29:29.259  3812  3812 D io.jxcore.node.ConnectivityMonitor: stop
08-03 17:29:29.259  3812  3812 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,08-03 17:29:29.260  3812  3850 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 56ms. Plugin should use CordovaInterface.getThreadPool().
,08-03 17:29:29.265  3812  3812 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-03 17:29:30.237  3861  3861 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-03 17:29:30.243  3861  3861 D AndroidRuntime: CheckJNI is OFF
,08-03 17:29:30.287  3861  3861 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-03 17:29:30.336  3861  3861 I Radio-JNI: register_android_hardware_Radio DONE
,08-03 17:29:30.359  3861  3861 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-03 17:29:30.369   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-03 17:29:30.371   873   886 I ActivityManager: Killing 3812:com.test.thalitest/u0a0 (adj 9): stop com.test.thalitest
,08-03 17:29:30.457   873  1780 D GraphicsStats: Buffer count: 2
,08-03 17:29:30.457   873  1308 D WifiService: Client connection lost with reason: 4
,08-03 17:29:30.468   873  1693 W ActivityManager: Spurious death for ProcessRecord{eb40f97 0:com.test.thalitest/u0a0}, curProc for 3812: null
,08-03 17:29:30.488   873   896 W PackageSettings: Skipping PackageSetting{67c4e5f com.example.hello/10273} due to missing metadata
,08-03 17:29:30.527   873   896 I art     : Starting a blocking GC Explicit
,08-03 17:29:30.607   873   896 I art     : Explicit concurrent mark sweep GC freed 24543(1652KB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 28MB/43MB, paused 857us total 79.643ms
,08-03 17:29:30.635   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-03 17:29:30.640  3861  3861 I art     : System.exit called, status: 0
,08-03 17:29:30.640  3861  3861 I AndroidRuntime: VM exiting with result code 0.
08-03 17:29:30.642   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-03 17:29:30.667  2615  2615 D BluetoothMapAppObserver: onReceive
,08-03 17:29:30.667  2615  2615 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-03 17:29:30.670  1888  2023 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-03 17:29:30.671  3625  3625 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-03 17:29:30.672   873  1299 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-03 17:29:30.674  1644  1644 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-03 17:29:30.691  1644  3873 I Keyboard.Facilitator.DecoderInitializer: run()
,08-03 17:29:30.714  1735  1735 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-03 17:29:30.732  1644  3873 I Decoder : createOrResetDecoder
,08-03 17:29:30.744  1676  3875 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-03 17:29:30.749   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-03 17:29:30.752  1533  1533 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,08-03 17:29:30.752  1533  1533 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-03 17:29:30.762  1747  1839 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-03 17:29:30.773   873   885 E PackageManager: Failed to write settings, restoring backup
08-03 17:29:30.773   873   885 E PackageManager: java.io.IOException: write failed: EROFS (Read-only file system)
08-03 17:29:30.773   873   885 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:498)
08-03 17:29:30.773   873   885 E PackageManager: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
08-03 17:29:30.773   873   885 E PackageManager: 	at java.io.OutputStreamWriter.flushBytes(OutputStreamWriter.java:170)
08-03 17:29:30.773   873   885 E PackageManager: 	at java.io.OutputStreamWriter.convert(OutputStreamWriter.java:184)
08-03 17:29:30.773   873   885 E PackageManager: 	at java.io.OutputStreamWriter.write(OutputStreamWriter.java:269)
08-03 17:29:30.773   873   885 E PackageManager: 	at java.io.BufferedWriter.write(BufferedWriter.java:288)
08-03 17:29:30.773   873   885 E PackageManager: 	at java.io.Writer.write(Writer.java:141)
08-03 17:29:30.773   873   885 E PackageManager: 	at org.kxml2.io.KXmlSerializer.attribute(KXmlSerializer.java:465)
08-03 17:29:30.773   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissions(Settings.java:4812)
08-03 17:29:30.773   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4645)
08-03 17:29:30.773   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-03 17:29:30.773   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-03 17:29:30.773   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 17:29:30.773   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-03 17:29:30.773   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 17:29:30.773   873   885 E PackageManager: Caused by: android.system.ErrnoException: write failed: EROFS (Read-only file system)
08-03 17:29:30.773   873   885 E PackageManager: 	at libcore.io.Posix.writeBytes(Native Method)
08-03 17:29:30.773   873   885 E PackageManager: 	at libcore.io.Posix.write(Posix.java:271)
08-03 17:29:30.773   873   885 E PackageManager: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
08-03 17:29:30.773   873   885 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:493)
08-03 17:29:30.773   873   885 E PackageManager: 	... 14 more
,08-03 17:29:30.777   873  1693 I ActivityManager: Start proc 3879:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-03 17:29:30.778  1747  1839 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-03 17:29:30.778  1747  1839 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1747
08-03 17:29:30.778  1747  1839 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-03 17:29:30.778  1747  1839 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-03 17:29:30.778  1747  1839 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-03 17:29:30.778  1747  1839 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-03 17:29:30.778  1747  1839 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-03 17:29:30.778  1747  1839 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-03 17:29:30.778  1747  1839 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-03 17:29:30.778  1747  1839 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-03 17:29:30.778  1747  1839 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 17:29:30.778  1747  1839 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 17:29:30.778  1747  1839 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-03 17:29:30.778  1747  1839 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 17:29:30.778   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-03 17:29:30.778   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-03 17:29:30.778   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 17:29:30.778   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 17:29:30.778   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 17:29:30.778   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 17:29:30.778   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 17:29:30.778   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 17:29:30.778   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-03 17:29:30.778   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-03 17:29:30.778   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-03 17:29:30.778   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 17:29:30.778   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 17:29:30.778   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-03 17:29:30.778   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 17:29:30.778   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-03 17:29:30.778   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 17:29:30.778   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 17:29:30.778   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.,java:186)
08-03 17:29:30.778   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 17:29:30.778   873   886 E DropBoxManagerService: 	... 13 more
08-03 17:29:30.780   873  1695 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-03 17:29:30.780   873  3885 E DropBoxManagerService: Can't write: system_app_crash
08-03 17:29:30.780   873  3885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop109.tmp: open failed: EROFS (Read-only file system)
08-03 17:29:30.780   873  3885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 17:29:30.780   873  3885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 17:29:30.780   873  3885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 17:29:30.780   873  3885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 17:29:30.780   873  3885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 17:29:30.780   873  3885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 17:29:30.780   873  3885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 17:29:30.780   873  3885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 17:29:30.780   873  3885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 17:29:30.780   873  3885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 17:29:30.780   873  3885 E DropBoxManagerService: 	... 5 more
08-03 17:29:30.789  1747  1839 I Process : Sending signal. PID: 1747 SIG: 9
08-03 17:29:30.803  1533  1533 I ConfigService: onCreate
08-03 17:29:30.811  1964  3892 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-03 17:29:30.812  1964  3892 D AccountUtils: Clearing selected account for com.test.thalitest
08-03 17:29:30.817  1676  3875 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,08-03 17:29:30.820  1676  3875 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-03 17:29:30.820  1676  3875 E AndroidRuntime: Process: android.process.acore, PID: 1676
08-03 17:29:30.820  1676  3875 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-03 17:29:30.820  1676  3875 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-03 17:29:30.820  1676  3875 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-03 17:29:30.820  1676  3875 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-03 17:29:30.820  1676  3875 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-03 17:29:30.820  1676  3875 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-03 17:29:30.820  1676  3875 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-03 17:29:30.820  1676  3875 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
08-03 17:29:30.820  1676  3875 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-03 17:29:30.820  1676  3875 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-03 17:29:30.820  1676  3875 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-03 17:29:30.820  1676  3875 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-03 17:29:30.820  1676  3875 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-03 17:29:30.820  1676  3875 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-03 17:29:30.820  1676  3875 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 17:29:30.820  1676  3875 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-03 17:29:30.820  1676  3875 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-03 17:29:30.821  1533  3893 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-03 17:29:30.821  1533  3893 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 17:29:30.821  1533  3893 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 17:29:30.821  1533  3893 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 17:29:30.821  1533  3893 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 17:29:30.821  1533  3893 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 17:29:30.821  1533  3893 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 17:29:30.821  1533  3893 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 17:29:30.821  1533  3893 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 17:29:30.821  1533  3893 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 17:29:30.821  1533  3893 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 17:29:30.821  1533  3893 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 17:29:30.821  1533  3893 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 17:29:30.821  1533  3893 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 17:29:30.821  1533  3893 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-03 17:29:30.821  1533  3893 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-03 17:29:30.821  1533  3893 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-03 17:29:30.821  1533  3893 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-03 17:29:30.824  1533  3893 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-03 17:29:30.824  1533  3893 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 17:29:30.824  1533  3893 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 17:29:30.824  1533  3893 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 17:29:30.824  1533  3893 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 17:29:30.824  1533  3893 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 17:29:30.824  1533  3893 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 17:29:30.824  1533  3893 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 17:29:30.824  1533  3893 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 17:29:30.824  1533  3893 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 17:29:30.824  1533  3893 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 17:29:30.824  1533  3893 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 17:29:30.824  1533  3893 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 17:29:30.824  1533  3893 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 17:29:30.824  1533  3893 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-03 17:29:30.824  1533  3893 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-03 17:29:30.824  1533  3893 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-03 17:29:30.824  1533  3893 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-03 17:29:30.824  1676  3875 I Process : Sending signal. PID: 1676 SIG: 9
,08-03 17:29:30.826   873  3896 E DropBoxManagerService: Can't write: system_app_crash
08-03 17:29:30.826   873  3896 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop110.tmp: open failed: EROFS (Read-only file system)
08-03 17:29:30.826   873  3896 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 17:29:30.826   873  3896 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 17:29:30.826   873  3896 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 17:29:30.826   873  3896 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 17:29:30.826   873  3896 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 17:29:30.826   873  3896 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 17:29:30.826   873  3896 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 17:29:30.826   873  3896 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 17:29:30.826   873  3896 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 17:29:30.826   873  3896 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 17:29:30.826   873  3896 E DropBoxManagerService: 	... 5 more
,08-03 17:29:30.829  1533  3893 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-03 17:29:30.839   279   279 E lowmemorykiller: Error writing /proc/1676/oom_score_adj; errno=22
,08-03 17:29:30.849   279   279 E lowmemorykiller: Error writing /proc/1676/oom_score_adj; errno=22
,08-03 17:29:30.851  1964  3892 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-03 17:29:30.860  1644  3873 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-03 17:29:30.867  1964  3892 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
08-03 17:29:30.867  1964  3892 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 17:29:30.867  1964  3892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 17:29:30.867  1964  3892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 17:29:30.867  1964  3892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 17:29:30.867  1964  3892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 17:29:30.867  1964  3892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 17:29:30.867  1964  3892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 17:29:30.867  1964  3892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 17:29:30.867  1964  3892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 17:29:30.867  1964  3892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 17:29:30.867  1964  3892 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 17:29:30.867  1964  3892 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 17:29:30.867  1964  3892 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 17:29:30.867  1964  3892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 17:29:30.867  1964  3892 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-03 17:29:30.867  1964  3892 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-03 17:29:30.867  1964  3892 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-03 17:29:30.867  1964  3892 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 17:29:30.867  1964  3892 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-03 17:29:30.867  1964  3892 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-03 17:29:30.867  1964  3892 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
08-03 17:29:30.867  1964  3892 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 17:29:30.867  1964  3892 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 17:29:30.867  1964  3892 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 17:29:30.867  1964  3892 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 17:29:30.867  1964  3892 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 17:29:30.867  1964  3892 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 17:29:30.867  1964  3892 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 17:29:30.867  1964  3892 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 17:29:30.867  1964  3892 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 17:29:30.867  1964  3892 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 17:29:30.867  1964  3892 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 17:29:30.867  1964  3892 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 17:29:30.867  1964  3892 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 17:29:30.867  1964  3892 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 17:29:30.867  1964  3892 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-03 17:29:30.867  1964  3892 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-03 17:29:30.867  1964  3892 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-03 17:29:30.867  1964  3892 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 17:29:30.867  1964  3892 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-03 17:29:30.867  1964  3892 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-03 17:29:30.875   873  1780 D GraphicsStats: Buffer count: 1
,08-03 17:29:30.876   873  1780 I WindowState: WIN DEATH: Window{f814a9c u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-03 17:29:30.878  1964  3892 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,08-03 17:29:30.887   873  1390 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1747) has died
,08-03 17:29:30.888   873  1390 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-03 17:29:30.909  1964  1964 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-03 17:29:30.909  1964  1964 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-03 17:29:30.913  1964  1964 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-03 17:29:30.913  1964  1964 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-03 17:29:30.919   279   279 E lowmemorykiller: Error writing /proc/1676/oom_score_adj; errno=22
,08-03 17:29:30.925  1964  3901 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-03 17:29:30.928  1644  3873 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-03 17:29:30.930  1644  3873 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-03 17:29:30.930  1644  3873 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-03 17:29:30.933  1644  3873 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-03 17:29:30.933  1644  3873 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-03 17:29:30.936  1964  3901 E DriveAsyncService: disk I/O error (code 3850)
08-03 17:29:30.936  1964  3901 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-03 17:29:30.936  1964  3901 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-03 17:29:30.936  1964  3901 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-03 17:29:30.936  1964  3901 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-03 17:29:30.936  1964  3901 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-03 17:29:30.936  1964  3901 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-03 17:29:30.936  1964  3901 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-03 17:29:30.936  1964  3901 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.k(SourceFile:483)
08-03 17:29:30.936  1964  3901 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(SourceFile:458)
08-03 17:29:30.936  1964  3901 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.i(SourceFile:1501)
08-03 17:29:30.936  1964  3901 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bj.a(SourceFile:16)
08-03 17:29:30.936  1964  3901 E DriveAsyncService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-03 17:29:30.936  1964  3901 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 17:29:30.936  1964  3901 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 17:29:30.936  1964  3901 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
,08-03 17:29:30.947  1964  3907 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-03 17:29:30.955  1644  3873 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-03 17:29:30.955  1644  3873 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-03 17:29:30.956  1644  3873 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-03 17:29:30.956  1644  3873 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-03 17:29:30.956  1644  3873 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-03 17:29:30.956  1644  3873 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-03 17:29:30.957  1644  3873 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-03 17:29:30.957  1644  3873 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon,
,08-03 17:29:30.964  1964  3902 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/metrics.db'.
08-03 17:29:30.964  1964  3902 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 17:29:30.964  1964  3902 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 17:29:30.964  1964  3902 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 17:29:30.964  1964  3902 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 17:29:30.964  1964  3902 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 17:29:30.964  1964  3902 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 17:29:30.964  1964  3902 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 17:29:30.964  1964  3902 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 17:29:30.964  1964  3902 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 17:29:30.964  1964  3902 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 17:29:30.964  1964  3902 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 17:29:30.964  1964  3902 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 17:29:30.964  1964  3902 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 17:29:30.964  1964  3902 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-03 17:29:30.964  1964  3902 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
08-03 17:29:30.964  1964  3902 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
08-03 17:29:30.964  1964  3902 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
08-03 17:29:30.964  1964  3902 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-03 17:29:30.964  1964  3902 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-03 17:29:30.964  1964  3902 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 17:29:30.964  1964  3902 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-03 17:29:30.964  1964  3902 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-03 17:29:30.965  1964  3902 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
08-03 17:29:30.965  1964  3902 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 17:29:30.965  1964  3902 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 17:29:30.965  1964  3902 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 17:29:30.965  1964  3902 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 17:29:30.965  1964  3902 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 17:29:30.965  1964  3902 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 17:29:30.965  1964  3902 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 17:29:30.965  1964  3902 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 17:29:30.965  1964  3902 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 17:29:30.965  1964  3902 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 17:29:30.965  1964  3902 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 17:29:30.965  1964  3902 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 17:29:30.965  1964  3902 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 17:29:30.965  1964  3902 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-03 17:29:30.965  1964  3902 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
08-03 17:29:30.965  1964  3902 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
08-03 17:29:30.965  1964  3902 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
08-03 17:29:30.965  1964  3902 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-03 17:29:30.965  1964  3902 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-03 17:29:30.965  1964  3902 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 17:29:30.965  1964  3902 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-03 17:29:30.965  1964  3902 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-03 17:29:30.966  1964  3907 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-03 17:29:30.966  1964  3907 E AndroidRuntime: Process: com.google.android.gms, PID: 1964
08-03 17:29:30.966  1964  3907 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-03 17:29:30.966  1964  3907 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-03 17:29:30.966  1964  3907 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-03 17:29:30.966  1964  3907 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-03 17:29:30.966  1964  3907 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-03 17:29:30.966  1964  3907 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-03 17:29:30.966  1964  3907 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-03 17:29:30.966  1964  3907 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-03 17:29:30.966  1964  3907 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-03 17:29:30.966  1964  3907 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-03 17:29:30.966  1964  3907 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-03 17:29:30.966  1964  3907 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-03 17:29:30.966  1964  3907 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-03 17:29:30.966  1964  3907 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-03 17:29:30.966  1964  3907 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-03 17:29:30.966  1964  3907 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-03 17:29:30.966  1964  3907 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 17:29:30.966  1964  3907 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 17:29:30.966  1964  3907 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,08-03 17:29:30.970  1964  3902 W SQLiteOpenHelper: Opened metrics.db in read-only mode
08-03 17:29:30.971  1964  3902 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
08-03 17:29:30.971  1964  3902 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
,08-03 17:29:30.972  1964  3902 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
,08-03 17:29:30.973  1964  3902 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
,08-03 17:29:30.973  1964  3902 I Process : Sending signal. PID: 1964 SIG: 9
,08-03 17:29:30.982   873  3016 I ActivityManager: Start proc 3909:com.google.android.googlequicksearchbox/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver
,08-03 17:29:30.985   279   279 E lowmemorykiller: Error writing /proc/1964/oom_score_adj; errno=22
08-03 17:29:30.986   279   279 E lowmemorykiller: Error writing /proc/1676/oom_score_adj; errno=22
,08-03 17:29:30.990  1799  3906 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-03 17:29:30.992   873  3919 E DropBoxManagerService: Can't write: system_app_crash
08-03 17:29:30.992   873  3919 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
08-03 17:29:30.992   873  3919 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 17:29:30.992   873  3919 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 17:29:30.992   873  3919 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 17:29:30.992   873  3919 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 17:29:30.992   873  3919 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 17:29:30.992   873  3919 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 17:29:30.992   873  3919 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 17:29:30.992   873  3919 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 17:29:30.992   873  3919 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 17:29:30.992   873  3919 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 17:29:30.992   873  3919 E DropBoxManagerService: 	... 5 more
,08-03 17:29:31.026  1799  3906 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-03 17:29:31.036  1799  3906 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,08-03 17:29:31.036  1799  3906 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-03 17:29:31.036  1799  3906 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 1799
08-03 17:29:31.036  1799  3906 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-03 17:29:31.036  1799  3906 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-03 17:29:31.036  1799  3906 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-03 17:29:31.036  1799  3906 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-03 17:29:31.036  1799  3906 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-03 17:29:31.036  1799  3906 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-03 17:29:31.036  1799  3906 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-03 17:29:31.036  1799  3906 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-03 17:29:31.036  1799  3906 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-03 17:29:31.036  1799  3906 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-03 17:29:31.036  1799  3906 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-03 17:29:31.036  1799  3906 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-03 17:29:31.036  1799  3906 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-03 17:29:31.036  1799  3906 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-03 17:29:31.036  1799  3906 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-03 17:29:31.036  1799  3906 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-03 17:29:31.036  1799  3906 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 17:29:31.036  1799  3906 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-03 17:29:31.036  1799  3906 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-03 17:29:31.043   873  1695 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
,08-03 17:29:31.043   873  1695 I ActivityManager: Killing 1799:com.google.android.googlequicksearchbox:search/u0a28 (adj 5): crash
08-03 17:29:31.045   873  3922 E DropBoxManagerService: Can't write: system_app_crash
08-03 17:29:31.045   873  3922 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
08-03 17:29:31.045   873  3922 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 17:29:31.045   873  3922 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 17:29:31.045   873  3922 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 17:29:31.045   873  3922 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 17:29:31.045   873  3922 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 17:29:31.045   873  3922 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 17:29:31.045   873  3922 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 17:29:31.045   873  3922 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 17:29:31.045   873  3922 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 17:29:31.045   873  3922 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 17:29:31.045   873  3922 E DropBoxManagerService: 	... 5 more
,08-03 17:29:31.103   873   884 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@23196a4)
,08-03 17:29:31.104   873  1309 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-03 17:29:31.106   873  1309 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-03 17:29:31.120  3909  3909 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-03 17:29:31.120  3909  3909 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 17:29:31.120  3909  3909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 17:29:31.120  3909  3909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 17:29:31.120  3909  3909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 17:29:31.120  3909  3909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 17:29:31.120  3909  3909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 17:29:31.120  3909  3909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 17:29:31.120  3909  3909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 17:29:31.120  3909  3909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 17:29:31.120  3909  3909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 17:29:31.120  3909  3909 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 17:29:31.120  3909  3909 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 17:29:31.120  3909  3909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 17:29:31.120  3909  3909 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-03 17:29:31.120  3909  3909 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-03 17:29:31.120  3909  3909 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-03 17:29:31.120  3909  3909 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-03 17:29:31.120  3909  3909 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-03 17:29:31.120  3909  3909 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-03 17:29:31.120  3909  3909 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-03 17:29:31.120  3909  3909 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-03 17:29:31.120  3909  3909 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 17:29:31.120  3909  3909 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 17:29:31.120  3909  3909 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 17:29:31.120  3909  3909 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-03 17:29:31.120  3909  3909 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 17:29:31.120  3909  3909 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 17:29:31.120  3909  3909 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 17:29:31.120  3909  3909 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-03 17:29:31.120  3909  3909 D AndroidRuntime: Shutting down VM

```
