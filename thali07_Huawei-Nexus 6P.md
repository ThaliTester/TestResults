#### Test 96008345c2441a7_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
,12-01 21:53:08.180  3852  4258 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
12-01 21:53:08.276  3852  4258 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
12-01 21:53:08.617  5532  5532 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
12-01 21:53:08.622  5532  5532 D AndroidRuntime: CheckJNI is OFF
12-01 21:53:08.652  5532  5532 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
12-01 21:53:08.688  5532  5532 I Radio-JNI: register_android_hardware_Radio DONE
12-01 21:53:08.705  5532  5532 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
12-01 21:53:08.711   928   938 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
12-01 21:53:08.731  5532  5532 D AndroidRuntime: Shutting down VM
12-01 21:53:08.744  3982  4316 W SearchService: Abort, client detached.
12-01 21:53:08.750  3982  3982 I HotwordDetector: Closing mic
12-01 21:53:08.750  3982  4202 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@ec3b0ea
12-01 21:53:08.751  3982  4231 E AudioRecord-JNI: Error -4 during AudioRecord native read
12-01 21:53:08.762   928  3430 I ActivityManager: Start proc 5541:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
12-01 21:53:08.827   510  4238 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
12-01 21:53:08.828   510  4238 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
12-01 21:53:08.831   510  4238 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
12-01 21:53:08.832   510  4238 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
12-01 21:53:08.833   510  3007 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
12-01 21:53:08.835  3982  4216 I MicroRecognitionRnrImpl: Stopping hotword detection.
12-01 21:53:08.836  3982  4228 I MicroRecognitionRnrImpl: Detection finished
12-01 21:53:08.867  5541  5541 I CordovaLog: Changing log level to DEBUG(3)
12-01 21:53:08.867  5541  5541 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
12-01 21:53:08.867  5541  5541 D CordovaActivity: CordovaActivity.onCreate()
12-01 21:53:08.873  5541  5541 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
12-01 21:53:08.895  5541  5541 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,12-01 21:53:08.950  5541  5541 I LibraryLoader: Time to load native libraries: 51 ms (timestamps 9837-9888)
,12-01 21:53:08.950  5541  5541 I LibraryLoader: Expected native library version number "",actual native library version number ""
,12-01 21:53:08.975  5541  5541 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ab7c519}
,12-01 21:53:08.975  5541  5541 I LibraryLoader: Expected native library version number "",actual native library version number ""
12-01 21:53:08.976  5541  5541 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,12-01 21:53:08.979  5541  5541 I BrowserStartupController: Initializing chromium process, singleProcess=true
,12-01 21:53:08.980  5541  5541 E SysUtils: ApplicationContext is null in ApplicationStatus
,12-01 21:53:09.036  5541  5541 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,12-01 21:53:09.045  5541  5541 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,12-01 21:53:09.045  5541  5541 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
12-01 21:53:09.045  5541  5541 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
12-01 21:53:09.045  5541  5541 I Adreno  : Build Date                       : 12/06/15
12-01 21:53:09.045  5541  5541 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
12-01 21:53:09.045  5541  5541 I Adreno  : Local Branch                     : mybranch17112971
12-01 21:53:09.045  5541  5541 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
12-01 21:53:09.045  5541  5541 I Adreno  : Remote Branch                    : NONE
12-01 21:53:09.045  5541  5541 I Adreno  : Reconstruct Branch               : NOTHING
,12-01 21:53:09.075   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7850682:true
,12-01 21:53:09.109   404   404 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[14031]" dev="sockfs" ino=14031 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
12-01 21:53:09.109   404   404 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[14031]" dev="sockfs" ino=14031 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,12-01 21:53:09.121  5541  5541 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,12-01 21:53:09.129  5541  5541 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,12-01 21:53:09.132  5541  5541 D PluginManager: init()
,12-01 21:53:09.135  5541  5541 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,12-01 21:53:09.149  5541  5541 D CordovaActivity: Started the activity.
,12-01 21:53:09.150  5541  5541 D CordovaActivity: Resumed the activity.
,12-01 21:53:09.154  5541  5578 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,12-01 21:53:09.149   733   733 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33037]" dev="sockfs" ino=33037 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
12-01 21:53:09.149   733   733 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[33037]" dev="sockfs" ino=33037 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,12-01 21:53:09.152  3203  3203 W Binder_4: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[14042]" dev="sockfs" ino=14042 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,12-01 21:53:09.152  3203  3203 W Binder_4: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[14042]" dev="sockfs" ino=14042 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
12-01 21:53:09.158  5541  5565 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,12-01 21:53:09.190  5541  5578 I OpenGLRenderer: Initialized EGL, version 1.4
,12-01 21:53:09.259  3430  3430 W Binder_6: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[31542]" dev="sockfs" ino=31542 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,12-01 21:53:09.259  3430  3430 W Binder_6: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[31542]" dev="sockfs" ino=31542 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,12-01 21:53:09.259  3791  3791 W Binder_8: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[31541]" dev="sockfs" ino=31541 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,12-01 21:53:09.259  3791  3791 W Binder_8: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[31541]" dev="sockfs" ino=31541 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
12-01 21:53:09.261   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +514ms
12-01 21:53:09.263  3672  3672 I Keyboard.Facilitator: onFinishInput()
,12-01 21:53:09.273  5541  5541 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,12-01 21:53:09.290  5541  5541 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5541
,12-01 21:53:09.378  5541  5541 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,12-01 21:53:09.523  5541  5580 D jxcore_app_log: JniHelper::setJavaVM(0xf557c000), pthread_self() = -578291408
,12-01 21:53:09.527  5541  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
12-01 21:53:09.527  5541  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
12-01 21:53:09.527  5541  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
12-01 21:53:09.527  5541  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
12-01 21:53:09.527  5541  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,12-01 21:53:09.527  5541  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e6e3e4 added. We now have 1 listener(s)
,12-01 21:53:09.529  5541  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,12-01 21:53:09.529  5541  5580 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
12-01 21:53:09.530  5541  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 21:53:09.530  5541  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,12-01 21:53:09.532  5541  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
12-01 21:53:09.532  5541  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
12-01 21:53:09.532  5541  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
12-01 21:53:09.532  5541  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
12-01 21:53:09.532  5541  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
12-01 21:53:09.532  5541  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
12-01 21:53:09.532  5541  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
12-01 21:53:09.532  5541  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
12-01 21:53:09.532  5541  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
12-01 21:53:09.532  5541  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
12-01 21:53:09.532  5541  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
12-01 21:53:09.532  5541  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
12-01 21:53:09.532  5541  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
12-01 21:53:09.532  5541  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
12-01 21:53:09.532  5541  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2b813 added. We now have 1 listener(s)
,12-01 21:53:09.532  5541  5580 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,12-01 21:53:09.538   928  2960 D WifiService: New client listening to asynchronous messages
,12-01 21:53:09.538  5541  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
12-01 21:53:09.538  5541  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
12-01 21:53:09.538  5541  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
12-01 21:53:09.539  5541  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
12-01 21:53:09.539  5541  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
12-01 21:53:09.539  5541  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
12-01 21:53:09.539  5541  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
,12-01 21:53:09.540  5541  5580 I io.jxcore.node.LifeCycleMonitor: start: OK
,12-01 21:53:09.631  5541  5541 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,12-01 21:53:09.633  5541  5541 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,12-01 21:53:09.633  5541  5541 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,12-01 21:53:10.063  5541  5587 W jxcore-log: Initializing JXcore engine
,12-01 21:53:10.063  5541  5587 W jxcore-log: JXcore engine is ready
,12-01 21:53:10.086  5587  5587 W Thread-57: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12366 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,12-01 21:53:10.086  5587  5587 W Thread-57: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[16421]" dev="sockfs" ino=16421 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,12-01 21:53:10.086  5587  5587 W Thread-57: type=1400 audit(0.0:113): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
12-01 21:53:10.086  5587  5587 W Thread-57: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[33016]" dev="sockfs" ino=33016 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,12-01 21:53:10.096  5541  5587 W jxcore-log: Starting JXcore engine
,12-01 21:53:10.147  5541  5587 W jxcore-log: Platform android
12-01 21:53:10.147  5541  5587 W jxcore-log: 
,12-01 21:53:10.147  5541  5587 W jxcore-log: Process ARCH arm
12-01 21:53:10.147  5541  5587 W jxcore-log: 
,12-01 21:53:10.338  5541  5587 I jxcore-log: JXcore Cordova bridge is ready!
12-01 21:53:10.338  5541  5587 I jxcore-log: 
12-01 21:53:10.338  5541  5587 W jxcore-log: JXcore engine is started
,12-01 21:53:10.345  5541  5580 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,12-01 21:53:10.353  5541  5541 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,12-01 21:53:10.353  5541  5541 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,12-01 21:53:12.323  3591  3591 I ConfigService: onDestroy
,12-01 21:53:13.757   928  3203 I ActivityManager: Killing 5146:org.codeaurora.ims/1001 (adj 15): empty #17
,12-01 21:53:18.856  3982  5589 W CronetSyncConnectionRcs: Upload content type not set.
,12-01 21:53:20.002   928  2959 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,12-01 21:53:20.093  5541  5587 I jxcore-log: 2016-12-01 20:53:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
12-01 21:53:20.093  5541  5587 I jxcore-log: 
,12-01 21:53:20.094  5541  5587 I jxcore-log: 2016-12-01 20:53:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
12-01 21:53:20.094  5541  5587 I jxcore-log: 
,12-01 21:53:20.099  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,12-01 21:53:20.100  5541  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
12-01 21:53:20.100  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 21:53:20.100  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 21:53:20.100  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
12-01 21:53:20.100  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
12-01 21:53:20.100  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
12-01 21:53:20.100  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
12-01 21:53:20.100  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
12-01 21:53:20.100  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
12-01 21:53:20.101  5541  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,12-01 21:53:20.102  5541  5587 I jxcore-log: 2016-12-01 20:53:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
12-01 21:53:20.102  5541  5587 I jxcore-log: 
12-01 21:53:20.103  5541  5587 I jxcore-log: 2016-12-01 20:53:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
12-01 21:53:20.103  5541  5587 I jxcore-log: 
,12-01 21:53:20.346  5541  5587 I jxcore-log: 2016-12-01 20:53:20 - DEBUG UnitTest_app: 'Running unit tests'
12-01 21:53:20.346  5541  5587 I jxcore-log: 
,12-01 21:53:20.346  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
12-01 21:53:20.346  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@141592c added. We now have 2 listener(s)
12-01 21:53:20.347  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,12-01 21:53:20.347  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 21:53:20.347  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 21:53:20.348  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 21:53:20.348  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6068ff5 added. We now have 2 listener(s)
,12-01 21:53:20.348  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 21:53:20.348  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
12-01 21:53:20.349  5541  5587 D executeNativeTests: Running unit tests
,12-01 21:53:20.391  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,12-01 21:53:20.391  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@152013a added. We now have 3 listener(s)
12-01 21:53:20.392  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
12-01 21:53:20.392  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 21:53:20.392  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,12-01 21:53:20.392  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 21:53:20.392  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb added. We now have 3 listener(s)
12-01 21:53:20.392  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 21:53:20.393  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,12-01 21:53:20.395  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
12-01 21:53:20.396  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,12-01 21:53:20.396  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
12-01 21:53:20.396  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
12-01 21:53:20.397  5541  5587 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
12-01 21:53:20.397  5541  5587 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,12-01 21:53:20.397  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
12-01 21:53:20.397  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
12-01 21:53:20.397  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
12-01 21:53:20.397  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
12-01 21:53:20.397  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,12-01 21:53:20.398  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 21:53:20.398  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 21:53:20.398  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:53:20.398  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,12-01 21:53:20.398  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
12-01 21:53:20.398  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@152013a removed from the list
12-01 21:53:20.398  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:20.398  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb removed from the list
,12-01 21:53:20.398  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
12-01 21:53:20.398  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:20.399  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:20.399  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:20.400  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:20.400  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:20.400  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 21:53:20.400  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 21:53:20.400  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:20.400  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
12-01 21:53:20.401  5541  5587 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,12-01 21:53:20.401  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 21:53:20.401  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,12-01 21:53:20.401  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 21:53:20.401  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:53:20.401  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 21:53:20.401  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@152013a not in the list
12-01 21:53:20.401  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 21:53:20.401  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
12-01 21:53:20.402  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
12-01 21:53:20.402  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:20.402  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:20.402  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:20.402  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:20.402  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:20.402  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 21:53:20.402  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,12-01 21:53:20.403  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:20.403  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
12-01 21:53:20.405  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
12-01 21:53:20.405  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,12-01 21:53:20.405  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
12-01 21:53:20.405  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
12-01 21:53:20.405  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
12-01 21:53:20.405  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
12-01 21:53:20.405  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
12-01 21:53:20.405  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
12-01 21:53:20.405  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
12-01 21:53:20.405  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,12-01 21:53:20.406  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
12-01 21:53:20.406  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
12-01 21:53:20.406  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
12-01 21:53:20.406  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
12-01 21:53:20.406  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,12-01 21:53:20.406  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
12-01 21:53:20.406  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
12-01 21:53:20.406  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
12-01 21:53:20.406  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
12-01 21:53:20.406  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
12-01 21:53:20.406  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
12-01 21:53:20.406  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
12-01 21:53:20.406  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,12-01 21:53:20.406  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
12-01 21:53:20.406  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
12-01 21:53:20.406  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,12-01 21:53:20.406  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
12-01 21:53:20.406  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
12-01 21:53:20.406  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
12-01 21:53:20.406  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
12-01 21:53:20.406  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,12-01 21:53:20.406  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 21:53:20.406  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 21:53:20.406  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,12-01 21:53:20.406  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:53:20.406  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 21:53:20.406  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@152013a not in the list
,12-01 21:53:20.407  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:20.407  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
12-01 21:53:20.407  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
12-01 21:53:20.407  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:20.407  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:20.408  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:20.408  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:20.408  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:20.408  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 21:53:20.408  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 21:53:20.408  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:20.408  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
12-01 21:53:20.408  5541  5587 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
12-01 21:53:20.410  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
12-01 21:53:20.410  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
12-01 21:53:20.414  5541  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
12-01 21:53:20.414  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 21:53:20.414  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 21:53:20.414  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
12-01 21:53:20.414  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
12-01 21:53:20.414  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
12-01 21:53:20.414  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
12-01 21:53:20.414  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
12-01 21:53:20.414  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
12-01 21:53:20.416  5541  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
12-01 21:53:20.418  5541  5587 D io.jxcore.node.ConnectivityMonitor: start: OK
12-01 21:53:20.418  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
12-01 21:53:20.418  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
12-01 21:53:20.418  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
12-01 21:53:20.418  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
12-01 21:53:20.418  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
12-01 21:53:20.420  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
12-01 21:53:20.421  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,12-01 21:53:20.421  5541  5587 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
12-01 21:53:20.421  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
12-01 21:53:20.424  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
12-01 21:53:20.426  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:20.426  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
12-01 21:53:20.427  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
12-01 21:53:20.427  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
12-01 21:53:20.427  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
12-01 21:53:20.428  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
12-01 21:53:20.429  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
12-01 21:53:20.429  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:20.429  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
12-01 21:53:20.429  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
12-01 21:53:20.429  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
12-01 21:53:20.430  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
12-01 21:53:20.430  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:20.430  5541  5587 D BluetoothAdapter: STATE_ON
12-01 21:53:20.432  4227  4244 D BtGatt.GattService: registerClient() - UUID=a8b93ee6-5023-4e53-bfcc-cae0ed35bae5
12-01 21:53:20.433  4227  4277 D BtGatt.GattService: onClientRegistered() - UUID=a8b93ee6-5023-4e53-bfcc-cae0ed35bae5, clientIf=5
12-01 21:53:20.434  5541  5551 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
12-01 21:53:20.435  4227  4404 D BtGatt.GattService: start scan with filters
12-01 21:53:20.440  4227  4288 D BtGatt.ScanManager: handling starting scan
12-01 21:53:20.440  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
12-01 21:53:20.440  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:20.440  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
12-01 21:53:20.441  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:20.441  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
12-01 21:53:20.441  5541  5541 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
12-01 21:53:20.441  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 21:53:20.441  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
12-01 21:53:20.441  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
12-01 21:53:20.441  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
12-01 21:53:20.441  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 21:53:20.442  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:20.442  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
12-01 21:53:20.442  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 21:53:20.442  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
12-01 21:53:20.442  4227  4288 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a585778
12-01 21:53:20.443  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:20.443  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:20.443  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:20.443  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 21:53:20.444  5541  5587 I io.jxcore.node.ConnectionHelper: start: OK
12-01 21:53:20.446  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 21:53:20.446  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
12-01 21:53:20.447  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 21:53:20.447  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
12-01 21:53:20.447  5541  5541 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
12-01 21:53:20.450  4227  4277 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
12-01 21:53:20.450  4227  4277 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:53:20.451  4227  4288 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
12-01 21:53:20.457  4227  4277 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
12-01 21:53:20.458  4227  4277 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:53:20.458  4227  4288 D BtGatt.ScanManager: Starting BLE batch scan
12-01 21:53:20.458  4227  4288 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
12-01 21:53:20.468  4227  4277 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
12-01 21:53:20.468  4227  4277 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 21:53:20.473  4227  4277 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
12-01 21:53:20.473  4227  4277 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 21:53:20.949  5541  5541 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
12-01 21:53:20.949  5541  5541 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,12-01 21:53:20.949  5541  5541 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,12-01 21:53:22.046   928  2961 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,12-01 21:53:22.049   928  2961 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,12-01 21:53:23.711   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:53:24.712   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:53:25.077   928  2961 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,12-01 21:53:25.084   928  2961 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,12-01 21:53:25.448  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,12-01 21:53:25.449  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
12-01 21:53:25.449  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
12-01 21:53:25.449  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 21:53:25.449  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
12-01 21:53:25.449  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,12-01 21:53:25.449  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
12-01 21:53:25.449  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
12-01 21:53:25.450  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:25.450  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
12-01 21:53:25.450  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
12-01 21:53:25.450  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:25.451  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:25.451  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:25.451  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
12-01 21:53:25.452  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:25.453  5541  5587 D BluetoothAdapter: STATE_ON
,12-01 21:53:25.453  4227  4244 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,12-01 21:53:25.453  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
12-01 21:53:25.454  5541  5587 D BluetoothAdapter: STATE_ON
12-01 21:53:25.455  4227  4288 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
12-01 21:53:25.455  4227  4243 D BtGatt.GattService: stopScan() - queue size =1
,12-01 21:53:25.456  4227  4244 D BtGatt.GattService: unregisterClient() - clientIf=5
12-01 21:53:25.456  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
12-01 21:53:25.456  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:25.456  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
12-01 21:53:25.457  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:25.457  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:25.457  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:25.457  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:25.457  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,12-01 21:53:25.457  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:25.458  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:25.458  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:25.458  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
12-01 21:53:25.458  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
12-01 21:53:25.459  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 21:53:25.459  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:25.460  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:25.460  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 21:53:25.461  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:25.461  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:25.461  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:53:25.461  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 21:53:25.461  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 21:53:25.461  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 21:53:25.461  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 21:53:25.461  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@152013a not in the list
12-01 21:53:25.461  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 21:53:25.461  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 21:53:25.462  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
,12-01 21:53:25.462  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
12-01 21:53:25.462  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
12-01 21:53:25.462  5541  5541 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
12-01 21:53:25.462  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,12-01 21:53:25.462  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
12-01 21:53:25.462  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
12-01 21:53:25.463  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,12-01 21:53:25.463  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
12-01 21:53:25.463  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 21:53:25.463  5541  5541 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 21:53:25.464  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
12-01 21:53:25.464  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,12-01 21:53:25.468  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 21:53:25.468  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 21:53:25.468  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,12-01 21:53:25.513  4227  4227 D BtGatt.ScanManager: awakened up at time 86452
,12-01 21:53:25.516  4227  4277 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,12-01 21:53:25.516  4227  4277 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:53:25.516  4227  4277 D BtGatt.GattService: current time is 86455343917
12-01 21:53:25.516  4227  4277 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -86, 92, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -89, 85, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -79, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -80, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
12-01 21:53:25.517  4227  4277 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
12-01 21:53:25.518  4227  4277 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
12-01 21:53:25.519  4227  4277 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
12-01 21:53:25.519  4227  4277 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
12-01 21:53:25.529  4227  4277 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
12-01 21:53:25.529  4227  4277 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 21:53:25.530  4227  4288 D BtGatt.ScanManager: stopping BLe Batch
,12-01 21:53:25.534  4227  4277 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,12-01 21:53:25.534  4227  4277 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:53:25.534  4227  4288 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,12-01 21:53:25.539  4227  4277 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
12-01 21:53:25.539  4227  4277 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 21:53:25.547  3852  5593 I EventLogService: Aggregate from 1480623769375 (log), 1480623769375 (data)
,12-01 21:53:25.634  4696  4733 D Finsky  : [176] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,12-01 21:53:25.636  4696  4696 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,12-01 21:53:25.678   928  3429 I ActivityManager: Killing 4831:com.google.android.calendar/u0a36 (adj 15): empty #17
,12-01 21:53:25.712   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:53:25.964  5541  5541 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,12-01 21:53:26.713   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:53:27.714   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:53:28.714   533   533 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,12-01 21:53:30.471  5541  5587 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,12-01 21:53:30.477  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,12-01 21:53:30.477  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,12-01 21:53:30.492  5541  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
12-01 21:53:30.492  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 21:53:30.492  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 21:53:30.492  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
12-01 21:53:30.492  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
12-01 21:53:30.492  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
12-01 21:53:30.492  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
12-01 21:53:30.492  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
12-01 21:53:30.492  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,12-01 21:53:30.496  5541  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,12-01 21:53:30.497  5541  5587 D io.jxcore.node.ConnectivityMonitor: start: OK
12-01 21:53:30.497  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,12-01 21:53:30.497  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
12-01 21:53:30.497  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,12-01 21:53:30.497  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
12-01 21:53:30.497  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,12-01 21:53:30.501  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 21:53:30.504  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,12-01 21:53:30.505  5541  5587 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
12-01 21:53:30.505  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
12-01 21:53:30.506  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 21:53:30.511  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:30.511  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
12-01 21:53:30.512  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
12-01 21:53:30.512  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
12-01 21:53:30.512  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,12-01 21:53:30.517  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:30.517  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
12-01 21:53:30.518  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
12-01 21:53:30.518  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,12-01 21:53:30.518  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
12-01 21:53:30.518  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.519  5541  5587 D BluetoothAdapter: STATE_ON
,12-01 21:53:30.523  4227  4244 D BtGatt.GattService: registerClient() - UUID=4c4f682a-925c-40e3-ba5c-fe4ae4119859
,12-01 21:53:30.523  4227  4277 D BtGatt.GattService: onClientRegistered() - UUID=4c4f682a-925c-40e3-ba5c-fe4ae4119859, clientIf=5
,12-01 21:53:30.524  5541  5551 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,12-01 21:53:30.524  4227  4404 D BtGatt.GattService: start scan with filters
,12-01 21:53:30.528  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,12-01 21:53:30.528  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:30.528  4227  4288 D BtGatt.ScanManager: handling starting scan
12-01 21:53:30.528  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
12-01 21:53:30.528  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.529  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
12-01 21:53:30.529  5541  5541 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
12-01 21:53:30.529  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 21:53:30.529  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
12-01 21:53:30.529  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,12-01 21:53:30.529  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,12-01 21:53:30.529  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
12-01 21:53:30.529  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 21:53:30.530  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
12-01 21:53:30.531  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,12-01 21:53:30.531  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.535  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.535  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
12-01 21:53:30.536  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.536  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:30.536  5541  5587 I io.jxcore.node.ConnectionHelper: start: OK
12-01 21:53:30.536  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 21:53:30.539  4227  4277 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
12-01 21:53:30.539  4227  4277 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:53:30.539  4227  4288 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
12-01 21:53:30.539   928  3203 I ActivityManager: Killing 5214:com.android.settings/1000 (adj 15): empty #17
12-01 21:53:30.540  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,12-01 21:53:30.540  5541  5587 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
12-01 21:53:30.541  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
12-01 21:53:30.541  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
12-01 21:53:30.541  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 21:53:30.541  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,12-01 21:53:30.541  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 21:53:30.541  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
12-01 21:53:30.542  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 21:53:30.543  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 21:53:30.543  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
12-01 21:53:30.543  5541  5541 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,12-01 21:53:30.543  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
12-01 21:53:30.543  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.543  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
12-01 21:53:30.543  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
12-01 21:53:30.543  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.543  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.544  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:30.544  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
12-01 21:53:30.544  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.545  5541  5587 D BluetoothAdapter: STATE_ON
12-01 21:53:30.545  4227  4244 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
12-01 21:53:30.545  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
12-01 21:53:30.546  5541  5587 D BluetoothAdapter: STATE_ON
12-01 21:53:30.547  4227  4403 D BtGatt.GattService: stopScan() - queue size =1
,12-01 21:53:30.548  4227  4243 D BtGatt.GattService: unregisterClient() - clientIf=5
12-01 21:53:30.549  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
12-01 21:53:30.549  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.549  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
12-01 21:53:30.549  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.549  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:30.549  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.549  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.549  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
12-01 21:53:30.550  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.550  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.550  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:30.550  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
12-01 21:53:30.550  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,12-01 21:53:30.575  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 21:53:30.575  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.576  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.576  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,12-01 21:53:30.576  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.576  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.576  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:53:30.576  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 21:53:30.576  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 21:53:30.576  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 21:53:30.576  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 21:53:30.576  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 21:53:30.576  5541  5541 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,12-01 21:53:30.576  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@152013a not in the list
12-01 21:53:30.576  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 21:53:30.576  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:30.576  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
12-01 21:53:30.576  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
12-01 21:53:30.576  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
12-01 21:53:30.576  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
12-01 21:53:30.576  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
12-01 21:53:30.576  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 21:53:30.577  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,12-01 21:53:30.577  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 21:53:30.577  5541  5541 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 21:53:30.577  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
12-01 21:53:30.577  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 21:53:30.577  4227  4277 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
12-01 21:53:30.577  4227  4277 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 21:53:30.577  4227  4288 D BtGatt.ScanManager: Starting BLE batch scan
12-01 21:53:30.577  4227  4288 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
12-01 21:53:30.581  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 21:53:30.581  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 21:53:30.581  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
12-01 21:53:30.581  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.581  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:30.583  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.583  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:30.583  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.583  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 21:53:30.583  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,12-01 21:53:30.583  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 21:53:30.584  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
12-01 21:53:30.584  5541  5587 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
12-01 21:53:30.586  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
12-01 21:53:30.586  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
12-01 21:53:30.590  4227  4277 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
12-01 21:53:30.590  4227  4277 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:53:30.592  5541  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
12-01 21:53:30.592  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 21:53:30.592  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 21:53:30.592  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
12-01 21:53:30.592  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
12-01 21:53:30.592  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
12-01 21:53:30.592  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
12-01 21:53:30.592  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
12-01 21:53:30.592  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
12-01 21:53:30.594  5541  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
12-01 21:53:30.594  5541  5587 D io.jxcore.node.ConnectivityMonitor: start: OK
12-01 21:53:30.594  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,12-01 21:53:30.595  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
12-01 21:53:30.595  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
12-01 21:53:30.595  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
12-01 21:53:30.595  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
12-01 21:53:30.595  4227  4277 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
12-01 21:53:30.595  4227  4277 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:53:30.597  4227  4288 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
12-01 21:53:30.598  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,12-01 21:53:30.598  5541  5587 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
12-01 21:53:30.598  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,12-01 21:53:30.601  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
12-01 21:53:30.602  4227  4277 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
12-01 21:53:30.602  4227  4277 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:53:30.602  4227  4277 E BtGatt.ContextMap: Context not found for ID 5
12-01 21:53:30.603  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.603  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
12-01 21:53:30.604  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
12-01 21:53:30.604  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
12-01 21:53:30.604  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
12-01 21:53:30.604  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
12-01 21:53:30.606  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.606  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
12-01 21:53:30.607  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,12-01 21:53:30.607  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
12-01 21:53:30.607  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
12-01 21:53:30.607  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.607  5541  5587 D BluetoothAdapter: STATE_ON
12-01 21:53:30.608  4227  4277 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
12-01 21:53:30.608  4227  4277 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:53:30.608  4227  4288 D BtGatt.ScanManager: stopping BLe Batch
12-01 21:53:30.609  4227  4243 D BtGatt.GattService: registerClient() - UUID=ad205439-6f60-41bd-ba52-276c718b872b
12-01 21:53:30.610  4227  4277 D BtGatt.GattService: onClientRegistered() - UUID=ad205439-6f60-41bd-ba52-276c718b872b, clientIf=5
12-01 21:53:30.610  5541  5551 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
12-01 21:53:30.611  4227  4403 D BtGatt.GattService: start scan with filters
,12-01 21:53:30.613  4227  4277 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
12-01 21:53:30.613  4227  4277 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:53:30.613  4227  4288 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
12-01 21:53:30.615  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
12-01 21:53:30.615  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.615  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
12-01 21:53:30.615  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.615  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
12-01 21:53:30.615  5541  5541 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
12-01 21:53:30.615  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 21:53:30.615  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
12-01 21:53:30.615  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
12-01 21:53:30.615  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 21:53:30.616  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
12-01 21:53:30.616  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 21:53:30.616  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
12-01 21:53:30.616  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
12-01 21:53:30.616  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.618  4227  4277 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
12-01 21:53:30.618  4227  4277 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:53:30.619  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.619  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
12-01 21:53:30.619  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.619  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:30.619  5541  5587 I io.jxcore.node.ConnectionHelper: start: OK
12-01 21:53:30.619  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 21:53:30.619  4227  4288 D BtGatt.ScanManager: handling starting scan
,12-01 21:53:30.622  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 21:53:30.623  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 21:53:30.623  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
12-01 21:53:30.623  5541  5541 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
12-01 21:53:30.625  4227  4277 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
12-01 21:53:30.625  4227  4277 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:53:30.625  4227  4288 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,12-01 21:53:30.629  4227  4277 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,12-01 21:53:30.629  4227  4277 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:53:30.629  4227  4288 D BtGatt.ScanManager: Starting BLE batch scan
12-01 21:53:30.629  4227  4288 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,12-01 21:53:30.637  4227  4277 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,12-01 21:53:30.637  4227  4277 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 21:53:30.641  4227  4277 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
12-01 21:53:30.642  4227  4277 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 21:53:31.124  5541  5541 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
12-01 21:53:31.124  5541  5541 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,12-01 21:53:31.125  5541  5541 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,12-01 21:53:31.133   928  2961 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,12-01 21:53:31.137   928  2961 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,12-01 21:53:34.156   928  2961 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,12-01 21:53:34.163   928  2961 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,12-01 21:53:34.685   928  5322 D NetlinkSocketObserver: NeighborEvent{elapsedMs=95623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,12-01 21:53:35.619  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,12-01 21:53:35.620  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
12-01 21:53:35.620  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
12-01 21:53:35.620  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 21:53:35.620  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
12-01 21:53:35.621  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,12-01 21:53:35.621  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
12-01 21:53:35.621  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
12-01 21:53:35.621  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:35.621  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
12-01 21:53:35.621  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
12-01 21:53:35.622  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:35.622  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:35.622  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:35.622  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
12-01 21:53:35.623  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:35.624  5541  5587 D BluetoothAdapter: STATE_ON
12-01 21:53:35.625  4227  4403 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,12-01 21:53:35.625  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
12-01 21:53:35.627  5541  5587 D BluetoothAdapter: STATE_ON
12-01 21:53:35.627  4227  4288 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,12-01 21:53:35.629  4227  4244 D BtGatt.GattService: stopScan() - queue size =1
,12-01 21:53:35.630  4227  4243 D BtGatt.GattService: unregisterClient() - clientIf=5
,12-01 21:53:35.631  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,12-01 21:53:35.631  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:35.632  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
12-01 21:53:35.632  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:35.632  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:35.632  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:35.633  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:35.633  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
12-01 21:53:35.633  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:35.633  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:35.633  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:35.633  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
12-01 21:53:35.634  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,12-01 21:53:35.635  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 21:53:35.635  4227  4227 D BtGatt.ScanManager: awakened up at time 96574
12-01 21:53:35.635  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:35.637  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:35.637  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,12-01 21:53:35.637  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:35.638  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:35.638  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 21:53:35.638  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 21:53:35.639  5541  5541 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,12-01 21:53:35.639  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 21:53:35.639  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
12-01 21:53:35.640  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
12-01 21:53:35.640  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 21:53:35.640  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,12-01 21:53:35.640  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 21:53:35.640  5541  5541 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 21:53:35.641  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
12-01 21:53:35.641  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,12-01 21:53:35.645  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 21:53:35.645  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 21:53:35.645  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,12-01 21:53:35.657  4227  4277 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,12-01 21:53:35.657  4227  4277 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 21:53:35.657  4227  4277 D BtGatt.GattService: current time is 96596631857
,12-01 21:53:35.658  4227  4277 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -86, 94, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -80, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -85, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -79, 63, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -90, 85, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -88, 64, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
12-01 21:53:35.658  4227  4277 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
12-01 21:53:35.658  4227  4277 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
12-01 21:53:35.659  4227  4277 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
12-01 21:53:35.659  4227  4277 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
12-01 21:53:35.659  4227  4277 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,12-01 21:53:35.660  4227  4277 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,12-01 21:53:35.668  4227  4277 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
12-01 21:53:35.668  4227  4277 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:53:35.668  4227  4288 D BtGatt.ScanManager: stopping BLe Batch
,12-01 21:53:35.674  4227  4277 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,12-01 21:53:35.674  4227  4277 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:53:35.674  4227  4288 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,12-01 21:53:35.680  4227  4277 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
12-01 21:53:35.681  4227  4277 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 21:53:36.141  5541  5541 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,12-01 21:53:36.141  5541  5541 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 21:53:36.141  5541  5541 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,12-01 21:53:40.639  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,12-01 21:53:40.640  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 21:53:40.640  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 21:53:40.640  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:53:40.640  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,12-01 21:53:40.640  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 21:53:40.641  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 21:53:40.641  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@152013a not in the list
12-01 21:53:40.641  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:40.641  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
12-01 21:53:40.642  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
12-01 21:53:40.642  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,12-01 21:53:40.648  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.648  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:40.652  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.653  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:40.653  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.653  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 21:53:40.653  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,12-01 21:53:40.653  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:40.653  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
,12-01 21:53:40.655  5541  5587 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,12-01 21:53:40.658  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 21:53:40.659  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,12-01 21:53:40.659  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 21:53:40.659  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:53:40.659  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 21:53:40.659  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@152013a not in the list
12-01 21:53:40.659  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 21:53:40.659  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
12-01 21:53:40.660  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
12-01 21:53:40.660  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.660  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:40.662  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.662  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.663  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:40.663  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 21:53:40.663  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 21:53:40.663  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:40.663  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
,12-01 21:53:40.667  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,12-01 21:53:40.668  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,12-01 21:53:40.668  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 21:53:40.668  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 21:53:40.668  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:53:40.668  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 21:53:40.669  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@152013a not in the list
12-01 21:53:40.669  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:40.669  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
,12-01 21:53:40.669  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
12-01 21:53:40.669  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.670  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:40.673  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.673  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.673  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.673  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,12-01 21:53:40.673  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 21:53:40.673  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 21:53:40.673  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
12-01 21:53:40.674  5541  5587 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
12-01 21:53:40.675  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 21:53:40.675  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 21:53:40.675  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 21:53:40.675  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:53:40.675  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,12-01 21:53:40.675  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@152013a not in the list
12-01 21:53:40.676  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:40.676  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
12-01 21:53:40.676  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
12-01 21:53:40.676  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.676  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.679  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.679  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.679  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.679  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,12-01 21:53:40.679  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 21:53:40.679  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:40.679  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
,12-01 21:53:40.680  5541  5587 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
12-01 21:53:40.680  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 21:53:40.680  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 21:53:40.681  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 21:53:40.681  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:53:40.681  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,12-01 21:53:40.681  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@152013a not in the list
12-01 21:53:40.681  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:40.681  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
12-01 21:53:40.681  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
12-01 21:53:40.681  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.681  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.683  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.683  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.683  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.683  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 21:53:40.683  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 21:53:40.683  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 21:53:40.684  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
12-01 21:53:40.685  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
12-01 21:53:40.685  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
12-01 21:53:40.685  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
12-01 21:53:40.685  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
12-01 21:53:40.685  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
12-01 21:53:40.685  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
12-01 21:53:40.685  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
12-01 21:53:40.685  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,12-01 21:53:40.686  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
12-01 21:53:40.686  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 21:53:40.686  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 21:53:40.686  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 21:53:40.686  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:53:40.686  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 21:53:40.686  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@152013a not in the list
12-01 21:53:40.686  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 21:53:40.686  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
12-01 21:53:40.686  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
12-01 21:53:40.687  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.687  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.688  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.688  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.688  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.689  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 21:53:40.689  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,12-01 21:53:40.689  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:40.689  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
,12-01 21:53:40.690  5541  5587 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,12-01 21:53:40.690  5541  5587 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
12-01 21:53:40.690  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
12-01 21:53:40.695  5541  5587 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
12-01 21:53:40.695  5541  5587 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
12-01 21:53:40.695  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
12-01 21:53:40.695  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
12-01 21:53:40.695  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
12-01 21:53:40.695  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,12-01 21:53:40.696  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
12-01 21:53:40.696  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
12-01 21:53:40.696  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
12-01 21:53:40.696  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
12-01 21:53:40.696  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
12-01 21:53:40.696  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
12-01 21:53:40.696  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,12-01 21:53:40.696  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
12-01 21:53:40.696  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
12-01 21:53:40.696  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
12-01 21:53:40.696  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
12-01 21:53:40.696  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
12-01 21:53:40.697  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,12-01 21:53:40.697  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
12-01 21:53:40.697  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
12-01 21:53:40.697  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
12-01 21:53:40.697  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
12-01 21:53:40.697  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
12-01 21:53:40.697  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
12-01 21:53:40.697  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
12-01 21:53:40.697  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
12-01 21:53:40.697  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
12-01 21:53:40.697  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,12-01 21:53:40.698  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
12-01 21:53:40.698  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
12-01 21:53:40.698  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
12-01 21:53:40.698  5541  5587 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
12-01 21:53:40.698  5541  5587 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
12-01 21:53:40.698  5541  5587 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
12-01 21:53:40.699  5541  5587 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
12-01 21:53:40.699  5541  5587 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
12-01 21:53:40.699  5541  5587 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
12-01 21:53:40.699  5541  5587 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
12-01 21:53:40.699  5541  5587 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
12-01 21:53:40.699  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
12-01 21:53:40.705  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,12-01 21:53:40.707  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,12-01 21:53:40.707  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
12-01 21:53:40.708  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
12-01 21:53:40.708  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
12-01 21:53:40.708  5541  5587 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
12-01 21:53:40.708  5541  5587 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
12-01 21:53:40.708  5541  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
12-01 21:53:40.709  5541  5587 E io.jxcore.node.ConnectionHelper: connect: Callback is null
12-01 21:53:40.709  5541  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
12-01 21:53:40.709  5541  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
12-01 21:53:40.709  5541  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
12-01 21:53:40.710  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,12-01 21:53:40.710  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 21:53:40.710  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 21:53:40.710  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:53:40.710  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 21:53:40.710  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
12-01 21:53:40.711  5541  5595 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
12-01 21:53:40.711  5541  5595 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
12-01 21:53:40.712  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@152013a not in the list
12-01 21:53:40.712  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 21:53:40.712  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
12-01 21:53:40.712  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
12-01 21:53:40.712  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.712  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.713  5541  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
12-01 21:53:40.713  5541  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
12-01 21:53:40.713  5541  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 121)
12-01 21:53:40.714  5541  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 121)
,12-01 21:53:40.714  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.715  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.715  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.715  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 21:53:40.715  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 21:53:40.715  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:40.715  5541  5595 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
12-01 21:53:40.715  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
12-01 21:53:40.715  5541  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
12-01 21:53:40.715  5541  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
12-01 21:53:40.716  5541  5587 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
12-01 21:53:40.717  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 21:53:40.717  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 21:53:40.712  4404  4404 W Binder_4: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[29520]" dev="sockfs" ino=29520 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
12-01 21:53:40.712  4404  4404 W Binder_4: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[29520]" dev="sockfs" ino=29520 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
12-01 21:53:40.717  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 21:53:40.718  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:53:40.718  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 21:53:40.718  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@152013a not in the list
,12-01 21:53:40.719  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:40.719  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
12-01 21:53:40.719  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
,12-01 21:53:40.719  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.719  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.720  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.721  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:40.724  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.724  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 21:53:40.724  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 21:53:40.724  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:40.724  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
,12-01 21:53:40.725  5541  5587 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
12-01 21:53:40.725  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,12-01 21:53:40.725  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 21:53:40.725  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 21:53:40.725  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:53:40.725  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,12-01 21:53:40.726  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@152013a not in the list
12-01 21:53:40.726  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:40.726  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
12-01 21:53:40.726  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
12-01 21:53:40.726  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:40.726  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.727  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.727  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.727  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.727  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,12-01 21:53:40.728  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 21:53:40.728  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:40.728  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
12-01 21:53:40.728  5541  5587 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,12-01 21:53:40.728  5541  5587 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
12-01 21:53:40.729  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
12-01 21:53:40.729  5541  5587 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
12-01 21:53:40.729  5541  5587 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
12-01 21:53:40.729  5541  5587 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
12-01 21:53:40.729  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,12-01 21:53:40.729  5541  5587 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
12-01 21:53:40.729  5541  5587 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
12-01 21:53:40.729  5541  5587 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
12-01 21:53:40.729  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,12-01 21:53:40.729  5541  5587 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
12-01 21:53:40.729  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 21:53:40.730  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,12-01 21:53:40.730  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 21:53:40.730  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:53:40.730  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 21:53:40.730  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@152013a not in the list
12-01 21:53:40.730  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:40.730  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
12-01 21:53:40.730  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
12-01 21:53:40.730  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.730  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.732  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.732  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:40.732  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:40.732  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 21:53:40.732  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 21:53:40.732  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:40.732  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
,12-01 21:53:40.733  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:53:40.733  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 21:53:40.733  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@152013a not in the list
12-01 21:53:40.733  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:40.733  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
,12-01 21:53:40.733  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
,12-01 21:53:43.228   928  2961 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,12-01 21:53:45.734  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 21:53:45.735  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
12-01 21:53:45.735  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:53:45.735  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 21:53:45.735  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@152013a not in the list
12-01 21:53:45.735  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 21:53:45.736  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,12-01 21:53:45.736  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 21:53:45.736  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:53:45.736  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 21:53:45.736  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@152013a not in the list
,12-01 21:53:45.736  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:45.737  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
12-01 21:53:45.737  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
12-01 21:53:45.737  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:45.737  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:45.741  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:45.741  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:45.741  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:45.741  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,12-01 21:53:45.741  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 21:53:45.742  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:45.742  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
12-01 21:53:45.745  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,12-01 21:53:45.746  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,12-01 21:53:45.746  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,12-01 21:53:45.752  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,12-01 21:53:45.754  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
12-01 21:53:45.755  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
12-01 21:53:45.755  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,12-01 21:53:45.755  5541  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,12-01 21:53:45.755  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
12-01 21:53:45.756  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
12-01 21:53:45.756  5541  5541 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
12-01 21:53:45.756  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:53:45.756  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
12-01 21:53:45.757  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,12-01 21:53:45.757  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
12-01 21:53:45.757  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
12-01 21:53:45.758  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
12-01 21:53:45.758  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
12-01 21:53:45.758  5541  5597 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,12-01 21:53:45.758  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@152013a not in the list
12-01 21:53:45.758  5541  5541 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
12-01 21:53:45.758  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:45.758  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
12-01 21:53:45.759  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:45.759  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
12-01 21:53:45.759  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
12-01 21:53:45.759  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:45.759  4244  4244 W Binder_2: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[31580]" dev="sockfs" ino=31580 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,12-01 21:53:45.762  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:45.762  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 21:53:45.762  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:45.762  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:45.762  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
,12-01 21:53:45.762  4244  4244 W Binder_2: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[31580]" dev="sockfs" ino=31580 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
12-01 21:53:45.762  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 21:53:45.763  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 21:53:45.763  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,12-01 21:53:45.763  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 21:53:45.763  5541  5541 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 21:53:45.763  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 21:53:45.763  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:53:45.763  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,12-01 21:53:45.763  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@152013a not in the list
12-01 21:53:45.763  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:45.763  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
12-01 21:53:45.763  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
,12-01 21:53:45.764  5541  5597 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,12-01 21:53:45.764  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:45.764  5541  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,12-01 21:53:45.764  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:45.764  5541  5597 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
12-01 21:53:45.765  5541  5541 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
12-01 21:53:45.765  5541  5541 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 21:53:45.767  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:45.767  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:45.768  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:45.768  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 21:53:45.768  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 21:53:45.768  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:45.768  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
12-01 21:53:45.770  5541  5587 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,12-01 21:53:45.770  5541  5587 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,12-01 21:53:45.770  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
12-01 21:53:45.771  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
12-01 21:53:45.771  5541  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
12-01 21:53:45.771  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 21:53:45.771  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 21:53:45.772  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 21:53:45.772  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:53:45.772  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 21:53:45.772  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@152013a not in the list
12-01 21:53:45.772  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:45.772  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
12-01 21:53:45.772  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
12-01 21:53:45.774  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:45.775  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:45.777  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:45.778  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:45.778  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:45.778  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 21:53:45.778  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 21:53:45.779  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:45.779  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
,12-01 21:53:45.788  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,12-01 21:53:45.788  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 21:53:45.788  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 21:53:45.788  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:53:45.788  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 21:53:45.788  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@152013a not in the list
12-01 21:53:45.789  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 21:53:45.789  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
12-01 21:53:45.789  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
,12-01 21:53:45.789  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:45.789  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:45.790  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:45.790  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:45.790  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:45.791  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,12-01 21:53:45.791  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 21:53:45.791  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:45.791  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
12-01 21:53:45.792  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 21:53:45.792  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,12-01 21:53:45.792  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 21:53:45.792  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:53:45.792  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 21:53:45.792  5541  5587 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@152013a not in the list
12-01 21:53:45.792  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 21:53:45.792  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
12-01 21:53:45.792  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
12-01 21:53:45.792  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:45.792  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:45.794  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:45.794  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:53:45.795  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:53:45.795  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 21:53:45.795  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 21:53:45.795  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:45.795  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92661eb not in the list
,12-01 21:53:45.796  5541  5587 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
12-01 21:53:45.796  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
12-01 21:53:45.796  5541  5587 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
12-01 21:53:45.796  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
12-01 21:53:45.796  5541  5587 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,12-01 21:53:45.796  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
12-01 21:53:45.798  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
12-01 21:53:45.798  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
12-01 21:53:45.798  5541  5587 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
12-01 21:53:45.798  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,12-01 21:53:45.799  5541  5587 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
12-01 21:53:45.799  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
12-01 21:53:45.799  5541  5587 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
12-01 21:53:45.799  5541  5587 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
12-01 21:53:45.799  5541  5587 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
12-01 21:53:45.799  5541  5587 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
12-01 21:53:45.799  5541  5587 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
12-01 21:53:45.800  5541  5587 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
12-01 21:53:45.800  5541  5587 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
12-01 21:53:45.800  5541  5587 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
12-01 21:53:45.800  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 21:53:45.800  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c4678 added. We now have 3 listener(s)
12-01 21:53:45.801  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 21:53:45.803  5541  5587 D BluetoothAdapter: enable(): BT is already enabled..!
12-01 21:53:45.803   928  3429 D WifiService: setWifiEnabled: true pid=5541, uid=10077
12-01 21:53:45.803   928  3429 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,12-01 21:53:45.846  4227  4393 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,12-01 21:53:45.846  4227  4401 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,12-01 21:53:46.264  5541  5541 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,12-01 21:53:49.266   928  2961 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,12-01 21:53:50.808  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 21:53:50.809  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@252c151 added. We now have 4 listener(s)
,12-01 21:53:50.809  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,12-01 21:53:50.821  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 21:53:50.822  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@252c151 removed from the list
12-01 21:53:50.822  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
12-01 21:53:50.823  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,12-01 21:53:50.824  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9c92db6 added. We now have 4 listener(s)
12-01 21:53:50.824  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 21:53:50.827  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:53:50.827  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9c92db6 removed from the list
12-01 21:53:50.827  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
,12-01 21:53:50.828  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,12-01 21:53:50.829  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@75a1ab7 added. We now have 4 listener(s)
,12-01 21:53:50.829  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,12-01 21:53:50.833   928   938 D WifiService: setWifiEnabled: false pid=5541, uid=10077
,12-01 21:53:50.833   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,12-01 21:53:50.838   928  2959 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,12-01 21:53:50.838   928  2959 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,12-01 21:53:50.838   928  2959 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
12-01 21:53:50.838   928  2959 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
12-01 21:53:50.844  4227  4270 D BluetoothAdapterState: Current state: ON, message: 23
12-01 21:53:50.844  4227  4270 D BluetoothAdapterProperties: Setting state to 13
12-01 21:53:50.845  4227  4270 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
12-01 21:53:50.845  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
12-01 21:53:50.845  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
12-01 21:53:50.848  4227  4270 D BluetoothAdapterProperties: onBluetoothDisable()
,12-01 21:53:50.850  4227  4270 I BluetoothAdapterState: Entering PendingCommandState
,12-01 21:53:50.852  4227  4277 D BluetoothAdapterProperties: Scan Mode:20
,12-01 21:53:50.853  4227  4270 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
12-01 21:53:50.857   928  5323 D DhcpClient: Clearing IP address
12-01 21:53:50.858   505   925 D CommandListener: Clearing all IP addresses on wlan0
12-01 21:53:50.858  4227  4227 D HeadsetService: Received stop request...Stopping profile...
,12-01 21:53:50.861   928   928 D BluetoothHeadset: Proxy object disconnected
12-01 21:53:50.861   928   928 D BluetoothHeadset: Proxy object disconnected
12-01 21:53:50.861  3768  3792 D BluetoothHeadset: Proxy object disconnected
12-01 21:53:50.862   928   928 D BluetoothHeadset: Proxy object disconnected
12-01 21:53:50.862  4227  4227 D A2dpService: Received stop request...Stopping profile...
12-01 21:53:50.862  3152  3997 D BluetoothHeadset: Proxy object disconnected
12-01 21:53:50.863  3152  3152 D HeadsetProfile: Bluetooth service disconnected
12-01 21:53:50.863  4227  4407 D A2dpStateMachine: Exit Disconnected: -1
12-01 21:53:50.865   505   925 D CommandListener: Setting iface cfg
12-01 21:53:50.865   928   928 D BluetoothA2dp: Proxy object disconnected
,12-01 21:53:50.867  3152  3152 D BluetoothA2dp: Proxy object disconnected
,12-01 21:53:50.867  4227  4227 D HidService: Received stop request...Stopping profile...
,12-01 21:53:50.867  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 21:53:50.867  4227  4227 D HidService: Stopping Bluetooth HidService
12-01 21:53:50.867  5541  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
12-01 21:53:50.867  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 21:53:50.867  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 21:53:50.867  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
12-01 21:53:50.867  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
12-01 21:53:50.867  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
12-01 21:53:50.867  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
12-01 21:53:50.867  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
12-01 21:53:50.867  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
12-01 21:53:50.868  3152  3152 D BluetoothInputDevice: Proxy object disconnected
,12-01 21:53:50.868  4227  4227 V BluetoothAdapterState: isTurningOff()=true
12-01 21:53:50.868  3152  3152 D HidProfile: Bluetooth service disconnected
12-01 21:53:50.868  4227  4227 V BluetoothAdapterState: isTurningOn()=false
12-01 21:53:50.868  4227  4227 V BluetoothAdapterState: isBleTurningOn()=false
12-01 21:53:50.868  4227  4227 V BluetoothAdapterState: isBleTurningOff()=false
12-01 21:53:50.869  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 21:53:50.869  5541  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
12-01 21:53:50.869  5541  5587 D io.jxcore.node.ConnectivityMonitor: start: OK
12-01 21:53:50.870  4227  4227 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
12-01 21:53:50.870  4227  4227 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
12-01 21:53:50.870  4227  4277 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
12-01 21:53:50.870  4227  4393 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
12-01 21:53:50.870  4227  4393 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
12-01 21:53:50.870  4227  4393 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
12-01 21:53:50.871   928  5324 D DhcpClient: Receive thread stopped
12-01 21:53:50.872  4227  4227 D HealthService: Received stop request...Stopping profile...
12-01 21:53:50.872  4227  4277 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
12-01 21:53:50.872  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
12-01 21:53:50.872  4227  4227 V BluetoothAdapterState: isTurningOff()=true
12-01 21:53:50.873  4227  4227 V BluetoothAdapterState: isTurningOn()=false
12-01 21:53:50.873  4227  4227 V BluetoothAdapterState: isBleTurningOn()=false
12-01 21:53:50.873  4227  4227 V BluetoothAdapterState: isBleTurningOff()=false
12-01 21:53:50.873  4227  4227 D PanService: Received stop request...Stopping profile...
12-01 21:53:50.874  3152  3152 D BluetoothPan: BluetoothPAN Proxy object disconnected
12-01 21:53:50.874  3152  3152 D PanProfile: Bluetooth service disconnected
12-01 21:53:50.874  4227  4227 D BluetoothMapService: Received stop request...Stopping profile...
12-01 21:53:50.874  4227  4227 D BluetoothMapService: stop()
12-01 21:53:50.875  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
12-01 21:53:50.876  4227  4227 D BluetoothMapAppObserver: deinitObservers()
12-01 21:53:50.876  4227  4227 D BluetoothMapAppObserver: removeReceiver()
12-01 21:53:50.877  3591  5390 V NativeCrypto: Read error: ssl=0x7fa88ca180: I/O error during system call, Connection timed out
12-01 21:53:50.878  3152  3152 D BluetoothMap: Proxy object disconnected
12-01 21:53:50.878  3152  3152 D MapProfile: Bluetooth service disconnected
12-01 21:53:50.879  3591  5390 V NativeCrypto: SSL shutdown failed: ssl=0x7fa88ca180: I/O error during system call, Broken pipe
12-01 21:53:50.882   928  3430 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,12-01 21:53:50.885   928  5321 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
12-01 21:53:50.885  4227  4277 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
12-01 21:53:50.885  4227  4393 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
12-01 21:53:50.886  4227  4393 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,12-01 21:53:50.886  4227  4393 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
12-01 21:53:50.886  4227  4393 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
12-01 21:53:50.886  4227  4393 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
12-01 21:53:50.886  4227  4393 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
12-01 21:53:50.886   928  2961 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
12-01 21:53:50.886   928  2961 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,12-01 21:53:50.888   531   531 E Parcel  : Reading a NULL string not supported here.
12-01 21:53:50.889   928  5321 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
12-01 21:53:50.889  4227  4227 D SapService: Received stop request...Stopping profile...
12-01 21:53:50.889  4227  4227 V SapService: stop()
,12-01 21:53:50.891   928   928 D RttService: SCAN_AVAILABLE : 1
12-01 21:53:50.891   928  3066 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,12-01 21:53:50.893  4227  4227 V BluetoothAdapterState: isTurningOff()=true
,12-01 21:53:50.893  4227  4227 V BluetoothAdapterState: isTurningOn()=false
12-01 21:53:50.893  4227  4227 V BluetoothAdapterState: isBleTurningOn()=false
12-01 21:53:50.893  4227  4227 V BluetoothAdapterState: isBleTurningOff()=false
12-01 21:53:50.893  4227  4227 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
12-01 21:53:50.893  4227  4227 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
12-01 21:53:50.893  4227  4277 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
12-01 21:53:50.894  4227  4227 V BluetoothAdapterState: isTurningOff()=true
,12-01 21:53:50.894  4227  4227 V BluetoothAdapterState: isTurningOn()=false
12-01 21:53:50.894  4227  4227 V BluetoothAdapterState: isBleTurningOn()=false
12-01 21:53:50.894  4227  4227 V BluetoothAdapterState: isBleTurningOff()=false
12-01 21:53:50.894   928  2961 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
12-01 21:53:50.894  4227  4227 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,12-01 21:53:50.895  4227  4277 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
12-01 21:53:50.895  4227  4227 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
12-01 21:53:50.895  4227  4227 V BluetoothAdapterState: isTurningOff()=true
12-01 21:53:50.895  4227  4227 V BluetoothAdapterState: isTurningOn()=false
12-01 21:53:50.895  4227  4227 V BluetoothAdapterState: isBleTurningOn()=false
12-01 21:53:50.895  4227  4227 V BluetoothAdapterState: isBleTurningOff()=false
12-01 21:53:50.896  3738  3880 W QCNEJ   : |CORE| network lost: 100
,12-01 21:53:50.897  3738  3880 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,12-01 21:53:50.901  4227  4227 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,12-01 21:53:50.901  4227  4227 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
12-01 21:53:50.902  4227  4227 D BluetoothMapService: MAP Service closeService in
12-01 21:53:50.902  4227  4227 D BluetoothMapMasInstance0: MAP Service shutdown
12-01 21:53:50.902  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 21:53:50.902  4227  4227 D ObexServerSockets0: shutdown(block = true)
12-01 21:53:50.902  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
12-01 21:53:50.902  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 21:53:50.902  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 21:53:50.902  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
12-01 21:53:50.902  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
12-01 21:53:50.902  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
12-01 21:53:50.902  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
12-01 21:53:50.902  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
12-01 21:53:50.902  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
12-01 21:53:50.903  4227  4227 D ObexServerSockets0: shutdown called from another thread - interrupt().
,12-01 21:53:50.903  4227  4415 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
12-01 21:53:50.903  4227  4227 D ObexServerSockets0: shutdown called from another thread - interrupt().
12-01 21:53:50.903  4227  4401 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
12-01 21:53:50.904  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 21:53:50.904  5541  5541 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
12-01 21:53:50.904  4227  4416 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,12-01 21:53:50.904  4227  4227 V BluetoothAdapterState: isTurningOff()=true
12-01 21:53:50.904  4227  4227 V BluetoothAdapterState: isTurningOn()=false
12-01 21:53:50.905  4227  4227 V BluetoothAdapterState: isBleTurningOn()=false
12-01 21:53:50.905  4227  4227 V BluetoothAdapterState: isBleTurningOff()=false
12-01 21:53:50.905  4227  4227 D BluetoothMapService: cleanup()
12-01 21:53:50.905  4227  4227 D BluetoothMapService: MAP Service closeService in
,12-01 21:53:50.905  4227  4227 V BluetoothAdapterState: isTurningOff()=true
12-01 21:53:50.905  4227  4227 V BluetoothAdapterState: isTurningOn()=false
12-01 21:53:50.906  4227  4227 V BluetoothAdapterState: isBleTurningOn()=false
12-01 21:53:50.906  4227  4227 V BluetoothAdapterState: isBleTurningOff()=false
12-01 21:53:50.906  4227  4270 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
12-01 21:53:50.906  4227  4270 D BluetoothAdapterProperties: Setting state to 15
12-01 21:53:50.906  4227  4227 I BtOppRfcommListener: stopping Accept Thread
,12-01 21:53:50.906  4227  4270 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,12-01 21:53:50.906  4227  5236 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
12-01 21:53:50.906  4227  4270 I BluetoothAdapterState: Entering BleOnState
12-01 21:53:50.907  4227  5236 I BtOppRfcommListener: BluetoothSocket listen thread finished
12-01 21:53:50.915   928  2959 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,12-01 21:53:50.921   505   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,12-01 21:53:50.922   928  3429 I ActivityManager: Start proc 5605:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,12-01 21:53:50.924   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
,12-01 21:53:50.925  3152  3996 D BluetoothHeadset: onBluetoothStateChange: up=false
,12-01 21:53:50.925   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
12-01 21:53:50.925   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
12-01 21:53:50.925   928  2959 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
12-01 21:53:50.925  3768  3789 D BluetoothHeadset: onBluetoothStateChange: up=false
,12-01 21:53:50.926  3152  3167 D BluetoothInputDevice: onBluetoothStateChange: up=false
12-01 21:53:50.926  3152  3997 D BluetoothMap: onBluetoothStateChange: up=false
12-01 21:53:50.927  3152  3165 D BluetoothPan: onBluetoothStateChange on: false
12-01 21:53:50.928   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
12-01 21:53:50.928  3152  3996 D BluetoothA2dp: onBluetoothStateChange: up=false
12-01 21:53:50.928  3152  3167 D BluetoothPbap: onBluetoothStateChange: up=false
12-01 21:53:50.929  4227  4270 D BluetoothAdapterState: Current state: BLE ON, message: 20
12-01 21:53:50.929  4227  4270 D BluetoothAdapterProperties: Setting state to 16
12-01 21:53:50.929  4227  4270 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
12-01 21:53:50.931  4227  4270 D BluetoothAdapterProperties: onBleDisable
12-01 21:53:50.931  4227  4270 I BluetoothAdapterState: Entering PendingCommandState
,12-01 21:53:50.931  4227  4271 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
12-01 21:53:50.932  4227  4393 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,12-01 21:53:50.932  4227  4393 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
12-01 21:53:50.933  4227  4277 D BluetoothAdapterProperties: Scan Mode:20
12-01 21:53:50.934  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
12-01 21:53:50.935  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 21:53:50.946   505   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,12-01 21:53:50.946   505   925 D CommandListener: Clearing all IP addresses on wlan0
12-01 21:53:50.947   505   925 D TetherController: Setting IP forward enable = 0
12-01 21:53:50.948   928  2961 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,12-01 21:53:50.948   928  2961 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,12-01 21:53:50.949   928   945 D Tethering: MasterInitialState.processMessage what=3
12-01 21:53:50.951   928  2959 D DhcpClient: doQuit
12-01 21:53:50.952   928  2959 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,12-01 21:53:50.952  3451  3451 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
12-01 21:53:50.952  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
12-01 21:53:50.952   928  5323 D DhcpClient: onQuitting
,12-01 21:53:50.955  3982  3982 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,12-01 21:53:50.953  5191  5191 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@44a395 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,12-01 21:53:50.956  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 21:53:50.956  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
12-01 21:53:50.956  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 21:53:50.956  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 21:53:50.956  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
12-01 21:53:50.956  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
12-01 21:53:50.956  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
12-01 21:53:50.956  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
12-01 21:53:50.956  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
12-01 21:53:50.956  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
12-01 21:53:50.957  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 21:53:50.957  5541  5541 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
12-01 21:53:50.957  4880  4895 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
12-01 21:53:50.957  4880  4895 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
12-01 21:53:50.957  4880  4895 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
12-01 21:53:50.957  4880  4895 E SarControlService: no key has been found,reset the power
,12-01 21:53:50.958  4880  4921 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
12-01 21:53:50.958  4880  4921 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
12-01 21:53:50.958  4880  4921 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
12-01 21:53:50.958  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
12-01 21:53:50.958  4909  4909 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
12-01 21:53:50.960  4880  4921 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
12-01 21:53:50.960  4880  4921 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
12-01 21:53:50.960  4880  4921 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
12-01 21:53:50.960  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
12-01 21:53:50.961  4909  4909 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,12-01 21:53:50.964  4909  4923 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a3b3863 HexData = [00000000ea03000000000000ffffffff]
,12-01 21:53:50.964  4909  4923 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
12-01 21:53:50.964  4909  4923 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
12-01 21:53:50.967  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
12-01 21:53:50.967  4880  4893 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
12-01 21:53:50.969  3451  3451 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,12-01 21:53:50.972  4909  4923 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a3b3863 HexData = [00000000eb03000000000000ffffffff]
,12-01 21:53:50.972  4909  4923 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,12-01 21:53:50.972  4909  4923 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
12-01 21:53:50.973  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
12-01 21:53:50.973  4880  4892 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
12-01 21:53:50.975  3451  3451 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,12-01 21:53:50.984  5605  5605 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
12-01 21:53:50.995  5605  5605 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
12-01 21:53:50.999   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a9983a8:true
12-01 21:53:51.001  3591  3591 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
12-01 21:53:51.005   505   925 E Netd    : netlink response contains error (No such file or directory)
12-01 21:53:51.006   505   925 D TetherController: Setting IP forward enable = 0
12-01 21:53:51.006   928  2961 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
12-01 21:53:51.006   928  2961 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
12-01 21:53:51.009  3451  3451 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
12-01 21:53:51.016  5605  5605 D LocalBluetoothProfileManager: Adding local MAP profile
12-01 21:53:51.018  5605  5605 D BluetoothMap: Create BluetoothMap proxy object
,12-01 21:53:51.021  3451  3451 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,12-01 21:53:51.025  5605  5605 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,12-01 21:53:51.031  5605  5605 D DockEventReceiver: finishStartingService: stopping service
,12-01 21:53:51.034  5605  5605 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,12-01 21:53:51.039  5605  5605 D DockEventReceiver: finishStartingService: stopping service
,12-01 21:53:51.039  3591  3591 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,12-01 21:53:51.041   928  3791 I ActivityManager: Killing 5191:com.google.android.music:main/u0a59 (adj 15): empty #17
,12-01 21:53:51.062  3852  3852 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,12-01 21:53:51.066  3852  3852 D SystemUpdateService: onCreate
,12-01 21:53:51.069  3852  3852 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,12-01 21:53:51.076  3852  5639 I SystemUpdateService: active receiver: enabled
,12-01 21:53:51.078  3852  3852 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,12-01 21:53:51.082  3852  5345 I iu.UploadsManager: num queued entries: 0
,12-01 21:53:51.083  3852  5345 I iu.UploadsManager: num updated entries: 0
12-01 21:53:51.083  3852  5345 I iu.SyncManager: NEXT; no task
,12-01 21:53:51.085  3852  3852 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,12-01 21:53:51.087  3852  3852 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,12-01 21:53:51.088  5348  5348 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,12-01 21:53:51.092  5348  5348 D SprintDMHelper: simOperator: 
12-01 21:53:51.092  5348  5348 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,12-01 21:53:51.093  3852  5639 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,12-01 21:53:51.102  3852  5639 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,12-01 21:53:51.103  3852  5639 I SystemUpdateService: now status is 0 (complete)
12-01 21:53:51.103  3852  5639 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
12-01 21:53:51.103  3852  5639 I SystemUpdateService: file has been verified
12-01 21:53:51.103  3852  5639 I SystemUpdateService: OTA package size = 21989297
,12-01 21:53:51.106  4355  5641 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,12-01 21:53:51.112  3852  5639 I SystemUpdateService: showing system update notification
,12-01 21:53:51.116   928  5638 I ActivityManager: Start proc 5642:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,12-01 21:53:51.125  4355  4355 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,12-01 21:53:51.125   928  2959 D wifi    : In wifi stop Hal
12-01 21:53:51.127   928  2959 D wifi    : halHandle = 0x7f97239dc0, mVM = 0x7fb274d140, mCls = 0x100a12
12-01 21:53:51.127   928  3450 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
12-01 21:53:51.127   928  3450 D WifiHAL : Got a signal to exit!!!
12-01 21:53:51.127   928  3450 I WifiHAL : Exit wifi_event_loop
12-01 21:53:51.128  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
12-01 21:53:51.128   928  2959 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
12-01 21:53:51.128   928  2959 E WifiHAL : Event processing terminated
,12-01 21:53:51.128   928  2959 D wifi    : In wifi cleaned up handler
12-01 21:53:51.128   928  2959 I WifiHAL : Internal cleanup completed
12-01 21:53:51.129  4054  4255 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
12-01 21:53:51.130   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,12-01 21:53:51.136  3852  3852 D SystemUpdateService: onDestroy
,12-01 21:53:51.143  4227  4277 I bt_hci  : shut_down
,12-01 21:53:51.146  4227  4290 D bt_hwcfg: hw_epilog_process
,12-01 21:53:51.147  4227  4290 I bt_vendor: low_power_mode_cb
,12-01 21:53:51.150   928  3450 D wifi    : set interface wlan0 flags (DOWN)
12-01 21:53:51.150  4227  4290 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
12-01 21:53:51.150  4227  4290 I bt_vendor: epilog_cb
12-01 21:53:51.150  4227  4290 I bt_hci  : epilog_finished_callback
12-01 21:53:51.150   928  2959 D WifiNative-HAL: HAL event thread stopped successfully
,12-01 21:53:51.155  4227  4277 I bt_hci_h4: hal_close
,12-01 21:53:51.155  4227  4277 I bt_userial_vendor: device fd = 54 close
,12-01 21:53:51.159  5642  5642 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,12-01 21:53:51.167   928   939 I ActivityManager: Killing 3903:com.android.providers.calendar/u0a1 (adj 15): empty #17
,12-01 21:53:51.262  4227  4271 D bt_stack_manager: event_shut_down_stack finished.
,12-01 21:53:51.262  4227  4270 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,12-01 21:53:51.264  4227  4270 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
12-01 21:53:51.264  4227  4227 D BtGatt.DebugUtils: handleDebugAction() action=null
,12-01 21:53:51.264  4227  4227 D BtGatt.GattService: Received stop request...Stopping profile...
12-01 21:53:51.264  4227  4227 D BtGatt.GattService: stop()
,12-01 21:53:51.264  4227  4227 D BtGatt.AdvertiseManager: advertise clients cleared
12-01 21:53:51.266  4227  4227 V BluetoothAdapterState: isTurningOff()=false
12-01 21:53:51.266  4227  4227 V BluetoothAdapterState: isTurningOn()=false
12-01 21:53:51.266  4227  4227 V BluetoothAdapterState: isBleTurningOn()=false
,12-01 21:53:51.266  4227  4227 V BluetoothAdapterState: isBleTurningOff()=true
,12-01 21:53:51.266  4227  4270 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
12-01 21:53:51.267  4227  4270 D BluetoothAdapterProperties: Setting state to 10
12-01 21:53:51.267  4227  4270 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
12-01 21:53:51.267  4227  4270 I BluetoothAdapterState: Entering OffState
,12-01 21:53:51.268   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,12-01 21:53:51.274  4227  4227 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,12-01 21:53:51.274  4227  4227 W BluetoothSdpJni: Cleaning up Bluetooth Health object
12-01 21:53:51.275  4227  4227 I BluetoothServiceJni: cleanupNative: return from cleanup
12-01 21:53:51.276  4227  4271 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,12-01 21:53:51.278  4227  4227 I art     : System.exit called, status: 0
12-01 21:53:51.278  4227  4227 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,12-01 21:53:51.302   928   939 I ActivityManager: Process com.android.bluetooth (pid 4227) has died
,12-01 21:53:51.353   928   945 D Tethering: InitialState.processMessage what=4
,12-01 21:53:51.357   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,12-01 21:53:53.715   533   533 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,12-01 21:53:53.715   533   533 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,12-01 21:53:55.872   928  3763 D WifiService: setWifiEnabled: true pid=5541, uid=10077
12-01 21:53:55.872   928  3763 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,12-01 21:53:55.883   505   925 D SoftapController: Softap fwReload - Ok
,12-01 21:53:55.887   505   925 D CommandListener: Setting iface cfg
,12-01 21:53:55.888   505   925 D CommandListener: Trying to bring down wlan0
,12-01 21:53:55.889   505   925 D CommandListener: Clearing all IP addresses on wlan0
,12-01 21:53:55.897   928  2959 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,12-01 21:53:56.502   928  2959 D wifi    : set interface wlan0 flags (UP)
,12-01 21:53:56.506   928  2959 I WifiHAL : Initializing wifi
,12-01 21:53:56.506   928  2959 I WifiHAL : Creating socket
12-01 21:53:56.509   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
12-01 21:53:56.512   928  2959 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
12-01 21:53:56.512   928  2959 D wifi    : Did set static halHandle = 0x7f97239dc0
12-01 21:53:56.512   928  2959 D wifi    : halHandle = 0x7f97239dc0, mVM = 0x7fb274d140, mCls = 0x1018e2
12-01 21:53:56.512   928  2959 D wifi    : array field set
12-01 21:53:56.513   928  2959 I WifiNative-HAL: interface[0] = wlan0
,12-01 21:53:56.515   928  5661 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547996540352
12-01 21:53:56.515   928  5661 D wifi    : waitForHalEvents called, vm = 0x7fb274d140, obj = 0x1018e2, env = 0x7f9b3e4440
,12-01 21:53:56.591  5662  5662 I wpa_supplicant: Successfully initialized wpa_supplicant
,12-01 21:53:56.618   928  2959 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,12-01 21:53:56.623  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 21:53:56.663  5662  5662 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,12-01 21:53:56.686  5662  5662 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,12-01 21:53:56.686  5662  5662 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,12-01 21:53:56.699   928  2959 D WifiConfigStore: Loading config and enabling all networks 
,12-01 21:53:56.702  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 21:53:56.702  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
12-01 21:53:56.702  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 21:53:56.702  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 21:53:56.702  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
12-01 21:53:56.702  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
12-01 21:53:56.702  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
12-01 21:53:56.702  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
12-01 21:53:56.702  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
12-01 21:53:56.702  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
12-01 21:53:56.702  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 21:53:56.702  5541  5541 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,12-01 21:53:56.721   928  2959 D WifiConfigStore: loaded 0 passpoint configs
,12-01 21:53:56.722   928  2959 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,12-01 21:53:56.722   928  2959 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
12-01 21:53:56.723   928  2959 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,12-01 21:53:56.723   928  2959 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
12-01 21:53:56.724   928  2959 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,12-01 21:53:56.724   928  2959 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,12-01 21:53:56.725   928  2959 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
12-01 21:53:56.725   928  2959 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
12-01 21:53:56.725   928  2959 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
12-01 21:53:56.725   928  2959 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,12-01 21:53:56.725   928  2959 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
12-01 21:53:56.725   928  2959 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,12-01 21:53:56.727   928  2959 D WifiNative-HAL: Setting external_sim to 1
,12-01 21:53:56.727   928  2959 D wifi    : setting dfs flag to true, 0x7f99d2d9a0
,12-01 21:53:56.728   928  2959 D WifiStateMachine: Setting OUI to DA-A1-19
12-01 21:53:56.728   928  2959 D wifi    : setting scan oui 0x7f99d2d9a0
12-01 21:53:56.728  4355  4355 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,12-01 21:53:56.728   928  2959 D WifiHAL : Sending mac address OUI
,12-01 21:53:56.731   928  2959 E native  : do suspend false
,12-01 21:53:56.737   928  2959 D wifi    : android_net_wifi_setLinkLayerStats: 1
12-01 21:53:56.737   928   928 D RttService: SCAN_AVAILABLE : 3
,12-01 21:53:56.737   928  3066 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,12-01 21:53:56.741   505   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,12-01 21:53:56.743   505   925 D CommandListener: Setting iface cfg
,12-01 21:53:56.746   928  2958 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '125 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 125 Failed to set address (No such device)'
,12-01 21:53:56.746   928  2958 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,12-01 21:53:56.752   928  2958 D WifiNative-HAL: p2pGetDeviceAddress
,12-01 21:53:56.756   928  2958 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,12-01 21:53:56.756   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=117695 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,12-01 21:53:58.716   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:53:59.717   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:53:59.908  5662  5662 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,12-01 21:53:59.912  5662  5662 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,12-01 21:53:59.919  5662  5662 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,12-01 21:53:59.924  5662  5662 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,12-01 21:53:59.988   928  2959 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,12-01 21:53:59.989   928  2959 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
12-01 21:53:59.989   928  2959 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,12-01 21:54:00.001   928  2959 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,12-01 21:54:00.034   928  2959 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,12-01 21:54:00.041  5662  5662 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,12-01 21:54:00.457  5662  5662 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,12-01 21:54:00.495  5662  5662 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,12-01 21:54:00.498  5662  5662 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,12-01 21:54:00.508   928  2959 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,12-01 21:54:00.509   928  2959 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,12-01 21:54:00.509   928  2961 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,12-01 21:54:00.525   928  2959 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,12-01 21:54:00.537   505   925 D CommandListener: Setting iface cfg
,12-01 21:54:00.543   928  2959 D WifiStateMachine: Start Dhcp Watchdog 2
,12-01 21:54:00.549   928  5668 D DhcpClient: Receive thread started
,12-01 21:54:00.553   928  2961 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,12-01 21:54:00.554   928  2959 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,12-01 21:54:00.554   928  2961 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,12-01 21:54:00.634   928  2959 E native  : do suspend false
,12-01 21:54:00.646   928  5667 D DhcpClient: Broadcasting DHCPDISCOVER
,12-01 21:54:00.660   928  5668 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172719, domain null
,12-01 21:54:00.660   928  5667 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172719 seconds
,12-01 21:54:00.662   928  5667 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,12-01 21:54:00.675   928  5668 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,12-01 21:54:00.676   928  5667 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,12-01 21:54:00.678   505   925 D CommandListener: Setting iface cfg
12-01 21:54:00.682   928  2959 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,12-01 21:54:00.687   928  5667 D DhcpClient: Scheduling renewal in 86399s
,12-01 21:54:00.693   928  2959 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,12-01 21:54:00.694   928  2959 D WifiConfigStore: No blacklist allowed without epno enabled
12-01 21:54:00.695   928  2961 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
12-01 21:54:00.698   928  2959 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
12-01 21:54:00.704   928  2961 D ConnectivityService: Adding iface wlan0 to network 101
,12-01 21:54:00.718   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:54:00.746   928  2961 E ConnectivityService: Unexpected mtu value: 0, wlan0
,12-01 21:54:00.746   928  2961 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,12-01 21:54:00.748   928  2961 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
12-01 21:54:00.749   928  2961 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,12-01 21:54:00.751   928  2961 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,12-01 21:54:00.757   928  2961 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,12-01 21:54:00.762   928  2961 D ConnectivityService: scheduleUnvalidatedPrompt 101
,12-01 21:54:00.762   928  2961 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
12-01 21:54:00.762   928  2961 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
12-01 21:54:00.762   928  2961 D ConnectivityService:    accepting network in place of null
12-01 21:54:00.762   928  2959 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
12-01 21:54:00.763   928  2959 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
12-01 21:54:00.763   928  2961 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,12-01 21:54:00.771   928  5666 D NetlinkSocketObserver: NeighborEvent{elapsedMs=121710, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,12-01 21:54:00.787   505   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,12-01 21:54:00.808   505   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,12-01 21:54:00.811  3738  3880 W QCNEJ   : |CORE| network available: 101
,12-01 21:54:00.811   928  2961 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,12-01 21:54:00.811   928  2961 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,12-01 21:54:00.812   928  2961 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
12-01 21:54:00.813   928   945 D Tethering: MasterInitialState.processMessage what=3
,12-01 21:54:00.814  3738  3880 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
12-01 21:54:00.815  3738  3880 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
12-01 21:54:00.815  3738  3880 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
12-01 21:54:00.818  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 21:54:00.818  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
12-01 21:54:00.818  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 21:54:00.818  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 21:54:00.818  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
12-01 21:54:00.818  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
12-01 21:54:00.818  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
12-01 21:54:00.818  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
12-01 21:54:00.818  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
12-01 21:54:00.818  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
12-01 21:54:00.818  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 21:54:00.818  5541  5541 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,12-01 21:54:00.824  4880  4895 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,12-01 21:54:00.824  4880  4895 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
12-01 21:54:00.824  4880  4895 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
,12-01 21:54:00.824  4880  4895 E SarControlService: no key has been found,reset the power
,12-01 21:54:00.824  4880  4921 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
12-01 21:54:00.825  4880  4921 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
12-01 21:54:00.825  4880  4921 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
12-01 21:54:00.825  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
12-01 21:54:00.825  4909  4909 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
12-01 21:54:00.826  4880  4921 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
12-01 21:54:00.827  4880  4921 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,12-01 21:54:00.827  4880  4921 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
12-01 21:54:00.827  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
12-01 21:54:00.827  4909  4909 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,12-01 21:54:00.828  3982  3982 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,12-01 21:54:00.832  3852  3852 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
12-01 21:54:00.833  4909  4923 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a3b3863 HexData = [00000000ec03000000000000ffffffff]
12-01 21:54:00.833  4909  4923 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
12-01 21:54:00.833  4909  4923 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
,12-01 21:54:00.835  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
12-01 21:54:00.835  4880  4893 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,12-01 21:54:00.837  4909  4923 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a3b3863 HexData = [00000000ed03000000000000ffffffff]
12-01 21:54:00.837  4909  4923 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
12-01 21:54:00.837  4909  4923 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
12-01 21:54:00.838   928  5665 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.14,2a00:1450:4001:81a::200e
12-01 21:54:00.838  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
12-01 21:54:00.839  4880  4892 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
12-01 21:54:00.840  3852  3852 D SystemUpdateService: onCreate
12-01 21:54:00.843  3852  3852 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,12-01 21:54:00.853  3852  3852 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,12-01 21:54:00.859  3852  5345 I iu.UploadsManager: num queued entries: 0
,12-01 21:54:00.859  3852  5345 I iu.UploadsManager: num updated entries: 0
12-01 21:54:00.859  3852  5345 I iu.SyncManager: NEXT; no task
,12-01 21:54:00.861  3852  5678 I SystemUpdateService: active receiver: enabled
,12-01 21:54:00.864  3852  3852 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,12-01 21:54:00.866  3852  3852 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,12-01 21:54:00.867  5348  5348 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,12-01 21:54:00.871  5348  5348 D SprintDMHelper: simOperator: 
12-01 21:54:00.871  5348  5348 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,12-01 21:54:00.880   928  3763 D WifiService: setWifiEnabled: false pid=5541, uid=10077
,12-01 21:54:00.880   928  3763 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,12-01 21:54:00.882   928  2959 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,12-01 21:54:00.882   928  2959 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,12-01 21:54:00.883   928  2959 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
12-01 21:54:00.883   928  2959 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,12-01 21:54:00.886   928  5665 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 01 Dec 2016 20:54:00 GMT], X-Android-Received-Millis=[1480625640886], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480625640863]}
,12-01 21:54:00.887   928  2961 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,12-01 21:54:00.887   928  2961 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
12-01 21:54:00.887   928  2961 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
12-01 21:54:00.888   928  2961 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,12-01 21:54:00.891   928  5667 D DhcpClient: Clearing IP address
12-01 21:54:00.891   505   925 D CommandListener: Clearing all IP addresses on wlan0
,12-01 21:54:00.892   505   925 D CommandListener: Setting iface cfg
,12-01 21:54:00.894   928  5668 D DhcpClient: Receive thread stopped
,12-01 21:54:00.896  3852  5678 I SystemUpdateService: Already downloaded, skipping offpeak checks.
12-01 21:54:00.899  4355  5682 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
12-01 21:54:00.900  4355  5682 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,12-01 21:54:00.907   928  2961 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
12-01 21:54:00.907   928  2961 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,12-01 21:54:00.914   531   531 E Parcel  : Reading a NULL string not supported here.
,12-01 21:54:00.915   928   928 D RttService: SCAN_AVAILABLE : 1
12-01 21:54:00.915   928  3066 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,12-01 21:54:00.917  3852  5678 I SystemUpdateService: network: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
12-01 21:54:00.917  3852  5678 I SystemUpdateService: now status is 0 (complete)
12-01 21:54:00.918  3852  5678 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
12-01 21:54:00.918  3852  5678 I SystemUpdateService: file has been verified
12-01 21:54:00.918  3852  5678 I SystemUpdateService: OTA package size = 21989297
,12-01 21:54:00.919   928  2961 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,12-01 21:54:00.920   928  2959 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
12-01 21:54:00.921  3738  3880 W QCNEJ   : |CORE| network lost: 101
12-01 21:54:00.922  3738  3880 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,12-01 21:54:00.925   928  2959 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,12-01 21:54:00.928  3852  5678 I SystemUpdateService: showing system update notification
,12-01 21:54:00.939   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,12-01 21:54:00.940  3852  3852 D SystemUpdateService: onDestroy
12-01 21:54:00.942   505   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,12-01 21:54:00.961   505   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,12-01 21:54:00.962   928  2961 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
12-01 21:54:00.962   928  2961 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
12-01 21:54:00.962   505   925 D CommandListener: Clearing all IP addresses on wlan0
,12-01 21:54:00.963   928   945 D Tethering: MasterInitialState.processMessage what=3
12-01 21:54:00.965  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 21:54:00.965  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
12-01 21:54:00.965  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 21:54:00.965  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 21:54:00.965  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
12-01 21:54:00.965  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
12-01 21:54:00.965  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
12-01 21:54:00.965  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
12-01 21:54:00.965  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
12-01 21:54:00.965  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
12-01 21:54:00.965  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 21:54:00.965  5541  5541 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,12-01 21:54:00.968  3982  3982 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,12-01 21:54:00.973  4880  4895 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
12-01 21:54:00.973  4880  4895 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
12-01 21:54:00.973  4880  4895 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
,12-01 21:54:00.973  4880  4895 E SarControlService: no key has been found,reset the power
12-01 21:54:00.974  4880  4921 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
12-01 21:54:00.974  4880  4921 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
12-01 21:54:00.974  4880  4921 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
12-01 21:54:00.974  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
12-01 21:54:00.974  4909  4909 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
12-01 21:54:00.972  3852  3852 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
12-01 21:54:00.976  4880  4921 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
12-01 21:54:00.976  4880  4921 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
12-01 21:54:00.977  4880  4921 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,12-01 21:54:00.977  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
12-01 21:54:00.977  4909  4909 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
12-01 21:54:00.980  3852  3852 D SystemUpdateService: onCreate
12-01 21:54:00.981  4909  4923 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a3b3863 HexData = [00000000ee03000000000000ffffffff]
12-01 21:54:00.981  4909  4923 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
12-01 21:54:00.981  4909  4923 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
,12-01 21:54:00.982  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
12-01 21:54:00.982  4880  4892 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
12-01 21:54:00.984  4909  4923 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a3b3863 HexData = [00000000ef03000000000000ffffffff]
12-01 21:54:00.984  4909  4923 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
12-01 21:54:00.984  4909  4923 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
,12-01 21:54:00.984  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
12-01 21:54:00.985  4880  4893 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
12-01 21:54:00.985  3852  3852 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,12-01 21:54:00.989  3852  5696 I SystemUpdateService: active receiver: enabled
,12-01 21:54:00.994  3852  3852 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,12-01 21:54:00.999  3852  5345 I iu.UploadsManager: num queued entries: 0
,12-01 21:54:01.000  3852  5345 I iu.UploadsManager: num updated entries: 0
12-01 21:54:01.000  3852  5345 I iu.SyncManager: NEXT; no task
,12-01 21:54:01.002  3852  3852 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,12-01 21:54:01.003  3852  3852 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,12-01 21:54:01.005  5348  5348 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,12-01 21:54:01.009  5348  5348 D SprintDMHelper: simOperator: 
12-01 21:54:01.009  5348  5348 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,12-01 21:54:01.009   505   925 E Netd    : netlink response contains error (No such file or directory)
,12-01 21:54:01.010  3852  5696 I SystemUpdateService: Already downloaded, skipping offpeak checks.
12-01 21:54:01.010   928  2961 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,12-01 21:54:01.011   928  2959 D DhcpClient: doQuit
,12-01 21:54:01.011   928  2959 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
12-01 21:54:01.012   928  5667 D DhcpClient: onQuitting
12-01 21:54:01.012  3852  5696 I SystemUpdateService: network: null; metered: false; mobile allowed: true
12-01 21:54:01.012  3852  5696 I SystemUpdateService: now status is 0 (complete)
12-01 21:54:01.012  3852  5696 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
12-01 21:54:01.012  5662  5662 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
12-01 21:54:01.012  3852  5696 I SystemUpdateService: file has been verified
12-01 21:54:01.013  3852  5696 I SystemUpdateService: OTA package size = 21989297
,12-01 21:54:01.016  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,12-01 21:54:01.016  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
12-01 21:54:01.016  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 21:54:01.016  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 21:54:01.016  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
12-01 21:54:01.016  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
12-01 21:54:01.016  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
12-01 21:54:01.016  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
12-01 21:54:01.016  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
12-01 21:54:01.016  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
12-01 21:54:01.016  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 21:54:01.016  5541  5541 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,12-01 21:54:01.026  4355  5700 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,12-01 21:54:01.028  5662  5662 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,12-01 21:54:01.030  5662  5662 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,12-01 21:54:01.040  3852  5696 I SystemUpdateService: showing system update notification
,12-01 21:54:01.046   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,12-01 21:54:01.047  3852  3852 D SystemUpdateService: onDestroy
,12-01 21:54:01.066  5662  5662 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,12-01 21:54:01.071  5662  5662 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,12-01 21:54:01.173   928  2959 D wifi    : In wifi stop Hal
,12-01 21:54:01.174   928  2959 D wifi    : halHandle = 0x7f97239dc0, mVM = 0x7fb274d140, mCls = 0x1018e2
12-01 21:54:01.178   928  5661 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
12-01 21:54:01.178   928  5661 D WifiHAL : Got a signal to exit!!!
,12-01 21:54:01.178   928  5661 I WifiHAL : Exit wifi_event_loop
12-01 21:54:01.179   928  2959 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
12-01 21:54:01.180   928  2959 E WifiHAL : Event processing terminated
12-01 21:54:01.180  4355  4355 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
12-01 21:54:01.180  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
12-01 21:54:01.180   928  2959 D wifi    : In wifi cleaned up handler
,12-01 21:54:01.180   928  2959 I WifiHAL : Internal cleanup completed
12-01 21:54:01.185  4054  4255 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,12-01 21:54:01.205   928  5661 D wifi    : set interface wlan0 flags (DOWN)
,12-01 21:54:01.206   928  2959 D WifiNative-HAL: HAL event thread stopped successfully
,12-01 21:54:01.411   928   945 D Tethering: InitialState.processMessage what=4
,12-01 21:54:01.416   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,12-01 21:54:01.719   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:54:01.811   928  2961 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,12-01 21:54:02.720   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:54:03.721   533   533 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,12-01 21:54:05.918   928   945 I ActivityManager: Start proc 5702:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,12-01 21:54:06.010  5702  5702 D AdapterServiceConfig: Adding HeadsetService
,12-01 21:54:06.010  5702  5702 D AdapterServiceConfig: Adding A2dpService
12-01 21:54:06.010  5702  5702 D AdapterServiceConfig: Adding HidService
12-01 21:54:06.010  5702  5702 D AdapterServiceConfig: Adding HealthService
12-01 21:54:06.011  5702  5702 D AdapterServiceConfig: Adding PanService
12-01 21:54:06.011  5702  5702 D AdapterServiceConfig: Adding GattService
,12-01 21:54:06.011  5702  5702 D AdapterServiceConfig: Adding BluetoothMapService
12-01 21:54:06.011  5702  5702 D AdapterServiceConfig: Adding SapService
,12-01 21:54:06.024   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@93b41e5:true
,12-01 21:54:06.024  5702  5702 D BluetoothAdapterState: make() - Creating AdapterState
,12-01 21:54:06.028  5702  5702 I bt_bluedroid: init
12-01 21:54:06.028  5702  5714 I BluetoothAdapterState: Entering OffState
,12-01 21:54:06.029  5702  5715 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,12-01 21:54:06.030  5702  5715 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
12-01 21:54:06.030  5702  5715 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
12-01 21:54:06.030  5702  5715 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,12-01 21:54:06.030  5702  5702 I bt_bluedroid: get_profile_interface socket
,12-01 21:54:06.032  5702  5702 I bt_bluedroid: get_profile_interface sdp
,12-01 21:54:06.032  5702  5718 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
12-01 21:54:06.033  5702  5718 D BluetoothAdapterProperties: Name is: Nexus 6P
,12-01 21:54:06.036  5702  5713 I bt_bluedroid: config_hci_snoop_log
,12-01 21:54:06.037   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,12-01 21:54:06.041  5702  5714 D BluetoothAdapterState: Current state: OFF, message: 0
12-01 21:54:06.041  5702  5714 D BluetoothAdapterProperties: Setting state to 14
12-01 21:54:06.041  5702  5714 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,12-01 21:54:06.042  5702  5714 D BluetoothBondStateMachine: make
,12-01 21:54:06.044  5702  5719 I BluetoothBondStateMachine: StableState(): Entering Off State
,12-01 21:54:06.046  5702  5714 I BluetoothAdapterState: Entering PendingCommandState
,12-01 21:54:06.047  5702  5702 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,12-01 21:54:06.049  5702  5702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a585778
12-01 21:54:06.050  5702  5702 D BtGatt.DebugUtils: handleDebugAction() action=null
12-01 21:54:06.051  5702  5702 D BtGatt.GattService: Received start request. Starting profile...
12-01 21:54:06.051  5702  5702 D BtGatt.GattService: start()
,12-01 21:54:06.051  5702  5702 I bt_bluedroid: get_profile_interface gatt
,12-01 21:54:06.052  5702  5702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a585778
12-01 21:54:06.052  5702  5702 D BtGatt.AdvertiseManager: advertise manager created
,12-01 21:54:06.056  5702  5702 V BluetoothAdapterState: isTurningOff()=false
,12-01 21:54:06.056  5702  5702 V BluetoothAdapterState: isTurningOn()=false
12-01 21:54:06.056  5702  5702 V BluetoothAdapterState: isBleTurningOn()=true
12-01 21:54:06.056  5702  5702 V BluetoothAdapterState: isBleTurningOff()=false
12-01 21:54:06.056  5702  5714 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,12-01 21:54:06.057  5702  5714 I bt_bluedroid: bt_bluedroid
12-01 21:54:06.058  5702  5715 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,12-01 21:54:06.058  5702  5715 I bt_hci  : start_up
,12-01 21:54:06.063  5702  5715 I bt_vendor: alloc value 0xf4239871
12-01 21:54:06.063  5702  5715 I bt_vendor: init
,12-01 21:54:06.063  5702  5715 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
12-01 21:54:06.063  5702  5715 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,12-01 21:54:06.174  5702  5715 D bt_hci  : start_up starting async portion
12-01 21:54:06.175  5702  5722 I bt_hci  : event_finish_startup
,12-01 21:54:06.175  5702  5722 I bt_hci_h4: hal_open
12-01 21:54:06.175  5702  5722 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,12-01 21:54:06.178  5702  5722 I bt_userial_vendor: device fd = 54 open
,12-01 21:54:06.172  5723  5723 W irq/448-msm_hs_: type=1400 audit(0.0:119): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,12-01 21:54:06.192  5702  5722 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,12-01 21:54:06.194  5702  5722 D bt_hwcfg: Chipset BCM4358A3
12-01 21:54:06.195  5702  5722 D bt_hwcfg: Target name = [BCM4358A3]
,12-01 21:54:06.195  5702  5722 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,12-01 21:54:06.590  5702  5722 I bt_hwcfg: bt vendor lib: set UART baud 115200
,12-01 21:54:06.590  5702  5722 D bt_hwcfg: Settlement delay -- 100 ms
12-01 21:54:06.590  5702  5722 I bt_hwcfg: Setting fw settlement delay to 100 
,12-01 21:54:06.725  5702  5722 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,12-01 21:54:06.725  5702  5722 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,12-01 21:54:06.727  5702  5722 I bt_hwcfg: vendor lib fwcfg completed
,12-01 21:54:06.727  5702  5722 I bt_vendor: firmware callback
,12-01 21:54:06.727  5702  5722 I bt_hci  : firmware_config_callback
,12-01 21:54:06.735  5702  5725 I bt_btu  : btu_task pending for preload complete event
,12-01 21:54:06.735  5702  5725 I bt_btu_task: Bluetooth chip preload is complete
,12-01 21:54:06.736  5702  5725 I bt_btu  : btu_task received preload complete event
,12-01 21:54:06.743  5702  5725 I         : BTE_InitTraceLevels -- TRC_HCI
,12-01 21:54:06.743  5702  5725 I         : BTE_InitTraceLevels -- TRC_L2CAP
,12-01 21:54:06.743  5702  5725 I         : BTE_InitTraceLevels -- TRC_RFCOMM
12-01 21:54:06.743  5702  5725 I         : BTE_InitTraceLevels -- TRC_AVDT
,12-01 21:54:06.743  5702  5725 I         : BTE_InitTraceLevels -- TRC_AVRC
12-01 21:54:06.743  5702  5725 I         : BTE_InitTraceLevels -- TRC_A2D
,12-01 21:54:06.743  5702  5725 I         : BTE_InitTraceLevels -- TRC_BNEP
12-01 21:54:06.743  5702  5725 I         : BTE_InitTraceLevels -- TRC_BTM
12-01 21:54:06.743  5702  5725 I         : BTE_InitTraceLevels -- TRC_GAP
,12-01 21:54:06.744  5702  5725 I         : BTE_InitTraceLevels -- TRC_PAN
12-01 21:54:06.744  5702  5725 I         : BTE_InitTraceLevels -- TRC_SDP
12-01 21:54:06.744  5702  5725 I         : BTE_InitTraceLevels -- TRC_GATT
,12-01 21:54:06.744  5702  5725 I         : BTE_InitTraceLevels -- TRC_SMP
12-01 21:54:06.744  5702  5725 I         : BTE_InitTraceLevels -- TRC_BTAPP
12-01 21:54:06.744  5702  5725 I         : BTE_InitTraceLevels -- TRC_BTIF
,12-01 21:54:06.825  5702  5725 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf41b7549
,12-01 21:54:06.825  5702  5725 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf41b7549 
,12-01 21:54:06.837  5702  5718 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,12-01 21:54:06.838  5702  5718 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
12-01 21:54:06.839  5702  5718 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,12-01 21:54:06.841  5702  5718 D BluetoothAdapterProperties: Name is: Nexus 6P
,12-01 21:54:06.844  5702  5718 D BluetoothAdapterProperties: Scan Mode:20
12-01 21:54:06.845  5702  5718 D BluetoothAdapterProperties: Discoverable Timeout:120
12-01 21:54:06.845  5702  5718 D bt_hci  : do_postload posting postload work item
,12-01 21:54:06.845  5702  5722 I bt_hci  : event_postload
12-01 21:54:06.845  5702  5722 I bt_vendor: sco_config_cb
12-01 21:54:06.846  5702  5722 I bt_hci  : sco_config_callback postload finished.
,12-01 21:54:06.852  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 21:54:06.852  5702  5718 D bt_bte_conf: Device ID record 1 : primary
12-01 21:54:06.852  5702  5718 D bt_bte_conf:   vendorId            = 000f
12-01 21:54:06.852  5702  5718 D bt_bte_conf:   vendorIdSource      = 0001
,12-01 21:54:06.852  5702  5718 D bt_bte_conf:   product             = 1200
,12-01 21:54:06.852  5702  5718 D bt_bte_conf:   version             = 1436
,12-01 21:54:06.852  5702  5718 D bt_bte_conf:   clientExecutableURL = 
12-01 21:54:06.852  5702  5718 D bt_bte_conf:   serviceDescription  = 
,12-01 21:54:06.852  5702  5718 D bt_bte_conf:   documentationURL    = 
12-01 21:54:06.852  5702  5718 D bt_bte_conf: bte_load_did_conf no section named DID2.
12-01 21:54:06.853  5702  5715 D bt_stack_manager: event_start_up_stack finished
12-01 21:54:06.853  5702  5714 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
12-01 21:54:06.854  5702  5714 D BluetoothAdapterProperties: Setting state to 15
12-01 21:54:06.854  5702  5714 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
12-01 21:54:06.854  5702  5722 I bt_vendor: low_power_mode_cb
12-01 21:54:06.855  5702  5714 I BluetoothAdapterState: Entering BleOnState
,12-01 21:54:06.860  5702  5714 D BluetoothAdapterState: Current state: BLE ON, message: 1
,12-01 21:54:06.861  5702  5714 D BluetoothAdapterProperties: Setting state to 11
,12-01 21:54:06.861  5702  5714 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,12-01 21:54:06.867  5702  5702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a585778
12-01 21:54:06.868  5702  5702 D HeadsetService: Received start request. Starting profile...
,12-01 21:54:06.869  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 21:54:06.872  5702  5702 I BluetoothHeadsetServiceJni: classInitNative: succeeds
12-01 21:54:06.872  5702  5702 D HeadsetStateMachine: make
,12-01 21:54:06.878  5702  5714 I BluetoothAdapterState: Entering PendingCommandState
,12-01 21:54:06.882  5702  5702 D HeadsetStateMachine: max_hf_connections = 1
,12-01 21:54:06.883  5702  5702 I bt_bluedroid: get_profile_interface handsfree
12-01 21:54:06.883  5702  5718 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
12-01 21:54:06.883  5702  5718 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,12-01 21:54:06.887  5702  5702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a585778
,12-01 21:54:06.888  5702  5702 D A2dpService: Received start request. Starting profile...
,12-01 21:54:06.889  5702  5702 I BluetoothAvrcpServiceJni: classInitNative: succeeds
12-01 21:54:06.889  5702  5702 I bt_bluedroid: get_profile_interface avrcp
,12-01 21:54:06.894  5702  5702 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,12-01 21:54:06.894  5702  5702 I BluetoothA2dpServiceJni: classInitNative: succeeds
12-01 21:54:06.895  5702  5702 D A2dpStateMachine: make
12-01 21:54:06.896  5702  5702 I bt_bluedroid: get_profile_interface a2dp
,12-01 21:54:06.896  5702  5718 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,12-01 21:54:06.898  5702  5733 D A2dpStateMachine: Enter Disconnected: -2
,12-01 21:54:06.900  5702  5702 I BluetoothHidServiceJni: classInitNative: succeeds
12-01 21:54:06.901  3591  3591 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,12-01 21:54:06.902  5702  5702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a585778
,12-01 21:54:06.903  5702  5702 D HidService: Received start request. Starting profile...
12-01 21:54:06.903  5702  5702 I bt_bluedroid: get_profile_interface hidhost
12-01 21:54:06.903  5702  5702 D HidService: setHidService(): set to: null
12-01 21:54:06.903  5702  5718 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf419856d
12-01 21:54:06.904  5702  5718 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
12-01 21:54:06.904  5702  5702 I BluetoothHealthServiceJni: classInitNative: succeeds
,12-01 21:54:06.905  5702  5702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a585778
,12-01 21:54:06.905  5702  5702 D HealthService: Received start request. Starting profile...
12-01 21:54:06.906  5605  5605 D BluetoothInputDevice: Proxy object connected
12-01 21:54:06.906  5605  5605 D HidProfile: Bluetooth service connected
12-01 21:54:06.907  5702  5702 I bt_bluedroid: get_profile_interface health
12-01 21:54:06.907  5702  5702 I BluetoothPanServiceJni: classInitNative(L105): succeeds
12-01 21:54:06.908  5702  5702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a585778
,12-01 21:54:06.909  5605  5605 D BluetoothPan: BluetoothPAN Proxy object connected
12-01 21:54:06.909  5702  5702 D PanService: Received start request. Starting profile...
12-01 21:54:06.909  5702  5702 D BluetoothPanServiceJni: initializeNative(L110): pan
12-01 21:54:06.909  5702  5702 I bt_bluedroid: get_profile_interface pan
12-01 21:54:06.909  5605  5605 D PanProfile: Bluetooth service connected
12-01 21:54:06.910  5702  5718 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,12-01 21:54:06.911  5702  5702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a585778
,12-01 21:54:06.912  5605  5605 D BluetoothMap: Proxy object connected
12-01 21:54:06.913  5605  5605 D MapProfile: Bluetooth service connected
12-01 21:54:06.913  5605  5605 D BluetoothMap: getConnectedDevices()
12-01 21:54:06.914  5702  5702 D BluetoothMapService: Received start request. Starting profile...
12-01 21:54:06.914  5702  5702 D BluetoothMapService: start()
12-01 21:54:06.916  5702  5702 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
12-01 21:54:06.917  5702  5702 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
12-01 21:54:06.917  5702  5702 D BluetoothMapAppObserver: createReceiver()
12-01 21:54:06.918  5702  5702 D BluetoothMapAppObserver: initObservers()
,12-01 21:54:06.918  5702  5702 D BluetoothMapAppObserver: getEnabledAccountItems()
12-01 21:54:06.923  5702  5702 V SapService: SapBinder()
12-01 21:54:06.924  5702  5702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a585778
12-01 21:54:06.924  5702  5702 D SapService: Received start request. Starting profile...
12-01 21:54:06.924  5702  5702 V SapService: start()
,12-01 21:54:06.927  5702  5702 V BluetoothAdapterState: isTurningOff()=false
12-01 21:54:06.927  5702  5702 V BluetoothAdapterState: isTurningOn()=true
12-01 21:54:06.927  5702  5702 V BluetoothAdapterState: isBleTurningOn()=false
12-01 21:54:06.927  5702  5702 V BluetoothAdapterState: isBleTurningOff()=false
12-01 21:54:06.927  5702  5702 V BluetoothAdapterState: isTurningOff()=false
,12-01 21:54:06.927  5702  5702 V BluetoothAdapterState: isTurningOn()=true
12-01 21:54:06.927  5702  5731 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
12-01 21:54:06.928  5702  5702 V BluetoothAdapterState: isBleTurningOn()=false
12-01 21:54:06.928  5702  5702 V BluetoothAdapterState: isBleTurningOff()=false
12-01 21:54:06.928  5702  5702 V BluetoothAdapterState: isTurningOff()=false
12-01 21:54:06.928  5702  5702 V BluetoothAdapterState: isTurningOn()=true
12-01 21:54:06.928  5702  5702 V BluetoothAdapterState: isBleTurningOn()=false
12-01 21:54:06.928  5702  5702 V BluetoothAdapterState: isBleTurningOff()=false
12-01 21:54:06.928  5702  5702 V BluetoothAdapterState: isTurningOff()=false
12-01 21:54:06.928  5702  5702 V BluetoothAdapterState: isTurningOn()=true
12-01 21:54:06.928  5702  5702 V BluetoothAdapterState: isBleTurningOn()=false
12-01 21:54:06.928  5702  5702 V BluetoothAdapterState: isBleTurningOff()=false
12-01 21:54:06.929  5702  5702 V BluetoothAdapterState: isTurningOff()=false
12-01 21:54:06.929  5702  5702 V BluetoothAdapterState: isTurningOn()=true
12-01 21:54:06.929  5702  5702 V BluetoothAdapterState: isBleTurningOn()=false
12-01 21:54:06.929  5702  5702 V BluetoothAdapterState: isBleTurningOff()=false
12-01 21:54:06.929  5702  5702 V BluetoothAdapterState: isTurningOff()=false
12-01 21:54:06.929  5702  5702 V BluetoothAdapterState: isTurningOn()=true
12-01 21:54:06.929  5702  5702 V BluetoothAdapterState: isBleTurningOn()=false
12-01 21:54:06.929  5702  5702 V BluetoothAdapterState: isBleTurningOff()=false
12-01 21:54:06.930  5702  5702 V BluetoothAdapterState: isTurningOff()=false
,12-01 21:54:06.930  5702  5702 V BluetoothAdapterState: isTurningOn()=true
12-01 21:54:06.930  5702  5702 V BluetoothAdapterState: isBleTurningOn()=false
12-01 21:54:06.930  5702  5702 V BluetoothAdapterState: isBleTurningOff()=false
12-01 21:54:06.930  5702  5714 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
12-01 21:54:06.930  5702  5714 D BluetoothAdapterProperties: ScanMode =  20
12-01 21:54:06.930  5702  5714 D BluetoothAdapterProperties: State =  11
,12-01 21:54:06.931  5702  5714 D BluetoothAdapterProperties: Setting state to 12
12-01 21:54:06.931  5702  5714 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
12-01 21:54:06.931   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
12-01 21:54:06.931  5702  5714 I BluetoothAdapterState: Entering OnState
12-01 21:54:06.931  5605  5605 D BluetoothMap: Bluetooth is Not enabled
12-01 21:54:06.933  3152  3165 D BluetoothHeadset: onBluetoothStateChange: up=true
12-01 21:54:06.934   928   928 D BluetoothA2dp: Proxy object connected
12-01 21:54:06.934   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,12-01 21:54:06.934   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
12-01 21:54:06.934  3768  3999 D BluetoothHeadset: onBluetoothStateChange: up=true
12-01 21:54:06.935  3152  3996 D BluetoothInputDevice: onBluetoothStateChange: up=true
12-01 21:54:06.935  5702  5718 D BluetoothAdapterProperties: Scan Mode:21
12-01 21:54:06.935  5702  5718 D BluetoothAdapterProperties: Discoverable Timeout:120
12-01 21:54:06.935  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
12-01 21:54:06.937  3152  3152 D BluetoothInputDevice: Proxy object connected
,12-01 21:54:06.938  3152  3152 D HidProfile: Bluetooth service connected
12-01 21:54:06.939  3152  3167 D BluetoothMap: onBluetoothStateChange: up=true
12-01 21:54:06.940  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
12-01 21:54:06.940  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 21:54:06.940  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 21:54:06.940  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
12-01 21:54:06.940  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
12-01 21:54:06.940  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
12-01 21:54:06.940  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
12-01 21:54:06.940  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
12-01 21:54:06.940  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,12-01 21:54:06.940  5605  5619 D BluetoothPan: onBluetoothStateChange on: true
12-01 21:54:06.940  3152  3152 D BluetoothMap: Proxy object connected
12-01 21:54:06.941  3152  3152 D MapProfile: Bluetooth service connected
12-01 21:54:06.941  3152  3152 D BluetoothMap: getConnectedDevices()
,12-01 21:54:06.941  3152  3997 D BluetoothPan: onBluetoothStateChange on: true
,12-01 21:54:06.943  5702  5702 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
12-01 21:54:06.943   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
12-01 21:54:06.943  5541  5541 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,12-01 21:54:06.943  5702  5702 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,12-01 21:54:06.943  5605  5620 D BluetoothMap: onBluetoothStateChange: up=true
12-01 21:54:06.944  3152  3152 D BluetoothPan: BluetoothPAN Proxy object connected
12-01 21:54:06.944  3152  3152 D PanProfile: Bluetooth service connected
12-01 21:54:06.944  5605  5619 D BluetoothInputDevice: onBluetoothStateChange: up=true
12-01 21:54:06.944  3152  3165 D BluetoothA2dp: onBluetoothStateChange: up=true
12-01 21:54:06.945  5702  5702 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,12-01 21:54:06.946  3152  3167 D BluetoothPbap: onBluetoothStateChange: up=true
12-01 21:54:06.946  5702  5702 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
12-01 21:54:06.946  3152  3152 D BluetoothA2dp: Proxy object connected
12-01 21:54:06.947  5702  5702 D ObexServerSockets: Succeed to create listening sockets 
12-01 21:54:06.947  5702  5702 D ObexServerSockets0: startAccept()
12-01 21:54:06.948  5702  5702 D ObexServerSockets0: prepareForNewConnect()
,12-01 21:54:06.948  5605  5620 D BluetoothPbap: onBluetoothStateChange: up=true
12-01 21:54:06.950  5702  5702 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
12-01 21:54:06.950  5702  5702 D BluetoothSdpJni: SDP Create record success - handle: 0
12-01 21:54:06.950  5702  5740 D ObexServerSockets0: Accepting socket connection...
12-01 21:54:06.950   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,12-01 21:54:06.951  5702  5741 D ObexServerSockets0: Accepting socket connection...
12-01 21:54:06.951  5702  5702 D BluetoothMapService: onReceive
12-01 21:54:06.951  5702  5702 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
12-01 21:54:06.951  5702  5702 D BluetoothMapService: STATE_ON
,12-01 21:54:06.952  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
12-01 21:54:06.953  5702  5742 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
12-01 21:54:06.953  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 21:54:06.954  5605  5605 D LocalBluetoothProfileManager: Adding local A2DP profile
12-01 21:54:06.954  5702  5742 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,12-01 21:54:06.955  5702  5742 D BluetoothSdpJni: SDP Create record success - handle: 1
12-01 21:54:06.958  5605  5605 D LocalBluetoothProfileManager: Adding local HEADSET profile
,12-01 21:54:06.963  5605  5605 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,12-01 21:54:06.965  5605  5605 D BluetoothA2dp: Proxy object connected
,12-01 21:54:06.968  3591  3591 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
12-01 21:54:06.970  5605  5605 D DockEventReceiver: finishStartingService: stopping service
,12-01 21:54:06.975  5605  5605 D BluetoothPbap: Proxy object connected
12-01 21:54:06.975  5702  5702 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
12-01 21:54:06.976  5605  5605 D PbapServerProfile: Bluetooth service connected
12-01 21:54:06.976  5702  5702 D ObexServerSockets0: prepareForNewConnect()
,12-01 21:54:06.980  3152  3152 D BluetoothPbap: Proxy object connected
,12-01 21:54:06.980  3152  3152 D PbapServerProfile: Bluetooth service connected
,12-01 21:54:06.984  5702  5746 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,12-01 21:54:06.996  5702  5750 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,12-01 21:54:06.998  5702  5750 I BtOppRfcommListener: Accept thread started.
,12-01 21:54:07.034   928   928 D BluetoothHeadset: Proxy object connected
,12-01 21:54:07.034   928   928 D BluetoothHeadset: Proxy object connected
12-01 21:54:07.035  3768  3789 D BluetoothHeadset: Proxy object connected
12-01 21:54:07.035   928   928 D BluetoothHeadset: Proxy object connected
12-01 21:54:07.035  3152  3997 D BluetoothHeadset: Proxy object connected
12-01 21:54:07.035  3152  3152 D HeadsetProfile: Bluetooth service connected
,12-01 21:54:07.043   928   945 D BluetoothHeadset: Proxy object connected
,12-01 21:54:07.059  5605  5620 D BluetoothHeadset: Proxy object connected
12-01 21:54:07.060  5605  5605 D HeadsetProfile: Bluetooth service connected
,12-01 21:54:08.722   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:54:08.769   928  2961 D ConnectivityService: handlePromptUnvalidated 101
,12-01 21:54:09.264  3672  3846 I Keyboard.Facilitator.LanguageModelFlusher: run()
,12-01 21:54:09.265  3672  3846 I Keyboard.Facilitator: flushDynamicLanguageModels()
,12-01 21:54:09.293  3591  3591 I ConfigService: onCreate
,12-01 21:54:09.723   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:54:10.724   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:54:10.896  5702  5714 D BluetoothAdapterState: Current state: ON, message: 23
12-01 21:54:10.896  5702  5714 D BluetoothAdapterProperties: Setting state to 13
12-01 21:54:10.896  5702  5714 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,12-01 21:54:10.898  5702  5714 D BluetoothAdapterProperties: onBluetoothDisable()
12-01 21:54:10.900  5702  5714 I BluetoothAdapterState: Entering PendingCommandState
,12-01 21:54:10.902  5702  5718 D BluetoothAdapterProperties: Scan Mode:20
,12-01 21:54:10.903  5702  5714 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
12-01 21:54:10.907  5702  5702 D BluetoothMapService: onReceive
,12-01 21:54:10.907  5702  5702 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
12-01 21:54:10.907  5702  5702 D BluetoothMapService: STATE_TURNING_OFF
12-01 21:54:10.907  5702  5702 D BluetoothMapService: MAP Service closeService in
12-01 21:54:10.908  5702  5702 D BluetoothMapMasInstance0: MAP Service shutdown
12-01 21:54:10.908  5702  5702 D ObexServerSockets0: shutdown(block = true)
12-01 21:54:10.908  5702  5702 D ObexServerSockets0: shutdown called from another thread - interrupt().
12-01 21:54:10.909  5702  5702 D ObexServerSockets0: shutdown called from another thread - interrupt().
12-01 21:54:10.909  5702  5740 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,12-01 21:54:10.909  5702  5741 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
12-01 21:54:10.909  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 21:54:10.909  5605  5605 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,12-01 21:54:10.909  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
12-01 21:54:10.909  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 21:54:10.909  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 21:54:10.909  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
12-01 21:54:10.909  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
12-01 21:54:10.909  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
12-01 21:54:10.909  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
12-01 21:54:10.909  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
12-01 21:54:10.909  5541  5541 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
12-01 21:54:10.911  5702  5727 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
12-01 21:54:10.911  5541  5541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
12-01 21:54:10.911  5541  5541 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,12-01 21:54:10.915  5702  5702 I BtOppRfcommListener: stopping Accept Thread
12-01 21:54:10.916  5702  5750 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
12-01 21:54:10.916  5702  5750 I BtOppRfcommListener: BluetoothSocket listen thread finished
12-01 21:54:10.916  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 21:54:10.917  5605  5605 D DockEventReceiver: finishStartingService: stopping service
12-01 21:54:10.918  5702  5702 D HeadsetService: Received stop request...Stopping profile...
,12-01 21:54:10.921   928   928 D BluetoothHeadset: Proxy object disconnected
,12-01 21:54:10.921   928   928 D BluetoothHeadset: Proxy object disconnected
12-01 21:54:10.921  5605  5620 D BluetoothHeadset: Proxy object disconnected
12-01 21:54:10.921  3768  3792 D BluetoothHeadset: Proxy object disconnected
12-01 21:54:10.922   928   928 D BluetoothHeadset: Proxy object disconnected
,12-01 21:54:10.922  3152  3165 D BluetoothHeadset: Proxy object disconnected
,12-01 21:54:10.923  5605  5605 D HeadsetProfile: Bluetooth service disconnected
12-01 21:54:10.923  5702  5702 D A2dpService: Received stop request...Stopping profile...
12-01 21:54:10.923  5702  5733 D A2dpStateMachine: Exit Disconnected: -1
12-01 21:54:10.924   928   928 D BluetoothA2dp: Proxy object disconnected
12-01 21:54:10.925  5605  5605 D BluetoothA2dp: Proxy object disconnected
12-01 21:54:10.925  5702  5702 D HidService: Received stop request...Stopping profile...
,12-01 21:54:10.925  5702  5702 D HidService: Stopping Bluetooth HidService
,12-01 21:54:10.926  5605  5605 D BluetoothInputDevice: Proxy object disconnected
12-01 21:54:10.926  5605  5605 D HidProfile: Bluetooth service disconnected
,12-01 21:54:10.927  5702  5702 D HealthService: Received stop request...Stopping profile...
,12-01 21:54:10.930  3591  3591 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
12-01 21:54:10.931  5702  5702 D PanService: Received stop request...Stopping profile...
,12-01 21:54:10.932  5605  5605 D BluetoothPan: BluetoothPAN Proxy object disconnected
,12-01 21:54:10.932  5605  5605 D PanProfile: Bluetooth service disconnected
12-01 21:54:10.932  5702  5702 V BluetoothAdapterState: isTurningOff()=true
12-01 21:54:10.932  5702  5702 V BluetoothAdapterState: isTurningOn()=false
12-01 21:54:10.932  5702  5702 V BluetoothAdapterState: isBleTurningOn()=false
12-01 21:54:10.932  5702  5702 V BluetoothAdapterState: isBleTurningOff()=false
,12-01 21:54:10.932  5702  5702 D BluetoothMapService: Received stop request...Stopping profile...
,12-01 21:54:10.933  5702  5702 D BluetoothMapService: stop()
12-01 21:54:10.933  5702  5702 D BluetoothMapAppObserver: deinitObservers()
12-01 21:54:10.933  5702  5702 D BluetoothMapAppObserver: removeReceiver()
12-01 21:54:10.934  3152  3152 D HeadsetProfile: Bluetooth service disconnected
12-01 21:54:10.934  3152  3152 D BluetoothA2dp: Proxy object disconnected
12-01 21:54:10.934  3152  3152 D BluetoothInputDevice: Proxy object disconnected
12-01 21:54:10.934  3152  3152 D HidProfile: Bluetooth service disconnected
,12-01 21:54:10.934  3152  3152 D BluetoothPan: BluetoothPAN Proxy object disconnected
12-01 21:54:10.935  3152  3152 D PanProfile: Bluetooth service disconnected
,12-01 21:54:10.936  5702  5702 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
12-01 21:54:10.937  5702  5702 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
12-01 21:54:10.937  5702  5725 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,12-01 21:54:10.937  5702  5725 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
12-01 21:54:10.937  5702  5725 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
12-01 21:54:10.937  5702  5718 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
12-01 21:54:10.937  5702  5718 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
12-01 21:54:10.937  5702  5702 D SapService: Received stop request...Stopping profile...
,12-01 21:54:10.938  5702  5702 V SapService: stop()
,12-01 21:54:10.938  3152  3152 D BluetoothMap: Proxy object disconnected
,12-01 21:54:10.938  3152  3152 D MapProfile: Bluetooth service disconnected
,12-01 21:54:10.938  5605  5605 D BluetoothMap: Proxy object disconnected
12-01 21:54:10.938  5605  5605 D MapProfile: Bluetooth service disconnected
12-01 21:54:10.939  5702  5702 V BluetoothAdapterState: isTurningOff()=true
12-01 21:54:10.939  5702  5702 V BluetoothAdapterState: isTurningOn()=false
12-01 21:54:10.939  5702  5702 V BluetoothAdapterState: isBleTurningOn()=false
12-01 21:54:10.939  5702  5702 V BluetoothAdapterState: isBleTurningOff()=false
12-01 21:54:10.940  5702  5718 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,12-01 21:54:10.940  5702  5725 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
12-01 21:54:10.940  5702  5702 V BluetoothAdapterState: isTurningOff()=true
,12-01 21:54:10.940  5702  5725 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
12-01 21:54:10.941  5702  5702 V BluetoothAdapterState: isTurningOn()=false
12-01 21:54:10.941  5702  5702 V BluetoothAdapterState: isBleTurningOn()=false
12-01 21:54:10.941  5702  5702 V BluetoothAdapterState: isBleTurningOff()=false
12-01 21:54:10.941  5702  5725 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
12-01 21:54:10.941  5702  5725 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,12-01 21:54:10.941  5702  5725 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
12-01 21:54:10.941  5702  5725 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
12-01 21:54:10.941  5702  5702 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
12-01 21:54:10.941  5702  5702 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
12-01 21:54:10.941  5702  5702 V BluetoothAdapterState: isTurningOff()=true
,12-01 21:54:10.941  5702  5702 V BluetoothAdapterState: isTurningOn()=false
12-01 21:54:10.941  5702  5702 V BluetoothAdapterState: isBleTurningOn()=false
12-01 21:54:10.941  5702  5702 V BluetoothAdapterState: isBleTurningOff()=false
12-01 21:54:10.941  5702  5702 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
12-01 21:54:10.941  5702  5718 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
12-01 21:54:10.942  5702  5718 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
12-01 21:54:10.942  5702  5702 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
12-01 21:54:10.944  3152  3152 D BluetoothPbap: Proxy object disconnected
12-01 21:54:10.944  3152  3152 D PbapServerProfile: Bluetooth service disconnected
12-01 21:54:10.944  5702  5702 V BluetoothAdapterState: isTurningOff()=true
12-01 21:54:10.944  5702  5702 V BluetoothAdapterState: isTurningOn()=false
12-01 21:54:10.944  5702  5702 V BluetoothAdapterState: isBleTurningOn()=false
,12-01 21:54:10.944  5702  5702 V BluetoothAdapterState: isBleTurningOff()=false
12-01 21:54:10.944  5605  5605 D BluetoothPbap: Proxy object disconnected
12-01 21:54:10.945  5605  5605 D PbapServerProfile: Bluetooth service disconnected
,12-01 21:54:10.945  5702  5702 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
12-01 21:54:10.945  5702  5702 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
12-01 21:54:10.946  5702  5702 D BluetoothMapService: MAP Service closeService in
12-01 21:54:10.946  5702  5702 V BluetoothAdapterState: isTurningOff()=true
12-01 21:54:10.946  5702  5702 V BluetoothAdapterState: isTurningOn()=false
12-01 21:54:10.946  5702  5702 V BluetoothAdapterState: isBleTurningOn()=false
12-01 21:54:10.946  5702  5702 V BluetoothAdapterState: isBleTurningOff()=false
12-01 21:54:10.946  5702  5702 D BluetoothMapService: cleanup()
12-01 21:54:10.946  5702  5702 D BluetoothMapService: MAP Service closeService in
12-01 21:54:10.947  5702  5702 V BluetoothAdapterState: isTurningOff()=true
12-01 21:54:10.947  5702  5702 V BluetoothAdapterState: isTurningOn()=false
12-01 21:54:10.947  5702  5702 V BluetoothAdapterState: isBleTurningOn()=false
12-01 21:54:10.947  5702  5702 V BluetoothAdapterState: isBleTurningOff()=false
12-01 21:54:10.947  5702  5714 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
12-01 21:54:10.947  5702  5714 D BluetoothAdapterProperties: Setting state to 15
12-01 21:54:10.947  5702  5714 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
12-01 21:54:10.948  5702  5714 I BluetoothAdapterState: Entering BleOnState
12-01 21:54:10.948   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
12-01 21:54:10.948  3152  3165 D BluetoothHeadset: onBluetoothStateChange: up=false
12-01 21:54:10.948   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
12-01 21:54:10.948   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,12-01 21:54:10.949  3768  3999 D BluetoothHeadset: onBluetoothStateChange: up=false
,12-01 21:54:10.949  3152  3996 D BluetoothInputDevice: onBluetoothStateChange: up=false
12-01 21:54:10.950  3152  3997 D BluetoothMap: onBluetoothStateChange: up=false
12-01 21:54:10.950  5605  5619 D BluetoothPan: onBluetoothStateChange on: false
12-01 21:54:10.951  3152  3167 D BluetoothPan: onBluetoothStateChange on: false
12-01 21:54:10.952  5605  5620 D BluetoothA2dp: onBluetoothStateChange: up=false
12-01 21:54:10.952   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,12-01 21:54:10.952  5605  5619 D BluetoothMap: onBluetoothStateChange: up=false
12-01 21:54:10.953  5605  5620 D BluetoothInputDevice: onBluetoothStateChange: up=false
12-01 21:54:10.953  3152  3165 D BluetoothA2dp: onBluetoothStateChange: up=false
12-01 21:54:10.954  3152  3996 D BluetoothPbap: onBluetoothStateChange: up=false
12-01 21:54:10.954  5605  5619 D BluetoothPbap: onBluetoothStateChange: up=false
12-01 21:54:10.955  5605  5620 D BluetoothHeadset: onBluetoothStateChange: up=false
12-01 21:54:10.955  5702  5714 D BluetoothAdapterState: Current state: BLE ON, message: 20
12-01 21:54:10.955  5702  5714 D BluetoothAdapterProperties: Setting state to 16
,12-01 21:54:10.955  5702  5714 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
12-01 21:54:10.956  5702  5714 D BluetoothAdapterProperties: onBleDisable
12-01 21:54:10.956  5702  5714 I BluetoothAdapterState: Entering PendingCommandState
12-01 21:54:10.957  5702  5715 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
12-01 21:54:10.958  5702  5718 D BluetoothAdapterProperties: Scan Mode:20
12-01 21:54:10.959  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
12-01 21:54:10.960  5605  5605 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
12-01 21:54:10.961  5702  5725 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
12-01 21:54:10.961  5702  5725 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
12-01 21:54:10.963  5541  5541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 21:54:10.968  5605  5605 D DockEventReceiver: finishStartingService: stopping service
,12-01 21:54:10.973  3591  3591 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,12-01 21:54:11.172  5702  5718 I bt_hci  : shut_down
,12-01 21:54:11.183  5702  5722 D bt_hwcfg: hw_epilog_process
,12-01 21:54:11.183  5702  5722 I bt_vendor: low_power_mode_cb
,12-01 21:54:11.187  5702  5722 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,12-01 21:54:11.187  5702  5722 I bt_vendor: epilog_cb
12-01 21:54:11.187  5702  5722 I bt_hci  : epilog_finished_callback
,12-01 21:54:11.193  5702  5718 I bt_hci_h4: hal_close
,12-01 21:54:11.194  5702  5718 I bt_userial_vendor: device fd = 54 close
,12-01 21:54:11.312  5702  5715 D bt_stack_manager: event_shut_down_stack finished.
12-01 21:54:11.312  5702  5714 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,12-01 21:54:11.317  5702  5702 D BtGatt.DebugUtils: handleDebugAction() action=null
12-01 21:54:11.318  5702  5714 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
12-01 21:54:11.318  5702  5702 D BtGatt.GattService: Received stop request...Stopping profile...
,12-01 21:54:11.318  5702  5702 D BtGatt.GattService: stop()
12-01 21:54:11.319  5702  5702 D BtGatt.AdvertiseManager: advertise clients cleared
,12-01 21:54:11.323  5702  5702 V BluetoothAdapterState: isTurningOff()=false
,12-01 21:54:11.323  5702  5702 V BluetoothAdapterState: isTurningOn()=false
,12-01 21:54:11.323  5702  5702 V BluetoothAdapterState: isBleTurningOn()=false
12-01 21:54:11.323  5702  5702 V BluetoothAdapterState: isBleTurningOff()=true
,12-01 21:54:11.324  5702  5714 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
12-01 21:54:11.324  5702  5714 D BluetoothAdapterProperties: Setting state to 10
12-01 21:54:11.325  5702  5714 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
12-01 21:54:11.326  5702  5714 I BluetoothAdapterState: Entering OffState
,12-01 21:54:11.327   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,12-01 21:54:11.347  5702  5702 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,12-01 21:54:11.347  5702  5702 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,12-01 21:54:11.348  5702  5715 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,12-01 21:54:11.350  5702  5702 I BluetoothServiceJni: cleanupNative: return from cleanup
,12-01 21:54:11.356  5702  5702 I art     : System.exit called, status: 0
,12-01 21:54:11.357  5702  5702 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,12-01 21:54:11.380   928   938 I ActivityManager: Process com.android.bluetooth (pid 5702) has died
,12-01 21:54:11.725   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:54:12.726   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:54:13.726   533   533 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,12-01 21:54:14.326  3591  3591 I ConfigService: onDestroy
,12-01 21:54:15.893  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
,12-01 21:54:15.894  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,12-01 21:54:15.900  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 21:54:15.900  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@75a1ab7 removed from the list
12-01 21:54:15.900  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
,12-01 21:54:15.902  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 21:54:15.902  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b26f42 added. We now have 4 listener(s)
,12-01 21:54:15.902  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,12-01 21:54:15.905  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 21:54:15.907  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b26f42 removed from the list
,12-01 21:54:15.907  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
,12-01 21:54:15.909  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 21:54:15.909  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8ebab53 added. We now have 4 listener(s)
,12-01 21:54:15.909  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,12-01 21:54:20.920  5541  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 21:54:20.956   928   945 I ActivityManager: Start proc 5759:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,12-01 21:54:21.042  5759  5759 D AdapterServiceConfig: Adding HeadsetService
,12-01 21:54:21.042  5759  5759 D AdapterServiceConfig: Adding A2dpService
12-01 21:54:21.042  5759  5759 D AdapterServiceConfig: Adding HidService
,12-01 21:54:21.043  5759  5759 D AdapterServiceConfig: Adding HealthService
12-01 21:54:21.043  5759  5759 D AdapterServiceConfig: Adding PanService
,12-01 21:54:21.043  5759  5759 D AdapterServiceConfig: Adding GattService
12-01 21:54:21.043  5759  5759 D AdapterServiceConfig: Adding BluetoothMapService
12-01 21:54:21.043  5759  5759 D AdapterServiceConfig: Adding SapService
,12-01 21:54:21.053   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e2f8d21:true
,12-01 21:54:21.054  5759  5759 D BluetoothAdapterState: make() - Creating AdapterState
,12-01 21:54:21.057  5759  5759 I bt_bluedroid: init
,12-01 21:54:21.057  5759  5771 I BluetoothAdapterState: Entering OffState
,12-01 21:54:21.059  5759  5772 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
12-01 21:54:21.059  5759  5772 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
12-01 21:54:21.059  5759  5772 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
12-01 21:54:21.059  5759  5772 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,12-01 21:54:21.060  5759  5759 I bt_bluedroid: get_profile_interface socket
,12-01 21:54:21.062  5759  5775 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
12-01 21:54:21.062  5759  5759 I bt_bluedroid: get_profile_interface sdp
12-01 21:54:21.064  5759  5775 D BluetoothAdapterProperties: Name is: Nexus 6P
,12-01 21:54:21.067  5759  5770 I bt_bluedroid: config_hci_snoop_log
12-01 21:54:21.068   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,12-01 21:54:21.072  5759  5771 D BluetoothAdapterState: Current state: OFF, message: 0
,12-01 21:54:21.072  5759  5771 D BluetoothAdapterProperties: Setting state to 14
12-01 21:54:21.072  5759  5771 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,12-01 21:54:21.074  5759  5771 D BluetoothBondStateMachine: make
,12-01 21:54:21.076  5759  5776 I BluetoothBondStateMachine: StableState(): Entering Off State
,12-01 21:54:21.078  5759  5771 I BluetoothAdapterState: Entering PendingCommandState
,12-01 21:54:21.080  5759  5759 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,12-01 21:54:21.082  5759  5759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a585778
12-01 21:54:21.082  5759  5759 D BtGatt.DebugUtils: handleDebugAction() action=null
,12-01 21:54:21.083  5759  5759 D BtGatt.GattService: Received start request. Starting profile...
12-01 21:54:21.083  5759  5759 D BtGatt.GattService: start()
,12-01 21:54:21.083  5759  5759 I bt_bluedroid: get_profile_interface gatt
,12-01 21:54:21.084  5759  5759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a585778
,12-01 21:54:21.084  5759  5759 D BtGatt.AdvertiseManager: advertise manager created
,12-01 21:54:21.091  5759  5759 V BluetoothAdapterState: isTurningOff()=false
12-01 21:54:21.091  5759  5759 V BluetoothAdapterState: isTurningOn()=false
12-01 21:54:21.091  5759  5759 V BluetoothAdapterState: isBleTurningOn()=true
12-01 21:54:21.091  5759  5759 V BluetoothAdapterState: isBleTurningOff()=false
,12-01 21:54:21.091  5759  5771 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,12-01 21:54:21.092  5759  5771 I bt_bluedroid: bt_bluedroid
12-01 21:54:21.093  5759  5772 D bt_stack_manager: event_start_up_stack is bringing up the stack.
12-01 21:54:21.093  5759  5772 I bt_hci  : start_up
,12-01 21:54:21.099  5759  5772 I bt_vendor: alloc value 0xf4239871
12-01 21:54:21.100  5759  5772 I bt_vendor: init
12-01 21:54:21.100  5759  5772 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
12-01 21:54:21.100  5759  5772 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,12-01 21:54:21.211  5759  5772 D bt_hci  : start_up starting async portion
12-01 21:54:21.212  5759  5779 I bt_hci  : event_finish_startup
12-01 21:54:21.212  5759  5779 I bt_hci_h4: hal_open
12-01 21:54:21.212  5759  5779 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,12-01 21:54:21.212  5780  5780 W irq/448-msm_hs_: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,12-01 21:54:21.217  5759  5779 I bt_userial_vendor: device fd = 54 open
,12-01 21:54:21.233  5759  5779 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,12-01 21:54:21.237  5759  5779 D bt_hwcfg: Chipset BCM4358A3
,12-01 21:54:21.237  5759  5779 D bt_hwcfg: Target name = [BCM4358A3]
,12-01 21:54:21.238  5759  5779 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,12-01 21:54:21.764  5759  5779 I bt_hwcfg: bt vendor lib: set UART baud 115200
,12-01 21:54:21.764  5759  5779 D bt_hwcfg: Settlement delay -- 100 ms
,12-01 21:54:21.765  5759  5779 I bt_hwcfg: Setting fw settlement delay to 100 
,12-01 21:54:21.898  5759  5779 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,12-01 21:54:21.898  5759  5779 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,12-01 21:54:21.900  5759  5779 I bt_hwcfg: vendor lib fwcfg completed
,12-01 21:54:21.901  5759  5779 I bt_vendor: firmware callback
,12-01 21:54:21.901  5759  5779 I bt_hci  : firmware_config_callback
,12-01 21:54:21.910  5759  5782 I bt_btu  : btu_task pending for preload complete event
,12-01 21:54:21.910  5759  5782 I bt_btu_task: Bluetooth chip preload is complete
12-01 21:54:21.910  5759  5782 I bt_btu  : btu_task received preload complete event
,12-01 21:54:21.916  5759  5782 I         : BTE_InitTraceLevels -- TRC_HCI
,12-01 21:54:21.916  5759  5782 I         : BTE_InitTraceLevels -- TRC_L2CAP
12-01 21:54:21.917  5759  5782 I         : BTE_InitTraceLevels -- TRC_RFCOMM
12-01 21:54:21.917  5759  5782 I         : BTE_InitTraceLevels -- TRC_AVDT
,12-01 21:54:21.917  5759  5782 I         : BTE_InitTraceLevels -- TRC_AVRC
12-01 21:54:21.917  5759  5782 I         : BTE_InitTraceLevels -- TRC_A2D
12-01 21:54:21.917  5759  5782 I         : BTE_InitTraceLevels -- TRC_BNEP
,12-01 21:54:21.917  5759  5782 I         : BTE_InitTraceLevels -- TRC_BTM
12-01 21:54:21.918  5759  5782 I         : BTE_InitTraceLevels -- TRC_GAP
,12-01 21:54:21.918  5759  5782 I         : BTE_InitTraceLevels -- TRC_PAN
,12-01 21:54:21.918  5759  5782 I         : BTE_InitTraceLevels -- TRC_SDP
,12-01 21:54:21.918  5759  5782 I         : BTE_InitTraceLevels -- TRC_GATT
12-01 21:54:21.918  5759  5782 I         : BTE_InitTraceLevels -- TRC_SMP
12-01 21:54:21.918  5759  5782 I         : BTE_InitTraceLevels -- TRC_BTAPP
12-01 21:54:21.918  5759  5782 I         : BTE_InitTraceLevels -- TRC_BTIF
,12-01 21:54:22.014  5759  5782 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf41b7549
,12-01 21:54:22.014  5759  5782 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf41b7549 
,12-01 21:54:22.039  5759  5775 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,12-01 21:54:22.042  5759  5775 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
12-01 21:54:22.043  5759  5775 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,12-01 21:54:22.045  5759  5775 D BluetoothAdapterProperties: Name is: Nexus 6P
,12-01 21:54:22.048  5759  5775 D BluetoothAdapterProperties: Scan Mode:20
12-01 21:54:22.048  5759  5775 D BluetoothAdapterProperties: Discoverable Timeout:120
12-01 21:54:22.048  5759  5775 D bt_hci  : do_postload posting postload work item
12-01 21:54:22.048  5759  5779 I bt_hci  : event_postload
,12-01 21:54:22.049  5759  5779 I bt_vendor: sco_config_cb
12-01 21:54:22.049  5759  5779 I bt_hci  : sco_config_callback postload finished.
,12-01 21:54:22.053  5759  5775 D bt_bte_conf: Device ID record 1 : primary
,12-01 21:54:22.053  5759  5775 D bt_bte_conf:   vendorId            = 000f
12-01 21:54:22.053  5759  5775 D bt_bte_conf:   vendorIdSource      = 0001
12-01 21:54:22.053  5759  5775 D bt_bte_conf:   product             = 1200
12-01 21:54:22.053  5759  5775 D bt_bte_conf:   version             = 1436
12-01 21:54:22.053  5759  5775 D bt_bte_conf:   clientExecutableURL = 
12-01 21:54:22.053  5759  5775 D bt_bte_conf:   serviceDescription  = 
12-01 21:54:22.053  5759  5775 D bt_bte_conf:   documentationURL    = 
,12-01 21:54:22.053  5759  5775 D bt_bte_conf: bte_load_did_conf no section named DID2.
12-01 21:54:22.053  5759  5772 D bt_stack_manager: event_start_up_stack finished
12-01 21:54:22.054  5759  5771 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
12-01 21:54:22.055  5759  5771 D BluetoothAdapterProperties: Setting state to 15
12-01 21:54:22.055  5759  5771 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
12-01 21:54:22.056  5759  5771 I BluetoothAdapterState: Entering BleOnState
,12-01 21:54:22.059  5759  5779 I bt_vendor: low_power_mode_cb
,12-01 21:54:22.062  5759  5771 D BluetoothAdapterState: Current state: BLE ON, message: 1
,12-01 21:54:22.062  5759  5771 D BluetoothAdapterProperties: Setting state to 11
12-01 21:54:22.062  5759  5771 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,12-01 21:54:22.067  5759  5759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a585778
,12-01 21:54:22.070  5759  5759 D HeadsetService: Received start request. Starting profile...
,12-01 21:54:22.073  5759  5759 I BluetoothHeadsetServiceJni: classInitNative: succeeds
12-01 21:54:22.074  5759  5759 D HeadsetStateMachine: make
,12-01 21:54:22.083  5759  5771 I BluetoothAdapterState: Entering PendingCommandState
,12-01 21:54:22.087  5759  5759 D HeadsetStateMachine: max_hf_connections = 1
,12-01 21:54:22.087  5759  5759 I bt_bluedroid: get_profile_interface handsfree
12-01 21:54:22.087  5759  5775 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,12-01 21:54:22.089  5759  5775 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,12-01 21:54:22.091  5759  5759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a585778
,12-01 21:54:22.092  5759  5759 D A2dpService: Received start request. Starting profile...
12-01 21:54:22.093  5759  5759 I BluetoothAvrcpServiceJni: classInitNative: succeeds
12-01 21:54:22.093  5759  5759 I bt_bluedroid: get_profile_interface avrcp
,12-01 21:54:22.100  5759  5759 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,12-01 21:54:22.100  5759  5759 I BluetoothA2dpServiceJni: classInitNative: succeeds
12-01 21:54:22.100  5759  5759 D A2dpStateMachine: make
12-01 21:54:22.101  5759  5759 I bt_bluedroid: get_profile_interface a2dp
,12-01 21:54:22.102  5759  5775 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,12-01 21:54:22.105  5759  5789 D A2dpStateMachine: Enter Disconnected: -2
,12-01 21:54:22.105  5759  5759 I BluetoothHidServiceJni: classInitNative: succeeds
,12-01 21:54:22.106  5759  5759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a585778
12-01 21:54:22.106  5759  5759 D HidService: Received start request. Starting profile...
12-01 21:54:22.107  5759  5759 I bt_bluedroid: get_profile_interface hidhost
12-01 21:54:22.107  5759  5759 D HidService: setHidService(): set to: null
12-01 21:54:22.107  5759  5775 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf419856d
12-01 21:54:22.107  5759  5775 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
12-01 21:54:22.109  5759  5759 I BluetoothHealthServiceJni: classInitNative: succeeds
12-01 21:54:22.110  5759  5759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a585778
12-01 21:54:22.110  3591  3591 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,12-01 21:54:22.110  5759  5759 D HealthService: Received start request. Starting profile...
12-01 21:54:22.112  5759  5759 I bt_bluedroid: get_profile_interface health
,12-01 21:54:22.113  5759  5759 I BluetoothPanServiceJni: classInitNative(L105): succeeds
12-01 21:54:22.113  5759  5759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a585778
12-01 21:54:22.114  5759  5759 D PanService: Received start request. Starting profile...
,12-01 21:54:22.114  5759  5759 D BluetoothPanServiceJni: initializeNative(L110): pan
12-01 21:54:22.114  5759  5759 I bt_bluedroid: get_profile_interface pan
12-01 21:54:22.115  5759  5775 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
12-01 21:54:22.116  5759  5759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a585778
12-01 21:54:22.117  5759  5759 D BluetoothMapService: Received start request. Starting profile...
12-01 21:54:22.117  5759  5759 D BluetoothMapService: start()
,12-01 21:54:22.119  5759  5759 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,12-01 21:54:22.120  5759  5759 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
12-01 21:54:22.120  5759  5759 D BluetoothMapAppObserver: createReceiver()
,12-01 21:54:22.122  5759  5759 D BluetoothMapAppObserver: initObservers()
,12-01 21:54:22.122  5759  5759 D BluetoothMapAppObserver: getEnabledAccountItems()
,12-01 21:54:22.128  5759  5759 V SapService: SapBinder()
,12-01 21:54:22.128  5759  5759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a585778
12-01 21:54:22.129  5759  5759 D SapService: Received start request. Starting profile...
12-01 21:54:22.129  5759  5759 V SapService: start()
,12-01 21:54:22.131  5759  5759 V BluetoothAdapterState: isTurningOff()=false
,12-01 21:54:22.131  5759  5759 V BluetoothAdapterState: isTurningOn()=true
12-01 21:54:22.131  5759  5759 V BluetoothAdapterState: isBleTurningOn()=false
12-01 21:54:22.132  5759  5759 V BluetoothAdapterState: isBleTurningOff()=false
12-01 21:54:22.132  5759  5759 V BluetoothAdapterState: isTurningOff()=false
12-01 21:54:22.132  5759  5759 V BluetoothAdapterState: isTurningOn()=true
12-01 21:54:22.132  5759  5759 V BluetoothAdapterState: isBleTurningOn()=false
12-01 21:54:22.132  5759  5759 V BluetoothAdapterState: isBleTurningOff()=false
12-01 21:54:22.132  5759  5787 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
12-01 21:54:22.132  5759  5759 V BluetoothAdapterState: isTurningOff()=false
12-01 21:54:22.132  5759  5759 V BluetoothAdapterState: isTurningOn()=true
12-01 21:54:22.132  5759  5759 V BluetoothAdapterState: isBleTurningOn()=false
12-01 21:54:22.132  5759  5759 V BluetoothAdapterState: isBleTurningOff()=false
12-01 21:54:22.132  5759  5759 V BluetoothAdapterState: isTurningOff()=false
12-01 21:54:22.132  5759  5759 V BluetoothAdapterState: isTurningOn()=true
12-01 21:54:22.133  5759  5759 V BluetoothAdapterState: isBleTurningOn()=false
12-01 21:54:22.133  5759  5759 V BluetoothAdapterState: isBleTurningOff()=false
12-01 21:54:22.133  5759  5759 V BluetoothAdapterState: isTurningOff()=false
12-01 21:54:22.133  5759  5759 V BluetoothAdapterState: isTurningOn()=true
12-01 21:54:22.133  5759  5759 V BluetoothAdapterState: isBleTurningOn()=false
12-01 21:54:22.133  5759  5759 V BluetoothAdapterState: isBleTurningOff()=false
12-01 21:54:22.133  5759  5759 V BluetoothAdapterState: isTurningOff()=false
12-01 21:54:22.134  5759  5759 V BluetoothAdapterState: isTurningOn()=true
12-01 21:54:22.134  5759  5759 V BluetoothAdapterState: isBleTurningOn()=false
12-01 21:54:22.134  5759  5759 V BluetoothAdapterState: isBleTurningOff()=false
12-01 21:54:22.135  5759  5759 V BluetoothAdapterState: isTurningOff()=false
12-01 21:54:22.135  5759  5759 V BluetoothAdapterState: isTurningOn()=true
12-01 21:54:22.135  5759  5759 V BluetoothAdapterState: isBleTurningOn()=false
12-01 21:54:22.135  5759  5759 V BluetoothAdapterState: isBleTurningOff()=false
,12-01 21:54:22.136  5759  5771 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,12-01 21:54:22.136  5759  5771 D BluetoothAdapterProperties: ScanMode =  20
12-01 21:54:22.136  5759  5771 D BluetoothAdapterProperties: State =  11
12-01 21:54:22.136  5759  5771 D BluetoothAdapterProperties: Setting state to 12
12-01 21:54:22.136  5759  5771 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,12-01 21:54:22.137   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
12-01 21:54:22.137  5759  5771 I BluetoothAdapterState: Entering OnState
12-01 21:54:22.137  5759  5775 D BluetoothAdapterProperties: Scan Mode:21
12-01 21:54:22.137  5759  5775 D BluetoothAdapterProperties: Discoverable Timeout:120
,12-01 21:54:22.137  3152  3997 D BluetoothHeadset: onBluetoothStateChange: up=true
,12-01 21:54:22.138   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
12-01 21:54:22.138   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
12-01 21:54:22.138   928   928 D BluetoothA2dp: Proxy object connected
12-01 21:54:22.138  3768  3789 D BluetoothHeadset: onBluetoothStateChange: up=true
12-01 21:54:22.139  3152  3996 D BluetoothInputDevice: onBluetoothStateChange: up=true
12-01 21:54:22.141  3152  3167 D BluetoothMap: onBluetoothStateChange: up=true
12-01 21:54:22.142  3152  3152 D BluetoothInputDevice: Proxy object connected
12-01 21:54:22.142  3152  3152 D HidProfile: Bluetooth service connected
,12-01 21:54:22.142  5605  5619 D BluetoothPan: onBluetoothStateChange on: true
,12-01 21:54:22.144  3152  3152 D BluetoothMap: Proxy object connected
12-01 21:54:22.144  3152  3152 D MapProfile: Bluetooth service connected
12-01 21:54:22.144  3152  3152 D BluetoothMap: getConnectedDevices()
12-01 21:54:22.144  3152  3165 D BluetoothPan: onBluetoothStateChange on: true
12-01 21:54:22.146  3152  3152 D BluetoothPan: BluetoothPAN Proxy object connected
12-01 21:54:22.146  5605  5619 D BluetoothA2dp: onBluetoothStateChange: up=true
12-01 21:54:22.146  3152  3152 D PanProfile: Bluetooth service connected
12-01 21:54:22.147  5759  5759 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
12-01 21:54:22.147  5759  5759 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,12-01 21:54:22.148   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
12-01 21:54:22.148  5605  5620 D BluetoothMap: onBluetoothStateChange: up=true
12-01 21:54:22.149  5759  5759 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
12-01 21:54:22.149  5605  5620 D BluetoothInputDevice: onBluetoothStateChange: up=true
12-01 21:54:22.151  3152  3167 D BluetoothA2dp: onBluetoothStateChange: up=true
12-01 21:54:22.151  5759  5759 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,12-01 21:54:22.152  5759  5759 D ObexServerSockets: Succeed to create listening sockets 
12-01 21:54:22.152  5759  5759 D ObexServerSockets0: startAccept()
12-01 21:54:22.152  5759  5759 D ObexServerSockets0: prepareForNewConnect()
12-01 21:54:22.153  3152  3997 D BluetoothPbap: onBluetoothStateChange: up=true
,12-01 21:54:22.153  3152  3152 D BluetoothA2dp: Proxy object connected
12-01 21:54:22.153  5605  5605 D BluetoothPan: BluetoothPAN Proxy object connected
12-01 21:54:22.153  5605  5605 D PanProfile: Bluetooth service connected
12-01 21:54:22.153  5605  5605 D BluetoothA2dp: Proxy object connected
12-01 21:54:22.155  5759  5759 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
12-01 21:54:22.155  5759  5759 D BluetoothSdpJni: SDP Create record success - handle: 0
12-01 21:54:22.156  5759  5796 D ObexServerSockets0: Accepting socket connection...
12-01 21:54:22.156  5759  5797 D ObexServerSockets0: Accepting socket connection...
,12-01 21:54:22.158  5605  5605 D BluetoothMap: Proxy object connected
12-01 21:54:22.158  5605  5605 D MapProfile: Bluetooth service connected
12-01 21:54:22.158  5605  5605 D BluetoothMap: getConnectedDevices()
12-01 21:54:22.160  5605  5605 D BluetoothInputDevice: Proxy object connected
12-01 21:54:22.160  5605  5605 D HidProfile: Bluetooth service connected
,12-01 21:54:22.162  5605  5619 D BluetoothPbap: onBluetoothStateChange: up=true
12-01 21:54:22.163  5605  5620 D BluetoothHeadset: onBluetoothStateChange: up=true
,12-01 21:54:22.165   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,12-01 21:54:22.165  5759  5759 D BluetoothMapService: onReceive
12-01 21:54:22.166  5759  5759 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
12-01 21:54:22.166  5759  5759 D BluetoothMapService: STATE_ON
,12-01 21:54:22.169  5759  5799 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,12-01 21:54:22.170  5759  5799 D BluetoothSdpJni: sdpCreateSapsRecordNative:
12-01 21:54:22.170  5759  5799 D BluetoothSdpJni: SDP Create record success - handle: 1
,12-01 21:54:22.173  5605  5605 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,12-01 21:54:22.179  3591  3591 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,12-01 21:54:22.183  5605  5605 D DockEventReceiver: finishStartingService: stopping service
,12-01 21:54:22.187  3152  3152 D BluetoothPbap: Proxy object connected
12-01 21:54:22.187  3152  3152 D PbapServerProfile: Bluetooth service connected
,12-01 21:54:22.187  5605  5605 D BluetoothPbap: Proxy object connected
12-01 21:54:22.190  5605  5605 D PbapServerProfile: Bluetooth service connected
,12-01 21:54:22.193  5759  5759 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,12-01 21:54:22.193  5759  5759 D ObexServerSockets0: prepareForNewConnect()
,12-01 21:54:22.195  5759  5803 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,12-01 21:54:22.205  5759  5807 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,12-01 21:54:22.207  5759  5807 I BtOppRfcommListener: Accept thread started.
,12-01 21:54:22.240   928   928 D BluetoothHeadset: Proxy object connected
12-01 21:54:22.240   928   928 D BluetoothHeadset: Proxy object connected
,12-01 21:54:22.241  5605  5620 D BluetoothHeadset: Proxy object connected
,12-01 21:54:22.241  3768  3792 D BluetoothHeadset: Proxy object connected
12-01 21:54:22.241   928   928 D BluetoothHeadset: Proxy object connected
12-01 21:54:22.242  3152  3167 D BluetoothHeadset: Proxy object connected
12-01 21:54:22.242  3152  3152 D HeadsetProfile: Bluetooth service connected
12-01 21:54:22.244  5605  5605 D HeadsetProfile: Bluetooth service connected
,12-01 21:54:22.248   928   945 D BluetoothHeadset: Proxy object connected
,12-01 21:54:22.265  5605  5619 D BluetoothHeadset: Proxy object connected
,12-01 21:54:22.265  5605  5605 D HeadsetProfile: Bluetooth service connected
,12-01 21:54:23.728   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:54:24.729   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:54:25.730   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:54:25.938  5541  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
12-01 21:54:25.938  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 21:54:25.938  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 21:54:25.938  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
12-01 21:54:25.938  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
12-01 21:54:25.938  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
12-01 21:54:25.938  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
12-01 21:54:25.938  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
12-01 21:54:25.938  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,12-01 21:54:25.945  5541  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,12-01 21:54:25.946  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:54:25.946  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8ebab53 removed from the list
12-01 21:54:25.946  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
,12-01 21:54:25.950  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,12-01 21:54:25.950  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fbd6c90 added. We now have 4 listener(s)
12-01 21:54:25.950  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,12-01 21:54:25.955   928  3811 D WifiService: setWifiEnabled: false pid=5541, uid=10077
,12-01 21:54:25.956   928  3811 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,12-01 21:54:26.731   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:54:27.732   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:54:28.733   533   533 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,12-01 21:54:30.967  5541  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,12-01 21:54:30.969   928  3763 D WifiService: setWifiEnabled: true pid=5541, uid=10077
,12-01 21:54:30.969   928  3763 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,12-01 21:54:30.983   505   925 D SoftapController: Softap fwReload - Ok
,12-01 21:54:30.985   505   925 D CommandListener: Setting iface cfg
12-01 21:54:30.985   505   925 D CommandListener: Trying to bring down wlan0
,12-01 21:54:30.987   505   925 D CommandListener: Clearing all IP addresses on wlan0
,12-01 21:54:30.991   928  2959 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,12-01 21:54:31.656   928  2959 D wifi    : set interface wlan0 flags (UP)
12-01 21:54:31.658   928  2959 I WifiHAL : Initializing wifi
12-01 21:54:31.658   928  2959 I WifiHAL : Creating socket
,12-01 21:54:31.665   928  2959 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,12-01 21:54:31.665   928  2959 D wifi    : Did set static halHandle = 0x7f97239dc0
,12-01 21:54:31.666   928  2959 D wifi    : halHandle = 0x7f97239dc0, mVM = 0x7fb274d140, mCls = 0x20182a
,12-01 21:54:31.666   928  2959 D wifi    : array field set
,12-01 21:54:31.666   928  2959 I WifiNative-HAL: interface[0] = wlan0
,12-01 21:54:31.667   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,12-01 21:54:31.670   928  5812 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547996540352
12-01 21:54:31.670   928  5812 D wifi    : waitForHalEvents called, vm = 0x7fb274d140, obj = 0x20182a, env = 0x7f9b3e5a00
,12-01 21:54:31.738  5813  5813 I wpa_supplicant: Successfully initialized wpa_supplicant
,12-01 21:54:31.770   928  2959 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,12-01 21:54:31.816  5813  5813 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,12-01 21:54:31.864  5813  5813 I wpa_supplicant: rfkill: Cannot open RFKILL control device
12-01 21:54:31.864  5813  5813 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,12-01 21:54:31.888   928  2959 D WifiConfigStore: Loading config and enabling all networks 
,12-01 21:54:31.912   928  2959 D WifiConfigStore: loaded 0 passpoint configs
,12-01 21:54:31.913   928  2959 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
12-01 21:54:31.913   928  2959 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
12-01 21:54:31.913   928  2959 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,12-01 21:54:31.914   928  2959 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
12-01 21:54:31.914   928  2959 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,12-01 21:54:31.915   928  2959 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
12-01 21:54:31.915   928  2959 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
12-01 21:54:31.915   928  2959 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
12-01 21:54:31.915   928  2959 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
12-01 21:54:31.915   928  2959 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
12-01 21:54:31.915   928  2959 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
12-01 21:54:31.915   928  2959 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,12-01 21:54:31.918   928  2959 D WifiNative-HAL: Setting external_sim to 1
12-01 21:54:31.918   928  2959 D wifi    : setting dfs flag to true, 0x7f99d2d420
,12-01 21:54:31.918  4355  4355 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
12-01 21:54:31.918   928  2959 D WifiStateMachine: Setting OUI to DA-A1-19
12-01 21:54:31.918   928  2959 D wifi    : setting scan oui 0x7f99d2d420
12-01 21:54:31.918   928  2959 D WifiHAL : Sending mac address OUI
,12-01 21:54:31.922   928  2959 E native  : do suspend false
,12-01 21:54:31.938   928  2959 D wifi    : android_net_wifi_setLinkLayerStats: 1
12-01 21:54:31.939   928   928 D RttService: SCAN_AVAILABLE : 3
,12-01 21:54:31.939   928  3066 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,12-01 21:54:31.944   505   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,12-01 21:54:31.945   505   925 D CommandListener: Setting iface cfg
,12-01 21:54:31.956   928  2958 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '158 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 158 Failed to set address (No such device)'
12-01 21:54:31.956   928  2958 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,12-01 21:54:31.960   928  2958 D WifiNative-HAL: p2pGetDeviceAddress
12-01 21:54:31.961   928  2958 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,12-01 21:54:31.996   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=152935 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=51 mControllerEnergyUsed=193 }
,12-01 21:54:33.457  4054  4538 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,12-01 21:54:35.110  5813  5813 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,12-01 21:54:35.114  5813  5813 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,12-01 21:54:35.119  5813  5813 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,12-01 21:54:35.125  5813  5813 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,12-01 21:54:35.181   928  2959 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,12-01 21:54:35.182   928  2959 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,12-01 21:54:35.182   928  2959 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,12-01 21:54:35.197   928  2959 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,12-01 21:54:35.236   928  2959 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,12-01 21:54:35.244  5813  5813 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,12-01 21:54:35.684  5813  5813 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,12-01 21:54:35.721  5813  5813 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
12-01 21:54:35.722  5813  5813 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,12-01 21:54:35.731   928  2959 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
12-01 21:54:35.731   928  2959 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,12-01 21:54:35.731   928  2961 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,12-01 21:54:35.752   928  2959 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,12-01 21:54:35.768   505   925 D CommandListener: Setting iface cfg
,12-01 21:54:35.774   928  2959 D WifiStateMachine: Start Dhcp Watchdog 3
,12-01 21:54:35.784   928  5818 D DhcpClient: Receive thread started
,12-01 21:54:35.789   928  2961 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,12-01 21:54:35.789   928  2959 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
12-01 21:54:35.789   928  2961 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,12-01 21:54:35.879   928  2959 E native  : do suspend false
,12-01 21:54:35.898   928  5817 D DhcpClient: Broadcasting DHCPDISCOVER
,12-01 21:54:35.913   928  5818 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,12-01 21:54:35.914   928  5817 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,12-01 21:54:35.916   928  5817 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,12-01 21:54:35.931   928  5818 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,12-01 21:54:35.932   928  5817 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
12-01 21:54:35.935   505   925 D CommandListener: Setting iface cfg
,12-01 21:54:35.939   928  2959 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,12-01 21:54:35.944   928  5817 D DhcpClient: Scheduling renewal in 86399s
,12-01 21:54:35.955   928  2959 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,12-01 21:54:35.958   928  2959 D WifiConfigStore: No blacklist allowed without epno enabled
,12-01 21:54:35.959   928  2961 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,12-01 21:54:35.961   928  2961 D ConnectivityService: Adding iface wlan0 to network 102
,12-01 21:54:35.970   928  2959 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,12-01 21:54:35.987  5541  5587 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
12-01 21:54:35.987  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
12-01 21:54:35.987  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
12-01 21:54:35.987  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
12-01 21:54:35.987  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
12-01 21:54:35.987  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
12-01 21:54:35.987  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
12-01 21:54:35.987  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
12-01 21:54:35.987  5541  5587 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,12-01 21:54:35.993  5541  5587 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
12-01 21:54:35.993  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 21:54:35.993  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fbd6c90 removed from the list
12-01 21:54:35.993  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
,12-01 21:54:35.998  5541  5587 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
12-01 21:54:35.999  5541  5587 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,12-01 21:54:36.001  5541  5587 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@d4e1fb7 Bundle[{}]
,12-01 21:54:36.002  5541  5587 I io.jxcore.node.LifeCycleMonitor: start: OK
,12-01 21:54:36.002  5541  5587 I io.jxcore.node.LifeCycleMonitor: stop: OK
12-01 21:54:36.003  5541  5587 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
12-01 21:54:36.004  5541  5587 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
12-01 21:54:36.004  5541  5587 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
12-01 21:54:36.005  5541  5587 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,12-01 21:54:36.006   928  2961 E ConnectivityService: Unexpected mtu value: 0, wlan0
12-01 21:54:36.006   928  2961 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
12-01 21:54:36.008   928  2961 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
12-01 21:54:36.009   928  2961 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,12-01 21:54:36.012   928  2961 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,12-01 21:54:36.015  5541  5587 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 165)
12-01 21:54:36.016  5541  5587 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
12-01 21:54:36.016  5541  5587 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 166)
12-01 21:54:36.018  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
12-01 21:54:36.019  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21b4989 added. We now have 3 listener(s)
12-01 21:54:36.020  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
12-01 21:54:36.020  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 21:54:36.020  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 21:54:36.020  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 21:54:36.020  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc3d8e added. We now have 4 listener(s)
,12-01 21:54:36.020  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 21:54:36.021  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,12-01 21:54:36.022  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
12-01 21:54:36.023  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fba9af added. We now have 4 listener(s)
12-01 21:54:36.023   928  2961 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,12-01 21:54:36.024  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
12-01 21:54:36.024  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 21:54:36.024  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 21:54:36.024  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,12-01 21:54:36.024  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@634c1bc added. We now have 5 listener(s)
12-01 21:54:36.024  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 21:54:36.025  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 21:54:36.025  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 21:54:36.025  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 21:54:36.025  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:54:36.025  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,12-01 21:54:36.025  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
12-01 21:54:36.025  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21b4989 removed from the list
12-01 21:54:36.025  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:54:36.025  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc3d8e removed from the list
12-01 21:54:36.025  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
12-01 21:54:36.025  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.025  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:54:36.027   928  2961 D ConnectivityService: scheduleUnvalidatedPrompt 102
12-01 21:54:36.027   928  2961 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,12-01 21:54:36.027   928  2961 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,12-01 21:54:36.027  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.027   928  2961 D ConnectivityService:    accepting network in place of null
12-01 21:54:36.027   928  2959 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,12-01 21:54:36.027  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.027   928  2959 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
12-01 21:54:36.028  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.028  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 21:54:36.028  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 21:54:36.028  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 21:54:36.028  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc3d8e not in the list
12-01 21:54:36.028  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.028  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.029   928  2961 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
12-01 21:54:36.030  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.030  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.030  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.030  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,12-01 21:54:36.030  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 21:54:36.030  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:54:36.030  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@634c1bc removed from the list
12-01 21:54:36.030  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:54:36.030  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 21:54:36.030  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
12-01 21:54:36.031  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fba9af removed from the list
12-01 21:54:36.031  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
12-01 21:54:36.032  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae5f545 added. We now have 3 listener(s)
,12-01 21:54:36.033  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
12-01 21:54:36.033  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 21:54:36.033  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 21:54:36.033  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 21:54:36.034  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d02a49a added. We now have 4 listener(s)
,12-01 21:54:36.034  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 21:54:36.034  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,12-01 21:54:36.036  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,12-01 21:54:36.036  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16331cb added. We now have 4 listener(s)
,12-01 21:54:36.037  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
12-01 21:54:36.037  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 21:54:36.037  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,12-01 21:54:36.038  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 21:54:36.038  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6a3da8 added. We now have 5 listener(s)
12-01 21:54:36.038  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 21:54:36.038  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
12-01 21:54:36.038  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
12-01 21:54:36.038  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
12-01 21:54:36.038  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
12-01 21:54:36.038  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,12-01 21:54:36.040  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,12-01 21:54:36.042  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,12-01 21:54:36.042  5541  5587 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
12-01 21:54:36.042  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,12-01 21:54:36.044  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:54:36.044  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
12-01 21:54:36.045  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
12-01 21:54:36.045  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
12-01 21:54:36.045  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,12-01 21:54:36.047  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:54:36.047  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
12-01 21:54:36.047  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
12-01 21:54:36.047  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
12-01 21:54:36.047  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
12-01 21:54:36.047  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:54:36.047  5541  5587 D BluetoothAdapter: STATE_ON
,12-01 21:54:36.049  5759  5798 D BtGatt.GattService: registerClient() - UUID=d026e381-1880-4983-8551-ff6e103dd9f3
,12-01 21:54:36.049  5759  5775 D BtGatt.GattService: onClientRegistered() - UUID=d026e381-1880-4983-8551-ff6e103dd9f3, clientIf=5
,12-01 21:54:36.050  5541  5656 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
12-01 21:54:36.051  5759  5794 D BtGatt.GattService: start scan with filters
,12-01 21:54:36.051   505   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,12-01 21:54:36.054  5759  5778 D BtGatt.ScanManager: handling starting scan
12-01 21:54:36.054  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
12-01 21:54:36.054  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.054  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
12-01 21:54:36.054  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:54:36.054  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
12-01 21:54:36.055  5541  5541 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
12-01 21:54:36.055  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.055  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
12-01 21:54:36.055  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
12-01 21:54:36.055  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.055  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.055  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,12-01 21:54:36.055  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.055  5759  5778 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a585778
12-01 21:54:36.055  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
12-01 21:54:36.055  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.057  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.057  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
12-01 21:54:36.057  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.057  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.057  5541  5587 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,12-01 21:54:36.057  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.057  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,12-01 21:54:36.057  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
12-01 21:54:36.057  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 21:54:36.057  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 21:54:36.057  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 21:54:36.057  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
12-01 21:54:36.059  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.059  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.059  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.059  5541  5541 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
12-01 21:54:36.059  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
12-01 21:54:36.060  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.060  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,12-01 21:54:36.060  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
12-01 21:54:36.060  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.060  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.060  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.060  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
12-01 21:54:36.060  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.060  5541  5587 D BluetoothAdapter: STATE_ON
12-01 21:54:36.061  5759  5769 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
12-01 21:54:36.061  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
12-01 21:54:36.061  5541  5587 D BluetoothAdapter: STATE_ON
12-01 21:54:36.062  5759  5794 D BtGatt.GattService: stopScan() - queue size =1
,12-01 21:54:36.062  5759  5798 D BtGatt.GattService: unregisterClient() - clientIf=5
,12-01 21:54:36.062  5759  5775 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
12-01 21:54:36.062  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
12-01 21:54:36.062  5759  5775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:54:36.062  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.062  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
12-01 21:54:36.062  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.062  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.062  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.063  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.063  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
12-01 21:54:36.063  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.063  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.063  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.063  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
12-01 21:54:36.063  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
12-01 21:54:36.063  5759  5778 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
12-01 21:54:36.063  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,12-01 21:54:36.064  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:54:36.065  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:54:36.065  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 21:54:36.065  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.065  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.065  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 21:54:36.065  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 21:54:36.065  5541  5541 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
12-01 21:54:36.065  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.065  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
12-01 21:54:36.065  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
12-01 21:54:36.065  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.065  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.065  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.066  5541  5541 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 21:54:36.066  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.066  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.068  5759  5775 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
12-01 21:54:36.068  5759  5775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:54:36.069  5759  5778 D BtGatt.ScanManager: Starting BLE batch scan
12-01 21:54:36.069  5759  5778 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
12-01 21:54:36.070  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.070  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 21:54:36.070  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,12-01 21:54:36.070  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 21:54:36.070  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.070  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 21:54:36.070  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:54:36.070  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 21:54:36.070  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
12-01 21:54:36.070  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae5f545 removed from the list
12-01 21:54:36.070  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:54:36.070  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d02a49a removed from the list
12-01 21:54:36.070  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
12-01 21:54:36.071  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.071  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.073   928  5816 D NetlinkSocketObserver: NeighborEvent{elapsedMs=157012, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
12-01 21:54:36.074   505   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,12-01 21:54:36.075  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.075  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.076  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.076  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 21:54:36.076  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 21:54:36.076  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:54:36.076  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d02a49a not in the list
12-01 21:54:36.076  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.076  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.077  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.077  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.077  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.077  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 21:54:36.077  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 21:54:36.077  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:54:36.078  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6a3da8 removed from the list
12-01 21:54:36.078  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,12-01 21:54:36.078  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,12-01 21:54:36.078  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,12-01 21:54:36.078  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16331cb removed from the list
12-01 21:54:36.078  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
12-01 21:54:36.078  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfa87fd added. We now have 3 listener(s)
12-01 21:54:36.080  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
12-01 21:54:36.080  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 21:54:36.080  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 21:54:36.080  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,12-01 21:54:36.080  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c92cf2 added. We now have 4 listener(s)
,12-01 21:54:36.080  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,12-01 21:54:36.080  5759  5775 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
12-01 21:54:36.081  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
12-01 21:54:36.081  5759  5775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:54:36.081   928  2961 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
12-01 21:54:36.081  3738  3880 W QCNEJ   : |CORE| network available: 102
,12-01 21:54:36.081   928  2961 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,12-01 21:54:36.083  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
12-01 21:54:36.083  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4860f43 added. We now have 4 listener(s)
12-01 21:54:36.083   928   945 D Tethering: MasterInitialState.processMessage what=3
12-01 21:54:36.084  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
12-01 21:54:36.084  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,12-01 21:54:36.084  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 21:54:36.084  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 21:54:36.084  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68d19c0 added. We now have 5 listener(s)
,12-01 21:54:36.084  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 21:54:36.084  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
12-01 21:54:36.085  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
12-01 21:54:36.085  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
12-01 21:54:36.085  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,12-01 21:54:36.085  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
12-01 21:54:36.085  3738  3880 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
12-01 21:54:36.085  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
12-01 21:54:36.086   928  2961 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
12-01 21:54:36.089  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
12-01 21:54:36.089  5759  5775 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
12-01 21:54:36.089  5759  5775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 21:54:36.091  5759  5778 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,12-01 21:54:36.091  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
12-01 21:54:36.092  5541  5587 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
12-01 21:54:36.092  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
12-01 21:54:36.092  3738  3880 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
12-01 21:54:36.093  3738  3880 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
12-01 21:54:36.094  4880  4895 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
12-01 21:54:36.094  4880  4895 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
12-01 21:54:36.094  4880  4895 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
,12-01 21:54:36.094  4880  4895 E SarControlService: no key has been found,reset the power
12-01 21:54:36.094  4880  4921 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
12-01 21:54:36.094  4880  4921 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
12-01 21:54:36.094  4880  4921 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
12-01 21:54:36.095  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.095  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
12-01 21:54:36.095  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
12-01 21:54:36.095  4909  4909 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
12-01 21:54:36.096  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,12-01 21:54:36.096  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
12-01 21:54:36.096  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
12-01 21:54:36.097  3982  3982 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
12-01 21:54:36.097  5759  5775 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
12-01 21:54:36.097  5759  5775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:54:36.097  5759  5775 E BtGatt.ContextMap: Context not found for ID 5
12-01 21:54:36.098  4880  4921 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
12-01 21:54:36.098  4880  4921 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,12-01 21:54:36.098  4880  4921 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
12-01 21:54:36.099  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
12-01 21:54:36.099  4909  4909 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
12-01 21:54:36.100  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.100  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
12-01 21:54:36.100  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
12-01 21:54:36.100  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
12-01 21:54:36.100  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
12-01 21:54:36.100  3852  3852 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
12-01 21:54:36.100  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:54:36.101  5541  5587 D BluetoothAdapter: STATE_ON
12-01 21:54:36.102  5759  5770 D BtGatt.GattService: registerClient() - UUID=cc7d83a2-3b21-4c0d-83c2-0aeed7acd281
12-01 21:54:36.103  5759  5775 D BtGatt.GattService: onClientRegistered() - UUID=cc7d83a2-3b21-4c0d-83c2-0aeed7acd281, clientIf=5
12-01 21:54:36.103  5541  5552 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
12-01 21:54:36.103  4909  4923 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a3b3863 HexData = [00000000f003000000000000ffffffff]
12-01 21:54:36.103  4909  4923 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
12-01 21:54:36.103  5759  5769 D BtGatt.GattService: start scan with filters
12-01 21:54:36.103  4909  4923 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
,12-01 21:54:36.103  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
12-01 21:54:36.103  5759  5775 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
12-01 21:54:36.103  5759  5775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:54:36.103  4880  4892 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
12-01 21:54:36.104  5759  5778 D BtGatt.ScanManager: stopping BLe Batch
12-01 21:54:36.104  3852  3852 D SystemUpdateService: onCreate
12-01 21:54:36.107  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
12-01 21:54:36.107  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.107  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
12-01 21:54:36.107  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.107  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,12-01 21:54:36.107  5541  5541 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
12-01 21:54:36.107  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.107  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
12-01 21:54:36.108  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
12-01 21:54:36.108  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.108  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.108  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.108  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.108  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
12-01 21:54:36.108  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:54:36.109  3852  3852 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
12-01 21:54:36.109  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.110  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
12-01 21:54:36.110  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.110  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.110  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
12-01 21:54:36.110  5541  5587 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
12-01 21:54:36.110  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.110  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 21:54:36.110  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 21:54:36.110  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 21:54:36.110  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:54:36.110  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 21:54:36.110  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,12-01 21:54:36.110  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 21:54:36.110  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
12-01 21:54:36.110  4909  4923 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a3b3863 HexData = [00000000f103000000000000ffffffff]
12-01 21:54:36.110  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfa87fd removed from the list
12-01 21:54:36.110  4909  4923 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
12-01 21:54:36.110  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:54:36.110  5759  5775 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
12-01 21:54:36.110  4909  4923 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
12-01 21:54:36.110  5759  5775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:54:36.110  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c92cf2 removed from the list
12-01 21:54:36.110  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
12-01 21:54:36.111  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 21:54:36.111  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 21:54:36.111  5759  5778 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
12-01 21:54:36.111  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:54:36.111  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,12-01 21:54:36.111  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
12-01 21:54:36.111  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 21:54:36.111  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 21:54:36.111  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.111  4909  4909 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
12-01 21:54:36.111  4880  4893 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
12-01 21:54:36.112  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:54:36.112  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.112  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.112  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 21:54:36.112  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 21:54:36.112  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:54:36.112  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c92cf2 not in the list
12-01 21:54:36.112  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.112  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.112  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.112  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
12-01 21:54:36.112  5541  5541 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
12-01 21:54:36.113  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.113  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
12-01 21:54:36.113  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,12-01 21:54:36.113  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.113  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.113  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.113  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
12-01 21:54:36.113  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.115  5541  5587 D BluetoothAdapter: STATE_ON
12-01 21:54:36.115  5759  5794 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
12-01 21:54:36.115  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
12-01 21:54:36.116  5541  5587 D BluetoothAdapter: STATE_ON
,12-01 21:54:36.116  5759  5798 D BtGatt.GattService: stopScan() - queue size =0
12-01 21:54:36.117  5759  5769 D BtGatt.GattService: unregisterClient() - clientIf=5
12-01 21:54:36.117  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
12-01 21:54:36.117  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.117  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
12-01 21:54:36.117  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.117  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.117  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.118  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.118  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
12-01 21:54:36.118  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
,12-01 21:54:36.118  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.118  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.118  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
12-01 21:54:36.118  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
12-01 21:54:36.118  5759  5775 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
12-01 21:54:36.118  5759  5775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:54:36.119  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
12-01 21:54:36.119  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.120  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,12-01 21:54:36.120  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 21:54:36.120  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.120  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.120  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 21:54:36.120  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 21:54:36.120  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:54:36.120  5759  5778 D BtGatt.ScanManager: handling starting scan
12-01 21:54:36.120  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68d19c0 removed from the list
12-01 21:54:36.120  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:54:36.120  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 21:54:36.120  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 21:54:36.120  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,12-01 21:54:36.120  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 21:54:36.120  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4860f43 removed from the list
12-01 21:54:36.120  5541  5541 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
12-01 21:54:36.120  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.120  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
12-01 21:54:36.120  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
12-01 21:54:36.120  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.120  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.121  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,12-01 21:54:36.121  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.121  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e47b9b5 added. We now have 3 listener(s)
12-01 21:54:36.121  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
12-01 21:54:36.121  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 21:54:36.122  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 21:54:36.121  5541  5541 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 21:54:36.122  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 21:54:36.122  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61d684a added. We now have 4 listener(s)
12-01 21:54:36.122  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 21:54:36.122  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
,12-01 21:54:36.122  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.122  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
12-01 21:54:36.123  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.123  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.123  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.124  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
12-01 21:54:36.124  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38823bb added. We now have 4 listener(s)
12-01 21:54:36.124  3852  5828 I SystemUpdateService: active receiver: enabled
12-01 21:54:36.125  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
12-01 21:54:36.125  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,12-01 21:54:36.125  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 21:54:36.125  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 21:54:36.125  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97c60d8 added. We now have 5 listener(s)
12-01 21:54:36.125  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 21:54:36.125  5759  5775 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
12-01 21:54:36.125  5759  5775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:54:36.125  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
12-01 21:54:36.125  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
12-01 21:54:36.125  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
12-01 21:54:36.125  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
12-01 21:54:36.125  5759  5778 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
12-01 21:54:36.125  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,12-01 21:54:36.128  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
12-01 21:54:36.131  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
12-01 21:54:36.131  5541  5587 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
12-01 21:54:36.131  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
12-01 21:54:36.132  5759  5775 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
12-01 21:54:36.132  5759  5775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 21:54:36.132  5759  5778 D BtGatt.ScanManager: Starting BLE batch scan
12-01 21:54:36.132  5759  5778 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
12-01 21:54:36.134  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.134  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
12-01 21:54:36.135  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
12-01 21:54:36.135  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
12-01 21:54:36.135  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
12-01 21:54:36.127  3852  5828 I SystemUpdateService: Already downloaded, skipping offpeak checks.
12-01 21:54:36.141  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.141  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
12-01 21:54:36.141  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
12-01 21:54:36.141  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
12-01 21:54:36.141  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
12-01 21:54:36.141  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.141  5541  5587 D BluetoothAdapter: STATE_ON
12-01 21:54:36.142  5759  5775 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
12-01 21:54:36.142  5759  5775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:54:36.142  3852  3852 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
12-01 21:54:36.146  5759  5769 D BtGatt.GattService: registerClient() - UUID=67bdccc2-a869-45fc-9dce-93c372f8dbf4
12-01 21:54:36.147  5759  5775 D BtGatt.GattService: onClientRegistered() - UUID=67bdccc2-a869-45fc-9dce-93c372f8dbf4, clientIf=5
12-01 21:54:36.147  5541  5552 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
12-01 21:54:36.147  5759  5794 D BtGatt.GattService: start scan with filters
12-01 21:54:36.149  5759  5775 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
12-01 21:54:36.149  5759  5775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:54:36.149  3852  5828 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
12-01 21:54:36.149  3852  5828 I SystemUpdateService: now status is 0 (complete)
12-01 21:54:36.151  3852  5828 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
12-01 21:54:36.151  5759  5778 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
12-01 21:54:36.151  3852  5828 I SystemUpdateService: file has been verified
12-01 21:54:36.151  3852  5828 I SystemUpdateService: OTA package size = 21989297
12-01 21:54:36.152   928  5815 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking h,ttp://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.14,2a00:1450:4001:81a::200e
12-01 21:54:36.152  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
12-01 21:54:36.152  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.152  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
12-01 21:54:36.152  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.152  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
12-01 21:54:36.152  5541  5541 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
12-01 21:54:36.152  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.152  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
12-01 21:54:36.153  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
12-01 21:54:36.153  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.153  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.153  3852  5345 I iu.UploadsManager: num queued entries: 0
12-01 21:54:36.153  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.153  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.153  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
12-01 21:54:36.153  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.153  3852  5345 I iu.UploadsManager: num updated entries: 0
12-01 21:54:36.155  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.155  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
12-01 21:54:36.155  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.155  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.155  5759  5775 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
12-01 21:54:36.155  5759  5775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:54:36.156  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,12-01 21:54:36.159  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 21:54:36.159  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 21:54:36.159  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 21:54:36.159  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:54:36.159  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 21:54:36.159  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 21:54:36.159  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 21:54:36.159  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
12-01 21:54:36.159  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e47b9b5 removed from the list
12-01 21:54:36.159  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:54:36.159  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61d684a removed from the list
12-01 21:54:36.159  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
12-01 21:54:36.160  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
12-01 21:54:36.160  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 21:54:36.160  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.160  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
12-01 21:54:36.160  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
12-01 21:54:36.160  5541  5587 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,12-01 21:54:36.160  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
12-01 21:54:36.160  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.161  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.161  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.161  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.161  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 21:54:36.161  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 21:54:36.161  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:54:36.161  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61d684a not in the list
12-01 21:54:36.161  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.161  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.161  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.161  5541  5541 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
12-01 21:54:36.161  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.161  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
12-01 21:54:36.162  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.162  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
12-01 21:54:36.162  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
12-01 21:54:36.162  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.162  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.162  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.162  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
12-01 21:54:36.162  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.164  5541  5587 D BluetoothAdapter: STATE_ON
,12-01 21:54:36.164  5759  5769 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
12-01 21:54:36.164  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
12-01 21:54:36.165  5759  5775 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
12-01 21:54:36.165  5759  5775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:54:36.165  5541  5587 D BluetoothAdapter: STATE_ON
12-01 21:54:36.165  5759  5778 D BtGatt.ScanManager: stopping BLe Batch
12-01 21:54:36.165  5759  5770 D BtGatt.GattService: stopScan() - queue size =0
12-01 21:54:36.166  5759  5794 D BtGatt.GattService: unregisterClient() - clientIf=5
12-01 21:54:36.167  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
12-01 21:54:36.167  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.167  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,12-01 21:54:36.167  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.167  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.168  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.168  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.168  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
12-01 21:54:36.168  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.168  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.168  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.168  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
12-01 21:54:36.168  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
12-01 21:54:36.168  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,12-01 21:54:36.169  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.169  3852  3852 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
12-01 21:54:36.170  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.170  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 21:54:36.170  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.170  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.170  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 21:54:36.170  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 21:54:36.170  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,12-01 21:54:36.170  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97c60d8 removed from the list
12-01 21:54:36.170  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:54:36.170  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 21:54:36.170  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
12-01 21:54:36.170  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 21:54:36.171  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38823bb removed from the list
12-01 21:54:36.171  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
12-01 21:54:36.171  5541  5541 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
12-01 21:54:36.171  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.171  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,12-01 21:54:36.171  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
12-01 21:54:36.171  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
12-01 21:54:36.171  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.171  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b626a6d added. We now have 3 listener(s)
12-01 21:54:36.171  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.171  5541  5541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.171  5541  5541 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
12-01 21:54:36.171  3852  3852 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
12-01 21:54:36.171  5541  5541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.171  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.172  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
12-01 21:54:36.172  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 21:54:36.172  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,12-01 21:54:36.172  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 21:54:36.172  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a2b6a2 added. We now have 4 listener(s)
12-01 21:54:36.172  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 21:54:36.173  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
12-01 21:54:36.174  3852  5828 I SystemUpdateService: showing system update notification
12-01 21:54:36.175  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.175  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.175  5541  5541 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
12-01 21:54:36.175  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
12-01 21:54:36.175  5348  5348 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
12-01 21:54:36.175  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6394f33 added. We now have 4 listener(s)
,12-01 21:54:36.176  5759  5775 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
12-01 21:54:36.176  5759  5775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:54:36.176  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
12-01 21:54:36.176  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
12-01 21:54:36.176  5759  5778 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
12-01 21:54:36.176  5541  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
12-01 21:54:36.176  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
12-01 21:54:36.176  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa72f0 added. We now have 5 listener(s)
12-01 21:54:36.176  5541  5587 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
12-01 21:54:36.176  5541  5587 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
12-01 21:54:36.176  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,12-01 21:54:36.176  5541  5587 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
12-01 21:54:36.176  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:54:36.176  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
12-01 21:54:36.177  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
12-01 21:54:36.177  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b626a6d removed from the list
12-01 21:54:36.177  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:54:36.177  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a2b6a2 removed from the list
12-01 21:54:36.177  5541  5587 D io.jxcore.node.ConnectivityMonitor: stop
12-01 21:54:36.177  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.177  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.178  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.178  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.178  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.178  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 21:54:36.178  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 21:54:36.178  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:54:36.178  5541  5587 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a2b6a2 not in the list
12-01 21:54:36.178  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.178  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.179  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.179  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.179  5541  5587 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
12-01 21:54:36.179  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
12-01 21:54:36.179  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
12-01 21:54:36.179  5541  5587 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
12-01 21:54:36.179  5541  5587 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa72f0 removed from the list
12-01 21:54:36.179  5541  5587 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
12-01 21:54:36.179  5541  5587 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,12-01 21:54:36.179  5541  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
12-01 21:54:36.179  5541  5587 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6394f33 removed from the list
12-01 21:54:36.179  5348  5348 D SprintDMHelper: simOperator: 
12-01 21:54:36.179  5348  5348 D SprintDMReceiver: Not Sprint UICC, don't do anything.
12-01 21:54:36.180  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
12-01 21:54:36.180  3852  5345 I iu.SyncManager: NEXT; no task
12-01 21:54:36.180  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
12-01 21:54:36.180  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
12-01 21:54:36.180  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
12-01 21:54:36.180  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
12-01 21:54:36.180  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,12-01 21:54:36.183  5759  5775 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
12-01 21:54:36.183  5759  5775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:54:36.184  5759  5778 D BtGatt.ScanManager: handling starting scan
,12-01 21:54:36.192  5759  5775 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,12-01 21:54:36.192  5759  5775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:54:36.192  5759  5778 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,12-01 21:54:36.201  5759  5775 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,12-01 21:54:36.201  5759  5775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:54:36.201  5759  5778 D BtGatt.ScanManager: Starting BLE batch scan
12-01 21:54:36.201  5759  5778 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,12-01 21:54:36.213  5759  5775 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,12-01 21:54:36.213  5759  5775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 21:54:36.216   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,12-01 21:54:36.218  5759  5775 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,12-01 21:54:36.218  5759  5775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 21:54:36.220  5759  5778 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,12-01 21:54:36.222  3852  3852 D SystemUpdateService: onDestroy
,12-01 21:54:36.226  5759  5775 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
12-01 21:54:36.226  5759  5775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:54:36.226  5759  5775 E BtGatt.ContextMap: Context not found for ID 5
12-01 21:54:36.229  3591  5838 I VacuumService: Vacuum at: now=1480625676229 tag=VacuumService
12-01 21:54:36.233  5759  5775 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
12-01 21:54:36.233  5759  5775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:54:36.233  5759  5778 D BtGatt.ScanManager: stopping BLe Batch
,12-01 21:54:36.238  5759  5775 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,12-01 21:54:36.238  5759  5775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
12-01 21:54:36.238  5759  5778 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
12-01 21:54:36.242   928  5815 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 01 Dec 2016 20:54:36 GMT], X-Android-Received-Millis=[1480625676240], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480625676195]}
12-01 21:54:36.242   928  2961 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
12-01 21:54:36.242   928  2961 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
12-01 21:54:36.242   928  2961 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
12-01 21:54:36.244   928  2961 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,12-01 21:54:36.248  5759  5775 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
12-01 21:54:36.248  5759  5775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,12-01 21:54:36.273  3591  5842 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,12-01 21:54:36.307  3591  5839 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,12-01 21:54:36.310  3591  5839 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,12-01 21:54:36.333  3591  5839 W Uploader:  no longer exists, so no auth token.
,12-01 21:54:36.340  3591  5842 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,12-01 21:54:36.345  4355  5834 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,12-01 21:54:36.568  5541  5541 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,12-01 21:54:36.623  5541  5541 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,12-01 21:54:36.671  5541  5541 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,12-01 21:54:36.759  3591  5839 W Uploader:  no longer exists, so no auth token.
,12-01 21:54:36.768  3591  5844 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,12-01 21:54:36.854  3591  5842 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,12-01 21:54:36.936  3591  5844 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,12-01 21:54:37.018  3591  5842 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,12-01 21:54:37.538  3591  3591 I SQLiteConnectionPool: The connection pool for /data/user/0/com.google.android.gms/databases/phenotype.db has been closed but there are still 1 connections in use.  They will be closed as they are released back to the pool.
,12-01 21:54:37.541  3591  5843 E ClearcutLoggerIntentService: attempt to re-open an already-closed object: SQLiteDatabase: /data/user/0/com.google.android.gms/databases/phenotype.db
12-01 21:54:37.541  3591  5843 E ClearcutLoggerIntentService: java.lang.IllegalStateException: attempt to re-open an already-closed object: SQLiteDatabase: /data/user/0/com.google.android.gms/databases/phenotype.db
12-01 21:54:37.541  3591  5843 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteClosable.acquireReference(SQLiteClosable.java:55)
12-01 21:54:37.541  3591  5843 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:520)
12-01 21:54:37.541  3591  5843 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:143)
12-01 21:54:37.541  3591  5843 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
12-01 21:54:37.541  3591  5843 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
12-01 21:54:37.541  3591  5843 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
12-01 21:54:37.541  3591  5843 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
12-01 21:54:37.541  3591  5843 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
12-01 21:54:37.541  3591  5843 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,12-01 21:54:38.335  5541  5850 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 174, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
12-01 21:54:38.335  5541  5850 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,12-01 21:54:38.809   928  2961 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,12-01 21:54:39.145  5541  5850 W !!      : call onHalfStreamCopied
,12-01 21:54:39.145  5541  5850 I testCopyDataAndClose: closing input stream
,12-01 21:54:39.915  5541  5850 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 174, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
12-01 21:54:39.915  5541  5850 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,12-01 21:54:39.915  5541  5850 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
12-01 21:54:39.915  5541  5850 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
12-01 21:54:39.915  5541  5850 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,12-01 21:54:39.915  5541  5850 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
12-01 21:54:39.915  5541  5850 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
12-01 21:54:39.915  5541  5850 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,12-01 21:54:39.915  5541  5850 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,12-01 21:54:39.915  5541  5850 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 174, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
12-01 21:54:39.915  5541  5850 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,12-01 21:54:41.836   928  2961 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,12-01 21:54:43.734   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:54:44.030   928  2961 D ConnectivityService: handlePromptUnvalidated 102
,12-01 21:54:44.142  5541  5851 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: My test thread name). Connection data: Peer properties: [null null].
12-01 21:54:44.142  5541  5851 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,12-01 21:54:44.736   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:54:45.737   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:54:46.142  5541  5587 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 177. Connection data: Peer properties: [null null].
12-01 21:54:46.142  5541  5587 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,12-01 21:54:46.142  5541  5587 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 177, name: My test thread name)
,12-01 21:54:46.242  5541  5851 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,12-01 21:54:46.242  5541  5851 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 177, name: My test thread name). Connection data: Peer properties: [null null].
12-01 21:54:46.242  5541  5851 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 132 and the total number of bytes written 132
,12-01 21:54:46.255  5541  5852 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 179, name: testCopyBigData thread). Connection data: Peer properties: [null null].
12-01 21:54:46.255  5541  5852 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,12-01 21:54:46.739   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:54:46.999   928  2959 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,12-01 21:54:47.739   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:54:47.903  5541  5852 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 179, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
12-01 21:54:47.903  5541  5852 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,12-01 21:54:47.903  5541  5852 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
12-01 21:54:47.903  5541  5852 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,12-01 21:54:47.903  5541  5852 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
12-01 21:54:47.903  5541  5852 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
12-01 21:54:47.903  5541  5852 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,12-01 21:54:47.903  5541  5852 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
12-01 21:54:47.903  5541  5852 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
12-01 21:54:47.903  5541  5852 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 179, name: testCopyBigData thread). Connection data: Peer properties: [null null].
12-01 21:54:47.903  5541  5852 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,12-01 21:54:48.740   533   533 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,12-01 21:54:52.212  5541  5853 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
12-01 21:54:52.212  5541  5853 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,12-01 21:54:52.213  5541  5853 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 181, thread name: My test thread name). Connection data: Peer properties: [null null].
12-01 21:54:52.213  5541  5853 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
12-01 21:54:52.213  5541  5853 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
12-01 21:54:52.213  5541  5853 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
12-01 21:54:52.213  5541  5853 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
12-01 21:54:52.213  5541  5853 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,12-01 21:54:52.213  5541  5853 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
12-01 21:54:52.213  5541  5853 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
12-01 21:54:52.213  5541  5853 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
12-01 21:54:52.214  5541  5853 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
12-01 21:54:52.214  5541  5853 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
12-01 21:54:52.215  5541  5587 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,12-01 21:54:52.218  5541  5854 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
12-01 21:54:52.218  5541  5854 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,12-01 21:54:52.219  5541  5854 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 185, thread name: My test thread name): Test exception.
12-01 21:54:52.219  5541  5854 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
12-01 21:54:52.219  5541  5854 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,12-01 21:54:52.219  5541  5854 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
12-01 21:54:52.219  5541  5854 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
12-01 21:54:52.219  5541  5854 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,12-01 21:54:52.224  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
12-01 21:54:52.224  5541  5587 I jxcore-log: 
12-01 21:54:52.225  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - DEBUG UnitTest_app: 'Number of passed tests:  82'
12-01 21:54:52.225  5541  5587 I jxcore-log: 
,12-01 21:54:52.225  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - DEBUG UnitTest_app: 'Number of failed tests:  0'
12-01 21:54:52.225  5541  5587 I jxcore-log: 
12-01 21:54:52.225  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
12-01 21:54:52.225  5541  5587 I jxcore-log: 
12-01 21:54:52.225  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - DEBUG UnitTest_app: 'Total duration:  91831'
12-01 21:54:52.225  5541  5587 I jxcore-log: 
12-01 21:54:52.227  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - DEBUG UnitTest_app: 'Unit Test app is loaded'
12-01 21:54:52.227  5541  5587 I jxcore-log: 
,12-01 21:54:52.231  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
12-01 21:54:52.231  5541  5587 I jxcore-log: 
12-01 21:54:52.231  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
12-01 21:54:52.231  5541  5587 I jxcore-log: 
12-01 21:54:52.232  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
12-01 21:54:52.232  5541  5587 I jxcore-log: 
,12-01 21:54:52.232  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
12-01 21:54:52.232  5541  5587 I jxcore-log: 
12-01 21:54:52.233  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
12-01 21:54:52.233  5541  5587 I jxcore-log: 
12-01 21:54:52.233  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
12-01 21:54:52.233  5541  5587 I jxcore-log: 
12-01 21:54:52.233  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
12-01 21:54:52.233  5541  5587 I jxcore-log: 
,12-01 21:54:52.233  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
12-01 21:54:52.233  5541  5587 I jxcore-log: 
12-01 21:54:52.234  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
12-01 21:54:52.234  5541  5587 I jxcore-log: 
12-01 21:54:52.234  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
12-01 21:54:52.234  5541  5587 I jxcore-log: 
12-01 21:54:52.234  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
12-01 21:54:52.234  5541  5587 I jxcore-log: 
12-01 21:54:52.234  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
12-01 21:54:52.234  5541  5587 I jxcore-log: 
12-01 21:54:52.235  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
12-01 21:54:52.235  5541  5587 I jxcore-log: 
12-01 21:54:52.235  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
12-01 21:54:52.235  5541  5587 I jxcore-log: 
12-01 21:54:52.235  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
12-01 21:54:52.235  5541  5587 I jxcore-log: 
12-01 21:54:52.235  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
12-01 21:54:52.235  5541  5587 I jxcore-log: 
12-01 21:54:52.236  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
12-01 21:54:52.236  5541  5587 I jxcore-log: 
12-01 21:54:52.236  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
12-01 21:54:52.236  5541  5587 I jxcore-log: 
,12-01 21:54:52.236  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
12-01 21:54:52.236  5541  5587 I jxcore-log: 
12-01 21:54:52.236  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
12-01 21:54:52.236  5541  5587 I jxcore-log: 
12-01 21:54:52.237  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
12-01 21:54:52.237  5541  5587 I jxcore-log: 
12-01 21:54:52.237  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
12-01 21:54:52.237  5541  5587 I jxcore-log: 
,12-01 21:54:52.237  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
12-01 21:54:52.237  5541  5587 I jxcore-log: 
12-01 21:54:52.238  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
12-01 21:54:52.238  5541  5587 I jxcore-log: 
,12-01 21:54:52.239  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
12-01 21:54:52.239  5541  5587 I jxcore-log: 
12-01 21:54:52.239  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
12-01 21:54:52.239  5541  5587 I jxcore-log: 
12-01 21:54:52.240  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
12-01 21:54:52.240  5541  5587 I jxcore-log: 
12-01 21:54:52.240  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
12-01 21:54:52.240  5541  5587 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,12-01 21:54:52.240  5541  5587 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
12-01 21:54:52.240  5541  5587 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
12-01 21:54:52.240  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
12-01 21:54:52.240  5541  5587 I jxcore-log: 
12-01 21:54:52.241  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
12-01 21:54:52.241  5541  5587 I jxcore-log: 
12-01 21:54:52.241  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
12-01 21:54:52.241  5541  5587 I jxcore-log: 
12-01 21:54:52.241  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
12-01 21:54:52.241  5541  5587 I jxcore-log: 
,12-01 21:54:52.241  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
12-01 21:54:52.241  5541  5587 I jxcore-log: 
12-01 21:54:52.241  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
12-01 21:54:52.241  5541  5587 I jxcore-log: 
,12-01 21:54:52.247  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
12-01 21:54:52.247  5541  5587 I jxcore-log: 
,12-01 21:54:52.247  5541  5587 I jxcore-log: 2016-12-01 20:54:52 - WARN testUtils: 'myNameCallback not set!'
12-01 21:54:52.247  5541  5587 I jxcore-log: 
,12-01 21:54:52.248  5541  5541 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
12-01 21:54:52.248  5541  5541 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,12-01 21:54:52.592   928  5816 D NetlinkSocketObserver: NeighborEvent{elapsedMs=173530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,12-01 21:54:54.353  5541  5587 I jxcore-log: 2016-12-01 20:54:54 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
12-01 21:54:54.353  5541  5587 I jxcore-log: 
,12-01 21:54:54.355  5541  5587 I jxcore-log: 2016-12-01 20:54:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
12-01 21:54:54.355  5541  5587 I jxcore-log: 
,12-01 21:54:54.713  5541  5587 I jxcore-log: 2016-12-01 20:54:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
12-01 21:54:54.713  5541  5587 I jxcore-log: 
,12-01 21:54:54.725  5541  5587 I jxcore-log: 2016-12-01 20:54:54 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
12-01 21:54:54.725  5541  5587 I jxcore-log: 
,12-01 21:54:55.845  5541  5587 I jxcore-log: 2016-12-01 20:54:55 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
12-01 21:54:55.845  5541  5587 I jxcore-log: 
,12-01 21:54:56.037  5541  5587 I jxcore-log: 2016-12-01 20:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
12-01 21:54:56.037  5541  5587 I jxcore-log: 
,12-01 21:54:56.043  5541  5587 I jxcore-log: 2016-12-01 20:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
12-01 21:54:56.043  5541  5587 I jxcore-log: 
,12-01 21:54:56.048  5541  5587 I jxcore-log: 2016-12-01 20:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
12-01 21:54:56.048  5541  5587 I jxcore-log: 
,12-01 21:54:56.540  5541  5587 I jxcore-log: 2016-12-01 20:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
12-01 21:54:56.540  5541  5587 I jxcore-log: 
,12-01 21:54:56.586  5541  5587 I jxcore-log: 2016-12-01 20:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
12-01 21:54:56.586  5541  5587 I jxcore-log: 
,12-01 21:54:56.599  5541  5587 I jxcore-log: 2016-12-01 20:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testSSDPServer.js'
12-01 21:54:56.599  5541  5587 I jxcore-log: 
,12-01 21:54:56.629  5541  5587 I jxcore-log: 2016-12-01 20:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
12-01 21:54:56.629  5541  5587 I jxcore-log: 
,12-01 21:54:56.633  5541  5587 I jxcore-log: 2016-12-01 20:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
12-01 21:54:56.633  5541  5587 I jxcore-log: 
,12-01 21:54:56.897  5541  5587 I jxcore-log: 2016-12-01 20:54:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
12-01 21:54:56.897  5541  5587 I jxcore-log: 
,12-01 21:54:57.024  5541  5587 I jxcore-log: 2016-12-01 20:54:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
12-01 21:54:57.024  5541  5587 I jxcore-log: 
,12-01 21:54:57.392  5541  5587 I jxcore-log: 2016-12-01 20:54:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
12-01 21:54:57.392  5541  5587 I jxcore-log: 
,12-01 21:54:57.401  5541  5587 I jxcore-log: 2016-12-01 20:54:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
12-01 21:54:57.401  5541  5587 I jxcore-log: 
,12-01 21:54:57.405  5541  5587 I jxcore-log: 2016-12-01 20:54:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
12-01 21:54:57.405  5541  5587 I jxcore-log: 
,12-01 21:54:57.410  5541  5587 I jxcore-log: 2016-12-01 20:54:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
12-01 21:54:57.410  5541  5587 I jxcore-log: 
,12-01 21:54:57.415  5541  5587 I jxcore-log: 2016-12-01 20:54:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
12-01 21:54:57.415  5541  5587 I jxcore-log: 
,12-01 21:54:57.443  5541  5587 I jxcore-log: 2016-12-01 20:54:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
12-01 21:54:57.443  5541  5587 I jxcore-log: 
,12-01 21:54:57.480  5541  5587 I jxcore-log: 2016-12-01 20:54:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
12-01 21:54:57.480  5541  5587 I jxcore-log: 
,12-01 21:54:57.488  5541  5587 I jxcore-log: 2016-12-01 20:54:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
12-01 21:54:57.488  5541  5587 I jxcore-log: 
,12-01 21:54:57.494  5541  5587 I jxcore-log: 2016-12-01 20:54:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
12-01 21:54:57.494  5541  5587 I jxcore-log: 
,12-01 21:54:57.511  5541  5587 I jxcore-log: 2016-12-01 20:54:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
12-01 21:54:57.511  5541  5587 I jxcore-log: 
,12-01 21:54:57.526  5541  5587 I jxcore-log: 2016-12-01 20:54:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
12-01 21:54:57.526  5541  5587 I jxcore-log: 
,12-01 21:54:57.532  5541  5587 I jxcore-log: 2016-12-01 20:54:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
12-01 21:54:57.532  5541  5587 I jxcore-log: 
,12-01 21:54:57.537  5541  5587 I jxcore-log: 2016-12-01 20:54:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
12-01 21:54:57.537  5541  5587 I jxcore-log: 
,12-01 21:54:57.551  5541  5587 I jxcore-log: 2016-12-01 20:54:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
12-01 21:54:57.551  5541  5587 I jxcore-log: 
,12-01 21:54:57.569  5541  5587 I jxcore-log: 2016-12-01 20:54:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
12-01 21:54:57.569  5541  5587 I jxcore-log: 
,12-01 21:54:57.583  5541  5587 I jxcore-log: 2016-12-01 20:54:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
12-01 21:54:57.583  5541  5587 I jxcore-log: 
,12-01 21:54:57.594  5541  5587 I jxcore-log: 2016-12-01 20:54:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
12-01 21:54:57.594  5541  5587 I jxcore-log: 
,12-01 21:54:57.607  5541  5587 I jxcore-log: 2016-12-01 20:54:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
12-01 21:54:57.607  5541  5587 I jxcore-log: 
,12-01 21:54:57.618  5541  5587 I jxcore-log: 2016-12-01 20:54:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
12-01 21:54:57.618  5541  5587 I jxcore-log: 
,12-01 21:54:57.631  5541  5587 I jxcore-log: 2016-12-01 20:54:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
12-01 21:54:57.631  5541  5587 I jxcore-log: 
,12-01 21:54:57.641  5541  5587 I jxcore-log: 2016-12-01 20:54:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
12-01 21:54:57.641  5541  5587 I jxcore-log: 
,12-01 21:54:57.648  5541  5587 I jxcore-log: 2016-12-01 20:54:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
12-01 21:54:57.648  5541  5587 I jxcore-log: 
,12-01 21:54:57.662  5541  5587 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,12-01 21:54:57.663  5541  5587 I jxcore-log: 2016-12-01 20:54:57 - INFO testUtils: 'BLE multiple advertisement supported'
12-01 21:54:57.663  5541  5587 I jxcore-log: 
,12-01 21:54:57.697  5541  5587 I jxcore-log: 2016-12-01 20:54:57 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
12-01 21:54:57.697  5541  5587 I jxcore-log: 
,12-01 21:54:57.995  5541  5587 I jxcore-log: 2016-12-01 20:54:57 - DEBUG CoordinatedClient: 'connected to the test server'
12-01 21:54:57.995  5541  5587 I jxcore-log: 
,12-01 21:55:02.738   928  5816 D NetlinkSocketObserver: NeighborEvent{elapsedMs=183677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,12-01 21:55:08.741   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:55:09.743   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:55:10.744   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:55:11.745   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:55:12.747   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:55:13.379   928  5816 D NetlinkSocketObserver: NeighborEvent{elapsedMs=194317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,12-01 21:55:13.747   533   533 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,12-01 21:55:16.009   928  2959 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,12-01 21:55:27.992   928  5816 D NetlinkSocketObserver: NeighborEvent{elapsedMs=208930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,12-01 21:55:38.552   928  5816 D NetlinkSocketObserver: NeighborEvent{elapsedMs=219490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,12-01 21:55:38.748   533   533 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,12-01 21:55:38.749   533   533 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,12-01 21:55:42.305   928  2961 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,12-01 21:55:45.333   928  2961 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,12-01 21:55:48.750   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:55:49.751   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:55:50.752   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:55:51.754   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:55:52.756   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:55:53.032   928  5816 D NetlinkSocketObserver: NeighborEvent{elapsedMs=233970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,12-01 21:55:53.757   533   533 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,12-01 21:55:56.016   928  2959 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,12-01 21:55:58.758   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:55:59.760   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:56:00.761   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:56:01.763   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:56:02.764   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:56:03.592   928  5816 D NetlinkSocketObserver: NeighborEvent{elapsedMs=244531, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,12-01 21:56:03.765   533   533 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,12-01 21:56:13.766   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:56:14.768   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:56:15.769   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:56:16.018   928  2959 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,12-01 21:56:16.771   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:56:17.258  5541  5587 I jxcore-log: TAP version 13
12-01 21:56:17.258  5541  5587 I jxcore-log: 
,12-01 21:56:17.301  5541  5587 I jxcore-log: # setup
12-01 21:56:17.301  5541  5587 I jxcore-log: 
,12-01 21:56:17.772   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:56:17.858  5541  5587 I jxcore-log: # calling createNativeListener directly rejects
12-01 21:56:17.858  5541  5587 I jxcore-log: 
,12-01 21:56:17.906  5541  5587 I jxcore-log: 2016-12-01 20:56:17 - DEBUG createNativeListener: 'Creating Native Server'
12-01 21:56:17.906  5541  5587 I jxcore-log: 
,12-01 21:56:17.910  5541  5587 I jxcore-log: 2016-12-01 20:56:17 - DEBUG createNativeListener: 'listening 38923'
12-01 21:56:17.910  5541  5587 I jxcore-log: 
,12-01 21:56:17.917  5541  5587 I jxcore-log: ok 1 Should throw
12-01 21:56:17.917  5541  5587 I jxcore-log: 
,12-01 21:56:17.925  5541  5587 I jxcore-log: # teardown
12-01 21:56:17.925  5541  5587 I jxcore-log: 
,12-01 21:56:18.072   928  5816 D NetlinkSocketObserver: NeighborEvent{elapsedMs=259011, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,12-01 21:56:18.086  5541  5587 I jxcore-log: 2016-12-01 20:56:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:18.086  5541  5587 I jxcore-log: 
,12-01 21:56:18.094  5541  5587 I jxcore-log: 2016-12-01 20:56:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:18.094  5541  5587 I jxcore-log: 
,12-01 21:56:18.097  5541  5587 I jxcore-log: 2016-12-01 20:56:18 - DEBUG createNativeListener: 'Native Server - close'
12-01 21:56:18.097  5541  5587 I jxcore-log: 
,12-01 21:56:18.117  5541  5587 I jxcore-log: # setup
12-01 21:56:18.117  5541  5587 I jxcore-log: 
,12-01 21:56:18.246  5541  5587 I jxcore-log: # emits incomingConnectionState
12-01 21:56:18.246  5541  5587 I jxcore-log: 
,12-01 21:56:18.428  5541  5587 I jxcore-log: 2016-12-01 20:56:18 - DEBUG createNativeListener: 'Creating Native Server'
12-01 21:56:18.428  5541  5587 I jxcore-log: 
,12-01 21:56:18.432  5541  5587 I jxcore-log: 2016-12-01 20:56:18 - DEBUG createNativeListener: 'listening 46875'
12-01 21:56:18.432  5541  5587 I jxcore-log: 
,12-01 21:56:18.441  5541  5587 I jxcore-log: 2016-12-01 20:56:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
12-01 21:56:18.441  5541  5587 I jxcore-log: 
,12-01 21:56:18.444  5541  5587 I jxcore-log: 2016-12-01 20:56:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
12-01 21:56:18.444  5541  5587 I jxcore-log: 
,12-01 21:56:18.458  5541  5587 I jxcore-log: ok 2 initial connection state should be CONNECTED
12-01 21:56:18.458  5541  5587 I jxcore-log: 
,12-01 21:56:18.475  5541  5587 I jxcore-log: 2016-12-01 20:56:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
12-01 21:56:18.475  5541  5587 I jxcore-log: 
,12-01 21:56:18.476  5541  5587 I jxcore-log: ok 3 final connection state should be DISCONNECTED
12-01 21:56:18.476  5541  5587 I jxcore-log: 
,12-01 21:56:18.484  5541  5587 I jxcore-log: # teardown
12-01 21:56:18.484  5541  5587 I jxcore-log: 
,12-01 21:56:18.548  5541  5587 I jxcore-log: 2016-12-01 20:56:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:18.548  5541  5587 I jxcore-log: 
,12-01 21:56:18.551  5541  5587 I jxcore-log: 2016-12-01 20:56:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:18.551  5541  5587 I jxcore-log: 
,12-01 21:56:18.553  5541  5587 I jxcore-log: 2016-12-01 20:56:18 - DEBUG createNativeListener: 'Native Server - close'
12-01 21:56:18.553  5541  5587 I jxcore-log: 
,12-01 21:56:18.561  5541  5587 I jxcore-log: # setup
12-01 21:56:18.561  5541  5587 I jxcore-log: 
,12-01 21:56:18.702  5541  5587 I jxcore-log: # emits routerPortConnectionFailed
12-01 21:56:18.702  5541  5587 I jxcore-log: 
,12-01 21:56:18.753  5541  5587 I jxcore-log: 2016-12-01 20:56:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:18.753  5541  5587 I jxcore-log: 
,12-01 21:56:18.756  5541  5587 I jxcore-log: 2016-12-01 20:56:18 - DEBUG createNativeListener: 'Creating Native Server'
12-01 21:56:18.756  5541  5587 I jxcore-log: 
,12-01 21:56:18.761  5541  5587 I jxcore-log: 2016-12-01 20:56:18 - DEBUG createNativeListener: 'listening 49436'
12-01 21:56:18.761  5541  5587 I jxcore-log: 
,12-01 21:56:18.769  5541  5587 I jxcore-log: 2016-12-01 20:56:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
12-01 21:56:18.769  5541  5587 I jxcore-log: 
,12-01 21:56:18.770  5541  5587 I jxcore-log: 2016-12-01 20:56:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
12-01 21:56:18.770  5541  5587 I jxcore-log: 
,12-01 21:56:18.772   533   533 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,12-01 21:56:18.798  5541  5587 I jxcore-log: 2016-12-01 20:56:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
12-01 21:56:18.798  5541  5587 I jxcore-log: 
,12-01 21:56:18.806  5541  5587 I jxcore-log: 2016-12-01 20:56:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
12-01 21:56:18.806  5541  5587 I jxcore-log: 
,12-01 21:56:18.807  5541  5587 I jxcore-log: ok 4 tried to connect to right port
12-01 21:56:18.807  5541  5587 I jxcore-log: 
12-01 21:56:18.807  5541  5587 I jxcore-log: ok 5 failed due to refused connection
12-01 21:56:18.807  5541  5587 I jxcore-log: 
12-01 21:56:18.808  5541  5587 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
12-01 21:56:18.808  5541  5587 I jxcore-log: 
,12-01 21:56:18.814  5541  5587 I jxcore-log: # teardown
12-01 21:56:18.814  5541  5587 I jxcore-log: 
,12-01 21:56:18.816  5541  5587 I jxcore-log: 2016-12-01 20:56:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
12-01 21:56:18.816  5541  5587 I jxcore-log: 
12-01 21:56:18.816  5541  5587 I jxcore-log: 2016-12-01 20:56:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
12-01 21:56:18.816  5541  5587 I jxcore-log: 
,12-01 21:56:18.973  5541  5587 I jxcore-log: 2016-12-01 20:56:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:18.973  5541  5587 I jxcore-log: 
,12-01 21:56:18.978  5541  5587 I jxcore-log: 2016-12-01 20:56:18 - DEBUG createNativeListener: 'Native Server - close'
12-01 21:56:18.978  5541  5587 I jxcore-log: 
,12-01 21:56:18.982  5541  5587 I jxcore-log: 2016-12-01 20:56:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
12-01 21:56:18.982  5541  5587 I jxcore-log: 
,12-01 21:56:18.991  5541  5587 I jxcore-log: 2016-12-01 20:56:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
12-01 21:56:18.991  5541  5587 I jxcore-log: 
,12-01 21:56:19.005  5541  5587 I jxcore-log: # setup
12-01 21:56:19.005  5541  5587 I jxcore-log: 
,12-01 21:56:19.135  5541  5587 I jxcore-log: # native server connections all up
12-01 21:56:19.135  5541  5587 I jxcore-log: 
,12-01 21:56:19.310  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'Creating Native Server'
12-01 21:56:19.310  5541  5587 I jxcore-log: 
,12-01 21:56:19.316  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'listening 49533'
12-01 21:56:19.316  5541  5587 I jxcore-log: 
,12-01 21:56:19.325  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
12-01 21:56:19.325  5541  5587 I jxcore-log: 
,12-01 21:56:19.327  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'Native Server - Creating Mux'
12-01 21:56:19.327  5541  5587 I jxcore-log: 
,12-01 21:56:19.363  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
12-01 21:56:19.363  5541  5587 I jxcore-log: 
,12-01 21:56:19.369  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
12-01 21:56:19.369  5541  5587 I jxcore-log: 
,12-01 21:56:19.394  5541  5587 I jxcore-log: ok 7 Send/recvd #1 should be equal length
12-01 21:56:19.394  5541  5587 I jxcore-log: 
,12-01 21:56:19.395  5541  5587 I jxcore-log: ok 8 Send/recvd #1 should be same
12-01 21:56:19.395  5541  5587 I jxcore-log: 
12-01 21:56:19.397  5541  5587 I jxcore-log: ok 9 Send/recvd #2 should be equal length
12-01 21:56:19.397  5541  5587 I jxcore-log: 
12-01 21:56:19.398  5541  5587 I jxcore-log: ok 10 Send/recvd #2 should be same
12-01 21:56:19.398  5541  5587 I jxcore-log: 
,12-01 21:56:19.401  5541  5587 I jxcore-log: ok 11 Should be exactly 2 client sockets
12-01 21:56:19.401  5541  5587 I jxcore-log: 
,12-01 21:56:19.408  5541  5587 I jxcore-log: # teardown
12-01 21:56:19.408  5541  5587 I jxcore-log: 
,12-01 21:56:19.423  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:19.423  5541  5587 I jxcore-log: 
,12-01 21:56:19.426  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:19.426  5541  5587 I jxcore-log: 
,12-01 21:56:19.428  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'Native Server - close'
12-01 21:56:19.428  5541  5587 I jxcore-log: 
12-01 21:56:19.428  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
12-01 21:56:19.428  5541  5587 I jxcore-log: 
12-01 21:56:19.430  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
12-01 21:56:19.430  5541  5587 I jxcore-log: 
,12-01 21:56:19.432  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
12-01 21:56:19.432  5541  5587 I jxcore-log: 
,12-01 21:56:19.436  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
12-01 21:56:19.436  5541  5587 I jxcore-log: 
,12-01 21:56:19.446  5541  5587 I jxcore-log: # setup
12-01 21:56:19.446  5541  5587 I jxcore-log: 
,12-01 21:56:19.447  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
12-01 21:56:19.447  5541  5587 I jxcore-log: 
,12-01 21:56:19.454  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
12-01 21:56:19.454  5541  5587 I jxcore-log: 
,12-01 21:56:19.485  5541  5587 I jxcore-log: # native server - closing incoming stream cleans outgoing socket
12-01 21:56:19.485  5541  5587 I jxcore-log: 
,12-01 21:56:19.513  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'Creating Native Server'
12-01 21:56:19.513  5541  5587 I jxcore-log: 
,12-01 21:56:19.515  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'listening 38096'
12-01 21:56:19.515  5541  5587 I jxcore-log: 
,12-01 21:56:19.521  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
12-01 21:56:19.521  5541  5587 I jxcore-log: 
,12-01 21:56:19.522  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'Native Server - Creating Mux'
12-01 21:56:19.522  5541  5587 I jxcore-log: 
,12-01 21:56:19.532  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
12-01 21:56:19.532  5541  5587 I jxcore-log: 
,12-01 21:56:19.544  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
12-01 21:56:19.544  5541  5587 I jxcore-log: 
,12-01 21:56:19.545  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
12-01 21:56:19.545  5541  5587 I jxcore-log: 
,12-01 21:56:19.556  5541  5587 I jxcore-log: ok 12 socket shouldn't close until after stream
12-01 21:56:19.556  5541  5587 I jxcore-log: 
,12-01 21:56:19.557  5541  5587 I jxcore-log: ok 13 incoming remains open
12-01 21:56:19.557  5541  5587 I jxcore-log: 
,12-01 21:56:19.561  5541  5587 I jxcore-log: # teardown
12-01 21:56:19.561  5541  5587 I jxcore-log: 
,12-01 21:56:19.565  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
12-01 21:56:19.565  5541  5587 I jxcore-log: 
,12-01 21:56:19.626  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:19.626  5541  5587 I jxcore-log: 
12-01 21:56:19.627  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:19.627  5541  5587 I jxcore-log: 
,12-01 21:56:19.630  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'Native Server - close'
12-01 21:56:19.630  5541  5587 I jxcore-log: 
,12-01 21:56:19.632  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
12-01 21:56:19.632  5541  5587 I jxcore-log: 
,12-01 21:56:19.637  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
12-01 21:56:19.637  5541  5587 I jxcore-log: 
,12-01 21:56:19.645  5541  5587 I jxcore-log: # setup
12-01 21:56:19.645  5541  5587 I jxcore-log: 
,12-01 21:56:19.698  5541  5587 I jxcore-log: # native server - closing incoming connection cleans outgoing socket
12-01 21:56:19.698  5541  5587 I jxcore-log: 
,12-01 21:56:19.805  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'Creating Native Server'
12-01 21:56:19.805  5541  5587 I jxcore-log: 
,12-01 21:56:19.809  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'listening 49440'
12-01 21:56:19.809  5541  5587 I jxcore-log: 
,12-01 21:56:19.816  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
12-01 21:56:19.816  5541  5587 I jxcore-log: 
,12-01 21:56:19.817  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'Native Server - Creating Mux'
12-01 21:56:19.817  5541  5587 I jxcore-log: 
,12-01 21:56:19.829  5541  5587 I jxcore-log: ok 14 we should not have gotten an error
12-01 21:56:19.829  5541  5587 I jxcore-log: 
,12-01 21:56:19.834  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
12-01 21:56:19.834  5541  5587 I jxcore-log: 
,12-01 21:56:19.849  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
12-01 21:56:19.849  5541  5587 I jxcore-log: 
,12-01 21:56:19.851  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
12-01 21:56:19.851  5541  5587 I jxcore-log: 
,12-01 21:56:19.860  5541  5587 I jxcore-log: ok 15 socket shouldn't close until after incoming
12-01 21:56:19.860  5541  5587 I jxcore-log: 
,12-01 21:56:19.860  5541  5587 I jxcore-log: ok 16 incoming is cleaned up
12-01 21:56:19.860  5541  5587 I jxcore-log: 
,12-01 21:56:19.866  5541  5587 I jxcore-log: # teardown
12-01 21:56:19.866  5541  5587 I jxcore-log: 
,12-01 21:56:19.870  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
12-01 21:56:19.870  5541  5587 I jxcore-log: 
,12-01 21:56:19.929  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:19.929  5541  5587 I jxcore-log: 
,12-01 21:56:19.935  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:19.935  5541  5587 I jxcore-log: 
,12-01 21:56:19.937  5541  5587 I jxcore-log: 2016-12-01 20:56:19 - DEBUG createNativeListener: 'Native Server - close'
12-01 21:56:19.937  5541  5587 I jxcore-log: 
,12-01 21:56:19.947  5541  5587 I jxcore-log: # setup
12-01 21:56:19.947  5541  5587 I jxcore-log: 
,12-01 21:56:20.003  5541  5587 I jxcore-log: # native server - closing outgoing socket cleans associated mux stream
12-01 21:56:20.003  5541  5587 I jxcore-log: 
,12-01 21:56:20.087  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'Creating Native Server'
12-01 21:56:20.087  5541  5587 I jxcore-log: 
,12-01 21:56:20.091  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'listening 37976'
12-01 21:56:20.091  5541  5587 I jxcore-log: 
,12-01 21:56:20.099  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
12-01 21:56:20.099  5541  5587 I jxcore-log: 
,12-01 21:56:20.101  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'Native Server - Creating Mux'
12-01 21:56:20.101  5541  5587 I jxcore-log: 
,12-01 21:56:20.117  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
12-01 21:56:20.117  5541  5587 I jxcore-log: 
,12-01 21:56:20.137  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
12-01 21:56:20.137  5541  5587 I jxcore-log: 
,12-01 21:56:20.138  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
12-01 21:56:20.138  5541  5587 I jxcore-log: 
12-01 21:56:20.141  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
12-01 21:56:20.141  5541  5587 I jxcore-log: 
,12-01 21:56:20.148  5541  5587 I jxcore-log: ok 17 stream was closed
12-01 21:56:20.148  5541  5587 I jxcore-log: 
,12-01 21:56:20.148  5541  5587 I jxcore-log: ok 18 incoming should survive
12-01 21:56:20.148  5541  5587 I jxcore-log: 
12-01 21:56:20.149  5541  5587 I jxcore-log: ok 19 mux should have no streams
12-01 21:56:20.149  5541  5587 I jxcore-log: 
,12-01 21:56:20.154  5541  5587 I jxcore-log: # teardown
12-01 21:56:20.154  5541  5587 I jxcore-log: 
,12-01 21:56:20.203  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:20.203  5541  5587 I jxcore-log: 
,12-01 21:56:20.205  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:20.205  5541  5587 I jxcore-log: 
,12-01 21:56:20.208  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'Native Server - close'
12-01 21:56:20.208  5541  5587 I jxcore-log: 
,12-01 21:56:20.209  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
12-01 21:56:20.209  5541  5587 I jxcore-log: 
,12-01 21:56:20.215  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
12-01 21:56:20.215  5541  5587 I jxcore-log: 
,12-01 21:56:20.224  5541  5587 I jxcore-log: # setup
12-01 21:56:20.224  5541  5587 I jxcore-log: 
,12-01 21:56:20.275  5541  5587 I jxcore-log: # native server - closing the whole server cleans everything up
12-01 21:56:20.275  5541  5587 I jxcore-log: 
,12-01 21:56:20.320  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'Creating Native Server'
12-01 21:56:20.320  5541  5587 I jxcore-log: 
,12-01 21:56:20.324  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'listening 41135'
12-01 21:56:20.324  5541  5587 I jxcore-log: 
,12-01 21:56:20.335  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
12-01 21:56:20.335  5541  5587 I jxcore-log: 
,12-01 21:56:20.338  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'Native Server - Creating Mux'
12-01 21:56:20.338  5541  5587 I jxcore-log: 
,12-01 21:56:20.347  5541  5587 I jxcore-log: ok 20 we should not have gotten an error
12-01 21:56:20.347  5541  5587 I jxcore-log: 
,12-01 21:56:20.352  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
12-01 21:56:20.352  5541  5587 I jxcore-log: 
,12-01 21:56:20.364  5541  5587 I jxcore-log: ok 21 Buffers are identical
12-01 21:56:20.364  5541  5587 I jxcore-log: 
,12-01 21:56:20.365  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:20.365  5541  5587 I jxcore-log: 
12-01 21:56:20.367  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'Native Server - close'
12-01 21:56:20.367  5541  5587 I jxcore-log: 
12-01 21:56:20.368  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
12-01 21:56:20.368  5541  5587 I jxcore-log: 
12-01 21:56:20.370  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
12-01 21:56:20.370  5541  5587 I jxcore-log: 
,12-01 21:56:20.372  5541  5587 I jxcore-log: ok 22 native server is nulled out
12-01 21:56:20.372  5541  5587 I jxcore-log: 
,12-01 21:56:20.373  5541  5587 I jxcore-log: ok 23 native server should be closed
12-01 21:56:20.373  5541  5587 I jxcore-log: 
,12-01 21:56:20.375  5541  5587 I jxcore-log: ok 24 incoming has been removed
12-01 21:56:20.375  5541  5587 I jxcore-log: 
12-01 21:56:20.375  5541  5587 I jxcore-log: ok 25 Incoming should be done
12-01 21:56:20.375  5541  5587 I jxcore-log: 
,12-01 21:56:20.376  5541  5587 I jxcore-log: ok 26 The mux object should be closed
12-01 21:56:20.376  5541  5587 I jxcore-log: 
12-01 21:56:20.376  5541  5587 I jxcore-log: ok 27 The mux stream should be closed
12-01 21:56:20.376  5541  5587 I jxcore-log: 
12-01 21:56:20.377  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
12-01 21:56:20.377  5541  5587 I jxcore-log: 
,12-01 21:56:20.394  5541  5587 I jxcore-log: # teardown
12-01 21:56:20.394  5541  5587 I jxcore-log: 
,12-01 21:56:20.395  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
12-01 21:56:20.395  5541  5587 I jxcore-log: 
,12-01 21:56:20.422  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:20.422  5541  5587 I jxcore-log: 
,12-01 21:56:20.429  5541  5587 I jxcore-log: # setup
12-01 21:56:20.429  5541  5587 I jxcore-log: 
,12-01 21:56:20.458  5541  5587 I jxcore-log: # native server - we can get a ton of connections and data through and still clean up the server completely
12-01 21:56:20.458  5541  5587 I jxcore-log: 
,12-01 21:56:20.504  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'Creating Native Server'
12-01 21:56:20.504  5541  5587 I jxcore-log: 
,12-01 21:56:20.508  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'listening 38680'
12-01 21:56:20.508  5541  5587 I jxcore-log: 
,12-01 21:56:20.541  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
12-01 21:56:20.541  5541  5587 I jxcore-log: 
,12-01 21:56:20.542  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'Native Server - Creating Mux'
12-01 21:56:20.542  5541  5587 I jxcore-log: 
,12-01 21:56:20.547  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
12-01 21:56:20.547  5541  5587 I jxcore-log: 
,12-01 21:56:20.548  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'Native Server - Creating Mux'
12-01 21:56:20.548  5541  5587 I jxcore-log: 
,12-01 21:56:20.558  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
12-01 21:56:20.558  5541  5587 I jxcore-log: 
,12-01 21:56:20.559  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'Native Server - Creating Mux'
12-01 21:56:20.559  5541  5587 I jxcore-log: 
,12-01 21:56:20.563  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
12-01 21:56:20.563  5541  5587 I jxcore-log: 
,12-01 21:56:20.564  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'Native Server - Creating Mux'
12-01 21:56:20.564  5541  5587 I jxcore-log: 
,12-01 21:56:20.568  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
12-01 21:56:20.568  5541  5587 I jxcore-log: 
,12-01 21:56:20.568  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'Native Server - Creating Mux'
12-01 21:56:20.568  5541  5587 I jxcore-log: 
,12-01 21:56:20.571  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
12-01 21:56:20.571  5541  5587 I jxcore-log: 
,12-01 21:56:20.572  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'Native Server - Creating Mux'
12-01 21:56:20.572  5541  5587 I jxcore-log: 
12-01 21:56:20.575  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
12-01 21:56:20.575  5541  5587 I jxcore-log: 
12-01 21:56:20.575  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'Native Server - Creating Mux'
12-01 21:56:20.575  5541  5587 I jxcore-log: 
,12-01 21:56:20.578  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
12-01 21:56:20.578  5541  5587 I jxcore-log: 
,12-01 21:56:20.578  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'Native Server - Creating Mux'
12-01 21:56:20.578  5541  5587 I jxcore-log: 
12-01 21:56:20.580  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
12-01 21:56:20.580  5541  5587 I jxcore-log: 
12-01 21:56:20.581  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'Native Server - Creating Mux'
12-01 21:56:20.581  5541  5587 I jxcore-log: 
,12-01 21:56:20.584  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
12-01 21:56:20.584  5541  5587 I jxcore-log: 
,12-01 21:56:20.584  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'Native Server - Creating Mux'
12-01 21:56:20.584  5541  5587 I jxcore-log: 
,12-01 21:56:20.654  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
12-01 21:56:20.654  5541  5587 I jxcore-log: 
,12-01 21:56:20.657  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
12-01 21:56:20.657  5541  5587 I jxcore-log: 
,12-01 21:56:20.659  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
12-01 21:56:20.659  5541  5587 I jxcore-log: 
,12-01 21:56:20.660  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
12-01 21:56:20.660  5541  5587 I jxcore-log: 
,12-01 21:56:20.662  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
12-01 21:56:20.662  5541  5587 I jxcore-log: 
,12-01 21:56:20.664  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
12-01 21:56:20.664  5541  5587 I jxcore-log: 
,12-01 21:56:20.665  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
12-01 21:56:20.665  5541  5587 I jxcore-log: 
,12-01 21:56:20.667  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
12-01 21:56:20.667  5541  5587 I jxcore-log: 
,12-01 21:56:20.669  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
12-01 21:56:20.669  5541  5587 I jxcore-log: 
,12-01 21:56:20.670  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
12-01 21:56:20.670  5541  5587 I jxcore-log: 
,12-01 21:56:20.672  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
12-01 21:56:20.672  5541  5587 I jxcore-log: 
,12-01 21:56:20.673  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
12-01 21:56:20.673  5541  5587 I jxcore-log: 
,12-01 21:56:20.675  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
12-01 21:56:20.675  5541  5587 I jxcore-log: 
,12-01 21:56:20.677  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
12-01 21:56:20.677  5541  5587 I jxcore-log: 
,12-01 21:56:20.678  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
12-01 21:56:20.678  5541  5587 I jxcore-log: 
,12-01 21:56:20.679  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
12-01 21:56:20.679  5541  5587 I jxcore-log: 
,12-01 21:56:20.681  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
12-01 21:56:20.681  5541  5587 I jxcore-log: 
,12-01 21:56:20.682  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
12-01 21:56:20.682  5541  5587 I jxcore-log: 
,12-01 21:56:20.683  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
12-01 21:56:20.683  5541  5587 I jxcore-log: 
,12-01 21:56:20.685  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
12-01 21:56:20.685  5541  5587 I jxcore-log: 
,12-01 21:56:20.686  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
12-01 21:56:20.686  5541  5587 I jxcore-log: 
,12-01 21:56:20.688  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
12-01 21:56:20.688  5541  5587 I jxcore-log: 
,12-01 21:56:20.689  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
12-01 21:56:20.689  5541  5587 I jxcore-log: 
,12-01 21:56:20.690  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
12-01 21:56:20.690  5541  5587 I jxcore-log: 
,12-01 21:56:20.692  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
12-01 21:56:20.692  5541  5587 I jxcore-log: 
,12-01 21:56:20.693  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
12-01 21:56:20.693  5541  5587 I jxcore-log: 
,12-01 21:56:20.695  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
12-01 21:56:20.695  5541  5587 I jxcore-log: 
,12-01 21:56:20.696  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
12-01 21:56:20.696  5541  5587 I jxcore-log: 
,12-01 21:56:20.698  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
12-01 21:56:20.698  5541  5587 I jxcore-log: 
,12-01 21:56:20.699  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
12-01 21:56:20.699  5541  5587 I jxcore-log: 
,12-01 21:56:20.700  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
12-01 21:56:20.700  5541  5587 I jxcore-log: 
,12-01 21:56:20.702  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
12-01 21:56:20.702  5541  5587 I jxcore-log: 
,12-01 21:56:20.703  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
12-01 21:56:20.703  5541  5587 I jxcore-log: 
,12-01 21:56:20.704  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
12-01 21:56:20.704  5541  5587 I jxcore-log: 
,12-01 21:56:20.710  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
12-01 21:56:20.710  5541  5587 I jxcore-log: 
,12-01 21:56:20.712  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
12-01 21:56:20.712  5541  5587 I jxcore-log: 
,12-01 21:56:20.714  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
12-01 21:56:20.714  5541  5587 I jxcore-log: 
,12-01 21:56:20.715  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
12-01 21:56:20.715  5541  5587 I jxcore-log: 
,12-01 21:56:20.716  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
12-01 21:56:20.716  5541  5587 I jxcore-log: 
,12-01 21:56:20.717  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
12-01 21:56:20.717  5541  5587 I jxcore-log: 
,12-01 21:56:20.762  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:20.762  5541  5587 I jxcore-log: 
,12-01 21:56:20.765  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'Native Server - close'
12-01 21:56:20.765  5541  5587 I jxcore-log: 
,12-01 21:56:20.765  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
12-01 21:56:20.765  5541  5587 I jxcore-log: 
,12-01 21:56:20.766  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
12-01 21:56:20.766  5541  5587 I jxcore-log: 
,12-01 21:56:20.767  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
12-01 21:56:20.767  5541  5587 I jxcore-log: 
,12-01 21:56:20.768  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
12-01 21:56:20.768  5541  5587 I jxcore-log: 
12-01 21:56:20.769  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
12-01 21:56:20.769  5541  5587 I jxcore-log: 
,12-01 21:56:20.769  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
12-01 21:56:20.769  5541  5587 I jxcore-log: 
12-01 21:56:20.770  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
12-01 21:56:20.770  5541  5587 I jxcore-log: 
12-01 21:56:20.770  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
12-01 21:56:20.770  5541  5587 I jxcore-log: 
,12-01 21:56:20.771  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
12-01 21:56:20.771  5541  5587 I jxcore-log: 
12-01 21:56:20.771  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
12-01 21:56:20.771  5541  5587 I jxcore-log: 
,12-01 21:56:20.772  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
12-01 21:56:20.772  5541  5587 I jxcore-log: 
,12-01 21:56:20.772  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
12-01 21:56:20.772  5541  5587 I jxcore-log: 
12-01 21:56:20.773  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
12-01 21:56:20.773  5541  5587 I jxcore-log: 
12-01 21:56:20.773  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
12-01 21:56:20.773  5541  5587 I jxcore-log: 
12-01 21:56:20.774  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
12-01 21:56:20.774  5541  5587 I jxcore-log: 
,12-01 21:56:20.779  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
12-01 21:56:20.779  5541  5587 I jxcore-log: 
,12-01 21:56:20.780  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
12-01 21:56:20.780  5541  5587 I jxcore-log: 
,12-01 21:56:20.781  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
12-01 21:56:20.781  5541  5587 I jxcore-log: 
12-01 21:56:20.782  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
12-01 21:56:20.782  5541  5587 I jxcore-log: 
,12-01 21:56:20.782  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
12-01 21:56:20.782  5541  5587 I jxcore-log: 
12-01 21:56:20.783  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
12-01 21:56:20.783  5541  5587 I jxcore-log: 
,12-01 21:56:20.783  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
12-01 21:56:20.783  5541  5587 I jxcore-log: 
12-01 21:56:20.783  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
12-01 21:56:20.783  5541  5587 I jxcore-log: 
,12-01 21:56:20.784  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
12-01 21:56:20.784  5541  5587 I jxcore-log: 
,12-01 21:56:20.785  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
12-01 21:56:20.785  5541  5587 I jxcore-log: 
12-01 21:56:20.785  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
12-01 21:56:20.785  5541  5587 I jxcore-log: 
,12-01 21:56:20.786  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
12-01 21:56:20.786  5541  5587 I jxcore-log: 
12-01 21:56:20.786  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
12-01 21:56:20.786  5541  5587 I jxcore-log: 
,12-01 21:56:20.786  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
12-01 21:56:20.786  5541  5587 I jxcore-log: 
12-01 21:56:20.787  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
12-01 21:56:20.787  5541  5587 I jxcore-log: 
,12-01 21:56:20.787  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
12-01 21:56:20.787  5541  5587 I jxcore-log: 
12-01 21:56:20.788  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
12-01 21:56:20.788  5541  5587 I jxcore-log: 
,12-01 21:56:20.788  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
12-01 21:56:20.788  5541  5587 I jxcore-log: 
12-01 21:56:20.789  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
12-01 21:56:20.789  5541  5587 I jxcore-log: 
,12-01 21:56:20.789  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
12-01 21:56:20.789  5541  5587 I jxcore-log: 
12-01 21:56:20.790  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
12-01 21:56:20.790  5541  5587 I jxcore-log: 
,12-01 21:56:20.790  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
12-01 21:56:20.790  5541  5587 I jxcore-log: 
12-01 21:56:20.790  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
12-01 21:56:20.790  5541  5587 I jxcore-log: 
,12-01 21:56:20.791  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
12-01 21:56:20.791  5541  5587 I jxcore-log: 
12-01 21:56:20.791  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
12-01 21:56:20.791  5541  5587 I jxcore-log: 
,12-01 21:56:20.792  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
12-01 21:56:20.792  5541  5587 I jxcore-log: 
12-01 21:56:20.792  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
12-01 21:56:20.792  5541  5587 I jxcore-log: 
,12-01 21:56:20.792  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
12-01 21:56:20.792  5541  5587 I jxcore-log: 
12-01 21:56:20.793  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
12-01 21:56:20.793  5541  5587 I jxcore-log: 
12-01 21:56:20.793  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
12-01 21:56:20.793  5541  5587 I jxcore-log: 
,12-01 21:56:20.794  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
12-01 21:56:20.794  5541  5587 I jxcore-log: 
12-01 21:56:20.794  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
12-01 21:56:20.794  5541  5587 I jxcore-log: 
12-01 21:56:20.795  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
12-01 21:56:20.795  5541  5587 I jxcore-log: 
12-01 21:56:20.795  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
12-01 21:56:20.795  5541  5587 I jxcore-log: 
,12-01 21:56:20.795  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
12-01 21:56:20.795  5541  5587 I jxcore-log: 
,12-01 21:56:20.797  5541  5587 I jxcore-log: ok 28 native server is nulled out
12-01 21:56:20.797  5541  5587 I jxcore-log: 
,12-01 21:56:20.798  5541  5587 I jxcore-log: ok 29 native server should be closed
12-01 21:56:20.798  5541  5587 I jxcore-log: 
12-01 21:56:20.798  5541  5587 I jxcore-log: ok 30 incoming has been removed
12-01 21:56:20.798  5541  5587 I jxcore-log: 
,12-01 21:56:20.799  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
12-01 21:56:20.799  5541  5587 I jxcore-log: 
12-01 21:56:20.799  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
12-01 21:56:20.799  5541  5587 I jxcore-log: 
,12-01 21:56:20.799  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
12-01 21:56:20.799  5541  5587 I jxcore-log: 
12-01 21:56:20.800  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
12-01 21:56:20.800  5541  5587 I jxcore-log: 
12-01 21:56:20.800  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
12-01 21:56:20.800  5541  5587 I jxcore-log: 
,12-01 21:56:20.800  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
12-01 21:56:20.800  5541  5587 I jxcore-log: 
12-01 21:56:20.801  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
12-01 21:56:20.801  5541  5587 I jxcore-log: 
12-01 21:56:20.801  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
12-01 21:56:20.801  5541  5587 I jxcore-log: 
12-01 21:56:20.801  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
12-01 21:56:20.801  5541  5587 I jxcore-log: 
12-01 21:56:20.801  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
12-01 21:56:20.801  5541  5587 I jxcore-log: 
,12-01 21:56:20.845  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
12-01 21:56:20.845  5541  5587 I jxcore-log: 
,12-01 21:56:20.845  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
12-01 21:56:20.845  5541  5587 I jxcore-log: 
12-01 21:56:20.846  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
12-01 21:56:20.846  5541  5587 I jxcore-log: 
12-01 21:56:20.846  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
12-01 21:56:20.846  5541  5587 I jxcore-log: 
,12-01 21:56:20.846  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
12-01 21:56:20.846  5541  5587 I jxcore-log: 
,12-01 21:56:20.847  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
12-01 21:56:20.847  5541  5587 I jxcore-log: 
12-01 21:56:20.847  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
12-01 21:56:20.847  5541  5587 I jxcore-log: 
12-01 21:56:20.847  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
12-01 21:56:20.847  5541  5587 I jxcore-log: 
12-01 21:56:20.847  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
12-01 21:56:20.847  5541  5587 I jxcore-log: 
,12-01 21:56:20.847  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
12-01 21:56:20.847  5541  5587 I jxcore-log: 
12-01 21:56:20.848  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
12-01 21:56:20.848  5541  5587 I jxcore-log: 
12-01 21:56:20.848  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
12-01 21:56:20.848  5541  5587 I jxcore-log: 
12-01 21:56:20.848  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
12-01 21:56:20.848  5541  5587 I jxcore-log: 
12-01 21:56:20.848  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
12-01 21:56:20.848  5541  5587 I jxcore-log: 
12-01 21:56:20.848  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
12-01 21:56:20.848  5541  5587 I jxcore-log: 
,12-01 21:56:20.848  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
12-01 21:56:20.848  5541  5587 I jxcore-log: 
12-01 21:56:20.849  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
12-01 21:56:20.849  5541  5587 I jxcore-log: 
,12-01 21:56:20.849  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
12-01 21:56:20.849  5541  5587 I jxcore-log: 
,12-01 21:56:20.849  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
12-01 21:56:20.849  5541  5587 I jxcore-log: 
12-01 21:56:20.849  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
12-01 21:56:20.849  5541  5587 I jxcore-log: 
12-01 21:56:20.849  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
12-01 21:56:20.849  5541  5587 I jxcore-log: 
,12-01 21:56:20.850  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
12-01 21:56:20.850  5541  5587 I jxcore-log: 
12-01 21:56:20.850  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
12-01 21:56:20.850  5541  5587 I jxcore-log: 
12-01 21:56:20.850  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
12-01 21:56:20.850  5541  5587 I jxcore-log: 
,12-01 21:56:20.850  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
12-01 21:56:20.850  5541  5587 I jxcore-log: 
12-01 21:56:20.850  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
12-01 21:56:20.850  5541  5587 I jxcore-log: 
12-01 21:56:20.850  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
12-01 21:56:20.850  5541  5587 I jxcore-log: 
12-01 21:56:20.851  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
12-01 21:56:20.851  5541  5587 I jxcore-log: 
12-01 21:56:20.851  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
12-01 21:56:20.851  5541  5587 I jxcore-log: 
12-01 21:56:20.851  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
12-01 21:56:20.851  5541  5587 I jxcore-log: 
12-01 21:56:20.851  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
12-01 21:56:20.851  5541  5587 I jxcore-log: 
12-01 21:56:20.851  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
12-01 21:56:20.851  5541  5587 I jxcore-log: 
12-01 21:56:20.852  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
12-01 21:56:20.852  5541  5587 I jxcore-log: 
12-01 21:56:20.854  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
12-01 21:56:20.854  5541  5587 I jxcore-log: 
12-01 21:56:20.855  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
12-01 21:56:20.855  5541  5587 I jxcore-log: 
12-01 21:56:20.855  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
12-01 21:56:20.855  5541  5587 I jxcore-log: 
12-01 21:56:20.855  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
12-01 21:56:20.855  5541  5587 I jxcore-log: 
12-01 21:56:20.855  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
12-01 21:56:20.855  5541  5587 I jxcore-log: 
12-01 21:56:20.856  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
12-01 21:56:20.856  5541  5587 I jxcore-log: 
12-01 21:56:20.856  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
12-01 21:56:20.856  5541  5587 I jxcore-log: 
12-01 21:56:20.885  5541  5587 I jxcore-log: # teardown
12-01 21:56:20.885  5541  5587 I jxcore-log: 
,12-01 21:56:20.900  5541  5587 I jxcore-log: 2016-12-01 20:56:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:20.900  5541  5587 I jxcore-log: 
12-01 21:56:20.906  5541  5587 I jxcore-log: # setup
12-01 21:56:20.906  5541  5587 I jxcore-log: 
,12-01 21:56:22.737  5541  5587 I jxcore-log: # native server - simulate mux failure, make sure everything is cleaned up
12-01 21:56:22.737  5541  5587 I jxcore-log: 
,12-01 21:56:22.810  5541  5587 I jxcore-log: 2016-12-01 20:56:22 - DEBUG createNativeListener: 'Creating Native Server'
12-01 21:56:22.810  5541  5587 I jxcore-log: 
,12-01 21:56:22.816  5541  5587 I jxcore-log: 2016-12-01 20:56:22 - DEBUG createNativeListener: 'listening 42930'
12-01 21:56:22.816  5541  5587 I jxcore-log: 
,12-01 21:56:22.824  5541  5587 I jxcore-log: 2016-12-01 20:56:22 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
12-01 21:56:22.824  5541  5587 I jxcore-log: 
,12-01 21:56:22.826  5541  5587 I jxcore-log: 2016-12-01 20:56:22 - DEBUG createNativeListener: 'Native Server - Creating Mux'
12-01 21:56:22.826  5541  5587 I jxcore-log: 
,12-01 21:56:22.838  5541  5587 I jxcore-log: ok 31 we should not have gotten an error
12-01 21:56:22.838  5541  5587 I jxcore-log: 
,12-01 21:56:22.843  5541  5587 I jxcore-log: 2016-12-01 20:56:22 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
12-01 21:56:22.843  5541  5587 I jxcore-log: 
,12-01 21:56:22.852  5541  5587 I jxcore-log: ok 32 Buffers are identical
12-01 21:56:22.852  5541  5587 I jxcore-log: 
,12-01 21:56:22.853  5541  5587 I jxcore-log: 2016-12-01 20:56:22 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
12-01 21:56:22.853  5541  5587 I jxcore-log: 
,12-01 21:56:22.855  5541  5587 I jxcore-log: 2016-12-01 20:56:22 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
12-01 21:56:22.855  5541  5587 I jxcore-log: 
,12-01 21:56:22.865  5541  5587 I jxcore-log: 2016-12-01 20:56:22 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
12-01 21:56:22.865  5541  5587 I jxcore-log: 
,12-01 21:56:22.866  5541  5587 I jxcore-log: ok 33 server should be fine
12-01 21:56:22.866  5541  5587 I jxcore-log: 
12-01 21:56:22.866  5541  5587 I jxcore-log: ok 34 server should be open
12-01 21:56:22.866  5541  5587 I jxcore-log: 
,12-01 21:56:22.867  5541  5587 I jxcore-log: ok 35 incoming has been removed
12-01 21:56:22.867  5541  5587 I jxcore-log: 
12-01 21:56:22.867  5541  5587 I jxcore-log: ok 36 The mux object should be closed
12-01 21:56:22.867  5541  5587 I jxcore-log: 
12-01 21:56:22.867  5541  5587 I jxcore-log: ok 37 The mux stream should be closed
12-01 21:56:22.867  5541  5587 I jxcore-log: 
,12-01 21:56:22.871  5541  5587 I jxcore-log: 2016-12-01 20:56:22 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
12-01 21:56:22.871  5541  5587 I jxcore-log: 
,12-01 21:56:22.873  5541  5587 I jxcore-log: # teardown
12-01 21:56:22.873  5541  5587 I jxcore-log: 
,12-01 21:56:22.922  5541  5587 I jxcore-log: 2016-12-01 20:56:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:22.922  5541  5587 I jxcore-log: 
,12-01 21:56:22.924  5541  5587 I jxcore-log: 2016-12-01 20:56:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:22.924  5541  5587 I jxcore-log: 
,12-01 21:56:22.925  5541  5587 I jxcore-log: 2016-12-01 20:56:22 - DEBUG createNativeListener: 'Native Server - close'
12-01 21:56:22.925  5541  5587 I jxcore-log: 
,12-01 21:56:22.932  5541  5587 I jxcore-log: # setup
12-01 21:56:22.932  5541  5587 I jxcore-log: 
,12-01 21:56:22.995  5541  5587 I jxcore-log: # native server - timing out the incoming connection cleans everything up
12-01 21:56:22.995  5541  5587 I jxcore-log: 
,12-01 21:56:23.055  5541  5587 I jxcore-log: 2016-12-01 20:56:23 - DEBUG createNativeListener: 'Creating Native Server'
12-01 21:56:23.055  5541  5587 I jxcore-log: 
,12-01 21:56:23.062  5541  5587 I jxcore-log: 2016-12-01 20:56:23 - DEBUG createNativeListener: 'listening 46813'
12-01 21:56:23.062  5541  5587 I jxcore-log: 
,12-01 21:56:23.069  5541  5587 I jxcore-log: 2016-12-01 20:56:23 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
12-01 21:56:23.069  5541  5587 I jxcore-log: 
,12-01 21:56:23.071  5541  5587 I jxcore-log: 2016-12-01 20:56:23 - DEBUG createNativeListener: 'Native Server - Creating Mux'
12-01 21:56:23.071  5541  5587 I jxcore-log: 
,12-01 21:56:23.079  5541  5587 I jxcore-log: ok 38 we should not have gotten an error
12-01 21:56:23.079  5541  5587 I jxcore-log: 
,12-01 21:56:23.083  5541  5587 I jxcore-log: 2016-12-01 20:56:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
12-01 21:56:23.083  5541  5587 I jxcore-log: 
,12-01 21:56:23.093  5541  5587 I jxcore-log: ok 39 Buffers are identical
12-01 21:56:23.093  5541  5587 I jxcore-log: 
,12-01 21:56:23.098  5541  5587 I jxcore-log: 2016-12-01 20:56:23 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
12-01 21:56:23.098  5541  5587 I jxcore-log: 
,12-01 21:56:23.099  5541  5587 I jxcore-log: 2016-12-01 20:56:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
12-01 21:56:23.099  5541  5587 I jxcore-log: 
,12-01 21:56:23.103  5541  5587 I jxcore-log: 2016-12-01 20:56:23 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
12-01 21:56:23.103  5541  5587 I jxcore-log: 
,12-01 21:56:23.107  5541  5587 I jxcore-log: 2016-12-01 20:56:23 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
12-01 21:56:23.107  5541  5587 I jxcore-log: 
,12-01 21:56:23.108  5541  5587 I jxcore-log: ok 40 server should be fine
12-01 21:56:23.108  5541  5587 I jxcore-log: 
12-01 21:56:23.109  5541  5587 I jxcore-log: ok 41 server should be open
12-01 21:56:23.109  5541  5587 I jxcore-log: 
12-01 21:56:23.109  5541  5587 I jxcore-log: ok 42 incoming has been removed
12-01 21:56:23.109  5541  5587 I jxcore-log: 
,12-01 21:56:23.109  5541  5587 I jxcore-log: ok 43 The mux object should be closed
12-01 21:56:23.109  5541  5587 I jxcore-log: 
12-01 21:56:23.109  5541  5587 I jxcore-log: ok 44 The mux stream should be closed
12-01 21:56:23.109  5541  5587 I jxcore-log: 
,12-01 21:56:23.115  5541  5587 I jxcore-log: # teardown
12-01 21:56:23.115  5541  5587 I jxcore-log: 
,12-01 21:56:23.120  5541  5587 I jxcore-log: 2016-12-01 20:56:23 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
12-01 21:56:23.120  5541  5587 I jxcore-log: 
,12-01 21:56:23.132  5541  5587 I jxcore-log: 2016-12-01 20:56:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:23.132  5541  5587 I jxcore-log: 
,12-01 21:56:23.134  5541  5587 I jxcore-log: 2016-12-01 20:56:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:23.134  5541  5587 I jxcore-log: 
,12-01 21:56:23.136  5541  5587 I jxcore-log: 2016-12-01 20:56:23 - DEBUG createNativeListener: 'Native Server - close'
12-01 21:56:23.136  5541  5587 I jxcore-log: 
,12-01 21:56:23.142  5541  5587 I jxcore-log: # setup
12-01 21:56:23.142  5541  5587 I jxcore-log: 
,12-01 21:56:23.195  5541  5587 I jxcore-log: # #_doImmediateSeqUpdate - server is not there
12-01 21:56:23.195  5541  5587 I jxcore-log: 
,12-01 21:56:23.251  5541  5587 I jxcore-log: 2016-12-01 20:56:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:23.251  5541  5587 I jxcore-log: 
,12-01 21:56:23.377  5541  5587 I jxcore-log: 2016-12-01 20:56:23 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
12-01 21:56:23.377  5541  5587 I jxcore-log: 
,12-01 21:56:23.378  5541  5587 I jxcore-log: ok 45 Got right error
12-01 21:56:23.378  5541  5587 I jxcore-log: 
,12-01 21:56:23.383  5541  5587 I jxcore-log: # teardown
12-01 21:56:23.383  5541  5587 I jxcore-log: 
,12-01 21:56:23.397  5541  5587 I jxcore-log: 2016-12-01 20:56:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:23.397  5541  5587 I jxcore-log: 
,12-01 21:56:23.401  5541  5587 I jxcore-log: # setup
12-01 21:56:23.401  5541  5587 I jxcore-log: 
,12-01 21:56:23.435  5541  5587 I jxcore-log: # #_doImmediateSeqUpdate - server accepts & closes connection
12-01 21:56:23.435  5541  5587 I jxcore-log: 
,12-01 21:56:23.543  5541  5587 I jxcore-log: 2016-12-01 20:56:23 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
12-01 21:56:23.543  5541  5587 I jxcore-log: 
,12-01 21:56:23.545  5541  5587 I jxcore-log: ok 46 Got socket hang up
12-01 21:56:23.545  5541  5587 I jxcore-log: 
,12-01 21:56:23.551  5541  5587 I jxcore-log: # teardown
12-01 21:56:23.551  5541  5587 I jxcore-log: 
,12-01 21:56:23.595  5541  5587 I jxcore-log: 2016-12-01 20:56:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:23.595  5541  5587 I jxcore-log: 
,12-01 21:56:23.615  5541  5587 I jxcore-log: # setup
12-01 21:56:23.615  5541  5587 I jxcore-log: 
,12-01 21:56:23.670  5541  5587 I jxcore-log: # #_doImmediateSeqUpdate - server always returns 500
12-01 21:56:23.670  5541  5587 I jxcore-log: 
,12-01 21:56:23.884  5541  5587 I jxcore-log: 2016-12-01 20:56:23 - DEBUG localSeqManager: 'Got an error trying to update seq []'
12-01 21:56:23.884  5541  5587 I jxcore-log: 
,12-01 21:56:23.885  5541  5587 I jxcore-log: ok 47 Got 500 as expected
12-01 21:56:23.885  5541  5587 I jxcore-log: 
,12-01 21:56:23.889  5541  5587 I jxcore-log: # teardown
12-01 21:56:23.889  5541  5587 I jxcore-log: 
,12-01 21:56:23.944  5541  5587 I jxcore-log: 2016-12-01 20:56:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:23.944  5541  5587 I jxcore-log: 
,12-01 21:56:23.968  5541  5587 I jxcore-log: # setup
12-01 21:56:23.968  5541  5587 I jxcore-log: 
,12-01 21:56:24.038  5541  5587 I jxcore-log: # #_doImmediateSeqUpdate - create new seq doc
12-01 21:56:24.038  5541  5587 I jxcore-log: 
,12-01 21:56:25.920  5541  5587 I jxcore-log: ok 48 should be equal
12-01 21:56:25.920  5541  5587 I jxcore-log: 
,12-01 21:56:25.921  5541  5587 I jxcore-log: ok 49 revs are equal
12-01 21:56:25.921  5541  5587 I jxcore-log: 
,12-01 21:56:25.933  5541  5587 I jxcore-log: # teardown
12-01 21:56:25.933  5541  5587 I jxcore-log: 
,12-01 21:56:25.962  5541  5587 I jxcore-log: 2016-12-01 20:56:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:25.962  5541  5587 I jxcore-log: 
,12-01 21:56:25.986  5541  5587 I jxcore-log: # setup
12-01 21:56:25.986  5541  5587 I jxcore-log: 
,12-01 21:56:26.194  5541  5587 I jxcore-log: # #_doImmediateSeqUpdate - doc exists, need to get rev and update
12-01 21:56:26.194  5541  5587 I jxcore-log: 
,12-01 21:56:26.919  5541  5587 I jxcore-log: ok 50 should be equal
12-01 21:56:26.919  5541  5587 I jxcore-log: 
,12-01 21:56:26.919  5541  5587 I jxcore-log: ok 51 revs are equal
12-01 21:56:26.919  5541  5587 I jxcore-log: 
,12-01 21:56:26.923  5541  5587 I jxcore-log: # teardown
12-01 21:56:26.923  5541  5587 I jxcore-log: 
,12-01 21:56:27.057  5541  5587 I jxcore-log: 2016-12-01 20:56:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:27.057  5541  5587 I jxcore-log: 
,12-01 21:56:27.092  5541  5587 I jxcore-log: # setup
12-01 21:56:27.092  5541  5587 I jxcore-log: 
,12-01 21:56:27.108  5541  5587 I jxcore-log: # #_doImmediateSeqUpdate - update seq three times
12-01 21:56:27.108  5541  5587 I jxcore-log: 
,12-01 21:56:27.735  5541  5587 I jxcore-log: ok 52 should be equal
12-01 21:56:27.735  5541  5587 I jxcore-log: 
,12-01 21:56:27.735  5541  5587 I jxcore-log: ok 53 revs are equal
12-01 21:56:27.735  5541  5587 I jxcore-log: 
,12-01 21:56:27.900  5541  5587 I jxcore-log: ok 54 should be equal
12-01 21:56:27.900  5541  5587 I jxcore-log: 
,12-01 21:56:27.900  5541  5587 I jxcore-log: ok 55 revs are equal
12-01 21:56:27.900  5541  5587 I jxcore-log: 
,12-01 21:56:28.086  5541  5587 I jxcore-log: ok 56 should be equal
12-01 21:56:28.086  5541  5587 I jxcore-log: 
,12-01 21:56:28.087  5541  5587 I jxcore-log: ok 57 revs are equal
12-01 21:56:28.087  5541  5587 I jxcore-log: 
,12-01 21:56:28.098  5541  5587 I jxcore-log: # teardown
12-01 21:56:28.098  5541  5587 I jxcore-log: 
,12-01 21:56:28.772  5541  5587 I jxcore-log: 2016-12-01 20:56:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:28.772  5541  5587 I jxcore-log: 
,12-01 21:56:28.809  5541  5587 I jxcore-log: # setup
12-01 21:56:28.809  5541  5587 I jxcore-log: 
,12-01 21:56:29.197  5541  5587 I jxcore-log: # #_doImmediateSeqUpdate - rev got changed under us
12-01 21:56:29.197  5541  5587 I jxcore-log: 
,12-01 21:56:30.012  5541  5587 I jxcore-log: 2016-12-01 20:56:30 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
12-01 21:56:30.012  5541  5587 I jxcore-log: 
,12-01 21:56:30.014  5541  5587 I jxcore-log: ok 58 Our rev is old so we should fail
12-01 21:56:30.014  5541  5587 I jxcore-log: 
,12-01 21:56:30.036  5541  5587 I jxcore-log: # teardown
12-01 21:56:30.036  5541  5587 I jxcore-log: 
,12-01 21:56:30.058  5541  5587 I jxcore-log: 2016-12-01 20:56:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:30.058  5541  5587 I jxcore-log: 
,12-01 21:56:30.076  5541  5587 I jxcore-log: # setup
12-01 21:56:30.076  5541  5587 I jxcore-log: 
,12-01 21:56:30.153  5541  5587 I jxcore-log: # #_doImmediateSeqUpdate - fail if stop is called
12-01 21:56:30.153  5541  5587 I jxcore-log: 
,12-01 21:56:30.253  5541  5587 I jxcore-log: ok 59 confirm stop caused failure
12-01 21:56:30.253  5541  5587 I jxcore-log: 
,12-01 21:56:30.266  5541  5587 I jxcore-log: # teardown
12-01 21:56:30.266  5541  5587 I jxcore-log: 
,12-01 21:56:30.285  5541  5587 I jxcore-log: 2016-12-01 20:56:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:30.285  5541  5587 I jxcore-log: 
,12-01 21:56:30.292  5541  5587 I jxcore-log: # setup
12-01 21:56:30.292  5541  5587 I jxcore-log: 
,12-01 21:56:30.367  5541  5587 I jxcore-log: # #_doImmediateSeqUpdate - stop after get but before put fails right
12-01 21:56:30.367  5541  5587 I jxcore-log: 
,12-01 21:56:30.822  5541  5587 I jxcore-log: 2016-12-01 20:56:30 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
12-01 21:56:30.822  5541  5587 I jxcore-log: 
12-01 21:56:30.823  5541  5587 I jxcore-log: ok 60 stop caused us to fail
12-01 21:56:30.823  5541  5587 I jxcore-log: 
12-01 21:56:30.824  5541  5587 I jxcore-log: ok 61 We specifically failed on a stop before put
12-01 21:56:30.824  5541  5587 I jxcore-log: 
,12-01 21:56:30.838  5541  5587 I jxcore-log: # teardown
12-01 21:56:30.838  5541  5587 I jxcore-log: 
,12-01 21:56:30.861  5541  5587 I jxcore-log: 2016-12-01 20:56:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:30.861  5541  5587 I jxcore-log: 
,12-01 21:56:30.874  5541  5587 I jxcore-log: # setup
12-01 21:56:30.874  5541  5587 I jxcore-log: 
,12-01 21:56:30.914  5541  5587 I jxcore-log: # #update - fail if stop is called
12-01 21:56:30.914  5541  5587 I jxcore-log: 
,12-01 21:56:31.002  5541  5587 I jxcore-log: ok 62 failed due to stop
12-01 21:56:31.002  5541  5587 I jxcore-log: 
,12-01 21:56:31.003  5541  5587 I jxcore-log: ok 63 failed due to stop
12-01 21:56:31.003  5541  5587 I jxcore-log: 
,12-01 21:56:31.013  5541  5587 I jxcore-log: # teardown
12-01 21:56:31.013  5541  5587 I jxcore-log: 
,12-01 21:56:31.042  5541  5587 I jxcore-log: 2016-12-01 20:56:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:31.042  5541  5587 I jxcore-log: 
,12-01 21:56:31.048  5541  5587 I jxcore-log: # setup
12-01 21:56:31.048  5541  5587 I jxcore-log: 
,12-01 21:56:31.089  5541  5587 I jxcore-log: # #update - set seq for first time
12-01 21:56:31.089  5541  5587 I jxcore-log: 
,12-01 21:56:31.772  5541  5587 I jxcore-log: ok 64 should be equal
12-01 21:56:31.772  5541  5587 I jxcore-log: 
,12-01 21:56:31.797  5541  5587 I jxcore-log: # teardown
12-01 21:56:31.797  5541  5587 I jxcore-log: 
,12-01 21:56:31.821  5541  5587 I jxcore-log: 2016-12-01 20:56:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:31.821  5541  5587 I jxcore-log: 
,12-01 21:56:31.844  5541  5587 I jxcore-log: # setup
12-01 21:56:31.844  5541  5587 I jxcore-log: 
,12-01 21:56:31.893  5541  5587 I jxcore-log: # #update - Fail on bad seq value
12-01 21:56:31.893  5541  5587 I jxcore-log: 
,12-01 21:56:32.459  5541  5587 I jxcore-log: 2016-12-01 20:56:32 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
12-01 21:56:32.459  5541  5587 I jxcore-log: 
,12-01 21:56:32.461  5541  5587 I jxcore-log: ok 65 Expected bad seq error
12-01 21:56:32.461  5541  5587 I jxcore-log: 
,12-01 21:56:32.480  5541  5587 I jxcore-log: # teardown
12-01 21:56:32.480  5541  5587 I jxcore-log: 
,12-01 21:56:32.537  5541  5587 I jxcore-log: 2016-12-01 20:56:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:32.537  5541  5587 I jxcore-log: 
,12-01 21:56:32.556  5541  5587 I jxcore-log: # setup
12-01 21:56:32.556  5541  5587 I jxcore-log: 
,12-01 21:56:32.605  5541  5587 I jxcore-log: # #update - do we cancel timer properly on an immediate?
12-01 21:56:32.605  5541  5587 I jxcore-log: 
,12-01 21:56:32.741  5541  5587 E jxcore-log: (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
12-01 21:56:32.741  5541  5587 E jxcore-log: 
,12-01 21:56:32.746  5541  5587 E jxcore-log: Trace: 
12-01 21:56:32.746  5541  5587 E jxcore-log:     at $3.prototype.trace@console.js:139:8
12-01 21:56:32.746  5541  5587 E jxcore-log:     at addListener@events.js:140:1
12-01 21:56:32.746  5541  5587 E jxcore-log:     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:82:3
12-01 21:56:32.746  5541  5587 E jxcore-log:     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
12-01 21:56:32.746  5541  5587 E jxcore-log:     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
12-01 21:56:32.746  5541  5587 E jxcore-log:     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
12-01 21:56:32.746  5541  5587 E jxcore-log: 
,12-01 21:56:33.210  5541  5587 I jxcore-log: ok 66 Different promises
12-01 21:56:33.210  5541  5587 I jxcore-log: 
,12-01 21:56:33.213  5541  5587 I jxcore-log: ok 67 Timer was cancelled
12-01 21:56:33.213  5541  5587 I jxcore-log: 
,12-01 21:56:33.441  5541  5587 I jxcore-log: ok 68 should be equal
12-01 21:56:33.441  5541  5587 I jxcore-log: 
,12-01 21:56:33.470  5541  5587 I jxcore-log: # teardown
12-01 21:56:33.470  5541  5587 I jxcore-log: 
,12-01 21:56:33.484  5541  5587 I jxcore-log: 2016-12-01 20:56:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:33.484  5541  5587 I jxcore-log: 
,12-01 21:56:33.507  5541  5587 I jxcore-log: # setup
12-01 21:56:33.507  5541  5587 I jxcore-log: 
,12-01 21:56:33.569  5541  5587 I jxcore-log: # #update - do we wait for blocked update
12-01 21:56:33.569  5541  5587 I jxcore-log: 
,12-01 21:56:33.676  5541  5587 I jxcore-log: ok 69 One go and one blocked
12-01 21:56:33.676  5541  5587 I jxcore-log: 
,12-01 21:56:33.677  5541  5587 I jxcore-log: ok 70 All blocked
12-01 21:56:33.677  5541  5587 I jxcore-log: 
12-01 21:56:33.678  5541  5587 I jxcore-log: ok 71 Still blocked
12-01 21:56:33.678  5541  5587 I jxcore-log: 
,12-01 21:56:33.693  5541  5587 E jxcore-log: (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
12-01 21:56:33.693  5541  5587 E jxcore-log: 
,12-01 21:56:33.696  5541  5587 E jxcore-log: Trace: 
12-01 21:56:33.696  5541  5587 E jxcore-log:     at $3.prototype.trace@console.js:139:8
12-01 21:56:33.696  5541  5587 E jxcore-log:     at addListener@events.js:140:1
12-01 21:56:33.696  5541  5587 E jxcore-log:     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:57:3
12-01 21:56:33.696  5541  5587 E jxcore-log:     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
12-01 21:56:33.696  5541  5587 E jxcore-log:     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
12-01 21:56:33.696  5541  5587 E jxcore-log:     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
12-01 21:56:33.696  5541  5587 E jxcore-log: 
,12-01 21:56:33.773   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:56:34.352  5541  5587 I jxcore-log: ok 72 should be equal
12-01 21:56:34.352  5541  5587 I jxcore-log: 
,12-01 21:56:34.389  5541  5587 I jxcore-log: # teardown
12-01 21:56:34.389  5541  5587 I jxcore-log: 
,12-01 21:56:34.774   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:56:35.440  5541  5587 I jxcore-log: 2016-12-01 20:56:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:35.440  5541  5587 I jxcore-log: 
,12-01 21:56:35.472  5541  5587 I jxcore-log: # setup
12-01 21:56:35.472  5541  5587 I jxcore-log: 
,12-01 21:56:35.491  5541  5587 I jxcore-log: # #update - test that we wait long enough
12-01 21:56:35.491  5541  5587 I jxcore-log: 
,12-01 21:56:35.775   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:56:36.021   928  2959 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,12-01 21:56:36.776   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:56:37.382  5541  5587 I jxcore-log: ok 73 We waited long enough
12-01 21:56:37.382  5541  5587 I jxcore-log: 
,12-01 21:56:37.591  5541  5587 I jxcore-log: ok 74 should be equal
12-01 21:56:37.591  5541  5587 I jxcore-log: 
,12-01 21:56:37.621  5541  5587 I jxcore-log: # teardown
12-01 21:56:37.621  5541  5587 I jxcore-log: 
,12-01 21:56:37.734  5541  5587 I jxcore-log: 2016-12-01 20:56:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:37.734  5541  5587 I jxcore-log: 
,12-01 21:56:37.769  5541  5587 I jxcore-log: # setup
12-01 21:56:37.769  5541  5587 I jxcore-log: 
,12-01 21:56:37.776   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:56:37.789  5541  5587 I jxcore-log: # #update - test that we pick up new sequences while we wait
12-01 21:56:37.789  5541  5587 I jxcore-log: 
,12-01 21:56:38.395  5541  5587 I jxcore-log: ok 75 Should have gotten same timer promise
12-01 21:56:38.395  5541  5587 I jxcore-log: 
,12-01 21:56:38.395  5541  5587 I jxcore-log: ok 76 Still same timer promise
12-01 21:56:38.395  5541  5587 I jxcore-log: 
,12-01 21:56:38.777   533   533 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,12-01 21:56:38.996  5541  5587 I jxcore-log: ok 77 We waited long enough
12-01 21:56:38.996  5541  5587 I jxcore-log: 
,12-01 21:56:39.127  5541  5587 I jxcore-log: ok 78 should be equal
12-01 21:56:39.127  5541  5587 I jxcore-log: 
,12-01 21:56:39.199  5541  5587 I jxcore-log: # teardown
12-01 21:56:39.199  5541  5587 I jxcore-log: 
,12-01 21:56:40.240  5541  5587 I jxcore-log: 2016-12-01 20:56:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
12-01 21:56:40.240  5541  5587 I jxcore-log: 
,12-01 21:56:40.279  5541  5587 I jxcore-log: # setup
12-01 21:56:40.279  5541  5587 I jxcore-log: 
,12-01 21:56:40.529  5541  5587 I jxcore-log: # Coordinated seq test
12-01 21:56:40.529  5541  5587 I jxcore-log: 
,12-01 21:56:40.858  5541  5587 I jxcore-log: 2016-12-01 20:56:40 - DEBUG thaliWifiInfrastructure: 'listening 45519'
12-01 21:56:40.858  5541  5587 I jxcore-log: 
,12-01 21:56:40.939  5541  5587 I jxcore-log: 2016-12-01 20:56:40 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:56:40.939  5541  5587 I jxcore-log: 
,12-01 21:56:40.944  5541  5587 I jxcore-log: 2016-12-01 20:56:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810,"connectionType":"tcp","suggestedTCPTimeout":1000}'
12-01 21:56:40.944  5541  5587 I jxcore-log: 
,12-01 21:56:40.976  5541  5587 I jxcore-log: 2016-12-01 20:56:40 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:56:40.976  5541  5587 I jxcore-log: 
,12-01 21:56:40.978  5541  5587 I jxcore-log: 2016-12-01 20:56:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386,"connectionType":"tcp","suggestedTCPTimeout":1000}'
12-01 21:56:40.978  5541  5587 I jxcore-log: 
,12-01 21:56:41.448  5541  5587 I jxcore-log: 2016-12-01 20:56:41 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:56:41.448  5541  5587 I jxcore-log: 
,12-01 21:56:41.962  5541  5587 I jxcore-log: 2016-12-01 20:56:41 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:56:41.962  5541  5587 I jxcore-log: 
,12-01 21:56:42.828  5541  5587 I jxcore-log: ok 79 should be equal
12-01 21:56:42.828  5541  5587 I jxcore-log: 
,12-01 21:56:42.990  5541  5587 I jxcore-log: 2016-12-01 20:56:42 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:56:42.990  5541  5587 I jxcore-log: 
,12-01 21:56:42.999  5541  5587 I jxcore-log: 2016-12-01 20:56:42 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:56:42.999  5541  5587 I jxcore-log: 
,12-01 21:56:43.395  5541  5587 I jxcore-log: ok 80 should be equal
12-01 21:56:43.395  5541  5587 I jxcore-log: 
,12-01 21:56:43.403  5541  5587 I jxcore-log: # teardown
12-01 21:56:43.403  5541  5587 I jxcore-log: 
,12-01 21:56:43.499  5541  5587 I jxcore-log: 2016-12-01 20:56:43 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:56:43.499  5541  5587 I jxcore-log: 
,12-01 21:56:43.910  5541  5587 I jxcore-log: 2016-12-01 20:56:43 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:56:43.910  5541  5587 I jxcore-log: 
,12-01 21:56:44.425  5541  5587 I jxcore-log: 2016-12-01 20:56:44 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:56:44.425  5541  5587 I jxcore-log: 
,12-01 21:56:44.433  5541  5587 I jxcore-log: 2016-12-01 20:56:44 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:56:44.433  5541  5587 I jxcore-log: 
,12-01 21:56:44.934  5541  5587 I jxcore-log: 2016-12-01 20:56:44 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:56:44.934  5541  5587 I jxcore-log: 
,12-01 21:56:46.471  5541  5587 I jxcore-log: 2016-12-01 20:56:46 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:56:46.471  5541  5587 I jxcore-log: 
,12-01 21:56:46.475  5541  5587 I jxcore-log: 2016-12-01 20:56:46 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:56:46.475  5541  5587 I jxcore-log: 
,12-01 21:56:46.982  5541  5587 I jxcore-log: 2016-12-01 20:56:46 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:56:46.982  5541  5587 I jxcore-log: 
,12-01 21:56:46.988  5541  5587 I jxcore-log: 2016-12-01 20:56:46 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:56:46.988  5541  5587 I jxcore-log: 
,12-01 21:56:47.494  5541  5587 I jxcore-log: 2016-12-01 20:56:47 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:56:47.494  5541  5587 I jxcore-log: 
,12-01 21:56:47.498  5541  5587 I jxcore-log: 2016-12-01 20:56:47 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:56:47.498  5541  5587 I jxcore-log: 
,12-01 21:56:48.006  5541  5587 I jxcore-log: 2016-12-01 20:56:48 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:56:48.006  5541  5587 I jxcore-log: 
,12-01 21:56:48.517  5541  5587 I jxcore-log: 2016-12-01 20:56:48 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:56:48.517  5541  5587 I jxcore-log: 
,12-01 21:56:49.029  5541  5587 I jxcore-log: 2016-12-01 20:56:49 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:56:49.029  5541  5587 I jxcore-log: 
,12-01 21:56:49.543  5541  5587 I jxcore-log: 2016-12-01 20:56:49 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:56:49.543  5541  5587 I jxcore-log: 
,12-01 21:56:50.053  5541  5587 I jxcore-log: 2016-12-01 20:56:50 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:56:50.053  5541  5587 I jxcore-log: 
,12-01 21:56:50.566  5541  5587 I jxcore-log: 2016-12-01 20:56:50 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:56:50.566  5541  5587 I jxcore-log: 
,12-01 21:56:51.590  5541  5587 I jxcore-log: 2016-12-01 20:56:51 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:56:51.590  5541  5587 I jxcore-log: 
,12-01 21:56:51.692  5541  5587 I jxcore-log: 2016-12-01 20:56:51 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:56:51.692  5541  5587 I jxcore-log: 
,12-01 21:56:51.998  5541  5587 I jxcore-log: 2016-12-01 20:56:51 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:56:51.998  5541  5587 I jxcore-log: 
,12-01 21:56:53.023  5541  5587 I jxcore-log: 2016-12-01 20:56:53 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:56:53.023  5541  5587 I jxcore-log: 
,12-01 21:56:53.126  5541  5587 I jxcore-log: 2016-12-01 20:56:53 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:56:53.126  5541  5587 I jxcore-log: 
,12-01 21:56:53.741  5541  5587 I jxcore-log: 2016-12-01 20:56:53 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:56:53.741  5541  5587 I jxcore-log: 
,12-01 21:56:54.661  5541  5587 I jxcore-log: 2016-12-01 20:56:54 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:56:54.661  5541  5587 I jxcore-log: 
,12-01 21:56:55.071  5541  5587 I jxcore-log: 2016-12-01 20:56:55 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:56:55.071  5541  5587 I jxcore-log: 
,12-01 21:56:55.584  5541  5587 I jxcore-log: 2016-12-01 20:56:55 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:56:55.584  5541  5587 I jxcore-log: 
,12-01 21:56:56.023   928  2959 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,12-01 21:56:56.232   928  5816 D NetlinkSocketObserver: NeighborEvent{elapsedMs=297170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,12-01 21:56:56.607  5541  5587 I jxcore-log: 2016-12-01 20:56:56 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:56:56.607  5541  5587 I jxcore-log: 
,12-01 21:56:57.056  5541  5587 I jxcore-log: 2016-12-01 20:56:57 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:56:57.056  5541  5587 I jxcore-log: 
,12-01 21:56:57.529  5541  5587 I jxcore-log: 2016-12-01 20:56:57 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:56:57.529  5541  5587 I jxcore-log: 
,12-01 21:56:57.632  5541  5587 I jxcore-log: 2016-12-01 20:56:57 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:56:57.632  5541  5587 I jxcore-log: 
,12-01 21:56:58.143  5541  5587 I jxcore-log: 2016-12-01 20:56:58 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:56:58.143  5541  5587 I jxcore-log: 
,12-01 21:56:58.554  5541  5587 I jxcore-log: 2016-12-01 20:56:58 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:56:58.554  5541  5587 I jxcore-log: 
,12-01 21:56:58.655  5541  5587 I jxcore-log: 2016-12-01 20:56:58 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:56:58.655  5541  5587 I jxcore-log: 
,12-01 21:56:58.778   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:56:59.064  5541  5587 I jxcore-log: 2016-12-01 20:56:59 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:56:59.064  5541  5587 I jxcore-log: 
,12-01 21:56:59.167  5541  5587 I jxcore-log: 2016-12-01 20:56:59 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:56:59.167  5541  5587 I jxcore-log: 
,12-01 21:56:59.679  5541  5587 I jxcore-log: 2016-12-01 20:56:59 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:56:59.679  5541  5587 I jxcore-log: 
,12-01 21:56:59.780   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:57:00.089  5541  5587 I jxcore-log: 2016-12-01 20:57:00 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:00.089  5541  5587 I jxcore-log: 
,12-01 21:57:00.612  5541  5587 I jxcore-log: 2016-12-01 20:57:00 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:00.612  5541  5587 I jxcore-log: 
,12-01 21:57:00.781   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:57:01.728  5541  5587 I jxcore-log: 2016-12-01 20:57:01 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:01.728  5541  5587 I jxcore-log: 
,12-01 21:57:01.733  5541  5587 I jxcore-log: 2016-12-01 20:57:01 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:01.733  5541  5587 I jxcore-log: 
,12-01 21:57:01.783   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:57:02.136  5541  5587 I jxcore-log: 2016-12-01 20:57:02 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:02.136  5541  5587 I jxcore-log: 
,12-01 21:57:02.648  5541  5587 I jxcore-log: 2016-12-01 20:57:02 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:02.648  5541  5587 I jxcore-log: 
,12-01 21:57:02.784   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:57:03.491  5541  5587 I jxcore-log: 2016-12-01 20:57:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":null,"portNumber":null,"connectionType":"tcp","suggestedTCPTimeout":1000}'
12-01 21:57:03.491  5541  5587 I jxcore-log: 
,12-01 21:57:03.585  5541  5587 I jxcore-log: 2016-12-01 20:57:03 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:03.585  5541  5587 I jxcore-log: 
,12-01 21:57:03.672  5541  5587 I jxcore-log: 2016-12-01 20:57:03 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:57:03.672  5541  5587 I jxcore-log: 
,12-01 21:57:03.675  5541  5587 I jxcore-log: 2016-12-01 20:57:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386,"connectionType":"tcp","suggestedTCPTimeout":1000}'
12-01 21:57:03.675  5541  5587 I jxcore-log: 
,12-01 21:57:03.785   533   533 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,12-01 21:57:04.700  5541  5587 I jxcore-log: 2016-12-01 20:57:04 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:57:04.700  5541  5587 I jxcore-log: 
,12-01 21:57:05.106  5541  5587 I jxcore-log: 2016-12-01 20:57:05 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:05.106  5541  5587 I jxcore-log: 
,12-01 21:57:05.211  5541  5587 I jxcore-log: 2016-12-01 20:57:05 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:57:05.211  5541  5587 I jxcore-log: 
,12-01 21:57:05.720  5541  5587 I jxcore-log: 2016-12-01 20:57:05 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:57:05.720  5541  5587 I jxcore-log: 
,12-01 21:57:06.148  5541  5587 I jxcore-log: 2016-12-01 20:57:06 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:06.148  5541  5587 I jxcore-log: 
,12-01 21:57:07.154  5541  5587 I jxcore-log: 2016-12-01 20:57:07 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:07.154  5541  5587 I jxcore-log: 
,12-01 21:57:07.666  5541  5587 I jxcore-log: 2016-12-01 20:57:07 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:07.666  5541  5587 I jxcore-log: 
,12-01 21:57:08.125   928  5816 D NetlinkSocketObserver: NeighborEvent{elapsedMs=309064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,12-01 21:57:08.180  5541  5587 I jxcore-log: 2016-12-01 20:57:08 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:08.180  5541  5587 I jxcore-log: 
,12-01 21:57:08.676  5541  5587 I jxcore-log: 2016-12-01 20:57:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":null,"portNumber":null,"connectionType":"tcp","suggestedTCPTimeout":1000}'
12-01 21:57:08.676  5541  5587 I jxcore-log: 
,12-01 21:57:09.099  5541  5587 I jxcore-log: 2016-12-01 20:57:09 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:09.099  5541  5587 I jxcore-log: 
,12-01 21:57:09.202  5541  5587 I jxcore-log: 2016-12-01 20:57:09 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:57:09.202  5541  5587 I jxcore-log: 
,12-01 21:57:09.208  5541  5587 I jxcore-log: 2016-12-01 20:57:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386,"connectionType":"tcp","suggestedTCPTimeout":1000}'
12-01 21:57:09.208  5541  5587 I jxcore-log: 
,12-01 21:57:09.612  5541  5587 I jxcore-log: 2016-12-01 20:57:09 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:09.612  5541  5587 I jxcore-log: 
,12-01 21:57:09.715  5541  5587 I jxcore-log: 2016-12-01 20:57:09 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:57:09.715  5541  5587 I jxcore-log: 
,12-01 21:57:10.225  5541  5587 I jxcore-log: 2016-12-01 20:57:10 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:57:10.225  5541  5587 I jxcore-log: 
,12-01 21:57:11.660  5541  5587 I jxcore-log: 2016-12-01 20:57:11 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:11.660  5541  5587 I jxcore-log: 
,12-01 21:57:12.170  5541  5587 I jxcore-log: 2016-12-01 20:57:12 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:12.170  5541  5587 I jxcore-log: 
,12-01 21:57:12.274  5541  5587 I jxcore-log: 2016-12-01 20:57:12 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:57:12.274  5541  5587 I jxcore-log: 
,12-01 21:57:12.998   928  2961 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,12-01 21:57:13.197  5541  5587 I jxcore-log: 2016-12-01 20:57:13 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:57:13.197  5541  5587 I jxcore-log: 
,12-01 21:57:15.954  5541  5587 I jxcore-log: 2016-12-01 20:57:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":null,"portNumber":null,"connectionType":"tcp","suggestedTCPTimeout":1000}'
12-01 21:57:15.954  5541  5587 I jxcore-log: 
,12-01 21:57:16.707  5541  5587 I jxcore-log: 2016-12-01 20:57:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":null,"portNumber":null,"connectionType":"tcp","suggestedTCPTimeout":1000}'
12-01 21:57:16.707  5541  5587 I jxcore-log: 
,12-01 21:57:19.053   928  2961 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,12-01 21:57:19.749  5541  5587 I jxcore-log: 2016-12-01 20:57:19 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:57:19.749  5541  5587 I jxcore-log: 
,12-01 21:57:19.751  5541  5587 I jxcore-log: 2016-12-01 20:57:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386,"connectionType":"tcp","suggestedTCPTimeout":1000}'
12-01 21:57:19.751  5541  5587 I jxcore-log: 
,12-01 21:57:20.158  5541  5587 I jxcore-log: 2016-12-01 20:57:20 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:20.158  5541  5587 I jxcore-log: 
12-01 21:57:20.161  5541  5587 I jxcore-log: 2016-12-01 20:57:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810,"connectionType":"tcp","suggestedTCPTimeout":1000}'
12-01 21:57:20.161  5541  5587 I jxcore-log: 
,12-01 21:57:20.670  5541  5587 I jxcore-log: 2016-12-01 20:57:20 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:20.670  5541  5587 I jxcore-log: 
,12-01 21:57:20.773  5541  5587 I jxcore-log: 2016-12-01 20:57:20 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:57:20.773  5541  5587 I jxcore-log: 
,12-01 21:57:21.286  5541  5587 I jxcore-log: 2016-12-01 20:57:21 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:57:21.286  5541  5587 I jxcore-log: 
,12-01 21:57:22.207  5541  5587 I jxcore-log: 2016-12-01 20:57:22 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:22.207  5541  5587 I jxcore-log: 
,12-01 21:57:22.311  5541  5587 I jxcore-log: 2016-12-01 20:57:22 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:57:22.311  5541  5587 I jxcore-log: 
,12-01 21:57:22.719  5541  5587 I jxcore-log: 2016-12-01 20:57:22 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:22.719  5541  5587 I jxcore-log: 
,12-01 21:57:22.823  5541  5587 I jxcore-log: 2016-12-01 20:57:22 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:57:22.823  5541  5587 I jxcore-log: 
,12-01 21:57:23.233  5541  5587 I jxcore-log: 2016-12-01 20:57:23 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:23.233  5541  5587 I jxcore-log: 
,12-01 21:57:23.699   928  5816 D NetlinkSocketObserver: NeighborEvent{elapsedMs=324637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,12-01 21:57:23.744  5541  5587 I jxcore-log: 2016-12-01 20:57:23 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:23.744  5541  5587 I jxcore-log: 
,12-01 21:57:24.357  5541  5587 I jxcore-log: 2016-12-01 20:57:24 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:57:24.357  5541  5587 I jxcore-log: 
,12-01 21:57:24.869  5541  5587 I jxcore-log: 2016-12-01 20:57:24 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:57:24.869  5541  5587 I jxcore-log: 
,12-01 21:57:25.278  5541  5587 I jxcore-log: 2016-12-01 20:57:25 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:25.278  5541  5587 I jxcore-log: 
,12-01 21:57:25.382  5541  5587 I jxcore-log: 2016-12-01 20:57:25 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:57:25.382  5541  5587 I jxcore-log: 
,12-01 21:57:25.793  5541  5587 I jxcore-log: 2016-12-01 20:57:25 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:57:25.793  5541  5587 I jxcore-log: 
,12-01 21:57:27.745  5541  5587 I jxcore-log: 2016-12-01 20:57:27 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:27.745  5541  5587 I jxcore-log: 
,12-01 21:57:27.749  5541  5587 I jxcore-log: 2016-12-01 20:57:27 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:27.749  5541  5587 I jxcore-log: 
,12-01 21:57:28.352  5541  5587 I jxcore-log: 2016-12-01 20:57:28 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:57:28.352  5541  5587 I jxcore-log: 
,12-01 21:57:28.761  5541  5587 I jxcore-log: 2016-12-01 20:57:28 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:28.761  5541  5587 I jxcore-log: 
,12-01 21:57:28.786   533   533 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,12-01 21:57:28.786   533   533 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,12-01 21:57:28.863  5541  5587 I jxcore-log: 2016-12-01 20:57:28 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:57:28.863  5541  5587 I jxcore-log: 
,12-01 21:57:29.683  5541  5587 I jxcore-log: 2016-12-01 20:57:29 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:29.683  5541  5587 I jxcore-log: 
,12-01 21:57:30.398  5541  5587 I jxcore-log: 2016-12-01 20:57:30 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:57:30.398  5541  5587 I jxcore-log: 
,12-01 21:57:31.217  5541  5587 I jxcore-log: 2016-12-01 20:57:31 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:31.217  5541  5587 I jxcore-log: 
,12-01 21:57:31.743  5541  5587 I jxcore-log: 2016-12-01 20:57:31 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:31.743  5541  5587 I jxcore-log: 
,12-01 21:57:32.242  5541  5587 I jxcore-log: 2016-12-01 20:57:32 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:32.242  5541  5587 I jxcore-log: 
,12-01 21:57:32.346  5541  5587 I jxcore-log: 2016-12-01 20:57:32 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:57:32.346  5541  5587 I jxcore-log: 
,12-01 21:57:33.139   928  5816 D NetlinkSocketObserver: NeighborEvent{elapsedMs=334078, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,12-01 21:57:33.267  5541  5587 I jxcore-log: 2016-12-01 20:57:33 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:33.267  5541  5587 I jxcore-log: 
,12-01 21:57:33.779  5541  5587 I jxcore-log: 2016-12-01 20:57:33 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:33.779  5541  5587 I jxcore-log: 
,12-01 21:57:34.904  5541  5587 I jxcore-log: 2016-12-01 20:57:34 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:57:34.904  5541  5587 I jxcore-log: 
,12-01 21:57:35.328  5541  5587 I jxcore-log: 2016-12-01 20:57:35 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:35.328  5541  5587 I jxcore-log: 
,12-01 21:57:35.831  5541  5587 I jxcore-log: 2016-12-01 20:57:35 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:35.831  5541  5587 I jxcore-log: 
,12-01 21:57:36.036   928  2959 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,12-01 21:57:37.797  5541  5587 I jxcore-log: 2016-12-01 20:57:37 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:37.797  5541  5587 I jxcore-log: 
,12-01 21:57:38.288  5541  5587 I jxcore-log: 2016-12-01 20:57:38 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:38.288  5541  5587 I jxcore-log: 
,12-01 21:57:38.387  5541  5587 I jxcore-log: 2016-12-01 20:57:38 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:57:38.387  5541  5587 I jxcore-log: 
,12-01 21:57:38.796  5541  5587 I jxcore-log: 2016-12-01 20:57:38 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:38.796  5541  5587 I jxcore-log: 
,12-01 21:57:39.819  5541  5587 I jxcore-log: 2016-12-01 20:57:39 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:39.819  5541  5587 I jxcore-log: 
,12-01 21:57:39.922  5541  5587 I jxcore-log: 2016-12-01 20:57:39 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:57:39.922  5541  5587 I jxcore-log: 
,12-01 21:57:40.333  5541  5587 I jxcore-log: 2016-12-01 20:57:40 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:40.333  5541  5587 I jxcore-log: 
,12-01 21:57:41.458  5541  5587 I jxcore-log: 2016-12-01 20:57:41 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:57:41.458  5541  5587 I jxcore-log: 
,12-01 21:57:41.868  5541  5587 I jxcore-log: 2016-12-01 20:57:41 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:41.868  5541  5587 I jxcore-log: 
,12-01 21:57:41.985  5541  5587 I jxcore-log: 2016-12-01 20:57:41 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:57:41.985  5541  5587 I jxcore-log: 
,12-01 21:57:42.378  5541  5587 I jxcore-log: 2016-12-01 20:57:42 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:42.378  5541  5587 I jxcore-log: 
,12-01 21:57:42.892  5541  5587 I jxcore-log: 2016-12-01 20:57:42 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:42.892  5541  5587 I jxcore-log: 
,12-01 21:57:43.301  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:95f4c8b5-cdd6-4638-855f-39eaf558bf5a","hostAddress":"192.168.1.113","portNumber":40810}'
12-01 21:57:43.301  5541  5587 I jxcore-log: 
,12-01 21:57:43.430  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
12-01 21:57:43.430  5541  5587 I jxcore-log: 
,12-01 21:57:43.431  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
12-01 21:57:43.431  5541  5587 I jxcore-log: 
12-01 21:57:43.432  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
12-01 21:57:43.432  5541  5587 I jxcore-log: 
12-01 21:57:43.432  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
12-01 21:57:43.432  5541  5587 I jxcore-log: 
,12-01 21:57:43.433  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
12-01 21:57:43.433  5541  5587 I jxcore-log: 
12-01 21:57:43.433  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
12-01 21:57:43.433  5541  5587 I jxcore-log: 
12-01 21:57:43.434  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
12-01 21:57:43.434  5541  5587 I jxcore-log: 
12-01 21:57:43.434  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
12-01 21:57:43.434  5541  5587 I jxcore-log: 
12-01 21:57:43.435  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
12-01 21:57:43.435  5541  5587 I jxcore-log: 
12-01 21:57:43.435  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
12-01 21:57:43.435  5541  5587 I jxcore-log: 
12-01 21:57:43.437  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
12-01 21:57:43.437  5541  5587 I jxcore-log: 
12-01 21:57:43.437  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server is not there'
12-01 21:57:43.437  5541  5587 I jxcore-log: 
,12-01 21:57:43.439  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server accepts & closes connection'
12-01 21:57:43.439  5541  5587 I jxcore-log: 
12-01 21:57:43.440  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - server always returns 500'
12-01 21:57:43.440  5541  5587 I jxcore-log: 
12-01 21:57:43.440  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - create new seq doc'
12-01 21:57:43.440  5541  5587 I jxcore-log: 
,12-01 21:57:43.442  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - doc exists, need to get rev and update'
12-01 21:57:43.442  5541  5587 I jxcore-log: 
12-01 21:57:43.443  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - update seq three times'
12-01 21:57:43.443  5541  5587 I jxcore-log: 
,12-01 21:57:43.446  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - rev got changed under us'
12-01 21:57:43.446  5541  5587 I jxcore-log: 
,12-01 21:57:43.447  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - fail if stop is called'
12-01 21:57:43.447  5541  5587 I jxcore-log: 
12-01 21:57:43.448  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #_doImmediateSeqUpdate - stop after get but before put fails right'
12-01 21:57:43.448  5541  5587 I jxcore-log: 
,12-01 21:57:43.448  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - fail if stop is called'
12-01 21:57:43.448  5541  5587 I jxcore-log: 
12-01 21:57:43.449  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - set seq for first time'
12-01 21:57:43.449  5541  5587 I jxcore-log: 
12-01 21:57:43.450  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - Fail on bad seq value'
12-01 21:57:43.450  5541  5587 I jxcore-log: 
,12-01 21:57:43.450  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - do we cancel timer properly on an immediate?'
12-01 21:57:43.450  5541  5587 I jxcore-log: 
12-01 21:57:43.451  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - do we wait for blocked update'
12-01 21:57:43.451  5541  5587 I jxcore-log: 
12-01 21:57:43.452  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - test that we wait long enough'
12-01 21:57:43.452  5541  5587 I jxcore-log: 
12-01 21:57:43.452  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #update - test that we pick up new sequences while we wait'
12-01 21:57:43.452  5541  5587 I jxcore-log: 
12-01 21:57:43.453  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Coordinated seq test, error: 'TimeoutError', stack: 'TimeoutError: 
12-01 21:57:43.453  5541  5587 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
12-01 21:57:43.453  5541  5587 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
12-01 21:57:43.453  5541  5587 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
12-01 21:57:43.453  5541  5587 I jxcore-log:     at $9@timers.js:120:1
12-01 21:57:43.453  5541  5587 I jxcore-log: ''
12-01 21:57:43.453  5541  5587 I jxcore-log: 
12-01 21:57:43.454  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'android''
12-01 21:57:43.454  5541  5587 I jxcore-log: 
12-01 21:57:43.455  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - DEBUG CoordinatedClient: 'test client failed'
12-01 21:57:43.455  5541  5587 I jxcore-log: 
,12-01 21:57:43.460  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - DEBUG CoordinatedClient: 'device disconnected from the test server'
12-01 21:57:43.460  5541  5587 I jxcore-log: 
12-01 21:57:43.462  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - ERROR CoordinatedThaliTape: 'tests failed, error: 'TimeoutError', stack: 'TimeoutError: 
12-01 21:57:43.462  5541  5587 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
12-01 21:57:43.462  5541  5587 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
12-01 21:57:43.462  5541  5587 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
12-01 21:57:43.462  5541  5587 I jxcore-log:     at $9@timers.js:120:1
12-01 21:57:43.462  5541  5587 I jxcore-log: ''
12-01 21:57:43.462  5541  5587 I jxcore-log: 
12-01 21:57:43.463  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
12-01 21:57:43.463  5541  5587 I jxcore-log: 
,12-01 21:57:43.503  5541  5587 I jxcore-log: 2016-12-01 20:57:43 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"urn:uuid:b4857670-1735-4078-99fd-bfc29f30b4f7","hostAddress":"192.168.1.107","portNumber":54386}'
12-01 21:57:43.503  5541  5587 I jxcore-log: 
,12-01 21:57:43.788   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:57:43.884  5865  5865 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,12-01 21:57:43.890  5865  5865 D AndroidRuntime: CheckJNI is OFF
,12-01 21:57:43.916  5865  5865 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,12-01 21:57:43.947  5865  5865 I Radio-JNI: register_android_hardware_Radio DONE
,12-01 21:57:43.963  5865  5865 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,12-01 21:57:43.973   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,12-01 21:57:43.973   928   941 I ActivityManager: Killing 5541:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,12-01 21:57:44.089   928  3791 D GraphicsStats: Buffer count: 2
12-01 21:57:44.089   928   938 I WindowState: WIN DEATH: Window{c101432 u0 com.test.thalitest/com.test.thalitest.MainActivity}
12-01 21:57:44.089   928  2960 D WifiService: Client connection lost with reason: 4
,12-01 21:57:44.110   928   941 W ActivityManager: Force removing ActivityRecord{a70b02b u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,12-01 21:57:44.162   928   951 I art     : Starting a blocking GC Explicit
,12-01 21:57:44.170   928  3811 W ActivityManager: Spurious death for ProcessRecord{ad22c49 0:com.test.thalitest/u0a77}, curProc for 5541: null
,12-01 21:57:44.199   939   939 W Binder_2: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[26214]" dev="sockfs" ino=26214 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
12-01 21:57:44.201   928   939 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5541 uid 10077
12-01 21:57:44.199   939   939 W Binder_2: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[26214]" dev="sockfs" ino=26214 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
12-01 21:57:44.202  3672  3672 I Keyboard.Facilitator: onFinishInput()
,12-01 21:57:44.265  3982  5877 I MicroRecognitionRnrImpl: Starting detection.
,12-01 21:57:44.266  3982  5878 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@ba66c5c
12-01 21:57:44.267   510  5880 I AudioFlinger: AudioFlinger's thread 0xf2000000 ready to run
,12-01 21:57:44.271   510  3007 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,12-01 21:57:44.273  3982  5878 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@ba66c5c
,12-01 21:57:44.275   928   951 I art     : Explicit concurrent mark sweep GC freed 104701(7MB) AllocSpace objects, 59(1948KB) LOS objects, 33% free, 29MB/43MB, paused 1.813ms total 113.178ms
,12-01 21:57:44.288   510  5880 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,12-01 21:57:44.289   510  5880 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
12-01 21:57:44.289   510  5880 I ACDB-LOADER: ACDB AFE returned = -19
,12-01 21:57:44.289   510  5880 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
12-01 21:57:44.289   510  5880 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
12-01 21:57:44.289   510  5880 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,12-01 21:57:44.295   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
12-01 21:57:44.296   510  5880 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
12-01 21:57:44.298  5865  5865 I art     : System.exit called, status: 0
12-01 21:57:44.298  5865  5865 I AndroidRuntime: VM exiting with result code 0.
,12-01 21:57:44.302   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,12-01 21:57:44.312  3672  3672 I Keyboard.Facilitator: resetDictionaries() : en_US
12-01 21:57:44.313  5759  5759 D BluetoothMapAppObserver: onReceive
12-01 21:57:44.313  5759  5759 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,12-01 21:57:44.317  4054  4172 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,12-01 21:57:44.321   928  2946 I InputReader: Reconfiguring input devices.  changes=0x00000010
,12-01 21:57:44.334  3672  5884 I Keyboard.Facilitator.DecoderInitializer: run()
,12-01 21:57:44.342  3414  5885 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
12-01 21:57:44.343  3672  5884 I Decoder : createOrResetDecoder
,12-01 21:57:44.367  3768  3768 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,12-01 21:57:44.379  3982  3982 I HotwordWorkerImpl: onReady
12-01 21:57:44.381  3591  3591 I ConfigService: onCreate
,12-01 21:57:44.387   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,12-01 21:57:44.389  3591  3591 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,12-01 21:57:44.389  3591  3591 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,12-01 21:57:44.396  3672  5884 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,12-01 21:57:44.400  3852  5891 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,12-01 21:57:44.400  3852  5891 D AccountUtils: Clearing selected account for com.test.thalitest
,12-01 21:57:44.413  3852  5891 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,12-01 21:57:44.426  5863  5863 W kworker/2:2: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,12-01 21:57:44.435  3852  3852 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
12-01 21:57:44.435  3852  3852 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
12-01 21:57:44.441  3852  3852 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
12-01 21:57:44.441  3852  3852 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,12-01 21:57:44.448  3982  5900 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,12-01 21:57:44.446  5863  5863 W kworker/2:2: type=1400 audit(0.0:124): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
12-01 21:57:44.451  3852  5896 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
12-01 21:57:44.451  3852  5896 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
12-01 21:57:44.451  3852  5896 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
12-01 21:57:44.451  3852  5896 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
,12-01 21:57:44.456  5863  5863 W kworker/2:2: type=1400 audit(0.0:125): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,12-01 21:57:44.456  3852  5896 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/help_responses.db, release reference: 1
12-01 21:57:44.457  3852  5896 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/help_responses.db: 2
12-01 21:57:44.457  3852  5896 E SQLiteLog: (3850) statement aborts at 21: [DELETE FROM help_responses WHERE app_package_name="com.test.thalitest"] disk I/O error
12-01 21:57:44.457  3852  5896 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/help_responses.db: 1
--------- beginning of crash
12-01 21:57:44.458  3852  5896 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
12-01 21:57:44.458  3852  5896 E AndroidRuntime: Process: com.google.android.gms, PID: 3852
12-01 21:57:44.458  3852  5896 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
12-01 21:57:44.458  3852  5896 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
12-01 21:57:44.458  3852  5896 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
12-01 21:57:44.458  3852  5896 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
12-01 21:57:44.458  3852  5896 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
12-01 21:57:44.458  3852  5896 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
12-01 21:57:44.458  3852  5896 E AndroidRuntime: 	at com.google.android.gms.googlehelp.c.b.d(SourceFile:535)
12-01 21:57:44.458  3852  5896 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:52)
12-01 21:57:44.458  3852  5896 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
12-01 21:57:44.458  3852  5896 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
12-01 21:57:44.458  3852  5896 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
12-01 21:57:44.458  3852  5896 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,12-01 21:57:44.462  3672  5884 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,12-01 21:57:44.465  3672  5884 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
12-01 21:57:44.465  3672  5884 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
12-01 21:57:44.471  3414  5885 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM voicemail_status WHERE (((source_package = 'com.test.thalitest')))] disk I/O error
12-01 21:57:44.472  3414  5885 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
12-01 21:57:44.472  3414  5885 E AndroidRuntime: Process: android.process.acore, PID: 3414
12-01 21:57:44.472  3414  5885 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
12-01 21:57:44.472  3414  5885 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
12-01 21:57:44.472  3414  5885 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
12-01 21:57:44.472  3414  5885 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
12-01 21:57:44.472  3414  5885 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
12-01 21:57:44.472  3414  5885 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
12-01 21:57:44.472  3414  5885 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
12-01 21:57:44.472  3414  5885 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailStatusTable.delete(VoicemailStatusTable.java:80)
12-01 21:57:44.472  3414  5885 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
12-01 21:57:44.472  3414  5885 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
12-01 21:57:44.472  3414  5885 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
12-01 21:57:44.472  3414  5885 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:52)
12-01 21:57:44.472  3414  5885 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
12-01 21:57:44.472  3414  5885 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
12-01 21:57:44.472  3414  5885 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
12-01 21:57:44.472  3414  5885 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
12-01 21:57:44.472  3414  5885 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,12-01 21:57:44.473  3982  5900 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,12-01 21:57:44.474  3672  5884 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,12-01 21:57:44.474  3672  5884 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
12-01 21:57:44.475   928  3763 I ActivityManager: Start proc 5903:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
12-01 21:57:44.476  3672  5884 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
12-01 21:57:44.476  3672  5884 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
12-01 21:57:44.477  3672  5884 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
12-01 21:57:44.477  3672  5884 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
12-01 21:57:44.477  3672  5884 I Keyboard.Facilitator.Delight2FileSweeper: run()
12-01 21:57:44.477  3672  5884 I Keyboard.Facilitator.RecurringTaskScheduler: run()
12-01 21:57:44.477  3672  5884 I StatsUtilsManager: startPeriodStatsRecorder() : Success
12-01 21:57:44.477  3672  5884 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,12-01 21:57:44.481   928  5909 E DropBoxManagerService: Can't write: system_app_crash
12-01 21:57:44.481   928  5909 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
12-01 21:57:44.481   928  5909 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
12-01 21:57:44.481   928  5909 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
12-01 21:57:44.481   928  5909 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
12-01 21:57:44.481   928  5909 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
12-01 21:57:44.481   928  5909 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
12-01 21:57:44.481   928  5909 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
12-01 21:57:44.481   928  5909 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
12-01 21:57:44.481   928  5909 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
12-01 21:57:44.481   928  5909 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
12-01 21:57:44.481   928  5909 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
12-01 21:57:44.481   928  5909 E DropBoxManagerService: 	... 5 more
,12-01 21:57:44.491   928  3791 I ActivityManager: Start proc 5914:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,12-01 21:57:44.493  3982  5900 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,12-01 21:57:44.493  3982  5900 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
12-01 21:57:44.493  3982  5900 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 3982
12-01 21:57:44.493  3982  5900 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
12-01 21:57:44.493  3982  5900 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
12-01 21:57:44.493  3982  5900 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
12-01 21:57:44.493  3982  5900 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
12-01 21:57:44.493  3982  5900 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
12-01 21:57:44.493  3982  5900 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
12-01 21:57:44.493  3982  5900 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
12-01 21:57:44.493  3982  5900 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
12-01 21:57:44.493  3982  5900 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
12-01 21:57:44.493  3982  5900 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
12-01 21:57:44.493  3982  5900 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
12-01 21:57:44.493  3982  5900 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
12-01 21:57:44.493  3982  5900 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
12-01 21:57:44.493  3982  5900 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
12-01 21:57:44.493  3982  5900 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
12-01 21:57:44.493  3982  5900 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
12-01 21:57:44.493  3982  5900 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
12-01 21:57:44.493  3982  5900 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
12-01 21:57:44.493  3982  5900 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
12-01 21:57:44.494   928  5924 E DropBoxManagerService: Can't write: system_app_crash
12-01 21:57:44.494   928  5924 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
12-01 21:57:44.494   928  5924 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
12-01 21:57:44.494   928  5924 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
12-01 21:57:44.494   928  5924 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
12-01 21:57:44.494   928  5924 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
12-01 21:57:44.494   928  5924 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
12-01 21:57:44.494   928  5924 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
12-01 21:57:44.494   928  5924 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
12-01 21:57:44.494   928  5924 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
12-01 21:57:44.494   928  5924 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186),
12-01 21:57:44.494   928  5924 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
12-01 21:57:44.494   928  5924 E DropBoxManagerService: 	... 5 more
12-01 21:57:44.523   928  5929 E DropBoxManagerService: Can't write: system_app_crash
12-01 21:57:44.523   928  5929 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
12-01 21:57:44.523   928  5929 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
12-01 21:57:44.523   928  5929 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
12-01 21:57:44.523   928  5929 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
12-01 21:57:44.523   928  5929 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
12-01 21:57:44.523   928  5929 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
12-01 21:57:44.523   928  5929 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
12-01 21:57:44.523   928  5929 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
12-01 21:57:44.523   928  5929 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
12-01 21:57:44.523   928  5929 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
12-01 21:57:44.523   928  5929 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
12-01 21:57:44.523   928  5929 E DropBoxManagerService: 	... 5 more
12-01 21:57:44.529  3852  5898 W BaseAppContext: Using Auth Proxy for data requests.
12-01 21:57:44.535  3852  5898 W BaseAppContext: Using Auth Proxy for data requests.
,12-01 21:57:44.566   928   941 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{c0e66f6 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{e1c0db8 3852 com.google.android.gms/10012/u0 remote:818f81b}: process crashing
,12-01 21:57:44.572   928   939 D ConnectivityService: listenForNetwork for Listen from uid/pid:10012/3852 for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,12-01 21:57:44.617  3591  3599 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/user/0/com.google.android.gms/databases/phenotype.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,12-01 21:57:44.640  3852  5895 W DriveInitializer: Awaiting to be initialized
,12-01 21:57:44.640  3852  5932 W DriveInitializer: Background init thread started
,12-01 21:57:44.789   533   533 I ServiceManager: Waiting for service AtCmdFwd...
,12-01 21:57:44.831   381   479 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
