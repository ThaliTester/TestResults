#### Test 79751015c29d5b7_thali06_htc-Nexus 9 Logs


```
--------- beginning of main
08-10 09:30:28.929  1096  2785 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-10 09:30:28.929  1096  2785 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-10 09:30:28.929  1096  2785 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:30:28.929  1096  2785 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-10 09:30:28.939  1096  2785 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 09:30:28.939  1096  2785 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 09:30:28.939  1096  2785 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 09:30:28.939  1096  2785 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 09:30:28.939  1096  2785 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-10 09:30:28.939  1096  2785 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-10 09:30:28.939  1096  2785 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-10 09:30:28.939  1096  2785 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-10 09:30:28.939  1096  2785 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-10 09:30:28.939  1096  2785 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-10 09:30:28.939  1096  2785 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-10 09:30:28.939  1096  2785 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-10 09:30:28.939  1096  2785 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
08-10 09:30:29.270  1096  1096 I ConfigService: onDestroy
08-10 09:30:29.279  2796  2796 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-10 09:30:29.283  2796  2796 D AndroidRuntime: CheckJNI is OFF
08-10 09:30:29.316  2796  2796 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-10 09:30:29.349  2796  2796 I Radio-JNI: register_android_hardware_Radio DONE
08-10 09:30:29.372  2796  2796 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-10 09:30:29.378   561   580 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-10 09:30:29.400  2796  2796 D AndroidRuntime: Shutting down VM
08-10 09:30:29.410  1080  2727 W SearchService: Abort, client detached.
08-10 09:30:29.423   561  1376 I ActivityManager: Start proc 2805:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-10 09:30:29.431  1080  1080 I HotwordDetector: Closing mic
08-10 09:30:29.431  1080  1344 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@ff38a9
08-10 09:30:29.442   223   643 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-10 09:30:29.451  1080  1351 I MicroRecognitionRnrImpl: Detection finished
08-10 09:30:29.451  1080  1345 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-10 09:30:29.529  2805  2805 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,08-10 09:30:29.641  2805  2805 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-10 09:30:29.664  2805  2805 I LibraryLoader: Time to load native libraries: 13 ms (timestamps 2634-2647)
,08-10 09:30:29.664  2805  2805 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-10 09:30:29.703  2805  2805 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {21fd694}
08-10 09:30:29.703  2805  2805 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 09:30:29.704  2805  2805 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-10 09:30:29.709  2805  2805 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-10 09:30:29.710  2805  2805 E SysUtils: ApplicationContext is null in ApplicationStatus
08-10 09:30:29.745  2805  2805 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-10 09:30:29.765  2805  2805 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-10 09:30:29.765  2805  2805 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-10 09:30:29.990   561   605 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@53976be:true
08-10 09:30:30.078  2805  2805 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-10 09:30:30.094  2805  2805 D SystemWebViewEngine: CordovaWebView is running on device made by: htc
08-10 09:30:30.153  2805  2849 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-10 09:30:30.166  2805  2835 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-10 09:30:30.191  2805  2849 I OpenGLRenderer: Initialized EGL, version 1.4
08-10 09:30:30.302   561   607 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +892ms
08-10 09:30:30.315   992   992 I Keyboard.Facilitator: onFinishInput()
08-10 09:30:30.339  2805  2805 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 2805
08-10 09:30:30.374   561   757 I ActivityManager: Killing 2553:com.google.process.gapps/u0a85 (adj 15): empty #17
08-10 09:30:30.413   561   757 I ActivityManager: Killing 2532:com.google.android.gm.exchange/u0a70 (adj 15): empty #18
08-10 09:30:30.472  2805  2805 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-10 09:30:30.637  2805  2851 D jxcore_app_log: JniHelper::setJavaVM(0xab5ba7b8), pthread_self() = -573462224
,08-10 09:30:30.642  2805  2851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-10 09:30:30.642  2805  2851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-10 09:30:30.642  2805  2851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-10 09:30:30.642  2805  2851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-10 09:30:30.642  2805  2851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-10 09:30:30.642  2805  2851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cab1bd8 added. We now have 1 listener(s)
,08-10 09:30:30.681  2805  2851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B4:CE:F6:34:3D:CC
08-10 09:30:30.682  2805  2851 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
,08-10 09:30:30.682  2805  2851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-10 09:30:30.683  2805  2851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-10 09:30:30.690  2805  2851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-10 09:30:30.690  2805  2851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-10 09:30:30.690  2805  2851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-10 09:30:30.690  2805  2851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B4:CE:F6:34:3D:CC
08-10 09:30:30.690  2805  2851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-10 09:30:30.690  2805  2851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-10 09:30:30.690  2805  2851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-10 09:30:30.690  2805  2851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-10 09:30:30.690  2805  2851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-10 09:30:30.690  2805  2851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-10 09:30:30.690  2805  2851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-10 09:30:30.690  2805  2851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-10 09:30:30.690  2805  2851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-10 09:30:30.690  2805  2851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-10 09:30:30.690  2805  2851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce97797 added. We now have 1 listener(s)
08-10 09:30:30.690  2805  2851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 09:30:30.706   561   664 D WifiService: New client listening to asynchronous messages
,08-10 09:30:30.711  2805  2851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-10 09:30:30.711  2805  2851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-10 09:30:30.711  2805  2851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-10 09:30:30.711  2805  2851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-10 09:30:30.711  2805  2851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-10 09:30:30.714  2805  2851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 09:30:30.716  2805  2851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B4:CE:F6:34:3D:CC
,08-10 09:30:30.723  2805  2851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-10 09:30:30.723  2805  2851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 09:30:30.723  2805  2851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:30:30.723  2805  2851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:30:30.723  2805  2851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 09:30:30.723  2805  2851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 09:30:30.723  2805  2851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 09:30:30.723  2805  2851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 09:30:30.723  2805  2851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 09:30:30.723  2805  2851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-10 09:30:30.723  2805  2851 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 09:30:30.726  2805  2805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 09:30:30.727  2805  2851 I io.jxcore.node.LifeCycleMonitor: start: OK
08-10 09:30:30.728  2805  2805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 09:30:30.756  2805  2805 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-10 09:30:31.141  2805  2814 I art     : Background partial concurrent mark sweep GC freed 20391(1980KB) AllocSpace objects, 8(632KB) LOS objects, 40% free, 11MB/18MB, paused 5.497ms total 82.576ms
,08-10 09:30:31.368  2805  2857 W jxcore-log: Initializing JXcore engine
,08-10 09:30:31.368  2805  2857 W jxcore-log: JXcore engine is ready
,08-10 09:30:31.429  2857  2857 W Thread-62: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=9238 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-10 09:30:31.429  2857  2857 W Thread-62: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10696]" dev="sockfs" ino=10696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-10 09:30:31.429  2857  2857 W Thread-62: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=454 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-10 09:30:31.429  2857  2857 W Thread-62: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20925]" dev="sockfs" ino=20925 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-10 09:30:31.443  2805  2857 W jxcore-log: Starting JXcore engine
,08-10 09:30:31.516  2805  2857 W jxcore-log: Platform android
08-10 09:30:31.516  2805  2857 W jxcore-log: 
08-10 09:30:31.516  2805  2857 W jxcore-log: Process ARCH arm
08-10 09:30:31.516  2805  2857 W jxcore-log: 
,08-10 09:30:31.658  2805  2857 I jxcore-log: JXcore Cordova bridge is ready!
08-10 09:30:31.658  2805  2857 I jxcore-log: 
08-10 09:30:31.658  2805  2857 W jxcore-log: JXcore engine is started
,08-10 09:30:31.663  2805  2851 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-10 09:30:31.665  2805  2805 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-10 09:30:31.671  2805  2857 E jxcore  : Error!: No such native module /data/user/0/com.test.thalitest/files/www/jxcore/app.js
08-10 09:30:31.671  2805  2857 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,08-10 09:30:31.676  2805  2805 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "No such native module /data/user/0/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/user/0/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,08-10 09:30:31.676  2805  2805 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,08-10 09:30:31.678   170   175 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (150 us)
,08-10 09:30:31.734  2805  2851 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 58ms. Plugin should use CordovaInterface.getThreadPool().
,08-10 09:30:31.734  2805  2805 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-10 09:30:31.735  2805  2805 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-10 09:30:31.744   561   592 I ActivityManager: Killing 2056:com.google.android.keep/u0a72 (adj 15): empty #17
,08-10 09:30:31.820  2805  2805 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-10 09:30:31.821  2805  2805 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-10 09:30:31.821  2805  2805 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-10 09:30:31.821  2805  2805 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-10 09:30:31.821  2805  2805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 09:30:31.821  2805  2805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:30:31.821  2805  2805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:30:31.821  2805  2805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 09:30:31.821  2805  2805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cab1bd8 removed from the list
08-10 09:30:31.821  2805  2805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:30:31.821  2805  2805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce97797 removed from the list
08-10 09:30:31.821  2805  2805 D io.jxcore.node.ConnectivityMonitor: stop
08-10 09:30:31.821  2805  2805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,08-10 09:30:31.867  2805  2805 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-10 09:30:31.870   992   992 I Keyboard.Facilitator: onFinishInput()
,08-10 09:30:31.913  1080  1080 W LocationOracleImpl: Best location was null
,08-10 09:30:31.940  1080  2868 I MicroRecognitionRnrImpl: Starting detection.
08-10 09:30:31.947  1080  2869 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@15d2aef
,08-10 09:30:31.956   223   643 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-10 09:30:31.956   223  2871 I AudioFlinger: AudioFlinger's thread 0xab945420 ready to run
08-10 09:30:31.958  1080  2869 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@15d2aef
,08-10 09:30:31.993  1055  1193 W GCoreFlp: No location to return for getLastLocation()
,08-10 09:30:32.006  1055  1193 W GCoreFlp: No location to return for getLastLocation()
,08-10 09:30:32.006  1055  1193 W GCoreFlp: No location to return for getLastLocation()
,08-10 09:30:32.045  1055  1193 W GCoreFlp: No location to return for getLastLocation()
,08-10 09:30:32.143  1080  1080 I HotwordWorkerImpl: onReady
,08-10 09:30:32.165  2805  2805 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 2805
,08-10 09:30:32.207  2860  2860 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-10 09:30:32.212  2860  2860 D AndroidRuntime: CheckJNI is OFF
,08-10 09:30:32.255  2860  2860 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-10 09:30:32.287  2860  2860 I Radio-JNI: register_android_hardware_Radio DONE
,08-10 09:30:32.314  2860  2860 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-10 09:30:32.319   561   592 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-10 09:30:32.320   561   592 I ActivityManager: Killing 2805:com.test.thalitest/u0a0 (adj 9): stop com.test.thalitest
,08-10 09:30:32.340   561   579 I WindowState: WIN DEATH: Window{70f0b6e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-10 09:30:32.340   561  1073 D GraphicsStats: Buffer count: 2
08-10 09:30:32.341   561   664 D WifiService: Client connection lost with reason: 4
,08-10 09:30:32.358  1034  1186 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,08-10 09:30:32.375   561   621 W PackageSettings: Skipping PackageSetting{bd75f3c com.example.hello/10095} due to missing metadata
,08-10 09:30:32.394   561  1376 W ActivityManager: Spurious death for ProcessRecord{574f218 0:com.test.thalitest/u0a0}, curProc for 2805: null
,08-10 09:30:32.408   561   621 I art     : Starting a blocking GC Explicit
,08-10 09:30:32.453   561   621 I art     : Explicit concurrent mark sweep GC freed 16788(1006KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 17MB/25MB, paused 576us total 43.457ms
,08-10 09:30:32.462   561   621 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-10 09:30:32.465  2860  2860 I art     : System.exit called, status: 0
,08-10 09:30:32.465  2860  2860 I AndroidRuntime: VM exiting with result code 0.
,08-10 09:30:32.471   561   621 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-10 09:30:32.509  1015  1015 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED,
08-10 09:30:32.514   561   655 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-10 09:30:32.519  1055  1265 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-10 09:30:32.554   992   992 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-10 09:30:32.567  2478  2891 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-10 09:30:32.577   992  2890 I Keyboard.Facilitator.DecoderInitializer: run()
,08-10 09:30:32.592   561   561 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-10 09:30:32.619   992  2890 I Decoder : createOrResetDecoder
,08-10 09:30:32.647  1096  1096 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,08-10 09:30:32.647  1096  1096 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-10 09:30:32.707  1096  1096 I ConfigService: onCreate
,08-10 09:30:32.716  1096  2894 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-10 09:30:32.716  1096  2894 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 09:30:32.716  1096  2894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 09:30:32.716  1096  2894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 09:30:32.716  1096  2894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 09:30:32.716  1096  2894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 09:30:32.716  1096  2894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 09:30:32.716  1096  2894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 09:30:32.716  1096  2894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 09:30:32.716  1096  2894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 09:30:32.716  1096  2894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 09:30:32.716  1096  2894 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 09:30:32.716  1096  2894 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 09:30:32.716  1096  2894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 09:30:32.716  1096  2894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 09:30:32.716  1096  2894 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-10 09:30:32.716  1096  2894 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-10 09:30:32.716  1096  2894 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-10 09:30:32.716  1096  2894 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-10 09:30:32.716  1096  2894 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 09:30:32.716  1096  2894 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 09:30:32.716  1096  2894 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 09:30:32.716  1096  2894 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 09:30:32.716  1096  2894 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 09:30:32.716  1096  2894 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 09:30:32.716  1096  2894 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 09:30:32.716  1096  2894 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 09:30:32.716  1096  2894 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 09:30:32.716  1096  2894 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 09:30:32.716  1096  2894 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 09:30:32.716  1096  2894 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 09:30:32.716  1096  2894 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 09:30:32.716  1096  2894 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 09:30:32.716  1096  2894 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-10 09:30:32.716  1096  2894 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-10 09:30:32.716  1096  2894 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-10 09:30:32.716  1187  2893 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-10 09:30:32.717  1187  2893 D AccountUtils: Clearing selected account for com.test.thalitest
08-10 09:30:32.718  1096  2894 W SQLiteOpenHelper: Opened config.db in read-only mode
08-10 09:30:32.718  2478  2891 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,08-10 09:30:32.732   992  2890 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-10 09:30:32.739   561   579 I ActivityManager: Start proc 2897:com.google.android.googlequicksearchbox:crash_report/u0a22 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-10 09:30:32.741  1034  1119 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-10 09:30:32.741  1034  1119 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1034
08-10 09:30:32.741  1034  1119 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-10 09:30:32.741  1034  1119 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-10 09:30:32.741  1034  1119 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-10 09:30:32.741  1034  1119 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-10 09:30:32.741  1034  1119 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-10 09:30:32.741  1034  1119 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-10 09:30:32.741  1034  1119 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-10 09:30:32.741  1034  1119 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-10 09:30:32.741  1034  1119 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 09:30:32.741  1034  1119 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 09:30:32.741  1034  1119 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-10 09:30:32.741  1034  1119 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 09:30:32.732  2478  2891 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-10 09:30:32.732  2478  2891 E AndroidRuntime: Process: android.process.acore, PID: 2478
08-10 09:30:32.732  2478  2891 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-10 09:30:32.732  2478  2891 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-10 09:30:32.732  2478  2891 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-10 09:30:32.732  2478  2891 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-10 09:30:32.732  2478  2891 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-10 09:30:32.732  2478  2891 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-10 09:30:32.732  2478  2891 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-10 09:30:32.732  2478  2891 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
08-10 09:30:32.732  2478  2891 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-10 09:30:32.732  2478  2891 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-10 09:30:32.732  2478  2891 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-10 09:30:32.732  2478  2891 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-10 09:30:32.732  2478  2891 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-10 09:30:32.732  2478  2891 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-10 09:30:32.732  2478  2891 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 09:30:32.732  2478  2891 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-10 09:30:32.732  2478  2891 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 09:30:32.748   561  1073 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-10 09:30:32.752  1080  2726 W SearchService: Abort, client detached.
08-10 09:30:32.758  1080  1080 I HotwordDetector: Closing mic
08-10 09:30:32.758  1080  1344 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@15d2aef
08-10 09:30:32.765  1187  2904 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-10 09:30:32.768  1187  1187 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-10 09:30:32.769  1187  1187 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-10 09:30:32.770  1187  2893 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
08-10 09:30:32.771   223   643 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-10 09:30:32.773  1080  2868 I MicroRecognitionRnrImpl: Detection finished
08-10 09:30:32.773  1080  1345 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-10 09:30:32.784  1187  2904 E DriveAsyncService: disk I/O error (code 3850)
08-10 09:30:32.784  1187  2904 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-10 09:30:32.784  1187  2904 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-10 09:30:32.784  1187  2904 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-10 09:30:32.784  1187  2904 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-10 09:30:32.784  1187  2904 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-10 09:30:32.784  1187  2904 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-10 09:30:32.784  1187  2904 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-10 09:30:32.784  1187  2904 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.k(SourceFile:483)
08-10 09:30:32.784  1187  2904 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(SourceFile:458)
08-10 09:30:32.784  1187  2904 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.i(SourceFile:1501)
08-10 09:30:32.784  1187  2904 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bj.a(SourceFile:16)
08-10 09:30:32.784  1187  2904 E DriveAsyncService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-10 09:30:32.784  1187  2904 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 09:30:32.784  1187  2904 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 09:30:32.784  1187  2904 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
,08-10 09:30:32.803   561   685 W System.err: java.io.IOException: write failed: EBADF (Bad file descriptor)
08-10 09:30:32.813   561   685 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:498)
08-10 09:30:32.813   561   685 W System.err: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
08-10 09:30:32.813   561   685 W System.err: 	at android.graphics.Bitmap.nativeCompress(Native Method)
08-10 09:30:32.813   561   685 W System.err: 	at android.graphics.Bitmap.compress(Bitmap.java:1027)
08-10 09:30:32.813   561   685 W System.err: 	at com.android.server.am.TaskPersister$LazyTaskWriterThread.run(TaskPersister.java:557)
08-10 09:30:32.813   561   685 W System.err: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
08-10 09:30:32.817   561  2905 E DropBoxManagerService: Can't write: system_app_crash
08-10 09:30:32.817   561  2905 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
08-10 09:30:32.817   561  2905 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 09:30:32.817   561  2905 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 09:30:32.817   561  2905 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 09:30:32.817   561  2905 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 09:30:32.817   561  2905 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 09:30:32.817   561  2905 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 09:30:32.817   561  2905 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 09:30:32.817   561  2905 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 09:30:32.817   561  2905 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 09:30:32.817   561  2905 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 09:30:32.817   561  2905 E DropBoxManagerService: 	... 5 more
08-10 09:30:32.820   561   685 W System.err: 	at libcore.io.Posix.writeBytes(Native Method)
08-10 09:30:32.820   561   685 W System.err: 	at libcore.io.Posix.write(Posix.java:271)
08-10 09:30:32.820   561   685 W System.err: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
08-10 09:30:32.820   561   685 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:493)
08-10 09:30:32.820   561   685 W System.err: 	... 4 more
08-10 09:30:32.820   561   685 D skia    : ------- write threw an exception

```
