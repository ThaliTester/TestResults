#### Test 82337235c8e499b_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-23 13:40:40.260   872  1888 D NetlinkSocketObserver: NeighborEvent{elapsedMs=118237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-23 13:40:41.982  3747  3747 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-23 13:40:41.987  3747  3747 D AndroidRuntime: CheckJNI is OFF
08-23 13:40:42.030  3747  3747 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-23 13:40:42.080  3747  3747 I Radio-JNI: register_android_hardware_Radio DONE
08-23 13:40:42.104  3747  3747 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-23 13:40:42.109   872  1988 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-23 13:40:42.164  2021  2037 W SearchService: Abort, client detached.
08-23 13:40:42.168  2021  2021 I HotwordDetector: Closing mic
08-23 13:40:42.168  2021  2331 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@a12e95
08-23 13:40:42.169  2021  2347 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-23 13:40:42.181  3747  3747 D AndroidRuntime: Shutting down VM
08-23 13:40:42.216   872   883 I ActivityManager: Start proc 3756:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-23 13:40:42.227   377  2349 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-23 13:40:42.229   377  2349 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-23 13:40:42.235   377  1273 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-23 13:40:42.239  2021  2346 I MicroRecognitionRnrImpl: Detection finished
08-23 13:40:42.239  2021  2345 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-23 13:40:42.294  3756  3756 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-23 13:40:42.317  3756  3756 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-23 13:40:42.324  3756  3756 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 298-302)
08-23 13:40:42.324  3756  3756 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 13:40:42.337  3756  3756 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {34e07ee}
08-23 13:40:42.337  3756  3756 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 13:40:42.338  3756  3756 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-23 13:40:42.344  3756  3756 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-23 13:40:42.345  3756  3756 E SysUtils: ApplicationContext is null in ApplicationStatus
08-23 13:40:42.361  3756  3756 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-23 13:40:42.370  3756  3756 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 13:40:42.371  3756  3756 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 13:40:42.371  3756  3756 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-23 13:40:42.371  3756  3756 I Adreno  : Build Date                       : 10/20/15
08-23 13:40:42.371  3756  3756 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-23 13:40:42.371  3756  3756 I Adreno  : Local Branch                     : M14
08-23 13:40:42.371  3756  3756 I Adreno  : Remote Branch                    : 
08-23 13:40:42.371  3756  3756 I Adreno  : Remote Branch                    : 
08-23 13:40:42.371  3756  3756 I Adreno  : Reconstruct Branch               : 
08-23 13:40:42.412   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@86382ea:true
,08-23 13:40:42.457  3756  3756 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-23 13:40:42.473  3756  3756 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-23 13:40:42.543  3756  3794 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-23 13:40:42.550  3756  3781 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-23 13:40:42.583  3756  3794 I OpenGLRenderer: Initialized EGL, version 1.4
,08-23 13:40:42.646   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +462ms
,08-23 13:40:42.655  1853  1853 I Keyboard.Facilitator: onFinishInput()
,08-23 13:40:42.743  3756  3756 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3756
,08-23 13:40:42.849  3756  3756 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 13:40:43.006   872  1942 I ActivityManager: Killing 3188:com.google.android.gm/u0a78 (adj 15): empty #17
,08-23 13:40:43.043   872  1942 I ActivityManager: Killing 3089:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-23 13:40:43.048  3756  3796 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1719666384
,08-23 13:40:43.058  3756  3796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 13:40:43.058  3756  3796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 13:40:43.058  3756  3796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 13:40:43.058  3756  3796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 13:40:43.058  3756  3796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-23 13:40:43.059  3756  3796 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c3f4b9d added. We now have 1 listener(s)
,08-23 13:40:43.069  3756  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-23 13:40:43.070  3756  3796 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 13:40:43.071  3756  3796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 13:40:43.071  3756  3796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 13:40:43.078  3756  3796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 13:40:43.078  3756  3796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 13:40:43.078  3756  3796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 13:40:43.078  3756  3796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-23 13:40:43.078  3756  3796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 13:40:43.078  3756  3796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 13:40:43.078  3756  3796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 13:40:43.078  3756  3796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 13:40:43.078  3756  3796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 13:40:43.078  3756  3796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 13:40:43.078  3756  3796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 13:40:43.078  3756  3796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 13:40:43.078  3756  3796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 13:40:43.078  3756  3796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-23 13:40:43.078  3756  3796 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f4e9e0 added. We now have 1 listener(s)
,08-23 13:40:43.080  3756  3796 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 13:40:43.084   872  1303 D WifiService: New client listening to asynchronous messages
08-23 13:40:43.086  3756  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 13:40:43.086  3756  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 13:40:43.086  3756  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 13:40:43.087  3756  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 13:40:43.087  3756  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-23 13:40:43.090  3756  3796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 13:40:43.090  3756  3796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-23 13:40:43.096  3756  3796 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-23 13:40:43.096  3756  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 13:40:43.096  3756  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 13:40:43.096  3756  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 13:40:43.096  3756  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 13:40:43.096  3756  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 13:40:43.096  3756  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 13:40:43.096  3756  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 13:40:43.096  3756  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 13:40:43.096  3756  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 13:40:43.096  3756  3796 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 13:40:43.097  3756  3796 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-23 13:40:43.100  3756  3756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 13:40:43.103  3756  3756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 13:40:43.123  3756  3756 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 13:40:44.060  3756  3804 W jxcore-log: Initializing JXcore engine
,08-23 13:40:44.060  3756  3804 W jxcore-log: JXcore engine is ready
,08-23 13:40:44.098  3804  3804 W Thread-321: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8934 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-23 13:40:44.098  3804  3804 W Thread-321: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10069]" dev="sockfs" ino=10069 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-23 13:40:44.098  3804  3804 W Thread-321: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-23 13:40:44.098  3804  3804 W Thread-321: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24337]" dev="sockfs" ino=24337 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-23 13:40:44.114  3756  3804 W jxcore-log: Starting JXcore engine
,08-23 13:40:44.199  3756  3804 W jxcore-log: Platform android
08-23 13:40:44.199  3756  3804 W jxcore-log: 
,08-23 13:40:44.199  3756  3804 W jxcore-log: Process ARCH arm
08-23 13:40:44.199  3756  3804 W jxcore-log: 
,08-23 13:40:44.431  3756  3804 I jxcore-log: JXcore Cordova bridge is ready!
08-23 13:40:44.431  3756  3804 I jxcore-log: 
,08-23 13:40:44.431  3756  3804 W jxcore-log: JXcore engine is started
,08-23 13:40:44.437  3756  3796 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-23 13:40:44.439  3756  3756 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 13:40:44.464  3756  3804 E jxcore  : Error!: missing name after . operator
08-23 13:40:44.464  3756  3804 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"591","_columnNumber":"9","_msg":"    at $w.prototype._compile@module.js:591:9"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"407","_columnNumber":"1","_msg":"    at $w._load@module.js:407:1"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:260:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,08-23 13:40:44.472  3756  3756 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "missing name after . operator\nSyntaxError: missing name after . operator\n    at $w.prototype._compile@module.js:591:9\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1\n    at $w._load@module.js:407:1\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at internal_methods.loadMainFile@main.js:260:5\n    at JXMobile.executeJSON@main.js:279:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (56)
,08-23 13:40:44.473  3756  3756 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
,08-23 13:40:44.480   280   364 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (335 us)
,08-23 13:40:44.515  3756  3756 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-23 13:40:44.515  3756  3756 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
08-23 13:40:44.516  3756  3796 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 43ms. Plugin should use CordovaInterface.getThreadPool().
08-23 13:40:44.528   872   885 I ActivityManager: Killing 2972:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-23 13:40:44.561   872  1302 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
,08-23 13:40:44.589  3756  3756 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-23 13:40:44.589  3756  3756 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-23 13:40:44.589  3756  3756 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-23 13:40:44.589  3756  3756 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-23 13:40:44.589  3756  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 13:40:44.589  3756  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 13:40:44.590  3756  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 13:40:44.590  3756  3756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 13:40:44.590  3756  3756 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c3f4b9d removed from the list
08-23 13:40:44.590  3756  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 13:40:44.590  3756  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f4e9e0 removed from the list
08-23 13:40:44.590  3756  3756 D io.jxcore.node.ConnectivityMonitor: stop
08-23 13:40:44.590  3756  3756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,08-23 13:40:44.603  3756  3756 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-23 13:40:44.652  1853  1853 I Keyboard.Facilitator: onFinishInput()
,08-23 13:40:44.725  2021  3811 I MicroRecognitionRnrImpl: Starting detection.
,08-23 13:40:44.726  2021  3812 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@8415051
08-23 13:40:44.728   377  3815 I AudioFlinger: AudioFlinger's thread 0xb1b00000 ready to run
08-23 13:40:44.730   377  1273 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-23 13:40:44.731  2021  3812 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@8415051
,08-23 13:40:44.741   377  3815 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
08-23 13:40:44.741   377  3815 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
08-23 13:40:44.741   377  3815 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
,08-23 13:40:44.747   377  3815 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,08-23 13:40:44.816  2021  2021 I HotwordWorkerImpl: onReady
,08-23 13:40:45.108  3806  3806 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-23 13:40:45.119  3806  3806 D AndroidRuntime: CheckJNI is OFF
,08-23 13:40:45.160  3806  3806 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-23 13:40:45.161  1944  2171 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,08-23 13:40:45.197  3806  3806 I Radio-JNI: register_android_hardware_Radio DONE
,08-23 13:40:45.216  3806  3806 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-23 13:40:45.229   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-23 13:40:45.229   872   885 I ActivityManager: Killing 3756:com.test.thalitest/u0a0 (adj 9): stop com.test.thalitest
,08-23 13:40:45.312   872  1975 D GraphicsStats: Buffer count: 2
,08-23 13:40:45.313   872  1303 D WifiService: Client connection lost with reason: 4
,08-23 13:40:45.330   872  1374 W ActivityManager: Spurious death for ProcessRecord{93b919e 0:com.test.thalitest/u0a0}, curProc for 3756: null
,08-23 13:40:45.338   872   895 W PackageSettings: Skipping PackageSetting{5401935 com.example.hello/10273} due to missing metadata
,08-23 13:40:45.380   872   895 I art     : Starting a blocking GC Explicit
,08-23 13:40:45.432   872   895 I art     : Explicit concurrent mark sweep GC freed 24676(1613KB) AllocSpace objects, 8(200KB) LOS objects, 33% free, 28MB/43MB, paused 822us total 51.863ms
,08-23 13:40:45.468   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-23 13:40:45.474  3806  3806 I art     : System.exit called, status: 0
,08-23 13:40:45.474  3806  3806 I AndroidRuntime: VM exiting with result code 0.
,08-23 13:40:45.484   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-23 13:40:45.522  2675  2675 D BluetoothMapAppObserver: onReceive
,08-23 13:40:45.523  2675  2675 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-23 13:40:45.523   872  1294 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-23 13:40:45.523  2153  2277 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 13:40:45.544  3625  3625 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-23 13:40:45.544  1853  1853 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-23 13:40:45.546  1853  3828 I Keyboard.Facilitator.DecoderInitializer: run()
,08-23 13:40:45.549  1853  3828 I Decoder : createOrResetDecoder
,08-23 13:40:45.576  1516  1516 I ConfigService: onCreate
,08-23 13:40:45.582  1926  1926 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-23 13:40:45.603  1516  1516 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
08-23 13:40:45.603  1516  1516 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-23 13:40:45.609  1853  3828 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-23 13:40:45.615  1687  3831 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-23 13:40:45.623  1727  3833 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-23 13:40:45.623  1727  3833 D AccountUtils: Clearing selected account for com.test.thalitest
,08-23 13:40:45.626   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-23 13:40:45.632  1687  1715 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj4AC8BC90E) - 
,--------- beginning of crash
08-23 13:40:45.635  1687  1715 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
08-23 13:40:45.635  1687  1715 E AndroidRuntime: Process: android.process.acore, PID: 1687
08-23 13:40:45.635  1687  1715 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
08-23 13:40:45.635  1687  1715 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-23 13:40:45.635  1687  1715 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-23 13:40:45.635  1687  1715 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
08-23 13:40:45.635  1687  1715 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
08-23 13:40:45.635  1687  1715 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
08-23 13:40:45.635  1687  1715 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
08-23 13:40:45.635  1687  1715 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
08-23 13:40:45.635  1687  1715 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
08-23 13:40:45.635  1687  1715 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-23 13:40:45.635  1687  1715 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:40:45.635  1687  1715 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 13:40:45.635  1687  1715 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 13:40:45.657   872  3836 E DropBoxManagerService: Can't write: system_app_crash
08-23 13:40:45.657   872  3836 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
08-23 13:40:45.657   872  3836 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 13:40:45.657   872  3836 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 13:40:45.657   872  3836 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 13:40:45.657   872  3836 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 13:40:45.657   872  3836 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 13:40:45.657   872  3836 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 13:40:45.657   872  3836 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 13:40:45.657   872  3836 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 13:40:45.657   872  3836 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 13:40:45.657   872  3836 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 13:40:45.657   872  3836 E DropBoxManagerService: 	... 5 more
08-23 13:40:45.658  1687  3831 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
08-23 13:40:45.658  1687  3831 I Process : Sending signal. PID: 1687 SIG: 9
08-23 13:40:45.661   872  3838 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-23 13:40:45.667  1727  3833 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-23 13:40:45.668  1727  3839 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-23 13:40:45.669  1727  3839 E DriveAsyncService: disk I/O error (code 3850)
08-23 13:40:45.669  1727  3839 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 13:40:45.669  1727  3839 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-23 13:40:45.669  1727  3839 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-23 13:40:45.669  1727  3839 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-23 13:40:45.669  1727  3839 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-23 13:40:45.669  1727  3839 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-23 13:40:45.669  1727  3839 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-23 13:40:45.669  1727  3839 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.k(SourceFile:483)
08-23 13:40:45.669  1727  3839 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(SourceFile:458)
08-23 13:40:45.669  1727  3839 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.i(SourceFile:1501)
08-23 13:40:45.669  1727  3839 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bj.a(SourceFile:16)
08-23 13:40:45.669  1727  3839 E DriveAsyncService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-23 13:40:45.669  1727  3839 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 13:40:45.669  1727  3839 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 13:40:45.669  1727  3839 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
08-23 13:40:45.669  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-23 13:40:45.669  1727  1727 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-23 13:40:45.673   872  1329 W System.err: java.io.IOException: write failed: EBADF (Bad file descriptor)
08-23 13:40:45.673   872  1329 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:498)
08-23 13:40:45.673   872  1329 W System.err: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
08-23 13:40:45.673   872  1329 W System.err: 	at android.graphics.Bitmap.nativeCompress(Native Method)
08-23 13:40:45.673   872  1329 W System.err: 	at android.graphics.Bitmap.compress(Bitmap.java:1027)
08-23 13:40:45.673   872  1329 W System.err: 	at com.android.server.am.TaskPersister$LazyTaskWriterThread.run(TaskPersister.java:557)
08-23 13:40:45.673   872  1329 W System.err: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
08-23 13:40:45.673   872  1329 W System.err: 	at libcore.io.Posix.writeBytes(Native Method)
08-23 13:40:45.673   872  1329 W System.err: 	at libcore.io.Posix.write(Posix.java:271)
08-23 13:40:45.673   872  1329 W System.err: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
08-23 13:40:45.673   872  1329 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:493)
08-23 13:40:45.674   872  1329 W System.err: 	... 4 more
08-23 13:40:45.674   872  1329 D skia    : ------- write threw an exception
08-23 13:40:45.675  1727  3840 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/metrics.db'.
08-23 13:40:45.675  1727  3840 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 13:40:45.675  1727  3840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 13:40:45.675  1727  3840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 13:40:45.675  1727  3840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 13:40:45.675  1727  3840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 13:40:45.675  1727  3840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 13:40:45.675  1727  3840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 13:40:45.675  1727  3840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 13:40:45.675  1727  3840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 13:40:45.675  1727  3840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 13:40:45.675  1727  3840 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 13:40:45.675  1727  3840 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 13:40:45.675  1727  3840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 13:40:45.675  1727  3840 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-23 13:40:45.675  1727  3840 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
08-23 13:40:45.675  1727  3840 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
08-23 13:40:45.675  1727  3840 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
08-23 13:40:45.675  1727  3840 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-23 13:40:45.675  1727  3840 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-23 13:40:45.675  1727  3840 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:40:45.675  1727  3840 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-23 13:40:45.675  1727  3840 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 13:40:45.676  1727  3840 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
08-23 13:40:45.676  1727  3840 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 13:40:45.676  1727  3840 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 13:40:45.676  1727  3840 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 13:40:45.676  1727  3840 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 13:40:45.676  1727  3840 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 13:40:45.676  1727  3840 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 13:40:45.676  1727  3840 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 13:40:45.676  1727  3840 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 13:40:45.676  1727  3840 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 13:40:45.676  1727  3840 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 13:40:45.676  1727  3840 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 13:40:45.676  1727  3840 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 13:40:45.676  1727  3840 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 13:40:45.676  1727  3840 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-23 13:40:45.676  1727  3840 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
08-23 13:40:45.676  1727  3840 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
08-23 13:40:45.676  1727  3840 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
08-23 13:40:45.676  1727  3840 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-23 13:40:45.676  1727  3840 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-23 13:40:45.676  1727  3840 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:40:45.676  1727  3840 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-23 13:40:45.676  1727  3840 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 13:40:45.678  1727  3840 W SQLiteOpenHelper: Opened metrics.db in read-only mode
08-23 13:40:45.678  1727  3840 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
08-23 13:40:45.678  1727  3840 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
08-23 13:40:45.679  1727  3840 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
08-23 13:40:45.679  1727  3840 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
08-23 13:40:45.680  1727  3840 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
08-23 13:40:45.680  1727  3840 E AndroidRuntime: Process: com.google.android.gms, PID: 1727
08-23 13:40:45.680  1727  3840 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-23 13:40:45.680  1727  3840 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-23 13:40:45.680  1727  3840 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-23 13:40:45.680  1727  3840 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-23 13:40:45.680  1727  3840 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 13:40:45.680  1727  3840 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-23 13:40:45.680  1727  3840 E AndroidRuntime: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
08-23 13:40:45.680  1727  3840 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-23 13:40:45.680  1727  3840 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-23 13:40:45.680  1727  3840 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:40:45.680  1727  3840 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 13:40:45.680  1727  3840 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 13:40:45.681  1727  3833 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
08-23 13:40:45.681  1727  3833 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 13:40:45.681  1727  3833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 13:40:45.681  1727  3833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 13:40:45.681  1727  3833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 13:40:45.681  1727  3833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 13:40:45.681  1727  3833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 13:40:45.681  1727  3833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 13:40:45.681  1727  3833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 13:40:45.681  1727  3833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 13:40:45.681  1727  3833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 13:40:45.681  1727  3833 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 13:40:45.681  1727  3833 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 13:40:45.681  1727  3833 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 13:40:45.681  1727  3833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 13:40:45.681  1727  3833 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-23 13:40:45.681  1727  3833 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-23 13:40:45.681  1727  3833 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-23 13:40:45.681  1727  3833 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:40:45.681  1727  3833 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-23 13:40:45.681  1727  3833 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 13:40:45.682  1727  3833 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
08-23 13:40:45.682  1727  3833 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 13:40:45.682  1727  3833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 13:40:45.682  1727  3833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 13:40:45.682  1727  3833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 13:40:45.682  1727  3833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 13:40:45.682  1727  3833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 13:40:45.682  1727  3833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 13:40:45.682  1727  3833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 13:40:45.682  1727  3833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 13:40:45.682  1727  3833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 13:40:45.682  1727  3833 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 13:40:45.682  1727  3833 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 13:40:45.682  1727  3833 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 13:40:45.682  1727  3833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 13:40:45.682  1727  3833 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-23 13:40:45.682  1727  3833 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-23 13:40:45.682  1727  3833 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-23 13:40:45.682  1727  3833 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:40:45.682  1727  3833 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-23 13:40:45.682  1727  3833 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 13:40:45.683  1727  3833 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
08-23 13:40:45.683  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-23 13:40:45.683  1727  1727 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-23 13:40:45.684   872  3843 E DropBoxManagerService: Can't write: system_app_crash
08-23 13:40:45.684   872  3843 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
08-23 13:40:45.684   872  3843 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 13:40:45.684   872  3843 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 13:40:45.684   872  3843 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 13:40:45.684   872  3843 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 13:40:45.684   872  3843 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 13:40:45.684   872  3843 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 13:40:45.684   872  3843 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 13:40:45.684   872  3843 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 13:40:45.684   872  3843 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 13:40:45.684   872  3843 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 13:40:45.684   872  3843 E DropBoxManagerService: 	... 5 more
08-23 13:40:45.687  1727  3845 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-23 13:40:45.688  1727  3845 I Process : Sending signal. PID: 1727 SIG: 9
08-23 13:40:45.697  1853  3828 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-23 13:40:45.698  1944  3848 E ReflectionEngine: Failed to save models
08-23 13:40:45.698  1944  3848 E ReflectionEngine: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/files/engine_16: open failed: EROFS (Read-only file system)
08-23 13:40:45.698  1944  3848 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 13:40:45.698  1944  3848 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 13:40:45.698  1944  3848 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 13:40:45.698  1944  3848 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.BT(ReflectionEngine.java:123)
08-23 13:40:45.698  1944  3848 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:240)
08-23 13:40:45.698  1944  3848 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-23 13:40:45.698  1944  3848 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-23 13:40:45.698  1944  3848 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-23 13:40:45.698  1944  3848 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 13:40:45.698  1944  3848 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 13:40:45.698  1944  3848 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 13:40:45.698  1944  3848 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 13:40:45.698  1944  3848 E ReflectionEngine: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-23 13:40:45.698  1944  3848 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 13:40:45.698  1944  3848 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 13:40:45.698  1944  3848 E ReflectionEngine: 	at java.lang.Thread.run(Thread.java:818)
08-23 13:40:45.698  1944  3848 E ReflectionEngine: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-23 13:40:45.698  1944  3848 E ReflectionEngine: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 13:40:45.698  1944  3848 E ReflectionEngine: 	at libcore.io.Posix.open(Native Method)
08-23 13:40:45.698  1944  3848 E ReflectionEngine: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 13:40:45.698  1944  3848 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 13:40:45.698  1944  3848 E ReflectionEngine: 	... 16 more
,08-23 13:40:45.703   872  1375 I ActivityManager: Start proc 3849:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
08-23 13:40:45.704  2021  3844 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-23 13:40:45.712   872  3838 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-23 13:40:45.712   872  3838 I Adreno  : Build Date                       : 10/20/15
08-23 13:40:45.712   872  3838 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-23 13:40:45.712   872  3838 I Adreno  : Local Branch                     : M14
08-23 13:40:45.712   872  3838 I Adreno  : Remote Branch                    : 
08-23 13:40:45.712   872  3838 I Adreno  : Remote Branch                    : 
08-23 13:40:45.712   872  3838 I Adreno  : Reconstruct Branch               : 
08-23 13:40:45.720   872  3838 I OpenGLRenderer: Initialized EGL, version 1.4
08-23 13:40:45.720  1944  3848 E ObservedEventLogger: Failed to write the stream file
08-23 13:40:45.720  1944  3848 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2431: open failed: EROFS (Read-only file system)
08-23 13:40:45.720  1944  3848 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 13:40:45.720  1944  3848 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 13:40:45.720  1944  3848 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
08-23 13:40:45.720  1944  3848 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
08-23 13:40:45.720  1944  3848 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
08-23 13:40:45.720  1944  3848 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-23 13:40:45.720  1944  3848 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-23 13:40:45.720  1944  3848 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-23 13:40:45.720  1944  3848 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 13:40:45.720  1944  3848 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 13:40:45.720  1944  3848 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 13:40:45.720  1944  3848 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 13:40:45.720  1944  3848 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-23 13:40:45.720  1944  3848 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 13:40:45.720  1944  3848 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 13:40:45.720  1944  3848 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
08-23 13:40:45.720  1944  3848 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-23 13:40:45.720  1944  3848 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 13:40:45.720  1944  3848 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
08-23 13:40:45.720  1944  3848 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 13:40:45.720  1944  3848 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 13:40:45.720  1944  3848 E ObservedEventLogger: 	... 16 more
08-23 13:40:45.721  1944  3848 E ObservedEventLogger: Failed to write the stream file
08-23 13:40:45.721  1944  3848 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2432: open failed: EROFS (Read-only file system)
08-23 13:40:45.721  1944  3848 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 13:40:45.721  1944  3848 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 13:40:45.721  1944  3848 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
08-23 13:40:45.721  1944  3848 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
08-23 13:40:45.721  1944  3848 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
08-23 13:40:45.721  1944  3848 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-23 13:40:45.721  1944  3848 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-23 13:40:45.721  1944  3848 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-23 13:40:45.721  1944  3848 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 13:40:45.721  1944  3848 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 13:40:45.721  1944  3848 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 13:40:45.721  1944  3848 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 13:40:45.721  1944  3848 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-23 13:40:45.721  1944  3848 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 13:40:45.721  1944  3848 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 13:40:45.721  1944  3848 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
08-23 13:40:45.721  1944  3848 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-23 13:40:45.721  1944  3848 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 13:40:45.721  1944  3848 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
08-23 13:40:45.721  1944  3848 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 13:40:45.721  1944  3848 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 13:40:45.721  1944  3848 E ObservedEventLogger: 	... 16 more
08-23 13:40:45.725   872  1952 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@702413b)
08-23 13:40:45.726   872  1304 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 13:40:45.727   872  1304 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 13:40:45.735   872  1375 I ActivityManager: Process com.google.android.gms (pid 1727) has died
08-23 13:40:45.736   872  1375 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
08-23 13:40:45.736   872  1375 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
08-23 13:40:45.737   872  1375 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
08-23 13:40:45.737   872  1375 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10999ms
08-23 13:40:45.737   872  1375 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10999ms
08-23 13:40:45.737   872  1375 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10999ms
08-23 13:40:45.737   872  1375 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 10999ms
08-23 13:40:45.746  2021  3844 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-23 13:40:45.749  1944  2046 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-23 13:40:45.759   872   883 I ActivityManager: Start proc 3864:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,08-23 13:40:45.761   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-23 13:40:45.761  1944  2046 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-23 13:40:45.761  1944  2046 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1944
08-23 13:40:45.761  1944  2046 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 13:40:45.761  1944  2046 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-23 13:40:45.761  1944  2046 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-23 13:40:45.761  1944  2046 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-23 13:40:45.761  1944  2046 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 13:40:45.761  1944  2046 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-23 13:40:45.761  1944  2046 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-23 13:40:45.761  1944  2046 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-23 13:40:45.761  1944  2046 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 13:40:45.761  1944  2046 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 13:40:45.761  1944  2046 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 13:40:45.761  1944  2046 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 13:40:45.761   872   884 E PackageManager: Failed to write settings, restoring backup
08-23 13:40:45.761   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-23 13:40:45.761   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-23 13:40:45.761   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-23 13:40:45.761   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-23 13:40:45.761   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-23 13:40:45.761   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:40:45.761   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-23 13:40:45.761   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 13:40:45.761  2021  3844 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
08-23 13:40:45.762  2021  3844 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-23 13:40:45.762  2021  3844 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 2021
08-23 13:40:45.762  2021  3844 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 13:40:45.762  2021  3844 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-23 13:40:45.762  2021  3844 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-23 13:40:45.762  2021  3844 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-23 13:40:45.762  2021  3844 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-23 13:40:45.762  2021  3844 E AndroidRunti,me: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-23 13:40:45.762  2021  3844 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-23 13:40:45.762  2021  3844 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-23 13:40:45.762  2021  3844 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-23 13:40:45.762  2021  3844 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-23 13:40:45.762  2021  3844 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-23 13:40:45.762  2021  3844 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-23 13:40:45.762  2021  3844 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-23 13:40:45.762  2021  3844 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-23 13:40:45.762  2021  3844 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-23 13:40:45.762  2021  3844 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-23 13:40:45.762  2021  3844 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:40:45.762  2021  3844 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 13:40:45.762  2021  3844 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 13:40:45.762   872  1702 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-23 13:40:45.765  2021  2038 W SearchService: Abort, client detached.
08-23 13:40:45.766   872  1374 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
08-23 13:40:45.766   872  1374 I ActivityManager: Killing 2021:com.google.android.googlequicksearchbox:search/u0a28 (adj 1): crash
08-23 13:40:45.771   872  3871 E DropBoxManagerService: Can't write: system_app_crash
08-23 13:40:45.771   872  3871 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
08-23 13:40:45.771   872  3871 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 13:40:45.771   872  3871 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 13:40:45.771   872  3871 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 13:40:45.771   872  3871 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 13:40:45.771   872  3871 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 13:40:45.771   872  3871 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 13:40:45.771   872  3871 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 13:40:45.771   872  3871 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 13:40:45.771   872  3871 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 13:40:45.771   872  3871 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 13:40:45.771   872  3871 E DropBoxManagerService: 	... 5 more
,08-23 13:40:45.776   872  3877 E DropBoxManagerService: Can't write: system_app_crash
08-23 13:40:45.776   872  3877 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
08-23 13:40:45.776   872  3877 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 13:40:45.776   872  3877 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 13:40:45.776   872  3877 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 13:40:45.776   872  3877 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 13:40:45.776   872  3877 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 13:40:45.776   872  3877 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 13:40:45.776   872  3877 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 13:40:45.776   872  3877 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 13:40:45.776   872  3877 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 13:40:45.776   872  3877 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 13:40:45.776   872  3877 E DropBoxManagerService: 	... 5 more
,08-23 13:40:45.780   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-23 13:40:45.780   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-23 13:40:45.780   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 13:40:45.780   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 13:40:45.780   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 13:40:45.780   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 13:40:45.780   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 13:40:45.780   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 13:40:45.780   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-23 13:40:45.780   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-23 13:40:45.780   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-23 13:40:45.780   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 13:40:45.780   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 13:40:45.780   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-23 13:40:45.780   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 13:40:45.780   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-23 13:40:45.780   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 13:40:45.780   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 13:40:45.780   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 13:40:45.780   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 13:40:45.780   872   885 E DropBoxManagerService: 	... 13 more
08-23 13:40:45.791  1853  3828 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-23 13:40:45.791  1853  3828 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-23 13:40:45.795  1853  3828 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-23 13:40:45.795  1853  3828 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-23 13:40:45.801  3849  3849 W System  : ClassLoader referenced unknown path: /system/app/KeyChain/lib/arm
,08-23 13:40:45.804  1853  3828 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-23 13:40:45.804  1853  3828 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-23 13:40:45.805  1853  3828 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-23 13:40:45.805  1853  3828 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-23 13:40:45.805  1853  3828 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-23 13:40:45.805  1853  3828 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-23 13:40:45.805  1853  3828 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-23 13:40:45.805  1853  3828 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-23 13:40:45.807   872  1303 D WifiService: Client connection lost with reason: 4
08-23 13:40:45.810  3849  3849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2725 
,08-23 13:40:45.811   872  1988 W ActivityManager: Spurious death for ProcessRecord{dca7bcf 0:com.google.android.googlequicksearchbox:search/u0a28}, curProc for 2021: null
,08-23 13:40:45.836   872  1952 I ActivityManager: Process android.process.acore (pid 1687) has died
,08-23 13:40:45.837   872  1952 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 20900ms
,08-23 13:40:45.856   872  1952 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-23 13:40:45.858   377  3815 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-23 13:40:45.859   377  3815 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
,08-23 13:40:45.861   377  1273 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-23 13:40:45.879  1944  1944 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a0bb4a1 new=com.google.android.velvet.VelvetApplication@a0bb4a1
,08-23 13:40:45.897   872   872 I ActivityManager: Start proc 3886:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,08-23 13:40:45.900  3849  3880 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.keychain/databases/grants.db'.
08-23 13:40:45.900  3849  3880 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 13:40:45.900  3849  3880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 13:40:45.900  3849  3880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 13:40:45.900  3849  3880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 13:40:45.900  3849  3880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 13:40:45.900  3849  3880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 13:40:45.900  3849  3880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 13:40:45.900  3849  3880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 13:40:45.900  3849  3880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 13:40:45.900  3849  3880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 13:40:45.900  3849  3880 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 13:40:45.900  3849  3880 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 13:40:45.900  3849  3880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 13:40:45.900  3849  3880 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 13:40:45.900  3849  3880 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-23 13:40:45.900  3849  3880 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-23 13:40:45.900  3849  3880 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-23 13:40:45.900  3849  3880 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:40:45.900  3849  3880 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-23 13:40:45.900  3849  3880 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 13:40:45.901  3849  3880 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-23 13:40:45.901  3849  3880 E AndroidRuntime: Process: com.android.keychain, PID: 3849
08-23 13:40:45.901  3849  3880 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 13:40:45.901  3849  3880 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 13:40:45.901  3849  3880 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 13:40:45.901  3849  3880 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 13:40:45.901  3849  3880 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 13:40:45.901  3849  3880 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 13:40:45.901  3849  3880 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 13:40:45.901  3849  3880 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 13:40:45.901  3849  3880 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 13:40:45.901  3849  3880 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 13:40:45.901  3849  3880 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 13:40:45.901  3849  3880 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 13:40:45.901  3849  3880 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 13:40:45.901  3849  3880 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 13:40:45.901  3849  3880 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-23 13:40:45.901  3849  3880 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-23 13:40:45.901  3849  3880 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-23 13:40:45.901  3849  3880 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:40:45.901  3849  3880 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 13:40:45.901  3849  3880 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 13:40:45.921   872  3899 E DropBoxManagerService: Can't write: system_app_crash
08-23 13:40:45.921   872  3899 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
08-23 13:40:45.921   872  3899 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 13:40:45.921   872  3899 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 13:40:45.921   872  3899 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 13:40:45.921   872  3899 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 13:40:45.921   872  3899 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 13:40:45.921   872  3899 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 13:40:45.921   872  3899 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 13:40:45.921   872  3899 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 13:40:45.921   872  3899 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 13:40:45.921   872  3899 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 13:40:45.921   872  3899 E DropBoxManagerService: 	... 5 more
,08-23 13:40:45.949   872  2097 I ActivityManager: Start proc 3900:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService
,08-23 13:40:45.953  1944  1944 I GEL     : handleIntent(Intent { act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL })
,08-23 13:40:45.978  3886  3886 W System  : ClassLoader referenced unknown path: /system/app/DocumentsUI/lib/arm
,08-23 13:40:46.027   280   280 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
08-23 13:40:46.027   280   280 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
08-23 13:40:46.027   280   280 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
08-23 13:40:46.027   280   280 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
08-23 13:40:46.027   280   280 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
08-23 13:40:46.027   280   280 E qdoverlay: MdpCtrl close error in unset
08-23 13:40:46.028  3900  3900 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-23 13:40:46.040  3900  3900 I MultiDex: VM with version 2.1.0 has multidex support
,08-23 13:40:46.040   872   890 I ActivityManager: Displayed com.google.android.googlequicksearchbox/com.google.android.launcher.GEL: +180ms
08-23 13:40:46.040  3900  3900 I MultiDex: install
08-23 13:40:46.040  3900  3900 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-23 13:40:46.043  1516  3913 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
08-23 13:40:46.043  1516  3913 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 13:40:46.043  1516  3913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 13:40:46.043  1516  3913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 13:40:46.043  1516  3913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 13:40:46.043  1516  3913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 13:40:46.043  1516  3913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 13:40:46.043  1516  3913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 13:40:46.043  1516  3913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 13:40:46.043  1516  3913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 13:40:46.043  1516  3913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 13:40:46.043  1516  3913 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 13:40:46.043  1516  3913 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 13:40:46.043  1516  3913 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 13:40:46.043  1516  3913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 13:40:46.043  1516  3913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-23 13:40:46.043  1516  3913 E SQLiteDatabase: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:100)
08-23 13:40:46.043  1516  3913 E SQLiteDatabase: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-23 13:40:46.043  1516  3913 E SQLiteDatabase: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-23 13:40:46.043  1516  3913 E SQLiteDatabase: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-23 13:40:46.043  1516  3913 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 13:40:46.043  1516  3913 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 13:40:46.043  1516  3913 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-23 13:40:46.044  1516  3913 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
08-23 13:40:46.044  1516  3913 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 13:40:46.044  1516  3913 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 13:40:46.044  1516  3913 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 13:40:46.044  1516  3913 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 13:40:46.044  1516  3913 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 13:40:46.044  1516  3913 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 13:40:46.044  1516  3913 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 13:40:46.044  1516  3913 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 13:40:46.044  1516  3913 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 13:40:46.044  1516  3913 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 13:40:46.044  1516  3913 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 13:40:46.044  1516  3913 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 13:40:46.044  1516  3913 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 13:40:46.044  1516  3913 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 13:40:46.044  1516  3913 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-23 13:40:46.044  1516  3913 E SQLiteOpenHelper: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:100)
08-23 13:40:46.044  1516  3913 E SQLiteOpenHelper: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-23 13:40:46.044  1516  3913 E SQLiteOpenHelper: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-23 13:40:46.044  1516  3913 E SQLiteOpenHelper: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-23 13:40:46.044  1516  3913 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 13:40:46.044  1516  3913 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 13:40:46.044  1516  3913 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-23 13:40:46.044  1516  3913 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
08-23 13:40:46.044  1516  3913 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
08-23 13:40:46.045  1516  3913 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
08-23 13:40:46.045  1516  3913 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-23 13:40:46.045  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-23 13:40:46.045  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-23 13:40:46.045  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-23 13:40:46.045  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-23 13:40:46.045  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-23 13:40:46.045  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-23 13:40:46.045  1516  3913 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-23 13:40:46.045  1516  3913 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-23 13:40:46.045  1516  3913 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-23 13:40:46.045  1516  3913 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-23 13:40:46.045  1516  3913 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 13:40:46.045  1516  3913 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 13:40:46.045  1516  3913 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,08-23 13:40:46.046  1516  3913 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,08-23 13:40:46.047  1516  3913 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
08-23 13:40:46.047  1516  3913 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-23 13:40:46.047  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-23 13:40:46.047  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-23 13:40:46.047  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-23 13:40:46.047  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-23 13:40:46.047  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-23 13:40:46.047  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-23 13:40:46.047  1516  3913 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-23 13:40:46.047  1516  3913 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-23 13:40:46.047  1516  3913 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-23 13:40:46.047  1516  3913 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-23 13:40:46.047  1516  3913 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 13:40:46.047  1516  3913 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 13:40:46.047  1516  3913 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
08-23 13:40:46.048  1516  3913 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,08-23 13:40:46.048  1516  3913 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
08-23 13:40:46.048  1516  3913 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-23 13:40:46.048  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-23 13:40:46.048  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-23 13:40:46.048  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-23 13:40:46.048  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-23 13:40:46.048  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-23 13:40:46.048  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-23 13:40:46.048  1516  3913 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-23 13:40:46.048  1516  3913 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-23 13:40:46.048  1516  3913 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-23 13:40:46.048  1516  3913 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-23 13:40:46.048  1516  3913 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 13:40:46.048  1516  3913 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 13:40:46.048  1516  3913 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
08-23 13:40:46.049  1516  3913 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,08-23 13:40:46.050  1516  3913 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
08-23 13:40:46.050  1516  3913 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-23 13:40:46.050  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-23 13:40:46.050  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-23 13:40:46.050  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-23 13:40:46.050  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-23 13:40:46.050  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-23 13:40:46.050  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-23 13:40:46.050  1516  3913 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-23 13:40:46.050  1516  3913 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-23 13:40:46.050  1516  3913 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-23 13:40:46.050  1516  3913 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-23 13:40:46.050  1516  3913 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 13:40:46.050  1516  3913 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 13:40:46.050  1516  3913 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
08-23 13:40:46.050  1516  3913 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
08-23 13:40:46.051  1516  3913 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
08-23 13:40:46.051  1516  3913 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-23 13:40:46.051  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-23 13:40:46.051  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-23 13:40:46.051  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-23 13:40:46.051  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-23 13:40:46.051  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-23 13:40:46.051  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-23 13:40:46.051  1516  3913 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-23 13:40:46.051  1516  3913 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-23 13:40:46.051  1516  3913 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-23 13:40:46.051  1516  3913 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-23 13:40:46.051  1516  3913 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 13:40:46.051  1516  3913 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 13:40:46.051  1516  3913 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
08-23 13:40:46.051  1516  3913 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
08-23 13:40:46.052  1516  3913 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
08-23 13:40:46.052  1516  3913 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-23 13:40:46.052  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-23 13:40:46.052  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-23 13:40:46.052  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-23 13:40:46.052  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-23 13:40:46.052  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-23 13:40:46.052  1516  3913 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-23 13:40:46.052  1516  3913 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-23 13:40:46.052  1516  3913 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-23 13:40:46.052  1516  3913 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-23 13:40:46.052  1516  3913 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-23 13:40:46.052  1516  3913 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 13:40:46.052  1516  3913 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 13:40:46.052  1516  3913 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
08-23 13:40:46.074   872  1943 I ActivityManager: Start proc 3914:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider

```
