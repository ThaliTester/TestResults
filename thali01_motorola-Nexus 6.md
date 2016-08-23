#### Test 82337235c72b2f9_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-23 13:54:25.025   872  2074 D NetlinkSocketObserver: NeighborEvent{elapsedMs=119410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-23 13:54:25.565  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-23 13:54:25.570  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-23 13:54:25.571  1496  1496 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-23 13:54:25.590  1496  3572 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-23 13:54:25.590  1496  3572 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-23 13:54:25.590  1496  3572 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 13:54:25.590  1496  3572 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-23 13:54:25.609  3489  3489 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-23 13:54:25.609  3489  3489 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-23 13:54:25.610  3489  3489 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-23 13:54:25.742  3732  3732 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-23 13:54:25.747  3732  3732 D AndroidRuntime: CheckJNI is OFF
08-23 13:54:25.790  3732  3732 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-23 13:54:25.842  3732  3732 I Radio-JNI: register_android_hardware_Radio DONE
08-23 13:54:25.864  3732  3732 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-23 13:54:25.869   872   882 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-23 13:54:25.903  2013  2024 W SearchService: Abort, client detached.
08-23 13:54:25.909  2013  2013 I HotwordDetector: Closing mic
08-23 13:54:25.910  2013  2340 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@63a0231
08-23 13:54:25.920  3732  3732 D AndroidRuntime: Shutting down VM
08-23 13:54:25.959   872  1938 I ActivityManager: Start proc 3741:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-23 13:54:25.977   376  2354 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-23 13:54:25.978   376  2354 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-23 13:54:25.983   376  1277 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-23 13:54:25.985  2013  2351 I MicroRecognitionRnrImpl: Detection finished
08-23 13:54:25.986  2013  2345 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-23 13:54:26.040  3741  3741 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-23 13:54:26.070  3741  3741 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-23 13:54:26.082  3741  3741 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 462-468)
08-23 13:54:26.083  3741  3741 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 13:54:26.102  3741  3741 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d37f719}
08-23 13:54:26.102  3741  3741 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 13:54:26.103  3741  3741 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-23 13:54:26.111  3741  3741 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-23 13:54:26.113  3741  3741 E SysUtils: ApplicationContext is null in ApplicationStatus
08-23 13:54:26.136  3741  3741 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-23 13:54:26.162  3741  3741 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 13:54:26.162  3741  3741 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 13:54:26.162  3741  3741 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-23 13:54:26.162  3741  3741 I Adreno  : Build Date                       : 10/20/15
08-23 13:54:26.162  3741  3741 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-23 13:54:26.162  3741  3741 I Adreno  : Local Branch                     : M14
08-23 13:54:26.162  3741  3741 I Adreno  : Remote Branch                    : 
08-23 13:54:26.162  3741  3741 I Adreno  : Remote Branch                    : 
08-23 13:54:26.162  3741  3741 I Adreno  : Reconstruct Branch               : 
,08-23 13:54:26.250   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@818b373:true
,08-23 13:54:26.337  3741  3741 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-23 13:54:26.367  3741  3741 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-23 13:54:26.465  3741  3780 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-23 13:54:26.477  3741  3766 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-23 13:54:26.524  3741  3780 I OpenGLRenderer: Initialized EGL, version 1.4
,08-23 13:54:26.575   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +652ms
,08-23 13:54:26.576  1866  1866 I Keyboard.Facilitator: onFinishInput()
,08-23 13:54:26.640  3741  3741 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3741
,08-23 13:54:26.782   872  1991 I ActivityManager: Killing 2966:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-23 13:54:26.800  3741  3741 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 13:54:26.829   872  1991 I ActivityManager: Killing 3082:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-23 13:54:26.984  3741  3782 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1695811280
,08-23 13:54:26.998  3741  3782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 13:54:26.998  3741  3782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 13:54:26.998  3741  3782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 13:54:26.998  3741  3782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 13:54:26.998  3741  3782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-23 13:54:26.999  3741  3782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53d7de4 added. We now have 1 listener(s)
,08-23 13:54:27.003  3741  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-23 13:54:27.005  3741  3782 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 13:54:27.006  3741  3782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 13:54:27.006  3741  3782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 13:54:27.012  3741  3782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 13:54:27.012  3741  3782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 13:54:27.012  3741  3782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 13:54:27.012  3741  3782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-23 13:54:27.012  3741  3782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 13:54:27.012  3741  3782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 13:54:27.012  3741  3782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 13:54:27.012  3741  3782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 13:54:27.012  3741  3782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 13:54:27.012  3741  3782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 13:54:27.012  3741  3782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 13:54:27.012  3741  3782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 13:54:27.012  3741  3782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 13:54:27.012  3741  3782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-23 13:54:27.012  3741  3782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c459a13 added. We now have 1 listener(s)
08-23 13:54:27.012  3741  3782 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 13:54:27.017   872  1306 D WifiService: New client listening to asynchronous messages
,08-23 13:54:27.019  3741  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 13:54:27.019  3741  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-23 13:54:27.019  3741  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 13:54:27.020  3741  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-23 13:54:27.020  3741  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-23 13:54:27.025  3741  3782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 13:54:27.025  3741  3782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-23 13:54:27.035  3741  3782 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-23 13:54:27.035  3741  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 13:54:27.035  3741  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 13:54:27.035  3741  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 13:54:27.035  3741  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 13:54:27.035  3741  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 13:54:27.035  3741  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 13:54:27.035  3741  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 13:54:27.035  3741  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 13:54:27.035  3741  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 13:54:27.035  3741  3782 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 13:54:27.036  3741  3782 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-23 13:54:27.038  3741  3741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 13:54:27.041  3741  3741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 13:54:27.071  3741  3741 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 13:54:27.644  3741  3751 I art     : Background sticky concurrent mark sweep GC freed 66439(6MB) AllocSpace objects, 17(1116KB) LOS objects, 28% free, 23MB/32MB, paused 668us total 150.981ms
,08-23 13:54:28.307  3741  3792 W jxcore-log: Initializing JXcore engine
,08-23 13:54:28.308  3741  3792 W jxcore-log: JXcore engine is ready
,08-23 13:54:28.362  3792  3792 W Thread-318: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8940 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-23 13:54:28.362  3792  3792 W Thread-318: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[13352]" dev="sockfs" ino=13352 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-23 13:54:28.362  3792  3792 W Thread-318: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-23 13:54:28.362  3792  3792 W Thread-318: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27650]" dev="sockfs" ino=27650 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-23 13:54:28.376  3741  3792 W jxcore-log: Starting JXcore engine
,08-23 13:54:28.454  3741  3792 W jxcore-log: Platform android
08-23 13:54:28.454  3741  3792 W jxcore-log: 
,08-23 13:54:28.454  3741  3792 W jxcore-log: Process ARCH arm
08-23 13:54:28.454  3741  3792 W jxcore-log: 
,08-23 13:54:28.641  3741  3792 I jxcore-log: JXcore Cordova bridge is ready!
08-23 13:54:28.641  3741  3792 I jxcore-log: 
08-23 13:54:28.641  3741  3792 W jxcore-log: JXcore engine is started
,08-23 13:54:28.649  3741  3782 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-23 13:54:28.656  3741  3741 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 13:54:28.706  3741  3792 E jxcore  : Error!: missing name after . operator
08-23 13:54:28.706  3741  3792 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"591","_columnNumber":"9","_msg":"    at $w.prototype._compile@module.js:591:9"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"407","_columnNumber":"1","_msg":"    at $w._load@module.js:407:1"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:260:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,08-23 13:54:28.722  3741  3741 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "missing name after . operator\nSyntaxError: missing name after . operator\n    at $w.prototype._compile@module.js:591:9\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1\n    at $w._load@module.js:407:1\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at internal_methods.loadMainFile@main.js:260:5\n    at JXMobile.executeJSON@main.js:279:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (56)
,08-23 13:54:28.724  3741  3741 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
,08-23 13:54:28.728   283   348 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (374 us)
,08-23 13:54:28.766  3741  3741 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-23 13:54:28.767  3741  3741 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
08-23 13:54:28.769  3741  3782 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 43ms. Plugin should use CordovaInterface.getThreadPool().
,08-23 13:54:28.791   872   885 I ActivityManager: Killing 3185:com.google.android.gm/u0a78 (adj 15): empty #17
,08-23 13:54:28.844  3741  3741 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-23 13:54:28.844  3741  3741 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-23 13:54:28.844  3741  3741 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-23 13:54:28.844  3741  3741 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,08-23 13:54:28.844  3741  3741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 13:54:28.844  3741  3741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 13:54:28.844  3741  3741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 13:54:28.844  3741  3741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 13:54:28.844  3741  3741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53d7de4 removed from the list
,08-23 13:54:28.845  3741  3741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 13:54:28.845  3741  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c459a13 removed from the list
,08-23 13:54:28.845  3741  3741 D io.jxcore.node.ConnectivityMonitor: stop
08-23 13:54:28.845  3741  3741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
08-23 13:54:28.846  3741  3741 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-23 13:54:28.872  1866  1866 I Keyboard.Facilitator: onFinishInput()
,08-23 13:54:28.932  2013  3801 I MicroRecognitionRnrImpl: Starting detection.
,08-23 13:54:28.934  2013  3802 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@8d9e732
,08-23 13:54:28.936   376  3804 I AudioFlinger: AudioFlinger's thread 0xb1d00000 ready to run
,08-23 13:54:28.940   376  1277 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-23 13:54:28.941  2013  3802 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@8d9e732
,08-23 13:54:28.948   872  1305 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
08-23 13:54:28.951   376  3804 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
,08-23 13:54:28.951   376  3804 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
,08-23 13:54:28.951   376  3804 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
08-23 13:54:28.957   376  3804 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,08-23 13:54:29.035  2013  2013 I HotwordWorkerImpl: onReady
,08-23 13:54:29.400  1961  2251 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,08-23 13:54:29.461  3795  3795 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-23 13:54:29.466  3795  3795 D AndroidRuntime: CheckJNI is OFF
,08-23 13:54:29.516  3795  3795 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-23 13:54:29.561  3795  3795 I Radio-JNI: register_android_hardware_Radio DONE
,08-23 13:54:29.583  3795  3795 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-23 13:54:29.590   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-23 13:54:29.591   872   885 I ActivityManager: Killing 3741:com.test.thalitest/u0a0 (adj 9): stop com.test.thalitest
,08-23 13:54:29.661   872  1938 D GraphicsStats: Buffer count: 2
,08-23 13:54:29.661   872  1306 D WifiService: Client connection lost with reason: 4
,08-23 13:54:29.679   872  1939 W ActivityManager: Spurious death for ProcessRecord{97ebc97 0:com.test.thalitest/u0a0}, curProc for 3741: null
,08-23 13:54:29.692   872   895 W PackageSettings: Skipping PackageSetting{82258dc com.example.hello/10273} due to missing metadata
,08-23 13:54:29.738   872   895 I art     : Starting a blocking GC Explicit
,08-23 13:54:29.788  1364  1364 W RecentsTaskLoader: Missing ActivityInfo for ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} u=0
,08-23 13:54:29.820   872   895 I art     : Explicit concurrent mark sweep GC freed 21653(1427KB) AllocSpace objects, 7(156KB) LOS objects, 33% free, 28MB/43MB, paused 736us total 78.851ms
,08-23 13:54:29.856   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-23 13:54:29.862  3795  3795 I art     : System.exit called, status: 0
,08-23 13:54:29.862  3795  3795 I AndroidRuntime: VM exiting with result code 0.
,08-23 13:54:29.865   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-23 13:54:29.904  1866  1866 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-23 13:54:29.906  2676  2676 D BluetoothMapAppObserver: onReceive
08-23 13:54:29.906  2676  2676 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-23 13:54:29.907  1880  2280 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 13:54:29.911  3580  3580 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-23 13:54:29.918   872  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-23 13:54:29.930  1866  3815 I Keyboard.Facilitator.DecoderInitializer: run()
,08-23 13:54:29.953  1949  1949 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-23 13:54:29.967  1866  3815 I Decoder : createOrResetDecoder
,08-23 13:54:29.979  1496  1496 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
08-23 13:54:29.980  1496  1496 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-23 13:54:29.986   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-23 13:54:29.987  1690  3819 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-23 13:54:30.002  1496  1496 I ConfigService: onCreate
,08-23 13:54:30.003  1690  1731 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj7D1F1F917) - 
,08-23 13:54:30.003  1710  3821 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-23 13:54:30.004  1710  3821 D AccountUtils: Clearing selected account for com.test.thalitest
08-23 13:54:30.004  1496  3822 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-23 13:54:30.004  1496  3822 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 13:54:30.004  1496  3822 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 13:54:30.004  1496  3822 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 13:54:30.004  1496  3822 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 13:54:30.004  1496  3822 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 13:54:30.004  1496  3822 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 13:54:30.004  1496  3822 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 13:54:30.004  1496  3822 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 13:54:30.004  1496  3822 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 13:54:30.004  1496  3822 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 13:54:30.004  1496  3822 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 13:54:30.004  1496  3822 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 13:54:30.004  1496  3822 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 13:54:30.004  1496  3822 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-23 13:54:30.004  1496  3822 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-23 13:54:30.004  1496  3822 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-23 13:54:30.004  1496  3822 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-23 13:54:30.004  1496  3822 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-23 13:54:30.004  1496  3822 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 13:54:30.004  1496  3822 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 13:54:30.004  1496  3822 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 13:54:30.004  1496  3822 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 13:54:30.004  1496  3822 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 13:54:30.004  1496  3822 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 13:54:30.004  1496  3822 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 13:54:30.004  1496  3822 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 13:54:30.004  1496  3822 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 13:54:30.004  1496  3822 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 13:54:30.004  1496  3822 E SQLiteOpenHelper: 	at andr,oid.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 13:54:30.004  1496  3822 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 13:54:30.004  1496  3822 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 13:54:30.004  1496  3822 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-23 13:54:30.004  1496  3822 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-23 13:54:30.004  1496  3822 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-23 13:54:30.004  1496  3822 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-23 13:54:30.006  1496  3822 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-23 13:54:30.016  1710  3821 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-23 13:54:30.019  1866  3815 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-23 13:54:30.036  1710  3821 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
08-23 13:54:30.036  1710  3821 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 13:54:30.036  1710  3821 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 13:54:30.036  1710  3821 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 13:54:30.036  1710  3821 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 13:54:30.036  1710  3821 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 13:54:30.036  1710  3821 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 13:54:30.036  1710  3821 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 13:54:30.036  1710  3821 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 13:54:30.036  1710  3821 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 13:54:30.036  1710  3821 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 13:54:30.036  1710  3821 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 13:54:30.036  1710  3821 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 13:54:30.036  1710  3821 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 13:54:30.036  1710  3821 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 13:54:30.036  1710  3821 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-23 13:54:30.036  1710  3821 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-23 13:54:30.036  1710  3821 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-23 13:54:30.036  1710  3821 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:54:30.036  1710  3821 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-23 13:54:30.036  1710  3821 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 13:54:30.036  1710  3821 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
08-23 13:54:30.036  1710  3821 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 13:54:30.036  1710  3821 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 13:54:30.036  1710  3821 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 13:54:30.036  1710  3821 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 13:54:30.036  1710  3821 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 13:54:30.036  1710  3821 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 13:54:30.036  1710  3821 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 13:54:30.036  1710  3821 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 13:54:30.036  1710  3821 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 13:54:30.036  1710  3821 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 13:54:30.036  1710  3821 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 13:54:30.036  1710  3821 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 13:54:30.036  1710  3821 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 13:54:30.036  1710  3821 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 13:54:30.036  1710  3821 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-23 13:54:30.036  1710  3821 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-23 13:54:30.036  1710  3821 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-23 13:54:30.036  1710  3821 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:54:30.036  1710  3821 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-23 13:54:30.036  1710  3821 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 13:54:30.037  1961  2052 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-23 13:54:30.038  1710  3821 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,08-23 13:54:30.040   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-23 13:54:30.040   872   884 E PackageManager: Failed to write settings, restoring backup
08-23 13:54:30.040   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-23 13:54:30.040   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-23 13:54:30.040   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-23 13:54:30.040   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-23 13:54:30.040   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-23 13:54:30.040   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:54:30.040   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-23 13:54:30.040   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 13:54:30.047   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-23 13:54:30.047   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-23 13:54:30.047   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 13:54:30.047   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 13:54:30.047   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 13:54:30.047   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 13:54:30.047   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 13:54:30.047   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 13:54:30.047   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-23 13:54:30.047   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-23 13:54:30.047   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-23 13:54:30.047   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 13:54:30.047   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 13:54:30.047   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-23 13:54:30.047   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 13:54:30.047   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-23 13:54:30.047   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 13:54:30.047   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 13:54:30.047   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 13:54:30.047   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 13:54:30.047   872   885 E DropBoxManagerService: 	... 13 more
,08-23 13:54:30.050   872  2245 I ActivityManager: Start proc 3827:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-23 13:54:30.050  1961  2052 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-23 13:54:30.050  1961  2052 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1961
08-23 13:54:30.050  1961  2052 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 13:54:30.050  1961  2052 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-23 13:54:30.050  1961  2052 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-23 13:54:30.050  1961  2052 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-23 13:54:30.050  1961  2052 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 13:54:30.050  1961  2052 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-23 13:54:30.050  1961  2052 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-23 13:54:30.050  1961  2052 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-23 13:54:30.050  1961  2052 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 13:54:30.050  1961  2052 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 13:54:30.050  1961  2052 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 13:54:30.050  1961  2052 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 13:54:30.053   872  2081 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-23 13:54:30.055   872  3837 E DropBoxManagerService: Can't write: system_app_crash
08-23 13:54:30.055   872  3837 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
08-23 13:54:30.055   872  3837 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 13:54:30.055   872  3837 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 13:54:30.055   872  3837 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 13:54:30.055   872  3837 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 13:54:30.055   872  3837 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 13:54:30.055   872  3837 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 13:54:30.055   872  3837 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 13:54:30.055   872  3837 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 13:54:30.055   872  3837 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 13:54:30.055   872  3837 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 13:54:30.055   872  3837 E DropBoxManagerService: 	... 5 more
08-23 13:54:30.056  1710  3833 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-23 13:54:30.056  2013  2437 W SearchService: Abort, client detached.
,08-23 13:54:30.056  1710  3833 E DriveAsyncService: disk I/O error (code 3850)
08-23 13:54:30.056  1710  3833 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 13:54:30.056  1710  3833 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-23 13:54:30.056  1710  3833 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-23 13:54:30.056  1710  3833 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-23 13:54:30.056  1710  3833 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-23 13:54:30.056  1710  3833 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-23 13:54:30.056  1710  3833 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-23 13:54:30.056  1710  3833 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.k(SourceFile:483)
08-23 13:54:30.056  1710  3833 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(SourceFile:458)
08-23 13:54:30.056  1710  3833 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.i(SourceFile:1501)
08-23 13:54:30.056  1710  3833 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bj.a(SourceFile:16)
08-23 13:54:30.056  1710  3833 E DriveAsyncService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-23 13:54:30.056  1710  3833 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 13:54:30.056  1710  3833 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 13:54:30.056  1710  3833 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
,08-23 13:54:30.058  1710  1710 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-23 13:54:30.058  1710  1710 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-23 13:54:30.060  1710  3834 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/metrics.db'.
08-23 13:54:30.060  1710  3834 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 13:54:30.060  1710  3834 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 13:54:30.060  1710  3834 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 13:54:30.060  1710  3834 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 13:54:30.060  1710  3834 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 13:54:30.060  1710  3834 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 13:54:30.060  1710  3834 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 13:54:30.060  1710  3834 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 13:54:30.060  1710  3834 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 13:54:30.060  1710  3834 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 13:54:30.060  1710  3834 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 13:54:30.060  1710  3834 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 13:54:30.060  1710  3834 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 13:54:30.060  1710  3834 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-23 13:54:30.060  1710  3834 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
08-23 13:54:30.060  1710  3834 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
08-23 13:54:30.060  1710  3834 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
08-23 13:54:30.060  1710  3834 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-23 13:54:30.060  1710  3834 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-23 13:54:30.060  1710  3834 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:54:30.060  1710  3834 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-23 13:54:30.060  1710  3834 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 13:54:30.061  1710  3834 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
08-23 13:54:30.061  1710  3834 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 13:54:30.061  1710  3834 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 13:54:30.061  1710  3834 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 13:54:30.061  1710  3834 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 13:54:30.061  1710  3834 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 13:54:30.061  1710  3834 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.ope,n(SQLiteConnectionPool.java:185)
08-23 13:54:30.061  1710  3834 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 13:54:30.061  1710  3834 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 13:54:30.061  1710  3834 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 13:54:30.061  1710  3834 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 13:54:30.061  1710  3834 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 13:54:30.061  1710  3834 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 13:54:30.061  1710  3834 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 13:54:30.061  1710  3834 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-23 13:54:30.061  1710  3834 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
08-23 13:54:30.061  1710  3834 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
08-23 13:54:30.061  1710  3834 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
08-23 13:54:30.061  1710  3834 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-23 13:54:30.061  1710  3834 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-23 13:54:30.061  1710  3834 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:54:30.061  1710  3834 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-23 13:54:30.061  1710  3834 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 13:54:30.063  1710  3834 W SQLiteOpenHelper: Opened metrics.db in read-only mode
08-23 13:54:30.063  1710  3834 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
08-23 13:54:30.063  1710  3834 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
08-23 13:54:30.064  1710  3834 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
08-23 13:54:30.064  1710  3834 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
08-23 13:54:30.064  2013  2013 I HotwordDetector: Closing mic
08-23 13:54:30.065  1710  3834 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
08-23 13:54:30.065  1710  3834 E AndroidRuntime: Process: com.google.android.gms, PID: 1710
08-23 13:54:30.065  1710  3834 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-23 13:54:30.065  1710  3834 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-23 13:54:30.065  1710  3834 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-23 13:54:30.065  1710  3834 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-23 13:54:30.065  1710  3834 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 13:54:30.065  1710  3834 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-23 13:54:30.065  1710  3834 E AndroidRuntime: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
08-23 13:54:30.065  1710  3834 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-23 13:54:30.065  1710  3834 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-23 13:54:30.065  1710  3834 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:54:30.065  1710  3834 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 13:54:30.065  1710  3834 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 13:54:30.065  2013  2340 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@8d9e732
08-23 13:54:30.065  2013  3802 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-23 13:54:30.066  1690  3819 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
08-23 13:54:30.067  1690  3819 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-23 13:54:30.067  1690  3819 E AndroidRuntime: Process: android.process.acore, PID: 1690
08-23 13:54:30.067  1690  3819 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 13:54:30.067  1690  3819 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-23 13:54:30.067  1690  3819 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-23 13:54:30.067  1690  3819 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-23 13:54:30.067  1690  3819 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 13:54:30.067  1690  3819 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-23 13:54:30.067  1690  3819 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-23 13:54:30.067  1690  3819 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
08-23 13:54:30.067  1690  3819 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-23 13:54:30.067  1690  3819 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-23 13:54:30.067  1690  3819 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-23 13:54:30.067  1690  3819 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-23 13:54:30.067  1690  3819 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-23 13:54:30.067  1690  3819 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-23 13:54:30.067  1690  3819 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:54:30.067  1690  3819 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 13:54:30.067  1690  3819 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 13:54:30.071   872  3844 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-23 13:54:30.072  1690  1731 I Process : Sending signal. PID: 1690 SIG: 9
08-23 13:54:30.076  1710  1710 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-23 13:54:30.076  1710  1710 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-23 13:54:30.081   872  3845 E DropBoxManagerService: Can't write: system_app_crash
08-23 13:54:30.081   872  3845 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
08-23 13:54:30.081   872  3845 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 13:54:30.081   872  3845 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 13:54:30.081   872  3845 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 13:54:30.081   872  3845 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 13:54:30.081   872  3845 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 13:54:30.081   872  3845 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 13:54:30.081   872  3845 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 13:54:30.081   872  3845 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 13:54:30.081   872  3845 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 13:54:30.081   872  3845 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 13:54:30.081   872  3845 E DropBoxManagerService: 	... 5 more
08-23 13:54:30.082  1710  3848 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-23 13:54:30.083  2013  3846 E Search.SharedPreferencesProto: Failed to rename to backup file /data/user/0/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
08-23 13:54:30.085  1710  3821 E GMPM-SVC: Scheduler not initialized or shutdown. Not logging error/warn.
08-23 13:54:30.091   872  3847 E DropBoxManagerService: Can't write: system_app_crash
08-23 13:54:30.091   872  3847 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
08-23 13:54:30.091   872  3847 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 13:54:30.091   872  3847 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 13:54:30.091   872  3847 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 13:54:30.091   872  3847 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 13:54:30.091   872  3847 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 13:54:30.091   872  3847 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 13:54:30.091   872  3847 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 13:54:30.091   872  3847 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 13:54:30.091   872  3847 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 13:54:30.091   872  3847 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 13:54:30.091   872  3847 E DropBoxManagerService: 	... 5 more
08-23 13:54:30.094   281   281 E lowmemorykiller: Error writing /proc/1690/oom_score_adj; errno=22
08-23 13:54:30.095   281   281 E lowmemorykiller: Error writing /proc/1690/oom_score_adj; errno=22
,08-23 13:54:30.116   376  3804 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,08-23 13:54:30.117   376  3804 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-23 13:54:30.121   376  1277 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-23 13:54:30.123  2013  3801 I MicroRecognitionRnrImpl: Detection finished
08-23 13:54:30.126  1710  3848 I Process : Sending signal. PID: 1710 SIG: 9
08-23 13:54:30.128  2013  2345 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-23 13:54:30.138   872  3844 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-23 13:54:30.138   872  3844 I Adreno  : Build Date                       : 10/20/15
08-23 13:54:30.138   872  3844 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-23 13:54:30.138   872  3844 I Adreno  : Local Branch                     : M14
08-23 13:54:30.138   872  3844 I Adreno  : Remote Branch                    : 
08-23 13:54:30.138   872  3844 I Adreno  : Remote Branch                    : 
08-23 13:54:30.138   872  3844 I Adreno  : Reconstruct Branch               : 
08-23 13:54:30.143   872  3844 I OpenGLRenderer: Initialized EGL, version 1.4
08-23 13:54:30.148   872  2239 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-23 13:54:30.159  1961  1961 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@10f5178 new=com.google.android.velvet.VelvetApplication@10f5178
08-23 13:54:30.169  1866  3815 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-23 13:54:30.178  1866  3815 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-23 13:54:30.178  1866  3815 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-23 13:54:30.179  1866  3815 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-23 13:54:30.179  1866  3815 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-23 13:54:30.180  1866  3815 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-23 13:54:30.180  1866  3815 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-23 13:54:30.187  1866  3815 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-23 13:54:30.187  1866  3815 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-23 13:54:30.187  1866  3815 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-23 13:54:30.189   281   281 E lowmemorykiller: Error writing /proc/1690/oom_score_adj; errno=22
08-23 13:54:30.189   281   281 E lowmemorykiller: Error writing /proc/1690/oom_score_adj; errno=22
,08-23 13:54:30.195  1866  3815 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-23 13:54:30.195  2013  3852 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-23 13:54:30.196  1866  3815 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-23 13:54:30.197  1866  3815 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-23 13:54:30.216  1961  1961 I GEL     : handleIntent(Intent { act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL })
,08-23 13:54:30.232  2013  3852 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-23 13:54:30.261   872  1938 I ActivityManager: Start proc 3863:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,08-23 13:54:30.264   872   890 I ActivityManager: Displayed com.google.android.googlequicksearchbox/com.google.android.launcher.GEL: +113ms,
08-23 13:54:30.275  1496  3868 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
08-23 13:54:30.275  1496  3868 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 13:54:30.275  1496  3868 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 13:54:30.275  1496  3868 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 13:54:30.275  1496  3868 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 13:54:30.275  1496  3868 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 13:54:30.275  1496  3868 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 13:54:30.275  1496  3868 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 13:54:30.275  1496  3868 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 13:54:30.275  1496  3868 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 13:54:30.275  1496  3868 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 13:54:30.275  1496  3868 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 13:54:30.275  1496  3868 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 13:54:30.275  1496  3868 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 13:54:30.275  1496  3868 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 13:54:30.275  1496  3868 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-23 13:54:30.275  1496  3868 E SQLiteDatabase: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:100)
08-23 13:54:30.275  1496  3868 E SQLiteDatabase: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532),
08-23 13:54:30.275  1496  3868 E SQLiteDatabase: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-23 13:54:30.275  1496  3868 E SQLiteDatabase: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-23 13:54:30.275  1496  3868 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 13:54:30.275  1496  3868 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 13:54:30.275  1496  3868 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-23 13:54:30.275  1496  3868 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
08-23 13:54:30.275  1496  3868 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 13:54:30.275  1496  3868 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 13:54:30.275  1496  3868 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 13:54:30.275  1496  3868 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 13:54:30.275  1496  3868 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 13:54:30.275  1496  3868 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 13:54:30.275  1496  3868 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 13:54:30.275  1496  3868 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 13:54:30.275  1496  3868 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 13:54:30.275  1496  3868 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 13:54:30.275  1496  3868 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 13:54:30.275  1496  3868 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 13:54:30.275  1496  3868 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 13:54:30.275  1496  3868 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 13:54:30.275  1496  3868 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-23 13:54:30.275  1496  3868 E SQLiteOpenHelper: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:100)
08-23 13:54:30.275  1496  3868 E SQLiteOpenHelper: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-23 13:54:30.275  1496  3868 E SQLiteOpenHelper: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-23 13:54:30.275  1496  3868 E SQLiteOpenHelper: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-23 13:54:30.275  1496  3868 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 13:54:30.275  1496  3868 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 13:54:30.275  1496  3868 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-23 13:54:30.276  1496  3868 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
08-23 13:54:30.276  1496  3868 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
08-23 13:54:30.276  1496  3868 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
08-23 13:54:30.276  1496  3868 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-23 13:54:30.276  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-23 13:54:30.276  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-23 13:54:30.276  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-23 13:54:30.276  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-23 13:54:30.276  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-23 13:54:30.276  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-23 13:54:30.276  1496  3868 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-23 13:54:30.276  1496  3868 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-23 13:54:30.276  1496  3868 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-23 13:54:30.276  1496  3868 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-23 13:54:30.276  1496  3868 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 13:54:30.276  1496  3868 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 13:54:30.276  1496  3868 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,08-23 13:54:30.277  1496  3868 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,08-23 13:54:30.278  1496  3868 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
08-23 13:54:30.278  1496  3868 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-23 13:54:30.278  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-23 13:54:30.278  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-23 13:54:30.278  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-23 13:54:30.278  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-23 13:54:30.278  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-23 13:54:30.278  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-23 13:54:30.278  1496  3868 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-23 13:54:30.278  1496  3868 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-23 13:54:30.278  1496  3868 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-23 13:54:30.278  1496  3868 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-23 13:54:30.278  1496  3868 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 13:54:30.278  1496  3868 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 13:54:30.278  1496  3868 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
08-23 13:54:30.279  1496  3868 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
08-23 13:54:30.279  1496  3868 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
08-23 13:54:30.279  1496  3868 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-23 13:54:30.279  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-23 13:54:30.279  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-23 13:54:30.279  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-23 13:54:30.279  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-23 13:54:30.279  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-23 13:54:30.279  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-23 13:54:30.279  1496  3868 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-23 13:54:30.279  1496  3868 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-23 13:54:30.279  1496  3868 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-23 13:54:30.279  1496  3868 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-23 13:54:30.279  1496  3868 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 13:54:30.279  1496  3868 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoo,lExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 13:54:30.279  1496  3868 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
08-23 13:54:30.280  1496  3868 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
08-23 13:54:30.280  1496  3868 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
08-23 13:54:30.280  1496  3868 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-23 13:54:30.280  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-23 13:54:30.280  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-23 13:54:30.280  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-23 13:54:30.280  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-23 13:54:30.280  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-23 13:54:30.280  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-23 13:54:30.280  1496  3868 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-23 13:54:30.280  1496  3868 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-23 13:54:30.280  1496  3868 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-23 13:54:30.280  1496  3868 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-23 13:54:30.280  1496  3868 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 13:54:30.280  1496  3868 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 13:54:30.280  1496  3868 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
08-23 13:54:30.282  1496  3868 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
08-23 13:54:30.282  1496  3868 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
08-23 13:54:30.282  1496  3868 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-23 13:54:30.282  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-23 13:54:30.282  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-23 13:54:30.282  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-23 13:54:30.282  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-23 13:54:30.282  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-23 13:54:30.282  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-23 13:54:30.282  1496  3868 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-23 13:54:30.282  1496  3868 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-23 13:54:30.282  1496  3868 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-23 13:54:30.282  1496  3868 E ClearcutLoggerIntentService: 	at com.google.android.g,ms.common.service.g.run(SourceFile:178)
08-23 13:54:30.282  1496  3868 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 13:54:30.282  1496  3868 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 13:54:30.282  1496  3868 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
08-23 13:54:30.282  1961  2639 E ReflectionEngine: Failed to save models
08-23 13:54:30.282  1961  2639 E ReflectionEngine: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/files/engine_16: open failed: EROFS (Read-only file system)
08-23 13:54:30.282  1961  2639 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 13:54:30.282  1961  2639 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 13:54:30.282  1961  2639 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 13:54:30.282  1961  2639 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.BT(ReflectionEngine.java:123)
08-23 13:54:30.282  1961  2639 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:240)
08-23 13:54:30.282  1961  2639 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-23 13:54:30.282  1961  2639 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-23 13:54:30.282  1961  2639 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-23 13:54:30.282  1961  2639 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 13:54:30.282  1961  2639 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 13:54:30.282  1961  2639 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 13:54:30.282  1961  2639 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 13:54:30.282  1961  2639 E ReflectionEngine: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-23 13:54:30.282  1961  2639 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 13:54:30.282  1961  2639 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 13:54:30.282  1961  2639 E ReflectionEngine: 	at java.lang.Thread.run(Thread.java:818)
08-23 13:54:30.282  1961  2639 E ReflectionEngine: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-23 13:54:30.282  1961  2639 E ReflectionEngine: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 13:54:30.282  1961  2639 E ReflectionEngine: 	at libcore.io.Posix.open(Native Method)
08-23 13:54:30.282  1961  2639 E ReflectionEngine: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 13:54:30.282  1961  2639 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 13:54:30.282  1961  2639 E ReflectionEngine: 	... 16 more
08-23 13:54:30.283  1496  3868 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
08-23 13:54:30.283  1496  3868 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
08-23 13:54:30.283  1496  3868 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-23 13:54:30.283  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-23 13:54:30.283  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-23 13:54:30.283  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-23 13:54:30.283  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-23 13:54:30.283  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-23 13:54:30.283  1496  3868 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-23 13:54:30.283  1496  3868 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-23 13:54:30.283  1496  3868 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-23 13:54:30.283  1496  3868 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-23 13:54:30.283  1496  3868 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-23 13:54:30.283  1496  3868 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 13:54:30.283  1496  3868 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 13:54:30.283  1496  3868 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
08-23 13:54:30.301  2013  3852 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
08-23 13:54:30.301  2013  3852 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-23 13:54:30.301  2013  3852 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 2013
08-23 13:54:30.301  2013  3852 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 13:54:30.301  2013  3852 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-23 13:54:30.301  2013  3852 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-23 13:54:30.301  2013  3852 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-23 13:54:30.301  2013  3852 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-23 13:54:30.301  2013  3852 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-23 13:54:30.301  2013  3852 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-23 13:54:30.301  2013  3852 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-23 13:54:30.301  2013  3852 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-23 13:54:30.301  2013  3852 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-23 13:54:30.301  2013  3852 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-23 13:54:30.301  2013  3852 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-23 13:54:30.301  2013  3852 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-23 13:54:30.301  2013  3852 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-23 13:54:30.301  2013  3852 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-23 13:54:30.301  2013  3852 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-23 13:54:30.301  2013  3852 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:54:30.301  2013  3852 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 13:54:30.301  2013  3852 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 13:54:30.302  1961  2639 E ObservedEventLogger: Failed to write the stream file
08-23 13:54:30.302  1961  2639 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2431: open failed: EROFS (Read-only file system)
08-23 13:54:30.302  1961  2639 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 13:54:30.302  1961  2639 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 13:54:30.302  1961  2639 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
08-23 13:54:30.302  1961  2639 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
08-23 13:54:30.302  1961  2639 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
08-23 13:54:30.302  1961  2639 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-23 13:54:30.302  1961  2639 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-23 13:54:30.302  1961  2639 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-23 13:54:30.302  1961  2639 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 13:54:30.302  1961  2639 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 13:54:30.302  1961  2639 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 13:54:30.302  1961  2639 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 13:54:30.302  1961  2639 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-23 13:54:30.302  1961  2639 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 13:54:30.302  1961  2639 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 13:54:30.302  1961  2639 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
08-23 13:54:30.302  1961  2639 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-23 13:54:30.302  1961  2639 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 13:54:30.302  1961  2639 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
08-23 13:54:30.302  1961  2639 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 13:54:30.302  1961  2639 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 13:54:30.302  1961  2639 E ObservedEventLogger: 	... 16 more
08-23 13:54:30.303  1961  2639 E ObservedEventLogger: Failed to write the stream file
08-23 13:54:30.303  1961  2639 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2432: open failed: EROFS (Read-only file system)
08-23 13:54:30.303  1961  2639 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 13:54:30.303  1961  2639 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 13:54:30.303  1961  2639 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
08-23 13:54:30.303  1961  2639 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
08-23 13:54:30.303  1961  2639 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
08-23 13:54:30.303  1961  2639 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-23 13:54:30.303  1961  2639 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-23 13:54:30.303  1961  2639 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-23 13:54:30.303  1961  2639 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 13:54:30.303  1961  2639 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 13:54:30.303  1961  2639 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 13:54:30.303  1961  2639 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 13:54:30.303  1961  2639 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-23 13:54:30.303  1961  2639 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 13:54:30.303  1961  2639 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 13:54:30.303  1961  2639 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
08-23 13:54:30.303  1961  2639 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-23 13:54:30.303  1961  2639 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 13:54:30.303  1961  2639 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
08-23 13:54:30.303  1961  2639 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 13:54:30.303  1961  2639 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 13:54:30.303  1961  2639 E ObservedEventLogger: 	... 16 more
08-23 13:54:30.306   872  1992 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
08-23 13:54:30.306   872  1992 I ActivityManager: Killing 2013:com.google.android.googlequicksearchbox:search/u0a28 (adj 5): crash
08-23 13:54:30.307   872  3876 E DropBoxManagerService: Can't write: system_app_crash
08-23 13:54:30.307   872  3876 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
08-23 13:54:30.307   872  3876 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 13:54:30.307   872  3876 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 13:54:30.307   872  3876 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 13:54:30.307   872  3876 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 13:54:30.307   872  3876 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 13:54:30.307   872  3876 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 13:54:30.307   872  3876 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 13:54:30.307   872  3876 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 13:54:30.307   872  3876 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 13:54:30.307   872  3876 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 13:54:30.307   872  3876 E DropBoxManagerService: 	... 5 more
08-23 13:54:30.328  3863  3863 W System  : ClassLoader referenced unknown path: /system/app/KeyChain/lib/arm
08-23 13:54:30.331  3863  3863 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2725 
,08-23 13:54:30.361   872  1675 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@3af15d2)
08-23 13:54:30.362   872  1307 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 13:54:30.363   872  1307 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 13:54:30.373   872  1306 D WifiService: Client connection lost with reason: 4
,08-23 13:54:30.375   872  1992 W ActivityManager: Exception when unbinding service com.google.android.gms/.icing.service.IndexService
08-23 13:54:30.375   872  1992 W ActivityManager: android.os.DeadObjectException
08-23 13:54:30.375   872  1992 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-23 13:54:30.375   872  1992 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
08-23 13:54:30.375   872  1992 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:956)
08-23 13:54:30.375   872  1992 W ActivityManager: 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1874)
08-23 13:54:30.375   872  1992 W ActivityManager: 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2237)
08-23 13:54:30.375   872  1992 W ActivityManager: 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15543)
08-23 13:54:30.375   872  1992 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4567)
08-23 13:54:30.375   872  1992 W ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-23 13:54:30.375   872  1992 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppCrashLocked(ActivityManagerService.java:12031)
08-23 13:54:30.375   872  1992 W ActivityManager: 	at com.android.server.am.ActivityManagerService.makeAppCrashingLocked(ActivityManagerService.java:11933)
08-23 13:54:30.375   872  1992 W ActivityManager: 	at com.android.server.am.ActivityManagerService.crashApplication(ActivityManagerService.java:12622)
08-23 13:54:30.375   872  1992 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12129)
08-23 13:54:30.375   872  1992 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12111)
08-23 13:54:30.375   872  1992 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1458)
08-23 13:54:30.375   872  1992 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
08-23 13:54:30.375   872  1992 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:453)
,08-23 13:54:30.379   872   883 I ActivityManager: Process com.google.android.gms (pid 1710) has died
08-23 13:54:30.381   872   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
08-23 13:54:30.381   872   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigFetchService in 1000ms
08-23 13:54:30.381   872   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 11000ms
08-23 13:54:30.381   872   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 21000ms
,08-23 13:54:30.381   872   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 21000ms
08-23 13:54:30.382   872   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20999ms
08-23 13:54:30.382   872   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.feedback.FeedbackService in 20999ms
08-23 13:54:30.382   872   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 30999ms
08-23 13:54:30.383   872  2239 W ActivityManager: Spurious death for ProcessRecord{269ad85 0:com.google.android.googlequicksearchbox:search/u0a28}, curProc for 2013: null
08-23 13:54:30.383   872  1676 I ActivityManager: Process android.process.acore (pid 1690) has died
,08-23 13:54:30.383   872  1676 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 30997ms
,08-23 13:54:30.417  3863  3878 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.keychain/databases/grants.db'.
08-23 13:54:30.417  3863  3878 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 13:54:30.417  3863  3878 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 13:54:30.417  3863  3878 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 13:54:30.417  3863  3878 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 13:54:30.417  3863  3878 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 13:54:30.417  3863  3878 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 13:54:30.417  3863  3878 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 13:54:30.417  3863  3878 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 13:54:30.417  3863  3878 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 13:54:30.417  3863  3878 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 13:54:30.417  3863  3878 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 13:54:30.417  3863  3878 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 13:54:30.417  3863  3878 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 13:54:30.417  3863  3878 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 13:54:30.417  3863  3878 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-23 13:54:30.417  3863  3878 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-23 13:54:30.417  3863  3878 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-23 13:54:30.417  3863  3878 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:54:30.417  3863  3878 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-23 13:54:30.417  3863  3878 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 13:54:30.421   283   283 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,08-23 13:54:30.421   283   283 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
08-23 13:54:30.421   283   283 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
08-23 13:54:30.421   283   283 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
08-23 13:54:30.421   283   283 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
08-23 13:54:30.421   283   283 E qdoverlay: MdpCtrl close error in unset
,08-23 13:54:30.422  3863  3878 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-23 13:54:30.422  3863  3878 E AndroidRuntime: Process: com.android.keychain, PID: 3863
08-23 13:54:30.422  3863  3878 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 13:54:30.422  3863  3878 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 13:54:30.422  3863  3878 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 13:54:30.422  3863  3878 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 13:54:30.422  3863  3878 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 13:54:30.422  3863  3878 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 13:54:30.422  3863  3878 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 13:54:30.422  3863  3878 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 13:54:30.422  3863  3878 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 13:54:30.422  3863  3878 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 13:54:30.422  3863  3878 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 13:54:30.422  3863  3878 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 13:54:30.422  3863  3878 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 13:54:30.422  3863  3878 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 13:54:30.422  3863  3878 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-23 13:54:30.422  3863  3878 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-23 13:54:30.422  3863  3878 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-23 13:54:30.422  3863  3878 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:54:30.422  3863  3878 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 13:54:30.422  3863  3878 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 13:54:30.428   872   872 I ActivityManager: Start proc 3881:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,08-23 13:54:30.431   872  3886 E DropBoxManagerService: Can't write: system_app_crash
08-23 13:54:30.431   872  3886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
08-23 13:54:30.431   872  3886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 13:54:30.431   872  3886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 13:54:30.431   872  3886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 13:54:30.431   872  3886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 13:54:30.431   872  3886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 13:54:30.431   872  3886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 13:54:30.431   872  3886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 13:54:30.431   872  3886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 13:54:30.431   872  3886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 13:54:30.431   872  3886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 13:54:30.431   872  3886 E DropBoxManagerService: 	... 5 more
,08-23 13:54:30.673   283   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-23 13:54:30.674   283   283 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
,08-23 13:54:30.674   283   283 E qdoverlay: MdpCtrl close error in unset

```
