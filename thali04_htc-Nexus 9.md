#### Test 78968685da35147_thali04_htc-Nexus 9 Logs


```
--------- beginning of main
07-27 08:54:01.372  2510  2521 D Finsky  : [221] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
07-27 08:54:01.387  1085  1085 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-27 08:54:01.402  1085  1085 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-27 08:54:01.406  1085  1085 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-27 08:54:01.448  1085  1104 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
07-27 08:54:01.448  1085  1104 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-27 08:54:01.449  1085  1104 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:54:01.449  1085  1104 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-27 08:54:01.478  2510  2521 D Finsky  : [221] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,07-27 08:54:02.806  2875  2875 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-27 08:54:02.810  2875  2875 D AndroidRuntime: CheckJNI is OFF
07-27 08:54:02.842  2875  2875 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-27 08:54:02.880  2875  2875 I Radio-JNI: register_android_hardware_Radio DONE
07-27 08:54:02.903  2875  2875 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-27 08:54:02.910   545  1292 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-27 08:54:02.930  2875  2875 D AndroidRuntime: Shutting down VM
07-27 08:54:02.940  1077  2723 W SearchService: Abort, client detached.
07-27 08:54:02.955  1077  1326 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@d4fda47
07-27 08:54:02.956  1077  1077 I HotwordDetector: Closing mic
07-27 08:54:02.957   545  1852 I ActivityManager: Start proc 2884:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-27 08:54:02.970   223   644 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
07-27 08:54:02.977  1077  1328 I MicroRecognitionRnrImpl: Stopping hotword detection.
07-27 08:54:02.981  1077  1332 I MicroRecognitionRnrImpl: Detection finished
07-27 08:54:03.073  2884  2884 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
07-27 08:54:03.187  2884  2884 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
07-27 08:54:03.210  2884  2884 I LibraryLoader: Time to load native libraries: 14 ms (timestamps 5764-5778)
07-27 08:54:03.210  2884  2884 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 08:54:03.250  2884  2884 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {965a513}
07-27 08:54:03.252  2884  2884 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 08:54:03.252  2884  2884 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-27 08:54:03.257  2884  2884 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-27 08:54:03.258  2884  2884 E SysUtils: ApplicationContext is null in ApplicationStatus
07-27 08:54:03.296  2884  2884 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-27 08:54:03.312  2884  2884 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-27 08:54:03.312  2884  2884 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-27 08:54:03.541   545   590 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2bbc768:true
07-27 08:54:03.629  2884  2884 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-27 08:54:03.647  2884  2884 D SystemWebViewEngine: CordovaWebView is running on device made by: htc
07-27 08:54:03.707  2884  2926 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
07-27 08:54:03.723  2884  2912 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
07-27 08:54:03.753  2884  2926 I OpenGLRenderer: Initialized EGL, version 1.4
07-27 08:54:03.844   545   591 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +897ms
07-27 08:54:03.849   987   987 I Keyboard.Facilitator: onFinishInput()
07-27 08:54:03.910  2884  2884 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 2884
07-27 08:54:03.918   545  1851 I ActivityManager: Killing 2543:com.google.android.gm.exchange/u0a70 (adj 15): empty #17
07-27 08:54:03.959   545  1851 I ActivityManager: Killing 1953:com.google.android.talk/u0a56 (adj 15): empty #18
07-27 08:54:04.025  2884  2884 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-27 08:54:04.189  2884  2927 D jxcore_app_log: JniHelper::setJavaVM(0xab8d87b8), pthread_self() = -539104976
,07-27 08:54:04.193  2884  2927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-27 08:54:04.193  2884  2927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-27 08:54:04.193  2884  2927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-27 08:54:04.193  2884  2927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-27 08:54:04.193  2884  2927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-27 08:54:04.193  2884  2927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34d1fe6 added. We now have 1 listener(s)
,07-27 08:54:04.196  2884  2927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B4:CE:F6:34:3D:CC
,07-27 08:54:04.197  2884  2927 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
,07-27 08:54:04.198  2884  2927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-27 08:54:04.199  2884  2927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-27 08:54:04.203  2884  2927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-27 08:54:04.203  2884  2927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-27 08:54:04.203  2884  2927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-27 08:54:04.203  2884  2927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B4:CE:F6:34:3D:CC
07-27 08:54:04.203  2884  2927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-27 08:54:04.203  2884  2927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-27 08:54:04.203  2884  2927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-27 08:54:04.203  2884  2927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-27 08:54:04.203  2884  2927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-27 08:54:04.203  2884  2927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-27 08:54:04.203  2884  2927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-27 08:54:04.203  2884  2927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3469d7d added. We now have 1 listener(s)
,07-27 08:54:04.204  2884  2927 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 08:54:04.207   545   663 D WifiService: New client listening to asynchronous messages
,07-27 08:54:04.209  2884  2927 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-27 08:54:04.214  2884  2927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-27 08:54:04.214  2884  2927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,07-27 08:54:04.214  2884  2927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
,07-27 08:54:04.214  2884  2927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-27 08:54:04.216  2884  2927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 08:54:04.216  2884  2927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B4:CE:F6:34:3D:CC
07-27 08:54:04.222  2884  2927 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 08:54:04.222  2884  2927 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:54:04.222  2884  2927 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 08:54:04.222  2884  2927 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 08:54:04.222  2884  2927 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 08:54:04.222  2884  2927 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 08:54:04.222  2884  2927 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 08:54:04.222  2884  2927 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 08:54:04.222  2884  2927 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-27 08:54:04.222  2884  2927 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 08:54:04.223  2884  2927 I io.jxcore.node.LifeCycleMonitor: start: OK
07-27 08:54:04.224  2884  2884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
07-27 08:54:04.225  2884  2884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 08:54:04.254  2884  2884 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-27 08:54:04.791  2884  2934 W jxcore-log: Initializing JXcore engine
,07-27 08:54:04.791  2884  2934 W jxcore-log: JXcore engine is ready
,07-27 08:54:04.833  2934  2934 W Thread-61: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=9257 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,07-27 08:54:04.833  2934  2934 W Thread-61: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9895]" dev="sockfs" ino=9895 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-27 08:54:04.833  2934  2934 W Thread-61: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=1032 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,07-27 08:54:04.833  2934  2934 W Thread-61: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[21289]" dev="sockfs" ino=21289 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-27 08:54:04.848  2884  2934 W jxcore-log: Starting JXcore engine
,07-27 08:54:04.924  2884  2934 W jxcore-log: Platform android
07-27 08:54:04.924  2884  2934 W jxcore-log: 
,07-27 08:54:04.925  2884  2934 W jxcore-log: Process ARCH arm
07-27 08:54:04.925  2884  2934 W jxcore-log: 
,07-27 08:54:05.044  2884  2934 I jxcore-log: JXcore Cordova bridge is ready!
07-27 08:54:05.044  2884  2934 I jxcore-log: 
,07-27 08:54:05.044  2884  2934 W jxcore-log: JXcore engine is started
,07-27 08:54:05.050  2884  2927 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-27 08:54:05.052  2884  2884 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-27 08:54:05.058  2884  2934 E jxcore  : Error!: No such native module /data/user/0/com.test.thalitest/files/www/jxcore/app.js
07-27 08:54:05.058  2884  2934 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-27 08:54:05.063  2884  2884 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/user/0/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/user/0/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,07-27 08:54:05.063  2884  2884 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-27 08:54:05.065   168   174 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (120 us)
,07-27 08:54:05.133  2884  2884 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-27 08:54:05.133  2884  2884 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
07-27 08:54:05.134  2884  2927 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 71ms. Plugin should use CordovaInterface.getThreadPool().
,07-27 08:54:05.145   545   579 I ActivityManager: Killing 2562:com.google.process.gapps/u0a85 (adj 15): empty #17
,07-27 08:54:05.193  2884  2884 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-27 08:54:05.194  2884  2884 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
07-27 08:54:05.194  2884  2884 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-27 08:54:05.194  2884  2884 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-27 08:54:05.194  2884  2884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 08:54:05.194  2884  2884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 08:54:05.194  2884  2884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 08:54:05.194  2884  2884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-27 08:54:05.194  2884  2884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34d1fe6 removed from the list
,07-27 08:54:05.194  2884  2884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-27 08:54:05.194  2884  2884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3469d7d removed from the list
07-27 08:54:05.194  2884  2884 D io.jxcore.node.ConnectivityMonitor: stop
07-27 08:54:05.194  2884  2884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
07-27 08:54:05.199  2884  2884 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-27 08:54:05.226   987   987 I Keyboard.Facilitator: onFinishInput()
,07-27 08:54:05.270  1077  1077 W ThreadPoolDumper: Queue length for executor AudioRouter with 1 threads is now 8. Perhaps some tasks are too long, or the pool is too small.
07-27 08:54:05.287  1077  1077 W LocationOracleImpl: Best location was null
07-27 08:54:05.335  1077  2945 I MicroRecognitionRnrImpl: Starting detection.
07-27 08:54:05.337  1077  2946 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@bd2b38
,07-27 08:54:05.340   223   644 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,07-27 08:54:05.347   223  2948 I AudioFlinger: AudioFlinger's thread 0xaba3a460 ready to run
,07-27 08:54:05.348  1077  2946 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@bd2b38
,07-27 08:54:05.530   999  1202 W GCoreFlp: No location to return for getLastLocation()
,07-27 08:54:05.532  1077  1077 I HotwordWorkerImpl: onReady
,07-27 08:54:05.552   999  1202 W GCoreFlp: No location to return for getLastLocation()
,07-27 08:54:05.583   999  1202 W GCoreFlp: No location to return for getLastLocation()
,07-27 08:54:05.589   999  1202 W GCoreFlp: No location to return for getLastLocation()
,07-27 08:54:05.655  2938  2938 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,07-27 08:54:05.660  2938  2938 D AndroidRuntime: CheckJNI is OFF
,07-27 08:54:05.700  2938  2938 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,07-27 08:54:05.736  2938  2938 I Radio-JNI: register_android_hardware_Radio DONE
,07-27 08:54:05.752  1035  1280 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,07-27 08:54:05.762  2938  2938 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-27 08:54:05.768   545   579 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,07-27 08:54:05.769   545   579 I ActivityManager: Killing 2884:com.test.thalitest/u0a0 (adj 9): stop com.test.thalitest
,07-27 08:54:05.792   545   564 D GraphicsStats: Buffer count: 2
,07-27 08:54:05.792   545   663 D WifiService: Client connection lost with reason: 4
,07-27 08:54:05.825   545   604 W PackageSettings: Skipping PackageSetting{88491db com.example.hello/10095} due to missing metadata
,07-27 08:54:05.827   545   755 W ActivityManager: Spurious death for ProcessRecord{ebca86c 0:com.test.thalitest/u0a0}, curProc for 2884: null
,07-27 08:54:05.848   545   604 I art     : Starting a blocking GC Explicit
,07-27 08:54:05.890   545   604 I art     : Explicit concurrent mark sweep GC freed 16980(1005KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 17MB/26MB, paused 623us total 41.090ms
,07-27 08:54:05.896   545   604 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,07-27 08:54:05.898  2938  2938 I art     : System.exit called, status: 0
,07-27 08:54:05.898  2938  2938 I AndroidRuntime: VM exiting with result code 0.
,07-27 08:54:05.902   545   604 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,07-27 08:54:05.944  1029  1029 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,07-27 08:54:05.946   999  1249 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-27 08:54:05.955   545   654 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-27 08:54:05.963   987   987 I Keyboard.Facilitator: resetDictionaries() : en_US
,07-27 08:54:05.993   987  2966 I Keyboard.Facilitator.DecoderInitializer: run()
,07-27 08:54:05.999  2493  2969 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,07-27 08:54:06.027   545   660 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,07-27 08:54:06.044  2493  2507 E SQLiteLog: (14) cannot open file at line 31278 of [2ef4f3a5b1]
,07-27 08:54:06.044  2493  2507 E SQLiteLog: (14) os_unix.c:31278: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjDD60C89A7) - 
,07-27 08:54:06.048   545   545 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-27 08:54:06.058   987  2966 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
,07-27 08:54:06.058   987  2966 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
,07-27 08:54:06.058   987  2966 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,07-27 08:54:06.058   987  2966 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,07-27 08:54:06.059   987  2966 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
07-27 08:54:06.059   987  2966 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,07-27 08:54:06.079  1085  1085 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,07-27 08:54:06.090  1035  1109 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,07-27 08:54:06.090   545   578 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,07-27 08:54:06.092   987  2966 I Decoder : createOrResetDecoder
,--------- beginning of crash
07-27 08:54:06.119  2493  2507 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
07-27 08:54:06.119  2493  2507 E AndroidRuntime: Process: android.process.acore, PID: 2493
07-27 08:54:06.119  2493  2507 E AndroidRuntime: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
07-27 08:54:06.119  2493  2507 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-27 08:54:06.119  2493  2507 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
07-27 08:54:06.119  2493  2507 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
07-27 08:54:06.119  2493  2507 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
07-27 08:54:06.119  2493  2507 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
07-27 08:54:06.119  2493  2507 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
07-27 08:54:06.119  2493  2507 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
07-27 08:54:06.119  2493  2507 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
07-27 08:54:06.119  2493  2507 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
07-27 08:54:06.119  2493  2507 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:54:06.119  2493  2507 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-27 08:54:06.119  2493  2507 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 08:54:06.121  1085  1085 D AndroidRuntime: Shutting down VM
,07-27 08:54:06.134   545  1851 I ActivityManager: Start proc 2972:com.google.android.googlequicksearchbox:crash_report/u0a22 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,07-27 08:54:06.135  1035  1109 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
07-27 08:54:06.135  1035  1109 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1035
07-27 08:54:06.135  1035  1109 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-27 08:54:06.135  1035  1109 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-27 08:54:06.135  1035  1109 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
07-27 08:54:06.135  1035  1109 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-27 08:54:06.135  1035  1109 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-27 08:54:06.135  1035  1109 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
07-27 08:54:06.135  1035  1109 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
07-27 08:54:06.135  1035  1109 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
07-27 08:54:06.135  1035  1109 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 08:54:06.135  1035  1109 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 08:54:06.135  1035  1109 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-27 08:54:06.135  1035  1109 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-27 08:54:06.136  1085  1085 E AndroidRuntime: FATAL EXCEPTION: main
07-27 08:54:06.136  1085  1085 E AndroidRuntime: Process: com.google.process.gapps, PID: 1085
07-27 08:54:06.136  1085  1085 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-27 08:54:06.136  1085  1085 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
07-27 08:54:06.136  1085  1085 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
07-27 08:54:06.136  1085  1085 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
07-27 08:54:06.136  1085  1085 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:54:06.136  1085  1085 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-27 08:54:06.136  1085  1085 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 08:54:06.136  1085  1085 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:54:06.136  1085  1085 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 08:54:06.136  1085  1085 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 08:54:06.136  1085  1085 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-27 08:54:06.136  1085  1085 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-27 08:54:06.136  1085  1085 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
07-27 08:54:06.136  1085  1085 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-27 08:54:06.136  1085  1085 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-27 08:54:06.136  1085  1085 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
07-27 08:54:06.136  1085  1085 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
07-27 08:54:06.136  1085  1085 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
07-27 08:54:06.136  1085  1085 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
07-27 08:54:06.136  1085  1085 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
07-27 08:54:06.136  1085  1085 E AndroidRuntime: 	... 8 more
,07-27 08:54:06.153  2493  2969 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
07-27 08:54:06.168  2493  2969 I Process : Sending signal. PID: 2493 SIG: 9

```
