#### Test 950476153ba6213_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-24 11:41:27.929  3828  4230 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-24 11:41:28.015  3828  4230 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-24 11:41:28.386  5604  5604 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-24 11:41:28.392  5604  5604 D AndroidRuntime: CheckJNI is OFF
11-24 11:41:28.417  5604  5604 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-24 11:41:28.452  5604  5604 I Radio-JNI: register_android_hardware_Radio DONE
11-24 11:41:28.467  5604  5604 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-24 11:41:28.470   929   940 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-24 11:41:28.497  3963  4273 W SearchService: Abort, client detached.
11-24 11:41:28.498  5604  5604 D AndroidRuntime: Shutting down VM
11-24 11:41:28.507  3963  3963 I HotwordDetector: Closing mic
11-24 11:41:28.508  3963  4180 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@6dd18e2
11-24 11:41:28.508  3963  4227 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-24 11:41:28.528   929  3820 I ActivityManager: Start proc 5613:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-24 11:41:28.572   514  4229 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-24 11:41:28.574   514  4229 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-24 11:41:28.577   514  4229 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-24 11:41:28.577   514  4229 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-24 11:41:28.579   514  2992 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-24 11:41:28.582  3963  4226 I MicroRecognitionRnrImpl: Detection finished
11-24 11:41:28.582  3963  4208 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-24 11:41:28.621  5613  5613 I CordovaLog: Changing log level to DEBUG(3)
11-24 11:41:28.622  5613  5613 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-24 11:41:28.622  5613  5613 D CordovaActivity: CordovaActivity.onCreate()
11-24 11:41:28.626  5613  5613 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-24 11:41:28.645  5613  5613 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-24 11:41:28.689  5613  5613 I LibraryLoader: Time to load native libraries: 41 ms (timestamps 9586-9627)
11-24 11:41:28.689  5613  5613 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-24 11:41:28.703  5613  5613 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7e7743d}
11-24 11:41:28.704  5613  5613 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-24 11:41:28.704  5613  5613 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-24 11:41:28.707  5613  5613 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-24 11:41:28.708  5613  5613 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-24 11:41:28.735  5613  5613 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-24 11:41:28.744  5613  5613 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-24 11:41:28.744  5613  5613 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-24 11:41:28.744  5613  5613 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-24 11:41:28.744  5613  5613 I Adreno  : Build Date                       : 12/06/15
11-24 11:41:28.744  5613  5613 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-24 11:41:28.744  5613  5613 I Adreno  : Local Branch                     : mybranch17112971
11-24 11:41:28.744  5613  5613 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-24 11:41:28.744  5613  5613 I Adreno  : Remote Branch                    : NONE
11-24 11:41:28.744  5613  5613 I Adreno  : Reconstruct Branch               : NOTHING
,11-24 11:41:28.794   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d028147:true
,11-24 11:41:28.821  3858  3858 W Binder_4: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[21385]" dev="sockfs" ino=21385 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 11:41:28.821  3858  3858 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[21385]" dev="sockfs" ino=21385 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 11:41:28.830  5613  5613 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-24 11:41:28.840  5613  5613 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-24 11:41:28.843  5613  5613 D PluginManager: init()
,11-24 11:41:28.846  5613  5613 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-24 11:41:28.859  5613  5613 D CordovaActivity: Started the activity.
,11-24 11:41:28.859  5613  5613 D CordovaActivity: Resumed the activity.
,11-24 11:41:28.861  3858  3858 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[30696]" dev="sockfs" ino=30696 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 11:41:28.861  3858  3858 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[30696]" dev="sockfs" ino=30696 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-24 11:41:28.864  5613  5650 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-24 11:41:28.864  4037  4037 W Binder_A: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[21397]" dev="sockfs" ino=21397 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 11:41:28.864  4037  4037 W Binder_A: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[21397]" dev="sockfs" ino=21397 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 11:41:28.867  5613  5637 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-24 11:41:28.887  5613  5650 I OpenGLRenderer: Initialized EGL, version 1.4
,11-24 11:41:28.960   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +453ms
,11-24 11:41:28.957  4037  4037 W Binder_A: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32504]" dev="sockfs" ino=32504 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 11:41:28.957  4037  4037 W Binder_A: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32504]" dev="sockfs" ino=32504 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 11:41:28.961  3827  3827 W Binder_9: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32503]" dev="sockfs" ino=32503 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 11:41:28.961  3827  3827 W Binder_9: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32503]" dev="sockfs" ino=32503 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 11:41:28.964  3655  3655 I Keyboard.Facilitator: onFinishInput()
,11-24 11:41:28.982  5613  5613 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-24 11:41:29.009  5613  5613 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5613
,11-24 11:41:29.093  5613  5613 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-24 11:41:29.238  5613  5652 D jxcore_app_log: JniHelper::setJavaVM(0xf547c000), pthread_self() = -583796432
,11-24 11:41:29.243  5613  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-24 11:41:29.243  5613  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-24 11:41:29.243  5613  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-24 11:41:29.243  5613  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-24 11:41:29.243  5613  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-24 11:41:29.243  5613  5652 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2fd6d8 added. We now have 1 listener(s)
,11-24 11:41:29.245  5613  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-24 11:41:29.246  5613  5652 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 11:41:29.246  5613  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-24 11:41:29.246  5613  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-24 11:41:29.249  5613  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-24 11:41:29.249  5613  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-24 11:41:29.249  5613  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-24 11:41:29.249  5613  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-24 11:41:29.249  5613  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-24 11:41:29.249  5613  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-24 11:41:29.249  5613  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-24 11:41:29.249  5613  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-24 11:41:29.249  5613  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-24 11:41:29.249  5613  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-24 11:41:29.249  5613  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-24 11:41:29.249  5613  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-24 11:41:29.249  5613  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-24 11:41:29.249  5613  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-24 11:41:29.249  5613  5652 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d15ae97 added. We now have 1 listener(s)
11-24 11:41:29.249  5613  5652 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 11:41:29.252   929  2986 D WifiService: New client listening to asynchronous messages
11-24 11:41:29.253  5613  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 11:41:29.253  5613  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,11-24 11:41:29.253  5613  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
,11-24 11:41:29.253  5613  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-24 11:41:29.253  5613  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-24 11:41:29.253  5613  5652 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-24 11:41:29.253  5613  5652 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
,11-24 11:41:29.254  5613  5652 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-24 11:41:29.350  5613  5613 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-24 11:41:29.352  5613  5613 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,11-24 11:41:29.352  5613  5613 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-24 11:41:29.851  5613  5660 W jxcore-log: Initializing JXcore engine
,11-24 11:41:29.851  5613  5660 W jxcore-log: JXcore engine is ready
,11-24 11:41:29.874  5660  5660 W Thread-58: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11933 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-24 11:41:29.874  5660  5660 W Thread-58: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[16487]" dev="sockfs" ino=16487 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,11-24 11:41:29.874  5660  5660 W Thread-58: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,11-24 11:41:29.874  5660  5660 W Thread-58: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32474]" dev="sockfs" ino=32474 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-24 11:41:29.884  5613  5660 W jxcore-log: Starting JXcore engine
,11-24 11:41:29.935  5613  5660 W jxcore-log: Platform android
11-24 11:41:29.935  5613  5660 W jxcore-log: 
,11-24 11:41:29.935  5613  5660 W jxcore-log: Process ARCH arm
11-24 11:41:29.935  5613  5660 W jxcore-log: 
,11-24 11:41:30.118  5613  5660 I jxcore-log: JXcore Cordova bridge is ready!
11-24 11:41:30.118  5613  5660 I jxcore-log: 
,11-24 11:41:30.119  5613  5660 W jxcore-log: JXcore engine is started
,11-24 11:41:30.130  5613  5652 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-24 11:41:30.137  5613  5613 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
11-24 11:41:30.137  5613  5613 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-24 11:41:32.062  3578  3578 I ConfigService: onDestroy
,11-24 11:41:33.514   929  3669 I ActivityManager: Killing 5127:com.google.android.youtube/u0a75 (adj 15): empty #17
,11-24 11:41:38.905   929  2985 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 11:41:39.769  5613  5660 I jxcore-log: 2016-11-24 10:41:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-24 11:41:39.769  5613  5660 I jxcore-log: 
,11-24 11:41:39.771  5613  5660 I jxcore-log: 2016-11-24 10:41:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-24 11:41:39.771  5613  5660 I jxcore-log: 
,11-24 11:41:39.778  5613  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-24 11:41:39.778  5613  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 11:41:39.778  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 11:41:39.778  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 11:41:39.778  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 11:41:39.778  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 11:41:39.778  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 11:41:39.778  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 11:41:39.778  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 11:41:39.778  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 11:41:39.780  5613  5660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 11:41:39.781  5613  5660 I jxcore-log: 2016-11-24 10:41:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-24 11:41:39.781  5613  5660 I jxcore-log: 
11-24 11:41:39.782  5613  5660 I jxcore-log: 2016-11-24 10:41:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-24 11:41:39.782  5613  5660 I jxcore-log: 
,11-24 11:41:40.027  5613  5660 I jxcore-log: 2016-11-24 10:41:40 - DEBUG UnitTest_app: 'Running unit tests'
11-24 11:41:40.027  5613  5660 I jxcore-log: 
,11-24 11:41:40.028  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 11:41:40.028  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35754a3 added. We now have 2 listener(s)
,11-24 11:41:40.028  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 11:41:40.028  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-24 11:41:40.028  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 11:41:40.029  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 11:41:40.029  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10ae3a0 added. We now have 2 listener(s)
11-24 11:41:40.029  5613  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 11:41:40.029  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 11:41:40.030  5613  5660 D executeNativeTests: Running unit tests
,11-24 11:41:40.072  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 11:41:40.072  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ff4cc9 added. We now have 3 listener(s)
11-24 11:41:40.073  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 11:41:40.073  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-24 11:41:40.073  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 11:41:40.073  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:41:40.073  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce added. We now have 3 listener(s)
,11-24 11:41:40.073  5613  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 11:41:40.074  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 11:41:40.076  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 11:41:40.076  5613  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 11:41:40.076  5613  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-24 11:41:40.076  5613  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 11:41:40.077  5613  5660 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-24 11:41:40.077  5613  5660 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-24 11:41:40.078  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-24 11:41:40.078  5613  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 11:41:40.078  5613  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 11:41:40.078  5613  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 11:41:40.078  5613  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:41:40.078  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 11:41:40.078  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:41:40.078  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:41:40.079  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:41:40.079  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-24 11:41:40.079  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ff4cc9 removed from the list
11-24 11:41:40.079  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:41:40.079  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce removed from the list
11-24 11:41:40.079  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:41:40.080  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:40.080  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:41:40.081  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:40.081  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:40.081  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:40.081  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:41:40.081  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:41:40.081  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:41:40.081  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:41:40.082  5613  5660 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-24 11:41:40.083  5613  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:41:40.083  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:41:40.083  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:41:40.083  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:41:40.083  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:41:40.083  5613  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ff4cc9 not in the list
11-24 11:41:40.083  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:41:40.083  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:41:40.083  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:41:40.083  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:40.083  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:40.084  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:40.084  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:40.084  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:40.084  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 11:41:40.084  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:41:40.084  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:41:40.084  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:41:40.087  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-24 11:41:40.087  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-24 11:41:40.087  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-24 11:41:40.087  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-24 11:41:40.087  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-24 11:41:40.087  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,11-24 11:41:40.087  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-24 11:41:40.087  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-24 11:41:40.087  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-24 11:41:40.087  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-24 11:41:40.087  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-24 11:41:40.087  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-24 11:41:40.087  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-24 11:41:40.087  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-24 11:41:40.087  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,11-24 11:41:40.088  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-24 11:41:40.088  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-24 11:41:40.088  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-24 11:41:40.088  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-24 11:41:40.088  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,11-24 11:41:40.088  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-24 11:41:40.088  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-24 11:41:40.088  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-24 11:41:40.088  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-24 11:41:40.088  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-24 11:41:40.088  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-24 11:41:40.088  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-24 11:41:40.088  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-24 11:41:40.088  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-24 11:41:40.088  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-24 11:41:40.088  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-24 11:41:40.088  5613  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:41:40.088  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 11:41:40.088  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:41:40.088  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:41:40.088  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:41:40.088  5613  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ff4cc9 not in the list
11-24 11:41:40.088  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:41:40.088  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
,11-24 11:41:40.088  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:41:40.088  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:40.089  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:40.089  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:40.089  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:40.089  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:40.089  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:41:40.089  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 11:41:40.089  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:41:40.089  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:41:40.090  5613  5660 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-24 11:41:40.091  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 11:41:40.091  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 11:41:40.103  5613  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 11:41:40.103  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 11:41:40.103  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 11:41:40.103  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 11:41:40.103  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 11:41:40.103  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 11:41:40.103  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 11:41:40.103  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 11:41:40.103  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 11:41:40.106  5613  5660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 11:41:40.106  5613  5660 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 11:41:40.107  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 11:41:40.107  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 11:41:40.107  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 11:41:40.107  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 11:41:40.108  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 11:41:40.110  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 11:41:40.110  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 11:41:40.110  5613  5660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 11:41:40.111  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 11:41:40.113  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:40.113  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-24 11:41:40.113  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 11:41:40.114  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 11:41:40.114  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 11:41:40.114  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 11:41:40.115  5613  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-24 11:41:40.116  5613  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-24 11:41:40.116  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:40.116  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-24 11:41:40.116  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-24 11:41:40.116  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 11:41:40.117  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 11:41:40.117  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:40.117  5613  5660 D BluetoothAdapter: STATE_ON
11-24 11:41:40.119  4600  4611 D BtGatt.GattService: registerClient() - UUID=fff60190-5b88-42f4-a307-7e5c16e4985b
,11-24 11:41:40.120  4600  4650 D BtGatt.GattService: onClientRegistered() - UUID=fff60190-5b88-42f4-a307-7e5c16e4985b, clientIf=5
,11-24 11:41:40.121  5613  5623 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 11:41:40.122  4600  4806 D BtGatt.GattService: start scan with filters
11-24 11:41:40.126  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 11:41:40.126  4600  4665 D BtGatt.ScanManager: handling starting scan
11-24 11:41:40.126  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:40.126  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 11:41:40.126  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:40.127  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 11:41:40.127  5613  5613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 11:41:40.128  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 11:41:40.128  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 11:41:40.128  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 11:41:40.128  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 11:41:40.128  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:40.128  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 11:41:40.128  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 11:41:40.129  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-24 11:41:40.129  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-24 11:41:40.131  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:40.131  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:40.131  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:40.132  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 11:41:40.132  5613  5660 I io.jxcore.node.ConnectionHelper: start: OK
11-24 11:41:40.132  4600  4665 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@836f2c
,11-24 11:41:40.135  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 11:41:40.135  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 11:41:40.136  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 11:41:40.136  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 11:41:40.136  5613  5613 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-24 11:41:40.139  4600  4650 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 11:41:40.140  4600  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 11:41:40.140  4600  4665 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-24 11:41:40.147  4600  4650 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 11:41:40.147  4600  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 11:41:40.147  4600  4665 D BtGatt.ScanManager: Starting BLE batch scan
11-24 11:41:40.148  4600  4665 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 11:41:40.159  4600  4650 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 11:41:40.159  4600  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 11:41:40.165  4600  4650 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 11:41:40.165  4600  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 11:41:40.637  5613  5613 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-24 11:41:40.638  5613  5613 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-24 11:41:40.638  5613  5613 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 11:41:40.987   929  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 11:41:42.549   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:41:43.550   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:41:44.026   929  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 11:41:44.552   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:41:45.136  5613  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 11:41:45.136  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 11:41:45.137  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 11:41:45.137  5613  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 11:41:45.137  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-24 11:41:45.137  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 11:41:45.137  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 11:41:45.137  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 11:41:45.138  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:45.138  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-24 11:41:45.138  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 11:41:45.139  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:45.139  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:45.139  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:41:45.139  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 11:41:45.139  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:45.140  5613  5660 D BluetoothAdapter: STATE_ON
,11-24 11:41:45.141  4600  4807 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-24 11:41:45.141  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 11:41:45.142  5613  5660 D BluetoothAdapter: STATE_ON
,11-24 11:41:45.143  4600  4806 D BtGatt.GattService: stopScan() - queue size =1
11-24 11:41:45.144  4600  4797 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 11:41:45.143  4600  4665 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 11:41:45.144  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 11:41:45.145  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:45.145  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 11:41:45.145  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:41:45.145  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:45.145  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:45.145  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:45.145  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 11:41:45.146  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:45.146  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:45.146  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:45.146  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 11:41:45.146  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 11:41:45.147  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 11:41:45.147  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:45.148  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:45.148  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 11:41:45.149  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:45.149  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:45.149  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 11:41:45.149  5613  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 11:41:45.149  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 11:41:45.149  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 11:41:45.149  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:41:45.149  5613  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ff4cc9 not in the list
,11-24 11:41:45.149  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:41:45.149  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 11:41:45.149  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:41:45.149  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:41:45.149  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 11:41:45.150  5613  5613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 11:41:45.150  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 11:41:45.150  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 11:41:45.150  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 11:41:45.150  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 11:41:45.151  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 11:41:45.151  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 11:41:45.151  5613  5613 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 11:41:45.151  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 11:41:45.152  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 11:41:45.154  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 11:41:45.154  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 11:41:45.154  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 11:41:45.155  4600  4600 D BtGatt.ScanManager: awakened up at time 86094
,11-24 11:41:45.207  4600  4650 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,11-24 11:41:45.207  4600  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:41:45.207  4600  4650 D BtGatt.GattService: current time is 86146846855
11-24 11:41:45.208  4600  4650 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -86, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -86, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -92, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-24 11:41:45.209  4600  4650 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-24 11:41:45.210  4600  4650 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-24 11:41:45.210  4600  4650 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-24 11:41:45.218  4600  4650 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 11:41:45.218  4600  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:41:45.219  4600  4665 D BtGatt.ScanManager: stopping BLe Batch
,11-24 11:41:45.225  4600  4650 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 11:41:45.225  4600  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:41:45.225  4600  4665 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 11:41:45.230  4600  4650 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 11:41:45.230  4600  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 11:41:45.242  3963  5663 W CronetSyncConnectionRcs: Upload content type not set.
,11-24 11:41:45.311  4783  4828 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-24 11:41:45.313  4783  4783 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-24 11:41:45.315   929  4037 I ActivityManager: Killing 5246:org.codeaurora.ims/1001 (adj 15): empty #17
,11-24 11:41:45.553   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:41:45.652  5613  5613 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 11:41:46.553   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:41:47.554   623   623 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 11:41:50.151  5613  5660 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-24 11:41:50.156  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-24 11:41:50.157  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 11:41:50.170  5613  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 11:41:50.170  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 11:41:50.170  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 11:41:50.170  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 11:41:50.170  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 11:41:50.170  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 11:41:50.170  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 11:41:50.170  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 11:41:50.170  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 11:41:50.175  5613  5660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 11:41:50.175  5613  5660 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 11:41:50.176  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 11:41:50.176  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-24 11:41:50.176  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 11:41:50.176  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-24 11:41:50.176  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 11:41:50.182  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 11:41:50.183  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 11:41:50.184  5613  5660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-24 11:41:50.184  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 11:41:50.187  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 11:41:50.193  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:41:50.193  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 11:41:50.194  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 11:41:50.194  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 11:41:50.194  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 11:41:50.200  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:41:50.200  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 11:41:50.200  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 11:41:50.200  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 11:41:50.201  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 11:41:50.201  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:41:50.202  5613  5660 D BluetoothAdapter: STATE_ON
,11-24 11:41:50.206  4600  4797 D BtGatt.GattService: registerClient() - UUID=b6eeaf5f-53b7-47b6-9e9a-fc66ebd68ece
,11-24 11:41:50.207  4600  4650 D BtGatt.GattService: onClientRegistered() - UUID=b6eeaf5f-53b7-47b6-9e9a-fc66ebd68ece, clientIf=5
11-24 11:41:50.208  5613  5623 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 11:41:50.208  4600  4807 D BtGatt.GattService: start scan with filters
,11-24 11:41:50.212  4600  4665 D BtGatt.ScanManager: handling starting scan
11-24 11:41:50.213  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 11:41:50.213  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.213  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 11:41:50.214  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:41:50.214  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 11:41:50.214  5613  5613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 11:41:50.214  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 11:41:50.214  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 11:41:50.214  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-24 11:41:50.214  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 11:41:50.215  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 11:41:50.215  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 11:41:50.215  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-24 11:41:50.217  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-24 11:41:50.218  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.223  4600  4650 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 11:41:50.223  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:41:50.223  4600  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:41:50.223  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 11:41:50.223  4600  4665 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 11:41:50.223  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.224  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.224  5613  5660 I io.jxcore.node.ConnectionHelper: start: OK
11-24 11:41:50.224  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 11:41:50.228  5613  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:41:50.228  5613  5660 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,11-24 11:41:50.228  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 11:41:50.228  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 11:41:50.228  5613  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 11:41:50.228  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-24 11:41:50.228  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:41:50.228  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 11:41:50.229  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 11:41:50.230  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-24 11:41:50.230  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 11:41:50.230  5613  5613 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 11:41:50.230  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 11:41:50.230  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.230  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-24 11:41:50.230  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 11:41:50.230  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:41:50.231  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.231  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.231  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-24 11:41:50.231  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:41:50.232  5613  5660 D BluetoothAdapter: STATE_ON
11-24 11:41:50.232  4600  4797 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 11:41:50.233  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 11:41:50.233  4600  4650 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 11:41:50.233  4600  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:41:50.233  4600  4665 D BtGatt.ScanManager: Starting BLE batch scan
11-24 11:41:50.233  4600  4665 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 11:41:50.233  5613  5660 D BluetoothAdapter: STATE_ON
,11-24 11:41:50.234  4600  4613 D BtGatt.GattService: stopScan() - queue size =1
11-24 11:41:50.235  4600  4807 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 11:41:50.236  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 11:41:50.236  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.236  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 11:41:50.236  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.236  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.236  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.236  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.236  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 11:41:50.236  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.236  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.236  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.237  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 11:41:50.237  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 11:41:50.237  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 11:41:50.238  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.239  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.239  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 11:41:50.239  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.239  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.239  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:41:50.239  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 11:41:50.239  5613  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 11:41:50.239  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 11:41:50.239  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 11:41:50.240  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:4,1:50.240  5613  5613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 11:41:50.240  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 11:41:50.240  5613  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ff4cc9 not in the list
11-24 11:41:50.240  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:41:50.240  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 11:41:50.240  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:41:50.240  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 11:41:50.240  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:41:50.240  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 11:41:50.240  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 11:41:50.240  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 11:41:50.240  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 11:41:50.240  5613  5613 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 11:41:50.240  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 11:41:50.240  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 11:41:50.244  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 11:41:50.244  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 11:41:50.244  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 11:41:50.244  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.244  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.245  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.246  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.246  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.246  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:41:50.246  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:41:50.246  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:41:50.246  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:41:50.247  5613  5660 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-24 11:41:50.249  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 11:41:50.249  4600  4650 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 11:41:50.249  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-24 11:41:50.249  4600  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:41:50.255  5613  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 11:41:50.255  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 11:41:50.255  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 11:41:50.255  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 11:41:50.255  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 11:41:50.255  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 11:41:50.255  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 11:41:50.255  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 11:41:50.255  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 11:41:50.255  4600  4650 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 11:41:50.255  4600  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:41:50.257  4600  4665 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 11:41:50.259  5613  5660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 11:41:50.259  5613  5660 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 11:41:50.259  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 11:41:50.259  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 11:41:50.259  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 11:41:50.259  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 11:41:50.259  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 11:41:50.263  4600  4650 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 11:41:50.263  4600  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:41:50.263  4600  4650 E BtGatt.ContextMap: Context not found for ID 5
11-24 11:41:50.263  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 11:41:50.266  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 11:41:50.266  5613  5660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 11:41:50.266  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 11:41:50.267  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 11:41:50.270  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.270  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 11:41:50.270  4600  4650 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 11:41:50.270  4600  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:41:50.270  4600  4665 D BtGatt.ScanManager: stopping BLe Batch
11-24 11:41:50.270  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 11:41:50.271  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 11:41:50.271  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 11:41:50.275  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.275  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 11:41:50.275  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 11:41:50.275  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 11:41:50.275  4600  4650 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 11:41:50.275  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 11:41:50.275  4600  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:41:50.275  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.275  4600  4665 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 11:41:50.276  5613  5660 D BluetoothAdapter: STATE_ON
,11-24 11:41:50.280  4600  4650 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 11:41:50.280  4600  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:41:50.281  4600  4797 D BtGatt.GattService: registerClient() - UUID=904950cd-f206-498c-9200-41b7d750afae
11-24 11:41:50.282  4600  4650 D BtGatt.GattService: onClientRegistered() - UUID=904950cd-f206-498c-9200-41b7d750afae, clientIf=5
11-24 11:41:50.282  5613  5624 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 11:41:50.283  4600  4807 D BtGatt.GattService: start scan with filters
11-24 11:41:50.285  4600  4665 D BtGatt.ScanManager: handling starting scan
11-24 11:41:50.285  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 11:41:50.286  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.286  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 11:41:50.286  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.286  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 11:41:50.286  5613  5613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 11:41:50.286  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 11:41:50.286  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 11:41:50.286  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 11:41:50.286  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 11:41:50.286  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 11:41:50.286  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 11:41:50.286  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 11:41:50.287  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 11:41:50.287  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.290  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.290  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 11:41:50.290  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.290  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:50.290  5613  5660 I io.jxcore.node.ConnectionHelper: start: OK
11-24 11:41:50.290  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 11:41:50.292  4600  4650 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 11:41:50.292  4600  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:41:50.292  4600  4665 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 11:41:50.293  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 11:41:50.293  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 11:41:50.293  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 11:41:50.293  5613  5613 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 11:41:50.297  4600  4650 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 11:41:50.297  4600  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:41:50.297  4600  4665 D BtGatt.ScanManager: Starting BLE batch scan
11-24 11:41:50.297  4600  4665 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 11:41:50.305  4600  4650 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 11:41:50.305  4600  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:41:50.309  4600  4650 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 11:41:50.309  4600  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 11:41:50.794  5613  5613 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-24 11:41:50.794  5613  5613 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 11:41:50.794  5613  5613 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 11:41:55.291  5613  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 11:41:55.291  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-24 11:41:55.291  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-24 11:41:55.291  5613  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 11:41:55.292  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-24 11:41:55.292  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 11:41:55.292  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 11:41:55.292  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 11:41:55.292  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:55.292  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-24 11:41:55.293  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-24 11:41:55.293  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:55.293  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:55.293  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:41:55.293  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 11:41:55.294  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:55.296  5613  5660 D BluetoothAdapter: STATE_ON
11-24 11:41:55.296  4600  4807 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-24 11:41:55.297  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-24 11:41:55.298  4600  4665 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 11:41:55.300  5613  5660 D BluetoothAdapter: STATE_ON
11-24 11:41:55.301  4600  4613 D BtGatt.GattService: stopScan() - queue size =1
11-24 11:41:55.303  4600  4611 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 11:41:55.304  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 11:41:55.305  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:55.305  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 11:41:55.305  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:55.305  4600  4600 D BtGatt.ScanManager: awakened up at time 96244
11-24 11:41:55.305  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:55.305  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:55.306  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:55.306  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 11:41:55.306  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:55.306  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:55.306  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:55.307  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 11:41:55.307  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 11:41:55.308   929  3413 I ActivityManager: Killing 5284:com.android.settings/1000 (adj 15): empty #17
,11-24 11:41:55.336  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-24 11:41:55.337  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:55.338  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:55.338  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 11:41:55.339  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:55.339  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:41:55.339  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 11:41:55.339  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 11:41:55.339  5613  5613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 11:41:55.339  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 11:41:55.339  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 11:41:55.339  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 11:41:55.340  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 11:41:55.340  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 11:41:55.340  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 11:41:55.340  5613  5613 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 11:41:55.340  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 11:41:55.340  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 11:41:55.341  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 11:41:55.341  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-24 11:41:55.341  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-24 11:41:55.350  4600  4650 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
11-24 11:41:55.350  4600  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 11:41:55.351  4600  4650 D BtGatt.GattService: current time is 96290069556
11-24 11:41:55.351  4600  4650 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -89, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -94, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -86, 96, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -82, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-24 11:41:55.351  4600  4650 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-24 11:41:55.351  4600  4650 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-24 11:41:55.352  4600  4650 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-24 11:41:55.352  4600  4650 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-24 11:41:55.357  4600  4650 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 11:41:55.357  4600  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:41:55.357  4600  4665 D BtGatt.ScanManager: stopping BLe Batch
,11-24 11:41:55.363  4600  4650 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 11:41:55.363  4600  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:41:55.363  4600  4665 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 11:41:55.369  4600  4650 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 11:41:55.369  4600  4650 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 11:41:55.840  5613  5613 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
11-24 11:41:55.841  5613  5613 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 11:41:55.841  5613  5613 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 11:41:56.107   929  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 11:41:56.114   929  2987 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,11-24 11:41:59.131   929  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 11:41:59.136   929  2987 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,11-24 11:42:00.341  5613  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 11:42:00.341  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:42:00.342  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:42:00.342  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:42:00.342  5613  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-24 11:42:00.342  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 11:42:00.342  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:42:00.342  5613  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ff4cc9 not in the list
11-24 11:42:00.343  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 11:42:00.343  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:42:00.343  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:42:00.343  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 11:42:00.345  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:00.346  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.350  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:00.350  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.350  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.350  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 11:42:00.351  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 11:42:00.351  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 11:42:00.351  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
,11-24 11:42:00.352  5613  5660 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-24 11:42:00.354  5613  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 11:42:00.355  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:42:00.355  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:42:00.355  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 11:42:00.355  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:42:00.355  5613  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ff4cc9 not in the list
11-24 11:42:00.355  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 11:42:00.356  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:42:00.356  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:42:00.356  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.356  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.359  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.359  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:00.359  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.360  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:42:00.360  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:42:00.360  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:00.360  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
,11-24 11:42:00.362  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-24 11:42:00.363  5613  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:42:00.363  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:42:00.363  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:42:00.363  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 11:42:00.363  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:42:00.363  5613  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ff4cc9 not in the list
11-24 11:42:00.363  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:00.363  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:42:00.363  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:42:00.363  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:00.364  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.366  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.366  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.366  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.366  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 11:42:00.366  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:42:00.366  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:00.366  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:42:00.367  5613  5660 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-24 11:42:00.368  5613  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:42:00.368  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 11:42:00.368  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:42:00.368  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:42:00.368  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:42:00.368  5613  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ff4cc9 not in the list
,11-24 11:42:00.368  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 11:42:00.368  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:42:00.368  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:42:00.368  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.369  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.370  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.370  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.370  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:00.370  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:42:00.370  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:42:00.370  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:00.371  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:42:00.372  5613  5660 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-24 11:42:00.372  5613  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:42:00.372  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:42:00.372  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:42:00.372  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 11:42:00.372  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:42:00.372  5613  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ff4cc9 not in the list
11-24 11:42:00.372  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:00.372  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:42:00.373  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:42:00.373  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.373  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:00.375  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.375  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.375  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.375  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:42:00.375  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:42:00.375  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:00.376  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
,11-24 11:42:00.377  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 11:42:00.377  5613  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 11:42:00.377  5613  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 11:42:00.377  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 11:42:00.378  5613  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 11:42:00.378  5613  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 11:42:00.378  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 11:42:00.378  5613  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 11:42:00.378  5613  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 11:42:00.378  5613  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:42:00.378  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 11:42:00.378  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:42:00.378  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:42:00.378  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:42:00.378  5613  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ff4cc9 not in the list
11-24 11:42:00.378  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:00.379  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:42:00.379  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:42:00.379  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.379  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:00.380  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:00.380  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.380  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.380  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:42:00.381  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:42:00.381  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:00.381  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:42:00.381  5613  5660 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 11:42:00.382  5613  5660 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-24 11:42:00.382  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-24 11:42:00.385  5613  5660 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-24 11:42:00.385  5613  5660 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-24 11:42:00.385  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-24 11:42:00.385  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-24 11:42:00.385  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-24 11:42:00.385  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,11-24 11:42:00.385  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-24 11:42:00.385  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-24 11:42:00.385  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-24 11:42:00.385  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-24 11:42:00.385  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-24 11:42:00.385  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,11-24 11:42:00.386  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,11-24 11:42:00.386  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-24 11:42:00.386  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-24 11:42:00.386  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-24 11:42:00.386  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-24 11:42:00.386  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-24 11:42:00.386  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-24 11:42:00.386  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-24 11:42:00.386  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-24 11:42:00.386  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-24 11:42:00.386  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-24 11:42:00.386  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-24 11:42:00.386  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-24 11:42:00.386  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-24 11:42:00.386  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,11-24 11:42:00.386  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-24 11:42:00.386  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-24 11:42:00.386  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-24 11:42:00.386  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-24 11:42:00.387  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-24 11:42:00.387  5613  5660 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-24 11:42:00.387  5613  5660 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 11:42:00.387  5613  5660 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-24 11:42:00.387  5613  5660 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 11:42:00.387  5613  5660 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 11:42:00.387  5613  5660 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-24 11:42:00.387  5613  5660 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 11:42:00.387  5613  5660 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 11:42:00.387  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-24 11:42:00.391  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-24 11:42:00.392  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-24 11:42:00.392  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-24 11:42:00.392  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-24 11:42:00.392  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,11-24 11:42:00.393  5613  5660 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-24 11:42:00.393  5613  5660 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 11:42:00.393  5613  5660 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-24 11:42:00.393  5613  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 123)
11-24 11:42:00.393  5613  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-24 11:42:00.393  5613  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-24 11:42:00.393  5613  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-24 11:42:00.394  5613  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 11:42:00.394  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 11:42:00.394  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:42:00.394  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:42:00.394  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:42:00.394  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-24 11:42:00.395  5613  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ff4cc9 not in the list
11-24 11:42:00.395  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:00.395  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:42:00.395  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:42:00.395  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.397  4807  4807 W Binder_5: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31492]" dev="sockfs" ino=31492 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 11:42:00.397  4807  4807 W Binder_5: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[31492]" dev="sockfs" ino=31492 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 11:42:00.396  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.397  5613  5668 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-24 11:42:00.397  5613  5668 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 11:42:00.397  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.398  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.398  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.398  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:42:00.398  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:42:00.398  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 11:42:00.398  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:42:00.397  5613  5669 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 123
11-24 11:42:00.399  5613  5660 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-24 11:42:00.399  5613  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:42:00.400  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:42:00.400  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:42:00.400  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:42:00.400  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:42:00.400  5613  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ff4cc9 not in the list
11-24 11:42:00.400  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:00.400  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:42:00.400  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:42:00.400  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.400  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.401  5613  5669 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-24 11:42:00.401  5613  5669 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 123)
11-24 11:42:00.401  5613  5668 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
11-24 11:42:00.401  5613  5669 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 123)
11-24 11:42:00.401  5613  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-24 11:42:00.401  5613  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 123)
11-24 11:42:00.403  4600  4795 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 5, channel: -1
11-24 11:42:00.403  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.403  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.404  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.404  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:42:00.404  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:42:00.404  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:00.405  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSett,ings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:42:00.405  5613  5660 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-24 11:42:00.405  5613  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:42:00.406  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:42:00.406  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:42:00.406  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:42:00.406  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:42:00.406  5613  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ff4cc9 not in the list
11-24 11:42:00.406  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:00.408  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:42:00.408  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:42:00.408  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.408  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:00.409  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.409  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.409  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.409  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:42:00.410  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:42:00.410  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:00.410  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
,11-24 11:42:00.410  5613  5660 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-24 11:42:00.410  5613  5660 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-24 11:42:00.410  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 11:42:00.411  5613  5660 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-24 11:42:00.411  5613  5660 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,11-24 11:42:00.411  5613  5660 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-24 11:42:00.411  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 11:42:00.411  5613  5660 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-24 11:42:00.411  5613  5660 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,11-24 11:42:00.411  5613  5660 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-24 11:42:00.411  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 11:42:00.411  5613  5660 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-24 11:42:00.411  5613  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:42:00.411  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:42:00.411  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 11:42:00.411  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:42:00.411  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:42:00.412  5613  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ff4cc9 not in the list
11-24 11:42:00.412  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:00.412  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
,11-24 11:42:00.412  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:42:00.412  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.412  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.413  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.413  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:00.413  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:00.413  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:42:00.413  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:42:00.413  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:00.413  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:42:00.414  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:42:00.414  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 11:42:00.414  5613  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ff4cc9 not in the list
11-24 11:42:00.414  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:00.414  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:42:00.414  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 11:42:05.415  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 11:42:05.415  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:42:05.415  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:42:05.416  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:42:05.416  5613  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ff4cc9 not in the list
11-24 11:42:05.416  5613  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:42:05.416  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:42:05.416  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 11:42:05.417  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:42:05.417  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:42:05.417  5613  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ff4cc9 not in the list
11-24 11:42:05.417  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 11:42:05.418  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:42:05.418  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:42:05.418  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:05.418  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:05.421  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:05.422  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:05.422  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:05.422  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 11:42:05.422  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:42:05.422  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:05.422  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
,11-24 11:42:05.427  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-24 11:42:05.428  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 11:42:05.428  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 11:42:05.433  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-24 11:42:05.435  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-24 11:42:05.435  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-24 11:42:05.435  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-24 11:42:05.436  5613  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-24 11:42:05.436  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-24 11:42:05.436  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 11:42:05.436  5613  5613 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-24 11:42:05.436  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:42:05.436  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-24 11:42:05.437  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-24 11:42:05.437  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-24 11:42:05.437  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-24 11:42:05.437  5613  5670 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 11:42:05.437  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-24 11:42:05.438  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-24 11:42:05.438  5613  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ff4cc9 not in the list
,11-24 11:42:05.438  5613  5613 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-24 11:42:05.438  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:05.438  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 11:42:05.438  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:05.438  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 11:42:05.438  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 11:42:05.438  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:05.437  4797  4797 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[29460]" dev="sockfs" ino=29460 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 11:42:05.439  5613  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-24 11:42:05.440  5613  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-24 11:42:05.440  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:05.440  5613  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-24 11:42:05.440  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-24 11:42:05.440  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:05.440  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:05.440  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:42:05.440  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 11:42:05.440  5613  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:42:05.440  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 11:42:05.440  5613  5613 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-24 11:42:05.440  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:42:05.440  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:42:05.440  5613  5613 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-24 11:42:05.440  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:42:05.440  5613  5613 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:42:05.441  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:42:05.441  5613  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ff4cc9 not in the list
,11-24 11:42:05.441  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:05.441  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:42:05.441  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:42:05.441  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:05.437  4797  4797 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[29460]" dev="sockfs" ino=29460 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 11:42:05.441  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:05.443  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:05.443  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:05.443  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:05.444  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:42:05.444  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:42:05.444  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:05.444  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:42:05.446  5613  5660 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-24 11:42:05.446  5613  5660 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-24 11:42:05.446  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-24 11:42:05.446  5613  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 11:42:05.446  5613  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 11:42:05.446  5613  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:42:05.446  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:42:05.446  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:42:05.447  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 11:42:05.447  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:42:05.447  5613  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ff4cc9 not in the list
11-24 11:42:05.447  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:05.447  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:42:05.448  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:42:05.448  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:05.449  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:05.455  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:05.455  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:05.455  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:05.455  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:42:05.455  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:42:05.455  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:05.455  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
,11-24 11:42:05.461  5613  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 11:42:05.461  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:42:05.461  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:42:05.461  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:42:05.461  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:42:05.461  5613  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ff4cc9 not in the list
11-24 11:42:05.461  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:05.461  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
,11-24 11:42:05.461  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 11:42:05.462  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:05.462  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:05.463  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:05.463  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:05.463  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:05.463  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:42:05.463  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:42:05.463  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 11:42:05.463  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:42:05.464  5613  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:42:05.464  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:42:05.464  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:42:05.464  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:42:05.465  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:42:05.465  5613  5660 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9ff4cc9 not in the list
,11-24 11:42:05.465  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:05.465  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:42:05.465  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:42:05.465  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:05.465  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:05.466  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:05.466  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:05.466  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:05.466  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:42:05.466  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:42:05.466  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:05.466  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78f1fce not in the list
11-24 11:42:05.467  5613  5660 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-24 11:42:05.467  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 11:42:05.467  5613  5660 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-24 11:42:05.467  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-24 11:42:05.467  5613  5660 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-24 11:42:05.467  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 11:42:05.470  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-24 11:42:05.470  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,11-24 11:42:05.471  5613  5660 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,11-24 11:42:05.471  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-24 11:42:05.472  5613  5660 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-24 11:42:05.472  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-24 11:42:05.472  5613  5660 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-24 11:42:05.472  5613  5660 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-24 11:42:05.472  5613  5660 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-24 11:42:05.472  5613  5660 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-24 11:42:05.473  5613  5660 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-24 11:42:05.473  5613  5660 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,11-24 11:42:05.473  5613  5660 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-24 11:42:05.473  5613  5660 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-24 11:42:05.474  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:42:05.474  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d2a01df added. We now have 3 listener(s)
11-24 11:42:05.475  5613  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 11:42:05.476  5613  5660 D BluetoothAdapter: enable(): BT is already enabled..!
11-24 11:42:05.476   929  3820 D WifiService: setWifiEnabled: true pid=5613, uid=10077
11-24 11:42:05.476   929  3820 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 11:42:05.529  4600  4769 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-24 11:42:05.529  4600  4769 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-24 11:42:05.940  5613  5613 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 11:42:08.214   929  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 11:42:10.481  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 11:42:10.482  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8eeee2c added. We now have 4 listener(s)
11-24 11:42:10.482  5613  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 11:42:10.495  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 11:42:10.495  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8eeee2c removed from the list
,11-24 11:42:10.495  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:42:10.497  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:42:10.497  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c5500f5 added. We now have 4 listener(s)
11-24 11:42:10.498  5613  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 11:42:10.502  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 11:42:10.502  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c5500f5 removed from the list
,11-24 11:42:10.503  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 11:42:10.504  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 11:42:10.505  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8fa3e8a added. We now have 4 listener(s)
,11-24 11:42:10.505  5613  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 11:42:10.509   929   939 D WifiService: setWifiEnabled: false pid=5613, uid=10077
,11-24 11:42:10.510   929   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 11:42:10.520   929  2985 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-24 11:42:10.520   929  2985 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-24 11:42:10.520   929  2985 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 11:42:10.521   929  2985 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 11:42:10.526  4600  4646 D BluetoothAdapterState: Current state: ON, message: 23
11-24 11:42:10.526  4600  4646 D BluetoothAdapterProperties: Setting state to 13
11-24 11:42:10.526  4600  4646 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-24 11:42:10.527  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 11:42:10.527  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-24 11:42:10.529  4600  4646 D BluetoothAdapterProperties: onBluetoothDisable()
,11-24 11:42:10.530  4600  4646 I BluetoothAdapterState: Entering PendingCommandState
,11-24 11:42:10.534  4600  4600 D BluetoothMapService: onReceive
11-24 11:42:10.535  4600  4600 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 11:42:10.535  4600  4600 D BluetoothMapService: STATE_TURNING_OFF
11-24 11:42:10.535  4600  4600 D BluetoothMapService: MAP Service closeService in
11-24 11:42:10.535  4600  4600 D BluetoothMapMasInstance0: MAP Service shutdown
,11-24 11:42:10.535  4600  4600 D ObexServerSockets0: shutdown(block = true)
11-24 11:42:10.537  4600  4600 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 11:42:10.537  4600  4600 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 11:42:10.537  4600  4809 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-24 11:42:10.538  4600  4795 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-24 11:42:10.538  4600  4810 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-24 11:42:10.540   929  5355 D DhcpClient: Clearing IP address
11-24 11:42:10.540   509   922 D CommandListener: Clearing all IP addresses on wlan0
11-24 11:42:10.542  4600  4600 I BtOppRfcommListener: stopping Accept Thread
11-24 11:42:10.542  4600  5309 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-24 11:42:10.542  4600  5309 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-24 11:42:10.548   509   922 D CommandListener: Setting iface cfg
,11-24 11:42:10.555   929   942 I ActivityManager: Start proc 5674:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-24 11:42:10.556   929  5356 D DhcpClient: Receive thread stopped
11-24 11:42:10.558  3578  5406 V NativeCrypto: Read error: ssl=0x7f77ec5100: I/O error during system call, Connection timed out
,11-24 11:42:10.561  4600  4650 D BluetoothAdapterProperties: Scan Mode:20
11-24 11:42:10.564  4600  4646 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-24 11:42:10.567  4600  4600 D HeadsetService: Received stop request...Stopping profile...
,11-24 11:42:10.568   929  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-24 11:42:10.568   929  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-24 11:42:10.568  3114  3989 D BluetoothHeadset: Proxy object disconnected
,11-24 11:42:10.569  3757  4013 D BluetoothHeadset: Proxy object disconnected
11-24 11:42:10.570   929   929 D BluetoothHeadset: Proxy object disconnected
11-24 11:42:10.570   929   929 D BluetoothHeadset: Proxy object disconnected
11-24 11:42:10.570   929   929 D BluetoothHeadset: Proxy object disconnected
,11-24 11:42:10.571  5613  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 11:42:10.572  4600  4600 D A2dpService: Received stop request...Stopping profile...
11-24 11:42:10.572  5613  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 11:42:10.572  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 11:42:10.572  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 11:42:10.572  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 11:42:10.572  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 11:42:10.572  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 11:42:10.572  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - SSID name: <unknown ssid>
11-24 11:42:10.572  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 11:42:10.572  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 11:42:10.572  4600  4800 D A2dpStateMachine: Exit Disconnected: -1
11-24 11:42:10.573  3578  5406 V NativeCrypto: SSL shutdown failed: ssl=0x7f77ec5100: I/O error during system call, Broken pipe
11-24 11:42:10.573  5613  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 11:42:10.573  5613  5660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: <unknown ssid>
11-24 11:42:10.573  5613  5660 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 11:42:10.576   621   621 E Parcel  : Reading a NULL string not supported here.
,11-24 11:42:10.578   929  2987 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-24 11:42:10.579  3114  3114 D HeadsetProfile: Bluetooth service disconnected
11-24 11:42:10.579  3114  3114 D BluetoothA2dp: Proxy object disconnected
11-24 11:42:10.582  3726  3857 W QCNEJ   : |CORE| network lost: 100
11-24 11:42:10.583  3726  3857 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-24 11:42:10.583  5613  5613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 11:42:10.583  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 11:42:10.583  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 11:42:10.583  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 11:42:10.583  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 11:42:10.583  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 11:42:10.583  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 11:42:10.583  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 11:42:10.583  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 11:42:10.583  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 11:42:10.583   929   929 D RttService: SCAN_AVAILABLE : 1
11-24 11:42:10.584   929   929 D BluetoothA2dp: Proxy object disconnected
11-24 11:42:10.584   929  3039 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-24 11:42:10.584  4600  4600 V BluetoothAdapterState: isTurningOff()=true
11-24 11:42:10.584  4600  4600 V BluetoothAdapterState: isTurningOn()=false
11-24 11:42:10.584  4600  4600 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:42:10.584  4600  4600 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:42:10.585  5613  5613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 11:42:10.585  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 11:42:10.588  5613  5613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 11:42:10.588  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 11:42:10.588  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 11:42:10.588  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 11:42:10.588  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 11:42:10.588  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 11:42:10.588  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 11:42:10.588  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 11:42:10.588  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 11:42:10.588  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 11:42:10.588  4600  4600 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-24 11:42:10.588  4600  4600 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-24 11:42:10.588  4600  4769 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 11:42:10.588  4600  4769 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 11:42:10.588  4600  4769 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 11:42:10.589  4600  4650 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-24 11:42:10.589  4600  4650 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,11-24 11:42:10.590  4600  4600 D HidService: Received stop request...Stopping profile...
,11-24 11:42:10.590  4600  4600 D HidService: Stopping Bluetooth HidService
11-24 11:42:10.591  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 11:42:10.593  3114  3114 D BluetoothInputDevice: Proxy object disconnected
11-24 11:42:10.593  3114  3114 D HidProfile: Bluetooth service disconnected
11-24 11:42:10.593   929  2985 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-24 11:42:10.593  4600  4600 D HealthService: Received stop request...Stopping profile...
11-24 11:42:10.594  4600  4600 V BluetoothAdapterState: isTurningOff()=true
11-24 11:42:10.594  4600  4600 V BluetoothAdapterState: isTurningOn()=false
,11-24 11:42:10.594  4600  4600 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:42:10.595  4600  4600 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 11:42:10.597  4600  4600 D PanService: Received stop request...Stopping profile...
,11-24 11:42:10.599  3114  3114 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-24 11:42:10.600  3114  3114 D PanProfile: Bluetooth service disconnected
,11-24 11:42:10.602  4600  4769 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-24 11:42:10.603  4600  4769 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 11:42:10.603  4600  4650 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-24 11:42:10.603  4600  4600 D BluetoothMapService: Received stop request...Stopping profile...
11-24 11:42:10.603  4600  4769 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 11:42:10.603  4600  4600 D BluetoothMapService: stop()
11-24 11:42:10.603  4600  4769 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 11:42:10.603  4600  4769 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 11:42:10.603  4600  4769 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 11:42:10.604  4600  4600 D BluetoothMapAppObserver: deinitObservers()
11-24 11:42:10.604  4600  4600 D BluetoothMapAppObserver: removeReceiver()
,11-24 11:42:10.605  3114  3114 D BluetoothMap: Proxy object disconnected
,11-24 11:42:10.605  3114  3114 D MapProfile: Bluetooth service disconnected
11-24 11:42:10.605  4600  4600 D SapService: Received stop request...Stopping profile...
11-24 11:42:10.606  4600  4600 V SapService: stop()
11-24 11:42:10.607  4600  4600 V BluetoothAdapterState: isTurningOff()=true
11-24 11:42:10.607  4600  4600 V BluetoothAdapterState: isTurningOn()=false
11-24 11:42:10.607  4600  4600 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:42:10.607  4600  4600 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:42:10.607  4600  4600 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-24 11:42:10.607  4600  4600 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-24 11:42:10.607  4600  4650 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-24 11:42:10.608  4600  4600 V BluetoothAdapterState: isTurningOff()=true
11-24 11:42:10.608  4600  4600 V BluetoothAdapterState: isTurningOn()=false
11-24 11:42:10.608  4600  4600 V BluetoothAdapterState: isBleTurningOn()=false
,11-24 11:42:10.608  4600  4600 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:42:10.608  4600  4600 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-24 11:42:10.608  4600  4650 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-24 11:42:10.608  4600  4600 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-24 11:42:10.609   929  2985 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 11:42:10.609  4600  4600 V BluetoothAdapterState: isTurningOff()=true
11-24 11:42:10.609  4600  4600 V BluetoothAdapterState: isTurningOn()=false
11-24 11:42:10.609  4600  4600 V BluetoothAdapterState: isBleTurningOn()=false
,11-24 11:42:10.609  4600  4600 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 11:42:10.609  4600  4600 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-24 11:42:10.609  4600  4600 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-24 11:42:10.610  4600  4600 D BluetoothMapService: MAP Service closeService in
11-24 11:42:10.611  4600  4600 V BluetoothAdapterState: isTurningOff()=true
11-24 11:42:10.611  4600  4600 V BluetoothAdapterState: isTurningOn()=false
11-24 11:42:10.611  4600  4600 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:42:10.611  4600  4600 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:42:10.611  4600  4600 D BluetoothMapService: cleanup()
11-24 11:42:10.611  4600  4600 D BluetoothMapService: MAP Service closeService in
11-24 11:42:10.611  4600  4600 V BluetoothAdapterState: isTurningOff()=true
,11-24 11:42:10.611  4600  4600 V BluetoothAdapterState: isTurningOn()=false
11-24 11:42:10.611  4600  4600 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:42:10.612  4600  4600 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:42:10.612  4600  4646 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-24 11:42:10.612  4600  4646 D BluetoothAdapterProperties: Setting state to 15
,11-24 11:42:10.612  4600  4646 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-24 11:42:10.612  4600  4646 I BluetoothAdapterState: Entering BleOnState
11-24 11:42:10.612  3114  3128 D BluetoothPan: onBluetoothStateChange on: false
11-24 11:42:10.613  3114  3989 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 11:42:10.614   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 11:42:10.614  3757  3779 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 11:42:10.614   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 11:42:10.614  3114  3981 D BluetoothMap: onBluetoothStateChange: up=false
11-24 11:42:10.615   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 11:42:10.615   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 11:42:10.615  3114  3128 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 11:42:10.616  3114  3989 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 11:42:10.616  3114  3126 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-24 11:42:10.617  4600  4646 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-24 11:42:10.617  4600  4646 D BluetoothAdapterProperties: Setting state to 16
11-24 11:42:10.617  4600  4646 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-24 11:42:10.618  4600  4646 D BluetoothAdapterProperties: onBleDisable
11-24 11:42:10.618  4600  4646 I BluetoothAdapterState: Entering PendingCommandState
11-24 11:42:10.618  4600  4647 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-24 11:42:10.618  4600  4650 D BluetoothAdapterProperties: Scan Mode:20
11-24 11:42:10.619  4600  4769 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-24 11:42:10.620  4600  4769 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 11:42:10.620  5674  5674 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
11-24 11:42:10.620  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 11:42:10.623  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 11:42:10.627   509   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 11:42:10.636  5674  5674 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 11:42:10.642   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e96959:true
,11-24 11:42:10.643  3578  3578 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 11:42:10.650   509   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-24 11:42:10.650   509   922 D CommandListener: Clearing all IP addresses on wlan0
11-24 11:42:10.651   929  2987 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-24 11:42:10.652   929  2987 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-24 11:42:10.654   929  2985 D DhcpClient: doQuit
11-24 11:42:10.654   929   946 D Tethering: MasterInitialState.processMessage what=3
11-24 11:42:10.654   929  2985 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-24 11:42:10.655  3437  3437 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-24 11:42:10.655   929  5355 D DhcpClient: onQuitting
11-24 11:42:10.655  5261  5261 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@39824f9 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-24 11:42:10.656  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 11:42:10.658  3963  3963 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-24 11:42:10.661  5613  5613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 11:42:10.661  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 11:42:10.661  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 11:42:10.661  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 11:42:10.661  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 11:42:10.661  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 11:42:10.661  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 11:42:10.661  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 11:42:10.661  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 11:42:10.661  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 11:42:10.662  5613  5613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 11:42:10.662  4937  4962 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-24 11:42:10.662  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 11:42:10.662  4937  4962 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 11:42:10.662  4937  4962 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-24 11:42:10.662  4937  4962 E SarControlService: no key has been found,reset the power
,11-24 11:42:10.662  4937  4985 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,11-24 11:42:10.662  4937  4985 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 11:42:10.662  4937  4985 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 11:42:10.663  4973  4973 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 11:42:10.663  4973  4973 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 11:42:10.664  4937  4985 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 11:42:10.664  4937  4985 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 11:42:10.664  4937  4985 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 11:42:10.665  4973  4973 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 11:42:10.665  4973  4973 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-24 11:42:10.670  4973  4988 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@bc6a1e7 HexData = [00000000ea03000000000000ffffffff]
,11-24 11:42:10.671  4973  4988 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 11:42:10.671  4973  4988 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-24 11:42:10.671  4973  4973 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 11:42:10.671  4937  4949 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-24 11:42:10.677  4973  4988 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@bc6a1e7 HexData = [00000000eb03000000000000ffffffff]
,11-24 11:42:10.677  4973  4988 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 11:42:10.677  4973  4988 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,11-24 11:42:10.678  4973  4973 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 11:42:10.678  4937  4951 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-24 11:42:10.678  3437  3437 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-24 11:42:10.680  5674  5674 D LocalBluetoothProfileManager: Adding local MAP profile
,11-24 11:42:10.683  3437  3437 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-24 11:42:10.685  5674  5674 D BluetoothMap: Create BluetoothMap proxy object
,11-24 11:42:10.692  5674  5674 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-24 11:42:10.698  5674  5674 D DockEventReceiver: finishStartingService: stopping service
,11-24 11:42:10.701  5674  5674 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 11:42:10.703   509   922 E Netd    : netlink response contains error (No such file or directory)
,11-24 11:42:10.707  5674  5674 D DockEventReceiver: finishStartingService: stopping service
,11-24 11:42:10.707  3578  3578 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 11:42:10.709   929  3827 I ActivityManager: Killing 5381:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-24 11:42:10.712  3437  3437 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-24 11:42:10.718  3437  3437 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-24 11:42:10.742  3828  3828 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-24 11:42:10.745  3828  3828 D SystemUpdateService: onCreate
,11-24 11:42:10.748  3828  3828 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 11:42:10.755  3828  3828 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-24 11:42:10.760  3828  5378 I iu.UploadsManager: num queued entries: 0
,11-24 11:42:10.760  3828  5378 I iu.UploadsManager: num updated entries: 0
,11-24 11:42:10.762  3828  5699 I SystemUpdateService: active receiver: enabled
,11-24 11:42:10.765  3828  3828 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 11:42:10.766  3828  3828 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 11:42:10.770  3828  5699 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 11:42:10.770  3828  5378 I iu.SyncManager: NEXT; no task
,11-24 11:42:10.774  3828  5699 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-24 11:42:10.774  3828  5699 I SystemUpdateService: now status is 0 (complete)
11-24 11:42:10.774  3828  5699 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 11:42:10.774  3828  5699 I SystemUpdateService: file has been verified
11-24 11:42:10.774  3828  5699 I SystemUpdateService: OTA package size = 21989297
,11-24 11:42:10.778   929  3827 I ActivityManager: Start proc 5701:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-24 11:42:10.783  3828  5699 I SystemUpdateService: showing system update notification
,11-24 11:42:10.795   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-24 11:42:10.800  3828  3828 D SystemUpdateService: onDestroy
,11-24 11:42:10.820   929  2985 D wifi    : In wifi stop Hal
,11-24 11:42:10.821   929  2985 D wifi    : halHandle = 0x7f76b0d400, mVM = 0x7f9314d140, mCls = 0x100a02
11-24 11:42:10.821  4299  4299 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 11:42:10.821   929  3435 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,11-24 11:42:10.821   929  3435 D WifiHAL : Got a signal to exit!!!
11-24 11:42:10.821   929  3435 I WifiHAL : Exit wifi_event_loop
11-24 11:42:10.823   929  2985 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-24 11:42:10.823  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 11:42:10.823   929  2985 E WifiHAL : Event processing terminated
11-24 11:42:10.823   929  2985 D wifi    : In wifi cleaned up handler
11-24 11:42:10.823   929  2985 I WifiHAL : Internal cleanup completed
11-24 11:42:10.827  4042  4221 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 11:42:10.828  4600  4650 I bt_hci  : shut_down
,11-24 11:42:10.832  4600  4666 I bt_vendor: low_power_mode_cb
11-24 11:42:10.837  5701  5701 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
11-24 11:42:10.837  4600  4666 D bt_hwcfg: hw_epilog_process
,11-24 11:42:10.840  5701  5701 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 11:42:10.841  4600  4666 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-24 11:42:10.841  4600  4666 I bt_vendor: epilog_cb
11-24 11:42:10.841  4600  4666 I bt_hci  : epilog_finished_callback
,11-24 11:42:10.843  4600  4650 I bt_hci_h4: hal_close
,11-24 11:42:10.844  4600  4650 I bt_userial_vendor: device fd = 54 close
11-24 11:42:10.845   929  3435 D wifi    : set interface wlan0 flags (DOWN)
11-24 11:42:10.845   929  2985 D WifiNative-HAL: HAL event thread stopped successfully
,11-24 11:42:10.850  5701  5701 D SprintDMHelper: simOperator: 
11-24 11:42:10.850  5701  5701 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-24 11:42:10.860  4299  5715 I Babel   : connection state changed from CONNECTED to DISCONNECTED
11-24 11:42:10.865   929  3413 I ActivityManager: Killing 5261:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-24 11:42:10.905   929  3820 I ActivityManager: Start proc 5720:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-24 11:42:10.908   509   922 E Netd    : netlink response contains error (No such file or directory)
,11-24 11:42:10.932  5720  5720 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-24 11:42:10.939   929  3820 I ActivityManager: Killing 5453:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-24 11:42:10.949  4600  4647 D bt_stack_manager: event_shut_down_stack finished.
,11-24 11:42:10.950  4600  4646 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-24 11:42:10.956  4600  4600 D BtGatt.DebugUtils: handleDebugAction() action=null
11-24 11:42:10.956  4600  4646 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-24 11:42:10.956  4600  4600 D BtGatt.GattService: Received stop request...Stopping profile...
11-24 11:42:10.957  4600  4600 D BtGatt.GattService: stop()
,11-24 11:42:10.957  4600  4600 D BtGatt.AdvertiseManager: advertise clients cleared
,11-24 11:42:10.959  4600  4600 V BluetoothAdapterState: isTurningOff()=false
11-24 11:42:10.959  4600  4600 V BluetoothAdapterState: isTurningOn()=false
11-24 11:42:10.959  4600  4600 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:42:10.959  4600  4600 V BluetoothAdapterState: isBleTurningOff()=true
11-24 11:42:10.960  4600  4646 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-24 11:42:10.960  4600  4646 D BluetoothAdapterProperties: Setting state to 10
,11-24 11:42:10.960  4600  4646 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-24 11:42:10.962  4600  4646 I BluetoothAdapterState: Entering OffState
11-24 11:42:10.962   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-24 11:42:10.969  4600  4600 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-24 11:42:10.969  4600  4600 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-24 11:42:10.969  4600  4600 I BluetoothServiceJni: cleanupNative: return from cleanup
11-24 11:42:10.970  4600  4647 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-24 11:42:10.981  4600  4647 D bt_stack_manager: event_clean_up_stack finished.
,11-24 11:42:10.982  4600  4600 I art     : System.exit called, status: 0
,11-24 11:42:10.982  4600  4600 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-24 11:42:11.008   929   940 I ActivityManager: Process com.android.bluetooth (pid 4600) has died
,11-24 11:42:11.047   929   946 D Tethering: InitialState.processMessage what=4
,11-24 11:42:11.051   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-24 11:42:12.555   623   623 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 11:42:12.555   623   623 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 11:42:15.576   929  3149 D WifiService: setWifiEnabled: true pid=5613, uid=10077
,11-24 11:42:15.577   929  3149 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 11:42:15.585   509   922 D SoftapController: Softap fwReload - Ok
,11-24 11:42:15.591   509   922 D CommandListener: Setting iface cfg
11-24 11:42:15.591   509   922 D CommandListener: Trying to bring down wlan0
,11-24 11:42:15.593   509   922 D CommandListener: Clearing all IP addresses on wlan0
,11-24 11:42:15.598   929  2985 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 11:42:16.167   929  2985 D wifi    : set interface wlan0 flags (UP)
,11-24 11:42:16.172   929  2985 I WifiHAL : Initializing wifi
11-24 11:42:16.172   929  2985 I WifiHAL : Creating socket
,11-24 11:42:16.177   929  2985 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-24 11:42:16.178   929  2985 D wifi    : Did set static halHandle = 0x7f76b0d400
11-24 11:42:16.178   929  2985 D wifi    : halHandle = 0x7f76b0d400, mVM = 0x7f9314d140, mCls = 0x1976
11-24 11:42:16.178   929  2985 D wifi    : array field set
11-24 11:42:16.179   929  2985 I WifiNative-HAL: interface[0] = wlan0
11-24 11:42:16.180   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-24 11:42:16.180   929  5737 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547452146688
11-24 11:42:16.180   929  5737 D wifi    : waitForHalEvents called, vm = 0x7f9314d140, obj = 0x1976, env = 0x7f742e88c0
,11-24 11:42:16.266  5738  5738 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-24 11:42:16.283   929  2985 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-24 11:42:16.287  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 11:42:16.348  5738  5738 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 11:42:16.379  5738  5738 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 11:42:16.379  5738  5738 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-24 11:42:16.393   929  2985 D WifiConfigStore: Loading config and enabling all networks 
,11-24 11:42:16.393  5613  5613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 11:42:16.393  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 11:42:16.393  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 11:42:16.393  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 11:42:16.393  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 11:42:16.393  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 11:42:16.393  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 11:42:16.393  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 11:42:16.393  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 11:42:16.393  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 11:42:16.394  5613  5613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 11:42:16.394  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 11:42:16.417   929  2985 D WifiConfigStore: loaded 0 passpoint configs
,11-24 11:42:16.418   929  2985 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-24 11:42:16.419   929  2985 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-24 11:42:16.420   929  2985 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-24 11:42:16.420   929  2985 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-24 11:42:16.421   929  2985 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-24 11:42:16.422   929  2985 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-24 11:42:16.423   929  2985 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-24 11:42:16.423   929  2985 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-24 11:42:16.423   929  2985 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-24 11:42:16.423   929  2985 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-24 11:42:16.423   929  2985 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-24 11:42:16.423   929  2985 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-24 11:42:16.427   929  2985 D WifiNative-HAL: Setting external_sim to 1
,11-24 11:42:16.427  4299  4299 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 11:42:16.427   929  2985 D wifi    : setting dfs flag to true, 0x7f74695e40
11-24 11:42:16.428   929  2985 D WifiStateMachine: Setting OUI to DA-A1-19
,11-24 11:42:16.428   929  2985 D wifi    : setting scan oui 0x7f74695e40
11-24 11:42:16.428   929  2985 D WifiHAL : Sending mac address OUI
,11-24 11:42:16.432   929  2985 E native  : do suspend false
,11-24 11:42:16.439   929  2985 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-24 11:42:16.439   929   929 D RttService: SCAN_AVAILABLE : 3
11-24 11:42:16.439   929  3039 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-24 11:42:16.439   509   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-24 11:42:16.440   509   922 D CommandListener: Setting iface cfg
,11-24 11:42:16.444   929  2973 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '125 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 125 Failed to set address (No such device)'
,11-24 11:42:16.444   929  2973 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-24 11:42:16.452   929  2973 D WifiNative-HAL: p2pGetDeviceAddress
,11-24 11:42:16.452   929  2973 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-24 11:42:16.458   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=117397 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,11-24 11:42:17.556   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:42:18.557   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:42:18.912   929  2985 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 7, 8 -> obsolete
,11-24 11:42:19.496  5738  5738 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 11:42:19.501  5738  5738 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 11:42:19.505  5738  5738 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 11:42:19.558   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:42:19.560   929  2985 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-24 11:42:19.561   929  2985 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-24 11:42:19.562   929  2985 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 11:42:19.573   929  2985 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-24 11:42:19.606   929  2985 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-24 11:42:19.611  5738  5738 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-24 11:42:20.038  5738  5738 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-24 11:42:20.071  5738  5738 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
11-24 11:42:20.071  5738  5738 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-24 11:42:20.080   929  2985 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 11:42:20.081   929  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
11-24 11:42:20.082   929  2985 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 11:42:20.098   929  2985 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 11:42:20.112   509   922 D CommandListener: Setting iface cfg
,11-24 11:42:20.117   929  2985 D WifiStateMachine: Start Dhcp Watchdog 2
,11-24 11:42:20.127   929  5753 D DhcpClient: Receive thread started
,11-24 11:42:20.127   929  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-24 11:42:20.127   929  2985 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-24 11:42:20.128   929  2987 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-24 11:42:20.208   929  2985 E native  : do suspend false
,11-24 11:42:20.224   929  5752 D DhcpClient: Broadcasting DHCPDISCOVER
,11-24 11:42:20.238   929  5753 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172719, domain null
,11-24 11:42:20.239   929  5752 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172719 seconds
,11-24 11:42:20.241   929  5752 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-24 11:42:20.253   929  5753 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-24 11:42:20.254   929  5752 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-24 11:42:20.257   509   922 D CommandListener: Setting iface cfg
11-24 11:42:20.261   929  2985 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-24 11:42:20.268   929  5752 D DhcpClient: Scheduling renewal in 86399s
,11-24 11:42:20.280   929  2985 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-24 11:42:20.282   929  2985 D WifiConfigStore: No blacklist allowed without epno enabled
11-24 11:42:20.283   929  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-24 11:42:20.285   929  2987 D ConnectivityService: Adding iface wlan0 to network 101
11-24 11:42:20.297   929  2985 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-24 11:42:20.343   929  2987 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-24 11:42:20.343   929  2987 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
11-24 11:42:20.346   929  2987 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-24 11:42:20.350   929  2987 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-24 11:42:20.353   929  2987 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-24 11:42:20.361   929  2987 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 11:42:20.366   929  2987 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-24 11:42:20.366   929  2987 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-24 11:42:20.366   929  2987 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-24 11:42:20.366   929  2985 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-24 11:42:20.366   929  2987 D ConnectivityService:    accepting network in place of null
11-24 11:42:20.366   929  2985 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 11:42:20.367   929  2987 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 11:42:20.376   929  5751 D NetlinkSocketObserver: NeighborEvent{elapsedMs=121314, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 11:42:20.393   509   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 11:42:20.416   509   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 11:42:20.420   929  2987 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-24 11:42:20.420   929  2987 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-24 11:42:20.420  3726  3857 W QCNEJ   : |CORE| network available: 101
11-24 11:42:20.422  3726  3857 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-24 11:42:20.423   929  2987 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-24 11:42:20.425   929   946 D Tethering: MasterInitialState.processMessage what=3
11-24 11:42:20.426  3726  3857 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-24 11:42:20.426  3726  3857 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-24 11:42:20.429  5613  5613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 11:42:20.429  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 11:42:20.429  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 11:42:20.429  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 11:42:20.429  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 11:42:20.429  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 11:42:20.429  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 11:42:20.429  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 11:42:20.429  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 11:42:20.429  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 11:42:20.429  5613  5613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 11:42:20.429  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 11:42:20.437  4937  4962 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-24 11:42:20.438  4937  4962 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 11:42:20.439  4937  4962 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
,11-24 11:42:20.439  4937  4962 E SarControlService: no key has been found,reset the power
11-24 11:42:20.439  4937  4985 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 11:42:20.439  4937  4985 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 11:42:20.439  4937  4985 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 11:42:20.439  4973  4973 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 11:42:20.439  4973  4973 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 11:42:20.441  4937  4985 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 11:42:20.441  4937  4985 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 11:42:20.441  4937  4985 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 11:42:20.441  4973  4973 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 11:42:20.441  4973  4973 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 11:42:20.442  3963  3963 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-24 11:42:20.445  3828  3828 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-24 11:42:20.445   929  5750 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
11-24 11:42:20.448  4973  4988 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@bc6a1e7 HexData = [00000000ec03000000000000ffffffff]
11-24 11:42:20.448  4973  4988 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 11:42:20.448  4973  4988 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-24 11:42:20.448  4973  4988 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@bc6a1e7 HexData = [00000000ed03000000000000ffffffff]
11-24 11:42:20.448  4973  4988 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 11:42:20.448  4973  4988 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-24 11:42:20.449  4973  4973 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 11:42:20.449  4937  4949 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-24 11:42:20.449  4973  4973 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 11:42:20.449  4937  4951 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-24 11:42:20.450  3828  3828 D SystemUpdateService: onCreate
11-24 11:42:20.453  3828  3828 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 11:42:20.462  3828  3828 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-24 11:42:20.469  3828  5378 I iu.UploadsManager: num queued entries: 0
,11-24 11:42:20.469  3828  5378 I iu.UploadsManager: num updated entries: 0
11-24 11:42:20.469  3828  5378 I iu.SyncManager: NEXT; no task
,11-24 11:42:20.472  3828  3828 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 11:42:20.473  3828  3828 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 11:42:20.475  5701  5701 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-24 11:42:20.478  5701  5701 D SprintDMHelper: simOperator: 
11-24 11:42:20.479  5701  5701 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 11:42:20.488  3828  5763 I SystemUpdateService: active receiver: enabled
,11-24 11:42:20.494   929  5750 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Nov 2016 10:42:20 GMT], X-Android-Received-Millis=[1479984140493], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479984140471]}
,11-24 11:42:20.495   929  2987 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-24 11:42:20.495   929  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-24 11:42:20.496   929  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-24 11:42:20.497   929  2987 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-24 11:42:20.510  3828  5763 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 11:42:20.517  3828  5763 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-24 11:42:20.517  3828  5763 I SystemUpdateService: now status is 0 (complete)
11-24 11:42:20.517  3828  5763 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 11:42:20.517  3828  5763 I SystemUpdateService: file has been verified
11-24 11:42:20.517  3828  5763 I SystemUpdateService: OTA package size = 21989297
,11-24 11:42:20.523  3828  5763 I SystemUpdateService: showing system update notification
,11-24 11:42:20.532   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-24 11:42:20.534  3828  3828 D SystemUpdateService: onDestroy
,11-24 11:42:20.558   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:42:20.581   929  3414 D WifiService: setWifiEnabled: false pid=5613, uid=10077
,11-24 11:42:20.581   929  3414 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-24 11:42:20.582   929  2985 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-24 11:42:20.582   929  2985 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-24 11:42:20.582  4299  5768 I Babel   : connection state changed from DISCONNECTED to CONNECTED
11-24 11:42:20.582   929  2985 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 11:42:20.583   929  2985 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 11:42:20.590   929  5752 D DhcpClient: Clearing IP address
11-24 11:42:20.590   509   922 D CommandListener: Clearing all IP addresses on wlan0
,11-24 11:42:20.593   509   922 D CommandListener: Setting iface cfg
,11-24 11:42:20.599  3578  5773 V NativeCrypto: Read error: ssl=0x7f918c9a80: I/O error during system call, Connection timed out
,11-24 11:42:20.600  3578  5773 V NativeCrypto: SSL shutdown failed: ssl=0x7f918c9a80: I/O error during system call, Broken pipe
,11-24 11:42:20.601   929  5753 D DhcpClient: Receive thread stopped
11-24 11:42:20.603   929  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-24 11:42:20.603   929  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-24 11:42:20.606   621   621 E Parcel  : Reading a NULL string not supported here.
11-24 11:42:20.606   929   929 D RttService: SCAN_AVAILABLE : 1
11-24 11:42:20.607   929  3039 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-24 11:42:20.608   929  2987 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-24 11:42:20.610  3726  3857 W QCNEJ   : |CORE| network lost: 101
11-24 11:42:20.610  3726  3857 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-24 11:42:20.613   929  2985 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-24 11:42:20.618   929  2985 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 11:42:20.632   509   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 11:42:20.651   509   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 11:42:20.651   509   922 D CommandListener: Clearing all IP addresses on wlan0
,11-24 11:42:20.652   929  2987 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-24 11:42:20.652   929  2987 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-24 11:42:20.653   929  2985 D DhcpClient: doQuit
11-24 11:42:20.653   929  2985 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-24 11:42:20.653   929  5752 D DhcpClient: onQuitting
,11-24 11:42:20.653  5738  5738 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-24 11:42:20.655   929   946 D Tethering: MasterInitialState.processMessage what=3
11-24 11:42:20.656  5613  5613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 11:42:20.656  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 11:42:20.656  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 11:42:20.656  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 11:42:20.656  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 11:42:20.656  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 11:42:20.656  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 11:42:20.656  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 11:42:20.656  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 11:42:20.656  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 11:42:20.657  5613  5613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 11:42:20.657  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 11:42:20.660  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 11:42:20.662  3963  3963 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-24 11:42:20.665  3828  3828 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-24 11:42:20.666  4937  4962 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-24 11:42:20.666  4937  4962 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 11:42:20.666  4937  4962 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-24 11:42:20.666  4937  4962 E SarControlService: no key has been found,reset the power
11-24 11:42:20.666  4937  4985 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 11:42:20.666  4937  4985 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 11:42:20.666  4937  4985 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,11-24 11:42:20.667  4973  4973 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 11:42:20.667  4973  4973 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-24 11:42:20.668  4937  4985 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 11:42:20.668  4937  4985 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-24 11:42:20.669  4937  4985 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 11:42:20.669  4973  4973 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 11:42:20.669  4973  4973 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 11:42:20.672  3828  3828 D SystemUpdateService: onCreate
11-24 11:42:20.674  4973  4988 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@bc6a1e7 HexData = [00000000ee03000000000000ffffffff]
11-24 11:42:20.674  4973  4988 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-24 11:42:20.674  4973  4988 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
,11-24 11:42:20.674  4973  4973 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 11:42:20.675  4937  4951 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-24 11:42:20.675  4973  4988 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@bc6a1e7 HexData = [00000000ef03000000000000ffffffff]
11-24 11:42:20.675  4973  4988 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 11:42:20.675  4973  4988 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
,11-24 11:42:20.676  4973  4973 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 11:42:20.676  4937  4949 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-24 11:42:20.678  3828  3828 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-24 11:42:20.678  5738  5738 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-24 11:42:20.684  3828  5783 I SystemUpdateService: active receiver: enabled
,11-24 11:42:20.685  5738  5738 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-24 11:42:20.686  3828  3828 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-24 11:42:20.692  3828  5378 I iu.UploadsManager: num queued entries: 0
,11-24 11:42:20.692  3828  5378 I iu.UploadsManager: num updated entries: 0
11-24 11:42:20.693  3828  5378 I iu.SyncManager: NEXT; no task
,11-24 11:42:20.696  3828  3828 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 11:42:20.697  3828  3828 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 11:42:20.699  5701  5701 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 11:42:20.703  5701  5701 D SprintDMHelper: simOperator: 
11-24 11:42:20.703  5701  5701 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 11:42:20.713   509   922 E Netd    : netlink response contains error (No such file or directory)
,11-24 11:42:20.715   929  2987 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-24 11:42:20.713  3828  5783 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-24 11:42:20.718  4299  5787 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-24 11:42:20.720  5738  5738 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-24 11:42:20.727  3828  5783 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-24 11:42:20.727  3828  5783 I SystemUpdateService: now status is 0 (complete)
11-24 11:42:20.727  3828  5783 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 11:42:20.727  3828  5783 I SystemUpdateService: file has been verified
11-24 11:42:20.727  3828  5783 I SystemUpdateService: OTA package size = 21989297
,11-24 11:42:20.728  5738  5738 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-24 11:42:20.737  3828  5783 I SystemUpdateService: showing system update notification
,11-24 11:42:20.745   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-24 11:42:20.746  3828  3828 D SystemUpdateService: onDestroy
,11-24 11:42:20.829   929  2985 D wifi    : In wifi stop Hal
11-24 11:42:20.830   929  2985 D wifi    : halHandle = 0x7f76b0d400, mVM = 0x7f9314d140, mCls = 0x1976
11-24 11:42:20.830   929  5737 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-24 11:42:20.830   929  5737 D WifiHAL : Got a signal to exit!!!
,11-24 11:42:20.830   929  5737 I WifiHAL : Exit wifi_event_loop
11-24 11:42:20.831  4299  4299 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 11:42:20.831   929  2985 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-24 11:42:20.831   929  2985 E WifiHAL : Event processing terminated
11-24 11:42:20.831   929  2985 D wifi    : In wifi cleaned up handler
11-24 11:42:20.831   929  2985 I WifiHAL : Internal cleanup completed
11-24 11:42:20.837  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 11:42:20.839  4042  4221 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 11:42:20.856   929  5737 D wifi    : set interface wlan0 flags (DOWN)
,11-24 11:42:20.856   929  2985 D WifiNative-HAL: HAL event thread stopped successfully
,11-24 11:42:20.931   509   922 E Netd    : netlink response contains error (No such file or directory)
,11-24 11:42:21.062   929   946 D Tethering: InitialState.processMessage what=4
,11-24 11:42:21.069   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-24 11:42:21.421   929  2987 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-24 11:42:21.559   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:42:22.559   623   623 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 11:42:25.620   929   946 I ActivityManager: Start proc 5795:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-24 11:42:25.724  5795  5795 D AdapterServiceConfig: Adding HeadsetService
,11-24 11:42:25.725  5795  5795 D AdapterServiceConfig: Adding A2dpService
,11-24 11:42:25.725  5795  5795 D AdapterServiceConfig: Adding HidService
11-24 11:42:25.725  5795  5795 D AdapterServiceConfig: Adding HealthService
,11-24 11:42:25.725  5795  5795 D AdapterServiceConfig: Adding PanService
11-24 11:42:25.725  5795  5795 D AdapterServiceConfig: Adding GattService
,11-24 11:42:25.726  5795  5795 D AdapterServiceConfig: Adding BluetoothMapService
11-24 11:42:25.726  5795  5795 D AdapterServiceConfig: Adding SapService
,11-24 11:42:25.739   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@83cbff2:true
,11-24 11:42:25.739  5795  5795 D BluetoothAdapterState: make() - Creating AdapterState
,11-24 11:42:25.743  5795  5795 I bt_bluedroid: init
,11-24 11:42:25.743  5795  5807 I BluetoothAdapterState: Entering OffState
,11-24 11:42:25.745  5795  5808 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-24 11:42:25.745  5795  5808 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-24 11:42:25.745  5795  5808 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-24 11:42:25.745  5795  5808 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-24 11:42:25.746  5795  5795 I bt_bluedroid: get_profile_interface socket
,11-24 11:42:25.747  5795  5795 I bt_bluedroid: get_profile_interface sdp
,11-24 11:42:25.747  5795  5811 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-24 11:42:25.749  5795  5811 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 11:42:25.751  5795  5806 I bt_bluedroid: config_hci_snoop_log
,11-24 11:42:25.752   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-24 11:42:25.757  5795  5807 D BluetoothAdapterState: Current state: OFF, message: 0
,11-24 11:42:25.757  5795  5807 D BluetoothAdapterProperties: Setting state to 14
11-24 11:42:25.757  5795  5807 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-24 11:42:25.758  5795  5807 D BluetoothBondStateMachine: make
11-24 11:42:25.760  5795  5812 I BluetoothBondStateMachine: StableState(): Entering Off State
11-24 11:42:25.763  5795  5807 I BluetoothAdapterState: Entering PendingCommandState
11-24 11:42:25.764  5795  5795 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-24 11:42:25.766  5795  5795 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@836f2c
11-24 11:42:25.767  5795  5795 D BtGatt.DebugUtils: handleDebugAction() action=null
11-24 11:42:25.768  5795  5795 D BtGatt.GattService: Received start request. Starting profile...
11-24 11:42:25.768  5795  5795 D BtGatt.GattService: start()
,11-24 11:42:25.768  5795  5795 I bt_bluedroid: get_profile_interface gatt
,11-24 11:42:25.769  5795  5795 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@836f2c
11-24 11:42:25.769  5795  5795 D BtGatt.AdvertiseManager: advertise manager created
,11-24 11:42:25.774  5795  5795 V BluetoothAdapterState: isTurningOff()=false
,11-24 11:42:25.774  5795  5795 V BluetoothAdapterState: isTurningOn()=false
11-24 11:42:25.774  5795  5795 V BluetoothAdapterState: isBleTurningOn()=true
11-24 11:42:25.775  5795  5795 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:42:25.775  5795  5807 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-24 11:42:25.776  5795  5807 I bt_bluedroid: bt_bluedroid
,11-24 11:42:25.776  5795  5808 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-24 11:42:25.777  5795  5808 I bt_hci  : start_up
,11-24 11:42:25.782  5795  5808 I bt_vendor: alloc value 0xf412b871
,11-24 11:42:25.782  5795  5808 I bt_vendor: init
11-24 11:42:25.782  5795  5808 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-24 11:42:25.782  5795  5808 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-24 11:42:25.892  5795  5808 D bt_hci  : start_up starting async portion
,11-24 11:42:25.893  5795  5815 I bt_hci  : event_finish_startup
,11-24 11:42:25.893  5795  5815 I bt_hci_h4: hal_open
11-24 11:42:25.893  5795  5815 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-24 11:42:25.887  5816  5816 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-24 11:42:25.895  5795  5815 I bt_userial_vendor: device fd = 54 open
,11-24 11:42:25.908  5795  5815 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 11:42:25.910  5795  5815 D bt_hwcfg: Chipset BCM4358A3
11-24 11:42:25.910  5795  5815 D bt_hwcfg: Target name = [BCM4358A3]
11-24 11:42:25.910  5795  5815 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-24 11:42:26.300  5795  5815 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-24 11:42:26.300  5795  5815 D bt_hwcfg: Settlement delay -- 100 ms
11-24 11:42:26.300  5795  5815 I bt_hwcfg: Setting fw settlement delay to 100 
,11-24 11:42:26.435  5795  5815 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 11:42:26.436  5795  5815 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-24 11:42:26.437  5795  5815 I bt_hwcfg: vendor lib fwcfg completed
11-24 11:42:26.437  5795  5815 I bt_vendor: firmware callback
11-24 11:42:26.437  5795  5815 I bt_hci  : firmware_config_callback
,11-24 11:42:26.447  5795  5818 I bt_btu  : btu_task pending for preload complete event
,11-24 11:42:26.447  5795  5818 I bt_btu_task: Bluetooth chip preload is complete
,11-24 11:42:26.448  5795  5818 I bt_btu  : btu_task received preload complete event
,11-24 11:42:26.455  5795  5818 I         : BTE_InitTraceLevels -- TRC_HCI
,11-24 11:42:26.455  5795  5818 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-24 11:42:26.456  5795  5818 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-24 11:42:26.456  5795  5818 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-24 11:42:26.456  5795  5818 I         : BTE_InitTraceLevels -- TRC_AVRC
11-24 11:42:26.456  5795  5818 I         : BTE_InitTraceLevels -- TRC_A2D
11-24 11:42:26.456  5795  5818 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-24 11:42:26.456  5795  5818 I         : BTE_InitTraceLevels -- TRC_BTM
11-24 11:42:26.456  5795  5818 I         : BTE_InitTraceLevels -- TRC_GAP
11-24 11:42:26.456  5795  5818 I         : BTE_InitTraceLevels -- TRC_PAN
,11-24 11:42:26.456  5795  5818 I         : BTE_InitTraceLevels -- TRC_SDP
11-24 11:42:26.456  5795  5818 I         : BTE_InitTraceLevels -- TRC_GATT
11-24 11:42:26.456  5795  5818 I         : BTE_InitTraceLevels -- TRC_SMP
,11-24 11:42:26.457  5795  5818 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-24 11:42:26.457  5795  5818 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-24 11:42:26.538  5795  5818 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf40a9549
11-24 11:42:26.539  5795  5818 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf40a9549 
,11-24 11:42:26.558  5795  5811 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-24 11:42:26.559  5795  5811 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-24 11:42:26.559  5795  5811 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-24 11:42:26.562  5795  5811 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 11:42:26.564  5795  5811 D BluetoothAdapterProperties: Scan Mode:20
,11-24 11:42:26.565  5795  5811 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-24 11:42:26.565  5795  5811 D bt_hci  : do_postload posting postload work item
,11-24 11:42:26.565  5795  5815 I bt_hci  : event_postload
11-24 11:42:26.565  5795  5815 I bt_vendor: sco_config_cb
11-24 11:42:26.566  5795  5815 I bt_hci  : sco_config_callback postload finished.
11-24 11:42:26.568  5795  5811 D bt_bte_conf: Device ID record 1 : primary
11-24 11:42:26.569  5795  5811 D bt_bte_conf:   vendorId            = 000f
,11-24 11:42:26.569  5795  5811 D bt_bte_conf:   vendorIdSource      = 0001
11-24 11:42:26.569  5795  5811 D bt_bte_conf:   product             = 1200
11-24 11:42:26.569  5795  5811 D bt_bte_conf:   version             = 1436
11-24 11:42:26.569  5795  5811 D bt_bte_conf:   clientExecutableURL = 
11-24 11:42:26.569  5795  5811 D bt_bte_conf:   serviceDescription  = 
11-24 11:42:26.569  5795  5811 D bt_bte_conf:   documentationURL    = 
11-24 11:42:26.569  5795  5811 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-24 11:42:26.570  5795  5808 D bt_stack_manager: event_start_up_stack finished
11-24 11:42:26.571  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 11:42:26.571  5795  5807 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-24 11:42:26.572  5795  5807 D BluetoothAdapterProperties: Setting state to 15
,11-24 11:42:26.572  5795  5807 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-24 11:42:26.573  5795  5807 I BluetoothAdapterState: Entering BleOnState
,11-24 11:42:26.577  5795  5815 I bt_vendor: low_power_mode_cb
,11-24 11:42:26.580  5795  5807 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-24 11:42:26.580  5795  5807 D BluetoothAdapterProperties: Setting state to 11
,11-24 11:42:26.581  5795  5807 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-24 11:42:26.586  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 11:42:26.590  5795  5795 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@836f2c
,11-24 11:42:26.594  5795  5795 D HeadsetService: Received start request. Starting profile...
,11-24 11:42:26.597  5795  5795 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-24 11:42:26.599  5795  5807 I BluetoothAdapterState: Entering PendingCommandState
,11-24 11:42:26.597  5795  5795 D HeadsetStateMachine: make
,11-24 11:42:26.617  5795  5795 D HeadsetStateMachine: max_hf_connections = 1
,11-24 11:42:26.617  5795  5795 I bt_bluedroid: get_profile_interface handsfree
11-24 11:42:26.618  5795  5811 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-24 11:42:26.618  5795  5811 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-24 11:42:26.620  5795  5795 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@836f2c
,11-24 11:42:26.621  5795  5795 D A2dpService: Received start request. Starting profile...
,11-24 11:42:26.622  5795  5795 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-24 11:42:26.622  5795  5795 I bt_bluedroid: get_profile_interface avrcp
,11-24 11:42:26.628  5795  5795 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-24 11:42:26.629  5795  5795 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-24 11:42:26.629  5795  5795 D A2dpStateMachine: make
,11-24 11:42:26.630  5795  5795 I bt_bluedroid: get_profile_interface a2dp
11-24 11:42:26.630  5795  5811 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-24 11:42:26.632  5795  5826 D A2dpStateMachine: Enter Disconnected: -2
,11-24 11:42:26.633  5795  5795 I BluetoothHidServiceJni: classInitNative: succeeds
11-24 11:42:26.634  5795  5795 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@836f2c
,11-24 11:42:26.635  3578  3578 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 11:42:26.635  5795  5795 D HidService: Received start request. Starting profile...
,11-24 11:42:26.635  5674  5674 D BluetoothInputDevice: Proxy object connected
11-24 11:42:26.635  5795  5795 I bt_bluedroid: get_profile_interface hidhost
11-24 11:42:26.636  5795  5795 D HidService: setHidService(): set to: null
11-24 11:42:26.636  5795  5811 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf408a56d
11-24 11:42:26.636  5674  5674 D HidProfile: Bluetooth service connected
11-24 11:42:26.636  5795  5811 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-24 11:42:26.636  5795  5795 I BluetoothHealthServiceJni: classInitNative: succeeds
11-24 11:42:26.637  5795  5795 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@836f2c
11-24 11:42:26.638  5795  5795 D HealthService: Received start request. Starting profile...
,11-24 11:42:26.639  5795  5795 I bt_bluedroid: get_profile_interface health
,11-24 11:42:26.640  5795  5795 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-24 11:42:26.640  5795  5795 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@836f2c
,11-24 11:42:26.642  5795  5795 D PanService: Received start request. Starting profile...
,11-24 11:42:26.642  5674  5674 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 11:42:26.642  5795  5795 D BluetoothPanServiceJni: initializeNative(L110): pan
11-24 11:42:26.642  5795  5795 I bt_bluedroid: get_profile_interface pan
11-24 11:42:26.642  5795  5811 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-24 11:42:26.642  5674  5674 D PanProfile: Bluetooth service connected
,11-24 11:42:26.644  5795  5795 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@836f2c
,11-24 11:42:26.645  5795  5795 D BluetoothMapService: Received start request. Starting profile...
,11-24 11:42:26.645  5674  5674 D BluetoothMap: Proxy object connected
11-24 11:42:26.645  5795  5795 D BluetoothMapService: start()
11-24 11:42:26.646  5674  5674 D MapProfile: Bluetooth service connected
,11-24 11:42:26.646  5674  5674 D BluetoothMap: getConnectedDevices()
11-24 11:42:26.647  5674  5674 D BluetoothMap: Bluetooth is Not enabled
,11-24 11:42:26.648  5795  5795 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-24 11:42:26.649  5795  5795 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-24 11:42:26.649  5795  5795 D BluetoothMapAppObserver: createReceiver()
11-24 11:42:26.650  5795  5795 D BluetoothMapAppObserver: initObservers()
11-24 11:42:26.650  5795  5795 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-24 11:42:26.656  5795  5795 V SapService: SapBinder()
,11-24 11:42:26.656  5795  5795 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@836f2c
11-24 11:42:26.656  5795  5795 D SapService: Received start request. Starting profile...
11-24 11:42:26.656  5795  5795 V SapService: start()
,11-24 11:42:26.659  5795  5795 V BluetoothAdapterState: isTurningOff()=false
11-24 11:42:26.659  5795  5795 V BluetoothAdapterState: isTurningOn()=true
11-24 11:42:26.659  5795  5795 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:42:26.659  5795  5795 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:42:26.659  5795  5795 V BluetoothAdapterState: isTurningOff()=false
11-24 11:42:26.659  5795  5795 V BluetoothAdapterState: isTurningOn()=true
11-24 11:42:26.659  5795  5795 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:42:26.659  5795  5795 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 11:42:26.659  5795  5824 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-24 11:42:26.659  5795  5795 V BluetoothAdapterState: isTurningOff()=false
11-24 11:42:26.659  5795  5795 V BluetoothAdapterState: isTurningOn()=true
11-24 11:42:26.659  5795  5795 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:42:26.659  5795  5795 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:42:26.660  5795  5795 V BluetoothAdapterState: isTurningOff()=false
11-24 11:42:26.660  5795  5795 V BluetoothAdapterState: isTurningOn()=true
11-24 11:42:26.660  5795  5795 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:42:26.660  5795  5795 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:42:26.660  5795  5795 V BluetoothAdapterState: isTurningOff()=false
,11-24 11:42:26.660  5795  5795 V BluetoothAdapterState: isTurningOn()=true
11-24 11:42:26.660  5795  5795 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:42:26.660  5795  5795 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:42:26.660  5795  5795 V BluetoothAdapterState: isTurningOff()=false
11-24 11:42:26.660  5795  5795 V BluetoothAdapterState: isTurningOn()=true
11-24 11:42:26.660  5795  5795 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:42:26.661  5795  5795 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:42:26.662  5795  5795 V BluetoothAdapterState: isTurningOff()=false
11-24 11:42:26.662  5795  5795 V BluetoothAdapterState: isTurningOn()=true
11-24 11:42:26.662  5795  5795 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:42:26.662  5795  5795 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 11:42:26.662  5795  5807 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-24 11:42:26.662  5795  5807 D BluetoothAdapterProperties: ScanMode =  20
11-24 11:42:26.662  5795  5807 D BluetoothAdapterProperties: State =  11
,11-24 11:42:26.665  5795  5811 D BluetoothAdapterProperties: Scan Mode:21
,11-24 11:42:26.665  5795  5807 D BluetoothAdapterProperties: Setting state to 12
11-24 11:42:26.665  5795  5807 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-24 11:42:26.665  5795  5811 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 11:42:26.665  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-24 11:42:26.665  5795  5807 I BluetoothAdapterState: Entering OnState
11-24 11:42:26.666  3114  3126 D BluetoothPan: onBluetoothStateChange on: true
,11-24 11:42:26.668  3114  3114 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 11:42:26.668  3114  3128 D BluetoothPbap: onBluetoothStateChange: up=true
,11-24 11:42:26.668  3114  3114 D PanProfile: Bluetooth service connected
11-24 11:42:26.669  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 11:42:26.669  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 11:42:26.669  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 11:42:26.669  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 11:42:26.669  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 11:42:26.669  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 11:42:26.669  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 11:42:26.669  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 11:42:26.669  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 11:42:26.670   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 11:42:26.670  5674  5684 D BluetoothPbap: onBluetoothStateChange: up=true
,11-24 11:42:26.672  3757  4013 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 11:42:26.672  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 11:42:26.672   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 11:42:26.672  3114  3981 D BluetoothMap: onBluetoothStateChange: up=true
11-24 11:42:26.674   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 11:42:26.674  3114  3114 D BluetoothMap: Proxy object connected
11-24 11:42:26.674  3114  3114 D MapProfile: Bluetooth service connected
11-24 11:42:26.674  3114  3114 D BluetoothMap: getConnectedDevices()
11-24 11:42:26.674  5674  5686 D BluetoothPan: onBluetoothStateChange on: true
11-24 11:42:26.674  5674  5684 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 11:42:26.674   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 11:42:26.675  5795  5795 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 11:42:26.675  5795  5795 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-24 11:42:26.675  5674  5686 D BluetoothMap: onBluetoothStateChange: up=true
11-24 11:42:26.675  3114  3989 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 11:42:26.676  3114  3128 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 11:42:26.676  5795  5795 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 11:42:26.677  3114  3981 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-24 11:42:26.678  5795  5795 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 11:42:26.679  5795  5795 D ObexServerSockets: Succeed to create listening sockets 
11-24 11:42:26.679  3114  3114 D BluetoothInputDevice: Proxy object connected
11-24 11:42:26.679  3114  3114 D HidProfile: Bluetooth service connected
11-24 11:42:26.679  5795  5795 D ObexServerSockets0: startAccept()
11-24 11:42:26.679  5795  5795 D ObexServerSockets0: prepareForNewConnect()
11-24 11:42:26.681  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-24 11:42:26.681   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
,11-24 11:42:26.682  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 11:42:26.683  5795  5795 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,11-24 11:42:26.683  5795  5795 D BluetoothSdpJni: SDP Create record success - handle: 0
11-24 11:42:26.683  5795  5832 D ObexServerSockets0: Accepting socket connection...
11-24 11:42:26.684  5795  5833 D ObexServerSockets0: Accepting socket connection...
11-24 11:42:26.684  5674  5674 D LocalBluetoothProfileManager: Adding local A2DP profile
11-24 11:42:26.685   929   929 D BluetoothA2dp: Proxy object connected
11-24 11:42:26.685  3114  3114 D BluetoothA2dp: Proxy object connected
11-24 11:42:26.686  5795  5795 D BluetoothMapService: onReceive
11-24 11:42:26.686  5795  5795 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 11:42:26.686  5795  5795 D BluetoothMapService: STATE_ON
,11-24 11:42:26.689  5674  5674 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-24 11:42:26.689  5795  5835 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 11:42:26.690  5795  5835 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-24 11:42:26.691  5795  5835 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-24 11:42:26.695  5674  5674 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 11:42:26.697  5674  5674 D BluetoothA2dp: Proxy object connected
,11-24 11:42:26.702  3578  3578 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 11:42:26.702  5674  5674 D DockEventReceiver: finishStartingService: stopping service
,11-24 11:42:26.708  5674  5674 D BluetoothPbap: Proxy object connected
,11-24 11:42:26.709  5674  5674 D PbapServerProfile: Bluetooth service connected
11-24 11:42:26.709  3114  3114 D BluetoothPbap: Proxy object connected
11-24 11:42:26.710  3114  3114 D PbapServerProfile: Bluetooth service connected
11-24 11:42:26.710  5795  5795 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 11:42:26.710  5795  5795 D ObexServerSockets0: prepareForNewConnect()
,11-24 11:42:26.717  5795  5839 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 11:42:26.730  5795  5843 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 11:42:26.731  5795  5843 I BtOppRfcommListener: Accept thread started.
,11-24 11:42:26.772  3114  3128 D BluetoothHeadset: Proxy object connected
,11-24 11:42:26.772  3114  3114 D HeadsetProfile: Bluetooth service connected
11-24 11:42:26.772  3757  3775 D BluetoothHeadset: Proxy object connected
11-24 11:42:26.773  3757  3779 D BluetoothHeadset: Proxy object connected
11-24 11:42:26.773   929   929 D BluetoothHeadset: Proxy object connected
11-24 11:42:26.773   929   929 D BluetoothHeadset: Proxy object connected
11-24 11:42:26.773   929   946 D BluetoothHeadset: Proxy object connected
11-24 11:42:26.773   929   929 D BluetoothHeadset: Proxy object connected
11-24 11:42:26.774   929   946 D BluetoothHeadset: Proxy object connected
,11-24 11:42:26.777  3114  3981 D BluetoothHeadset: Proxy object connected
,11-24 11:42:26.777  3114  3114 D HeadsetProfile: Bluetooth service connected
,11-24 11:42:26.791  5674  5686 D BluetoothHeadset: Proxy object connected
,11-24 11:42:26.792  5674  5674 D HeadsetProfile: Bluetooth service connected
,11-24 11:42:27.560   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:42:28.373   929  2987 D ConnectivityService: handlePromptUnvalidated 101
,11-24 11:42:28.562   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:42:28.965  3655  3835 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-24 11:42:28.965  3655  3835 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-24 11:42:28.995  3578  3578 I ConfigService: onCreate
,11-24 11:42:29.562   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:42:30.564   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:42:30.598  5795  5807 D BluetoothAdapterState: Current state: ON, message: 23
,11-24 11:42:30.599  5795  5807 D BluetoothAdapterProperties: Setting state to 13
,11-24 11:42:30.599  5795  5807 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-24 11:42:30.600  5795  5807 D BluetoothAdapterProperties: onBluetoothDisable()
11-24 11:42:30.602  5795  5807 I BluetoothAdapterState: Entering PendingCommandState
,11-24 11:42:30.607  5795  5795 D BluetoothMapService: onReceive
11-24 11:42:30.607  5795  5795 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 11:42:30.607  5795  5795 D BluetoothMapService: STATE_TURNING_OFF
11-24 11:42:30.608  5795  5795 D BluetoothMapService: MAP Service closeService in
11-24 11:42:30.608  5795  5795 D BluetoothMapMasInstance0: MAP Service shutdown
,11-24 11:42:30.608  5795  5795 D ObexServerSockets0: shutdown(block = true)
,11-24 11:42:30.609  5795  5795 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 11:42:30.609  5795  5795 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-24 11:42:30.610  5795  5820 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-24 11:42:30.610  5795  5833 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,11-24 11:42:30.610  5795  5832 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-24 11:42:30.614  5795  5795 I BtOppRfcommListener: stopping Accept Thread
,11-24 11:42:30.615  5795  5843 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,11-24 11:42:30.615  5795  5843 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-24 11:42:30.616  5674  5674 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 11:42:30.616  5613  5613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 11:42:30.617  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 11:42:30.617  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 11:42:30.617  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 11:42:30.617  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 11:42:30.617  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 11:42:30.617  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 11:42:30.617  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 11:42:30.617  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 11:42:30.617  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 11:42:30.619  5613  5613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 11:42:30.620  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 11:42:30.620  5795  5811 D BluetoothAdapterProperties: Scan Mode:20
11-24 11:42:30.621  5795  5807 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-24 11:42:30.625  5795  5795 D HeadsetService: Received stop request...Stopping profile...
11-24 11:42:30.627  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 11:42:30.629  5674  5674 D DockEventReceiver: finishStartingService: stopping service
,11-24 11:42:30.630  3578  3578 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 11:42:30.635  3114  3126 D BluetoothHeadset: Proxy object disconnected
11-24 11:42:30.636  5674  5686 D BluetoothHeadset: Proxy object disconnected
11-24 11:42:30.636  3757  3978 D BluetoothHeadset: Proxy object disconnected
11-24 11:42:30.637   929   929 D BluetoothHeadset: Proxy object disconnected
,11-24 11:42:30.637   929   929 D BluetoothHeadset: Proxy object disconnected
11-24 11:42:30.637   929   929 D BluetoothHeadset: Proxy object disconnected
11-24 11:42:30.637  5674  5674 D HeadsetProfile: Bluetooth service disconnected
11-24 11:42:30.637  5795  5795 D A2dpService: Received stop request...Stopping profile...
11-24 11:42:30.638  5795  5826 D A2dpStateMachine: Exit Disconnected: -1
,11-24 11:42:30.639  3114  3114 D HeadsetProfile: Bluetooth service disconnected
11-24 11:42:30.639   929   929 D BluetoothA2dp: Proxy object disconnected
11-24 11:42:30.640  3114  3114 D BluetoothPbap: Proxy object disconnected
11-24 11:42:30.640  3114  3114 D PbapServerProfile: Bluetooth service disconnected
,11-24 11:42:30.640  5795  5795 V BluetoothAdapterState: isTurningOff()=true
11-24 11:42:30.640  3114  3114 D BluetoothA2dp: Proxy object disconnected
11-24 11:42:30.640  5795  5795 V BluetoothAdapterState: isTurningOn()=false
,11-24 11:42:30.640  5795  5795 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:42:30.640  5795  5795 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:42:30.640  5674  5674 D BluetoothPbap: Proxy object disconnected
11-24 11:42:30.640  5674  5674 D PbapServerProfile: Bluetooth service disconnected
,11-24 11:42:30.641  5674  5674 D BluetoothA2dp: Proxy object disconnected
11-24 11:42:30.641  5795  5795 D HidService: Received stop request...Stopping profile...
11-24 11:42:30.641  5795  5795 D HidService: Stopping Bluetooth HidService
11-24 11:42:30.642  5674  5674 D BluetoothInputDevice: Proxy object disconnected
11-24 11:42:30.642  5674  5674 D HidProfile: Bluetooth service disconnected
11-24 11:42:30.642  3114  3114 D BluetoothInputDevice: Proxy object disconnected
11-24 11:42:30.643  3114  3114 D HidProfile: Bluetooth service disconnected
11-24 11:42:30.643  5795  5795 D HealthService: Received stop request...Stopping profile...
11-24 11:42:30.650  5795  5795 D PanService: Received stop request...Stopping profile...
11-24 11:42:30.652  5674  5674 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 11:42:30.652  5674  5674 D PanProfile: Bluetooth service disconnected
11-24 11:42:30.652  3114  3114 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 11:42:30.652  3114  3114 D PanProfile: Bluetooth service disconnected
11-24 11:42:30.653  5795  5795 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-24 11:42:30.653  5795  5795 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-24 11:42:30.654  5795  5818 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 11:42:30.654  5795  5818 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-24 11:42:30.654  5795  5818 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 11:42:30.654  5795  5811 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-24 11:42:30.654  5795  5795 V BluetoothAdapterState: isTurningOff()=true
11-24 11:42:30.654  5795  5795 V BluetoothAdapterState: isTurningOn()=false
11-24 11:42:30.654  5795  5795 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:42:30.654  5795  5795 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:42:30.655  5795  5811 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-24 11:42:30.656  5795  5818 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 11:42:30.656  5795  5818 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 11:42:30.656  5795  5811 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-24 11:42:30.656  5795  5818 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 11:42:30.656  5795  5818 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 11:42:30.656  5795  5818 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 11:42:30.656  5795  5818 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 11:42:30.660  5795  5795 V BluetoothAdapterState: isTurningOff()=true
11-24 11:42:30.660  5795  5795 V BluetoothAdapterState: isTurningOn()=false
11-24 11:42:30.660  5795  5795 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:42:30.660  5795  5795 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:42:30.660  5795  5795 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-24 11:42:30.660  5795  5795 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-24 11:42:30.661  5795  5811 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-24 11:42:30.661  5795  5795 V BluetoothAdapterState: isTurningOff()=true
11-24 11:42:30.661  5795  5795 V BluetoothAdapterState: isTurningOn()=false
,11-24 11:42:30.661  5795  5795 V BluetoothAdapterState: isBleTurningOn()=false
,11-24 11:42:30.661  5795  5795 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 11:42:30.661  5795  5795 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-24 11:42:30.661  5795  5811 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-24 11:42:30.662  5795  5795 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-24 11:42:30.662  5795  5795 D BluetoothMapService: Received stop request...Stopping profile...
11-24 11:42:30.662  5795  5795 D BluetoothMapService: stop()
11-24 11:42:30.663  5795  5795 D BluetoothMapAppObserver: deinitObservers()
11-24 11:42:30.663  5795  5795 D BluetoothMapAppObserver: removeReceiver()
11-24 11:42:30.665  5674  5674 D BluetoothMap: Proxy object disconnected
,11-24 11:42:30.665  5674  5674 D MapProfile: Bluetooth service disconnected
11-24 11:42:30.665  3114  3114 D BluetoothMap: Proxy object disconnected
11-24 11:42:30.665  5795  5795 D SapService: Received stop request...Stopping profile...
11-24 11:42:30.665  3114  3114 D MapProfile: Bluetooth service disconnected
11-24 11:42:30.665  5795  5795 V SapService: stop()
11-24 11:42:30.666  5795  5795 V BluetoothAdapterState: isTurningOff()=true
11-24 11:42:30.666  5795  5795 V BluetoothAdapterState: isTurningOn()=false
11-24 11:42:30.666  5795  5795 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:42:30.666  5795  5795 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:42:30.666  5795  5795 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-24 11:42:30.667  5795  5795 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-24 11:42:30.668  5795  5795 D BluetoothMapService: MAP Service closeService in
11-24 11:42:30.668  5795  5795 V BluetoothAdapterState: isTurningOff()=true
11-24 11:42:30.668  5795  5795 V BluetoothAdapterState: isTurningOn()=false
11-24 11:42:30.668  5795  5795 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:42:30.668  5795  5795 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:42:30.668  5795  5795 D BluetoothMapService: cleanup()
11-24 11:42:30.668  5795  5795 D BluetoothMapService: MAP Service closeService in
11-24 11:42:30.668  5795  5795 V BluetoothAdapterState: isTurningOff()=true
11-24 11:42:30.669  5795  5795 V BluetoothAdapterState: isTurningOn()=false
11-24 11:42:30.669  5795  5795 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:42:30.669  5795  5795 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:42:30.669  5795  5807 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-24 11:42:30.669  5795  5807 D BluetoothAdapterProperties: Setting state to 15
11-24 11:42:30.669  5795  5807 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-24 11:42:30.670  5795  5807 I BluetoothAdapterState: Entering BleOnState
11-24 11:42:30.671  3114  3128 D BluetoothPan: onBluetoothStateChange on: false
11-24 11:42:30.672  3114  3126 D BluetoothPbap: onBluetoothStateChange: up=false
,11-24 11:42:30.674  5674  5684 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 11:42:30.674   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 11:42:30.675  5674  5848 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 11:42:30.675  3757  3775 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 11:42:30.675   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 11:42:30.675  3114  3981 D BluetoothMap: onBluetoothStateChange: up=false
11-24 11:42:30.676   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-24 11:42:30.676  5674  5686 D BluetoothPan: onBluetoothStateChange on: false
11-24 11:42:30.677  5674  5684 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-24 11:42:30.677   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 11:42:30.677  5674  5848 D BluetoothMap: onBluetoothStateChange: up=false
11-24 11:42:30.678  5674  5686 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 11:42:30.679  3114  3989 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 11:42:30.679  3114  3128 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 11:42:30.679  3114  3126 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-24 11:42:30.680  5795  5807 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-24 11:42:30.680  5795  5807 D BluetoothAdapterProperties: Setting state to 16
11-24 11:42:30.680  5795  5807 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,11-24 11:42:30.684  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 11:42:30.684  5795  5807 D BluetoothAdapterProperties: onBleDisable
11-24 11:42:30.684  5674  5674 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 11:42:30.685  5795  5807 I BluetoothAdapterState: Entering PendingCommandState
11-24 11:42:30.685  5795  5808 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-24 11:42:30.685  5795  5818 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-24 11:42:30.685  5795  5818 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 11:42:30.686  5795  5811 D BluetoothAdapterProperties: Scan Mode:20
11-24 11:42:30.690  5674  5674 D DockEventReceiver: finishStartingService: stopping service
11-24 11:42:30.690  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 11:42:30.692  3578  3578 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 11:42:30.896  5795  5811 I bt_hci  : shut_down
,11-24 11:42:30.901  5795  5815 D bt_hwcfg: hw_epilog_process
,11-24 11:42:30.901  5795  5815 I bt_vendor: low_power_mode_cb
,11-24 11:42:30.903  5795  5815 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-24 11:42:30.903  5795  5815 I bt_vendor: epilog_cb
11-24 11:42:30.904  5795  5815 I bt_hci  : epilog_finished_callback
,11-24 11:42:30.905  5795  5811 I bt_hci_h4: hal_close
,11-24 11:42:30.906  5795  5811 I bt_userial_vendor: device fd = 54 close
,11-24 11:42:31.013  5795  5808 D bt_stack_manager: event_shut_down_stack finished.
,11-24 11:42:31.014  5795  5807 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-24 11:42:31.020  5795  5807 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-24 11:42:31.020  5795  5795 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-24 11:42:31.021  5795  5795 D BtGatt.GattService: Received stop request...Stopping profile...
,11-24 11:42:31.021  5795  5795 D BtGatt.GattService: stop()
11-24 11:42:31.022  5795  5795 D BtGatt.AdvertiseManager: advertise clients cleared
11-24 11:42:31.026  5795  5795 V BluetoothAdapterState: isTurningOff()=false
11-24 11:42:31.026  5795  5795 V BluetoothAdapterState: isTurningOn()=false
11-24 11:42:31.026  5795  5795 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:42:31.026  5795  5795 V BluetoothAdapterState: isBleTurningOff()=true
,11-24 11:42:31.027  5795  5807 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-24 11:42:31.027  5795  5807 D BluetoothAdapterProperties: Setting state to 10
11-24 11:42:31.027  5795  5807 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-24 11:42:31.028  5795  5807 I BluetoothAdapterState: Entering OffState
,11-24 11:42:31.029   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-24 11:42:31.041  5795  5795 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-24 11:42:31.041  5795  5795 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-24 11:42:31.041  5795  5795 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-24 11:42:31.044  5795  5808 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-24 11:42:31.052  5795  5795 I art     : System.exit called, status: 0
,11-24 11:42:31.052  5795  5795 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-24 11:42:31.082   929  3413 I ActivityManager: Process com.android.bluetooth (pid 5795) has died
,11-24 11:42:31.565   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:42:32.565   623   623 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-24 11:42:34.025  3578  3578 I ConfigService: onDestroy
,11-24 11:42:35.596  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 11:42:35.597  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 11:42:35.602  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:35.603  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8fa3e8a removed from the list
11-24 11:42:35.603  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:42:35.605  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:42:35.605  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f41b771 added. We now have 4 listener(s)
11-24 11:42:35.605  5613  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 11:42:35.607  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:35.607  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f41b771 removed from the list
11-24 11:42:35.607  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:42:35.609  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:42:35.609  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@745b956 added. We now have 4 listener(s)
,11-24 11:42:35.609  5613  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 11:42:40.620  5613  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 11:42:40.650   929   946 I ActivityManager: Start proc 5853:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-24 11:42:40.726  5853  5853 D AdapterServiceConfig: Adding HeadsetService
,11-24 11:42:40.726  5853  5853 D AdapterServiceConfig: Adding A2dpService
11-24 11:42:40.726  5853  5853 D AdapterServiceConfig: Adding HidService
11-24 11:42:40.726  5853  5853 D AdapterServiceConfig: Adding HealthService
11-24 11:42:40.727  5853  5853 D AdapterServiceConfig: Adding PanService
11-24 11:42:40.727  5853  5853 D AdapterServiceConfig: Adding GattService
,11-24 11:42:40.727  5853  5853 D AdapterServiceConfig: Adding BluetoothMapService
11-24 11:42:40.727  5853  5853 D AdapterServiceConfig: Adding SapService
,11-24 11:42:40.738   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@564475f:true
,11-24 11:42:40.738  5853  5853 D BluetoothAdapterState: make() - Creating AdapterState
,11-24 11:42:40.741  5853  5853 I bt_bluedroid: init
,11-24 11:42:40.741  5853  5865 I BluetoothAdapterState: Entering OffState
,11-24 11:42:40.743  5853  5866 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-24 11:42:40.743  5853  5866 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-24 11:42:40.743  5853  5866 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-24 11:42:40.743  5853  5866 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-24 11:42:40.744  5853  5853 I bt_bluedroid: get_profile_interface socket
,11-24 11:42:40.745  5853  5869 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-24 11:42:40.746  5853  5853 I bt_bluedroid: get_profile_interface sdp
11-24 11:42:40.747  5853  5869 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 11:42:40.751  5853  5864 I bt_bluedroid: config_hci_snoop_log
,11-24 11:42:40.752   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-24 11:42:40.756  5853  5865 D BluetoothAdapterState: Current state: OFF, message: 0
11-24 11:42:40.756  5853  5865 D BluetoothAdapterProperties: Setting state to 14
11-24 11:42:40.756  5853  5865 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-24 11:42:40.758  5853  5865 D BluetoothBondStateMachine: make
,11-24 11:42:40.760  5853  5870 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-24 11:42:40.762  5853  5865 I BluetoothAdapterState: Entering PendingCommandState
,11-24 11:42:40.764  5853  5853 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-24 11:42:40.766  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@836f2c
11-24 11:42:40.766  5853  5853 D BtGatt.DebugUtils: handleDebugAction() action=null
11-24 11:42:40.767  5853  5853 D BtGatt.GattService: Received start request. Starting profile...
,11-24 11:42:40.767  5853  5853 D BtGatt.GattService: start()
11-24 11:42:40.767  5853  5853 I bt_bluedroid: get_profile_interface gatt
11-24 11:42:40.768  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@836f2c
11-24 11:42:40.768  5853  5853 D BtGatt.AdvertiseManager: advertise manager created
,11-24 11:42:40.774  5853  5853 V BluetoothAdapterState: isTurningOff()=false
11-24 11:42:40.774  5853  5853 V BluetoothAdapterState: isTurningOn()=false
11-24 11:42:40.774  5853  5853 V BluetoothAdapterState: isBleTurningOn()=true
,11-24 11:42:40.774  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:42:40.774  5853  5865 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-24 11:42:40.775  5853  5865 I bt_bluedroid: bt_bluedroid
11-24 11:42:40.776  5853  5866 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-24 11:42:40.776  5853  5866 I bt_hci  : start_up
,11-24 11:42:40.781  5853  5866 I bt_vendor: alloc value 0xf412b871
,11-24 11:42:40.781  5853  5866 I bt_vendor: init
11-24 11:42:40.782  5853  5866 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-24 11:42:40.782  5853  5866 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-24 11:42:40.891  5853  5866 D bt_hci  : start_up starting async portion
,11-24 11:42:40.891  5853  5873 I bt_hci  : event_finish_startup
11-24 11:42:40.891  5853  5873 I bt_hci_h4: hal_open
,11-24 11:42:40.892  5853  5873 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-24 11:42:40.887  5874  5874 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 11:42:40.894  5853  5873 I bt_userial_vendor: device fd = 54 open
,11-24 11:42:40.908  5853  5873 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 11:42:40.911  5853  5873 D bt_hwcfg: Chipset BCM4358A3
,11-24 11:42:40.911  5853  5873 D bt_hwcfg: Target name = [BCM4358A3]
11-24 11:42:40.911  5853  5873 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-24 11:42:41.288  5853  5873 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-24 11:42:41.288  5853  5873 D bt_hwcfg: Settlement delay -- 100 ms
11-24 11:42:41.288  5853  5873 I bt_hwcfg: Setting fw settlement delay to 100 
,11-24 11:42:41.423  5853  5873 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 11:42:41.424  5853  5873 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-24 11:42:41.425  5853  5873 I bt_hwcfg: vendor lib fwcfg completed
11-24 11:42:41.425  5853  5873 I bt_vendor: firmware callback
,11-24 11:42:41.426  5853  5873 I bt_hci  : firmware_config_callback
,11-24 11:42:41.434  5853  5876 I bt_btu  : btu_task pending for preload complete event
,11-24 11:42:41.434  5853  5876 I bt_btu_task: Bluetooth chip preload is complete
11-24 11:42:41.434  5853  5876 I bt_btu  : btu_task received preload complete event
,11-24 11:42:41.442  5853  5876 I         : BTE_InitTraceLevels -- TRC_HCI
,11-24 11:42:41.442  5853  5876 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-24 11:42:41.442  5853  5876 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-24 11:42:41.442  5853  5876 I         : BTE_InitTraceLevels -- TRC_AVDT
11-24 11:42:41.442  5853  5876 I         : BTE_InitTraceLevels -- TRC_AVRC
11-24 11:42:41.443  5853  5876 I         : BTE_InitTraceLevels -- TRC_A2D
11-24 11:42:41.443  5853  5876 I         : BTE_InitTraceLevels -- TRC_BNEP
11-24 11:42:41.443  5853  5876 I         : BTE_InitTraceLevels -- TRC_BTM
11-24 11:42:41.443  5853  5876 I         : BTE_InitTraceLevels -- TRC_GAP
11-24 11:42:41.443  5853  5876 I         : BTE_InitTraceLevels -- TRC_PAN
11-24 11:42:41.443  5853  5876 I         : BTE_InitTraceLevels -- TRC_SDP
11-24 11:42:41.443  5853  5876 I         : BTE_InitTraceLevels -- TRC_GATT
11-24 11:42:41.443  5853  5876 I         : BTE_InitTraceLevels -- TRC_SMP
,11-24 11:42:41.444  5853  5876 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-24 11:42:41.444  5853  5876 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-24 11:42:41.528  5853  5876 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf40a9549
,11-24 11:42:41.529  5853  5876 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf40a9549 
,11-24 11:42:41.545  5853  5869 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-24 11:42:41.546  5853  5869 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-24 11:42:41.547  5853  5869 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-24 11:42:41.549  5853  5869 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 11:42:41.552  5853  5869 D BluetoothAdapterProperties: Scan Mode:20
11-24 11:42:41.552  5853  5869 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 11:42:41.553  5853  5869 D bt_hci  : do_postload posting postload work item
11-24 11:42:41.553  5853  5873 I bt_hci  : event_postload
11-24 11:42:41.553  5853  5873 I bt_vendor: sco_config_cb
11-24 11:42:41.553  5853  5873 I bt_hci  : sco_config_callback postload finished.
,11-24 11:42:41.555  5853  5869 D bt_bte_conf: Device ID record 1 : primary
,11-24 11:42:41.556  5853  5869 D bt_bte_conf:   vendorId            = 000f
11-24 11:42:41.556  5853  5869 D bt_bte_conf:   vendorIdSource      = 0001
11-24 11:42:41.556  5853  5869 D bt_bte_conf:   product             = 1200
,11-24 11:42:41.556  5853  5869 D bt_bte_conf:   version             = 1436
11-24 11:42:41.556  5853  5869 D bt_bte_conf:   clientExecutableURL = 
11-24 11:42:41.556  5853  5869 D bt_bte_conf:   serviceDescription  = 
11-24 11:42:41.556  5853  5869 D bt_bte_conf:   documentationURL    = 
11-24 11:42:41.556  5853  5869 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-24 11:42:41.557  5853  5866 D bt_stack_manager: event_start_up_stack finished
,11-24 11:42:41.558  5853  5865 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-24 11:42:41.558  5853  5865 D BluetoothAdapterProperties: Setting state to 15
11-24 11:42:41.558  5853  5865 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,11-24 11:42:41.560  5853  5873 I bt_vendor: low_power_mode_cb
,11-24 11:42:41.564  5853  5865 I BluetoothAdapterState: Entering BleOnState
11-24 11:42:41.566  5853  5865 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-24 11:42:41.566  5853  5865 D BluetoothAdapterProperties: Setting state to 11
11-24 11:42:41.566  5853  5865 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-24 11:42:41.576  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@836f2c
,11-24 11:42:41.576  5853  5853 D HeadsetService: Received start request. Starting profile...
,11-24 11:42:41.580  5853  5853 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-24 11:42:41.580  5853  5853 D HeadsetStateMachine: make
,11-24 11:42:41.589  5853  5865 I BluetoothAdapterState: Entering PendingCommandState
,11-24 11:42:41.599  5853  5853 D HeadsetStateMachine: max_hf_connections = 1
,11-24 11:42:41.599  5853  5853 I bt_bluedroid: get_profile_interface handsfree
,11-24 11:42:41.599  5853  5869 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,11-24 11:42:41.599  5853  5869 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-24 11:42:41.604  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@836f2c
11-24 11:42:41.605  5853  5853 D A2dpService: Received start request. Starting profile...
11-24 11:42:41.608  5853  5853 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-24 11:42:41.609  5853  5853 I bt_bluedroid: get_profile_interface avrcp
,11-24 11:42:41.615  5853  5853 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-24 11:42:41.616  5853  5853 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-24 11:42:41.616  5853  5853 D A2dpStateMachine: make
,11-24 11:42:41.617  5853  5853 I bt_bluedroid: get_profile_interface a2dp
,11-24 11:42:41.618  5853  5869 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-24 11:42:41.621  5853  5883 D A2dpStateMachine: Enter Disconnected: -2
,11-24 11:42:41.622  5853  5853 I BluetoothHidServiceJni: classInitNative: succeeds
,11-24 11:42:41.623  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@836f2c
11-24 11:42:41.624  5853  5853 D HidService: Received start request. Starting profile...
11-24 11:42:41.624  5853  5853 I bt_bluedroid: get_profile_interface hidhost
11-24 11:42:41.624  5853  5853 D HidService: setHidService(): set to: null
11-24 11:42:41.624  5853  5869 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf408a56d
,11-24 11:42:41.624  5853  5869 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-24 11:42:41.625  5853  5853 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-24 11:42:41.626  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@836f2c
,11-24 11:42:41.626  5853  5853 D HealthService: Received start request. Starting profile...
,11-24 11:42:41.629  5853  5853 I bt_bluedroid: get_profile_interface health
11-24 11:42:41.630  5853  5853 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-24 11:42:41.631  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@836f2c
11-24 11:42:41.632  5853  5853 D PanService: Received start request. Starting profile...
11-24 11:42:41.632  5853  5853 D BluetoothPanServiceJni: initializeNative(L110): pan
11-24 11:42:41.632  5853  5853 I bt_bluedroid: get_profile_interface pan
11-24 11:42:41.632  5853  5869 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-24 11:42:41.634  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@836f2c
,11-24 11:42:41.635  5853  5853 D BluetoothMapService: Received start request. Starting profile...
,11-24 11:42:41.635  5853  5853 D BluetoothMapService: start()
11-24 11:42:41.639  5853  5853 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-24 11:42:41.640  5853  5853 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-24 11:42:41.640  5853  5853 D BluetoothMapAppObserver: createReceiver()
,11-24 11:42:41.642  5853  5853 D BluetoothMapAppObserver: initObservers()
11-24 11:42:41.642  5853  5853 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-24 11:42:41.649  5853  5853 V SapService: SapBinder()
,11-24 11:42:41.649  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@836f2c
,11-24 11:42:41.650  5853  5853 D SapService: Received start request. Starting profile...
11-24 11:42:41.650  5853  5853 V SapService: start()
,11-24 11:42:41.653  5853  5853 V BluetoothAdapterState: isTurningOff()=false
,11-24 11:42:41.653  5853  5853 V BluetoothAdapterState: isTurningOn()=true
11-24 11:42:41.653  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:42:41.653  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 11:42:41.654  5853  5881 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-24 11:42:41.655  5853  5853 V BluetoothAdapterState: isTurningOff()=false
11-24 11:42:41.655  5853  5853 V BluetoothAdapterState: isTurningOn()=true
11-24 11:42:41.655  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:42:41.655  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:42:41.655  5853  5853 V BluetoothAdapterState: isTurningOff()=false
11-24 11:42:41.655  5853  5853 V BluetoothAdapterState: isTurningOn()=true
11-24 11:42:41.655  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:42:41.655  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:42:41.656  5853  5853 V BluetoothAdapterState: isTurningOff()=false
11-24 11:42:41.656  5853  5853 V BluetoothAdapterState: isTurningOn()=true
,11-24 11:42:41.656  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:42:41.656  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:42:41.656  5853  5853 V BluetoothAdapterState: isTurningOff()=false
11-24 11:42:41.656  5853  5853 V BluetoothAdapterState: isTurningOn()=true
11-24 11:42:41.656  3578  3578 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 11:42:41.656  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:42:41.656  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
11-24 11:42:41.656  5853  5853 V BluetoothAdapterState: isTurningOff()=false
11-24 11:42:41.656  5853  5853 V BluetoothAdapterState: isTurningOn()=true
11-24 11:42:41.657  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:42:41.657  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 11:42:41.657  5853  5853 V BluetoothAdapterState: isTurningOff()=false
11-24 11:42:41.658  5853  5853 V BluetoothAdapterState: isTurningOn()=true
11-24 11:42:41.658  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
11-24 11:42:41.658  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 11:42:41.658  5853  5865 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-24 11:42:41.658  5853  5865 D BluetoothAdapterProperties: ScanMode =  20
,11-24 11:42:41.658  5853  5865 D BluetoothAdapterProperties: State =  11
11-24 11:42:41.658  5853  5865 D BluetoothAdapterProperties: Setting state to 12
11-24 11:42:41.658  5853  5865 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-24 11:42:41.659  5853  5865 I BluetoothAdapterState: Entering OnState
11-24 11:42:41.659  3114  3128 D BluetoothPan: onBluetoothStateChange on: true
11-24 11:42:41.662  5853  5869 D BluetoothAdapterProperties: Scan Mode:21
11-24 11:42:41.662  5853  5869 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 11:42:41.662  3114  3126 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 11:42:41.663  3114  3114 D BluetoothPan: BluetoothPAN Proxy object connected
,11-24 11:42:41.663  3114  3114 D PanProfile: Bluetooth service connected
,11-24 11:42:41.664  5674  5848 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 11:42:41.665   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 11:42:41.665  5674  5686 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 11:42:41.666  3757  3775 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 11:42:41.666   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 11:42:41.666  3114  3989 D BluetoothMap: onBluetoothStateChange: up=true
11-24 11:42:41.668   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 11:42:41.668  5674  5684 D BluetoothPan: onBluetoothStateChange on: true
11-24 11:42:41.669  5853  5853 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 11:42:41.670  5853  5853 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-24 11:42:41.671  5674  5686 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 11:42:41.671  5853  5853 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 11:42:41.672  5674  5674 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 11:42:41.672  5674  5674 D PanProfile: Bluetooth service connected
,11-24 11:42:41.675   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-24 11:42:41.675  5853  5853 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 11:42:41.676  5853  5853 D ObexServerSockets: Succeed to create listening sockets 
11-24 11:42:41.676  5853  5853 D ObexServerSockets0: startAccept()
11-24 11:42:41.676  5853  5853 D ObexServerSockets0: prepareForNewConnect()
,11-24 11:42:41.678  5853  5853 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-24 11:42:41.678  5853  5853 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-24 11:42:41.679  5853  5888 D ObexServerSockets0: Accepting socket connection...
11-24 11:42:41.679  5853  5889 D ObexServerSockets0: Accepting socket connection...
,11-24 11:42:41.680  3114  3114 D BluetoothMap: Proxy object connected
11-24 11:42:41.680  3114  3114 D MapProfile: Bluetooth service connected
11-24 11:42:41.680  3114  3114 D BluetoothMap: getConnectedDevices()
11-24 11:42:41.681  5674  5848 D BluetoothMap: onBluetoothStateChange: up=true
,11-24 11:42:41.682   929   929 D BluetoothA2dp: Proxy object connected
,11-24 11:42:41.683  5674  5684 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-24 11:42:41.685  3114  3981 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 11:42:41.686  3114  3126 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-24 11:42:41.688  3114  3114 D BluetoothA2dp: Proxy object connected
11-24 11:42:41.688  3114  3128 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 11:42:41.690  3114  3114 D BluetoothInputDevice: Proxy object connected
11-24 11:42:41.690  5674  5674 D BluetoothInputDevice: Proxy object connected
11-24 11:42:41.690  3114  3114 D HidProfile: Bluetooth service connected
11-24 11:42:41.690  5674  5674 D HidProfile: Bluetooth service connected
11-24 11:42:41.690   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
11-24 11:42:41.691  5853  5853 D BluetoothMapService: onReceive
11-24 11:42:41.691  5853  5853 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-24 11:42:41.691  5853  5853 D BluetoothMapService: STATE_ON
,11-24 11:42:41.694  5674  5674 D BluetoothMap: Proxy object connected
,11-24 11:42:41.694  5674  5674 D MapProfile: Bluetooth service connected
11-24 11:42:41.694  5674  5674 D BluetoothMap: getConnectedDevices()
11-24 11:42:41.695  5853  5893 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 11:42:41.695  5674  5674 D BluetoothA2dp: Proxy object connected
11-24 11:42:41.696  5853  5893 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-24 11:42:41.696  5853  5893 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-24 11:42:41.701  5674  5674 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 11:42:41.706  5674  5674 D DockEventReceiver: finishStartingService: stopping service
,11-24 11:42:41.709  3578  3578 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 11:42:41.715  5674  5674 D BluetoothPbap: Proxy object connected
,11-24 11:42:41.715  3114  3114 D BluetoothPbap: Proxy object connected
11-24 11:42:41.715  5674  5674 D PbapServerProfile: Bluetooth service connected
11-24 11:42:41.715  3114  3114 D PbapServerProfile: Bluetooth service connected
,11-24 11:42:41.716  5853  5853 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-24 11:42:41.716  5853  5853 D ObexServerSockets0: prepareForNewConnect()
,11-24 11:42:41.724  5853  5897 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 11:42:41.733  5853  5901 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 11:42:41.735  5853  5901 I BtOppRfcommListener: Accept thread started.
,11-24 11:42:41.766  3114  3126 D BluetoothHeadset: Proxy object connected
,11-24 11:42:41.766  3114  3114 D HeadsetProfile: Bluetooth service connected
,11-24 11:42:41.766  5674  5684 D BluetoothHeadset: Proxy object connected
,11-24 11:42:41.766  3757  3779 D BluetoothHeadset: Proxy object connected
,11-24 11:42:41.767   929   946 D BluetoothHeadset: Proxy object connected
11-24 11:42:41.767  5674  5674 D HeadsetProfile: Bluetooth service connected
11-24 11:42:41.767  3757  3978 D BluetoothHeadset: Proxy object connected
11-24 11:42:41.767   929   929 D BluetoothHeadset: Proxy object connected
11-24 11:42:41.767   929   929 D BluetoothHeadset: Proxy object connected
,11-24 11:42:41.767   929   929 D BluetoothHeadset: Proxy object connected
11-24 11:42:41.768   929   946 D BluetoothHeadset: Proxy object connected
,11-24 11:42:41.786  3114  3128 D BluetoothHeadset: Proxy object connected
11-24 11:42:41.786  3114  3114 D HeadsetProfile: Bluetooth service connected
,11-24 11:42:42.566   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:42:43.567   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:42:44.568   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:42:45.569   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:42:45.636  5613  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 11:42:45.636  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 11:42:45.636  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 11:42:45.636  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 11:42:45.636  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 11:42:45.636  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 11:42:45.636  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 11:42:45.636  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 11:42:45.636  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 11:42:45.641  5613  5660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 11:42:45.642  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 11:42:45.642  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@745b956 removed from the list
11-24 11:42:45.642  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:42:45.644  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 11:42:45.644  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5ac4dd7 added. We now have 4 listener(s)
11-24 11:42:45.644  5613  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 11:42:45.648   929  3820 D WifiService: setWifiEnabled: false pid=5613, uid=10077
11-24 11:42:45.648   929  3820 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 11:42:46.570   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:42:47.570   623   623 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-24 11:42:50.657  5613  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 11:42:50.658   929   939 D WifiService: setWifiEnabled: true pid=5613, uid=10077
,11-24 11:42:50.659   929   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 11:42:50.667   509   922 D SoftapController: Softap fwReload - Ok
,11-24 11:42:50.673   509   922 D CommandListener: Setting iface cfg
11-24 11:42:50.674   509   922 D CommandListener: Trying to bring down wlan0
,11-24 11:42:50.677   509   922 D CommandListener: Clearing all IP addresses on wlan0
,11-24 11:42:50.681   929  2985 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 11:42:51.345   929  2985 D wifi    : set interface wlan0 flags (UP)
,11-24 11:42:51.349   929  2985 I WifiHAL : Initializing wifi
11-24 11:42:51.349   929  2985 I WifiHAL : Creating socket
,11-24 11:42:51.354   929  2985 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-24 11:42:51.355   929  2985 D wifi    : Did set static halHandle = 0x7f76b0d400
,11-24 11:42:51.355   929  2985 D wifi    : halHandle = 0x7f76b0d400, mVM = 0x7f9314d140, mCls = 0x18ae
,11-24 11:42:51.355   929  2985 D wifi    : array field set
,11-24 11:42:51.355   929  2985 I WifiNative-HAL: interface[0] = wlan0
,11-24 11:42:51.355   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-24 11:42:51.359   929  5907 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547452146688
11-24 11:42:51.360   929  5907 D wifi    : waitForHalEvents called, vm = 0x7f9314d140, obj = 0x18ae, env = 0x7f78872900
,11-24 11:42:51.406  5908  5908 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-24 11:42:51.458   929  2985 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-24 11:42:51.469  5908  5908 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 11:42:51.555  5908  5908 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 11:42:51.555  5908  5908 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-24 11:42:51.578   929  2985 D WifiConfigStore: Loading config and enabling all networks 
,11-24 11:42:51.603   929  2985 D WifiConfigStore: loaded 0 passpoint configs
11-24 11:42:51.604   929  2985 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-24 11:42:51.604   929  2985 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-24 11:42:51.605   929  2985 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-24 11:42:51.606   929  2985 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-24 11:42:51.606   929  2985 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-24 11:42:51.607   929  2985 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-24 11:42:51.607   929  2985 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-24 11:42:51.607   929  2985 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-24 11:42:51.607   929  2985 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,11-24 11:42:51.608   929  2985 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-24 11:42:51.608   929  2985 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-24 11:42:51.608   929  2985 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-24 11:42:51.611   929  2985 D WifiNative-HAL: Setting external_sim to 1
,11-24 11:42:51.612  4299  4299 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 11:42:51.612   929  2985 D wifi    : setting dfs flag to true, 0x7f74695f40
11-24 11:42:51.612   929  2985 D WifiStateMachine: Setting OUI to DA-A1-19
11-24 11:42:51.612   929  2985 D wifi    : setting scan oui 0x7f74695f40
11-24 11:42:51.612   929  2985 D WifiHAL : Sending mac address OUI
,11-24 11:42:51.617   929  2985 E native  : do suspend false
,11-24 11:42:51.629   929  2985 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-24 11:42:51.629   929   929 D RttService: SCAN_AVAILABLE : 3
11-24 11:42:51.629   509   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-24 11:42:51.629   929  3039 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-24 11:42:51.630   509   922 D CommandListener: Setting iface cfg
,11-24 11:42:51.635   929  2973 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '158 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 158 Failed to set address (No such device)'
,11-24 11:42:51.636   929  2973 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-24 11:42:51.646   929  2973 D WifiNative-HAL: p2pGetDeviceAddress
11-24 11:42:51.646   929  2973 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-24 11:42:51.652   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=152591 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
,11-24 11:42:54.341  4042  4451 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-24 11:42:54.695  5908  5908 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 11:42:54.700  5908  5908 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 11:42:54.705  5908  5908 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 11:42:54.749   929  2985 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-24 11:42:54.751   929  2985 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-24 11:42:54.751   929  2985 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 11:42:54.765   929  2985 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-24 11:42:54.800   929  2985 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-24 11:42:54.806  5908  5908 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-24 11:42:55.237  5908  5908 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-24 11:42:55.681  5613  5660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 11:42:55.681  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 11:42:55.681  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 11:42:55.681  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 11:42:55.681  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 11:42:55.681  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 11:42:55.681  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 11:42:55.681  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 11:42:55.681  5613  5660 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 11:42:55.686  5613  5660 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 11:42:55.687  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 11:42:55.688  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5ac4dd7 removed from the list
,11-24 11:42:55.688  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 11:42:55.695  5613  5660 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-24 11:42:55.698  5613  5660 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-24 11:42:55.701  5613  5660 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@21211fb Bundle[{}]
,11-24 11:42:55.702  5613  5660 I io.jxcore.node.LifeCycleMonitor: start: OK
11-24 11:42:55.703  5613  5660 I io.jxcore.node.LifeCycleMonitor: stop: OK
,11-24 11:42:55.704  5613  5660 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-24 11:42:55.705  5613  5660 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-24 11:42:55.706  5613  5660 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-24 11:42:55.707  5613  5660 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-24 11:42:55.716  5613  5660 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 166)
,11-24 11:42:55.716  5613  5660 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-24 11:42:55.717  5613  5660 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 167)
,11-24 11:42:55.719  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 11:42:55.719  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@55ed6c4 added. We now have 3 listener(s)
,11-24 11:42:55.721  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-24 11:42:55.722  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-24 11:42:55.722  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 11:42:55.722  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:42:55.722  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6959ad added. We now have 4 listener(s)
,11-24 11:42:55.722  5613  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 11:42:55.723  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 11:42:55.725  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 11:42:55.725  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4fc14e2 added. We now have 4 listener(s)
11-24 11:42:55.727  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-24 11:42:55.727  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-24 11:42:55.727  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-24 11:42:55.727  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:42:55.728  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67df073 added. We now have 5 listener(s)
,11-24 11:42:55.728  5613  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 11:42:55.728  5613  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:42:55.728  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:42:55.728  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:42:55.728  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 11:42:55.728  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:42:55.728  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 11:42:55.728  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@55ed6c4 removed from the list
11-24 11:42:55.728  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:55.729  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6959ad removed from the list
,11-24 11:42:55.729  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:42:55.729  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.729  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.733  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.733  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:55.733  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.733  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:42:55.733  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:42:55.733  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:55.733  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6959ad not in the list
11-24 11:42:55.733  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.734  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.735  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:55.736  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.736  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.736  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:42:55.736  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:42:55.736  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:55.736  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67df073 removed from the list
11-24 11:42:55.736  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:42:55.736  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 11:42:55.736  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 11:42:55.736  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4fc14e2 removed from the list
11-24 11:42:55.737  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 11:42:55.737  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ed49b30 added. We now have 3 listener(s)
11-24 11:42:55.739  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 11:42:55.739  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 11:42:55.739  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-24 11:42:55.740  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:42:55.740  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eeee3a9 added. We now have 4 listener(s)
11-24 11:42:55.740  5613  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 11:42:55.740  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 11:42:55.742  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 11:42:55.742  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ca9d2e added. We now have 4 listener(s)
11-24 11:42:55.744  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 11:42:55.744  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 11:42:55.744  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 11:42:55.745  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:42:55.745  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bbd20cf added. We now have 5 listener(s)
11-24 11:42:55.745  5613  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 11:42:55.745  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 11:42:55.745  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 11:42:55.745  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 11:42:55.745  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 11:42:55.745  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 11:42:55.747  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 11:42:55.752  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-24 11:42:55.752  5613  5660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 11:42:55.752  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-24 11:42:55.756  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:55.756  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-24 11:42:55.756  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 11:42:55.757  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 11:42:55.757  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 11:42:55.760  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:55.760  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 11:42:55.760  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 11:42:55.760  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 11:42:55.760  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 11:42:55.760  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.761  5613  5660 D BluetoothAdapter: STATE_ON
,11-24 11:42:55.763  5853  5863 D BtGatt.GattService: registerClient() - UUID=181036c2-61c2-445f-bad4-7081b0d50281
,11-24 11:42:55.764  5853  5869 D BtGatt.GattService: onClientRegistered() - UUID=181036c2-61c2-445f-bad4-7081b0d50281, clientIf=5
,11-24 11:42:55.765  5613  5624 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 11:42:55.766  5853  5891 D BtGatt.GattService: start scan with filters
,11-24 11:42:55.769  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 11:42:55.769  5853  5872 D BtGatt.ScanManager: handling starting scan
,11-24 11:42:55.769  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.769  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 11:42:55.769  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.769  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 11:42:55.770  5613  5613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 11:42:55.770  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.770  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 11:42:55.770  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 11:42:55.770  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-24 11:42:55.770  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.770  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.770  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.771  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 11:42:55.771  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:55.773  5853  5872 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@836f2c
,11-24 11:42:55.774  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:55.774  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 11:42:55.775  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.775  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.775  5613  5660 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-24 11:42:55.775  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.775  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 11:42:55.775  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 11:42:55.775  5613  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 11:42:55.775  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 11:42:55.775  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:42:55.775  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-24 11:42:55.779  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-24 11:42:55.779  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.779  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.779  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 11:42:55.779  5613  5613 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 11:42:55.779  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.779  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 11:42:55.779  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 11:42:55.779  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.779  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:55.779  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.779  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 11:42:55.779  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.780  5853  5869 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 11:42:55.780  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 11:42:55.781  5853  5872 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 11:42:55.781  5613  5660 D BluetoothAdapter: STATE_ON
11-24 11:42:55.781  5853  5863 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-24 11:42:55.782  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-24 11:42:55.783  5613  5660 D BluetoothAdapter: STATE_ON
,11-24 11:42:55.785  5853  5890 D BtGatt.GattService: stopScan() - queue size =1
,11-24 11:42:55.785  5853  5864 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 11:42:55.786  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 11:42:55.786  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:55.786  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 11:42:55.786  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.786  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.786  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.786  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.786  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 11:42:55.786  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.786  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.786  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.787  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 11:42:55.787  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-24 11:42:55.788  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-24 11:42:55.788  5853  5869 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-24 11:42:55.788  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:42:55.789  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.789  5853  5872 D BtGatt.ScanManager: Starting BLE batch scan
11-24 11:42:55.789  5853  5872 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 11:42:55.790  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.790  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-24 11:42:55.790  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.790  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.790  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 11:42:55.790  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 11:42:55.791  5613  5613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 11:42:55.791  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.791  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 11:42:55.791  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 11:42:55.791  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.791  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.791  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.791  5613  5613 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 11:42:55.791  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.791  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-24 11:42:55.793  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.793  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.793  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.793  5613  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:42:55.793  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:42:55.793  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:42:55.793  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:42:55.793  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:42:55.794  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 11:42:55.794  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ed49b30 removed from the list
11-24 11:42:55.794  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:55.794  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eeee3a9 removed from the list
11-24 11:42:55.794  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 11:42:55.794  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.794  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.795  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.795  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.795  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.795  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:42:55.795  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:42:55.795  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 11:42:55.795  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eeee3a9 not in the list
11-24 11:42:55.795  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.795  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.797  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.798  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.798  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.798  5853  5869 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 11:42:55.798  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:42:55.798  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:42:55.798  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:42:55.798  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 11:42:55.798  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bbd20cf removed from the list
11-24 11:42:55.798  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:42:55.798  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:42:55.798  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 11:42:55.798  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ca9d2e removed from the list
11-24 11:42:55.799  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 11:42:55.799  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@224a048 added. We now have 3 listener(s)
11-24 11:42:55.800  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 11:42:55.800  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-24 11:42:55.800  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 11:42:55.800  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:42:55.800  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21e5ee1 added. We now have 4 listener(s)
11-24 11:42:55.801  5613  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 11:42:55.801  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 11:42:55.803  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 11:42:55.803  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@add2406 added. We now have 4 listener(s)
,11-24 11:42:55.803  5853  5869 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 11:42:55.803  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:42:55.804  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 11:42:55.804  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 11:42:55.804  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 11:42:55.804  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:42:55.805  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c65ac7 added. We now have 5 listener(s)
,11-24 11:42:55.805  5613  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 11:42:55.805  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 11:42:55.805  5853  5872 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 11:42:55.805  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 11:42:55.806  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 11:42:55.806  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 11:42:55.806  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-24 11:42:55.806  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-24 11:42:55.807  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 11:42:55.811  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-24 11:42:55.811  5613  5660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 11:42:55.811  5853  5869 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 11:42:55.811  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 11:42:55.811  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:42:55.811  5853  5869 E BtGatt.ContextMap: Context not found for ID 5
,11-24 11:42:55.814  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:55.814  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 11:42:55.815  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 11:42:55.815  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 11:42:55.815  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 11:42:55.817  5853  5869 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 11:42:55.817  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:42:55.817  5853  5872 D BtGatt.ScanManager: stopping BLe Batch
,11-24 11:42:55.818  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.818  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 11:42:55.818  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 11:42:55.818  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 11:42:55.818  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 11:42:55.818  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:55.819  5613  5660 D BluetoothAdapter: STATE_ON
,11-24 11:42:55.822  5853  5891 D BtGatt.GattService: registerClient() - UUID=62ba6539-e6b8-4ee0-a4b1-c57375778807
,11-24 11:42:55.823  5853  5869 D BtGatt.GattService: onClientRegistered() - UUID=62ba6539-e6b8-4ee0-a4b1-c57375778807, clientIf=5
11-24 11:42:55.823  5613  5661 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 11:42:55.823  5853  5890 D BtGatt.GattService: start scan with filters
,11-24 11:42:55.824  5853  5869 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 11:42:55.824  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:42:55.824  5853  5872 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 11:42:55.825  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 11:42:55.825  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.825  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 11:42:55.826  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.826  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-24 11:42:55.826  5613  5613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 11:42:55.826  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.826  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 11:42:55.826  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 11:42:55.826  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-24 11:42:55.826  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.826  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.826  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-24 11:42:55.827  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 11:42:55.827  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:55.829  5853  5869 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 11:42:55.829  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:42:55.830  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.830  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 11:42:55.830  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:55.830  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:55.831  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.831  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 11:42:55.831  5613  5660 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-24 11:42:55.831  5613  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:42:55.831  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:42:55.831  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:42:55.831  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:42:55.831  5853  5872 D BtGatt.ScanManager: handling starting scan
11-24 11:42:55.831  5613  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-24 11:42:55.831  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 11:42:55.831  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:42:55.831  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 11:42:55.832  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@224a048 removed from the list
11-24 11:42:55.832  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:55.832  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21e5ee1 removed from the list
11-24 11:42:55.832  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 11:42:55.832  5613  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 11:42:55.832  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 11:42:55.832  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.832  5613  5660 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-24 11:42:55.832  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-24 11:42:55.832  5613  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 11:42:55.832  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-24 11:42:55.833  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.833  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.833  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.833  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.833  5613  5613 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-24 11:42:55.836  5853  5869 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-24 11:42:55.836  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:42:55.837  5853  5872 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-24 11:42:55.837  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.837  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.837  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:55.837  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:42:55.837  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:42:55.837  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:55.837  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21e5ee1 not in the list
11-24 11:42:55.837  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 11:42:55.837  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.837  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-24 11:42:55.837  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 11:42:55.837  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.837  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.837  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.837  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 11:42:55.837  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:55.838  5613  5660 D BluetoothAdapter: STATE_ON
11-24 11:42:55.838  5853  5890 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-24 11:42:55.839  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 11:42:55.839  5613  5660 D BluetoothAdapter: STATE_ON
11-24 11:42:55.840  5853  5863 D BtGatt.GattService: stopScan() - queue size =1
11-24 11:42:55.840  5853  5891 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 11:42:55.840  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-24 11:42:55.840  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.841  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 11:42:55.841  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.841  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.841  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.841  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.841  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 11:42:55.841  5853  5869 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 11:42:55.841  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:42:55.841  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:55.841  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.841  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.841  5853  5872 D BtGatt.ScanManager: Starting BLE batch scan
11-24 11:42:55.841  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 11:42:55.841  5853  5872 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 11:42:55.841  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 11:42:55.842  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 11:42:55.842  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.843  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:55.843  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 11:42:55.843  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.843  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.843  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:42:55.843  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:42:55.843  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:55.843  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 11:42:55.843  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c65ac7 removed from the list
11-24 11:42:55.843  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:42:55.843  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-24 11:42:55.843  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:42:55.843  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 11:42:55.843  5613  5613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 11:42:55.843  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@add2406 removed from the list
11-24 11:42:55.843  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.843  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 11:42:55.843  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 11:42:55.843  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.844  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.844  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-24 11:42:55.844  5613  5613 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 11:42:55.844  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.844  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.844  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 11:42:55.844  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19d3060 added. We now have 3 listener(s)
11-24 11:42:55.845  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.845  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.845  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.845  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 11:42:55.845  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 11:42:55.845  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 11:42:55.845  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:42:55.845  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eeb0919 added. We now have 4 listener(s)
,11-24 11:42:55.846  5613  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 11:42:55.847  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 11:42:55.848  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 11:42:55.848  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@92eadde added. We now have 4 listener(s)
11-24 11:42:55.849  5853  5869 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 11:42:55.849  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:42:55.850  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 11:42:55.850  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 11:42:55.850  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 11:42:55.850  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:42:55.850  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98ddbbf added. We now have 5 listener(s)
11-24 11:42:55.850  5613  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 11:42:55.850  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 11:42:55.850  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 11:42:55.850  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 11:42:55.850  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 11:42:55.850  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-24 11:42:55.851  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 11:42:55.854  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 11:42:55.854  5613  5660 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-24 11:42:55.854  5853  5869 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 11:42:55.854  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 11:42:55.854  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 11:42:55.855  5853  5872 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 11:42:55.860  5853  5869 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 11:42:55.860  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:42:55.860  5853  5869 E BtGatt.ContextMap: Context not found for ID 5
11-24 11:42:55.860  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.861  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-24 11:42:55.861  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-24 11:42:55.861  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 11:42:55.861  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 11:42:55.864  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:55.864  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 11:42:55.864  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 11:42:55.864  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 11:42:55.864  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 11:42:55.864  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.865  5613  5660 D BluetoothAdapter: STATE_ON
11-24 11:42:55.865  5853  5869 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 11:42:55.865  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:42:55.866  5853  5872 D BtGatt.ScanManager: stopping BLe Batch
11-24 11:42:55.866  5853  5892 D BtGatt.GattService: registerClient() - UUID=3470ee35-e47d-4a4c-a086-6bd18c412ef7
,11-24 11:42:55.867  5853  5869 D BtGatt.GattService: onClientRegistered() - UUID=3470ee35-e47d-4a4c-a086-6bd18c412ef7, clientIf=5
11-24 11:42:55.867  5613  5661 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 11:42:55.868  5853  5863 D BtGatt.GattService: start scan with filters
,11-24 11:42:55.870  5853  5869 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 11:42:55.870  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 11:42:55.870  5853  5872 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 11:42:55.870  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 11:42:55.871  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.871  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-24 11:42:55.871  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.871  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 11:42:55.871  5613  5613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 11:42:55.871  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.871  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 11:42:55.871  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 11:42:55.871  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-24 11:42:55.872  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.872  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.872  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.872  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 11:42:55.872  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:55.874  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.874  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 11:42:55.874  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:55.874  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.874  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.876  5853  5869 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 11:42:55.876  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:42:55.876  5613  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:42:55.876  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:42:55.876  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:42:55.876  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 11:42:55.876  5613  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 11:42:55.876  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 11:42:55.876  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:42:55.876  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 11:42:55.876  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19d3060 removed from the list
,11-24 11:42:55.876  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:55.876  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eeb0919 removed from the list
11-24 11:42:55.877  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:42:55.877  5613  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 11:42:55.877  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 11:42:55.877  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:55.877  5613  5660 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-24 11:42:55.877  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-24 11:42:55.877  5613  5660 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 11:42:55.877  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 11:42:55.877  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.877  5853  5872 D BtGatt.ScanManager: handling starting scan
,11-24 11:42:55.877  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.878  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.878  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.878  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.878  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.878  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.878  5613  5613 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 11:42:55.878  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 11:42:55.878  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:42:55.878  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:55.878  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eeb0919 not in the list
11-24 11:42:55.878  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 11:42:55.878  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.878  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 11:42:55.878  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 11:42:55.878  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:55.878  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.878  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.878  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 11:42:55.878  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.879  5613  5660 D BluetoothAdapter: STATE_ON
11-24 11:42:55.880  5853  5863 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 11:42:55.880  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 11:42:55.880  5613  5660 D BluetoothAdapter: STATE_ON
11-24 11:42:55.881  5853  5864 D BtGatt.GattService: stopScan() - queue size =1
,11-24 11:42:55.881  5853  5892 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-24 11:42:55.882  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 11:42:55.882  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.882  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 11:42:55.882  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.882  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.882  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.882  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.882  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 11:42:55.882  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.882  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:55.882  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.882  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 11:42:55.882  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 11:42:55.883  5853  5869 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 11:42:55.883  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 11:42:55.883  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:42:55.884  5853  5872 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 11:42:55.884  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.885  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:55.885  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 11:42:55.885  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.885  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.885  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:42:55.885  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:42:55.885  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:55.885  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98ddbbf removed from the list
11-24 11:42:55.885  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:42:55.885  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 11:42:55.885  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-24 11:42:55.885  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@92eadde removed from the list
11-24 11:42:55.886  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 11:42:55.886  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@264ab78 added. We now have 3 listener(s)
11-24 11:42:55.886  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-24 11:42:55.887  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 11:42:55.887  5613  5613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 11:42:55.887  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.887  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 11:42:55.887  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 11:42:55.887  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.887  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.887  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-24 11:42:55.887  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.887  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 11:42:55.887  5613  5613 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 11:42:55.887  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 11:42:55.887  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.887  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:42:55.887  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.887  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ebc251 added. We now have 4 listener(s)
11-24 11:42:55.887  5613  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 11:42:55.888  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 11:42:55.888  5853  5869 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 11:42:55.888  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:42:55.888  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.888  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.888  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 11:42:55.888  5853  5872 D BtGatt.ScanManager: Starting BLE batch scan
11-24 11:42:55.888  5853  5872 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 11:42:55.889  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 11:42:55.889  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c9ab6 added. We now have 4 listener(s)
11-24 11:42:55.890  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-24 11:42:55.890  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 11:42:55.891  5613  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 11:42:55.891  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 11:42:55.891  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb583b7 added. We now have 5 listener(s)
11-24 11:42:55.891  5613  5660 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 11:42:55.891  5613  5660 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 11:42:55.891  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:42:55.891  5613  5660 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 11:42:55.891  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:42:55.892  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 11:42:55.892  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 11:42:55.892  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@264ab78 removed from the list
11-24 11:42:55.892  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:55.892  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ebc251 removed from the list
11-24 11:42:55.892  5613  5660 D io.jxcore.node.ConnectivityMonitor: stop
11-24 11:42:55.892  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.892  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.893  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.893  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:55.894  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.894  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:42:55.894  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:42:55.894  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:55.894  5613  5660 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ebc251 not in the list
11-24 11:42:55.894  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-58,5,main], id: 58
,11-24 11:42:55.894  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.895  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.895  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.895  5613  5660 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
11-24 11:42:55.896  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 11:42:55.896  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 11:42:55.896  5613  5660 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 11:42:55.896  5613  5660 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb583b7 removed from the list
11-24 11:42:55.896  5613  5660 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 11:42:55.896  5613  5660 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 11:42:55.896  5613  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 11:42:55.896  5613  5660 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c9ab6 removed from the list
11-24 11:42:55.897  5853  5869 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-24 11:42:55.897  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-24 11:42:55.897  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:42:55.897  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-24 11:42:55.897  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-24 11:42:55.897  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 11:42:55.897  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,11-24 11:42:55.898  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-24 11:42:55.901  5853  5869 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-24 11:42:55.901  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 11:42:55.902  5853  5872 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 11:42:55.907  5853  5869 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 11:42:55.907  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:42:55.907  5853  5869 E BtGatt.ContextMap: Context not found for ID 5
,11-24 11:42:55.912  5853  5869 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-24 11:42:55.912  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:42:55.912  5853  5872 D BtGatt.ScanManager: stopping BLe Batch
,11-24 11:42:55.917  5853  5869 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 11:42:55.917  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 11:42:55.917  5853  5872 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 11:42:55.921  5853  5869 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 11:42:55.922  5853  5869 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 11:42:56.273  5908  5908 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-24 11:42:56.274  5908  5908 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-24 11:42:56.292   929  2985 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 11:42:56.292  5613  5613 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
11-24 11:42:56.292   929  2985 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 11:42:56.292   929  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-24 11:42:56.310   929  2985 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 11:42:56.324   509   922 D CommandListener: Setting iface cfg
,11-24 11:42:56.330   929  2985 D WifiStateMachine: Start Dhcp Watchdog 3
,11-24 11:42:56.336   929  5922 D DhcpClient: Receive thread started
,11-24 11:42:56.341   929  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 11:42:56.341   929  2985 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-24 11:42:56.341   929  2987 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-24 11:42:56.344  5613  5613 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 11:42:56.387  5613  5613 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 11:42:56.422   929  2985 E native  : do suspend false
,11-24 11:42:56.434   929  5921 D DhcpClient: Broadcasting DHCPDISCOVER
,11-24 11:42:56.447   929  5922 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172763, domain null
,11-24 11:42:56.448   929  5921 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172763 seconds
,11-24 11:42:56.450   929  5921 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-24 11:42:56.469   929  5922 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-24 11:42:56.470   929  5921 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-24 11:42:56.473   509   922 D CommandListener: Setting iface cfg
,11-24 11:42:56.479   929  2985 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-24 11:42:56.482   929  5921 D DhcpClient: Scheduling renewal in 86399s
,11-24 11:42:56.496   929  2985 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-24 11:42:56.499   929  2985 D WifiConfigStore: No blacklist allowed without epno enabled
,11-24 11:42:56.499   929  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-24 11:42:56.512   929  2987 D ConnectivityService: Adding iface wlan0 to network 102
,11-24 11:42:56.512   929  2985 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-24 11:42:56.553   929  2987 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-24 11:42:56.554   929  2987 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-24 11:42:56.555   929  2987 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-24 11:42:56.557   929  2987 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-24 11:42:56.559   929  2987 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-24 11:42:56.566   929  2987 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 11:42:56.571   929  2987 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-24 11:42:56.571   929  2987 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-24 11:42:56.571   929  2987 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-24 11:42:56.571   929  2985 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-24 11:42:56.571   929  2987 D ConnectivityService:    accepting network in place of null
11-24 11:42:56.571   929  2985 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 11:42:56.572   929  2987 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 11:42:56.580   929  5920 D NetlinkSocketObserver: NeighborEvent{elapsedMs=157518, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 11:42:56.596   509   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 11:42:56.618   509   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 11:42:56.622   929  2987 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-24 11:42:56.622  3726  3857 W QCNEJ   : |CORE| network available: 102
11-24 11:42:56.622   929  2987 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-24 11:42:56.623   929  2987 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,11-24 11:42:56.625  3726  3857 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-24 11:42:56.626   929   946 D Tethering: MasterInitialState.processMessage what=3
11-24 11:42:56.626  3726  3857 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-24 11:42:56.627  3726  3857 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-24 11:42:56.640  4937  4962 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-24 11:42:56.640  4937  4962 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,11-24 11:42:56.640  4937  4962 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-24 11:42:56.640  4937  4962 E SarControlService: no key has been found,reset the power
11-24 11:42:56.641  4937  4985 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 11:42:56.641  4937  4985 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 11:42:56.641  4937  4985 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 11:42:56.642  3963  3963 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-24 11:42:56.643   929  5919 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
11-24 11:42:56.644  4973  4973 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 11:42:56.644  4973  4973 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 11:42:56.646  4937  4985 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-24 11:42:56.647  3828  3828 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-24 11:42:56.650  4937  4985 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 11:42:56.650  4937  4985 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 11:42:56.652  4973  4988 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@bc6a1e7 HexData = [00000000f003000000000000ffffffff]
11-24 11:42:56.652  4973  4988 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 11:42:56.652  4973  4988 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
11-24 11:42:56.653  4973  4973 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 11:42:56.653  4973  4973 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 11:42:56.654  4973  4973 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-24 11:42:56.654  4937  4951 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-24 11:42:56.656  3828  3828 D SystemUpdateService: onCreate
11-24 11:42:56.657  4973  4988 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@bc6a1e7 HexData = [00000000f103000000000000ffffffff]
11-24 11:42:56.657  4973  4988 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 11:42:56.657  4973  4988 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
11-24 11:42:56.658  4973  4973 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 11:42:56.658  4937  4949 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-24 11:42:56.661  3828  3828 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 11:42:56.673  3828  3828 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-24 11:42:56.675  3828  5378 I iu.UploadsManager: num queued entries: 0
,11-24 11:42:56.676  3828  5378 I iu.UploadsManager: num updated entries: 0
11-24 11:42:56.676  3828  5378 I iu.SyncManager: NEXT; no task
,11-24 11:42:56.686  3828  5932 I SystemUpdateService: active receiver: enabled
,11-24 11:42:56.688  3828  3828 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 11:42:56.689  3828  3828 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 11:42:56.691  5701  5701 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 11:42:56.692   929  5919 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Nov 2016 10:42:56 GMT], X-Android-Received-Millis=[1479984176691], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479984176668]}
,11-24 11:42:56.692   929  2987 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-24 11:42:56.692   929  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-24 11:42:56.692   929  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-24 11:42:56.693   929  2987 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-24 11:42:56.698  5701  5701 D SprintDMHelper: simOperator: 
,11-24 11:42:56.698  5701  5701 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 11:42:56.716  3828  5932 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 11:42:56.742  3828  5932 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-24 11:42:56.742  3828  5932 I SystemUpdateService: now status is 0 (complete)
11-24 11:42:56.743  3828  5932 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-24 11:42:56.743  3828  5932 I SystemUpdateService: file has been verified
11-24 11:42:56.743  3828  5932 I SystemUpdateService: OTA package size = 21989297
,11-24 11:42:56.757  3828  5932 I SystemUpdateService: showing system update notification
,11-24 11:42:56.760  3578  5943 I VacuumService: Vacuum at: now=1479984176760 tag=VacuumService
,11-24 11:42:56.766   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-24 11:42:56.767  3828  3828 D SystemUpdateService: onDestroy
,11-24 11:42:56.784  3578  5946 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-24 11:42:56.795  4299  5938 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-24 11:42:56.828  3578  5944 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-24 11:42:56.831  3578  5944 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-24 11:42:56.851  3578  5944 W Uploader:  no longer exists, so no auth token.
,11-24 11:42:56.857  3578  5946 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 11:42:57.227  3578  5950 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 11:42:57.291  3578  5944 W Uploader:  no longer exists, so no auth token.
,11-24 11:42:57.304  3578  5946 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 11:42:57.385  3578  5950 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 11:42:57.467  3578  5946 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 11:42:57.710   929  2985 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{4}, ntable=[192.168.1.1/NUD_REACHABLE]
,11-24 11:42:57.721   929  2987 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 11:42:57.727  3726  3857 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,fe80::6283:34ff:fe25:d770/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-24 11:42:57.727  3726  3857 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,fe80::6283:34ff:fe25:d770/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-24 11:42:58.029  5613  5954 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 175, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 11:42:58.029  5613  5954 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 11:42:58.815  5613  5954 W !!      : call onHalfStreamCopied
,11-24 11:42:58.815  5613  5954 I testCopyDataAndClose: closing input stream
,11-24 11:42:59.585  5613  5954 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 175, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 11:42:59.585  5613  5954 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 11:42:59.586  5613  5954 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 11:42:59.586  5613  5954 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 11:42:59.586  5613  5954 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-24 11:42:59.586  5613  5954 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-24 11:42:59.586  5613  5954 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-24 11:42:59.586  5613  5954 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-24 11:42:59.586  5613  5954 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-24 11:42:59.586  5613  5954 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 175, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 11:42:59.586  5613  5954 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-24 11:43:02.572   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:43:03.572   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:43:04.058  5613  5955 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: My test thread name). Connection data: Peer properties: [null null].
11-24 11:43:04.058  5613  5955 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 11:43:04.574   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:43:04.577   929  2987 D ConnectivityService: handlePromptUnvalidated 102
,11-24 11:43:05.576   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:43:06.057  5613  5660 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 178. Connection data: Peer properties: [null null].
11-24 11:43:06.057  5613  5660 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 11:43:06.058  5613  5660 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 178, name: My test thread name)
,11-24 11:43:06.088  5613  5955 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-24 11:43:06.088  5613  5955 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: My test thread name). Connection data: Peer properties: [null null].
11-24 11:43:06.088  5613  5955 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,11-24 11:43:06.214  5613  5956 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 180, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 11:43:06.214  5613  5956 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 11:43:06.578   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:43:06.646   929  2985 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,11-24 11:43:07.579   623   623 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-24 11:43:07.848  5613  5956 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 180, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 11:43:07.848  5613  5956 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 11:43:07.848  5613  5956 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 11:43:07.848  5613  5956 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 11:43:07.848  5613  5956 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-24 11:43:07.848  5613  5956 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-24 11:43:07.848  5613  5956 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-24 11:43:07.849  5613  5956 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 11:43:07.849  5613  5956 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-24 11:43:07.849  5613  5956 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 180, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 11:43:07.849  5613  5956 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-24 11:43:12.216  5613  5957 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 182, name: My test thread name). Connection data: Peer properties: [null null].
11-24 11:43:12.216  5613  5957 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 11:43:12.216  5613  5957 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 182, thread name: My test thread name). Connection data: Peer properties: [null null].
11-24 11:43:12.216  5613  5957 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 11:43:12.216  5613  5957 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 11:43:12.216  5613  5957 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 11:43:12.216  5613  5957 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-24 11:43:12.217  5613  5957 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-24 11:43:12.217  5613  5957 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-24 11:43:12.217  5613  5957 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 11:43:12.217  5613  5957 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-24 11:43:12.217  5613  5957 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 182, name: My test thread name). Connection data: Peer properties: [null null].
11-24 11:43:12.217  5613  5957 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-24 11:43:12.219  5613  5660 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-24 11:43:12.222  5613  5958 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 186, name: My test thread name). Connection data: Peer properties: [null null].
11-24 11:43:12.222  5613  5958 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 11:43:12.222  5613  5958 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 186, thread name: My test thread name): Test exception.
,11-24 11:43:12.223  5613  5958 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 186, name: My test thread name). Connection data: Peer properties: [null null].
11-24 11:43:12.223  5613  5958 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-24 11:43:12.223  5613  5958 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,11-24 11:43:12.223  5613  5958 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 186, name: My test thread name). Connection data: Peer properties: [null null].
11-24 11:43:12.223  5613  5958 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-24 11:43:12.228  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-24 11:43:12.228  5613  5660 I jxcore-log: 
,11-24 11:43:12.229  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-24 11:43:12.229  5613  5660 I jxcore-log: 
11-24 11:43:12.229  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-24 11:43:12.229  5613  5660 I jxcore-log: 
11-24 11:43:12.229  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-24 11:43:12.229  5613  5660 I jxcore-log: 
11-24 11:43:12.230  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - DEBUG UnitTest_app: 'Total duration:  92155'
11-24 11:43:12.230  5613  5660 I jxcore-log: 
,11-24 11:43:12.232  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-24 11:43:12.232  5613  5660 I jxcore-log: 
,11-24 11:43:12.235  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 11:43:12.235  5613  5660 I jxcore-log: 
,11-24 11:43:12.236  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 11:43:12.236  5613  5660 I jxcore-log: 
11-24 11:43:12.236  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-24 11:43:12.236  5613  5660 I jxcore-log: 
11-24 11:43:12.237  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-24 11:43:12.237  5613  5660 I jxcore-log: 
11-24 11:43:12.237  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 11:43:12.237  5613  5660 I jxcore-log: 
11-24 11:43:12.237  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 11:43:12.237  5613  5660 I jxcore-log: 
11-24 11:43:12.237  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 11:43:12.237  5613  5660 I jxcore-log: 
11-24 11:43:12.238  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 11:43:12.238  5613  5660 I jxcore-log: 
,11-24 11:43:12.238  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 11:43:12.238  5613  5660 I jxcore-log: 
11-24 11:43:12.238  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-24 11:43:12.238  5613  5660 I jxcore-log: 
11-24 11:43:12.239  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-24 11:43:12.239  5613  5660 I jxcore-log: 
11-24 11:43:12.239  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 11:43:12.239  5613  5660 I jxcore-log: 
11-24 11:43:12.239  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 11:43:12.239  5613  5660 I jxcore-log: 
11-24 11:43:12.239  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 11:43:12.239  5613  5660 I jxcore-log: 
11-24 11:43:12.239  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 11:43:12.239  5613  5660 I jxcore-log: 
11-24 11:43:12.240  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 11:43:12.240  5613  5660 I jxcore-log: 
11-24 11:43:12.240  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 11:43:12.240  5613  5660 I jxcore-log: 
11-24 11:43:12.240  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","ssidName":"<unknown ssid>"}'
11-24 11:43:12.240  5613  5660 I jxcore-log: 
11-24 11:43:12.240  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 11:43:12.240  5613  5660 I jxcore-log: 
11-24 11:43:12.241  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 11:43:12.241  5613  5660 I jxcore-log: 
11-24 11:43:12.241  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 11:43:12.241  5613  5660 I jxcore-log: 
11-24 11:43:12.241  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 11:43:12.241  5613  5660 I jxcore-log: 
,11-24 11:43:12.242  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-24 11:43:12.242  5613  5660 I jxcore-log: 
11-24 11:43:12.242  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 11:43:12.242  5613  5660 I jxcore-log: 
,11-24 11:43:12.243  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-24 11:43:12.243  5613  5660 I jxcore-log: 
11-24 11:43:12.244  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-24 11:43:12.244  5613  5660 I jxcore-log: 
,11-24 11:43:12.244  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 11:43:12.244  5613  5660 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-24 11:43:12.244  5613  5660 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 11:43:12.244  5613  5660 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,11-24 11:43:12.244  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 11:43:12.244  5613  5660 I jxcore-log: 
11-24 11:43:12.245  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 11:43:12.245  5613  5660 I jxcore-log: 
11-24 11:43:12.245  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 11:43:12.245  5613  5660 I jxcore-log: 
11-24 11:43:12.245  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 11:43:12.245  5613  5660 I jxcore-log: 
11-24 11:43:12.245  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 11:43:12.245  5613  5660 I jxcore-log: 
11-24 11:43:12.245  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 11:43:12.245  5613  5660 I jxcore-log: 
,11-24 11:43:12.251  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-24 11:43:12.251  5613  5660 I jxcore-log: 
,11-24 11:43:12.251  5613  5660 I jxcore-log: 2016-11-24 10:43:12 - WARN testUtils: 'myNameCallback not set!'
11-24 11:43:12.251  5613  5660 I jxcore-log: 
11-24 11:43:12.251  5613  5613 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
11-24 11:43:12.251  5613  5613 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-24 11:43:14.311  5613  5660 I jxcore-log: 2016-11-24 10:43:14 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-24 11:43:14.311  5613  5660 I jxcore-log: 
,11-24 11:43:14.313  5613  5660 I jxcore-log: 2016-11-24 10:43:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-24 11:43:14.313  5613  5660 I jxcore-log: 
,11-24 11:43:14.661  5613  5660 I jxcore-log: 2016-11-24 10:43:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-24 11:43:14.661  5613  5660 I jxcore-log: 
,11-24 11:43:14.671  5613  5660 I jxcore-log: 2016-11-24 10:43:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-24 11:43:14.671  5613  5660 I jxcore-log: 
,11-24 11:43:15.790  5613  5660 I jxcore-log: 2016-11-24 10:43:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-24 11:43:15.790  5613  5660 I jxcore-log: 
,11-24 11:43:15.984  5613  5660 I jxcore-log: 2016-11-24 10:43:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-24 11:43:15.984  5613  5660 I jxcore-log: 
,11-24 11:43:15.989  5613  5660 I jxcore-log: 2016-11-24 10:43:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-24 11:43:15.989  5613  5660 I jxcore-log: 
,11-24 11:43:15.994  5613  5660 I jxcore-log: 2016-11-24 10:43:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-24 11:43:15.994  5613  5660 I jxcore-log: 
,11-24 11:43:16.481  5613  5660 I jxcore-log: 2016-11-24 10:43:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-24 11:43:16.481  5613  5660 I jxcore-log: 
,11-24 11:43:16.526  5613  5660 I jxcore-log: 2016-11-24 10:43:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-24 11:43:16.526  5613  5660 I jxcore-log: 
,11-24 11:43:16.539  5613  5660 I jxcore-log: 2016-11-24 10:43:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-24 11:43:16.539  5613  5660 I jxcore-log: 
,11-24 11:43:16.543  5613  5660 I jxcore-log: 2016-11-24 10:43:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-24 11:43:16.543  5613  5660 I jxcore-log: 
,11-24 11:43:16.815  5613  5660 I jxcore-log: 2016-11-24 10:43:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-24 11:43:16.815  5613  5660 I jxcore-log: 
,11-24 11:43:16.945  5613  5660 I jxcore-log: 2016-11-24 10:43:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-24 11:43:16.945  5613  5660 I jxcore-log: 
,11-24 11:43:17.322  5613  5660 I jxcore-log: 2016-11-24 10:43:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-24 11:43:17.322  5613  5660 I jxcore-log: 
,11-24 11:43:17.331  5613  5660 I jxcore-log: 2016-11-24 10:43:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-24 11:43:17.331  5613  5660 I jxcore-log: 
,11-24 11:43:17.335  5613  5660 I jxcore-log: 2016-11-24 10:43:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-24 11:43:17.335  5613  5660 I jxcore-log: 
,11-24 11:43:17.340  5613  5660 I jxcore-log: 2016-11-24 10:43:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-24 11:43:17.340  5613  5660 I jxcore-log: 
,11-24 11:43:17.346  5613  5660 I jxcore-log: 2016-11-24 10:43:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-24 11:43:17.346  5613  5660 I jxcore-log: 
,11-24 11:43:17.374  5613  5660 I jxcore-log: 2016-11-24 10:43:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-24 11:43:17.374  5613  5660 I jxcore-log: 
,11-24 11:43:17.409  5613  5660 I jxcore-log: 2016-11-24 10:43:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-24 11:43:17.409  5613  5660 I jxcore-log: 
,11-24 11:43:17.416  5613  5660 I jxcore-log: 2016-11-24 10:43:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-24 11:43:17.416  5613  5660 I jxcore-log: 
,11-24 11:43:17.423  5613  5660 I jxcore-log: 2016-11-24 10:43:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-24 11:43:17.423  5613  5660 I jxcore-log: 
,11-24 11:43:17.438  5613  5660 I jxcore-log: 2016-11-24 10:43:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-24 11:43:17.438  5613  5660 I jxcore-log: 
,11-24 11:43:17.454  5613  5660 I jxcore-log: 2016-11-24 10:43:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-24 11:43:17.454  5613  5660 I jxcore-log: 
,11-24 11:43:17.460  5613  5660 I jxcore-log: 2016-11-24 10:43:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-24 11:43:17.460  5613  5660 I jxcore-log: 
,11-24 11:43:17.465  5613  5660 I jxcore-log: 2016-11-24 10:43:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-24 11:43:17.465  5613  5660 I jxcore-log: 
,11-24 11:43:17.478  5613  5660 I jxcore-log: 2016-11-24 10:43:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-24 11:43:17.478  5613  5660 I jxcore-log: 
,11-24 11:43:17.495  5613  5660 I jxcore-log: 2016-11-24 10:43:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-24 11:43:17.495  5613  5660 I jxcore-log: 
,11-24 11:43:17.510  5613  5660 I jxcore-log: 2016-11-24 10:43:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-24 11:43:17.510  5613  5660 I jxcore-log: 
,11-24 11:43:17.520  5613  5660 I jxcore-log: 2016-11-24 10:43:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-24 11:43:17.520  5613  5660 I jxcore-log: 
,11-24 11:43:17.533  5613  5660 I jxcore-log: 2016-11-24 10:43:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-24 11:43:17.533  5613  5660 I jxcore-log: 
,11-24 11:43:17.543  5613  5660 I jxcore-log: 2016-11-24 10:43:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-24 11:43:17.543  5613  5660 I jxcore-log: 
,11-24 11:43:17.556  5613  5660 I jxcore-log: 2016-11-24 10:43:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-24 11:43:17.556  5613  5660 I jxcore-log: 
,11-24 11:43:17.566  5613  5660 I jxcore-log: 2016-11-24 10:43:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-24 11:43:17.566  5613  5660 I jxcore-log: 
,11-24 11:43:17.573  5613  5660 I jxcore-log: 2016-11-24 10:43:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-24 11:43:17.573  5613  5660 I jxcore-log: 
,11-24 11:43:17.597  5613  5660 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-24 11:43:17.598  5613  5660 I jxcore-log: 2016-11-24 10:43:17 - INFO testUtils: 'BLE multiple advertisement supported'
11-24 11:43:17.598  5613  5660 I jxcore-log: 
,11-24 11:43:17.629  5613  5660 I jxcore-log: 2016-11-24 10:43:17 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-24 11:43:17.629  5613  5660 I jxcore-log: 
,11-24 11:43:17.976  5613  5660 I jxcore-log: 2016-11-24 10:43:17 - DEBUG CoordinatedClient: 'connected to the test server'
11-24 11:43:17.976  5613  5660 I jxcore-log: 
,11-24 11:43:27.581   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:43:28.582   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:43:29.583   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:43:30.585   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:43:31.586   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:43:32.587   623   623 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 11:43:36.557   929  2985 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 11:43:57.588   623   623 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 11:43:57.588   623   623 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 11:44:07.589   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:44:08.591   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:44:09.592   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:44:10.594   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:44:11.595   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:44:12.596   623   623 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 11:44:16.562   929  2985 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 11:44:17.598   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:44:18.599   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:44:19.601   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:44:20.602   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:44:21.603   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:44:22.604   623   623 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-24 11:44:32.606   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:44:33.607   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:44:34.609   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:44:35.610   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:44:36.564   929  2985 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 11:44:36.611   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:44:37.612   623   623 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-24 11:44:52.613   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:44:53.615   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:44:54.616   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:44:55.618   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:44:56.619   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:44:57.620   623   623 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-24 11:45:16.569   929  2985 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 11:45:17.622   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:45:18.623   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:45:19.624   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:45:20.625   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:45:21.626   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:45:22.627   623   623 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 11:45:36.572   929  2985 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 11:45:39.765   929  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 11:45:45.807   929  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 11:45:47.628   623   623 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 11:45:47.628   623   623 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 11:45:56.574   929  2985 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 11:46:02.630   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:46:03.631   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:46:04.633   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:46:05.634   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:46:06.636   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:46:07.636   623   623 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 11:46:12.638   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:46:13.639   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:46:14.641   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:46:15.642   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:46:16.644   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:46:17.645   623   623 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-24 11:46:27.646   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:46:28.648   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:46:29.649   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:46:30.650   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:46:31.652   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:46:32.653   623   623 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-24 11:46:36.578   929  2985 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 11:46:46.377   929  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 11:46:47.654   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:46:48.656   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:46:49.405   929  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 11:46:49.658   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:46:50.659   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:46:51.661   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:46:52.661   623   623 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-24 11:46:56.580   929  2985 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 11:47:12.663   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:47:13.664   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:47:14.665   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:47:15.666   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:47:16.583   929  2985 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 11:47:16.667   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:47:17.668   623   623 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 11:47:22.709   929  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 11:47:23.495   929  3820 I ActivityManager: Start proc 5969:com.google.android.youtube/u0a75 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,11-24 11:47:23.527  5969  5969 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm64
,11-24 11:47:23.625  5969  5981 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,11-24 11:47:23.694  5969  5981 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,11-24 11:47:23.736  5969  5981 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,11-24 11:47:23.767  5969  5969 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,11-24 11:47:23.794  5994  5994 I dex2oat : /system/bin/dex2oat -j2 --dex-file=/data/user/0/com.google.android.youtube/cache/ads447460913.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads447460913.dex
,11-24 11:47:23.832  5994  5994 I dex2oat : dex2oat took 37.890ms (threads: 2) arena alloc=180KB java alloc=37KB native alloc=1257KB free=1302KB
,11-24 11:47:23.933  5969  5969 W InstanceID/Rpc: Found 10012
,11-24 11:47:23.985   929   939 I ActivityManager: Killing 3397:android.process.acore/u0a2 (adj 15): empty #17
,11-24 11:47:25.745   929  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 11:47:34.822   929  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 11:47:36.586   929  2985 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 11:47:37.852   929  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 11:47:42.669   623   623 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 11:47:42.669   623   623 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 11:47:56.588   929  2985 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 11:48:02.671   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:48:03.672   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:48:04.673   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:48:04.843  5613  5660 I jxcore-log: 2016-11-24 10:48:04 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-24 11:48:04.843  5613  5660 I jxcore-log: 
,11-24 11:48:05.126  5613  5660 I jxcore-log: 2016-11-24 10:48:05 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-24 11:48:05.126  5613  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-24 11:48:05.126  5613  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-24 11:48:05.126  5613  5660 I jxcore-log: emit@events.js:82:1
11-24 11:48:05.126  5613  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-24 11:48:05.126  5613  5660 I jxcore-log: emit@events.js:82:1''
11-24 11:48:05.126  5613  5660 I jxcore-log: 
,11-24 11:48:05.127  5613  5660 I jxcore-log: 2016-11-24 10:48:05 - DEBUG CoordinatedClient: 'test client failed'
11-24 11:48:05.127  5613  5660 I jxcore-log: 
,11-24 11:48:05.139  5613  5660 I jxcore-log: 2016-11-24 10:48:05 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-24 11:48:05.139  5613  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-24 11:48:05.139  5613  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-24 11:48:05.139  5613  5660 I jxcore-log: emit@events.js:82:1
11-24 11:48:05.139  5613  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-24 11:48:05.139  5613  5660 I jxcore-log: emit@events.js:82:1''
11-24 11:48:05.139  5613  5660 I jxcore-log: 
,11-24 11:48:05.140  5613  5660 I jxcore-log: 2016-11-24 10:48:05 - DEBUG CoordinatedClient: 'test client failed'
11-24 11:48:05.140  5613  5660 I jxcore-log: 
,11-24 11:48:05.144  5613  5660 I jxcore-log: 2016-11-24 10:48:05 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-24 11:48:05.144  5613  5660 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-24 11:48:05.144  5613  5660 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-24 11:48:05.144  5613  5660 I jxcore-log: emit@events.js:82:1
11-24 11:48:05.144  5613  5660 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-24 11:48:05.144  5613  5660 I jxcore-log: emit@events.js:82:1''
11-24 11:48:05.144  5613  5660 I jxcore-log: 
,11-24 11:48:05.145  5613  5660 I jxcore-log: 2016-11-24 10:48:05 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-24 11:48:05.145  5613  5660 I jxcore-log: 
,11-24 11:48:05.674   623   623 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 11:48:05.705  6052  6052 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-24 11:48:05.730  6052  6052 D AndroidRuntime: CheckJNI is OFF
,11-24 11:48:05.758  6052  6052 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-24 11:48:05.795  6052  6052 I Radio-JNI: register_android_hardware_Radio DONE
,11-24 11:48:05.812  6052  6052 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-24 11:48:05.822   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
11-24 11:48:05.823   929   942 I ActivityManager: Killing 5613:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-24 11:48:05.935   929  3413 I WindowState: WIN DEATH: Window{5884a37 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-24 11:48:05.937   929  3149 D GraphicsStats: Buffer count: 2
11-24 11:48:05.938   929  2986 D WifiService: Client connection lost with reason: 4
,11-24 11:48:05.952   929   942 W ActivityManager: Force removing ActivityRecord{38a22ac u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-24 11:48:05.966   929   952 I art     : Starting a blocking GC Explicit
,11-24 11:48:05.971   929  3820 W ActivityManager: Spurious death for ProcessRecord{dc0cdfd 0:com.test.thalitest/u0a77}, curProc for 5613: null
,11-24 11:48:05.996   929  3413 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5613 uid 10077
,11-24 11:48:05.991  3413  3413 W Binder_5: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[16704]" dev="sockfs" ino=16704 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 11:48:05.991  3413  3413 W Binder_5: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[16704]" dev="sockfs" ino=16704 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 11:48:05.998  3655  3655 I Keyboard.Facilitator: onFinishInput()
,11-24 11:48:06.068  3963  6066 I MicroRecognitionRnrImpl: Starting detection.
,11-24 11:48:06.070  3963  6067 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@ae98f15
11-24 11:48:06.070   929   952 I art     : Explicit concurrent mark sweep GC freed 125526(8MB) AllocSpace objects, 79(2MB) LOS objects, 33% free, 29MB/44MB, paused 1.981ms total 103.485ms
,11-24 11:48:06.073   514  6069 I AudioFlinger: AudioFlinger's thread 0xf1a40000 ready to run
11-24 11:48:06.079   514  2992 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-24 11:48:06.080  3963  6067 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@ae98f15
,11-24 11:48:06.091   514  6069 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
11-24 11:48:06.091   514  6069 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-24 11:48:06.091   514  6069 I ACDB-LOADER: ACDB AFE returned = -19
11-24 11:48:06.091   514  6069 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-24 11:48:06.091   514  6069 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-24 11:48:06.091   514  6069 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
11-24 11:48:06.091   929   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-24 11:48:06.093  6052  6052 I art     : System.exit called, status: 0
,11-24 11:48:06.094  6052  6052 I AndroidRuntime: VM exiting with result code 0.
,11-24 11:48:06.102   514  6069 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-24 11:48:06.110   929   952 I ActivityManager: Start proc 6073:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-24 11:48:06.112   929   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-24 11:48:06.129  3655  3655 I Keyboard.Facilitator: resetDictionaries() : en_US
11-24 11:48:06.129  5853  5853 D BluetoothMapAppObserver: onReceive
11-24 11:48:06.129  5853  5853 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-24 11:48:06.135  3655  6086 I Keyboard.Facilitator.DecoderInitializer: run()
,11-24 11:48:06.135   929  2966 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-24 11:48:06.139  4042  4161 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-24 11:48:06.143  3655  6086 I Decoder : createOrResetDecoder
,11-24 11:48:06.162   929   942 I ActivityManager: Start proc 6089:android.process.acore/u0a2 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,11-24 11:48:06.167  3757  3757 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-24 11:48:06.169  3578  3578 I ConfigService: onCreate
,11-24 11:48:06.185  3963  3963 I HotwordWorkerImpl: onReady
,11-24 11:48:06.193   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-24 11:48:06.204    27    27 W kworker/1:1: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 11:48:06.209  3655  6086 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-24 11:48:06.207    27    27 W kworker/1:1: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 11:48:06.231    27    27 W kworker/1:1: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 11:48:06.241   929  3827 I ActivityManager: Start proc 6103:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
11-24 11:48:06.242  3781  3924 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-24 11:48:06.242  3781  3924 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3781
11-24 11:48:06.242  3781  3924 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
11-24 11:48:06.242  3781  3924 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-24 11:48:06.242  3781  3924 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-24 11:48:06.242  3781  3924 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-24 11:48:06.242  3781  3924 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-24 11:48:06.242  3781  3924 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-24 11:48:06.242  3781  3924 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-24 11:48:06.242  3781  3924 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-24 11:48:06.242  3781  3924 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-24 11:48:06.242  3781  3924 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-24 11:48:06.242  3781  3924 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 11:48:06.242  3781  3924 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 11:48:06.246   929  6113 E DropBoxManagerService: Can't write: system_app_crash
11-24 11:48:06.246   929  6113 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
11-24 11:48:06.246   929  6113 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 11:48:06.246   929  6113 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 11:48:06.246   929  6113 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 11:48:06.246   929  6113 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-24 11:48:06.246   929  6113 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 11:48:06.246   929  6113 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 11:48:06.246   929  6113 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 11:48:06.246   929  6113 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-24 11:48:06.246   929  6113 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 11:48:06.246   929  6113 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 11:48:06.246   929  6113 E DropBoxManagerService: 	... 5 more
,11-24 11:48:06.246   929  3155 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-24 11:48:06.250  3963  3974 W SearchService: Abort, client detached.
11-24 11:48:06.253  3963  4180 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@ae98f15
11-24 11:48:06.254  3963  6067 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-24 11:48:06.254  3963  3963 I HotwordDetector: Closing mic
,11-24 11:48:06.261   779   779 W Binder_3: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[15248]" dev="sockfs" ino=15248 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-24 11:48:06.261   779   779 W Binder_3: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[15248]" dev="sockfs" ino=15248 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 11:48:06.269   929  6117 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-24 11:48:06.264   779   779 W Binder_3: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[35004]" dev="sockfs" ino=35004 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-24 11:48:06.264   779   779 W Binder_3: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[35004]" dev="sockfs" ino=35004 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 11:48:06.273  6089  6089 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm64
,11-24 11:48:06.284  3655  6086 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,11-24 11:48:06.287  3655  6086 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,11-24 11:48:06.287  3655  6086 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,11-24 11:48:06.307  3655  6086 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
11-24 11:48:06.307  3655  6086 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,11-24 11:48:06.307  3655  6086 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-24 11:48:06.307  3655  6086 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-24 11:48:06.308  3655  6086 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
11-24 11:48:06.308  3655  6086 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-24 11:48:06.308  3655  6086 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-24 11:48:06.308  3655  6086 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-24 11:48:06.308  3655  6086 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-24 11:48:06.308  3655  6086 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,11-24 11:48:06.318   514  6069 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,11-24 11:48:06.319   514  6069 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,11-24 11:48:06.325   514  6069 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-24 11:48:06.325   514  6069 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
,11-24 11:48:06.326   514  2992 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-24 11:48:06.328  3963  4208 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-24 11:48:06.328  3963  6066 I MicroRecognitionRnrImpl: Detection finished
,11-24 11:48:06.397  6089  6089 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm64
,11-24 11:48:06.423  6089  6124 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-24 11:48:06.614   382   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
