#### Test 9510406483d1755_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-28 18:15:07.759  3953  4195 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-28 18:15:07.845  3953  4195 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-28 18:15:08.217  5570  5570 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-28 18:15:08.222  5570  5570 D AndroidRuntime: CheckJNI is OFF
11-28 18:15:08.247  5570  5570 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-28 18:15:08.278  5570  5570 I Radio-JNI: register_android_hardware_Radio DONE
11-28 18:15:08.293  5570  5570 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-28 18:15:08.300   928  3787 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-28 18:15:08.317  5570  5570 D AndroidRuntime: Shutting down VM
11-28 18:15:08.334  3934  3950 W SearchService: Abort, client detached.
11-28 18:15:08.338  3934  3934 I HotwordDetector: Closing mic
11-28 18:15:08.339  3934  4174 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@997df35
11-28 18:15:08.339  3934  4178 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-28 18:15:08.361   928  3787 I ActivityManager: Start proc 5580:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-28 18:15:08.414   511  4180 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-28 18:15:08.417   511  4180 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-28 18:15:08.423   511  4180 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-28 18:15:08.423   511  4180 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-28 18:15:08.424   511  2986 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-28 18:15:08.427  3934  4175 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-28 18:15:08.427  3934  4177 I MicroRecognitionRnrImpl: Detection finished
11-28 18:15:08.449  5580  5580 I CordovaLog: Changing log level to DEBUG(3)
11-28 18:15:08.449  5580  5580 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-28 18:15:08.449  5580  5580 D CordovaActivity: CordovaActivity.onCreate()
11-28 18:15:08.455  5580  5580 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-28 18:15:08.487  5580  5580 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-28 18:15:08.548  5580  5580 I LibraryLoader: Time to load native libraries: 55 ms (timestamps 5586-5641)
,11-28 18:15:08.548  5580  5580 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-28 18:15:08.582  5580  5580 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6248a3c}
,11-28 18:15:08.582  5580  5580 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-28 18:15:08.583  5580  5580 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-28 18:15:08.589  5580  5580 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-28 18:15:08.591  5580  5580 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-28 18:15:08.638  5580  5580 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-28 18:15:08.652  5580  5580 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-28 18:15:08.652  5580  5580 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-28 18:15:08.652  5580  5580 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-28 18:15:08.652  5580  5580 I Adreno  : Build Date                       : 12/06/15
11-28 18:15:08.652  5580  5580 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-28 18:15:08.652  5580  5580 I Adreno  : Local Branch                     : mybranch17112971
11-28 18:15:08.652  5580  5580 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-28 18:15:08.652  5580  5580 I Adreno  : Remote Branch                    : NONE
11-28 18:15:08.652  5580  5580 I Adreno  : Reconstruct Branch               : NOTHING
,11-28 18:15:08.711   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9d7a27f:true
,11-28 18:15:08.746   407   407 W Binder_2: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[25214]" dev="sockfs" ino=25214 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-28 18:15:08.746   407   407 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[25214]" dev="sockfs" ino=25214 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-28 18:15:08.759  5580  5580 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-28 18:15:08.768  5580  5580 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-28 18:15:08.772  5580  5580 D PluginManager: init()
,11-28 18:15:08.775  5580  5580 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-28 18:15:08.814  5580  5580 D CordovaActivity: Started the activity.
11-28 18:15:08.814  5580  5580 D CordovaActivity: Resumed the activity.
,11-28 18:15:08.819  5580  5617 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-28 18:15:08.816  2575  2575 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33796]" dev="sockfs" ino=33796 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-28 18:15:08.816  2575  2575 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33796]" dev="sockfs" ino=33796 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-28 18:15:08.820  3843  3843 W Binder_8: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32797]" dev="sockfs" ino=32797 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-28 18:15:08.820  3843  3843 W Binder_8: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[32797]" dev="sockfs" ino=32797 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-28 18:15:08.823  5580  5604 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-28 18:15:08.848  5580  5617 I OpenGLRenderer: Initialized EGL, version 1.4
,11-28 18:15:08.930  3406  3406 W Binder_5: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[30558]" dev="sockfs" ino=30558 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-28 18:15:08.930  3406  3406 W Binder_5: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[30558]" dev="sockfs" ino=30558 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-28 18:15:08.931   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +592ms
,11-28 18:15:08.933  3843  3843 W Binder_8: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[30557]" dev="sockfs" ino=30557 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-28 18:15:08.933  3843  3843 W Binder_8: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[30557]" dev="sockfs" ino=30557 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-28 18:15:08.937  3653  3653 I Keyboard.Facilitator: onFinishInput()
,11-28 18:15:08.950  5580  5580 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-28 18:15:08.961  5580  5580 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5580
,11-28 18:15:09.059  5580  5580 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-28 18:15:09.336  5580  5620 D jxcore_app_log: JniHelper::setJavaVM(0xf51bc000), pthread_self() = -586938064
,11-28 18:15:09.344  5580  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-28 18:15:09.344  5580  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-28 18:15:09.344  5580  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-28 18:15:09.344  5580  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-28 18:15:09.344  5580  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-28 18:15:09.344  5580  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b214983 added. We now have 1 listener(s)
,11-28 18:15:09.349  5580  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-28 18:15:09.350  5580  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-28 18:15:09.351  5580  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 18:15:09.351  5580  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-28 18:15:09.356  5580  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-28 18:15:09.356  5580  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-28 18:15:09.356  5580  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-28 18:15:09.356  5580  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-28 18:15:09.356  5580  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-28 18:15:09.356  5580  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-28 18:15:09.356  5580  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-28 18:15:09.356  5580  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-28 18:15:09.356  5580  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-28 18:15:09.356  5580  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-28 18:15:09.356  5580  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-28 18:15:09.356  5580  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-28 18:15:09.356  5580  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-28 18:15:09.356  5580  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-28 18:15:09.356  5580  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c80557e added. We now have 1 listener(s)
11-28 18:15:09.357  5580  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-28 18:15:09.363   928  2965 D WifiService: New client listening to asynchronous messages
11-28 18:15:09.364  5580  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-28 18:15:09.364  5580  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-28 18:15:09.365  5580  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-28 18:15:09.365  5580  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-28 18:15:09.365  5580  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-28 18:15:09.365  5580  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-28 18:15:09.365  5580  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-28 18:15:09.368  5580  5620 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-28 18:15:09.386  5580  5580 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-28 18:15:09.398  5580  5580 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,11-28 18:15:09.398  5580  5580 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-28 18:15:09.794  5580  5628 W jxcore-log: Initializing JXcore engine
,11-28 18:15:09.794  5580  5628 W jxcore-log: JXcore engine is ready
,11-28 18:15:09.820  5628  5628 W Thread-62: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12551 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-28 18:15:09.820  5628  5628 W Thread-62: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[16403]" dev="sockfs" ino=16403 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,11-28 18:15:09.820  5628  5628 W Thread-62: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-28 18:15:09.820  5628  5628 W Thread-62: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32752]" dev="sockfs" ino=32752 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-28 18:15:09.827  5580  5628 W jxcore-log: Starting JXcore engine
,11-28 18:15:09.880  5580  5628 W jxcore-log: Platform android
11-28 18:15:09.880  5580  5628 W jxcore-log: 
11-28 18:15:09.880  5580  5628 W jxcore-log: Process ARCH arm
11-28 18:15:09.880  5580  5628 W jxcore-log: 
,11-28 18:15:10.029  5580  5628 I jxcore-log: JXcore Cordova bridge is ready!
11-28 18:15:10.029  5580  5628 I jxcore-log: 
,11-28 18:15:10.029  5580  5628 W jxcore-log: JXcore engine is started
,11-28 18:15:10.034  5580  5620 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-28 18:15:10.037  5580  5580 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,11-28 18:15:10.037  5580  5580 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-28 18:15:11.857  3571  3571 I ConfigService: onDestroy
,11-28 18:15:13.220   928  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-28 18:15:13.347   928  3845 I ActivityManager: Killing 5024:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-28 18:15:14.173   928  2964 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-28 18:15:16.249   928  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-28 18:15:16.933   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:15:17.935   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:15:18.378   928  2915 I ActivityManager: Killing 5366:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-28 18:15:18.531   928  2965 D WifiService: New client listening to asynchronous messages
,11-28 18:15:18.535  3934  5629 W CronetSyncConnectionRcs: Upload content type not set.
,11-28 18:15:18.936   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:15:19.642  5580  5628 I jxcore-log: 2016-11-28 17:15:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-28 18:15:19.642  5580  5628 I jxcore-log: 
,11-28 18:15:19.643  5580  5628 I jxcore-log: 2016-11-28 17:15:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-28 18:15:19.643  5580  5628 I jxcore-log: 
,11-28 18:15:19.648  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-28 18:15:19.649  5580  5628 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-28 18:15:19.649  5580  5628 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 18:15:19.649  5580  5628 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 18:15:19.649  5580  5628 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 18:15:19.649  5580  5628 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 18:15:19.649  5580  5628 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 18:15:19.649  5580  5628 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 18:15:19.649  5580  5628 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 18:15:19.649  5580  5628 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-28 18:15:19.650  5580  5628 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-28 18:15:19.652  5580  5628 I jxcore-log: 2016-11-28 17:15:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-28 18:15:19.652  5580  5628 I jxcore-log: 
,11-28 18:15:19.654  5580  5628 I jxcore-log: 2016-11-28 17:15:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-28 18:15:19.654  5580  5628 I jxcore-log: 
,11-28 18:15:19.901  5580  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-28 18:15:19.901  5580  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd83418 added. We now have 2 listener(s)
,11-28 18:15:19.902  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-28 18:15:19.902  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-28 18:15:19.902  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-28 18:15:19.902  5580  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 18:15:19.902  5580  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77dae71 added. We now have 2 listener(s)
,11-28 18:15:19.902  5580  5628 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 18:15:19.903  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-28 18:15:19.904  5580  5628 D ExecuteNativeTests: Running unit tests
11-28 18:15:19.905  5580  5628 D BluetoothAdapter: enable(): BT is already enabled..!
11-28 18:15:19.905   928  3146 D WifiService: setWifiEnabled: true pid=5580, uid=10077
,11-28 18:15:19.905   928  3146 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-28 18:15:19.937   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:15:20.938   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:15:21.510  4837  4882 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-28 18:15:21.512  4837  4837 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-28 18:15:21.939   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-28 18:15:29.910  5580  5628 I com.test.thalitest.ThaliTestRunner: Running UT
,11-28 18:15:29.981  5580  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-28 18:15:29.981  5580  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80153db added. We now have 3 listener(s)
,11-28 18:15:29.982  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-28 18:15:29.982  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-28 18:15:29.982  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-28 18:15:29.982  5580  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-28 18:15:29.983  5580  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67f9e78 added. We now have 3 listener(s)
11-28 18:15:29.983  5580  5628 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 18:15:29.984  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-28 18:15:29.989  5580  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
11-28 18:15:29.989  5580  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-28 18:15:29.989  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 18:15:29.989  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 18:15:29.989  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 18:15:29.991  5580  5628 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-28 18:15:29.991  5580  5628 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-28 18:15:29.991  5580  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-28 18:15:29.991  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-28 18:15:29.991  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 18:15:29.991  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 18:15:29.992  5580  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-28 18:15:29.993  5580  5628 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-28 18:15:29.994  5580  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
11-28 18:15:29.996  5580  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-28 18:15:29.996  5580  5628 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,11-28 18:15:29.997  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 18:15:29.997  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-28 18:15:30.003  5580  5628 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-28 18:15:30.003  5580  5628 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 18:15:30.003  5580  5628 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 18:15:30.003  5580  5628 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 18:15:30.003  5580  5628 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 18:15:30.003  5580  5628 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 18:15:30.003  5580  5628 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 18:15:30.003  5580  5628 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 18:15:30.003  5580  5628 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-28 18:15:30.005  5580  5628 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-28 18:15:30.005  5580  5628 D io.jxcore.node.ConnectivityMonitor: start: OK
11-28 18:15:30.005  5580  5628 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-28 18:15:30.005  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-28 18:15:30.005  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:30.005  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.005  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.005  5580  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-28 18:15:30.005  5580  5628 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-28 18:15:30.005  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-28 18:15:30.005  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 18:15:30.006  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-28 18:15:30.007  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-28 18:15:30.007  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-28 18:15:30.008  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-28 18:15:30.008  5580  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-28 18:15:30.010  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-28 18:15:30.010  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-28 18:15:30.010  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-28 18:15:30.011  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 18:15:30.013  5580  5643 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-28 18:15:30.014  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-28 18:15:30.014  5580  5580 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-28 18:15:30.016  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-28 18:15:30.016  5580  5628 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-28 18:15:30.016  5580  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-28 18:15:30.016  5580  5643 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-28 18:15:30.020  5580  5643 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-28 18:15:30.016  4653  4653 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[30577]" dev="sockfs" ino=30577 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-28 18:15:30.016  4653  4653 W Binder_2: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[30577]" dev="sockfs" ino=30577 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 18:15:30.021  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.021  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-28 18:15:30.022  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 18:15:30.022  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-28 18:15:30.022  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 1
11-28 18:15:30.023  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.023  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.023  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-28 18:15:30.023  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-28 18:15:30.024  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 18:15:30.024  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
11-28 18:15:30.024  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 18:15:30.024  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 18:15:30.024  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:30.024  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-28 18:15:30.024  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-28 18:15:30.024  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.024  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.024  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:30.025  5580  5628 D BluetoothAdapter: STATE_ON
11-28 18:15:30.027  4633  4851 D BtGatt.GattService: registerClient() - UUID=15d1b05a-843c-4f98-98f9-18314a86d921
11-28 18:15:30.028  4633  4703 D BtGatt.GattService: onClientRegistered() - UUID=15d1b05a-843c-4f98-98f9-18314a86d921, clientIf=5
11-28 18:15:30.029  5580  5590 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-28 18:15:30.031  4633  4705 D BtGatt.AdvertiseManager: message : 0
,11-28 18:15:30.034  4633  4705 D BtGatt.AdvertiseManager: starting multi advertising
,11-28 18:15:30.050  4633  4703 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-28 18:15:30.057  4633  4703 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-28 18:15:30.059  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.059  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:30.059  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-28 18:15:30.059  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.059  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.059  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.059  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.059  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.059  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-28 18:15:30.060  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 18:15:30.060  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.060  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.060  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.060  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.061  5580  5628 I io.jxcore.node.ConnectionHelper: start: OK
11-28 18:15:30.061  5580  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-28 18:15:30.061  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-28 18:15:30.061  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-28 18:15:30.062  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-28 18:15:30.062  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-28 18:15:30.062  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-28 18:15:30.062  5580  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 18:15:30.062  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 18:15:30.063  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-28 18:15:30.063  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 18:15:30.063  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 18:15:30.063  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-28 18:15:30.063  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 18:15:30.064  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-28 18:15:30.064  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 18:15:30.067  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 18:15:30.067  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-28 18:15:30.068  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 18:15:30.068  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 18:15:30.068  5580  5580 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-28 18:15:30.563  5580  5644 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,11-28 18:15:30.565  5580  5628 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-28 18:15:30.565  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-28 18:15:30.565  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-28 18:15:30.566  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-28 18:15:30.566  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,11-28 18:15:30.566  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-28 18:15:30.566  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-28 18:15:30.566  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-28 18:15:30.566  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-28 18:15:30.566  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-28 18:15:30.566  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,11-28 18:15:30.567  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-28 18:15:30.567  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-28 18:15:30.567  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-28 18:15:30.567  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-28 18:15:30.567  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-28 18:15:30.567  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-28 18:15:30.567  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-28 18:15:30.567  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,11-28 18:15:30.568  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-28 18:15:30.568  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-28 18:15:30.568  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-28 18:15:30.568  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-28 18:15:30.568  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-28 18:15:30.568  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-28 18:15:30.568  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-28 18:15:30.569  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-28 18:15:30.569  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-28 18:15:30.569  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-28 18:15:30.569  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-28 18:15:30.569  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-28 18:15:30.569  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-28 18:15:30.569  5580  5628 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-28 18:15:30.569  5580  5580 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-28 18:15:30.570  5580  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-28 18:15:30.570  5580  5628 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-28 18:15:30.570  5580  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-28 18:15:30.570  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-28 18:15:30.570  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-28 18:15:30.571  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-28 18:15:30.571  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-28 18:15:30.571  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-28 18:15:30.571  5580  5643 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-28 18:15:30.571  5580  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-28 18:15:30.571  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-28 18:15:30.571  5580  5643 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-28 18:15:30.571  5580  5628 D org.thaliproject.p2p.btconnectorlib.,DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.572  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 18:15:30.571  5580  5643 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-28 18:15:30.572  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 18:15:30.573  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62,
11-28 18:15:30.573  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.573  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.573  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:30.574  5580  5628 D BluetoothAdapter: STATE_ON
11-28 18:15:30.574  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-28 18:15:30.575  5580  5628 D BluetoothAdapter: STATE_ON
11-28 18:15:30.575  5580  5628 D BluetoothLeScanner: could not find callback wrapper
,11-28 18:15:30.575  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-28 18:15:30.576  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.576  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.576  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.576  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-28 18:15:30.576  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.577  4633  4705 D BtGatt.AdvertiseManager: message : 1
11-28 18:15:30.578  4633  4705 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-28 18:15:30.589  4633  4703 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-28 18:15:30.589  4633  4703 D BtGatt.GattService: Client app is not null!
11-28 18:15:30.590  4633  4652 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 18:15:30.590  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-28 18:15:30.590  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.590  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-28 18:15:30.591  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:30.591  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.591  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.591  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-28 18:15:30.591  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-28 18:15:30.592  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 18:15:30.592  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:30.593  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:30.593  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-28 18:15:30.594  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.594  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.594  5580  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 18:15:30.594  5580  5580 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-28 18:15:30.595  5580  5580 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-28 18:15:30.595  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 18:15:30.595  5580  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-28 18:15:30.595  5580  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:15:30.596  5580  5645 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
11-28 18:15:30.595  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 18:15:30.596  5580  5628 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-28 18:15:30.596  5580  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-28 18:15:30.597  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 18:15:30.597  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-28 18:15:30.597  5580  5628 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-28 18:15:30.597  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-28 18:15:30.597  5580  5628 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-28 18:15:30.597  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-28 18:15:30.598  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.598  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 18:15:30.598  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:30.598  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-28 18:15:30.598  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.598  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 18:15:30.598  5580  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-28 18:15:30.598  5580  5628 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-28 18:15:30.598  5580  5580 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 18:15:30.598  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-28 18:15:30.598  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-28 18:15:30.598  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-28 18:15:30.598  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-28 18:15:30.605  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-28 18:15:30.605  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-28 18:15:30.605  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-28 18:15:30.605  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-28 18:15:30.605  5580  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-28 18:15:30.605  5580  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-28 18:15:30.606  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 18:15:30.606  5580  5646 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 18:15:30.606  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-28 18:15:30.606  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 18:15:30.606  5580  5580 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-28 18:15:30.606  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-28 18:15:30.606  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 18:15:30.606  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-28 18:15:30.609  5580  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-28 18:15:30.606  4652  4652 W Binder_1: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[33885]" dev="sockfs" ino=33885 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 18:15:30.609  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-28 18:15:30.609  5580  5628 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 18:15:30.609  5580  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-28 18:15:30.606  4652  4652 W Binder_1: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33885]" dev="sockfs" ino=33885 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-28 18:15:30.613  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:30.613  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-28 18:15:30.614  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-28 18:15:30.614  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 18:15:30.614  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 2
11-28 18:15:30.616  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.616  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.616  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-28 18:15:30.616  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-28 18:15:30.616  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 18:15:30.616  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-28 18:15:30.616  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 18:15:30.616  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 18:15:30.616  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.617  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-28 18:15:30.617  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-28 18:15:30.617  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.617  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.617  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.618  5580  5628 D BluetoothAdapter: STATE_ON
,11-28 18:15:30.620  4633  4652 D BtGatt.GattService: registerClient() - UUID=96cf71f4-8dbd-49b4-aa2b-0f3c03fb45e9
,11-28 18:15:30.621  4633  4703 D BtGatt.GattService: onClientRegistered() - UUID=96cf71f4-8dbd-49b4-aa2b-0f3c03fb45e9, clientIf=5
11-28 18:15:30.621  5580  5624 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-28 18:15:30.622  4633  4705 D BtGatt.AdvertiseManager: message : 0
,11-28 18:15:30.625  4633  4705 D BtGatt.AdvertiseManager: starting multi advertising
,11-28 18:15:30.635  4633  4703 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-28 18:15:30.642  4633  4703 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-28 18:15:30.642  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:30.643  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.643  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-28 18:15:30.643  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.643  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.643  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.643  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.643  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.643  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-28 18:15:30.645  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 18:15:30.645  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.646  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.646  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.646  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:30.646  5580  5628 I io.jxcore.node.ConnectionHelper: start: OK
11-28 18:15:30.646  5580  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-28 18:15:30.646  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-28 18:15:30.647  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-28 18:15:30.647  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-28 18:15:30.647  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-28 18:15:30.647  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-28 18:15:30.647  5580  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 18:15:30.647  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 18:15:30.647  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-28 18:15:30.647  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 18:15:30.647  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 18:15:30.647  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-28 18:15:30.647  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 18:15:30.647  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-28 18:15:30.647  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-28 18:15:30.650  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 18:15:30.650  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-28 18:15:30.650  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 18:15:30.650  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 18:15:30.650  5580  5580 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-28 18:15:31.148  5580  5647 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,11-28 18:15:31.151  5580  5580 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-28 18:15:31.151  5580  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,11-28 18:15:31.152  5580  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-28 18:15:31.152  5580  5628 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-28 18:15:31.152  5580  5580 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-28 18:15:31.152  5580  5628 V io.jxcore.node.ConnectivityMonitor: start: Already started
,11-28 18:15:31.152  5580  5628 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,11-28 18:15:31.152  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-28 18:15:31.153  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:31.153  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:31.153  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.156  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-28 18:15:31.156  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-28 18:15:31.156  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-28 18:15:31.156  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-28 18:15:31.156  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-28 18:15:31.156  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-28 18:15:31.156  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-28 18:15:31.156  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-28 18:15:31.156  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-28 18:15:31.156  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.156  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 3
,11-28 18:15:31.159  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.159  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:31.159  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.161  4633  4705 D BtGatt.AdvertiseManager: message : 1
11-28 18:15:31.162  4633  4705 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-28 18:15:31.173  4633  4703 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-28 18:15:31.173  4633  4703 D BtGatt.GattService: Client app is not null!
,11-28 18:15:31.174  4633  4653 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 18:15:31.175  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-28 18:15:31.175  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:31.175  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-28 18:15:31.175  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.175  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.175  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.175  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-28 18:15:31.175  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.176  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.176  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.176  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-28 18:15:31.176  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-28 18:15:31.176  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 18:15:31.176  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
11-28 18:15:31.176  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-28 18:15:31.176  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 18:15:31.177  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.177  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-28 18:15:31.177  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-28 18:15:31.177  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.178  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.178  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.179  5580  5628 D BluetoothAdapter: STATE_ON
,11-28 18:15:31.182  4633  4851 D BtGatt.GattService: registerClient() - UUID=7aa608bf-4d63-4ad2-b14c-c61c13281cf3
11-28 18:15:31.182  4633  4703 D BtGatt.GattService: onClientRegistered() - UUID=7aa608bf-4d63-4ad2-b14c-c61c13281cf3, clientIf=5
,11-28 18:15:31.183  5580  5624 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-28 18:15:31.184  4633  4705 D BtGatt.AdvertiseManager: message : 0
11-28 18:15:31.189  4633  4705 D BtGatt.AdvertiseManager: starting multi advertising
,11-28 18:15:31.202  4633  4703 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-28 18:15:31.210  4633  4703 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-28 18:15:31.211  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-28 18:15:31.211  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.211  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.211  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-28 18:15:31.211  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.211  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.211  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.211  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.211  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.211  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.212  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 18:15:31.212  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-28 18:15:31.212  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-28 18:15:31.212  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:31.212  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.212  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 18:15:31.212  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.212  5580  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-28 18:15:31.212  5580  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 18:15:31.212  5580  5628 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 18:15:31.212  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.212  5580  5628 I io.jxcore.node.ConnectionHelper: start: OK
11-28 18:15:31.212  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-28 18:15:31.212  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-28 18:15:31.212  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.212  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-28 18:15:31.213  5580  5648 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
11-28 18:15:31.214  5580  5628 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-28 18:15:31.214  5580  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-28 18:15:31.214  5580  5628 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-28 18:15:31.214  5580  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-28 18:15:31.214  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-28 18:15:31.214  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-28 18:15:31.214  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-28 18:15:31.214  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-28 18:15:31.214  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-28 18:15:31.214  5580  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-28 18:15:31.215  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-28 18:15:31.215  5580  5580 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-28 18:15:31.215  5580  5646 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-28 18:15:31.215  5580  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-28 18:15:31.215  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:31.215  5580  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-28 18:15:31.215  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 18:15:31.215  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 18:15:31.215  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.215  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.215  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.215  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:31.216  5580  5628 D BluetoothAdapter: STATE_ON
11-28 18:15:31.216  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-28 18:15:31.217  5580  5628 D BluetoothAdapter: STATE_ON
11-28 18:15:31.217  5580  5628 D BluetoothLeScanner: could not find callback wrapper
11-28 18:15:31.217  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-28 18:15:31.217  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.218  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:31.218  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.218  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-28 18:15:31.218  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.219  4633  4705 D BtGatt.AdvertiseManager: message : 1
11-28 18:15:31.219  4633  4705 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-28 18:15:31.227  4633  4703 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-28 18:15:31.227  4633  4703 D BtGatt.GattService: Client app is not null!
,11-28 18:15:31.228  4633  4851 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 18:15:31.229  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-28 18:15:31.229  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.229  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-28 18:15:31.229  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.229  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.229  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.229  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-28 18:15:31.229  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-28 18:15:31.230  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-28 18:15:31.231  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:31.232  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.232  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 18:15:31.232  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.232  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.233  5580  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 18:15:31.233  5580  5580 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-28 18:15:31.233  5580  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-28 18:15:31.233  5580  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:15:31.233  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 18:15:31.233  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 18:15:31.233  5580  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-28 18:15:31.234  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.234  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 18:15:31.234  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-28 18:15:31.234  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.234  5580  5649 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
11-28 18:15:31.234  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.234  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.234  5580  5580 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 18:15:31.234  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.234  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.235  5580  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-28 18:15:31.235  5580  5628 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-28 18:15:31.235  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.236  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.236  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: upda,teState finished Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.236  5580  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-28 18:15:31.237  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-28 18:15:31.238  5580  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-28 18:15:31.238  5580  5628 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-28 18:15:31.239  5580  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-28 18:15:31.239  5580  5628 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-28 18:15:31.239  5580  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-28 18:15:31.239  5580  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-28 18:15:31.240  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 18:15:31.240  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 18:15:31.240  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 18:15:31.240  5580  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-28 18:15:31.240  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 18:15:31.240  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 18:15:31.240  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 18:15:31.240  5580  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-28 18:15:31.241  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 18:15:31.241  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 18:15:31.241  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 18:15:31.241  5580  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-28 18:15:31.242  5580  5628 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-28 18:15:31.242  5580  5628 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-28 18:15:31.242  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-28 18:15:31.244  5580  5628 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-28 18:15:31.245  5580  5628 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-28 18:15:31.245  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-28 18:15:31.245  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-28 18:15:31.245  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-28 18:15:31.245  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-28 18:15:31.245  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-28 18:15:31.245  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-28 18:15:31.245  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-28 18:15:31.245  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-28 18:15:31.245  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-28 18:15:31.245  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-28 18:15:31.245  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-28 18:15:31.245  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-28 18:15:31.245  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-28 18:15:31.246  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-28 18:15:31.246  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-28 18:15:31.246  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-28 18:15:31.246  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-28 18:15:31.246  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-28 18:15:31.246  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-28 18:15:31.246  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-28 18:15:31.246  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-28 18:15:31.246  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-28 18:15:31.246  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-28 18:15:31.246  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-28 18:15:31.246  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-28 18:15:31.246  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-28 18:15:31.246  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-28 18:15:31.246  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-28 18:15:31.246  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-28 18:15:31.246  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-28 18:15:31.246  5580  5628 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-28 18:15:31.247  5580  5628 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-28 18:15:31.247  5580  5628 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-28 18:15:31.247  5580  5628 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-28 18:15:31.247  5580  5628 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-28 18:15:31.247  5580  5628 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-28 18:15:31.247  5580  5628 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-28 18:15:31.247  5580  5628 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-28 18:15:31.247  5580  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-28 18:15:31.252  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-28 18:15:31.253  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
11-28 18:15:31.253  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-28 18:15:31.254  5580  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-28 18:15:31.254  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-28 18:15:31.254  5580  5628 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-28 18:15:31.254  5580  5628 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-28 18:15:31.254  5580  5628 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-28 18:15:31.254  5580  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 134)
11-28 18:15:31.255  5580  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-28 18:15:31.255  5580  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-28 18:15:31.255  5580  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: given port
11-28 18:15:31.255  5580  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
11-28 18:15:31.255  5580  5650 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-28 18:15:31.255  5580  5650 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 18:15:31.256  5580  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-28 18:15:31.256  5580  5628 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-28 18:15:31.256  4653  4653 W Binder_2: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[29391]" dev="sockfs" ino=29391 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 18:15:31.256  4653  4653 W Binder_2: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[29391]" dev="sockfs" ino=29391 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 18:15:31.258  5580  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-28 18:15:31.258  5580  5628 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-28 18:15:31.259  5580  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-28 18:15:31.259  5580  5628 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-28 18:15:31.259  5580  5628 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-28 18:15:31.259  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-28 18:15:31.259  5580  5628 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-28 18:15:31.259  5580  5628 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-28 18:15:31.259  5580  5628 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-28 18:15:31.259  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-28 18:15:31.259  5580  5628 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-28 18:15:31.259  5580  5628 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-28 18:15:31.260  5580  5628 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-28 18:15:31.260  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-28 18:15:31.260  5580  5628 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-28 18:15:31.261  5580  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-28 18:15:31.261  5580  5628 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-28 18:15:31.261  5580  5628 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-28 18:15:31.261  5580  5628 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-28 18:15:31.261  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-28 18:15:31.261  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.261  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.261  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.261  5580  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-28 18:15:31.262  5580  5628 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-28 18:15:31.262  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-28 18:15:31.262  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 18:15:31.263  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-28 18:15:31.264  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-28 18:15:31.264  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-28 18:15:31.264  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-28 18:15:31.264  5580  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-28 18:15:31.264  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-28 18:15:31.264  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 18:15:31.264  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-28 18:15:31.264  5580  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-28 18:15:31.264  5580  5580 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-28 18:15:31.265  5580  5651 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 18:15:31.266  4851  4851 W Binder_3: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[31350]" dev="sockfs" ino=31350 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 18:15:31.266  4851  4851 W Binder_3: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[31350]" dev="sockfs" ino=31350 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 18:15:31.267  5580  5651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-28 18:15:31.267  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-28 18:15:31.267  5580  5628 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 18:15:31.268  5580  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-28 18:15:31.272  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.272  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-28 18:15:31.273  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 18:15:31.273  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 18:15:31.273  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 4
11-28 18:15:31.275  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.275  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.275  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-28 18:15:31.275  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-28 18:15:31.275  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 18:15:31.275  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-28 18:15:31.275  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 18:15:31.275  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 18:15:31.275  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.275  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-28 18:15:31.275  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 18:15:31.275  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.276  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.276  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.276  5580  5628 D BluetoothAdapter: STATE_ON
11-28 18:15:31.279  4633  4653 D BtGatt.GattService: registerClient() - UUID=afbc01ac-3f9e-4d6c-a2e5-4a4948728953
11-28 18:15:31.279  4633  4703 D BtGatt.GattService: onClientRegistered() - UUID=afbc01ac-3f9e-4d6c-a2e5-4a4948728953, clientIf=5
11-28 18:15:31.280  5580  5591 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-28 18:15:31.280  4633  4705 D BtGatt.AdvertiseManager: message : 0
11-28 18:15:31.282  4633  4705 D BtGatt.AdvertiseManager: starting multi advertising
11-28 18:15:31.291  4633  4703 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
11-28 18:15:31.297  4633  4703 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-28 18:15:31.297  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.297  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.297  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-28 18:15:31.297  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.297  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.298  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.298  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.298  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.298  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-28 18:15:31.299  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 18:15:31.299  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.300  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.300  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.300  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.300  5580  5628 I io.jxcore.node.ConnectionHelper: start: OK
11-28 18:15:31.300  5580  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-28 18:15:31.301  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.301  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-28 18:15:31.301  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-28 18:15:31.301  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.301  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.301  5580  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 18:15:31.301  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.301  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-28 18:15:31.301  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 18:15:31.301  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.301  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.301  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.302  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.302  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.304  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.304  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-28 18:15:31.304  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.304  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.304  5580  5580 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-28 18:15:31.801  5580  5644 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,11-28 18:15:31.802  5580  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:15:31.802  5580  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-28 18:15:31.802  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-28 18:15:31.803  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-28 18:15:31.803  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-28 18:15:31.803  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-28 18:15:31.803  5580  5651 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-28 18:15:31.804  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-28 18:15:31.804  5580  5651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-28 18:15:31.804  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-28 18:15:31.804  5580  5651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-28 18:15:31.804  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-28 18:15:31.805  5580  5580 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-28 18:15:31.806  5580  5580 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-28 18:15:31.806  5580  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-28 18:15:31.806  5580  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:15:31.808  5580  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80153db removed from the list
11-28 18:15:31.808  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:15:31.808  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-28 18:15:31.808  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.808  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 18:15:31.808  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 18:15:31.809  5580  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 134
11-28 18:15:31.809  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.809  5580  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-28 18:15:31.809  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:31.809  5580  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 134)
11-28 18:15:31.809  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.809  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.810  4633  4849 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: 1
11-28 18:15:31.810  5580  5652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 134)
,11-28 18:15:31.810  5580  5650 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
11-28 18:15:31.810  5580  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-28 18:15:31.810  5580  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 134)
11-28 18:15:31.811  5580  5628 D BluetoothAdapter: STATE_ON
,11-28 18:15:31.811  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-28 18:15:31.814  5580  5628 D BluetoothAdapter: STATE_ON
11-28 18:15:31.814  5580  5628 D BluetoothLeScanner: could not find callback wrapper
11-28 18:15:31.814  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-28 18:15:31.815  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.815  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:31.815  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.815  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-28 18:15:31.816  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.818  4633  4705 D BtGatt.AdvertiseManager: message : 1
11-28 18:15:31.820  4633  4705 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-28 18:15:31.831  4633  4703 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-28 18:15:31.831  4633  4703 D BtGatt.GattService: Client app is not null!
,11-28 18:15:31.833  4633  4851 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-28 18:15:31.834  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-28 18:15:31.834  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:31.834  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-28 18:15:31.834  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.834  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.834  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.834  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-28 18:15:31.835  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-28 18:15:31.835  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 18:15:31.836  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:31.838  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.838  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 18:15:31.838  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.838  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:31.838  5580  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67f9e78 removed from the list
11-28 18:15:31.838  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 18:15:31.838  5580  5628 D io.jxcore.node.ConnectivityMonitor: stop
11-28 18:15:31.838  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-28 18:15:31.838  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 18:15:31.839  5580  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-28 18:15:31.839  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.839  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 18:15:31.839  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-28 18:15:31.839  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.839  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-28 18:15:31.839  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.840  5580  5580 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 18:15:31.840  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.840  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.842  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 18:15:31.843  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-28 18:15:31.843  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-28 18:15:32.342  5580  5580 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-28 18:15:36.385  4633  4834 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-28 18:15:36.385  4633  4834 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 7
,11-28 18:15:36.840  5580  5645 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,11-28 18:15:36.843  5580  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-28 18:15:36.845  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-28 18:15:36.845  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 18:15:36.846  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-28 18:15:36.852  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-28 18:15:36.853  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-28 18:15:36.853  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-28 18:15:36.856  4652  4652 W Binder_1: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[31360]" dev="sockfs" ino=31360 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 18:15:36.860  4652  4652 W Binder_1: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[31360]" dev="sockfs" ino=31360 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 18:15:36.854  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-28 18:15:36.854  5580  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-28 18:15:36.854  5580  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-28 18:15:36.854  5580  5580 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-28 18:15:36.854  5580  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-28 18:15:36.856  5580  5653 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 18:15:36.856  5580  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
11-28 18:15:36.858  5580  5628 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-28 18:15:36.858  5580  5628 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-28 18:15:36.859  5580  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-28 18:15:36.859  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 18:15:36.859  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 18:15:36.861  5580  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-28 18:15:36.866  5580  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,11-28 18:15:36.875  5580  5628 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-28 18:15:36.876  5580  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:15:36.876  5580  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-28 18:15:36.876  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-28 18:15:36.876  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-28 18:15:36.876  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-28 18:15:36.876  5580  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-28 18:15:36.876  5580  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-28 18:15:36.877  5580  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-28 18:15:36.877  5580  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-28 18:15:36.878  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-28 18:15:36.878  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-28 18:15:36.878  5580  5628 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80153db not in the list
11-28 18:15:36.878  5580  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:15:36.878  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 18:15:36.878  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-28 18:15:36.878  5580  5580 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-28 18:15:36.878  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:36.878  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 18:15:36.879  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 18:15:36.879  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:36.881  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:36.881  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 18:15:36.881  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:36.881  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:36.882  5580  5628 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67f9e78 not in the list
11-28 18:15:36.882  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-28 18:15:36.882  5580  5628 D io.jxcore.node.ConnectivityMonitor: stop
11-28 18:15:36.882  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 18:15:36.882  5580  5580 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-28 18:15:36.883  5580  5628 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,11-28 18:15:36.884  5580  5628 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-28 18:15:36.884  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-28 18:15:36.884  5580  5628 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,11-28 18:15:36.884  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-28 18:15:36.884  5580  5628 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-28 18:15:36.884  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-28 18:15:36.885  5580  5628 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,11-28 18:15:36.886  5580  5628 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
11-28 18:15:36.888  5580  5628 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
11-28 18:15:36.888  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-28 18:15:36.888  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,11-28 18:15:36.889  5580  5628 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-28 18:15:36.889  5580  5628 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-28 18:15:36.889  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-28 18:15:36.889  5580  5628 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-28 18:15:36.889  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-28 18:15:36.889  5580  5628 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-28 18:15:36.889  5580  5628 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-28 18:15:36.890  5580  5628 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-28 18:15:36.890  5580  5628 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,11-28 18:15:36.890  5580  5628 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-28 18:15:36.891  5580  5628 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
11-28 18:15:36.891  5580  5628 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-28 18:15:36.892  5580  5628 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,11-28 18:15:36.892  5580  5628 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-28 18:15:36.892  5580  5628 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-28 18:15:36.892  5580  5628 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
11-28 18:15:36.893  5580  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-28 18:15:36.893  5580  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27b8866 added. We now have 3 listener(s)
11-28 18:15:36.895  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 18:15:36.895  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-28 18:15:36.895  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 18:15:36.896  5580  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 18:15:36.896  5580  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70c57a7 added. We now have 3 listener(s)
11-28 18:15:36.896  5580  5628 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 18:15:36.896  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-28 18:15:36.899  5580  5628 D BluetoothAdapter: enable(): BT is already enabled..!
,11-28 18:15:36.900   928  3146 D WifiService: setWifiEnabled: true pid=5580, uid=10077
11-28 18:15:36.900   928  3146 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-28 18:15:36.901  5580  5628 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-28 18:15:36.904  5580  5628 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-28 18:15:36.905  5580  5628 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
11-28 18:15:36.906  5580  5628 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-28 18:15:36.911  4633  4699 D BluetoothAdapterState: Current state: ON, message: 23
11-28 18:15:36.911  4633  4699 D BluetoothAdapterProperties: Setting state to 13
11-28 18:15:36.911  4633  4699 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-28 18:15:36.911  4633  4699 D BluetoothAdapterProperties: onBluetoothDisable()
11-28 18:15:36.912  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,11-28 18:15:36.912  5580  5628 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 18:15:36.912  5580  5628 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 18:15:36.912  5580  5628 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
11-28 18:15:36.912  5580  5628 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 18:15:36.912  5580  5628 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 18:15:36.912  5580  5628 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 18:15:36.912  5580  5628 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 18:15:36.912  5580  5628 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 18:15:36.912  5580  5628 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-28 18:15:36.913  4633  4699 I BluetoothAdapterState: Entering PendingCommandState
,11-28 18:15:36.913  5580  5628 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 18:15:36.914  5580  5628 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-28 18:15:36.918  4633  4633 D BluetoothMapService: onReceive
11-28 18:15:36.918  4633  4633 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-28 18:15:36.918  4633  4633 D BluetoothMapService: STATE_TURNING_OFF
11-28 18:15:36.918  4633  4633 D BluetoothMapService: MAP Service closeService in
11-28 18:15:36.918  4633  4633 D BluetoothMapMasInstance0: MAP Service shutdown
11-28 18:15:36.918  4633  4633 D ObexServerSockets0: shutdown(block = true)
11-28 18:15:36.919  4633  4633 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-28 18:15:36.919  4633  4860 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-28 18:15:36.919  4633  4633 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-28 18:15:36.919  4633  4861 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-28 18:15:36.919  4633  4849 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-28 18:15:36.920  4633  4633 I BtOppRfcommListener: stopping Accept Thread
11-28 18:15:36.921  4633  5269 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-28 18:15:36.921  4633  5269 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-28 18:15:36.932   928   941 I ActivityManager: Start proc 5656:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-28 18:15:36.933  4633  4703 D BluetoothAdapterProperties: Scan Mode:20
11-28 18:15:36.933  4633  4699 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-28 18:15:36.938  4633  4633 D HeadsetService: Received stop request...Stopping profile...
,11-28 18:15:36.940   928   928 D BluetoothHeadset: Proxy object disconnected
,11-28 18:15:36.941  3131  3972 D BluetoothHeadset: Proxy object disconnected
,11-28 18:15:36.941   928   928 D BluetoothHeadset: Proxy object disconnected
,11-28 18:15:36.941  3131  3131 D HeadsetProfile: Bluetooth service disconnected
11-28 18:15:36.941  3770  3989 D BluetoothHeadset: Proxy object disconnected
11-28 18:15:36.942   928   928 D BluetoothHeadset: Proxy object disconnected
,11-28 18:15:36.944  4633  4633 D A2dpService: Received stop request...Stopping profile...
,11-28 18:15:36.946  4633  4854 D A2dpStateMachine: Exit Disconnected: -1
11-28 18:15:36.948   928   928 D BluetoothA2dp: Proxy object disconnected
11-28 18:15:36.949  3131  3131 D BluetoothA2dp: Proxy object disconnected
11-28 18:15:36.949  4633  4633 D HidService: Received stop request...Stopping profile...
11-28 18:15:36.949  4633  4633 D HidService: Stopping Bluetooth HidService
,11-28 18:15:36.950  3131  3131 D BluetoothInputDevice: Proxy object disconnected
11-28 18:15:36.950  3131  3131 D HidProfile: Bluetooth service disconnected
11-28 18:15:36.950  4633  4633 V BluetoothAdapterState: isTurningOff()=true
11-28 18:15:36.951  4633  4633 V BluetoothAdapterState: isTurningOn()=false
,11-28 18:15:36.951  4633  4633 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:15:36.951  4633  4633 V BluetoothAdapterState: isBleTurningOff()=false
,11-28 18:15:36.951  4633  4633 D HealthService: Received stop request...Stopping profile...
,11-28 18:15:36.954  4633  4633 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-28 18:15:36.954  4633  4633 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-28 18:15:36.954  4633  4834 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 18:15:36.954  4633  4834 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 18:15:36.954  4633  4834 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 18:15:36.955  4633  4633 D PanService: Received stop request...Stopping profile...
11-28 18:15:36.955  4633  4703 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-28 18:15:36.955  4633  4703 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-28 18:15:36.956  3131  3131 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-28 18:15:36.956  3131  3131 D PanProfile: Bluetooth service disconnected
11-28 18:15:36.956  4633  4633 D BluetoothMapService: Received stop request...Stopping profile...
11-28 18:15:36.957  4633  4633 D BluetoothMapService: stop()
,11-28 18:15:36.957  4633  4633 D BluetoothMapAppObserver: deinitObservers()
11-28 18:15:36.957  4633  4633 D BluetoothMapAppObserver: removeReceiver()
,11-28 18:15:36.960   928  3847 I ActivityManager: Killing 5378:com.android.chrome/u0a39 (adj 15): empty #17
,11-28 18:15:36.978  3131  3131 D BluetoothMap: Proxy object disconnected
,11-28 18:15:36.978  3131  3131 D MapProfile: Bluetooth service disconnected
,11-28 18:15:36.978  4633  4633 D SapService: Received stop request...Stopping profile...
11-28 18:15:36.978  4633  4633 V SapService: stop()
,11-28 18:15:36.980  4633  4633 V BluetoothAdapterState: isTurningOff()=true
11-28 18:15:36.980  4633  4633 V BluetoothAdapterState: isTurningOn()=false
11-28 18:15:36.980  4633  4633 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:15:36.980  4633  4633 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:15:36.981  4633  4834 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-28 18:15:36.981  4633  4834 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 18:15:36.981  4633  4633 V BluetoothAdapterState: isTurningOff()=true
11-28 18:15:36.981  4633  4633 V BluetoothAdapterState: isTurningOn()=false
11-28 18:15:36.981  4633  4633 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:15:36.981  4633  4633 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:15:36.982  4633  4633 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-28 18:15:36.982  4633  4633 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-28 18:15:36.982  4633  4834 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-28 18:15:36.982  4633  4834 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-28 18:15:36.982  4633  4834 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-28 18:15:36.982  4633  4633 V BluetoothAdapterState: isTurningOff()=true
11-28 18:15:36.982  4633  4834 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-28 18:15:36.982  4633  4633 V BluetoothAdapterState: isTurningOn()=false
11-28 18:15:36.982  4633  4633 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:15:36.982  4633  4633 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:15:36.982  4633  4633 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-28 18:15:36.982  4633  4703 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-28 18:15:36.982  4633  4703 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-28 18:15:36.983  4633  4633 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-28 18:15:36.983  4633  4703 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,11-28 18:15:36.984  4633  4633 V BluetoothAdapterState: isTurningOff()=true
,11-28 18:15:36.984  4633  4633 V BluetoothAdapterState: isTurningOn()=false
11-28 18:15:36.984  4633  4633 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:15:36.984  4633  4633 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:15:36.984  4633  4633 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-28 18:15:36.984  4633  4633 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,11-28 18:15:36.985  4633  4633 D BluetoothMapService: MAP Service closeService in
,11-28 18:15:36.985  4633  4633 V BluetoothAdapterState: isTurningOff()=true
11-28 18:15:36.985  4633  4633 V BluetoothAdapterState: isTurningOn()=false
11-28 18:15:36.985  4633  4633 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:15:36.985  4633  4633 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:15:36.986  4633  4633 D BluetoothMapService: cleanup()
11-28 18:15:36.986  4633  4633 D BluetoothMapService: MAP Service closeService in
11-28 18:15:36.986  4633  4633 V BluetoothAdapterState: isTurningOff()=true
11-28 18:15:36.986  4633  4633 V BluetoothAdapterState: isTurningOn()=false
11-28 18:15:36.986  4633  4633 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:15:36.986  4633  4633 V BluetoothAdapterState: isBleTurningOff()=false
,11-28 18:15:36.986  4633  4699 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-28 18:15:36.986  4633  4699 D BluetoothAdapterProperties: Setting state to 15
11-28 18:15:36.986  4633  4699 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-28 18:15:36.987   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 18:15:36.987   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 18:15:36.987  3131  3143 D BluetoothPbap: onBluetoothStateChange: up=false
11-28 18:15:36.988  3770  3968 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 18:15:36.989   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 18:15:36.989  3131  5579 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-28 18:15:36.989  3131  3972 D BluetoothA2dp: onBluetoothStateChange: up=false
11-28 18:15:36.990  3131  3145 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-28 18:15:36.990   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
11-28 18:15:36.991  3131  3143 D BluetoothMap: onBluetoothStateChange: up=false
11-28 18:15:36.991  3131  5579 D BluetoothPan: onBluetoothStateChange on: false
11-28 18:15:36.991  4633  4699 I BluetoothAdapterState: Entering BleOnState
11-28 18:15:36.992  4633  4699 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-28 18:15:36.992  4633  4699 D BluetoothAdapterProperties: Setting state to 16
11-28 18:15:36.992  4633  4699 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-28 18:15:36.994  4633  4699 D BluetoothAdapterProperties: onBleDisable
11-28 18:15:36.994  4633  4699 I BluetoothAdapterState: Entering PendingCommandState
11-28 18:15:36.994  4633  4700 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-28 18:15:36.995  4633  4703 D BluetoothAdapterProperties: Scan Mode:20
11-28 18:15:36.995  4633  4834 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-28 18:15:36.996  4633  4834 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 18:15:36.996  5656  5656 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-28 18:15:37.009  5656  5656 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-28 18:15:37.016   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@175a0e0:true
11-28 18:15:37.017  3571  3571 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-28 18:15:37.030   928  3406 I ActivityManager: Start proc 5668:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-28 18:15:37.044  5656  5656 D LocalBluetoothProfileManager: Adding local MAP profile
,11-28 18:15:37.047  5656  5656 D BluetoothMap: Create BluetoothMap proxy object
,11-28 18:15:37.060  5656  5656 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-28 18:15:37.068  5668  5668 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-28 18:15:37.073  5656  5656 D DockEventReceiver: finishStartingService: stopping service
,11-28 18:15:37.081   928  3843 I ActivityManager: Killing 4465:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-28 18:15:37.202  4633  4703 I bt_hci  : shut_down
,11-28 18:15:37.207  4633  4707 D bt_hwcfg: hw_epilog_process
,11-28 18:15:37.207  4633  4707 I bt_vendor: low_power_mode_cb
,11-28 18:15:37.209  4633  4707 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-28 18:15:37.209  4633  4707 I bt_vendor: epilog_cb
11-28 18:15:37.209  4633  4707 I bt_hci  : epilog_finished_callback
,11-28 18:15:37.211  4633  4703 I bt_hci_h4: hal_close
,11-28 18:15:37.212  4633  4703 I bt_userial_vendor: device fd = 54 close
,11-28 18:15:37.274  5668  5668 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 18:15:37.274  5668  5668 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 18:15:37.274  5668  5668 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-28 18:15:37.274  5668  5668 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-28 18:15:37.274  5668  5668 D StrictMode: 	at java.io.File.exists(File.java:361)
11-28 18:15:37.274  5668  5668 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-28 18:15:37.274  5668  5668 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-28 18:15:37.274  5668  5668 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-28 18:15:37.274  5668  5668 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-28 18:15:37.274  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-28 18:15:37.274  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-28 18:15:37.274  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 18:15:37.274  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 18:15:37.274  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-28 18:15:37.274  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 18:15:37.274  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 18:15:37.274  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 18:15:37.274  5668  5668 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 18:15:37.274  5668  5668 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 18:15:37.274  5668  5668 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 18:15:37.274  5668  5668 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 18:15:37.274  5668  5668 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 18:15:37.274  5668  5668 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 18:15:37.274  5668  5668 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 18:15:37.274  5668  5668 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 18:15:37.274  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 18:15:37.274  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-28 18:15:37.275  5668  5668 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 18:15:37.275  5668  5668 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 18:15:37.275  5668  5668 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.r.e.b(PG:170)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 18:15:37.275  5668  5668 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.r.k.d(PG:583)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.r.e.b(PG:170)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 18:15:37.275  5668  5668 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at java.io.File.exists(File.java:361)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 18:15:37.275  5668  5668 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at java.io.File.exists(File.java:361)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 18:15:37.275  5668  5668 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 18:15:37.275  5668  5668 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 18:15:37.293  5656  5656 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-28 18:15:37.298  3571  3571 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-28 18:15:37.308  5656  5656 D DockEventReceiver: finishStartingService: stopping service
11-28 18:15:37.309   928  3406 I ActivityManager: Killing 5411:com.qualcomm.timeservice/1000 (adj 15): empty #17
,11-28 18:15:37.341  4633  4700 D bt_stack_manager: event_shut_down_stack finished.
11-28 18:15:37.341  4633  4699 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-28 18:15:37.342  4633  4699 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-28 18:15:37.342  4633  4633 D BtGatt.DebugUtils: handleDebugAction() action=null
11-28 18:15:37.343  4633  4633 D BtGatt.GattService: Received stop request...Stopping profile...
11-28 18:15:37.343  4633  4633 D BtGatt.GattService: stop()
11-28 18:15:37.343  4633  4633 D BtGatt.AdvertiseManager: advertise clients cleared
11-28 18:15:37.344  4633  4633 V BluetoothAdapterState: isTurningOff()=false
11-28 18:15:37.344  4633  4633 V BluetoothAdapterState: isTurningOn()=false
11-28 18:15:37.344  4633  4633 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:15:37.344  4633  4633 V BluetoothAdapterState: isBleTurningOff()=true
11-28 18:15:37.344  4633  4699 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-28 18:15:37.345  4633  4699 D BluetoothAdapterProperties: Setting state to 10
11-28 18:15:37.345  4633  4699 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-28 18:15:37.345  4633  4699 I BluetoothAdapterState: Entering OffState
11-28 18:15:37.346   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,11-28 18:15:37.352  4633  4633 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-28 18:15:37.352  4633  4633 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-28 18:15:37.352  4633  4633 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-28 18:15:37.354  4633  4700 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-28 18:15:37.356  4633  4633 I art     : System.exit called, status: 0
,11-28 18:15:37.357  4633  4633 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-28 18:15:37.383  5580  5580 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-28 18:15:37.411   928  3407 I ActivityManager: Process com.android.bluetooth (pid 4633) has died
,11-28 18:15:37.413  5580  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-28 18:15:37.414  5580  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 18:15:37.414  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 18:15:37.414  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
11-28 18:15:37.414  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 18:15:37.414  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-28 18:15:37.414  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 18:15:37.414  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 18:15:37.414  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 18:15:37.414  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-28 18:15:37.414  5580  5654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 18:15:37.414  5580  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-28 18:15:37.418  5580  5628 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 18:15:37.429   928   945 I ActivityManager: Start proc 5701:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-28 18:15:37.456  5668  5700 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,11-28 18:15:37.483  5701  5701 D AdapterServiceConfig: Adding HeadsetService
,11-28 18:15:37.483  5701  5701 D AdapterServiceConfig: Adding A2dpService
11-28 18:15:37.483  5701  5701 D AdapterServiceConfig: Adding HidService
11-28 18:15:37.483  5701  5701 D AdapterServiceConfig: Adding HealthService
11-28 18:15:37.483  5701  5701 D AdapterServiceConfig: Adding PanService
11-28 18:15:37.484  5701  5701 D AdapterServiceConfig: Adding GattService
,11-28 18:15:37.484  5701  5701 D AdapterServiceConfig: Adding BluetoothMapService
11-28 18:15:37.484  5701  5701 D AdapterServiceConfig: Adding SapService
,11-28 18:15:37.492   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ef329d4:true
,11-28 18:15:37.493  5701  5701 D BluetoothAdapterState: make() - Creating AdapterState
,11-28 18:15:37.495  5701  5701 I bt_bluedroid: init
,11-28 18:15:37.495  5701  5714 I BluetoothAdapterState: Entering OffState
,11-28 18:15:37.497  5701  5715 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-28 18:15:37.497  5701  5715 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-28 18:15:37.497  5701  5715 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-28 18:15:37.497  5701  5715 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-28 18:15:37.498  5701  5701 I bt_bluedroid: get_profile_interface socket
,11-28 18:15:37.499  5701  5718 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-28 18:15:37.500  5701  5701 I bt_bluedroid: get_profile_interface sdp
11-28 18:15:37.500  5701  5718 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-28 18:15:37.505  5701  5712 I bt_bluedroid: config_hci_snoop_log
,11-28 18:15:37.506   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,11-28 18:15:37.510  5701  5714 D BluetoothAdapterState: Current state: OFF, message: 0
,11-28 18:15:37.510  5701  5714 D BluetoothAdapterProperties: Setting state to 14
,11-28 18:15:37.511  5701  5714 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-28 18:15:37.512  5701  5714 D BluetoothBondStateMachine: make
11-28 18:15:37.513  5701  5719 I BluetoothBondStateMachine: StableState(): Entering Off State
11-28 18:15:37.516  5701  5714 I BluetoothAdapterState: Entering PendingCommandState
,11-28 18:15:37.517  5701  5701 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-28 18:15:37.519  5701  5701 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8a18a27
,11-28 18:15:37.520  5701  5701 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-28 18:15:37.520  5701  5701 D BtGatt.GattService: Received start request. Starting profile...
11-28 18:15:37.521  5701  5701 D BtGatt.GattService: start()
11-28 18:15:37.521  5701  5701 I bt_bluedroid: get_profile_interface gatt
,11-28 18:15:37.522  5701  5701 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8a18a27
11-28 18:15:37.522  5701  5701 D BtGatt.AdvertiseManager: advertise manager created
,11-28 18:15:37.527  5701  5701 V BluetoothAdapterState: isTurningOff()=false
11-28 18:15:37.527  5701  5701 V BluetoothAdapterState: isTurningOn()=false
,11-28 18:15:37.527  5701  5701 V BluetoothAdapterState: isBleTurningOn()=true
11-28 18:15:37.527  5701  5701 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:15:37.527  5701  5714 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-28 18:15:37.528  5701  5714 I bt_bluedroid: bt_bluedroid
11-28 18:15:37.528  5701  5715 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-28 18:15:37.529  5701  5715 I bt_hci  : start_up
,11-28 18:15:37.534  5701  5715 I bt_vendor: alloc value 0xf3e91871
,11-28 18:15:37.534  5701  5715 I bt_vendor: init
11-28 18:15:37.534  5701  5715 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-28 18:15:37.534  5701  5715 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-28 18:15:37.537  5668  5688 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-28 18:15:37.545   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@62f3935:true
,11-28 18:15:37.643  5701  5715 D bt_hci  : start_up starting async portion
,11-28 18:15:37.643  5701  5722 I bt_hci  : event_finish_startup
11-28 18:15:37.643  5701  5722 I bt_hci_h4: hal_open
11-28 18:15:37.643  5701  5722 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-28 18:15:37.645  5701  5722 I bt_userial_vendor: device fd = 54 open
,11-28 18:15:37.643  5726  5726 W irq/448-msm_hs_: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-28 18:15:37.657  5701  5722 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-28 18:15:37.659  5701  5722 D bt_hwcfg: Chipset BCM4358A3
,11-28 18:15:37.659  5701  5722 D bt_hwcfg: Target name = [BCM4358A3]
11-28 18:15:37.659  5701  5722 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-28 18:15:37.917  5701  5714 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-28 18:15:37.922  3571  5730 V NQFileLogger: [132] e.a: about to write to file
,11-28 18:15:37.926  3571  5730 V ProcessReports: [132] ProcessReportsService.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
,11-28 18:15:37.982  5701  5722 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-28 18:15:37.982  5701  5722 D bt_hwcfg: Settlement delay -- 100 ms
11-28 18:15:37.982  5701  5722 I bt_hwcfg: Setting fw settlement delay to 100 
,11-28 18:15:38.106  5701  5722 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-28 18:15:38.106  5701  5722 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-28 18:15:38.108  5701  5722 I bt_hwcfg: vendor lib fwcfg completed
11-28 18:15:38.109  5701  5722 I bt_vendor: firmware callback
11-28 18:15:38.109  5701  5722 I bt_hci  : firmware_config_callback
,11-28 18:15:38.118  5701  5732 I bt_btu  : btu_task pending for preload complete event
,11-28 18:15:38.118  5701  5732 I bt_btu_task: Bluetooth chip preload is complete
11-28 18:15:38.118  5701  5732 I bt_btu  : btu_task received preload complete event
,11-28 18:15:38.124  5701  5732 I         : BTE_InitTraceLevels -- TRC_HCI
,11-28 18:15:38.124  5701  5732 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-28 18:15:38.124  5701  5732 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-28 18:15:38.124  5701  5732 I         : BTE_InitTraceLevels -- TRC_AVDT
11-28 18:15:38.125  5701  5732 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-28 18:15:38.125  5701  5732 I         : BTE_InitTraceLevels -- TRC_A2D
11-28 18:15:38.125  5701  5732 I         : BTE_InitTraceLevels -- TRC_BNEP
11-28 18:15:38.125  5701  5732 I         : BTE_InitTraceLevels -- TRC_BTM
11-28 18:15:38.125  5701  5732 I         : BTE_InitTraceLevels -- TRC_GAP
11-28 18:15:38.125  5701  5732 I         : BTE_InitTraceLevels -- TRC_PAN
11-28 18:15:38.125  5701  5732 I         : BTE_InitTraceLevels -- TRC_SDP
,11-28 18:15:38.125  5701  5732 I         : BTE_InitTraceLevels -- TRC_GATT
11-28 18:15:38.125  5701  5732 I         : BTE_InitTraceLevels -- TRC_SMP
11-28 18:15:38.125  5701  5732 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-28 18:15:38.125  5701  5732 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-28 18:15:38.209  5701  5732 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3e0f549
11-28 18:15:38.209  5701  5732 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3e0f549 
,11-28 18:15:38.221  5701  5718 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-28 18:15:38.222  5701  5718 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-28 18:15:38.223  5701  5718 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-28 18:15:38.225  5701  5718 D BluetoothAdapterProperties: Name is: Nexus 6P
11-28 18:15:38.228  5701  5718 D BluetoothAdapterProperties: Scan Mode:20
11-28 18:15:38.228  5701  5718 D BluetoothAdapterProperties: Discoverable Timeout:120
11-28 18:15:38.228  5701  5718 D bt_hci  : do_postload posting postload work item
11-28 18:15:38.229  5701  5722 I bt_hci  : event_postload
11-28 18:15:38.229  5701  5722 I bt_vendor: sco_config_cb
11-28 18:15:38.229  5701  5722 I bt_hci  : sco_config_callback postload finished.
,11-28 18:15:38.232  5701  5718 D bt_bte_conf: Device ID record 1 : primary
11-28 18:15:38.232  5701  5718 D bt_bte_conf:   vendorId            = 000f
11-28 18:15:38.232  5701  5718 D bt_bte_conf:   vendorIdSource      = 0001
11-28 18:15:38.232  5701  5718 D bt_bte_conf:   product             = 1200
11-28 18:15:38.232  5701  5718 D bt_bte_conf:   version             = 1436
11-28 18:15:38.232  5701  5718 D bt_bte_conf:   clientExecutableURL = 
,11-28 18:15:38.232  5701  5718 D bt_bte_conf:   serviceDescription  = 
11-28 18:15:38.232  5701  5718 D bt_bte_conf:   documentationURL    = 
11-28 18:15:38.233  5701  5718 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-28 18:15:38.233  5701  5715 D bt_stack_manager: event_start_up_stack finished
11-28 18:15:38.234  5701  5714 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-28 18:15:38.234  5701  5714 D BluetoothAdapterProperties: Setting state to 15
11-28 18:15:38.234  5701  5714 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-28 18:15:38.235  5701  5714 I BluetoothAdapterState: Entering BleOnState
,11-28 18:15:38.237  5701  5722 I bt_vendor: low_power_mode_cb
11-28 18:15:38.241  5701  5714 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-28 18:15:38.241  5701  5714 D BluetoothAdapterProperties: Setting state to 11
11-28 18:15:38.241  5701  5714 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-28 18:15:38.250  5701  5701 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8a18a27
11-28 18:15:38.251  5701  5701 D HeadsetService: Received start request. Starting profile...
11-28 18:15:38.254  5701  5701 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-28 18:15:38.254  5701  5701 D HeadsetStateMachine: make
11-28 18:15:38.266  5701  5714 I BluetoothAdapterState: Entering PendingCommandState
11-28 18:15:38.270  5701  5701 D HeadsetStateMachine: max_hf_connections = 1
11-28 18:15:38.270  5701  5701 I bt_bluedroid: get_profile_interface handsfree
11-28 18:15:38.270  5701  5718 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-28 18:15:38.271  5701  5718 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-28 18:15:38.274  5701  5701 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8a18a27
11-28 18:15:38.275  5701  5701 D A2dpService: Received start request. Starting profile...
11-28 18:15:38.275  5701  5701 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-28 18:15:38.276  5701  5701 I bt_bluedroid: get_profile_interface avrcp
,11-28 18:15:38.283  5701  5701 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-28 18:15:38.283  5701  5701 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-28 18:15:38.283  5701  5701 D A2dpStateMachine: make
11-28 18:15:38.284  5701  5701 I bt_bluedroid: get_profile_interface a2dp
11-28 18:15:38.285  5701  5718 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-28 18:15:38.286  5701  5739 D A2dpStateMachine: Enter Disconnected: -2
,11-28 18:15:38.287  5701  5701 I BluetoothHidServiceJni: classInitNative: succeeds
,11-28 18:15:38.289  5701  5701 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8a18a27
,11-28 18:15:38.291  5656  5656 D BluetoothInputDevice: Proxy object connected
,11-28 18:15:38.291  5656  5656 D HidProfile: Bluetooth service connected
11-28 18:15:38.292  5701  5701 D HidService: Received start request. Starting profile...
11-28 18:15:38.292  5701  5701 I bt_bluedroid: get_profile_interface hidhost
11-28 18:15:38.292  5701  5718 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3df056d
11-28 18:15:38.292  5701  5701 D HidService: setHidService(): set to: null
11-28 18:15:38.292  5701  5718 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-28 18:15:38.293  5701  5701 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-28 18:15:38.294  5701  5701 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8a18a27
,11-28 18:15:38.294  5701  5701 D HealthService: Received start request. Starting profile...
,11-28 18:15:38.295  5701  5701 I bt_bluedroid: get_profile_interface health
11-28 18:15:38.296  5701  5701 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-28 18:15:38.297  5701  5701 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8a18a27
,11-28 18:15:38.298  5656  5656 D BluetoothPan: BluetoothPAN Proxy object connected
11-28 18:15:38.298  5701  5701 D PanService: Received start request. Starting profile...
11-28 18:15:38.298  5656  5656 D PanProfile: Bluetooth service connected
11-28 18:15:38.299  5701  5701 D BluetoothPanServiceJni: initializeNative(L110): pan
11-28 18:15:38.299  5701  5701 I bt_bluedroid: get_profile_interface pan
,11-28 18:15:38.299  5701  5718 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-28 18:15:38.302  5701  5701 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8a18a27
,11-28 18:15:38.303  3571  3571 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-28 18:15:38.305  5701  5701 D BluetoothMapService: Received start request. Starting profile...
,11-28 18:15:38.305  5701  5701 D BluetoothMapService: start()
,11-28 18:15:38.308  5701  5701 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-28 18:15:38.309  5701  5701 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-28 18:15:38.309  5701  5701 D BluetoothMapAppObserver: createReceiver()
11-28 18:15:38.310  5701  5701 D BluetoothMapAppObserver: initObservers()
11-28 18:15:38.310  5701  5701 D BluetoothMapAppObserver: getEnabledAccountItems()
11-28 18:15:38.313  5656  5656 D BluetoothMap: Proxy object connected
11-28 18:15:38.314  5656  5656 D MapProfile: Bluetooth service connected
11-28 18:15:38.314  5656  5656 D BluetoothMap: getConnectedDevices()
11-28 18:15:38.315  5656  5656 D BluetoothMap: Bluetooth is Not enabled
,11-28 18:15:38.318  5701  5701 V SapService: SapBinder()
,11-28 18:15:38.318  5701  5701 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8a18a27
11-28 18:15:38.319  5701  5701 D SapService: Received start request. Starting profile...
11-28 18:15:38.319  5701  5701 V SapService: start()
,11-28 18:15:38.320  5701  5701 V BluetoothAdapterState: isTurningOff()=false
,11-28 18:15:38.320  5701  5701 V BluetoothAdapterState: isTurningOn()=true
11-28 18:15:38.321  5701  5701 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:15:38.321  5701  5701 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:15:38.321  5701  5701 V BluetoothAdapterState: isTurningOff()=false
11-28 18:15:38.321  5701  5701 V BluetoothAdapterState: isTurningOn()=true
11-28 18:15:38.321  5701  5701 V BluetoothAdapterState: isBleTurningOn()=false
,11-28 18:15:38.321  5701  5737 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-28 18:15:38.321  5701  5701 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:15:38.321  5701  5701 V BluetoothAdapterState: isTurningOff()=false
11-28 18:15:38.321  5701  5701 V BluetoothAdapterState: isTurningOn()=true
11-28 18:15:38.322  5701  5701 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:15:38.322  5701  5701 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:15:38.322  5701  5701 V BluetoothAdapterState: isTurningOff()=false
11-28 18:15:38.322  5701  5701 V BluetoothAdapterState: isTurningOn()=true
11-28 18:15:38.322  5701  5701 V BluetoothAdapterState: isBleTurningOn()=false
,11-28 18:15:38.322  5701  5701 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:15:38.322  5701  5701 V BluetoothAdapterState: isTurningOff()=false
11-28 18:15:38.322  5701  5701 V BluetoothAdapterState: isTurningOn()=true
11-28 18:15:38.322  5701  5701 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:15:38.322  5701  5701 V BluetoothAdapterState: isBleTurningOff()=false
,11-28 18:15:38.323  5701  5701 V BluetoothAdapterState: isTurningOff()=false
11-28 18:15:38.323  5701  5701 V BluetoothAdapterState: isTurningOn()=true
11-28 18:15:38.323  5701  5701 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:15:38.323  5701  5701 V BluetoothAdapterState: isBleTurningOff()=false
,11-28 18:15:38.324  5701  5701 V BluetoothAdapterState: isTurningOff()=false
11-28 18:15:38.324  5701  5701 V BluetoothAdapterState: isTurningOn()=true
11-28 18:15:38.324  5701  5701 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:15:38.324  5701  5701 V BluetoothAdapterState: isBleTurningOff()=false
,11-28 18:15:38.325  5701  5714 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-28 18:15:38.325  5701  5714 D BluetoothAdapterProperties: ScanMode =  20
11-28 18:15:38.325  5701  5714 D BluetoothAdapterProperties: State =  11
11-28 18:15:38.325  5701  5714 D BluetoothAdapterProperties: Setting state to 12
11-28 18:15:38.325  5701  5714 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,11-28 18:15:38.327   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 18:15:38.327   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 18:15:38.327  5701  5714 I BluetoothAdapterState: Entering OnState
,11-28 18:15:38.327  3131  5579 D BluetoothPbap: onBluetoothStateChange: up=true
11-28 18:15:38.328  5701  5718 D BluetoothAdapterProperties: Scan Mode:21
11-28 18:15:38.329  5701  5718 D BluetoothAdapterProperties: Discoverable Timeout:120
11-28 18:15:38.329  3770  3783 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-28 18:15:38.329  5656  5666 D BluetoothPan: onBluetoothStateChange on: true
,11-28 18:15:38.330  5656  5667 D BluetoothPbap: onBluetoothStateChange: up=true
11-28 18:15:38.331   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 18:15:38.331  3131  3143 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-28 18:15:38.332  3131  3131 D BluetoothInputDevice: Proxy object connected
11-28 18:15:38.332  3131  3972 D BluetoothA2dp: onBluetoothStateChange: up=true
11-28 18:15:38.332  3131  3131 D HidProfile: Bluetooth service connected
11-28 18:15:38.334  3131  5579 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 18:15:38.334   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-28 18:15:38.334  5701  5701 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-28 18:15:38.335  5701  5701 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-28 18:15:38.335  3131  3143 D BluetoothMap: onBluetoothStateChange: up=true
11-28 18:15:38.336  5701  5701 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 18:15:38.337  3131  3131 D BluetoothMap: Proxy object connected
11-28 18:15:38.337  5656  5666 D BluetoothMap: onBluetoothStateChange: up=true
11-28 18:15:38.337  3131  3131 D MapProfile: Bluetooth service connected
11-28 18:15:38.337  3131  3131 D BluetoothMap: getConnectedDevices()
,11-28 18:15:38.337  5656  5667 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-28 18:15:38.337  3131  3972 D BluetoothPan: onBluetoothStateChange on: true
11-28 18:15:38.339  5701  5701 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 18:15:38.339  3131  3131 D BluetoothPan: BluetoothPAN Proxy object connected
11-28 18:15:38.339  3131  3131 D PanProfile: Bluetooth service connected
,11-28 18:15:38.341   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
11-28 18:15:38.342  5701  5701 D ObexServerSockets: Succeed to create listening sockets 
11-28 18:15:38.342  5701  5701 D ObexServerSockets0: startAccept()
11-28 18:15:38.342  5701  5701 D ObexServerSockets0: prepareForNewConnect()
11-28 18:15:38.342  5656  5656 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-28 18:15:38.344  5701  5701 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-28 18:15:38.344  5701  5701 D BluetoothSdpJni: SDP Create record success - handle: 0
11-28 18:15:38.344  5701  5745 D ObexServerSockets0: Accepting socket connection...
11-28 18:15:38.345  5701  5746 D ObexServerSockets0: Accepting socket connection...
11-28 18:15:38.345  5656  5656 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-28 18:15:38.346   928   928 D BluetoothA2dp: Proxy object connected
,11-28 18:15:38.346  5701  5701 D BluetoothMapService: onReceive
11-28 18:15:38.346  3131  3131 D BluetoothA2dp: Proxy object connected
11-28 18:15:38.346  5701  5701 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-28 18:15:38.346  5701  5701 D BluetoothMapService: STATE_ON
,11-28 18:15:38.352  5656  5656 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-28 18:15:38.352  5701  5748 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 18:15:38.355  5656  5656 D BluetoothA2dp: Proxy object connected
,11-28 18:15:38.356  5701  5748 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-28 18:15:38.356  5701  5748 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-28 18:15:38.360  3571  3571 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-28 18:15:38.360  5656  5656 D DockEventReceiver: finishStartingService: stopping service
,11-28 18:15:38.368  5656  5656 D BluetoothPbap: Proxy object connected
,11-28 18:15:38.369  3131  3131 D BluetoothPbap: Proxy object connected
11-28 18:15:38.369  3131  3131 D PbapServerProfile: Bluetooth service connected
11-28 18:15:38.370  5656  5656 D PbapServerProfile: Bluetooth service connected
,11-28 18:15:38.373  5701  5701 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-28 18:15:38.373  5701  5701 D ObexServerSockets0: prepareForNewConnect()
11-28 18:15:38.375  5701  5752 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-28 18:15:38.389  5701  5756 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-28 18:15:38.390  5701  5756 I BtOppRfcommListener: Accept thread started.
,11-28 18:15:38.421  5580  5654 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-28 18:15:38.421  5580  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 18:15:38.421  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 18:15:38.421  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 18:15:38.421  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 18:15:38.421  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 18:15:38.421  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 18:15:38.421  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 18:15:38.421  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 18:15:38.421  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-28 18:15:38.422  5580  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-28 18:15:38.423  5580  5628 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,11-28 18:15:38.424   928  3843 D WifiService: setWifiEnabled: false pid=5580, uid=10077
11-28 18:15:38.424   928  3843 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-28 18:15:38.426   928  2964 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-28 18:15:38.426   928  2964 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-28 18:15:38.426   928  2964 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-28 18:15:38.426   928  2964 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-28 18:15:38.427  5580  5628 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 18:15:38.428   928   928 D BluetoothHeadset: Proxy object connected
11-28 18:15:38.429  3131  3143 D BluetoothHeadset: Proxy object connected
11-28 18:15:38.429  3131  3131 D HeadsetProfile: Bluetooth service connected
11-28 18:15:38.429   928   928 D BluetoothHeadset: Proxy object connected
11-28 18:15:38.429  3770  3989 D BluetoothHeadset: Proxy object connected
,11-28 18:15:38.429   928   928 D BluetoothHeadset: Proxy object connected
11-28 18:15:38.430  3770  3783 D BluetoothHeadset: Proxy object connected
11-28 18:15:38.431   928   945 D BluetoothHeadset: Proxy object connected
,11-28 18:15:38.434   928  5337 D DhcpClient: Clearing IP address
11-28 18:15:38.434   506   925 D CommandListener: Clearing all IP addresses on wlan0
11-28 18:15:38.434  3131  3145 D BluetoothHeadset: Proxy object connected
11-28 18:15:38.434  3131  3131 D HeadsetProfile: Bluetooth service connected
,11-28 18:15:38.441   506   925 D CommandListener: Setting iface cfg
11-28 18:15:38.442  3571  5391 V NativeCrypto: Read error: ssl=0x7f7bd85000: I/O error during system call, Connection timed out
11-28 18:15:38.444  3571  5391 V NativeCrypto: SSL shutdown failed: ssl=0x7f7bd85000: I/O error during system call, Broken pipe
,11-28 18:15:38.445   928  3787 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,11-28 18:15:38.445   928  5335 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-28 18:15:38.447   928  5335 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-28 18:15:38.447   928  2966 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-28 18:15:38.447   928  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-28 18:15:38.448  5656  5666 D BluetoothHeadset: Proxy object connected
11-28 18:15:38.448   928  2966 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-28 18:15:38.452  5656  5656 D HeadsetProfile: Bluetooth service connected
,11-28 18:15:38.456   928  5338 D DhcpClient: Receive thread stopped
,11-28 18:15:38.459   928  2966 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-28 18:15:38.459   928  2966 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,11-28 18:15:38.462   928   928 D RttService: SCAN_AVAILABLE : 1
11-28 18:15:38.462   928  3073 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-28 18:15:38.464   533   533 E Parcel  : Reading a NULL string not supported here.
,11-28 18:15:38.468   928  2966 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-28 18:15:38.469  3732  3864 W QCNEJ   : |CORE| network lost: 100
,11-28 18:15:38.470  3732  3864 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-28 18:15:38.477   928  2964 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-28 18:15:38.492   506   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-28 18:15:38.493   928  2964 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-28 18:15:38.511   506   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-28 18:15:38.511   506   925 D CommandListener: Clearing all IP addresses on wlan0
11-28 18:15:38.512   506   925 D TetherController: Setting IP forward enable = 0
,11-28 18:15:38.513   928  2966 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,11-28 18:15:38.513   928  2966 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-28 18:15:38.514   928  2964 D DhcpClient: doQuit
11-28 18:15:38.515   928  2964 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-28 18:15:38.516  3439  3439 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-28 18:15:38.516   928   945 D Tethering: MasterInitialState.processMessage what=3
,11-28 18:15:38.518   928  5337 D DhcpClient: onQuitting
11-28 18:15:38.518  5223  5223 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@1d222e8 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-28 18:15:38.525  3953  3953 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-28 18:15:38.525  3934  3934 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-28 18:15:38.527  5012  5034 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-28 18:15:38.527  5012  5034 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-28 18:15:38.527  5012  5034 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-28 18:15:38.527  5012  5034 E SarControlService: no key has been found,reset the power
11-28 18:15:38.527  5012  5046 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-28 18:15:38.527  5012  5046 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-28 18:15:38.527  5012  5046 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-28 18:15:38.528  5037  5037 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-28 18:15:38.528  5037  5037 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-28 18:15:38.528  3953  3953 D SystemUpdateService: onCreate
11-28 18:15:38.529  5012  5046 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-28 18:15:38.529  5012  5046 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-28 18:15:38.529  5012  5046 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-28 18:15:38.530  5037  5037 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-28 18:15:38.530  5037  5037 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-28 18:15:38.532  3953  3953 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-28 18:15:38.532  5037  5051 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6efb20e HexData = [00000000ea03000000000000ffffffff]
11-28 18:15:38.532  5037  5051 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-28 18:15:38.533  5037  5051 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-28 18:15:38.534  5037  5037 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-28 18:15:38.534  3953  5770 I SystemUpdateService: active receiver: enabled
11-28 18:15:38.534  5012  5023 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-28 18:15:38.537  3953  5770 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-28 18:15:38.539  3953  5770 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-28 18:15:38.539  3953  5770 I SystemUpdateService: now status is 0 (complete)
11-28 18:15:38.539  3953  5770 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-28 18:15:38.539  3953  5770 I SystemUpdateService: file has been verified
,11-28 18:15:38.539  3953  5770 I SystemUpdateService: OTA package size = 21989297
11-28 18:15:38.542  3953  5770 I SystemUpdateService: showing system update notification
11-28 18:15:38.546  5037  5051 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6efb20e HexData = [00000000eb03000000000000ffffffff]
,11-28 18:15:38.547  5037  5051 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-28 18:15:38.547  5037  5051 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-28 18:15:38.548  5037  5037 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-28 18:15:38.548  5012  5022 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-28 18:15:38.548  3439  3439 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-28 18:15:38.550  3953  3953 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-28 18:15:38.551  3953  5363 I iu.UploadsManager: num queued entries: 0
11-28 18:15:38.552  3953  5363 I iu.UploadsManager: num updated entries: 0
11-28 18:15:38.552  3953  5363 I iu.SyncManager: NEXT; no task
11-28 18:15:38.553   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-28 18:15:38.555  3953  3953 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-28 18:15:38.556  3953  3953 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-28 18:15:38.557  3439  3439 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-28 18:15:38.569   928   938 I ActivityManager: Start proc 5778:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-28 18:15:38.570  3953  3953 D SystemUpdateService: onDestroy
,11-28 18:15:38.575   506   925 E Netd    : netlink response contains error (No such file or directory)
11-28 18:15:38.576   506   925 D TetherController: Setting IP forward enable = 0
,11-28 18:15:38.577   928  2966 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-28 18:15:38.577   928  2966 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-28 18:15:38.588  3439  3439 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-28 18:15:38.600  3439  3439 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-28 18:15:38.608  5778  5778 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-28 18:15:38.610  5778  5778 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-28 18:15:38.616  5778  5778 D SprintDMHelper: simOperator: 
,11-28 18:15:38.616  5778  5778 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-28 18:15:38.628   928  3144 I ActivityManager: Start proc 5792:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-28 18:15:38.703   928  2964 D wifi    : In wifi stop Hal
,11-28 18:15:38.703   928  2964 D wifi    : halHandle = 0x7f6101be00, mVM = 0x7f7d60d140, mCls = 0x100a02
11-28 18:15:38.703   928  3438 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-28 18:15:38.703   928  3438 D WifiHAL : Got a signal to exit!!!
11-28 18:15:38.704   928  3438 I WifiHAL : Exit wifi_event_loop
11-28 18:15:38.704  4987  4987 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-28 18:15:38.705   928  2964 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-28 18:15:38.705   928  2964 E WifiHAL : Event processing terminated
11-28 18:15:38.705   928  2964 D wifi    : In wifi cleaned up handler
11-28 18:15:38.705   928  2964 I WifiHAL : Internal cleanup completed
,11-28 18:15:38.705  4089  4214 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-28 18:15:38.707  4987  5806 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-28 18:15:38.722   928  3845 I ActivityManager: Start proc 5807:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-28 18:15:38.725   928   939 I ActivityManager: Killing 5223:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-28 18:15:38.729   928  3438 D wifi    : set interface wlan0 flags (DOWN)
,11-28 18:15:38.731   928  2964 D WifiNative-HAL: HAL event thread stopped successfully
,11-28 18:15:38.761  5807  5807 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-28 18:15:38.768   928  3144 I ActivityManager: Killing 5085:com.google.android.deskclock/u0a66 (adj 15): empty #17
,11-28 18:15:38.929  5580  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 18:15:38.929  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 18:15:38.929  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 18:15:38.929  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-28 18:15:38.929  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 18:15:38.929  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-28 18:15:38.929  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-28 18:15:38.929  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-28 18:15:38.929  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-28 18:15:38.931  5580  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-28 18:15:38.934   928  3407 D WifiService: setWifiEnabled: true pid=5580, uid=10077
11-28 18:15:38.935   928  3407 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-28 18:15:38.937   928   945 D Tethering: InitialState.processMessage what=4
11-28 18:15:38.938  5580  5628 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-28 18:15:38.939   506   925 D SoftapController: Softap fwReload - Ok
11-28 18:15:38.940   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-28 18:15:38.941   506   925 D CommandListener: Setting iface cfg
11-28 18:15:38.941   506   925 D CommandListener: Trying to bring down wlan0
,11-28 18:15:38.942   506   925 D CommandListener: Clearing all IP addresses on wlan0
,11-28 18:15:38.945   928  2964 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-28 18:15:39.439   928  3843 D WifiService: setWifiEnabled: true pid=5580, uid=10077
,11-28 18:15:39.439   928  3843 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-28 18:15:39.557   928  2964 D wifi    : set interface wlan0 flags (UP)
,11-28 18:15:39.558   928  2964 I WifiHAL : Initializing wifi
,11-28 18:15:39.558   928  2964 I WifiHAL : Creating socket
,11-28 18:15:39.564   928  2964 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-28 18:15:39.565   928  2964 D wifi    : Did set static halHandle = 0x7f6101be00
,11-28 18:15:39.565   928  2964 D wifi    : halHandle = 0x7f6101be00, mVM = 0x7f7d60d140, mCls = 0x184e
11-28 18:15:39.565   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-28 18:15:39.566   928  2964 D wifi    : array field set
,11-28 18:15:39.566   928  2964 I WifiNative-HAL: interface[0] = wlan0
11-28 18:15:39.570   928  5823 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547088350720
11-28 18:15:39.570   928  5823 D wifi    : waitForHalEvents called, vm = 0x7f7d60d140, obj = 0x184e, env = 0x7f5eb948c0
,11-28 18:15:39.646  5824  5824 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-28 18:15:39.670   928  2964 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-28 18:15:39.722  5824  5824 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-28 18:15:39.735  5824  5824 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-28 18:15:39.735  5824  5824 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-28 18:15:39.749   928  2964 D WifiConfigStore: Loading config and enabling all networks 
,11-28 18:15:39.768   928  2964 D WifiConfigStore: loaded 0 passpoint configs
,11-28 18:15:39.769   928  2964 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-28 18:15:39.769   928  2964 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-28 18:15:39.770   928  2964 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-28 18:15:39.770   928  2964 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-28 18:15:39.770   928  2964 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-28 18:15:39.771   928  2964 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-28 18:15:39.771   928  2964 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
,11-28 18:15:39.771   928  2964 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-28 18:15:39.772   928  2964 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-28 18:15:39.772   928  2964 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-28 18:15:39.772   928  2964 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-28 18:15:39.772   928  2964 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-28 18:15:39.774   928  2964 D WifiNative-HAL: Setting external_sim to 1
,11-28 18:15:39.775   928  2964 D wifi    : setting dfs flag to true, 0x7f660fea20
,11-28 18:15:39.775  4987  4987 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-28 18:15:39.775   928  2964 D WifiStateMachine: Setting OUI to DA-A1-19
,11-28 18:15:39.775   928  2964 D wifi    : setting scan oui 0x7f660fea20
11-28 18:15:39.775   928  2964 D WifiHAL : Sending mac address OUI
,11-28 18:15:39.778   928  2964 E native  : do suspend false
,11-28 18:15:39.784   928  2964 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-28 18:15:39.784   928   928 D RttService: SCAN_AVAILABLE : 3
11-28 18:15:39.784   928  3073 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-28 18:15:39.787   506   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-28 18:15:39.789   506   925 D CommandListener: Setting iface cfg
,11-28 18:15:39.790   928  2956 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '125 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 125 Failed to set address (No such device)'
11-28 18:15:39.790   928  2956 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-28 18:15:39.794   928  2956 D WifiNative-HAL: p2pGetDeviceAddress
,11-28 18:15:39.794   928  2956 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-28 18:15:39.798   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=106891 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=10 mControllerEnergyUsed=38 }
,11-28 18:15:39.950  5580  5654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 18:15:39.950  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 18:15:39.950  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 18:15:39.950  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 18:15:39.950  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 18:15:39.950  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-28 18:15:39.950  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-28 18:15:39.950  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-28 18:15:39.950  5580  5654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-28 18:15:39.958  5580  5654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-28 18:15:39.961  5580  5628 D BluetoothAdapter: enable(): BT is already enabled..!
,11-28 18:15:39.962   928  3787 D WifiService: setWifiEnabled: true pid=5580, uid=10077
,11-28 18:15:39.962   928  3787 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-28 18:15:39.964  5580  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-28 18:15:39.964  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:15:39.964  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-28 18:15:39.964  5580  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27b8866 removed from the list
,11-28 18:15:39.964  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 18:15:39.965  5580  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70c57a7 removed from the list
11-28 18:15:39.965  5580  5628 D io.jxcore.node.ConnectivityMonitor: stop
,11-28 18:15:39.969  5580  5628 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,11-28 18:15:39.972  5580  5628 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
11-28 18:15:39.975  5580  5628 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,11-28 18:15:39.977  5580  5628 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-28 18:15:39.981  5580  5628 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,11-28 18:15:39.982  5580  5628 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-28 18:15:39.983  5580  5628 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
11-28 18:15:39.983  5580  5628 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-28 18:15:39.984  5580  5628 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-28 18:15:39.988  5580  5628 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,11-28 18:15:39.988  5580  5628 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b92a1c3 Bundle[{}]
11-28 18:15:39.989  5580  5628 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-28 18:15:39.990  5580  5628 I io.jxcore.node.LifeCycleMonitor: start: OK
11-28 18:15:39.990  5580  5628 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-28 18:15:39.991  5580  5628 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,11-28 18:15:39.991  5580  5628 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-28 18:15:39.992  5580  5628 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-28 18:15:39.993  5580  5628 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-28 18:15:39.994  5580  5628 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
,11-28 18:15:39.994  5580  5628 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,11-28 18:15:39.995  5580  5628 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,11-28 18:15:39.996  5580  5628 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-28 18:15:39.998  5580  5628 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,11-28 18:15:40.000  5580  5628 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-28 18:15:40.001  5580  5628 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
11-28 18:15:40.002  5580  5628 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,11-28 18:15:40.003  5580  5628 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
11-28 18:15:40.004  5580  5628 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-28 18:15:40.005  5580  5628 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-28 18:15:40.007  5580  5628 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testNoAvailablePorts
,11-28 18:15:41.012  5580  5628 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,11-28 18:15:41.014  5580  5628 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-28 18:15:41.018  5580  5628 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-28 18:15:41.020  5580  5628 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,11-28 18:15:41.022  5580  5628 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,11-28 18:15:41.022  5580  5628 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 177)
,11-28 18:15:41.024  5580  5628 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-28 18:15:41.025  5580  5628 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,11-28 18:15:41.025  5580  5628 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 178)
,11-28 18:15:41.027  5580  5628 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,11-28 18:15:41.028  5580  5628 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,11-28 18:15:41.029  5580  5628 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
11-28 18:15:41.030  5580  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-28 18:15:41.030  5580  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a547ffd added. We now have 3 listener(s)
,11-28 18:15:41.032  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-28 18:15:41.032  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 18:15:41.033  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 18:15:41.033  5580  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-28 18:15:41.033  5580  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa7c4f2 added. We now have 3 listener(s)
11-28 18:15:41.033  5580  5628 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 18:15:41.034  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-28 18:15:41.040  5580  5628 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,11-28 18:15:41.041  5580  5628 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-28 18:15:41.041  5580  5628 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-28 18:15:41.041  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-28 18:15:41.042  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:41.042  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:41.042  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:41.042  5580  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-28 18:15:41.042  5580  5628 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-28 18:15:41.042  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-28 18:15:41.042  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 18:15:41.042  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-28 18:15:41.047  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-28 18:15:41.048  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-28 18:15:41.048  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-28 18:15:41.048  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-28 18:15:41.048  5580  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-28 18:15:41.048  5580  5580 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-28 18:15:41.048  5580  5828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-28 18:15:41.049  5580  5828 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 18:15:41.049  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-28 18:15:41.050  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 18:15:41.050  5712  5712 W Binder_2: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[31528]" dev="sockfs" ino=31528 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 18:15:41.050  5712  5712 W Binder_2: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[31528]" dev="sockfs" ino=31528 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-28 18:15:41.050  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-28 18:15:41.055  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-28 18:15:41.055  5580  5628 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 18:15:41.055  5580  5828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-28 18:15:41.055  5580  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-28 18:15:41.060  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:41.060  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-28 18:15:41.061  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 18:15:41.061  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 18:15:41.061  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
11-28 18:15:41.064  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:41.064  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:41.064  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-28 18:15:41.064  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-28 18:15:41.064  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 18:15:41.065  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
11-28 18:15:41.065  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 18:15:41.065  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 18:15:41.065  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:41.065  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-28 18:15:41.065  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 18:15:41.065  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:41.065  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:41.065  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:41.066  5580  5628 D BluetoothAdapter: STATE_ON
,11-28 18:15:41.070  5701  5712 D BtGatt.GattService: registerClient() - UUID=06bcff54-7bef-4234-ab59-284dc5581923
11-28 18:15:41.071  5701  5718 D BtGatt.GattService: onClientRegistered() - UUID=06bcff54-7bef-4234-ab59-284dc5581923, clientIf=5
,11-28 18:15:41.072  5580  5591 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-28 18:15:41.074  5701  5720 D BtGatt.AdvertiseManager: message : 0
,11-28 18:15:41.078  5701  5720 D BtGatt.AdvertiseManager: starting multi advertising
,11-28 18:15:41.091  5701  5718 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-28 18:15:41.099  5701  5718 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-28 18:15:41.100  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:41.100  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:41.101  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-28 18:15:41.101  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:41.101  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:41.101  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:41.101  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:41.101  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:41.101  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-28 18:15:41.104  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-28 18:15:41.104  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:41.105  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:41.105  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:41.105  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:41.106  5580  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-28 18:15:41.106  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-28 18:15:41.106  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-28 18:15:41.106  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-28 18:15:41.106  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-28 18:15:41.106  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-28 18:15:41.106  5580  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 18:15:41.106  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 18:15:41.107  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-28 18:15:41.107  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 18:15:41.107  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 18:15:41.107  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-28 18:15:41.107  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 18:15:41.107  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-28 18:15:41.107  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-28 18:15:41.111  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 18:15:41.111  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-28 18:15:41.111  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 18:15:41.111  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-28 18:15:41.111  5580  5580 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-28 18:15:41.611  5580  5580 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-28 18:15:41.612  5580  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-28 18:15:41.612  5580  5580 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-28 18:15:42.914   928  3847 I ActivityManager: Killing 3869:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-28 18:15:42.967  5824  5824 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-28 18:15:42.974  5824  5824 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-28 18:15:42.978  5824  5824 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-28 18:15:42.982  5824  5824 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-28 18:15:43.004   928  2964 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-28 18:15:43.005   928  2964 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-28 18:15:43.005   928  2964 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-28 18:15:43.018   928  2964 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-28 18:15:43.052   928  2964 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-28 18:15:43.059  5824  5824 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-28 18:15:43.476  5824  5824 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-28 18:15:43.512  5824  5824 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-28 18:15:43.513  5824  5824 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-28 18:15:43.526   928  2964 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-28 18:15:43.526   928  2964 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-28 18:15:43.526   928  2966 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-28 18:15:43.542   928  2964 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-28 18:15:43.554   506   925 D CommandListener: Setting iface cfg
,11-28 18:15:43.560   928  2964 D WifiStateMachine: Start Dhcp Watchdog 2
,11-28 18:15:43.567   928  5833 D DhcpClient: Receive thread started
,11-28 18:15:43.571   928  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 18:15:43.571   928  2964 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-28 18:15:43.571   928  2966 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-28 18:15:43.652   928  2964 E native  : do suspend false
,11-28 18:15:43.662   928  5832 D DhcpClient: Broadcasting DHCPDISCOVER
,11-28 18:15:43.678   928  5833 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172730, domain null
,11-28 18:15:43.678   928  5832 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172730 seconds
,11-28 18:15:43.679   928  5832 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-28 18:15:43.691   928  5833 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-28 18:15:43.691   928  5832 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-28 18:15:43.692   506   925 D CommandListener: Setting iface cfg
,11-28 18:15:43.694   928  2964 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-28 18:15:43.695   928  5832 D DhcpClient: Scheduling renewal in 86399s
,11-28 18:15:43.702   928  2964 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-28 18:15:43.703   928  2964 D WifiConfigStore: No blacklist allowed without epno enabled
11-28 18:15:43.703   928  2966 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-28 18:15:43.704   928  2964 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
11-28 18:15:43.707   928  2966 D ConnectivityService: Adding iface wlan0 to network 101
,11-28 18:15:43.733   928  2966 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-28 18:15:43.733   928  2966 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-28 18:15:43.734   928  2966 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-28 18:15:43.735   928  2966 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-28 18:15:43.736   928  2966 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-28 18:15:43.742   928  2966 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 18:15:43.745   928  2966 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-28 18:15:43.745   928  2966 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-28 18:15:43.745   928  2966 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-28 18:15:43.745   928  2964 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-28 18:15:43.745   928  2966 D ConnectivityService:    accepting network in place of null
11-28 18:15:43.745   928  2964 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-28 18:15:43.746   928  2966 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-28 18:15:43.758   928  5831 D NetlinkSocketObserver: NeighborEvent{elapsedMs=110851, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-28 18:15:43.766   506   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-28 18:15:43.786   506   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-28 18:15:43.789   928  2966 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-28 18:15:43.789   928  2966 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-28 18:15:43.789  3732  3864 W QCNEJ   : |CORE| network available: 101
11-28 18:15:43.790   928  2966 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-28 18:15:43.791  3732  3864 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-28 18:15:43.791   928   945 D Tethering: MasterInitialState.processMessage what=3
11-28 18:15:43.792  3732  3864 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-28 18:15:43.792  3732  3864 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-28 18:15:43.801  5012  5034 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-28 18:15:43.802  5012  5034 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,11-28 18:15:43.802  5012  5034 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-28 18:15:43.802  5012  5034 E SarControlService: no key has been found,reset the power
11-28 18:15:43.802  5012  5046 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-28 18:15:43.802  5012  5046 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-28 18:15:43.802  5012  5046 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-28 18:15:43.802  5037  5037 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-28 18:15:43.803  5037  5037 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-28 18:15:43.807  5012  5046 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-28 18:15:43.807  5012  5046 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-28 18:15:43.807  5012  5046 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-28 18:15:43.807  5037  5037 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-28 18:15:43.807  5037  5037 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-28 18:15:43.809  3934  3934 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-28 18:15:43.810  5037  5051 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6efb20e HexData = [00000000ec03000000000000ffffffff]
11-28 18:15:43.810  5037  5051 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-28 18:15:43.810  5037  5051 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-28 18:15:43.810  5037  5037 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-28 18:15:43.811  5012  5023 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-28 18:15:43.812  3953  3953 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-28 18:15:43.815  3953  3953 D SystemUpdateService: onCreate
,11-28 18:15:43.819  3953  3953 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-28 18:15:43.820  5037  5051 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6efb20e HexData = [00000000ed03000000000000ffffffff]
11-28 18:15:43.820  5037  5051 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-28 18:15:43.820  5037  5051 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-28 18:15:43.821  5037  5037 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-28 18:15:43.821  5012  5022 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-28 18:15:43.825   928  5830 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-28 18:15:43.831  3953  3953 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-28 18:15:43.836  3953  5363 I iu.UploadsManager: num queued entries: 0
,11-28 18:15:43.837  3953  5843 I SystemUpdateService: active receiver: enabled
,11-28 18:15:43.840  3953  3953 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-28 18:15:43.841  3953  3953 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-28 18:15:43.843  5778  5778 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-28 18:15:43.846  5778  5778 D SprintDMHelper: simOperator: 
,11-28 18:15:43.846  5778  5778 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-28 18:15:43.836  3953  5363 I iu.UploadsManager: num updated entries: 0
,11-28 18:15:43.858  3953  5363 I iu.SyncManager: NEXT; no task
,11-28 18:15:43.867  3953  5843 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-28 18:15:43.877   928  5830 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 28 Nov 2016 17:15:43 GMT], X-Android-Received-Millis=[1480353343876], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480353343850]}
,11-28 18:15:43.877   928  2966 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-28 18:15:43.878   928  2966 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-28 18:15:43.878   928  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-28 18:15:43.879   928  2966 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-28 18:15:43.884  3953  5843 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-28 18:15:43.884  3953  5843 I SystemUpdateService: now status is 0 (complete)
11-28 18:15:43.884  3953  5843 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-28 18:15:43.884  3953  5843 I SystemUpdateService: file has been verified
11-28 18:15:43.885  3953  5843 I SystemUpdateService: OTA package size = 21989297
,11-28 18:15:43.890  3953  5843 I SystemUpdateService: showing system update notification
,11-28 18:15:43.898   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-28 18:15:43.899  3953  3953 D SystemUpdateService: onDestroy
,11-28 18:15:43.965  4987  5847 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-28 18:15:44.608  5580  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-28 18:15:44.608  5580  5628 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-28 18:15:44.608  5580  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-28 18:15:44.609  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-28 18:15:44.609  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-28 18:15:44.609  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 18:15:44.609  5580  5828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-28 18:15:44.609  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-28 18:15:44.609  5580  5828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-28 18:15:44.610  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-28 18:15:44.610  5580  5828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-28 18:15:44.610  5580  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-28 18:15:44.610  5580  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-28 18:15:44.610  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-28 18:15:44.610  5580  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:15:44.610  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:44.610  5580  5580 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-28 18:15:44.611  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 18:15:44.611  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 18:15:44.611  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:44.611  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:44.611  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:44.612  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:44.615  5580  5628 D BluetoothAdapter: STATE_ON
,11-28 18:15:44.615  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-28 18:15:44.617  5580  5628 D BluetoothAdapter: STATE_ON
11-28 18:15:44.617  5580  5628 D BluetoothLeScanner: could not find callback wrapper
11-28 18:15:44.618  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-28 18:15:44.618  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:44.618  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:44.618  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:44.619  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-28 18:15:44.619  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:44.621  5701  5720 D BtGatt.AdvertiseManager: message : 1
,11-28 18:15:44.623  5701  5720 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-28 18:15:44.640  5701  5718 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-28 18:15:44.640  5701  5718 D BtGatt.GattService: Client app is not null!
11-28 18:15:44.642  5701  5744 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-28 18:15:44.643  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-28 18:15:44.643  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:44.643  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-28 18:15:44.643  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:44.644  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:44.644  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:44.644  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-28 18:15:44.644  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-28 18:15:44.645  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-28 18:15:44.646  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:44.648  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:44.648  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 18:15:44.648  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:44.649  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:44.649  5580  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 18:15:44.649  5580  5580 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-28 18:15:44.649  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 18:15:44.649  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 18:15:44.650  5580  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-28 18:15:44.650  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 18:15:44.650  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 18:15:44.650  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-28 18:15:44.650  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 18:15:44.650  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-28 18:15:44.651  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-28 18:15:44.651  5580  5580 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 18:15:44.651  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-28 18:15:44.651  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 18:15:44.653  5580  5628 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
11-28 18:15:44.653  5580  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 18:15:44.654  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-28 18:15:44.654  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 18:15:44.654  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 18:15:44.654  5580  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 18:15:44.654  5580  5628 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-28 18:15:44.654  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-28 18:15:44.654  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 18:15:44.654  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-28 18:15:44.657  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-28 18:15:44.662  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-28 18:15:44.662  5580  5628 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 18:15:44.663  5580  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-28 18:15:44.668  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:44.668  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-28 18:15:44.669  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-28 18:15:44.670  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 18:15:44.670  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-28 18:15:44.673  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-28 18:15:44.680  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,11-28 18:15:44.681  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:44.681  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-28 18:15:44.681  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-28 18:15:44.681  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-28 18:15:44.682  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-28 18:15:44.682  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:44.684  5580  5628 D BluetoothAdapter: STATE_ON
11-28 18:15:44.689  5701  5712 D BtGatt.GattService: registerClient() - UUID=9d2dd6ff-e368-4998-b94a-9d7646376703
,11-28 18:15:44.690  5701  5718 D BtGatt.GattService: onClientRegistered() - UUID=9d2dd6ff-e368-4998-b94a-9d7646376703, clientIf=5
11-28 18:15:44.690  5580  5590 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-28 18:15:44.691  5701  5711 D BtGatt.GattService: start scan with filters
,11-28 18:15:44.695  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-28 18:15:44.695  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:44.695  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-28 18:15:44.695  5701  5721 D BtGatt.ScanManager: handling starting scan
,11-28 18:15:44.696  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:44.696  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-28 18:15:44.696  5580  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 18:15:44.696  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 18:15:44.696  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-28 18:15:44.697  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 18:15:44.697  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 18:15:44.697  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-28 18:15:44.697  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 18:15:44.697  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-28 18:15:44.698  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 18:15:44.698  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:44.698  5701  5721 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8a18a27
11-28 18:15:44.701  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:44.701  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-28 18:15:44.701  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:44.701  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:44.701  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-28 18:15:44.704  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 18:15:44.704  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 18:15:44.705  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 18:15:44.705  5580  5580 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-28 18:15:44.705  5701  5718 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-28 18:15:44.705  5701  5718 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:15:44.705  5701  5721 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-28 18:15:44.713  5701  5718 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-28 18:15:44.713  5701  5718 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:15:44.713  5701  5721 D BtGatt.ScanManager: Starting BLE batch scan
11-28 18:15:44.713  5701  5721 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-28 18:15:44.723  5701  5718 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-28 18:15:44.723  5701  5718 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 18:15:44.728  5701  5718 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-28 18:15:44.728  5701  5718 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 18:15:44.790   928  2966 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-28 18:15:45.206  5580  5580 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-28 18:15:45.206  5580  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 18:15:45.206  5580  5580 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-28 18:15:46.940   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-28 18:15:46.940   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-28 18:15:47.704  5580  5628 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-28 18:15:47.704  5580  5628 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,11-28 18:15:47.704  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,11-28 18:15:47.705  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:47.705  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:47.705  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.705  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-28 18:15:47.705  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-28 18:15:47.705  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-28 18:15:47.705  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-28 18:15:47.705  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-28 18:15:47.705  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-28 18:15:47.705  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-28 18:15:47.705  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-28 18:15:47.705  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-28 18:15:47.705  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.706  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 6
11-28 18:15:47.706  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:47.706  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.706  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-28 18:15:47.707  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-28 18:15:47.707  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.707  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.707  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.710  5580  5628 D BluetoothAdapter: STATE_ON
11-28 18:15:47.711  5701  5744 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-28 18:15:47.712  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-28 18:15:47.713  5701  5721 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-28 18:15:47.713  5580  5628 D BluetoothAdapter: STATE_ON
11-28 18:15:47.715  5701  5712 D BtGatt.GattService: stopScan() - queue size =1
11-28 18:15:47.717  5701  5711 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 18:15:47.718  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-28 18:15:47.718  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.718  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-28 18:15:47.719  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.719  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 18:15:47.719  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.719  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.719  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-28 18:15:47.720  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-28 18:15:47.720  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-28 18:15:47.720  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-28 18:15:47.721  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.722  5701  5701 D BtGatt.ScanManager: awakened up at time 114815
11-28 18:15:47.727  5580  5628 D BluetoothAdapter: STATE_ON
11-28 18:15:47.733  5701  5747 D BtGatt.GattService: registerClient() - UUID=e2f972d6-97a6-4f62-83b7-bcc6c0c05b12
11-28 18:15:47.734  5701  5718 D BtGatt.GattService: onClientRegistered() - UUID=e2f972d6-97a6-4f62-83b7-bcc6c0c05b12, clientIf=5
11-28 18:15:47.734  5580  5590 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-28 18:15:47.735  5701  5711 D BtGatt.GattService: start scan with filters
,11-28 18:15:47.738  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-28 18:15:47.738  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:47.738  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-28 18:15:47.738  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.738  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.738  5580  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 18:15:47.738  5580  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-28 18:15:47.739  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 18:15:47.739  5580  5628 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,11-28 18:15:47.739  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-28 18:15:47.739  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-28 18:15:47.739  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-28 18:15:47.739  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 18:15:47.739  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 18:15:47.739  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 18:15:47.740  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-28 18:15:47.741  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-28 18:15:47.741  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-28 18:15:47.741  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-28 18:15:47.741  5580  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-28 18:15:47.741  5580  5580 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-28 18:15:47.741  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-28 18:15:47.741  5580  5856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-28 18:15:47.742  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-28 18:15:47.742  5580  5628 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 18:15:47.743  5701  5718 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
11-28 18:15:47.743  5701  5718 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:15:47.743  5580  5856 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 18:15:47.743  5701  5718 D BtGatt.GattService: current time is 114836895458
11-28 18:15:47.744  5701  5718 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -84, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -84, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -82, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -84, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -84, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-28 18:15:47.746  5580  5856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-28 18:15:47.746  5701  5718 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,11-28 18:15:47.743  5744  5744 W Binder_3: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[31575]" dev="sockfs" ino=31575 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-28 18:15:47.747  5701  5718 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-28 18:15:47.747  5701  5718 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-28 18:15:47.743  5744  5744 W Binder_3: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[31575]" dev="sockfs" ino=31575 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 18:15:47.748  5701  5718 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-28 18:15:47.748  5701  5718 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-28 18:15:47.751  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:47.751  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.751  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.751  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-28 18:15:47.751  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-28 18:15:47.751  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 18:15:47.751  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
11-28 18:15:47.751  5580  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 18:15:47.751  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-28 18:15:47.752  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.752  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-28 18:15:47.752  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 18:15:47.752  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.752  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.752  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.753  5580  5628 D BluetoothAdapter: STATE_ON
11-28 18:15:47.754  5701  5718 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-28 18:15:47.754  5701  5718 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:15:47.754  5701  5721 D BtGatt.ScanManager: stopping BLe Batch
11-28 18:15:47.756  5701  5711 D BtGatt.GattService: registerClient() - UUID=f7ee4b06-0594-4f67-b52c-76ce90efc90c
11-28 18:15:47.757  5701  5718 D BtGatt.GattService: onClientRegistered() - UUID=f7ee4b06-0594-4f67-b52c-76ce90efc90c, clientIf=6
,11-28 18:15:47.757  5580  5624 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
11-28 18:15:47.758  5701  5720 D BtGatt.AdvertiseManager: message : 0
,11-28 18:15:47.760  5701  5718 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-28 18:15:47.760  5701  5718 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:15:47.760  5701  5720 D BtGatt.AdvertiseManager: starting multi advertising
,11-28 18:15:47.761  5701  5721 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-28 18:15:47.770  5701  5718 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-28 18:15:47.775  5701  5718 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-28 18:15:47.775  5701  5718 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 18:15:47.777  5701  5721 D BtGatt.ScanManager: handling starting scan
,11-28 18:15:47.780  5701  5718 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-28 18:15:47.780  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.780  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.780  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-28 18:15:47.780  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.780  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.780  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.781  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.781  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.781  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.781  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.781  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.781  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-28 18:15:47.781  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-28 18:15:47.781  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-28 18:15:47.782  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 18:15:47.782  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.784  5701  5718 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-28 18:15:47.784  5701  5718 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:15:47.784  5701  5721 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-28 18:15:47.784  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.784  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.784  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:47.785  5580  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-28 18:15:47.785  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-28 18:15:47.785  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-28 18:15:47.785  5580  5580 ,D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-28 18:15:47.785  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,11-28 18:15:47.787  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-28 18:15:47.787  5580  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 18:15:47.787  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 18:15:47.787  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-28 18:15:47.787  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,11-28 18:15:47.787  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 18:15:47.787  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-28 18:15:47.787  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 18:15:47.787  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-28 18:15:47.787  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-28 18:15:47.789  5701  5718 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-28 18:15:47.789  5701  5718 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:15:47.789  5701  5721 D BtGatt.ScanManager: Starting BLE batch scan
11-28 18:15:47.790  5701  5721 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-28 18:15:47.791  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-28 18:15:47.791  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-28 18:15:47.792  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 18:15:47.792  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 18:15:47.792  5580  5580 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,11-28 18:15:47.798  5701  5718 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-28 18:15:47.798  5701  5718 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 18:15:47.803  5701  5718 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-28 18:15:47.803  5701  5718 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 18:15:48.293  5580  5580 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-28 18:15:48.293  5580  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-28 18:15:48.293  5580  5580 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-28 18:15:50.789  5580  5628 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-28 18:15:50.790  5580  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-28 18:15:50.790  5580  5628 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-28 18:15:50.791  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-28 18:15:50.791  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-28 18:15:50.791  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 18:15:50.791  5580  5856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-28 18:15:50.791  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-28 18:15:50.792  5580  5856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-28 18:15:50.792  5580  5628 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-28 18:15:50.792  5580  5856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-28 18:15:50.792  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-28 18:15:50.792  5580  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a547ffd removed from the list
,11-28 18:15:50.792  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 18:15:50.792  5580  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-28 18:15:50.792  5580  5580 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-28 18:15:50.793  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:50.793  5580  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-28 18:15:50.793  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 18:15:50.793  5580  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:15:50.793  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 18:15:50.794  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:50.794  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:50.794  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:50.794  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-28 18:15:50.795  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:50.797  5580  5628 D BluetoothAdapter: STATE_ON
11-28 18:15:50.798  5701  5744 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-28 18:15:50.798  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-28 18:15:50.800  5701  5721 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-28 18:15:50.801  5580  5628 D BluetoothAdapter: STATE_ON
11-28 18:15:50.803  5701  5712 D BtGatt.GattService: stopScan() - queue size =1
,11-28 18:15:50.805  5701  5711 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 18:15:50.806  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-28 18:15:50.809  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:50.809  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-28 18:15:50.809  5701  5701 D BtGatt.ScanManager: awakened up at time 117902
11-28 18:15:50.809  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:50.809  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:50.809  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:50.810  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-28 18:15:50.810  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:50.811  5701  5720 D BtGatt.AdvertiseManager: message : 1
11-28 18:15:50.812  5701  5720 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-28 18:15:50.825  5701  5718 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,11-28 18:15:50.825  5701  5718 D BtGatt.GattService: Client app is not null!
11-28 18:15:50.826  5701  5712 D BtGatt.GattService: unregisterClient() - clientIf=6
11-28 18:15:50.826  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-28 18:15:50.827  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:50.827  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-28 18:15:50.827  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:50.827  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:50.827  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:50.827  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-28 18:15:50.827  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-28 18:15:50.828  5580  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-28 18:15:50.829  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:50.833  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:50.833  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 18:15:50.834  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-28 18:15:50.834  5580  5628 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-28 18:15:50.834  5580  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa7c4f2 removed from the list
11-28 18:15:50.834  5580  5628 D io.jxcore.node.ConnectivityMonitor: stop
11-28 18:15:50.834  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 18:15:50.834  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 18:15:50.834  5580  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-28 18:15:50.834  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 18:15:50.834  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 18:15:50.834  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
11-28 18:15:50.834  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 18:15:50.834  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-28 18:15:50.834  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-28 18:15:50.835  5580  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-28 18:15:50.835  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 18:15:50.835  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 18:15:50.835  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 18:15:50.835  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 18:15:50.835  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 18:15:50.835  5580  5580 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 18:15:50.835  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-28 18:15:50.835  5580  5628 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-28 18:15:50.835  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 18:15:50.835  5580  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-28 18:15:50.835  5580  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-28 18:15:50.835  5580  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-28 18:15:50.836  5580  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 18:15:50.836  5580  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-28 18:15:50.837  5580  5628 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-28 18:15:50.837  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 18:15:50.837  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 18:15:50.837  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 18:15:50.838  5580  5628 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-28 18:15:50.839  5580  5628 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-28 18:15:50.839  5580  5628 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
,11-28 18:15:50.840  5580  5628 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
,11-28 18:15:50.840  5701  5718 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
11-28 18:15:50.840  5701  5718 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:15:50.841  5701  5718 D BtGatt.GattService: current time is 117934321349
11-28 18:15:50.841  5701  5718 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -84, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -81, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -87, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -87, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -86, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-28 18:15:50.841  5580  5628 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-28 18:15:50.841  5701  5718 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-28 18:15:50.841  5701  5718 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
11-28 18:15:50.842  5701  5718 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-28 18:15:50.842  5701  5718 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-28 18:15:50.842  5580  5628 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-28 18:15:50.842  5701  5718 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-28 18:15:50.842  5701  5718 E BtGatt.ContextMap: Context not found for ID 5
11-28 18:15:50.843  5580  5628 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-28 18:15:50.843  5580  5628 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-28 18:15:50.849  5701  5718 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-28 18:15:50.849  5701  5718 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:15:50.849  5701  5721 D BtGatt.ScanManager: stopping BLe Batch
,11-28 18:15:50.854  5701  5718 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-28 18:15:50.854  5701  5718 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:15:50.854  5701  5721 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-28 18:15:50.858  5701  5718 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-28 18:15:50.858  5701  5718 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 18:15:51.335  5580  5580 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-28 18:15:51.751   928  2966 D ConnectivityService: handlePromptUnvalidated 101
,11-28 18:15:51.941   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:15:52.848  5580  5628 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-28 18:15:52.942   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:15:53.000  5580  5858 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 191, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-28 18:15:53.000  5580  5858 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 18:15:53.821  5580  5858 W !!      : call onHalfStreamCopied
,11-28 18:15:53.821  5580  5858 I testCopyDataAndClose: closing input stream
,11-28 18:15:53.942   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:15:54.178   928  2964 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 7, 9 -> obsolete
,11-28 18:15:54.590  5580  5858 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 191, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-28 18:15:54.590  5580  5858 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 18:15:54.590  5580  5858 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-28 18:15:54.590  5580  5858 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 18:15:54.590  5580  5858 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-28 18:15:54.590  5580  5858 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-28 18:15:54.590  5580  5858 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-28 18:15:54.590  5580  5858 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-28 18:15:54.590  5580  5858 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-28 18:15:54.591  5580  5858 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 191, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-28 18:15:54.591  5580  5858 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-28 18:15:54.799   928  2964 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 8, 9 -> obsolete
,11-28 18:15:54.943   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:15:55.654   928  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 18:15:55.944   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:15:56.945   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-28 18:15:58.685   928  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 18:15:58.873  5580  5628 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-28 18:15:58.967  5580  5859 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 194, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-28 18:15:58.967  5580  5859 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 18:16:00.636  5580  5859 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 194, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-28 18:16:00.636  5580  5859 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 18:16:00.636  5580  5859 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-28 18:16:00.636  5580  5859 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-28 18:16:00.636  5580  5859 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-28 18:16:00.636  5580  5859 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-28 18:16:00.636  5580  5859 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-28 18:16:00.636  5580  5859 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-28 18:16:00.636  5580  5859 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-28 18:16:00.636  5580  5859 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 194, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-28 18:16:00.636  5580  5859 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-28 18:16:01.721   928  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 18:16:01.946   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:16:02.947   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:16:03.949   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:16:04.738   928  2966 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 18:16:04.742  5580  5628 I StreamCopyingThreadTest: Starting test: testRunNotify
11-28 18:16:04.745  5580  5860 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
11-28 18:16:04.745  5580  5860 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-28 18:16:04.745  5580  5860 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 196, thread name: My test thread name). Connection data: Peer properties: [null null].
11-28 18:16:04.745  5580  5860 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 18:16:04.746  5580  5860 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-28 18:16:04.746  5580  5860 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-28 18:16:04.746  5580  5860 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-28 18:16:04.746  5580  5860 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-28 18:16:04.746  5580  5860 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-28 18:16:04.746  5580  5860 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-28 18:16:04.746  5580  5860 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-28 18:16:04.747  5580  5860 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
11-28 18:16:04.747  5580  5860 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-28 18:16:04.749  5580  5628 I StreamCopyingThreadTest: Starting test: testSetBufferSize
11-28 18:16:04.750  5580  5628 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-28 18:16:04.752  5580  5628 I StreamCopyingThreadTest: Starting test: testRunWithException
11-28 18:16:04.754  5580  5861 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 200, name: My test thread name). Connection data: Peer properties: [null null].
11-28 18:16:04.754  5580  5861 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-28 18:16:04.754  5580  5861 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 200, thread name: My test thread name): Test exception.
,11-28 18:16:04.754  5580  5861 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 200, name: My test thread name). Connection data: Peer properties: [null null].
11-28 18:16:04.754  5580  5861 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-28 18:16:04.754  5580  5861 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-28 18:16:04.754  5580  5861 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 200, name: My test thread name). Connection data: Peer properties: [null null].
11-28 18:16:04.754  5580  5861 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-28 18:16:04.757  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - DEBUG UnitTest_app: 'Running unit tests'
11-28 18:16:04.757  5580  5628 I jxcore-log: 
11-28 18:16:04.757  5580  5628 I jxcore-log: *Native tests were executed*
11-28 18:16:04.757  5580  5628 I jxcore-log: 
,11-28 18:16:04.757  5580  5628 I jxcore-log: Total number of executed tests:  81
11-28 18:16:04.757  5580  5628 I jxcore-log: 
11-28 18:16:04.757  5580  5628 I jxcore-log: Number of passed tests:  79
11-28 18:16:04.757  5580  5628 I jxcore-log: 
11-28 18:16:04.757  5580  5628 I jxcore-log: Number of failed tests:  0
11-28 18:16:04.757  5580  5628 I jxcore-log: 
11-28 18:16:04.757  5580  5628 I jxcore-log: Number of ignored tests:  2
11-28 18:16:04.757  5580  5628 I jxcore-log: 
11-28 18:16:04.757  5580  5628 I jxcore-log: Total duration:  34776
11-28 18:16:04.757  5580  5628 I jxcore-log: 
,11-28 18:16:04.759  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-28 18:16:04.759  5580  5628 I jxcore-log: 
,11-28 18:16:04.762  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 18:16:04.762  5580  5628 I jxcore-log: 
11-28 18:16:04.762  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-28 18:16:04.762  5580  5628 I jxcore-log: 
,11-28 18:16:04.763  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 18:16:04.763  5580  5628 I jxcore-log: 
,11-28 18:16:04.764  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-28 18:16:04.764  5580  5628 I jxcore-log: 
,11-28 18:16:04.764  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-28 18:16:04.764  5580  5628 I jxcore-log: 
11-28 18:16:04.765  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-28 18:16:04.765  5580  5628 I jxcore-log: 
11-28 18:16:04.765  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 18:16:04.765  5580  5628 I jxcore-log: 
,11-28 18:16:04.766  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-28 18:16:04.766  5580  5628 I jxcore-log: 
11-28 18:16:04.766  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-28 18:16:04.766  5580  5628 I jxcore-log: 
11-28 18:16:04.766  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 18:16:04.766  5580  5628 I jxcore-log: 
,11-28 18:16:04.766  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-28 18:16:04.766  5580  5628 I jxcore-log: 
11-28 18:16:04.767  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-28 18:16:04.767  5580  5628 I jxcore-log: 
,11-28 18:16:04.767  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 18:16:04.767  5580  5628 I jxcore-log: 
11-28 18:16:04.767  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-28 18:16:04.767  5580  5628 I jxcore-log: 
11-28 18:16:04.767  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 18:16:04.767  5580  5628 I jxcore-log: 
11-28 18:16:04.768  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 18:16:04.768  5580  5628 I jxcore-log: 
11-28 18:16:04.768  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-28 18:16:04.768  5580  5628 I jxcore-log: 
11-28 18:16:04.768  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-28 18:16:04.768  5580  5628 I jxcore-log: 
11-28 18:16:04.768  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 18:16:04.768  5580  5628 I jxcore-log: 
11-28 18:16:04.768  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 18:16:04.768  5580  5628 I jxcore-log: 
11-28 18:16:04.769  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-28 18:16:04.769  5580  5628 I jxcore-log: 
11-28 18:16:04.769  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 18:16:04.769  5580  5628 I jxcore-log: 
11-28 18:16:04.769  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-28 18:16:04.769  5580  5628 I jxcore-log: 
11-28 18:16:04.769  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-28 18:16:04.769  5580  5628 I jxcore-log: 
,11-28 18:16:04.770  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-28 18:16:04.770  5580  5628 I jxcore-log: 
11-28 18:16:04.770  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-28 18:16:04.770  5580  5628 I jxcore-log: 
11-28 18:16:04.770  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-28 18:16:04.770  5580  5628 I jxcore-log: 
11-28 18:16:04.770  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-28 18:16:04.770  5580  5628 I jxcore-log: 
11-28 18:16:04.770  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-28 18:16:04.770  5580  5628 I jxcore-log: 
11-28 18:16:04.772  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 18:16:04.772  5580  5628 I jxcore-log: 
,11-28 18:16:04.772  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-28 18:16:04.772  5580  5628 I jxcore-log: 
11-28 18:16:04.772  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-28 18:16:04.772  5580  5628 I jxcore-log: 
11-28 18:16:04.773  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 18:16:04.773  5580  5628 I jxcore-log: 
11-28 18:16:04.773  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-28 18:16:04.773  5580  5628 I jxcore-log: 
11-28 18:16:04.773  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-28 18:16:04.773  5580  5628 I jxcore-log: 
,11-28 18:16:04.773  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 18:16:04.773  5580  5628 I jxcore-log: 
11-28 18:16:04.773  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-28 18:16:04.773  5580  5628 I jxcore-log: 
11-28 18:16:04.774  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 18:16:04.774  5580  5628 I jxcore-log: 
,11-28 18:16:04.778  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-28 18:16:04.778  5580  5628 I jxcore-log: 
11-28 18:16:04.779  5580  5628 I jxcore-log: 2016-11-28 17:16:04 - WARN testUtils: 'myNameCallback not set!'
11-28 18:16:04.779  5580  5628 I jxcore-log: 
,11-28 18:16:04.780  5580  5580 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
11-28 18:16:04.780  5580  5580 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-28 18:16:04.950   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:16:05.951   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:16:06.826  5580  5628 I jxcore-log: 2016-11-28 17:16:06 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-28 18:16:06.826  5580  5628 I jxcore-log: 
,11-28 18:16:06.828  5580  5628 I jxcore-log: 2016-11-28 17:16:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-28 18:16:06.828  5580  5628 I jxcore-log: 
,11-28 18:16:06.952   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-28 18:16:07.167  5580  5628 I jxcore-log: 2016-11-28 17:16:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-28 18:16:07.167  5580  5628 I jxcore-log: 
,11-28 18:16:07.179  5580  5628 I jxcore-log: 2016-11-28 17:16:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-28 18:16:07.179  5580  5628 I jxcore-log: 
,11-28 18:16:08.010   928  3146 I ActivityManager: Start proc 5862:com.google.android.youtube/u0a75 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,11-28 18:16:08.056  5862  5862 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm64
,11-28 18:16:08.123  5862  5874 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,11-28 18:16:08.186  5862  5874 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,11-28 18:16:08.210  5862  5874 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,11-28 18:16:08.226  5862  5862 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,11-28 18:16:08.261  5580  5628 I jxcore-log: 2016-11-28 17:16:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-28 18:16:08.261  5580  5628 I jxcore-log: 
,11-28 18:16:08.275  5887  5887 I dex2oat : /system/bin/dex2oat -j2 --dex-file=/data/user/0/com.google.android.youtube/cache/ads-904437237.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-904437237.dex
,11-28 18:16:08.308  5887  5887 I dex2oat : dex2oat took 33.054ms (threads: 2) arena alloc=180KB java alloc=37KB native alloc=1258KB free=1045KB
,11-28 18:16:08.329  5862  5862 W InstanceID/Rpc: Found 10012
,11-28 18:16:08.397   928  3843 I ActivityManager: Killing 5454:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-28 18:16:08.424  5580  5628 I jxcore-log: 2016-11-28 17:16:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-28 18:16:08.424  5580  5628 I jxcore-log: 
,11-28 18:16:08.428  5580  5628 I jxcore-log: 2016-11-28 17:16:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-28 18:16:08.428  5580  5628 I jxcore-log: 
,11-28 18:16:08.438  5580  5628 I jxcore-log: 2016-11-28 17:16:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-28 18:16:08.438  5580  5628 I jxcore-log: 
,11-28 18:16:08.441  3571  5942 I VacuumService: Vacuum at: now=1480353368441 tag=VacuumService
,11-28 18:16:08.900  5580  5628 I jxcore-log: 2016-11-28 17:16:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-28 18:16:08.900  5580  5628 I jxcore-log: 
,11-28 18:16:08.938  3653  3815 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-28 18:16:08.939  3653  3815 I Keyboard.Facilitator: flushDynamicLanguageModels()
11-28 18:16:08.944  5580  5628 I jxcore-log: 2016-11-28 17:16:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-28 18:16:08.944  5580  5628 I jxcore-log: 
,11-28 18:16:08.958  5580  5628 I jxcore-log: 2016-11-28 17:16:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-28 18:16:08.958  5580  5628 I jxcore-log: 
,11-28 18:16:08.962  5580  5628 I jxcore-log: 2016-11-28 17:16:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-28 18:16:08.962  5580  5628 I jxcore-log: 
,11-28 18:16:08.976  3571  3571 I ConfigService: onCreate
,11-28 18:16:09.238  5580  5628 I jxcore-log: 2016-11-28 17:16:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-28 18:16:09.238  5580  5628 I jxcore-log: 
,11-28 18:16:09.365  5580  5628 I jxcore-log: 2016-11-28 17:16:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-28 18:16:09.365  5580  5628 I jxcore-log: 
,11-28 18:16:09.749  5580  5628 I jxcore-log: 2016-11-28 17:16:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-28 18:16:09.749  5580  5628 I jxcore-log: 
,11-28 18:16:09.756  5580  5628 I jxcore-log: 2016-11-28 17:16:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-28 18:16:09.756  5580  5628 I jxcore-log: 
,11-28 18:16:09.760  5580  5628 I jxcore-log: 2016-11-28 17:16:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-28 18:16:09.760  5580  5628 I jxcore-log: 
,11-28 18:16:09.764  5580  5628 I jxcore-log: 2016-11-28 17:16:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-28 18:16:09.764  5580  5628 I jxcore-log: 
,11-28 18:16:09.770  5580  5628 I jxcore-log: 2016-11-28 17:16:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-28 18:16:09.770  5580  5628 I jxcore-log: 
,11-28 18:16:09.808  5580  5628 I jxcore-log: 2016-11-28 17:16:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-28 18:16:09.808  5580  5628 I jxcore-log: 
,11-28 18:16:09.815  5580  5628 I jxcore-log: 2016-11-28 17:16:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-28 18:16:09.815  5580  5628 I jxcore-log: 
,11-28 18:16:09.842  5580  5628 I jxcore-log: 2016-11-28 17:16:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-28 18:16:09.842  5580  5628 I jxcore-log: 
,11-28 18:16:09.880  5580  5628 I jxcore-log: 2016-11-28 17:16:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-28 18:16:09.880  5580  5628 I jxcore-log: 
,11-28 18:16:09.888  5580  5628 I jxcore-log: 2016-11-28 17:16:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-28 18:16:09.888  5580  5628 I jxcore-log: 
,11-28 18:16:09.894  5580  5628 I jxcore-log: 2016-11-28 17:16:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-28 18:16:09.894  5580  5628 I jxcore-log: 
,11-28 18:16:09.909  5580  5628 I jxcore-log: 2016-11-28 17:16:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-28 18:16:09.909  5580  5628 I jxcore-log: 
,11-28 18:16:09.924  5580  5628 I jxcore-log: 2016-11-28 17:16:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-28 18:16:09.924  5580  5628 I jxcore-log: 
,11-28 18:16:09.930  5580  5628 I jxcore-log: 2016-11-28 17:16:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-28 18:16:09.930  5580  5628 I jxcore-log: 
,11-28 18:16:09.935  5580  5628 I jxcore-log: 2016-11-28 17:16:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-28 18:16:09.935  5580  5628 I jxcore-log: 
,11-28 18:16:09.949  5580  5628 I jxcore-log: 2016-11-28 17:16:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-28 18:16:09.949  5580  5628 I jxcore-log: 
,11-28 18:16:09.966  5580  5628 I jxcore-log: 2016-11-28 17:16:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-28 18:16:09.966  5580  5628 I jxcore-log: 
,11-28 18:16:09.981  5580  5628 I jxcore-log: 2016-11-28 17:16:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-28 18:16:09.981  5580  5628 I jxcore-log: 
,11-28 18:16:09.992  5580  5628 I jxcore-log: 2016-11-28 17:16:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-28 18:16:09.992  5580  5628 I jxcore-log: 
,11-28 18:16:10.004  5580  5628 I jxcore-log: 2016-11-28 17:16:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-28 18:16:10.004  5580  5628 I jxcore-log: 
,11-28 18:16:10.014  5580  5628 I jxcore-log: 2016-11-28 17:16:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-28 18:16:10.014  5580  5628 I jxcore-log: 
,11-28 18:16:10.028  5580  5628 I jxcore-log: 2016-11-28 17:16:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-28 18:16:10.028  5580  5628 I jxcore-log: 
,11-28 18:16:10.038  5580  5628 I jxcore-log: 2016-11-28 17:16:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-28 18:16:10.038  5580  5628 I jxcore-log: 
,11-28 18:16:10.045  5580  5628 I jxcore-log: 2016-11-28 17:16:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-28 18:16:10.045  5580  5628 I jxcore-log: 
,11-28 18:16:10.066  5580  5628 I jxcore-log: 2016-11-28 17:16:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-28 18:16:10.066  5580  5628 I jxcore-log: 
,11-28 18:16:10.072  5580  5628 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-28 18:16:10.073  5580  5628 I jxcore-log: 2016-11-28 17:16:10 - INFO testUtils: 'BLE multiple advertisement supported'
11-28 18:16:10.073  5580  5628 I jxcore-log: 
,11-28 18:16:10.107  5580  5628 I jxcore-log: 2016-11-28 17:16:10 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-28 18:16:10.107  5580  5628 I jxcore-log: 
,11-28 18:16:10.161  5580  5628 I jxcore-log: 2016-11-28 17:16:10 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-28 18:16:10.161  5580  5628 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-28 18:16:10.161  5580  5628 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-28 18:16:10.161  5580  5628 I jxcore-log: emit@events.js:82:1
11-28 18:16:10.161  5580  5628 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-28 18:16:10.161  5580  5628 I jxcore-log: emit@events.js:82:1''
11-28 18:16:10.161  5580  5628 I jxcore-log: 
,11-28 18:16:10.162  5580  5628 I jxcore-log: 2016-11-28 17:16:10 - DEBUG CoordinatedClient: 'test client failed'
11-28 18:16:10.162  5580  5628 I jxcore-log: 
,11-28 18:16:10.165  5580  5628 I jxcore-log: 2016-11-28 17:16:10 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-28 18:16:10.165  5580  5628 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-28 18:16:10.165  5580  5628 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-28 18:16:10.165  5580  5628 I jxcore-log: emit@events.js:82:1
11-28 18:16:10.165  5580  5628 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-28 18:16:10.165  5580  5628 I jxcore-log: emit@events.js:82:1''
11-28 18:16:10.165  5580  5628 I jxcore-log: 
11-28 18:16:10.165  5580  5628 I jxcore-log: 2016-11-28 17:16:10 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-28 18:16:10.165  5580  5628 I jxcore-log: 
11-28 18:16:10.166  5580  5628 I jxcore-log: 2016-11-28 17:16:10 - ERROR runTests: 'websocket error
11-28 18:16:10.166  5580  5628 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-28 18:16:10.166  5580  5628 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-28 18:16:10.166  5580  5628 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-28 18:16:10.166  5580  5628 I jxcore-log: emit@events.js:82:1
11-28 18:16:10.166  5580  5628 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-28 18:16:10.166  5580  5628 I jxcore-log: emit@events.js:82:1'
11-28 18:16:10.166  5580  5628 I jxcore-log: 
,11-28 18:16:10.716  5945  5945 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-28 18:16:10.730  5945  5945 D AndroidRuntime: CheckJNI is OFF
,11-28 18:16:10.755  5945  5945 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-28 18:16:10.784  5945  5945 I Radio-JNI: register_android_hardware_Radio DONE
,11-28 18:16:10.799  5945  5945 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-28 18:16:10.808   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
11-28 18:16:10.809   928   941 I ActivityManager: Killing 5580:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-28 18:16:10.921   928  3787 I WindowState: WIN DEATH: Window{7b3ed8b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-28 18:16:10.922   928  2965 D WifiService: Client connection lost with reason: 4
,11-28 18:16:10.922   928  3144 D GraphicsStats: Buffer count: 2
,11-28 18:16:10.939   928   941 W ActivityManager: Force removing ActivityRecord{2f49b33 u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-28 18:16:10.950   928   951 I art     : Starting a blocking GC Explicit
,11-28 18:16:10.956   928  3146 W ActivityManager: Spurious death for ProcessRecord{d80667 0:com.test.thalitest/u0a77}, curProc for 5580: null
,11-28 18:16:10.984   928   939 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5580 uid 10077
,11-28 18:16:10.983   939   939 W Binder_2: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[28441]" dev="sockfs" ino=28441 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-28 18:16:10.983   939   939 W Binder_2: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[28441]" dev="sockfs" ino=28441 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-28 18:16:11.009  3934  3934 W ThreadPoolDumper: Queue length for executor AudioRouter with 1 threads is now 8. Perhaps some tasks are too long, or the pool is too small.
,11-28 18:16:11.033   928   951 I art     : Explicit concurrent mark sweep GC freed 15680(974KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.672ms total 82.954ms
,11-28 18:16:11.049  3934  5957 I MicroRecognitionRnrImpl: Starting detection.
,11-28 18:16:11.050  3934  5958 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@a8cb3ba
,11-28 18:16:11.052   511  5960 I AudioFlinger: AudioFlinger's thread 0xf2000000 ready to run
,11-28 18:16:11.056   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
11-28 18:16:11.057   511  2986 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-28 18:16:11.058  3934  5958 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@a8cb3ba
,11-28 18:16:11.059  5945  5945 I art     : System.exit called, status: 0
,11-28 18:16:11.059  5945  5945 I AndroidRuntime: VM exiting with result code 0.
,11-28 18:16:11.068   511  5960 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
11-28 18:16:11.068   511  5960 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-28 18:16:11.069   511  5960 I ACDB-LOADER: ACDB AFE returned = -19
11-28 18:16:11.069   511  5960 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-28 18:16:11.069   511  5960 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-28 18:16:11.069   511  5960 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-28 18:16:11.076   928   951 I ActivityManager: Start proc 5962:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-28 18:16:11.077   511  5960 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-28 18:16:11.080   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-28 18:16:11.089  5701  5701 D BluetoothMapAppObserver: onReceive
11-28 18:16:11.089  5701  5701 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-28 18:16:11.090  4089  4173 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-28 18:16:11.099  3653  3653 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-28 18:16:11.100   928  2926 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-28 18:16:11.117  3653  5975 I Keyboard.Facilitator.DecoderInitializer: run()
,11-28 18:16:11.120  3389  5976 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-28 18:16:11.132  3653  5975 I Decoder : createOrResetDecoder
,11-28 18:16:11.159  3770  3770 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-28 18:16:11.167  3934  3934 I HotwordWorkerImpl: onReady
,11-28 18:16:11.175   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-28 18:16:11.189  3653  5975 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-28 18:16:11.201  3571  3571 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-28 18:16:11.201  3571  3571 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-28 18:16:11.206    64    64 W kworker/2:2: type=1400 audit(0.0:130): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-28 18:16:11.220  3953  5983 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-28 18:16:11.221  3953  5983 D AccountUtils: Clearing selected account for com.test.thalitest
,11-28 18:16:11.223    64    64 W kworker/2:2: type=1400 audit(0.0:131): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-28 18:16:11.232  3953  5983 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-28 18:16:11.233    64    64 W kworker/2:2: type=1400 audit(0.0:132): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-28 18:16:11.249  3953  5983 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-28 18:16:11.249  3953  5983 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-28 18:16:11.249  3953  5983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-28 18:16:11.249  3953  5983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-28 18:16:11.249  3953  5983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-28 18:16:11.249  3953  5983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-28 18:16:11.249  3953  5983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-28 18:16:11.249  3953  5983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-28 18:16:11.249  3953  5983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-28 18:16:11.249  3953  5983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-28 18:16:11.249  3953  5983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-28 18:16:11.249  3953  5983 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-28 18:16:11.249  3953  5983 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-28 18:16:11.249  3953  5983 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-28 18:16:11.249  3953  5983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-28 18:16:11.249  3953  5983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-28 18:16:11.249  3953  5983 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-28 18:16:11.249  3953  5983 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-28 18:16:11.249  3953  5983 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 18:16:11.249  3953  5983 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-28 18:16:11.249  3953  5983 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-28 18:16:11.249  3953  3953 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-28 18:16:11.249  3953  3953 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
11-28 18:16:11.249  3953  5983 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-28 18:16:11.249  3953  5983 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-28 18:16:11.249  3953  5983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-28 18:16:11.249  3953  5983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-28 18:16:11.249  3953  5983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-28 18:16:11.249  3953  5983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-28 18:16:11.249  3953  5983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-28 18:16:11.249  3953  5983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-28 18:16:11.249  3953  5983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-28 18:16:11.249  3953  5983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-28 18:16:11.249  3953  5983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-28 18:16:11.249  3953  5983 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-28 18:16:11.249  3953  5983 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-28 18:16:11.249  3953  5983 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-28 18:16:11.249  3953  5983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-28 18:16:11.249  3953  5983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-28 18:16:11.249  3953  5983 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-28 18:16:11.249  3953  5983 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-28 18:16:11.249  3953  5983 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 18:16:11.249  3953  5983 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-28 18:16:11.249  3953  5983 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-28 18:16:11.251  3953  5988 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/metrics.db'.
11-28 18:16:11.251  3953  5988 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-28 18:16:11.251  3953  5988 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-28 18:16:11.251  3953  5988 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-28 18:16:11.251  3953  5988 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-28 18:16:11.251  3953  5988 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-28 18:16:11.251  3953  5988 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-28 18:16:11.251  3953  5988 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-28 18:16:11.251  3953,  5988 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-28 18:16:11.251  3953  5988 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-28 18:16:11.251  3953  5988 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-28 18:16:11.251  3953  5988 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-28 18:16:11.251  3953  5988 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-28 18:16:11.251  3953  5988 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-28 18:16:11.251  3953  5988 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-28 18:16:11.251  3953  5988 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
11-28 18:16:11.251  3953  5988 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-28 18:16:11.251  3953  5988 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
11-28 18:16:11.251  3953  5988 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-28 18:16:11.251  3953  5988 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-28 18:16:11.251  3953  5988 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 18:16:11.251  3953  5988 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-28 18:16:11.251  3953  5988 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-28 18:16:11.251  3953  5983 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
11-28 18:16:11.251  3953  5988 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
11-28 18:16:11.251  3953  5988 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-28 18:16:11.251  3953  5988 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-28 18:16:11.251  3953  5988 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-28 18:16:11.251  3953  5988 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-28 18:16:11.251  3953  5988 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-28 18:16:11.251  3953  5988 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-28 18:16:11.251  3953  5988 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-28 18:16:11.251  3953  5988 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-28 18:16:11.251  3953  5988 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-28 18:16:11.251  3953  5988 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-28 18:16:11.251  3953  5988 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-28 18:16:11.251  3953  5988 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-28 18:16:11.251  3953  5988 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-28 18:16:11.251  3953  5988 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-28 18:16:11.251  3953  5988 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
11-28 18:16:11.251  3953  5988 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-28 18:16:11.251  3953  5988 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
11-28 18:16:11.251  3953  5988 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-28 18:16:11.251  3953  5988 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-28 18:16:11.251  3953  5988 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 18:16:11.251  3953  5988 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-28 18:16:11.251  3953  5988 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-28 18:16:11.253  3953  5988 W SQLiteOpenHelper: Opened metrics.db in read-only mode
11-28 18:16:11.253  3953  5988 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
11-28 18:16:11.253  3953  5988 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
11-28 18:16:11.254  3953  5988 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
11-28 18:16:11.255  3953  5988 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
11-28 18:16:11.255  3953  3953 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-28 18:16:11.255  3953  3953 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
--------- beginning of crash
11-28 18:16:11.257  3953  5988 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
11-28 18:16:11.257  3953  5988 E AndroidRuntime: Process: com.google.android.gms, PID: 3953
11-28 18:16:11.257  3953  5988 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
11-28 18:16:11.257  3953  5988 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-28 18:16:11.257  3953  5988 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-28 18:16:11.257  3953  5988 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-28 18:16:11.257  3953  5988 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-28 18:16:11.257  3953  5988 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-28 18:16:11.257  3953  5988 E AndroidRuntime: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
11-28 18:16:11.257  3953  5988 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-28 18:16:11.257  3953  5988 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-28 18:16:11.257  3953  5988 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 18:16:11.257  3953  5988 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-28 18:16:11.257  3953  5988 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-28 18:16:11.265   928  5993 E DropBoxManagerService: Can't write: system_app_crash
11-28 18:16:11.265   928  5993 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
11-28 18:16:11.265   928  5993 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-28 18:16:11.265   928  5993 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-28 18:16:11.265   928  5993 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-28 18:16:11.265   928  5993 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-28 18:16:11.265   928  5993 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-28 18:16:11.265   928  5993 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-28 18:16:11.265   928  5993 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-28 18:16:11.265   928  5993 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-28 18:16:11.265   928  5993 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-28 18:16:11.265   928  5993 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-28 18:16:11.265   928  5993 E DropBoxManagerService: 	... 5 more
11-28 18:16:11.275  3389  5976 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM voicemail_status WHERE (((source_package = 'com.test.thalitest')))] disk I/O error
11-28 18:16:11.280   407   407 W Binder_2: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[15870]" dev="sockfs" ino=15870 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-28 18:16:11.280   407   407 W Binder_2: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[15870]" dev="sockfs" ino=15870 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-28 18:16:11.283   405   405 W Binder_1: type=1400 audit(0.0:135): avc: denied { ioctl } for path="socket:[34954]" dev="sockfs" ino=34954 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-28 18:16:11.285  3389  5976 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-28 18:16:11.285  3389  5976 E AndroidRuntime: Process: android.process.acore, PID: 3389
11-28 18:16:11.285  3389  5976 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-28 18:16:11.285  3389  5976 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-28 18:16:11.285  3389  5976 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-28 18:16:11.285  3389  5976 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-28 18:16:11.285  3389  5976 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-28 18:16:11.285  3389  5976 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-28 18:16:11.285  3389  5976 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-28 18:16:11.285  3389  5976 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailStatusTable.delete(VoicemailStatusTable.java:80)
11-28 18:16:11.285  3389  5976 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-28 18:16:11.285  3389  5976 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-28 18:16:11.285  3389  5976 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-28 18:16:11.285  3389  5976 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:52)
11-28 18:16:11.285  3389  5976 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-28 18:16:11.285  3389  5976 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-28 18:16:11.285  3389  5976 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 18:16:11.285  3389  5976 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-28 18:16:11.285  3389  5976 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-28 18:16:11.285   928  5994 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-28 18:16:11.283   405   405 W Binder_1: type=1400 audit(0.0:136): avc: denied { ioctl } for path="socket:[34954]" dev="sockfs" ino=34954 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-28 18:16:11.288  3934  5992 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,11-28 18:16:11.312   928  5995 E DropBoxManagerService: Can't write: system_app_crash
11-28 18:16:11.312   928  5995 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
11-28 18:16:11.312   928  5995 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-28 18:16:11.312   928  5995 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-28 18:16:11.312   928  5995 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-28 18:16:11.312   928  5995 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-28 18:16:11.312   928  5995 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-28 18:16:11.312   928  5995 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-28 18:16:11.312   928  5995 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-28 18:16:11.312   928  5995 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-28 18:16:11.312   928  5995 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-28 18:16:11.312   928  5995 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-28 18:16:11.312   928  5995 E DropBoxManagerService: 	... 5 more
11-28 18:16:11.321  3653  5975 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
11-28 18:16:11.323   928  3847 I ActivityManager: Start proc 5998:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
11-28 18:16:11.324  3653  5975 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,11-28 18:16:11.324  3653  5975 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
11-28 18:16:11.327  3653  5975 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
11-28 18:16:11.327  3653  5975 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
11-28 18:16:11.328  3653  5975 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-28 18:16:11.328  3653  5975 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,11-28 18:16:11.329  3653  5975 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
11-28 18:16:11.329  3653  5975 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,11-28 18:16:11.329  3653  5975 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-28 18:16:11.329  3653  5975 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-28 18:16:11.329  3653  5975 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-28 18:16:11.330  3653  5975 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
11-28 18:16:11.334  3953  5990 W BaseAppContext: Using Auth Proxy for data requests.
,11-28 18:16:11.338  3953  5990 W BaseAppContext: Using Auth Proxy for data requests.
,11-28 18:16:11.344  3953  5983 E GMPM-SVC: Scheduler not initialized or shutdown. Not logging error/warn.
,11-28 18:16:11.350  3953  6005 I GMPM-SVC: App measurement is starting up
,11-28 18:16:11.354  3953  6005 E GMPM-SVC: AppMeasurementService not registered/enabled
,11-28 18:16:11.354  3953  6005 E GMPM-SVC: Uploading is not possible. App measurement disabled
11-28 18:16:11.354   928   941 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{25924ce u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{b15b1d0 3953 com.google.android.gms/10012/u0 remote:590bd93}: process crashing
,11-28 18:16:11.358  3953  3953 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,11-28 18:16:11.360  3953  6005 E SQLiteLog: (14) cannot open file at line 31278 of [2ef4f3a5b1]
,11-28 18:16:11.360  3953  6005 E SQLiteLog: (14) os_unix.c:31278: (2) open(/data/user/0/com.google.android.gms/databases/google_app_measurement2.db) - 
11-28 18:16:11.361  3953  6005 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_app_measurement2.db'.
11-28 18:16:11.361  3953  6005 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
11-28 18:16:11.361  3953  6005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-28 18:16:11.361  3953  6005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-28 18:16:11.361  3953  6005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-28 18:16:11.361  3953  6005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-28 18:16:11.361  3953  6005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-28 18:16:11.361  3953  6005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-28 18:16:11.361  3953  6005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-28 18:16:11.361  3953  6005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-28 18:16:11.361  3953  6005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-28 18:16:11.361  3953  6005 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-28 18:16:11.361  3953  6005 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-28 18:16:11.361  3953  6005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-28 18:16:11.361  3953  6005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-28 18:16:11.361  3953  6005 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1022)
11-28 18:16:11.361  3953  6005 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.j(SourceFile:271)
11-28 18:16:11.361  3953  6005 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.d(SourceFile:877)
11-28 18:16:11.361  3953  6005 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ao.run(SourceFile:397)
11-28 18:16:11.361  3953  6005 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-28 18:16:11.361  3953  6005 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-28 18:16:11.361  3953  6005 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.al.run(SourceFile:257)
,11-28 18:16:11.361  3953  6005 E GMPM-SVC: Opening the database failed, dropping and recreating it
11-28 18:16:11.362  3953  6005 E SQLiteLog: (14) cannot open file at line 31278 of [2ef4f3a5b1]
11-28 18:16:11.362  3953  6005 E SQLiteLog: (14) os_unix.c:31278: (2) open(/data/user/0/com.google.android.gms/databases/google_app_measurement2.db) - 
11-28 18:16:11.362  3953  6005 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_app_measurement2.db'.
11-28 18:16:11.362  3953  6005 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
11-28 18:16:11.362  3953  6005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-28 18:16:11.362  3953  6005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-28 18:16:11.362  3953  6005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-28 18:16:11.362  3953  6005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-28 18:16:11.362  3953  6005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-28 18:16:11.362  3953  6005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-28 18:16:11.362  3953  6005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-28 18:16:11.362  3953  6005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-28 18:16:11.362  3953  6005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-28 18:16:11.362  3953  6005 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-28 18:16:11.362  3953  6005 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-28 18:16:11.362  3953  6005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-28 18:16:11.362  3953  6005 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-28 18:16:11.362  3953  6005 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
11-28 18:16:11.362  3953  6005 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.j(SourceFile:271)
11-28 18:16:11.362  3953  6005 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.d(SourceFile:877)
11-28 18:16:11.362  3953  6005 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ao.run(SourceFile:397)
11-28 18:16:11.362  3953  6005 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-28 18:16:11.362  3953  6005 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-28 18:16:11.362  3953  6005 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.al.run(SourceFile:257)
11-28 18:16:11.363  3953  6005 E GMPM-SVC: Failed to open freshly created database: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
11-28 18:16:11.363  3953  6005 W GMPM-SVC: Error opening database: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
,11-28 18:16:11.364  3953  6005 E GMPM-SVC: Error deleting application data. appId, error: com.test.thalitest, android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
,11-28 18:16:11.367   928  3406 D ConnectivityService: listenForNetwork for Listen from uid/pid:10012/3953 for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,11-28 18:16:11.414  3953  5987 W DriveInitializer: Awaiting to be initialized
,11-28 18:16:11.415  3953  6009 W DriveInitializer: Background init thread started
,11-28 18:16:11.611   382   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
