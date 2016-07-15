#### Test 75789268514fc25_thali04_htc-Nexus 9 Logs


```
--------- beginning of system
07-15 15:21:56.039   554   602 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-15 15:21:56.045   554   602 I PowerManagerService: Sleeping (uid 1000)...
--------- beginning of main
07-15 15:21:56.071  1029  1029 I Keyboard.Facilitator: onFinishInput()
07-15 15:21:56.101  1102  1116 W SearchService: Abort, client detached.
07-15 15:21:56.132  1102  1102 I HotwordDetector: Closing mic
07-15 15:21:56.132  1102  1263 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@7b27e1
07-15 15:21:56.158   223   645 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
07-15 15:21:56.161  1102  1279 I MicroRecognitionRnrImpl: Detection finished
07-15 15:21:56.161  1102  1266 I MicroRecognitionRnrImpl: Stopping hotword detection.
07-15 15:21:56.190   169   233 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (121 us)
07-15 15:21:56.197   554   571 I ActivityManager: Killing 2539:com.google.android.gm.exchange/u0a70 (adj 15): empty #17
07-15 15:21:56.259   554   571 I ActivityManager: Killing 2179:com.google.android.music:main/u0a61 (adj 15): empty #18
07-15 15:21:56.544  2790  2790 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-15 15:21:56.549  2790  2790 D AndroidRuntime: CheckJNI is OFF
07-15 15:21:56.585  2790  2790 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-15 15:21:56.621  2790  2790 I Radio-JNI: register_android_hardware_Radio DONE
07-15 15:21:56.647  2790  2790 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-15 15:21:56.652   554   571 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-15 15:21:56.670   554   571 I ActivityManager: Start proc 2804:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-15 15:21:56.672  2790  2790 D AndroidRuntime: Shutting down VM
,07-15 15:21:56.877   554   602 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-15 15:21:56.884   554   602 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
07-15 15:21:56.885   554   600 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-15 15:21:56.886   169   169 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x557b874430
,07-15 15:21:56.886   169   169 D hwcomposer: hwc_blank: display 0: blank
07-15 15:21:56.886   169   169 D hwcomposer: hwc_blank_display: display 0: [0 -> 1]
,07-15 15:21:57.194   554   682 D SurfaceControl: Excessive delay in setPowerMode(): 309ms
,07-15 15:21:57.213   554   663 D WifiConfigStore: Retrieve network priorities after PNO.
,07-15 15:21:57.221   554   663 E native  : do suspend false
,07-15 15:21:57.229   554   663 D WifiConfigStore: No blacklist allowed without epno enabled
,07-15 15:21:57.271   554   663 D WifiConfigStore: Retrieve network priorities after PNO.
,07-15 15:21:57.275   554   663 E native  : do suspend true
,07-15 15:21:57.294  2804  2804 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,07-15 15:21:57.373   554   586 W ActivityManager: Activity pause timeout for ActivityRecord{ec20078 u0 com.test.thalitest/.MainActivity t67}
,07-15 15:21:57.437  2804  2804 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-15 15:21:57.469  2804  2804 I LibraryLoader: Time to load native libraries: 20 ms (timestamps 4936-4956)
,07-15 15:21:57.470  2804  2804 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-15 15:21:57.547  2804  2804 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {32cd0e1}
,07-15 15:21:57.548  2804  2804 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-15 15:21:57.549  2804  2804 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-15 15:21:57.567  2804  2804 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-15 15:21:57.571  2804  2804 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-15 15:21:57.632  2804  2804 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-15 15:21:57.656  2804  2804 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-15 15:21:57.656  2804  2804 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-15 15:21:57.717   554   663 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 12 -> obsolete
,07-15 15:21:58.058   554   599 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ca293c0:true
,07-15 15:21:58.167  2804  2804 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-15 15:21:58.195  2804  2804 D SystemWebViewEngine: CordovaWebView is running on device made by: htc
,07-15 15:21:58.293  2804  2842 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-15 15:21:58.310  2804  2829 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-15 15:21:58.347  2804  2842 I OpenGLRenderer: Initialized EGL, version 1.4
,07-15 15:21:58.415  1029  1029 I Keyboard.Facilitator: onFinishInput()
,07-15 15:21:58.540   554   600 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s667ms (total +1s877ms)
,07-15 15:21:58.627  2804  2804 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 2804
,07-15 15:21:58.873  2804  2804 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-15 15:21:59.051  2804  2843 D jxcore_app_log: JniHelper::setJavaVM(0xaaf857b8), pthread_self() = -552249040
,07-15 15:21:59.061  2804  2843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: ,
07-15 15:21:59.061  2804  2843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-15 15:21:59.061  2804  2843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-15 15:21:59.061  2804  2843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-15 15:21:59.061  2804  2843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-15 15:21:59.061  2804  2843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d17e54c added. We now have 1 listener(s)
,07-15 15:21:59.093  2804  2843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B4:CE:F6:34:3D:CC
,07-15 15:21:59.095  2804  2843 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
,07-15 15:21:59.096  2804  2843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-15 15:21:59.097  2804  2843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-15 15:21:59.104  2804  2843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-15 15:21:59.104  2804  2843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-15 15:21:59.104  2804  2843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-15 15:21:59.104  2804  2843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B4:CE:F6:34:3D:CC
07-15 15:21:59.104  2804  2843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-15 15:21:59.104  2804  2843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-15 15:21:59.104  2804  2843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-15 15:21:59.104  2804  2843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-15 15:21:59.104  2804  2843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-15 15:21:59.104  2804  2843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-15 15:21:59.104  2804  2843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-15 15:21:59.104  2804  2843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b69169b added. We now have 1 listener(s)
,07-15 15:21:59.104  2804  2843 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-15 15:21:59.113   554   664 D WifiService: New client listening to asynchronous messages
,07-15 15:21:59.116  2804  2843 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
07-15 15:21:59.117  2804  2843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-15 15:21:59.117  2804  2843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-15 15:21:59.118  2804  2843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-15 15:21:59.118  2804  2843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-15 15:21:59.123  2804  2843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-15 15:21:59.126  2804  2843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B4:CE:F6:34:3D:CC
,07-15 15:21:59.135  2804  2843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:21:59.135  2804  2843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:59.135  2804  2843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-15 15:21:59.135  2804  2843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-15 15:21:59.135  2804  2843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-15 15:21:59.135  2804  2843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-15 15:21:59.135  2804  2843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-15 15:21:59.135  2804  2843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-15 15:21:59.135  2804  2843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-15 15:21:59.136  2804  2843 D io.jxcore.node.ConnectivityMonitor: start: OK
07-15 15:21:59.137  2804  2843 I io.jxcore.node.LifeCycleMonitor: start: OK
07-15 15:21:59.138  2804  2843 D io.jxcore.node.JXcoreExtension: Unit Tests on
07-15 15:21:59.138  2804  2804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-15 15:21:59.142  2804  2804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-15 15:21:59.190  2804  2804 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-15 15:21:59.663  1267  1526 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-15 15:22:00.083  2804  2850 W jxcore-log: Initializing JXcore engine
,07-15 15:22:00.083  2804  2850 W jxcore-log: JXcore engine is ready
,07-15 15:22:00.196  2850  2850 W Thread-61: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=10052 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,07-15 15:22:00.196  2850  2850 W Thread-61: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10599]" dev="sockfs" ino=10599 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-15 15:22:00.196  2850  2850 W Thread-61: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=454 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-15 15:22:00.196  2850  2850 W Thread-61: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20261]" dev="sockfs" ino=20261 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-15 15:22:00.223  2804  2850 W jxcore-log: Starting JXcore engine
,07-15 15:22:00.438  2804  2850 W jxcore-log: Platform android
07-15 15:22:00.438  2804  2850 W jxcore-log: 
,07-15 15:22:00.438  2804  2850 W jxcore-log: Process ARCH arm
07-15 15:22:00.438  2804  2850 W jxcore-log: 
,07-15 15:22:00.906  2804  2850 I jxcore-log: JXcore Cordova bridge is ready!
07-15 15:22:00.906  2804  2850 I jxcore-log: 
07-15 15:22:00.906  2804  2850 W jxcore-log: JXcore engine is started
,07-15 15:22:00.915  2804  2843 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-15 15:22:00.919  2804  2804 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-15 15:22:00.935  2804  2850 E jxcore  : Error!: No such native module /data/user/0/com.test.thalitest/files/www/jxcore/app.js
07-15 15:22:00.935  2804  2850 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-15 15:22:00.944  2804  2804 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "No such native module /data/user/0/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/user/0/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,07-15 15:22:00.945  2804  2804 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-15 15:22:00.951   554   998 I ActivityManager: Killing 2552:com.google.process.gapps/u0a85 (adj 15): empty #17
,07-15 15:22:00.982  2804  2804 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-15 15:22:00.982  2804  2804 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-15 15:22:00.983  2804  2804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:22:00.983  2804  2804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:22:00.983  2804  2804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:22:00.983  2804  2804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-15 15:22:00.983  2804  2804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d17e54c removed from the list
07-15 15:22:00.983  2804  2804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:22:00.983  2804  2804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b69169b removed from the list
07-15 15:22:00.983  2804  2804 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:22:00.984  2804  2804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
07-15 15:22:00.984  2804  2843 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 34ms. Plugin should use CordovaInterface.getThreadPool().
07-15 15:22:00.985  2804  2804 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-15 15:22:01.494  1102  2853 I art     : Waiting for a blocking GC DisableMovingGc
,07-15 15:22:01.499  1102  2853 I art     : WaitForGcToComplete blocked for 5.694ms for cause DisableMovingGc
,07-15 15:22:01.500  1102  2853 I art     : Starting a blocking GC DisableMovingGc
,07-15 15:22:01.733   554   663 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 12 -> obsolete
,07-15 15:22:01.748  2851  2851 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,07-15 15:22:01.759  2851  2851 D AndroidRuntime: CheckJNI is OFF
,07-15 15:22:01.849  2851  2851 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,07-15 15:22:01.935  2851  2851 I Radio-JNI: register_android_hardware_Radio DONE
,07-15 15:22:02.006  2851  2851 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-15 15:22:02.023   554   586 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,07-15 15:22:02.024   554   586 I ActivityManager: Killing 2804:com.test.thalitest/u0a0 (adj 9): stop com.test.thalitest
,07-15 15:22:02.065   554   984 D GraphicsStats: Buffer count: 2
,07-15 15:22:02.066   554   664 D WifiService: Client connection lost with reason: 4
,07-15 15:22:02.130   554  1028 W ActivityManager: Spurious death for ProcessRecord{5969add 0:com.test.thalitest/u0a0}, curProc for 2804: null
,07-15 15:22:02.138   554   614 W PackageSettings: Skipping PackageSetting{b366be9 com.example.hello/10095} due to missing metadata
,07-15 15:22:02.183   554   614 I art     : Starting a blocking GC Explicit
,07-15 15:22:02.273   554   614 I art     : Explicit concurrent mark sweep GC freed 18071(1073KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 17MB/26MB, paused 1.733ms total 89.261ms
,07-15 15:22:02.296   554   614 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,07-15 15:22:02.304  2851  2851 I art     : System.exit called, status: 0
,07-15 15:22:02.304  2851  2851 I AndroidRuntime: VM exiting with result code 0.
,07-15 15:22:02.320   554   614 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,07-15 15:22:02.395  1267  1325 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-15 15:22:02.400  1059  1059 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,07-15 15:22:02.402  1029  1029 I Keyboard.Facilitator: resetDictionaries() : en_US
,07-15 15:22:02.407   554   655 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-15 15:22:02.444  2473  2491 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,07-15 15:22:02.446  1029  2867 I Keyboard.Facilitator.DecoderInitializer: run()
,07-15 15:22:02.478  1029  2867 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
,07-15 15:22:02.478  1029  2867 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
,07-15 15:22:02.482  1029  2867 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,07-15 15:22:02.482  1029  2867 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
07-15 15:22:02.483  1029  2867 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,07-15 15:22:02.483  1029  2867 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,07-15 15:22:02.509  1029  2867 I Decoder : createOrResetDecoder
,07-15 15:22:02.537  2473  2870 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,07-15 15:22:02.552   966   966 I ConfigService: onCreate
,07-15 15:22:02.553   554   661 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak

```
