#### Test 82337235d68dad2_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-23 13:27:23.159   873  1310 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
,08-23 13:27:23.915  3959  3959 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-23 13:27:23.919  3959  3959 D AndroidRuntime: CheckJNI is OFF
08-23 13:27:23.956  3959  3959 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-23 13:27:23.998  3959  3959 I Radio-JNI: register_android_hardware_Radio DONE
08-23 13:27:24.018  3959  3959 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-23 13:27:24.022   873  1980 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-23 13:27:24.068  2008  2403 W SearchService: Abort, client detached.
08-23 13:27:24.074  3959  3959 D AndroidRuntime: Shutting down VM
08-23 13:27:24.079  2008  2008 I HotwordDetector: Closing mic
08-23 13:27:24.081  2008  2345 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@9df3b90
08-23 13:27:24.081  2008  2355 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-23 13:27:24.090   873  1978 I ActivityManager: Start proc 3968:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-23 13:27:24.131   376  2357 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-23 13:27:24.132   376  2357 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-23 13:27:24.137   376  1282 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-23 13:27:24.138  2008  2354 I MicroRecognitionRnrImpl: Detection finished
08-23 13:27:24.139  2008  2349 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-23 13:27:24.160  3968  3968 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-23 13:27:24.179  3968  3968 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-23 13:27:24.185  3968  3968 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3745-3747)
08-23 13:27:24.186  3968  3968 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 13:27:24.202  3968  3968 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9d69ff4}
08-23 13:27:24.202  3968  3968 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 13:27:24.203  3968  3968 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-23 13:27:24.208  3968  3968 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-23 13:27:24.209  3968  3968 E SysUtils: ApplicationContext is null in ApplicationStatus
08-23 13:27:24.230  3968  3968 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-23 13:27:24.239  3968  3968 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 13:27:24.239  3968  3968 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 13:27:24.239  3968  3968 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-23 13:27:24.239  3968  3968 I Adreno  : Build Date                       : 10/20/15
08-23 13:27:24.239  3968  3968 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-23 13:27:24.239  3968  3968 I Adreno  : Local Branch                     : M14
08-23 13:27:24.239  3968  3968 I Adreno  : Remote Branch                    : 
08-23 13:27:24.239  3968  3968 I Adreno  : Remote Branch                    : 
08-23 13:27:24.239  3968  3968 I Adreno  : Reconstruct Branch               : 
08-23 13:27:24.282   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@aac5fee:true
,08-23 13:27:24.321  3968  3968 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-23 13:27:24.332  3968  3968 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-23 13:27:24.413  3968  4006 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-23 13:27:24.421  3968  3993 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-23 13:27:24.462  3968  4006 I OpenGLRenderer: Initialized EGL, version 1.4
,08-23 13:27:24.519  1867  1867 I Keyboard.Facilitator: onFinishInput()
,08-23 13:27:24.521   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +444ms
,08-23 13:27:24.617  3968  3968 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3968
,08-23 13:27:24.722  3968  3968 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 13:27:24.890   873   884 I ActivityManager: Killing 3535:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-23 13:27:24.891   278   278 E lowmemorykiller: Error writing /proc/3535/oom_score_adj; errno=22
,08-23 13:27:24.893  3968  4008 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1694959312
,08-23 13:27:24.900  3968  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 13:27:24.900  3968  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 13:27:24.900  3968  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 13:27:24.900  3968  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 13:27:24.900  3968  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-23 13:27:24.900  3968  4008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@296e79b added. We now have 1 listener(s)
,08-23 13:27:24.906  3968  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-23 13:27:24.914  3968  4008 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 13:27:24.916  3968  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 13:27:24.917  3968  4008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 13:27:24.927  3968  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 13:27:24.927  3968  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 13:27:24.927  3968  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 13:27:24.927  3968  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-23 13:27:24.927  3968  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 13:27:24.927  3968  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 13:27:24.927  3968  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 13:27:24.927  3968  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 13:27:24.927  3968  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 13:27:24.927  3968  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 13:27:24.927  3968  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 13:27:24.927  3968  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 13:27:24.927  3968  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 13:27:24.927  3968  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-23 13:27:24.927  3968  4008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47abc76 added. We now have 1 listener(s)
08-23 13:27:24.929  3968  4008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 13:27:24.934   873  1311 D WifiService: New client listening to asynchronous messages
,08-23 13:27:24.934  3968  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 13:27:24.935  3968  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-23 13:27:24.935  3968  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 13:27:24.935  3968  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 13:27:24.935  3968  4008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-23 13:27:24.943   873   884 I ActivityManager: Killing 3114:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-23 13:27:24.991  3968  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 13:27:24.991  3968  4008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-23 13:27:24.997  3968  4008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-23 13:27:24.998  3968  4008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 13:27:24.998  3968  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 13:27:24.998  3968  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 13:27:24.998  3968  4008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 13:27:24.998  3968  4008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 13:27:24.998  3968  4008 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 13:27:24.998  3968  4008 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 13:27:24.998  3968  4008 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 13:27:24.998  3968  4008 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 13:27:24.998  3968  4008 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 13:27:24.999  3968  4008 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-23 13:27:25.124  3968  3968 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 13:27:25.127  3968  3968 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 13:27:25.130  3968  3968 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 13:27:25.981  3968  4016 W jxcore-log: Initializing JXcore engine
,08-23 13:27:25.981  3968  4016 W jxcore-log: JXcore engine is ready
,08-23 13:27:26.020  4016  4016 W Thread-345: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8933 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-23 13:27:26.023  4016  4016 W Thread-345: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10608]" dev="sockfs" ino=10608 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-23 13:27:26.023  4016  4016 W Thread-345: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-23 13:27:26.023  4016  4016 W Thread-345: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27062]" dev="sockfs" ino=27062 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-23 13:27:26.040  3968  4016 W jxcore-log: Starting JXcore engine
,08-23 13:27:26.139  3968  4016 W jxcore-log: Platform android
08-23 13:27:26.139  3968  4016 W jxcore-log: 
08-23 13:27:26.140  3968  4016 W jxcore-log: Process ARCH arm
08-23 13:27:26.140  3968  4016 W jxcore-log: 
,08-23 13:27:26.387  3968  4016 I jxcore-log: JXcore Cordova bridge is ready!
08-23 13:27:26.387  3968  4016 I jxcore-log: 
,08-23 13:27:26.388  3968  4016 W jxcore-log: JXcore engine is started
,08-23 13:27:26.404  3968  4008 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-23 13:27:26.411  3968  3968 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 13:27:26.466  3968  4016 E jxcore  : Error!: missing name after . operator
08-23 13:27:26.466  3968  4016 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"591","_columnNumber":"9","_msg":"    at $w.prototype._compile@module.js:591:9"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"407","_columnNumber":"1","_msg":"    at $w._load@module.js:407:1"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:260:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,08-23 13:27:26.475  3968  3968 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "missing name after . operator\nSyntaxError: missing name after . operator\n    at $w.prototype._compile@module.js:591:9\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1\n    at $w._load@module.js:407:1\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at internal_methods.loadMainFile@main.js:260:5\n    at JXMobile.executeJSON@main.js:279:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (56)
,08-23 13:27:26.476  3968  3968 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
,08-23 13:27:26.482   280  1763 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (338 us)
,08-23 13:27:26.527  3968  3968 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-23 13:27:26.527  3968  3968 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-23 13:27:26.530  3968  4008 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 53ms. Plugin should use CordovaInterface.getThreadPool().
,08-23 13:27:26.553   873   886 I ActivityManager: Killing 2264:com.google.android.talk/u0a61 (adj 15): empty #17
,08-23 13:27:26.607  3968  3968 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-23 13:27:26.607  3968  3968 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-23 13:27:26.607  3968  3968 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-23 13:27:26.607  3968  3968 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-23 13:27:26.607  3968  3968 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 13:27:26.607  3968  3968 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 13:27:26.608  3968  3968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 13:27:26.608  3968  3968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 13:27:26.608  3968  3968 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@296e79b removed from the list
,08-23 13:27:26.608  3968  3968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 13:27:26.609  3968  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47abc76 removed from the list
08-23 13:27:26.609  3968  3968 D io.jxcore.node.ConnectivityMonitor: stop
08-23 13:27:26.610  3968  3968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
08-23 13:27:26.611  3968  3968 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-23 13:27:26.653  1867  1867 I Keyboard.Facilitator: onFinishInput()
,08-23 13:27:26.713  2008  4025 I MicroRecognitionRnrImpl: Starting detection.
,08-23 13:27:26.714  2008  4026 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@d47c219
,08-23 13:27:26.715   376  4028 I AudioFlinger: AudioFlinger's thread 0xb1d40000 ready to run
,08-23 13:27:26.718   376  1282 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-23 13:27:26.719  2008  4026 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@d47c219
,08-23 13:27:26.729   376  4028 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
,08-23 13:27:26.729   376  4028 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
08-23 13:27:26.729   376  4028 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
,08-23 13:27:26.736   376  4028 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,08-23 13:27:26.805  2008  2008 I HotwordWorkerImpl: onReady
,08-23 13:27:27.149  4019  4019 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-23 13:27:27.153  4019  4019 D AndroidRuntime: CheckJNI is OFF
,08-23 13:27:27.163  1958  2196 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,08-23 13:27:27.193  4019  4019 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-23 13:27:27.234  4019  4019 I Radio-JNI: register_android_hardware_Radio DONE
,08-23 13:27:27.257  4019  4019 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-23 13:27:27.267   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-23 13:27:27.268   873   886 I ActivityManager: Killing 3968:com.test.thalitest/u0a0 (adj 9): stop com.test.thalitest
,08-23 13:27:27.350   873  1979 D GraphicsStats: Buffer count: 2
,08-23 13:27:27.350   873  1311 D WifiService: Client connection lost with reason: 4
,08-23 13:27:27.371   873  2220 W ActivityManager: Spurious death for ProcessRecord{7be4a62 0:com.test.thalitest/u0a0}, curProc for 3968: null
,08-23 13:27:27.407   873   896 W PackageSettings: Skipping PackageSetting{7a185f3 com.example.hello/10273} due to missing metadata
,08-23 13:27:27.441   873   896 I art     : Starting a blocking GC Explicit
,08-23 13:27:27.488   873   896 I art     : Explicit concurrent mark sweep GC freed 19422(1201KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 28MB/43MB, paused 721us total 46.560ms
,08-23 13:27:27.522   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-23 13:27:27.526  4019  4019 I art     : System.exit called, status: 0
08-23 13:27:27.526  4019  4019 I AndroidRuntime: VM exiting with result code 0.
,08-23 13:27:27.542   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-23 13:27:27.572  2791  2791 D BluetoothMapAppObserver: onReceive
,08-23 13:27:27.572  2791  2791 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-23 13:27:27.580  3784  3784 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-23 13:27:27.585  1904  2271 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 13:27:27.586  1867  1867 I Keyboard.Facilitator: resetDictionaries() : en_US
08-23 13:27:27.589  1867  4042 I Keyboard.Facilitator.DecoderInitializer: run()
08-23 13:27:27.589   873  1300 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-23 13:27:27.591  1867  4042 I Decoder : createOrResetDecoder
,08-23 13:27:27.610  2008  2018 I art     : Background partial concurrent mark sweep GC freed 30747(2MB) AllocSpace objects, 16(1156KB) LOS objects, 40% free, 23MB/39MB, paused 5.863ms total 61.655ms
,08-23 13:27:27.632  1942  1942 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-23 13:27:27.653  1680  1730 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,--------- beginning of crash
08-23 13:27:27.654  1680  1730 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
08-23 13:27:27.654  1680  1730 E AndroidRuntime: Process: android.process.acore, PID: 1680
08-23 13:27:27.654  1680  1730 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 13:27:27.654  1680  1730 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-23 13:27:27.654  1680  1730 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-23 13:27:27.654  1680  1730 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-23 13:27:27.654  1680  1730 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-23 13:27:27.654  1680  1730 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-23 13:27:27.654  1680  1730 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-23 13:27:27.654  1680  1730 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:391)
08-23 13:27:27.654  1680  1730 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
08-23 13:27:27.654  1680  1730 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
08-23 13:27:27.654  1680  1730 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-23 13:27:27.654  1680  1730 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:27:27.654  1680  1730 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 13:27:27.654  1680  1730 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 13:27:27.658   873  4046 E DropBoxManagerService: Can't write: system_app_crash
08-23 13:27:27.658   873  4046 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop108.tmp: open failed: EROFS (Read-only file system)
08-23 13:27:27.658   873  4046 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 13:27:27.658   873  4046 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 13:27:27.658   873  4046 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 13:27:27.658   873  4046 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 13:27:27.658   873  4046 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 13:27:27.658   873  4046 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 13:27:27.658   873  4046 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 13:27:27.658   873  4046 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 13:27:27.658   873  4046 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 13:27:27.658   873  4046 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 13:27:27.658   873  4046 E DropBoxManagerService: 	... 5 more
,08-23 13:27:27.667  1680  4045 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-23 13:27:27.678   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-23 13:27:27.679   873  4047 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-23 13:27:27.688  1501  1501 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-23 13:27:27.689  1501  1501 D AndroidRuntime: Shutting down VM
08-23 13:27:27.690  1501  1501 E AndroidRuntime: FATAL EXCEPTION: main
08-23 13:27:27.690  1501  1501 E AndroidRuntime: Process: com.google.process.gapps, PID: 1501
08-23 13:27:27.690  1501  1501 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 13:27:27.690  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-23 13:27:27.690  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-23 13:27:27.690  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-23 13:27:27.690  1501  1501 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:27:27.690  1501  1501 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 13:27:27.690  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 13:27:27.690  1501  1501 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 13:27:27.690  1501  1501 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 13:27:27.690  1501  1501 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 13:27:27.690  1501  1501 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 13:27:27.690  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-23 13:27:27.690  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-23 13:27:27.690  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-23 13:27:27.690  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 13:27:27.690  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-23 13:27:27.690  1501  1501 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-23 13:27:27.690  1501  1501 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-23 13:27:27.690  1501  1501 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-23 13:27:27.690  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-23 13:27:27.690  1501  1501 E AndroidRuntime: 	... 8 more
08-23 13:27:27.694  1680  4045 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
08-23 13:27:27.695  1680  4045 I Process : Sending signal. PID: 1680 SIG: 9
,08-23 13:27:27.718   873  4049 E DropBoxManagerService: Can't write: system_app_crash
08-23 13:27:27.718   873  4049 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop110.tmp: open failed: EROFS (Read-only file system)
08-23 13:27:27.718   873  4049 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 13:27:27.718   873  4049 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 13:27:27.718   873  4049 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 13:27:27.718   873  4049 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 13:27:27.718   873  4049 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 13:27:27.718   873  4049 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 13:27:27.718   873  4049 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 13:27:27.718   873  4049 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 13:27:27.718   873  4049 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 13:27:27.718   873  4049 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 13:27:27.718   873  4049 E DropBoxManagerService: 	... 5 more
,08-23 13:27:27.729   873   884 I ActivityManager: Process android.process.acore (pid 1680) has died
,08-23 13:27:27.729   873   884 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,08-23 13:27:27.733  1958  2037 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-23 13:27:27.733   873  1335 W System.err: java.io.IOException: write failed: EBADF (Bad file descriptor)
08-23 13:27:27.733   873  1335 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:498)
08-23 13:27:27.733   873  1335 W System.err: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
,08-23 13:27:27.733   873  1335 W System.err: 	at android.graphics.Bitmap.nativeCompress(Native Method)
08-23 13:27:27.733   873  1335 W System.err: 	at android.graphics.Bitmap.compress(Bitmap.java:1027)
08-23 13:27:27.734   873  1335 W System.err: 	at com.android.server.am.TaskPersister$LazyTaskWriterThread.run(TaskPersister.java:557)
,08-23 13:27:27.734   873  1335 W System.err: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
,08-23 13:27:27.734   873  1335 W System.err: 	at libcore.io.Posix.writeBytes(Native Method)
,08-23 13:27:27.734   873  1335 W System.err: 	at libcore.io.Posix.write(Posix.java:271)
08-23 13:27:27.734   873  1335 W System.err: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
08-23 13:27:27.734   873  1335 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:493)
08-23 13:27:27.734   873  1335 W System.err: 	... 4 more
,08-23 13:27:27.734   873  1335 D skia    : ------- write threw an exception
08-23 13:27:27.734   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-23 13:27:27.735   873   885 E PackageManager: Failed to write settings, restoring backup
08-23 13:27:27.735   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-23 13:27:27.735   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-23 13:27:27.735   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-23 13:27:27.735   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-23 13:27:27.735   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-23 13:27:27.735   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:27:27.735   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-23 13:27:27.735   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 13:27:27.737   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-23 13:27:27.737   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-23 13:27:27.737   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 13:27:27.737   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 13:27:27.737   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 13:27:27.737   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 13:27:27.737   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 13:27:27.737   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 13:27:27.737   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-23 13:27:27.737   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-23 13:27:27.737   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-23 13:27:27.737   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 13:27:27.737   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 13:27:27.737   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-23 13:27:27.737   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 13:27:27.737   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-23 13:27:27.737   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 13:27:27.737   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 13:27:27.737   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 13:27:27.737   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 13:27:27.737   873   886 E DropBoxManagerService: 	... 13 more
,08-23 13:27:27.741   873  4047 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-23 13:27:27.741   873  4047 I Adreno  : Build Date                       : 10/20/15
08-23 13:27:27.741   873  4047 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-23 13:27:27.741   873  4047 I Adreno  : Local Branch                     : M14
08-23 13:27:27.741   873  4047 I Adreno  : Remote Branch                    : 
08-23 13:27:27.741   873  4047 I Adreno  : Remote Branch                    : 
08-23 13:27:27.741   873  4047 I Adreno  : Reconstruct Branch               : 
,08-23 13:27:27.746   873  4047 I OpenGLRenderer: Initialized EGL, version 1.4
,08-23 13:27:27.749   873  1676 I ActivityManager: Start proc 4050:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,08-23 13:27:27.749  1958  2037 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-23 13:27:27.749  1958  2037 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1958
08-23 13:27:27.749  1958  2037 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 13:27:27.749  1958  2037 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-23 13:27:27.749  1958  2037 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-23 13:27:27.749  1958  2037 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-23 13:27:27.749  1958  2037 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 13:27:27.749  1958  2037 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-23 13:27:27.749  1958  2037 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-23 13:27:27.749  1958  2037 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-23 13:27:27.749  1958  2037 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 13:27:27.749  1958  2037 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 13:27:27.749  1958  2037 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 13:27:27.749  1958  2037 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 13:27:27.751   873  1898 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-23 13:27:27.755  2008  2024 W SearchService: Abort, client detached.
08-23 13:27:27.757   873  4060 E DropBoxManagerService: Can't write: system_app_crash
08-23 13:27:27.757   873  4060 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
08-23 13:27:27.757   873  4060 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 13:27:27.757   873  4060 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 13:27:27.757   873  4060 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 13:27:27.757   873  4060 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 13:27:27.757   873  4060 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 13:27:27.757   873  4060 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 13:27:27.757   873  4060 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 13:27:27.757   873  4060 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 13:27:27.757   873  4060 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 13:27:27.757   873  4060 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 13:27:27.757   873  4060 E DropBoxManagerService: 	... 5 more
,08-23 13:27:27.758  2008  2008 I HotwordDetector: Closing mic
,08-23 13:27:27.758  2008  2345 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@d47c219
,08-23 13:27:27.758  2008  4026 E AudioRecord-JNI: Error -4 during AudioRecord native read
,08-23 13:27:27.807   376  4028 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,08-23 13:27:27.807   873  1675 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-23 13:27:27.807   376  4028 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-23 13:27:27.811   376  1282 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-23 13:27:27.815  1958  1958 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@f3e9ebf new=com.google.android.velvet.VelvetApplication@f3e9ebf
,08-23 13:27:27.860  2008  4025 I MicroRecognitionRnrImpl: Detection finished
,08-23 13:27:27.861  2008  2349 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-23 13:27:27.864  1958  1958 I GEL     : handleIntent(Intent { act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL })
,08-23 13:27:27.875  2008  4063 E Search.SharedPreferencesProto: Failed to rename to backup file /data/user/0/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,08-23 13:27:27.922   873   891 I ActivityManager: Displayed com.google.android.googlequicksearchbox/com.google.android.launcher.GEL: +111ms
,08-23 13:27:27.930  1711  4073 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-23 13:27:27.931  1711  4073 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-23 13:27:28.053   280   280 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,08-23 13:27:28.053   280   280 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
,08-23 13:27:28.053   280   280 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
08-23 13:27:28.053   280   280 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
08-23 13:27:28.053   280   280 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
08-23 13:27:28.054   280   280 E qdoverlay: MdpCtrl close error in unset

```
