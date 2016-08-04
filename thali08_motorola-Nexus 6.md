#### Test 79426650eeb77ae_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
08-05 01:32:58.153   872  2100 D NetlinkSocketObserver: NeighborEvent{elapsedMs=374719, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 01:32:58.872  3951  3951 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-05 01:32:58.876  3951  3951 D AndroidRuntime: CheckJNI is OFF
08-05 01:32:58.911  3951  3951 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-05 01:32:58.953  3951  3951 I Radio-JNI: register_android_hardware_Radio DONE
08-05 01:32:58.972  3951  3951 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-05 01:32:58.976   872  1707 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-05 01:32:59.029   872  1707 I ActivityManager: Start proc 3960:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-05 01:32:59.042  3951  3951 D AndroidRuntime: Shutting down VM
08-05 01:32:59.186  3960  3960 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-05 01:32:59.216  3960  3960 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-05 01:32:59.229  3960  3960 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 5789-5795)
08-05 01:32:59.230  3960  3960 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 01:32:59.263  3960  3960 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {72ae89e}
08-05 01:32:59.264  3960  3960 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 01:32:59.264  3960  3960 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-05 01:32:59.272  3960  3960 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-05 01:32:59.275  3960  3960 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-05 01:32:59.306  3960  3960 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-05 01:32:59.323  3960  3960 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-05 01:32:59.323  3960  3960 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-05 01:32:59.323  3960  3960 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-05 01:32:59.323  3960  3960 I Adreno  : Build Date                       : 10/20/15
08-05 01:32:59.323  3960  3960 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-05 01:32:59.323  3960  3960 I Adreno  : Local Branch                     : M14
08-05 01:32:59.323  3960  3960 I Adreno  : Remote Branch                    : 
08-05 01:32:59.323  3960  3960 I Adreno  : Remote Branch                    : 
08-05 01:32:59.323  3960  3960 I Adreno  : Reconstruct Branch               : 
,08-05 01:32:59.405   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ed78235:true
,08-05 01:32:59.485  3960  3960 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-05 01:32:59.503  3960  3960 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-05 01:32:59.613   872   885 W ActivityManager: Activity pause timeout for ActivityRecord{c6696e6 u0 com.test.thalitest/.MainActivity t2}
,08-05 01:32:59.629  3960  3997 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-05 01:32:59.682  3960  3984 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-05 01:32:59.731  3960  3997 I OpenGLRenderer: Initialized EGL, version 1.4
,08-05 01:32:59.773   872   881 I art     : Background partial concurrent mark sweep GC freed 27948(1826KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 29MB/43MB, paused 1.236ms total 103.400ms
,08-05 01:32:59.831   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +719ms (total +824ms)
08-05 01:32:59.834  1648  1648 I Keyboard.Facilitator: onFinishInput()
,08-05 01:32:59.922  3960  3960 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3960
,08-05 01:33:00.036  3960  3960 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-05 01:33:00.289  3960  3999 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1664681680
,08-05 01:33:00.298  3960  3999 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-05 01:33:00.298  3960  3999 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-05 01:33:00.298  3960  3999 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-05 01:33:00.298  3960  3999 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-05 01:33:00.298  3960  3999 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-05 01:33:00.298  3960  3999 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44c760d added. We now have 1 listener(s)
,08-05 01:33:00.302  3960  3999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-05 01:33:00.303  3960  3999 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-05 01:33:00.304  3960  3999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-05 01:33:00.304  3960  3999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-05 01:33:00.310  3960  3999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-05 01:33:00.310  3960  3999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-05 01:33:00.310  3960  3999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-05 01:33:00.310  3960  3999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-05 01:33:00.310  3960  3999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-05 01:33:00.310  3960  3999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-05 01:33:00.310  3960  3999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-05 01:33:00.310  3960  3999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-05 01:33:00.310  3960  3999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-05 01:33:00.310  3960  3999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-05 01:33:00.310  3960  3999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-05 01:33:00.310  3960  3999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-05 01:33:00.310  3960  3999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-05 01:33:00.310  3960  3999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-05 01:33:00.310  3960  3999 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e2b10 added. We now have 1 listener(s)
,08-05 01:33:00.310  3960  3999 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 01:33:00.318   872  1305 D WifiService: New client listening to asynchronous messages
,08-05 01:33:00.319  3960  3999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-05 01:33:00.319  3960  3999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-05 01:33:00.319  3960  3999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-05 01:33:00.320  3960  3999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-05 01:33:00.320  3960  3999 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-05 01:33:00.323  3960  3999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 01:33:00.324  3960  3999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-05 01:33:00.334  3960  3999 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-05 01:33:00.335  3960  3999 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 01:33:00.335  3960  3999 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 01:33:00.335  3960  3999 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 01:33:00.335  3960  3999 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 01:33:00.335  3960  3999 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 01:33:00.335  3960  3999 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 01:33:00.335  3960  3999 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 01:33:00.335  3960  3999 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 01:33:00.336  3960  3999 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-05 01:33:00.336  3960  3999 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 01:33:00.338  3960  3999 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-05 01:33:00.341  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 01:33:00.348  3960  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 01:33:00.371  3960  3960 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-05 01:33:01.805  3960  4007 W jxcore-log: Initializing JXcore engine
,08-05 01:33:01.805  3960  4007 W jxcore-log: JXcore engine is ready
,08-05 01:33:01.840  4007  4007 W Thread-362: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8953 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-05 01:33:01.840  4007  4007 W Thread-362: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11478]" dev="sockfs" ino=11478 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-05 01:33:01.840  4007  4007 W Thread-362: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-05 01:33:01.840  4007  4007 W Thread-362: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[28073]" dev="sockfs" ino=28073 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-05 01:33:01.857  3960  4007 W jxcore-log: Starting JXcore engine
,08-05 01:33:01.937  3960  4007 W jxcore-log: Platform android
08-05 01:33:01.937  3960  4007 W jxcore-log: 
,08-05 01:33:01.937  3960  4007 W jxcore-log: Process ARCH arm
08-05 01:33:01.937  3960  4007 W jxcore-log: 
,08-05 01:33:02.162  3960  4007 I jxcore-log: JXcore Cordova bridge is ready!
08-05 01:33:02.162  3960  4007 I jxcore-log: 
,08-05 01:33:02.163  3960  4007 W jxcore-log: JXcore engine is started
,08-05 01:33:02.174  3960  3999 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-05 01:33:02.179  3960  3960 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-05 01:33:14.737   872  2100 D NetlinkSocketObserver: NeighborEvent{elapsedMs=391304, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-05 01:33:15.091  3960  4007 E jxcore  : Error!: Cannot find module '../thalilogger'
08-05 01:33:15.091  3960  4007 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w._oldRes","_lineNumber":"802","_columnNumber":"9","_msg":"    at $w._oldRes@module.js:802:9"},{"_fileName":"module.js","_functionName":"$w._resolveFilename","_lineNumber":"1771","_columnNumber":"1","_msg":"    at $w._resolveFilename@module.js:1771:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"362","_columnNumber":"4","_msg":"    at $w._load@module.js:362:4"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js","_functionName":"","_lineNumber":"5","_columnNumber":"14","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js:5:14"}]
,08-05 01:33:15.103  3960  3960 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "Cannot find module '../thalilogger'\nError: Cannot find module '../thalilogger'\n    at $w._oldRes@module.js:802:9\n    at $w._resolveFilename@module.js:1771:1\n    at $w._load@module.js:362:4\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at @/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js:5:14"", source: file:///android_asset/www/js/thali_main.js (57)
,08-05 01:33:15.104  3960  3960 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,08-05 01:33:15.117   872  1707 I ActivityManager: Killing 3279:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-05 01:33:15.169  3960  3960 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-05 01:33:15.170  3960  3960 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,08-05 01:33:15.170  3960  3999 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 67ms. Plugin should use CordovaInterface.getThreadPool().
,08-05 01:33:15.171  3960  3960 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-05 01:33:15.171  3960  3960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 01:33:15.171  3960  3960 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 01:33:15.171  3960  3960 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-05 01:33:15.171  3960  3960 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44c760d removed from the list
,08-05 01:33:15.171  3960  3960 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 01:33:15.172  3960  3960 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1e2b10 removed from the list
08-05 01:33:15.172  3960  3960 D io.jxcore.node.ConnectivityMonitor: stop
08-05 01:33:15.172  3960  3960 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
08-05 01:33:15.173  3960  3960 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-05 01:33:16.607  4008  4008 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-05 01:33:16.612  4008  4008 D AndroidRuntime: CheckJNI is OFF
,08-05 01:33:16.649  4008  4008 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-05 01:33:16.690  4008  4008 I Radio-JNI: register_android_hardware_Radio DONE
,08-05 01:33:16.710  4008  4008 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-05 01:33:16.724   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-05 01:33:16.725   872   885 I ActivityManager: Killing 3960:com.test.thalitest/u0a0 (adj 9): stop com.test.thalitest
,08-05 01:33:16.798   872  1722 D GraphicsStats: Buffer count: 2
,08-05 01:33:16.798   872  1305 D WifiService: Client connection lost with reason: 4
,08-05 01:33:16.832   872   895 W PackageSettings: Skipping PackageSetting{edbd9a5 com.example.hello/10273} due to missing metadata
,08-05 01:33:16.853   872  1722 W ActivityManager: Spurious death for ProcessRecord{37eaaa0 0:com.test.thalitest/u0a0}, curProc for 3960: null
,08-05 01:33:16.875   872   895 I art     : Starting a blocking GC Explicit
,08-05 01:33:16.923   872   895 I art     : Explicit concurrent mark sweep GC freed 16613(1178KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 28MB/43MB, paused 621us total 47.676ms
,08-05 01:33:16.953   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-05 01:33:16.958  4008  4008 I art     : System.exit called, status: 0
08-05 01:33:16.958  4008  4008 I AndroidRuntime: VM exiting with result code 0.
08-05 01:33:16.975   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-05 01:33:16.998  2667  2667 D BluetoothMapAppObserver: onReceive
08-05 01:33:16.998  2667  2667 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-05 01:33:17.000  1677  2006 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-05 01:33:17.002  3645  3645 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-05 01:33:17.010   872  1293 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-05 01:33:17.010  1648  1648 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-05 01:33:17.016  1648  4019 I Keyboard.Facilitator.DecoderInitializer: run()
,08-05 01:33:17.017  1648  4019 I Decoder : createOrResetDecoder
,08-05 01:33:17.054  3032  4021 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-05 01:33:17.086  1724  1724 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-05 01:33:17.090  1486  1486 I ConfigService: onCreate
,08-05 01:33:17.097   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-05 01:33:17.130  1648  4019 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-05 01:33:17.182  1486  1486 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-05 01:33:17.184  1486  1486 D AndroidRuntime: Shutting down VM
,--------- beginning of crash,
08-05 01:33:17.185  1486  1486 E AndroidRuntime: FATAL EXCEPTION: main
08-05 01:33:17.185  1486  1486 E AndroidRuntime: Process: com.google.process.gapps, PID: 1486
08-05 01:33:17.185  1486  1486 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-05 01:33:17.185  1486  1486 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-05 01:33:17.185  1486  1486 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-05 01:33:17.185  1486  1486 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-05 01:33:17.185  1486  1486 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 01:33:17.185  1486  1486 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-05 01:33:17.185  1486  1486 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-05 01:33:17.185  1486  1486 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 01:33:17.185  1486  1486 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-05 01:33:17.185  1486  1486 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-05 01:33:17.185  1486  1486 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-05 01:33:17.185  1486  1486 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-05 01:33:17.185  1486  1486 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-05 01:33:17.185  1486  1486 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-05 01:33:17.185  1486  1486 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-05 01:33:17.185  1486  1486 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-05 01:33:17.185  1486  1486 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-05 01:33:17.185  1486  1486 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-05 01:33:17.185  1486  1486 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-05 01:33:17.185  1486  1486 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-05 01:33:17.185  1486  1486 E AndroidRuntime: 	... 8 more
,08-05 01:33:17.190  1486  1486 I Process : Sending signal. PID: 1486 SIG: 9
,08-05 01:33:17.191   872  4027 E DropBoxManagerService: Can't write: system_app_crash
08-05 01:33:17.191   872  4027 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop108.tmp: open failed: EROFS (Read-only file system)
08-05 01:33:17.191   872  4027 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-05 01:33:17.191   872  4027 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 01:33:17.191   872  4027 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-05 01:33:17.191   872  4027 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-05 01:33:17.191   872  4027 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-05 01:33:17.191   872  4027 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-05 01:33:17.191   872  4027 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 01:33:17.191   872  4027 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-05 01:33:17.191   872  4027 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 01:33:17.191   872  4027 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-05 01:33:17.191   872  4027 E DropBoxManagerService: 	... 5 more
,08-05 01:33:17.205  1648  4019 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-05 01:33:17.207  1648  4019 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-05 01:33:17.207  1648  4019 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-05 01:33:17.208  1648  4019 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-05 01:33:17.208  1648  4019 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-05 01:33:17.209  1648  4019 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-05 01:33:17.209  1648  4019 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-05 01:33:17.210  1648  4019 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-05 01:33:17.210  1648  4019 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-05 01:33:17.210  1648  4019 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-05 01:33:17.210  1648  4019 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-05 01:33:17.210  1648  4019 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-05 01:33:17.210  1648  4019 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-05 01:33:17.230   872  1305 D WifiService: Client connection lost with reason: 4
,08-05 01:33:17.236   872  1730 I ActivityManager: Process com.google.process.gapps (pid 1486) has died
,08-05 01:33:17.236   872  1730 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
08-05 01:33:17.236   872  1730 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
08-05 01:33:17.237   872  1730 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
,08-05 01:33:17.249  1806  1806 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-05 01:33:17.259   872  1722 I ActivityManager: Start proc 4029:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,08-05 01:33:17.280  1806  1806 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-05 01:33:17.280  1806  1806 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-05 01:33:17.290  1806  1806 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-05 01:33:17.290  1806  1806 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-05 01:33:17.296  1806  4044 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-05 01:33:17.310  1834  4043 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-05 01:33:17.334  1806  4044 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-05 01:33:17.334  1806  4044 E AndroidRuntime: Process: com.google.android.gms, PID: 1806
08-05 01:33:17.334  1806  4044 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-05 01:33:17.334  1806  4044 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-05 01:33:17.334  1806  4044 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-05 01:33:17.334  1806  4044 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-05 01:33:17.334  1806  4044 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-05 01:33:17.334  1806  4044 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-05 01:33:17.334  1806  4044 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-05 01:33:17.334  1806  4044 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-05 01:33:17.334  1806  4044 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-05 01:33:17.334  1806  4044 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-05 01:33:17.334  1806  4044 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-05 01:33:17.334  1806  4044 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-05 01:33:17.334  1806  4044 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-05 01:33:17.334  1806  4044 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-05 01:33:17.334  1806  4044 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-05 01:33:17.334  1806  4044 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-05 01:33:17.334  1806  4044 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 01:33:17.334  1806  4044 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 01:33:17.334  1806  4044 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,08-05 01:33:17.340   872  4046 E DropBoxManagerService: Can't write: system_app_crash
08-05 01:33:17.340   872  4046 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop109.tmp: open failed: EROFS (Read-only file system)
08-05 01:33:17.340   872  4046 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-05 01:33:17.340   872  4046 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 01:33:17.340   872  4046 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-05 01:33:17.340   872  4046 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-05 01:33:17.340   872  4046 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-05 01:33:17.340   872  4046 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-05 01:33:17.340   872  4046 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 01:33:17.340   872  4046 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-05 01:33:17.340   872  4046 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 01:33:17.340   872  4046 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-05 01:33:17.340   872  4046 E DropBoxManagerService: 	... 5 more
,08-05 01:33:17.353   872  1756 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3960 uid 10000
,08-05 01:33:17.355  1648  1648 I Keyboard.Facilitator: onFinishInput()
,08-05 01:33:17.355   872  1378 I ActivityManager: Start proc 4048:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,08-05 01:33:17.357  1806  4044 I Process : Sending signal. PID: 1806 SIG: 9
,08-05 01:33:17.363  1737  4047 E ReflectionEngine: Failed to save models
08-05 01:33:17.363  1737  4047 E ReflectionEngine: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/files/engine_16: open failed: EROFS (Read-only file system)
08-05 01:33:17.363  1737  4047 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-05 01:33:17.363  1737  4047 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 01:33:17.363  1737  4047 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-05 01:33:17.363  1737  4047 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.BT(ReflectionEngine.java:123)
08-05 01:33:17.363  1737  4047 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:240)
08-05 01:33:17.363  1737  4047 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-05 01:33:17.363  1737  4047 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-05 01:33:17.363  1737  4047 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-05 01:33:17.363  1737  4047 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 01:33:17.363  1737  4047 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 01:33:17.363  1737  4047 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 01:33:17.363  1737  4047 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 01:33:17.363  1737  4047 E ReflectionEngine: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-05 01:33:17.363  1737  4047 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 01:33:17.363  1737  4047 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 01:33:17.363  1737  4047 E ReflectionEngine: 	at java.lang.Thread.run(Thread.java:818)
08-05 01:33:17.363  1737  4047 E ReflectionEngine: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-05 01:33:17.363  1737  4047 E ReflectionEngine: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 01:33:17.363  1737  4047 E ReflectionEngine: 	at libcore.io.Posix.open(Native Method)
08-05 01:33:17.363  1737  4047 E ReflectionEngine: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 01:33:17.363  1737  4047 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-05 01:33:17.363  1737  4047 E ReflectionEngine: 	... 16 more
,08-05 01:33:17.367  1834  4043 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-05 01:33:17.380  1737  4047 E ObservedEventLogger: Failed to write the stream file
08-05 01:33:17.380  1737  4047 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2424: open failed: EROFS (Read-only file system)
08-05 01:33:17.380  1737  4047 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-05 01:33:17.380  1737  4047 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 01:33:17.380  1737  4047 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
08-05 01:33:17.380  1737  4047 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
08-05 01:33:17.380  1737  4047 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
08-05 01:33:17.380  1737  4047 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-05 01:33:17.380  1737  4047 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-05 01:33:17.380  1737  4047 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-05 01:33:17.380  1737  4047 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 01:33:17.380  1737  4047 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 01:33:17.380  1737  4047 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 01:33:17.380  1737  4047 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 01:33:17.380  1737  4047 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-05 01:33:17.380  1737  4047 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 01:33:17.380  1737  4047 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 01:33:17.380  1737  4047 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
08-05 01:33:17.380  1737  4047 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-05 01:33:17.380  1737  4047 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 01:33:17.380  1737  4047 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
08-05 01:33:17.380  1737  4047 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 01:33:17.380  1737  4047 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-05 01:33:17.380  1737  4047 E ObservedEventLogger: 	... 16 more
08-05 01:33:17.382  1737  4047 E ObservedEventLogger: Failed to write the stream file
08-05 01:33:17.382  1737  4047 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2427: open failed: EROFS (Read-only file system)
08-05 01:33:17.382  1737  4047 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-05 01:33:17.382  1737  4047 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 01:33:17.382  1737  4047 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
08-05 01:33:17.382  1737  4047 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
08-05 01:33:17.382  1737  4047 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
08-05 01:33:17.382  1737  4047 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-05 01:33:17.382  1737  4047 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-05 01:33:17.382  1737  4047 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-05 01:33:17.382  1737  4047 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 01:33:17.382  1737  4047 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 01:33:17.382  1737  4047 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 01:33:17.382  1737  4047 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 01:33:17.382  1737  4047 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-05 01:33:17.382  1737  4047 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 01:33:17.382  1737  4047 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 01:33:17.382  1737  4047 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
08-05 01:33:17.382  1737  4047 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-05 01:33:17.382  1737  4047 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 01:33:17.382  1737  4047 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
08-05 01:33:17.382  1737  4047 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 01:33:17.382  1737  4047 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-05 01:33:17.382  1737  4047 E ObservedEventLogger: 	... 16 more
,08-05 01:33:17.404   872  1380 I ActivityManager: Start proc 4060:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-05 01:33:17.408  4048  4048 W System  : ClassLoader referenced unknown path: /system/app/KeyChain/lib/arm
08-05 01:33:17.409  1834  4043 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
08-05 01:33:17.410  1834  4043 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-05 01:33:17.410  1834  4043 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 1834
08-05 01:33:17.410  1834  4043 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-05 01:33:17.410  1834  4043 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-05 01:33:17.410  1834  4043 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-05 01:33:17.410  1834  4043 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-05 01:33:17.410  1834  4043 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-05 01:33:17.410  1834  4043 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-05 01:33:17.410  1834  4043 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-05 01:33:17.410  1834  4043 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-05 01:33:17.410  1834  4043 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-05 01:33:17.410  1834  4043 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-05 01:33:17.410  1834  4043 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-05 01:33:17.410  1834  4043 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-05 01:33:17.410  1834  4043 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-05 01:33:17.410  1834  4043 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-05 01:33:17.410  1834  4043 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-05 01:33:17.410  1834  4043 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-05 01:33:17.410  1834  4043 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 01:33:17.410  1834  4043 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-05 01:33:17.410  1834  4043 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-05 01:33:17.413  1834  4043 I Process : Sending signal. PID: 1834 SIG: 9
08-05 01:33:17.416   872  4070 E DropBoxManagerService: Can't write: system_app_crash
08-05 01:33:17.416   872  4070 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop110.tmp: open failed: EROFS (Read-only file system)
08-05 01:33:17.416   872  4070 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-05 01:33:17.416   872  4070 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 01:33:17.416   872  4070 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-05 01:33:17.416   872  4070 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-05 01:33:17.416   872  4070 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-05 01:33:17.416   872  4070 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-05 01:33:17.416   872  4070 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 01:33:17.416   872  4070 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-05 01:33:17.416   872  4070 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 01:33:17.416   872  4070 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-05 01:33:17.416   872  4070 E DropBoxManagerService: 	... 5 more
08-05 01:33:17.424  4029  4029 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
08-05 01:33:17.427  4048  4048 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2725 
,08-05 01:33:17.464   872  1722 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@1cf923e)
08-05 01:33:17.464   872  1306 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 01:33:17.465   872  1306 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 01:33:17.489  4048  4074 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.keychain/databases/grants.db'.
08-05 01:33:17.489  4048  4074 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 01:33:17.489  4048  4074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 01:33:17.489  4048  4074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-05 01:33:17.489  4048  4074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-05 01:33:17.489  4048  4074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-05 01:33:17.489  4048  4074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-05 01:33:17.489  4048  4074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-05 01:33:17.489  4048  4074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-05 01:33:17.489  4048  4074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-05 01:33:17.489  4048  4074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-05 01:33:17.489  4048  4074 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-05 01:33:17.489  4048  4074 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-05 01:33:17.489  4048  4074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 01:33:17.489  4048  4074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-05 01:33:17.489  4048  4074 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-05 01:33:17.489  4048  4074 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-05 01:33:17.489  4048  4074 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-05 01:33:17.489  4048  4074 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 01:33:17.489  4048  4074 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-05 01:33:17.489  4048  4074 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-05 01:33:17.492  4029  4029 I MultiDex: VM with version 2.1.0 has multidex support
,08-05 01:33:17.493  4048  4074 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-05 01:33:17.493  4048  4074 E AndroidRuntime: Process: com.android.keychain, PID: 4048
08-05 01:33:17.493  4048  4074 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 01:33:17.493  4048  4074 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 01:33:17.493  4048  4074 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-05 01:33:17.493  4048  4074 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-05 01:33:17.493  4048  4074 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-05 01:33:17.493  4048  4074 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-05 01:33:17.493  4048  4074 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-05 01:33:17.493  4048  4074 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-05 01:33:17.493  4048  4074 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-05 01:33:17.493  4048  4074 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-05 01:33:17.493  4048  4074 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-05 01:33:17.493  4048  4074 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-05 01:33:17.493  4048  4074 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 01:33:17.493  4048  4074 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-05 01:33:17.493  4048  4074 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-05 01:33:17.493  4048  4074 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-05 01:33:17.493  4048  4074 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-05 01:33:17.493  4048  4074 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 01:33:17.493  4048  4074 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-05 01:33:17.493  4048  4074 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-05 01:33:17.493  4029  4029 I MultiDex: install
,08-05 01:33:17.496  4029  4029 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-05 01:33:17.504   872   872 I ActivityManager: Start proc 4077:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,08-05 01:33:17.506   872  1722 I ActivityManager: Process com.google.android.gms (pid 1806) has died
,08-05 01:33:17.506   872  1722 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
,08-05 01:33:17.511   872  1305 D WifiService: Client connection lost with reason: 4
08-05 01:33:17.515   872  4083 E DropBoxManagerService: Can't write: system_app_crash
08-05 01:33:17.515   872  4083 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
08-05 01:33:17.515   872  4083 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-05 01:33:17.515   872  4083 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 01:33:17.515   872  4083 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-05 01:33:17.515   872  4083 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-05 01:33:17.515   872  4083 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-05 01:33:17.515   872  4083 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-05 01:33:17.515   872  4083 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 01:33:17.515   872  4083 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-05 01:33:17.515   872  4083 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 01:33:17.515   872  4083 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-05 01:33:17.515   872  4083 E DropBoxManagerService: 	... 5 more
,08-05 01:33:17.522   872  1715 I ActivityManager: Process com.google.android.googlequicksearchbox:search (pid 1834) has died
,08-05 01:33:17.522   872  1715 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 1000ms
,08-05 01:33:17.525  4048  4074 I Process : Sending signal. PID: 4048 SIG: 9
,08-05 01:33:17.539  4029  4029 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm

```
