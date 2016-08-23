#### Test 8233723530fac5a_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-23 12:25:29.862  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 12:25:29.871  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-23 12:25:29.874  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-23 12:25:29.914  1512  2036 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-23 12:25:29.915  1512  2036 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-23 12:25:29.915  1512  2036 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 12:25:29.915  1512  2036 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-23 12:25:29.958  3541  3541 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-23 12:25:29.960  3541  3541 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-23 12:25:29.962  3541  3541 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
08-23 12:25:30.520  3783  3783 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-23 12:25:30.525  3783  3783 D AndroidRuntime: CheckJNI is OFF
08-23 12:25:30.567  3783  3783 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-23 12:25:30.618  3783  3783 I Radio-JNI: register_android_hardware_Radio DONE
08-23 12:25:30.640  3783  3783 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-23 12:25:30.644   871  1375 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-23 12:25:30.679  2012  2026 W SearchService: Abort, client detached.
08-23 12:25:30.683  2012  2323 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@b8b5574
08-23 12:25:30.683  2012  2331 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-23 12:25:30.683  2012  2012 I HotwordDetector: Closing mic
08-23 12:25:30.686  3783  3783 D AndroidRuntime: Shutting down VM
08-23 12:25:30.701   871  1963 I ActivityManager: Start proc 3792:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-23 12:25:30.741   376  2333 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-23 12:25:30.742   376  2333 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-23 12:25:30.752   376  1272 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-23 12:25:30.758  2012  2329 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-23 12:25:30.758  2012  2330 I MicroRecognitionRnrImpl: Detection finished
08-23 12:25:30.792  3792  3792 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-23 12:25:30.814  3792  3792 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-23 12:25:30.821  3792  3792 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9692-9695)
08-23 12:25:30.821  3792  3792 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 12:25:30.833  3792  3792 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b95d47b}
08-23 12:25:30.834  3792  3792 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 12:25:30.834  3792  3792 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-23 12:25:30.843  3792  3792 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-23 12:25:30.844  3792  3792 E SysUtils: ApplicationContext is null in ApplicationStatus
08-23 12:25:30.871  3792  3792 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-23 12:25:30.900  3792  3792 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 12:25:30.900  3792  3792 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 12:25:30.900  3792  3792 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-23 12:25:30.900  3792  3792 I Adreno  : Build Date                       : 10/20/15
08-23 12:25:30.900  3792  3792 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-23 12:25:30.900  3792  3792 I Adreno  : Local Branch                     : M14
08-23 12:25:30.900  3792  3792 I Adreno  : Remote Branch                    : 
08-23 12:25:30.900  3792  3792 I Adreno  : Remote Branch                    : 
08-23 12:25:30.900  3792  3792 I Adreno  : Reconstruct Branch               : 
,08-23 12:25:30.958   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7f9303f:true
,08-23 12:25:31.027  3792  3792 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-23 12:25:31.048  3792  3792 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-23 12:25:31.147  3792  3833 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-23 12:25:31.161  3792  3819 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-23 12:25:31.236  3792  3833 I OpenGLRenderer: Initialized EGL, version 1.4
,08-23 12:25:31.305   871   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +619ms
,08-23 12:25:31.311  1856  1856 I Keyboard.Facilitator: onFinishInput()
,08-23 12:25:31.416  3792  3792 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3792
,08-23 12:25:31.557   871  1963 I ActivityManager: Killing 3202:com.google.android.gm/u0a78 (adj 15): empty #17
,08-23 12:25:31.589  3792  3792 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 12:25:31.623   871  1963 I ActivityManager: Killing 3083:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-23 12:25:31.805  3792  3835 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1712850640
,08-23 12:25:31.820  3792  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 12:25:31.820  3792  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 12:25:31.820  3792  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 12:25:31.820  3792  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 12:25:31.820  3792  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-23 12:25:31.820  3792  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1ad56e added. We now have 1 listener(s)
,08-23 12:25:31.830  3792  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-23 12:25:31.831  3792  3835 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 12:25:31.832  3792  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
,08-23 12:25:31.832  3792  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 12:25:31.837  3792  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 12:25:31.837  3792  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 12:25:31.837  3792  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 12:25:31.837  3792  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-23 12:25:31.837  3792  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 12:25:31.837  3792  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 12:25:31.837  3792  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 12:25:31.837  3792  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 12:25:31.837  3792  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 12:25:31.837  3792  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 12:25:31.837  3792  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 12:25:31.837  3792  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 12:25:31.837  3792  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 12:25:31.837  3792  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-23 12:25:31.837  3792  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6fd6a5 added. We now have 1 listener(s)
08-23 12:25:31.837  3792  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 12:25:31.840   871  1302 D WifiService: New client listening to asynchronous messages
,08-23 12:25:31.841  3792  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 12:25:31.842  3792  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 12:25:31.842  3792  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-23 12:25:31.842  3792  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 12:25:31.842  3792  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-23 12:25:31.844  3792  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 12:25:31.845  3792  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-23 12:25:31.851  3792  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-23 12:25:31.851  3792  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:25:31.851  3792  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:25:31.851  3792  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
08-23 12:25:31.851  3792  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:25:31.851  3792  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:25:31.851  3792  3835 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:25:31.851  3792  3835 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:25:31.851  3792  3835 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 12:25:31.851  3792  3835 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 12:25:31.851  3792  3835 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 12:25:31.853  3792  3835 I io.jxcore.node.LifeCycleMonitor: start: OK
08-23 12:25:31.853  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:25:31.855  3792  3792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:25:32.009  3792  3792 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 12:25:32.617  3792  3844 W jxcore-log: Initializing JXcore engine
,08-23 12:25:32.617  3792  3844 W jxcore-log: JXcore engine is ready
,08-23 12:25:32.655  3844  3844 W Thread-321: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8945 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-23 12:25:32.655  3844  3844 W Thread-321: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12808]" dev="sockfs" ino=12808 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-23 12:25:32.655  3844  3844 W Thread-321: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-23 12:25:32.655  3844  3844 W Thread-321: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26849]" dev="sockfs" ino=26849 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-23 12:25:32.670  3792  3844 W jxcore-log: Starting JXcore engine
,08-23 12:25:32.753  3792  3844 W jxcore-log: Platform android
08-23 12:25:32.753  3792  3844 W jxcore-log: 
,08-23 12:25:32.754  3792  3844 W jxcore-log: Process ARCH arm
08-23 12:25:32.754  3792  3844 W jxcore-log: 
,08-23 12:25:33.000  3792  3844 I jxcore-log: JXcore Cordova bridge is ready!
08-23 12:25:33.000  3792  3844 I jxcore-log: 
,08-23 12:25:33.001  3792  3844 W jxcore-log: JXcore engine is started
,08-23 12:25:33.006  3792  3835 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-23 12:25:33.008  3792  3792 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 12:25:33.049  3792  3844 E jxcore  : Error!: missing name after . operator
08-23 12:25:33.049  3792  3844 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"591","_columnNumber":"9","_msg":"    at $w.prototype._compile@module.js:591:9"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"407","_columnNumber":"1","_msg":"    at $w._load@module.js:407:1"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:260:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,08-23 12:25:33.052   871  1301 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
,08-23 12:25:33.062  3792  3792 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "missing name after . operator\nSyntaxError: missing name after . operator\n    at $w.prototype._compile@module.js:591:9\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1\n    at $w._load@module.js:407:1\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at internal_methods.loadMainFile@main.js:260:5\n    at JXMobile.executeJSON@main.js:279:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (56)
,08-23 12:25:33.063  3792  3792 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
08-23 12:25:33.066   280   306 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (318 us)
,08-23 12:25:33.087  3792  3835 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 25ms. Plugin should use CordovaInterface.getThreadPool().
,08-23 12:25:33.087  3792  3792 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-23 12:25:33.089  3792  3792 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-23 12:25:33.123   871   884 I ActivityManager: Killing 2959:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-23 12:25:33.187  3792  3792 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-23 12:25:33.187  3792  3792 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-23 12:25:33.188  3792  3792 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-23 12:25:33.188  3792  3792 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-23 12:25:33.188  3792  3792 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:25:33.188  3792  3792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:25:33.188  3792  3792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:25:33.188  3792  3792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 12:25:33.188  3792  3792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1ad56e removed from the list
,08-23 12:25:33.188  3792  3792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:25:33.188  3792  3792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6fd6a5 removed from the list
08-23 12:25:33.188  3792  3792 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 12:25:33.189  3792  3792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,08-23 12:25:33.190  3792  3792 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-23 12:25:33.240  1856  1856 I Keyboard.Facilitator: onFinishInput(),
,08-23 12:25:33.308  2012  3851 I MicroRecognitionRnrImpl: Starting detection.
,08-23 12:25:33.308  2012  3852 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@48729dc
,08-23 12:25:33.310   376  3854 I AudioFlinger: AudioFlinger's thread 0xb1dc0000 ready to run
,08-23 12:25:33.313   376  1272 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-23 12:25:33.315  2012  3852 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@48729dc
08-23 12:25:33.324   376  3854 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
08-23 12:25:33.324   376  3854 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
08-23 12:25:33.324   376  3854 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
08-23 12:25:33.330   376  3854 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,08-23 12:25:33.404  2012  2012 I HotwordWorkerImpl: onReady
,08-23 12:25:33.706  3845  3845 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-23 12:25:33.711  3845  3845 D AndroidRuntime: CheckJNI is OFF
,08-23 12:25:33.750  1937  2112 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,08-23 12:25:33.776  3845  3845 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-23 12:25:33.825  3845  3845 I Radio-JNI: register_android_hardware_Radio DONE
,08-23 12:25:33.846  3845  3845 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-23 12:25:33.853   871   884 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-23 12:25:33.854   871   884 I ActivityManager: Killing 3792:com.test.thalitest/u0a0 (adj 9): stop com.test.thalitest
,08-23 12:25:33.942   871   882 D GraphicsStats: Buffer count: 2
,08-23 12:25:33.942   871  1302 D WifiService: Client connection lost with reason: 4
,08-23 12:25:33.970   871  1963 W ActivityManager: Spurious death for ProcessRecord{cc5b0a3 0:com.test.thalitest/u0a0}, curProc for 3792: null
,08-23 12:25:33.976   871   894 W PackageSettings: Skipping PackageSetting{efd4ca6 com.example.hello/10273} due to missing metadata
,08-23 12:25:34.011   871   894 I art     : Starting a blocking GC Explicit
,08-23 12:25:34.063   871   894 I art     : Explicit concurrent mark sweep GC freed 23941(1579KB) AllocSpace objects, 8(204KB) LOS objects, 33% free, 28MB/43MB, paused 680us total 48.900ms
,08-23 12:25:34.100   871   894 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-23 12:25:34.108  3845  3845 I art     : System.exit called, status: 0
,08-23 12:25:34.108  3845  3845 I AndroidRuntime: VM exiting with result code 0.
,08-23 12:25:34.112   871   894 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-23 12:25:34.173  2668  2668 D BluetoothMapAppObserver: onReceive
,08-23 12:25:34.173  2668  2668 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-23 12:25:34.176   871  1291 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-23 12:25:34.176  1980  2280 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 12:25:34.176  1856  1856 I Keyboard.Facilitator: resetDictionaries() : en_US
08-23 12:25:34.177  3688  3688 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-23 12:25:34.187  1856  3867 I Keyboard.Facilitator.DecoderInitializer: run()
,08-23 12:25:34.189  1856  3867 I Decoder : createOrResetDecoder
,08-23 12:25:34.220  1913  1913 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-23 12:25:34.233  1718  3869 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-23 12:25:34.235  1512  1512 I ConfigService: onCreate
,08-23 12:25:34.249  1512  1512 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,08-23 12:25:34.249  1512  1512 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-23 12:25:34.251  1856  3867 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-23 12:25:34.265  1689  3873 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-23 12:25:34.265  1689  3873 D AccountUtils: Clearing selected account for com.test.thalitest
,08-23 12:25:34.268   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-23 12:25:34.273  1689  1689 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-23 12:25:34.273  1689  1689 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-23 12:25:34.274  1689  3873 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-23 12:25:34.281  1689  3092 E SQLiteLog: (3850) statement aborts at 167: [DELETE FROM FileContent143 WHERE hash IN WipeoutFileContentHashView AND hash NOT IN ()] disk I/O error
,08-23 12:25:34.282  1689  3092 E DocListDatabase: Failed to delete from FileContent143 table
08-23 12:25:34.282  1689  3092 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 12:25:34.282  1689  3092 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-23 12:25:34.282  1689  3092 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-23 12:25:34.282  1689  3092 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-23 12:25:34.282  1689  3092 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 12:25:34.282  1689  3092 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-23 12:25:34.282  1689  3092 E DocListDatabase: 	at com.google.android.gms.drive.database.k.a(SourceFile:327)
08-23 12:25:34.282  1689  3092 E DocListDatabase: 	at com.google.android.gms.drive.database.f.a(SourceFile:970)
08-23 12:25:34.282  1689  3092 E DocListDatabase: 	at com.google.android.gms.drive.b.e.run(SourceFile:72)
08-23 12:25:34.282  1689  3092 E DocListDatabase: 	at com.google.android.gms.drive.i.bz.run(SourceFile:51)
08-23 12:25:34.282  1689  3092 E DocListDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 12:25:34.282  1689  3092 E DocListDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 12:25:34.282  1689  3092 E DocListDatabase: 	at java.lang.Thread.run(Thread.java:818)
,--------- beginning of crash
08-23 12:25:34.283  1689  3092 E AndroidRuntime: FATAL EXCEPTION: pool-10-thread-1
08-23 12:25:34.283  1689  3092 E AndroidRuntime: Process: com.google.android.gms, PID: 1689
08-23 12:25:34.283  1689  3092 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 12:25:34.283  1689  3092 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-23 12:25:34.283  1689  3092 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-23 12:25:34.283  1689  3092 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-23 12:25:34.283  1689  3092 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 12:25:34.283  1689  3092 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-23 12:25:34.283  1689  3092 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.a(SourceFile:327)
08-23 12:25:34.283  1689  3092 E AndroidRuntime: 	at com.google.android.gms.drive.database.f.a(SourceFile:970)
08-23 12:25:34.283  1689  3092 E AndroidRuntime: 	at com.google.android.gms.drive.b.e.run(SourceFile:72)
08-23 12:25:34.283  1689  3092 E AndroidRuntime: 	at com.google.android.gms.drive.i.bz.run(SourceFile:51)
08-23 12:25:34.283  1689  3092 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 12:25:34.283  1689  3092 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 12:25:34.283  1689  3092 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,08-23 12:25:34.285  1689  1689 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-23 12:25:34.285  1689  1689 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-23 12:25:34.288  1689  3881 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error,
,08-23 12:25:34.296  1689  3881 I Process : Sending signal. PID: 1689 SIG: 9
,08-23 12:25:34.299  1856  3867 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-23 12:25:34.303  1856  3867 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-23 12:25:34.303  1856  3867 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-23 12:25:34.305   871  3886 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-23 12:25:34.305  1856  3867 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-23 12:25:34.305  1856  3867 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-23 12:25:34.306  1856  3867 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-23 12:25:34.306  1856  3867 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-23 12:25:34.308   871  3882 E DropBoxManagerService: Can't write: system_app_crash
08-23 12:25:34.308   871  3882 E DropBoxManagerService: java.io.IOException: write failed: EROFS (Read-only file system)
08-23 12:25:34.308   871  3882 E DropBoxManagerService: 	at libcore.io.IoBridge.write(IoBridge.java:498)
08-23 12:25:34.308   871  3882 E DropBoxManagerService: 	at java.io.FileOutputStream.write(FileOutputStream.java:186),
08-23 12:25:34.308   871  3882 E DropBoxManagerService: 	at java.io.BufferedOutputStream.flushInternal(BufferedOutputStream.java:185)
08-23 12:25:34.308   871  3882 E DropBoxManagerService: 	at java.io.BufferedOutputStream.flush(BufferedOutputStream.java:85)
08-23 12:25:34.308   871  3882 E DropBoxManagerService: 	at java.io.FilterOutputStream.close(FilterOutputStream.java:61)
08-23 12:25:34.308   871  3882 E DropBoxManagerService: 	at java.io.BufferedOutputStream.close(BufferedOutputStream.java:152)
08-23 12:25:34.308   871  3882 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:230)
08-23 12:25:34.308   871  3882 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 12:25:34.308   871  3882 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 12:25:34.308   871  3882 E DropBoxManagerService: Caused by: android.system.ErrnoException: write failed: EROFS (Read-only file system)
08-23 12:25:34.308   871  3882 E DropBoxManagerService: 	at libcore.io.Posix.writeBytes(Native Method)
08-23 12:25:34.308   871  3882 E DropBoxManagerService: 	at libcore.io.Posix.write(Posix.java:271)
08-23 12:25:34.308   871  3882 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
08-23 12:25:34.308   871  3882 E DropBoxManagerService: 	at libcore.io.IoBridge.write(IoBridge.java:493)
08-23 12:25:34.308   871  3882 E DropBoxManagerService: 	... 8 more
,08-23 12:25:34.311  1718  3869 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,08-23 12:25:34.313  1718  3869 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-23 12:25:34.313  1718  3869 E AndroidRuntime: Process: android.process.acore, PID: 1718
08-23 12:25:34.313  1718  3869 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 12:25:34.313  1718  3869 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-23 12:25:34.313  1718  3869 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-23 12:25:34.313  1718  3869 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-23 12:25:34.313  1718  3869 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 12:25:34.313  1718  3869 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-23 12:25:34.313  1718  3869 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-23 12:25:34.313  1718  3869 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
08-23 12:25:34.313  1718  3869 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-23 12:25:34.313  1718  3869 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-23 12:25:34.313  1718  3869 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-23 12:25:34.313  1718  3869 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-23 12:25:34.313  1718  3869 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-23 12:25:34.313  1718  3869 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-23 12:25:34.313  1718  3869 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:25:34.313  1718  3869 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 12:25:34.313  1718  3869 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 12:25:34.316   871  3887 E DropBoxManagerService: Can't write: system_app_crash
08-23 12:25:34.316   871  3887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
08-23 12:25:34.316   871  3887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 12:25:34.316   871  3887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:25:34.316   871  3887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 12:25:34.316   871  3887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 12:25:34.316   871  3887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 12:25:34.316   871  3887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 12:25:34.316   871  3887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:25:34.316   871  3887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 12:25:34.316   871  3887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:25:34.316   871  3887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 12:25:34.316   871  3887 E DropBoxManagerService: 	... 5 more
08-23 12:25:34.317  1856  3867 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-23 12:25:34.317  1856  3867 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-23 12:25:34.317  1856  3867 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-23 12:25:34.318  1856  3867 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-23 12:25:34.318  1856  3867 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-23 12:25:34.318  1856  3867 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-23 12:25:34.320  2012  3883 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-23 12:25:34.324   871  1326 W System.err: java.io.IOException: write failed: EBADF (Bad file descriptor)
08-23 12:25:34.324   871  1326 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:498)
08-23 12:25:34.324   871  1326 W System.err: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
08-23 12:25:34.324   871  1326 W System.err: 	at android.graphics.Bitmap.nativeCompress(Native Method)
08-23 12:25:34.324   871  1326 W System.err: 	at android.graphics.Bitmap.compress(Bitmap.java:1027)
08-23 12:25:34.324   871  1326 W System.err: 	at com.android.server.am.TaskPersister$LazyTaskWriterThread.run(TaskPersister.java:557)
08-23 12:25:34.324   871  1326 W System.err: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
08-23 12:25:34.324   871  1326 W System.err: 	at libcore.io.Posix.writeBytes(Native Method)
08-23 12:25:34.325   871  1326 W System.err: 	at libcore.io.Posix.write(Posix.java:271)
08-23 12:25:34.325   871  1326 W System.err: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
08-23 12:25:34.325   871  1326 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:493)
08-23 12:25:34.325   871  1326 W System.err: 	... 4 more
08-23 12:25:34.325   871  1326 D skia    : ------- write threw an exception
08-23 12:25:34.328  1937  2613 E ReflectionEngine: Failed to save models
08-23 12:25:34.328  1937  2613 E ReflectionEngine: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/files/engine_16: open failed: EROFS (Read-only file system)
08-23 12:25:34.328  1937  2613 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 12:25:34.328  1937  2613 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:25:34.328  1937  2613 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 12:25:34.328  1937  2613 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.BT(ReflectionEngine.java:123)
08-23 12:25:34.328  1937  2613 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:240)
08-23 12:25:34.328  1937  2613 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-23 12:25:34.328  1937  2613 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-23 12:25:34.328  1937  2613 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-23 12:25:34.328  1937  2613 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 12:25:34.328  1937  2613 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 12:25:34.328  1937  2613 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 12:25:34.328  1937  2613 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 12:25:34.328  1937  2613 E ReflectionEngine: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-23 12:25:34.328  1937  2613 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 12:25:34.328  1937  2613 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 12:25:34.328  1937  2613 E ReflectionEngine: 	at java.lang.Thread.run(Thread.java:818)
08-23 12:25:34.328  1937  2613 E ReflectionEngine: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-23 12:25:34.328  1937  2613 E ReflectionEngine: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:25:34.328  1937  2613 E ReflectionEngine: 	at libcore.io.Posix.open(Native Method)
08-23 12:25:34.328  1937  2613 E ReflectionEngine: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:25:34.328  1937  2613 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 12:25:34.328  1937  2613 E ReflectionEngine: 	... 16 more
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: Failed to write the stream file
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2431: open failed: EROFS (Read-only file system)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	... 16 more
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: Failed to write the stream file
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2432: open failed: EROFS (Read-only file system)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 12:25:34.341  1937  2613 E ObservedEventLogger: 	... 16 more
08-23 12:25:34.345   871  3886 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-23 12:25:34.345   871  3886 I Adreno  : Build Date                       : 10/20/15
08-23 12:25:34.345   871  3886 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-23 12:25:34.345   871  3886 I Adreno  : Local Branch                     : M14
08-23 12:25:34.345   871  3886 I Adreno  : Remote Branch                    : 
08-23 12:25:34.345   871  3886 I Adreno  : Remote Branch                    : 
08-23 12:25:34.345   871  3886 I Adreno  : Reconstruct Branch               : 
08-23 12:25:34.347   871  2028 I ActivityManager: Start proc 3889:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,08-23 12:25:34.351  2012  3883 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-23 12:25:34.351   871  3886 I OpenGLRenderer: Initialized EGL, version 1.4
08-23 12:25:34.352   871  2958 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@26ad4fd)
08-23 12:25:34.354   871  1303 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 12:25:34.355   871  1303 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 12:25:34.357   871  1963 I ActivityManager: Process com.google.android.gms (pid 1689) has died
08-23 12:25:34.360   871  1963 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
08-23 12:25:34.360   871  1963 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
08-23 12:25:34.360   871  1963 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
08-23 12:25:34.361   871  1963 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
08-23 12:25:34.361   871  1963 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 11000ms
08-23 12:25:34.361   871  1963 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 21000ms
08-23 12:25:34.361   871  1963 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 31000ms
08-23 12:25:34.374   871  1931 I ActivityManager: Start proc 3902:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-23 12:25:34.377  2012  3883 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
08-23 12:25:34.377  2012  3883 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-23 12:25:34.377  2012  3883 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 2012
08-23 12:25:34.377  2012  3883 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 12:25:34.377  2012  3883 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-23 12:25:34.377  2012  3883 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-23 12:25:34.377  2012  3883 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-23 12:25:34.377  2012  3883 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-23 12:25:34.377  2012  3883 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-23 12:25:34.377  2012  3883 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-23 12:25:34.377  2012  3883 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-23 12:25:34.377  2012  3883 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-23 12:25:34.377  2012  3883 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-23 12:25:34.377  2012  3883 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-23 12:25:34.377  2012  3883 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-23 12:25:34.377  2012  3883 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-23 12:25:34.377  2012  3883 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-23 12:25:34.377  2012  3883 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-23 12:25:34.377  2012  3883 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-23 12:25:34.377  2012  3883 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:25:34.377  2012  3883 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 12:25:34.377  2012  3883 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 12:25:34.391   871  3914 E DropBoxManagerService: Can't write: system_app_crash
08-23 12:25:34.391   871  3914 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
08-23 12:25:34.391   871  3914 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 12:25:34.391   871  3914 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:25:34.391   871  3914 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 12:25:34.391   871  3914 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 12:25:34.391   871  3914 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 12:25:34.391   871  3914 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 12:25:34.391   871  3914 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:25:34.391   871  3914 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 12:25:34.391   871  3914 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:25:34.391   871  3914 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 12:25:34.391   871  3914 E DropBoxManagerService: 	... 5 more
,08-23 12:25:34.407  3889  3889 W System  : ClassLoader referenced unknown path: /system/app/KeyChain/lib/arm
,08-23 12:25:34.410  3889  3889 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2725 
,08-23 12:25:34.431  3889  3920 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.keychain/databases/grants.db'.
08-23 12:25:34.431  3889  3920 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:25:34.431  3889  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:25:34.431  3889  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 12:25:34.431  3889  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 12:25:34.431  3889  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 12:25:34.431  3889  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 12:25:34.431  3889  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 12:25:34.431  3889  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 12:25:34.431  3889  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 12:25:34.431  3889  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 12:25:34.431  3889  3920 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 12:25:34.431  3889  3920 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 12:25:34.431  3889  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:25:34.431  3889  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 12:25:34.431  3889  3920 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-23 12:25:34.431  3889  3920 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-23 12:25:34.431  3889  3920 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-23 12:25:34.431  3889  3920 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:25:34.431  3889  3920 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-23 12:25:34.431  3889  3920 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 12:25:34.431  3889  3920 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-23 12:25:34.431  3889  3920 E AndroidRuntime: Process: com.android.keychain, PID: 3889
08-23 12:25:34.431  3889  3920 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:25:34.431  3889  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:25:34.431  3889  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 12:25:34.431  3889  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 12:25:34.431  3889  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 12:25:34.431  3889  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 12:25:34.431  3889  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 12:25:34.431  3889  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 12:25:34.431  3889  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 12:25:34.431  3889  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 12:25:34.431  3889  3920 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 12:25:34.431  3889  3920 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 12:25:34.431  3889  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:25:34.431  3889  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 12:25:34.431  3889  3920 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-23 12:25:34.431  3889  3920 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-23 12:25:34.431  3889  3920 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-23 12:25:34.431  3889  3920 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:25:34.431  3889  3920 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 12:25:34.431  3889  3920 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 12:25:34.436   871   871 I ActivityManager: Start proc 3922:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,08-23 12:25:34.443   871  3927 E DropBoxManagerService: Can't write: system_app_crash
08-23 12:25:34.443   871  3927 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
08-23 12:25:34.443   871  3927 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 12:25:34.443   871  3927 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:25:34.443   871  3927 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 12:25:34.443   871  3927 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 12:25:34.443   871  3927 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 12:25:34.443   871  3927 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 12:25:34.443   871  3927 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:25:34.443   871  3927 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 12:25:34.443   871  3927 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:25:34.443   871  3927 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 12:25:34.443   871  3927 E DropBoxManagerService: 	... 5 more
,08-23 12:25:34.460  1937  2025 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-23 12:25:34.464  1937  2025 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-23 12:25:34.464  1937  2025 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1937
08-23 12:25:34.464  1937  2025 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 12:25:34.464  1937  2025 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-23 12:25:34.464  1937  2025 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-23 12:25:34.464  1937  2025 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-23 12:25:34.464  1937  2025 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 12:25:34.464  1937  2025 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-23 12:25:34.464  1937  2025 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-23 12:25:34.464  1937  2025 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-23 12:25:34.464  1937  2025 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 12:25:34.464  1937  2025 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 12:25:34.464  1937  2025 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 12:25:34.464  1937  2025 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 12:25:34.466   871  3937 E DropBoxManagerService: Can't write: system_app_crash
08-23 12:25:34.466   871  3937 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
08-23 12:25:34.466   871  3937 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 12:25:34.466   871  3937 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:25:34.466   871  3937 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 12:25:34.466   871  3937 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 12:25:34.466   871  3937 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 12:25:34.466   871  3937 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 12:25:34.466   871  3937 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:25:34.466   871  3937 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 12:25:34.466   871  3937 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:25:34.466   871  3937 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 12:25:34.466   871  3937 E DropBoxManagerService: 	... 5 more
,08-23 12:25:34.468   871   883 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-23 12:25:34.468   871  1375 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
08-23 12:25:34.468   871  1375 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-23 12:25:34.468   871   883 E PackageManager: Failed to write settings, restoring backup
08-23 12:25:34.468   871   883 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-23 12:25:34.468   871   883 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-23 12:25:34.468   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-23 12:25:34.468   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-23 12:25:34.468   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-23 12:25:34.468   871   883 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:25:34.468   871   883 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-23 12:25:34.468   871   883 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 12:25:34.470   871   884 E DropBoxManagerService: Can't write: system_server_wtf
08-23 12:25:34.470   871   884 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-23 12:25:34.470   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 12:25:34.470   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:25:34.470   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 12:25:34.470   871   884 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 12:25:34.470   871   884 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 12:25:34.470   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 12:25:34.470   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-23 12:25:34.470   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-23 12:25:34.470   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-23 12:25:34.470   871   884 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 12:25:34.470   871   884 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 12:25:34.470   871   884 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-23 12:25:34.470   871   884 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 12:25:34.470   871   884 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-23 12:25:34.470   871   884 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:25:34.470   871   884 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 12:25:34.470   871   884 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:25:34.470   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 12:25:34.470   871   884 E DropBoxManagerService: 	... 13 more
08-23 12:25:34.472   871  1375 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-23 12:25:34.474   871  1375 I ActivityManager: Killing 1937:com.google.android.googlequicksearchbox/u0a28 (adj 0): crash
,08-23 12:25:34.488  3922  3922 W System  : ClassLoader referenced unknown path: /system/app/DocumentsUI/lib/arm
,08-23 12:25:34.523   871  1933 D GraphicsStats: Buffer count: 2
,08-23 12:25:34.525  2012  2012 E AttachedClient: AttachedClient[8319351675016, ClientConfig[mFlags=[210d800202] mSuggestFlags=[3b] mClientStats=SearchBoxStats[gel/android-search-app]]]: failed callback onGenericEvent()
08-23 12:25:34.525  2012  2012 E AttachedClient: android.os.DeadObjectException
08-23 12:25:34.525  2012  2012 E AttachedClient: 	at android.os.BinderProxy.transactNative(Native Method)
08-23 12:25:34.525  2012  2012 E AttachedClient: 	at android.os.BinderProxy.transact(Binder.java:503)
08-23 12:25:34.525  2012  2012 E AttachedClient: 	at com.google.android.apps.gsa.search.shared.service.l.c(ISearchServiceUiCallback.java:578)
08-23 12:25:34.525  2012  2012 E AttachedClient: 	at com.google.android.search.core.service.a.c(AttachedClient.java:4725)
08-23 12:25:34.525  2012  2012 E AttachedClient: 	at com.google.android.search.core.service.a.b(AttachedClient.java:185)
08-23 12:25:34.525  2012  2012 E AttachedClient: 	at com.google.android.search.core.ad.c(SearchController.java:51069)
08-23 12:25:34.525  2012  2012 E AttachedClient: 	at com.google.android.search.core.service.SearchService.bca(SearchService.java:373)
08-23 12:25:34.525  2012  2012 E AttachedClient: 	at com.google.android.search.core.service.SearchService$1.run(SearchService.java:83)
08-23 12:25:34.525  2012  2012 E AttachedClient: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 12:25:34.525  2012  2012 E AttachedClient: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 12:25:34.525  2012  2012 E AttachedClient: 	at android.os.Looper.loop(Looper.java:148)
08-23 12:25:34.525  2012  2012 E AttachedClient: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 12:25:34.525  2012  2012 E AttachedClient: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:25:34.525  2012  2012 E AttachedClient: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 12:25:34.525  2012  2012 E AttachedClient: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-23 12:25:34.525  2012  2012 I SearchService: Ignoring already detached client
,08-23 12:25:34.527  2012  2323 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@48729dc
,08-23 12:25:34.527  2012  3852 E AudioRecord-JNI: Error -4 during AudioRecord native read
,08-23 12:25:34.527  2012  2012 I HotwordDetector: Closing mic
,08-23 12:25:34.553   871  1375 I ActivityManager: Start proc 3938:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-23 12:25:34.575   871  1942 I ActivityManager: Start proc 3950:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService
,08-23 12:25:34.588   376  3854 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,08-23 12:25:34.589   376  3854 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-23 12:25:34.591   871   881 W ActivityManager: Spurious death for ProcessRecord{b9cf44 0:com.google.android.googlequicksearchbox/u0a28}, curProc for 1937: null
08-23 12:25:34.598   376  1272 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0,
,08-23 12:25:34.607  2012  2329 I MicroRecognitionRnrImpl: Stopping hotword detection.
,08-23 12:25:34.608  2012  3851 I MicroRecognitionRnrImpl: Detection finished
,08-23 12:25:34.620  3938  3938 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-23 12:25:34.620  3938  3938 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:25:34.620  3938  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:25:34.620  3938  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 12:25:34.620  3938  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 12:25:34.620  3938  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 12:25:34.620  3938  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 12:25:34.620  3938  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 12:25:34.620  3938  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 12:25:34.620  3938  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 12:25:34.620  3938  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 12:25:34.620  3938  3938 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 12:25:34.620  3938  3938 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 12:25:34.620  3938  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:25:34.620  3938  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 12:25:34.620  3938  3938 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-23 12:25:34.620  3938  3938 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-23 12:25:34.620  3938  3938 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-23 12:25:34.620  3938  3938 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-23 12:25:34.620  3938  3938 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-23 12:25:34.620  3938  3938 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-23 12:25:34.620  3938  3938 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-23 12:25:34.620  3938  3938 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 12:25:34.620  3938  3938 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 12:25:34.620  3938  3938 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:25:34.620  3938  3938 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-23 12:25:34.620  3938  3938 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 12:25:34.620  3938  3938 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:25:34.620  3938  3938 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 12:25:34.620  3938  3938 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-23 12:25:34.621  3938  3938 D AndroidRuntime: Shutting down VM
,08-23 12:25:34.622  3922  3922 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.documentsui/databases/recents.db'.
,08-23 12:25:34.622  3922  3922 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:25:34.622  3922  3922 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:25:34.622  3922  3922 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 12:25:34.622  3922  3922 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 12:25:34.622  3922  3922 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 12:25:34.622  3922  3922 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 12:25:34.622  3922  3922 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 12:25:34.622  3922  3922 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 12:25:34.622  3922  3922 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 12:25:34.622  3922  3922 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 12:25:34.622  3922  3922 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 12:25:34.622  3922  3922 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 12:25:34.622  3922  3922 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:25:34.622  3922  3922 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 12:25:34.622  3922  3922 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
08-23 12:25:34.622  3922  3922 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
08-23 12:25:34.622  3922  3922 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:398)
08-23 12:25:34.622  3922  3922 E SQLiteDatabase: 	at android.content.ContentResolver.call(ContentResolver.java:1398)
08-23 12:25:34.622  3922  3922 E SQLiteDatabase: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
08-23 12:25:34.622  3922  3922 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-23 12:25:34.622  3922  3922 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-23 12:25:34.622  3922  3922 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-23 12:25:34.622  3922  3922 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:25:34.622  3922  3922 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-23 12:25:34.622  3922  3922 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 12:25:34.622  3922  3922 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:25:34.622  3922  3922 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 12:25:34.622  3922  3922 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-23 12:25:34.631  3938  3938 E AndroidRuntime: FATAL EXCEPTION: main
08-23 12:25:34.631  3938  3938 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3938
08-23 12:25:34.631  3938  3938 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:25:34.631  3938  3938 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-23 12:25:34.631  3938  3938 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-23 12:25:34.631  3938  3938 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-23 12:25:34.631  3938  3938 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 12:25:34.631  3938  3938 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 12:25:34.631  3938  3938 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:25:34.631  3938  3938 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 12:25:34.631  3938  3938 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 12:25:34.631  3938  3938 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:25:34.631  3938  3938 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 12:25:34.631  3938  3938 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 12:25:34.631  3938  3938 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:25:34.631  3938  3938 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:25:34.631  3938  3938 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 12:25:34.631  3938  3938 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 12:25:34.631  3938  3938 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 12:25:34.631  3938  3938 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 12:25:34.631  3938  3938 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 12:25:34.631  3938  3938 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 12:25:34.631  3938  3938 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 12:25:34.631  3938  3938 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 12:25:34.631  3938  3938 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 12:25:34.631  3938  3938 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 12:25:34.631  3938  3938 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:25:34.631  3938  3938 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 12:25:34.631  3938  3938 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-23 12:25:34.631  3938  3938 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-23 12:25:34.631  3938  3938 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-23 12:25:34.631  3938  3938 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-23 12:25:34.631  3938  3938 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-23 12:25:34.631  3938  3938 E AndroidRuntime: 	... 10 more
08-23 12:25:34.634   871  3964 E DropBoxManagerService: Can't write: system_app_crash
08-23 12:25:34.634   871  3964 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
08-23 12:25:34.634   871  3964 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 12:25:34.634   871  3964 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:25:34.634   871  3964 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 12:25:34.634   871  3964 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 12:25:34.634   871  3964 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 12:25:34.634   871  3964 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 12:25:34.634   871  3964 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:25:34.634   871  3964 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 12:25:34.634   871  3964 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:25:34.634   871  3964 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 12:25:34.634   871  3964 E DropBoxManagerService: 	... 5 more
08-23 12:25:34.637  1333  2410 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10000)] disk I/O error
08-23 12:25:34.638  1333  2410 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
08-23 12:25:34.638  1333  2410 E AndroidRuntime: Process: android.process.media, PID: 1333
08-23 12:25:34.638  1333  2410 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 12:25:34.638  1333  2410 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-23 12:25:34.638  1333  2410 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-23 12:25:34.638  1333  2410 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-23 12:25:34.638  1333  2410 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 12:25:34.638  1333  2410 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-23 12:25:34.638  1333  2410 E AndroidRuntime: 	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1215)
08-23 12:25:34.638  1333  2410 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-23 12:25:34.638  1333  2410 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-23 12:25:34.638  1333  2410 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:117)
08-23 12:25:34.638  1333  2410 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.-wrap1(DownloadReceiver.java)
08-23 12:25:34.638  1333  2410 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:85)
08-23 12:25:34.638  1333  2410 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 12:25:34.638  1333  2410 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 12:25:34.638  1333  2410 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 12:25:34.638  1333  2410 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 12:25:34.638,  3922  3922 D AndroidRuntime: Shutting down VM
08-23 12:25:34.639  3922  3922 E AndroidRuntime: FATAL EXCEPTION: main
08-23 12:25:34.639  3922  3922 E AndroidRuntime: Process: com.android.documentsui, PID: 3922
08-23 12:25:34.639  3922  3922 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:25:34.639  3922  3922 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-23 12:25:34.639  3922  3922 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-23 12:25:34.639  3922  3922 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-23 12:25:34.639  3922  3922 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:25:34.639  3922  3922 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 12:25:34.639  3922  3922 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 12:25:34.639  3922  3922 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:25:34.639  3922  3922 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 12:25:34.639  3922  3922 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 12:25:34.639  3922  3922 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:25:34.639  3922  3922 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:25:34.639  3922  3922 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 12:25:34.639  3922  3922 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 12:25:34.639  3922  3922 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 12:25:34.639  3922  3922 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 12:25:34.639  3922  3922 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 12:25:34.639  3922  3922 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 12:25:34.639  3922  3922 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 12:25:34.639  3922  3922 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 12:25:34.639  3922  3922 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 12:25:34.639  3922  3922 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 12:25:34.639  3922  3922 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:25:34.639  3922  3922 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 12:25:34.639  3922  3922 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
08-23 12:25:34.639  3922  3922 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
08-23 12:25:34.639  3922  3922 E AndroidRuntime: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:398)
08-23 12:25:34.639  3922  3922 E AndroidRuntime: 	at android.content.ContentResolver.call(ContentResolver.java:1398)
08-23 12:25:34.639  3922  3922 E AndroidRuntime: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
08-23 12:25:34.639  3922  3922 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-23 12:25:34.639  3922  3922 E AndroidRuntime: 	... 8 more
08-23 12:25:34.639  3950  3950 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
08-23 12:25:34.644  2012  3963 E Search.SharedPreferencesProto: Failed to rename to backup file /data/user/0/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
08-23 12:25:34.647   871  1375 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-23 12:25:34.652  3950  3950 I MultiDex: VM with version 2.1.0 has multidex support
08-23 12:25:34.652  3950  3950 I MultiDex: install
08-23 12:25:34.652  3950  3950 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-23 12:25:34.653   871  3965 E DropBoxManagerService: Can't write: system_app_crash
08-23 12:25:34.653   871  3965 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop120.tmp: open failed: EROFS (Read-only file system)
08-23 12:25:34.653   871  3965 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 12:25:34.653   871  3965 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:25:34.653   871  3965 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 12:25:34.653   871  3965 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 12:25:34.653   871  3965 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 12:25:34.653   871  3965 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 12:25:34.653   871  3965 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:25:34.653   871  3965 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 12:25:34.653   871  3965 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:25:34.653   871  3965 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 12:25:34.653   871  3965 E DropBoxManagerService: 	... 5 more
08-23 12:25:34.658   871  3966 E DropBoxManagerService: Can't write: system_app_crash
08-23 12:25:34.658   871  3966 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
08-23 12:25:34.658   871  3966 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 12:25:34.658   871  3966 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:25:34.658   871  3966 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 12:25:34.658   871  3966 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 12:25:34.658   871  3966 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 12:25:34.658   871  3966 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 12:25:34.658   871  3966 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:25:34.658   871  3966 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 12:25:34.658   871  3966 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:25:34.658   871  3966 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 12:25:34.658   871  3966 E DropBoxManagerService: 	... 5 more
,08-23 12:25:34.678   280   280 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
08-23 12:25:34.679   280   280 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
08-23 12:25:34.679   280   280 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
08-23 12:25:34.679   280   280 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
08-23 12:25:34.679   280   280 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
08-23 12:25:34.679   280   280 E qdoverlay: MdpCtrl close error in unset
,08-23 12:25:34.933   280   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-23 12:25:34.934   280   280 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
,08-23 12:25:34.934   280   280 E qdoverlay: MdpCtrl close error in unset

```
