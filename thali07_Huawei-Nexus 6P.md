#### Test 899757340363162_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-25 13:46:03.344   928  5326 D NetlinkSocketObserver: NeighborEvent{elapsedMs=152904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-25 13:46:03.815  5564  5564 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-25 13:46:03.821  5564  5564 D AndroidRuntime: CheckJNI is OFF
11-25 13:46:03.852  5564  5564 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-25 13:46:03.888  5564  5564 I Radio-JNI: register_android_hardware_Radio DONE
11-25 13:46:03.903  5564  5564 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-25 13:46:03.907   928  3390 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-25 13:46:03.926  5564  5564 D AndroidRuntime: Shutting down VM
11-25 13:46:03.931  3937  4353 W SearchService: Abort, client detached.
11-25 13:46:03.942  3937  4198 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@82bbe36
11-25 13:46:03.941  3937  3937 I HotwordDetector: Closing mic
11-25 13:46:03.942  3937  4206 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-25 13:46:03.961   928  3780 I ActivityManager: Start proc 5573:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-25 13:46:04.005   513  4208 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-25 13:46:04.006   513  4208 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-25 13:46:04.011   513  4208 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-25 13:46:04.011   513  4208 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-25 13:46:04.012   513  2966 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-25 13:46:04.013  3937  4199 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-25 13:46:04.013  3937  4205 I MicroRecognitionRnrImpl: Detection finished
11-25 13:46:04.066  5573  5573 I CordovaLog: Changing log level to DEBUG(3)
11-25 13:46:04.066  5573  5573 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-25 13:46:04.066  5573  5573 D CordovaActivity: CordovaActivity.onCreate()
11-25 13:46:04.072  5573  5573 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-25 13:46:04.094  5573  5573 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-25 13:46:04.159  5573  5573 I LibraryLoader: Time to load native libraries: 61 ms (timestamps 3659-3720)
,11-25 13:46:04.159  5573  5573 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-25 13:46:04.189  5573  5573 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a56fa9d}
,11-25 13:46:04.190  5573  5573 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-25 13:46:04.190  5573  5573 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-25 13:46:04.193  5573  5573 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-25 13:46:04.194  5573  5573 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-25 13:46:04.247  5573  5573 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-25 13:46:04.256  5573  5573 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-25 13:46:04.256  5573  5573 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-25 13:46:04.256  5573  5573 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-25 13:46:04.256  5573  5573 I Adreno  : Build Date                       : 12/06/15
11-25 13:46:04.256  5573  5573 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-25 13:46:04.256  5573  5573 I Adreno  : Local Branch                     : mybranch17112971
11-25 13:46:04.256  5573  5573 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-25 13:46:04.256  5573  5573 I Adreno  : Remote Branch                    : NONE
11-25 13:46:04.256  5573  5573 I Adreno  : Reconstruct Branch               : NOTHING
,11-25 13:46:04.287   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d3a9423:true
,11-25 13:46:04.322   415   415 W Binder_2: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[24559]" dev="sockfs" ino=24559 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 13:46:04.322   415   415 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[24559]" dev="sockfs" ino=24559 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 13:46:04.332  5573  5573 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-25 13:46:04.339  5573  5573 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-25 13:46:04.343  5573  5573 D PluginManager: init()
,11-25 13:46:04.345  5573  5573 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-25 13:46:04.360  5573  5573 D CordovaActivity: Started the activity.
,11-25 13:46:04.360  5573  5573 D CordovaActivity: Resumed the activity.
,11-25 13:46:04.362   836   836 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32470]" dev="sockfs" ino=32470 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 13:46:04.364  5573  5610 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-25 13:46:04.362   836   836 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32470]" dev="sockfs" ino=32470 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 13:46:04.367  5573  5597 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-25 13:46:04.365  3774  3774 W Binder_A: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[14141]" dev="sockfs" ino=14141 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-25 13:46:04.365  3774  3774 W Binder_A: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[14141]" dev="sockfs" ino=14141 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-25 13:46:04.386  5573  5610 I OpenGLRenderer: Initialized EGL, version 1.4
,11-25 13:46:04.456   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +520ms
,11-25 13:46:04.455   938   938 W Binder_1: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32477]" dev="sockfs" ino=32477 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-25 13:46:04.455   938   938 W Binder_1: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32477]" dev="sockfs" ino=32477 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-25 13:46:04.458  3744  3744 W Binder_9: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32476]" dev="sockfs" ino=32476 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-25 13:46:04.458  3744  3744 W Binder_9: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32476]" dev="sockfs" ino=32476 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-25 13:46:04.461  3637  3637 I Keyboard.Facilitator: onFinishInput()
,11-25 13:46:04.481  5573  5573 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-25 13:46:04.506  5573  5573 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5573
,11-25 13:46:04.598  5573  5573 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-25 13:46:04.766  5573  5612 D jxcore_app_log: JniHelper::setJavaVM(0xf51bc000), pthread_self() = -582747856
,11-25 13:46:04.771  5573  5612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-25 13:46:04.771  5573  5612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-25 13:46:04.771  5573  5612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-25 13:46:04.771  5573  5612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-25 13:46:04.771  5573  5612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-25 13:46:04.771  5573  5612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1263b1b added. We now have 1 listener(s)
,11-25 13:46:04.774  5573  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-25 13:46:04.774  5573  5612 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-25 13:46:04.774  5573  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:46:04.775  5573  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-25 13:46:04.777  5573  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-25 13:46:04.777  5573  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-25 13:46:04.777  5573  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-25 13:46:04.777  5573  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-25 13:46:04.777  5573  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-25 13:46:04.777  5573  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-25 13:46:04.777  5573  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-25 13:46:04.777  5573  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-25 13:46:04.777  5573  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-25 13:46:04.777  5573  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-25 13:46:04.777  5573  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-25 13:46:04.777  5573  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-25 13:46:04.777  5573  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-25 13:46:04.777  5573  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-25 13:46:04.777  5573  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a2c5f6 added. We now have 1 listener(s)
11-25 13:46:04.777  5573  5612 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 13:46:04.781   928  2945 D WifiService: New client listening to asynchronous messages
,11-25 13:46:04.781  5573  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 13:46:04.782  5573  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-25 13:46:04.782  5573  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
,11-25 13:46:04.782  5573  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-25 13:46:04.782  5573  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-25 13:46:04.782  5573  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-25 13:46:04.782  5573  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
11-25 13:46:04.782   928  3636 I ActivityManager: Killing 5008:com.google.android.apps.maps/u0a58 (adj 15): empty #17
11-25 13:46:04.783  5573  5612 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-25 13:46:04.796  5573  5573 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-25 13:46:04.831   928  3636 I ActivityManager: Killing 5236:com.android.settings/1000 (adj 15): empty #18
,11-25 13:46:04.872  5573  5573 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,11-25 13:46:04.872  5573  5573 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-25 13:46:05.429  5573  5620 W jxcore-log: Initializing JXcore engine
,11-25 13:46:05.429  5573  5620 W jxcore-log: JXcore engine is ready
,11-25 13:46:05.452  5620  5620 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12597 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
11-25 13:46:05.452  5620  5620 W Thread-57: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[1854]" dev="sockfs" ino=1854 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,11-25 13:46:05.452  5620  5620 W Thread-57: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-25 13:46:05.452  5620  5620 W Thread-57: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32452]" dev="sockfs" ino=32452 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
11-25 13:46:05.461  5573  5620 W jxcore-log: Starting JXcore engine
,11-25 13:46:05.510  5573  5620 W jxcore-log: Platform android
11-25 13:46:05.510  5573  5620 W jxcore-log: 
,11-25 13:46:05.510  5573  5620 W jxcore-log: Process ARCH arm
11-25 13:46:05.510  5573  5620 W jxcore-log: 
,11-25 13:46:05.692  5573  5620 I jxcore-log: JXcore Cordova bridge is ready!
11-25 13:46:05.692  5573  5620 I jxcore-log: 
,11-25 13:46:05.693  5573  5620 W jxcore-log: JXcore engine is started
,11-25 13:46:05.710  5573  5612 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-25 13:46:05.718  5573  5573 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,11-25 13:46:05.718  5573  5573 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-25 13:46:07.708  3924  4400 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-25 13:46:14.051  3937  5621 W CronetSyncConnectionRcs: Upload content type not set.
,11-25 13:46:15.400   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:46:15.448  5573  5620 I jxcore-log: 2016-11-25 12:46:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-25 13:46:15.448  5573  5620 I jxcore-log: 
,11-25 13:46:15.449  5573  5620 I jxcore-log: 2016-11-25 12:46:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-25 13:46:15.449  5573  5620 I jxcore-log: 
,11-25 13:46:15.455  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-25 13:46:15.455  5573  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 13:46:15.455  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:46:15.455  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:46:15.455  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:46:15.455  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 13:46:15.455  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 13:46:15.455  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 13:46:15.455  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 13:46:15.455  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-25 13:46:15.456  5573  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-25 13:46:15.458  5573  5620 I jxcore-log: 2016-11-25 12:46:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-25 13:46:15.458  5573  5620 I jxcore-log: 
,11-25 13:46:15.461  5573  5620 I jxcore-log: 2016-11-25 12:46:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-25 13:46:15.461  5573  5620 I jxcore-log: 
,11-25 13:46:15.707  5573  5620 I jxcore-log: 2016-11-25 12:46:15 - DEBUG UnitTest_app: 'Running unit tests'
11-25 13:46:15.707  5573  5620 I jxcore-log: 
,11-25 13:46:15.708  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:46:15.708  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c88203 added. We now have 2 listener(s)
11-25 13:46:15.709  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:46:15.709  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:46:15.709  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:46:15.709  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 13:46:15.709  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4e7580 added. We now have 2 listener(s)
11-25 13:46:15.709  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 13:46:15.710  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 13:46:15.711  5573  5620 D executeNativeTests: Running unit tests
,11-25 13:46:15.752  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-25 13:46:15.753  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb68129 added. We now have 3 listener(s)
11-25 13:46:15.753  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:46:15.753  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-25 13:46:15.753  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:46:15.753  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 13:46:15.754  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae added. We now have 3 listener(s)
,11-25 13:46:15.754  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:46:15.754  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 13:46:15.756  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-25 13:46:15.757  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 13:46:15.757  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-25 13:46:15.757  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 13:46:15.757  5573  5620 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-25 13:46:15.758  5573  5620 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-25 13:46:15.758  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-25 13:46:15.758  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 13:46:15.758  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 13:46:15.758  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 13:46:15.758  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:46:15.758  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:46:15.758  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:46:15.759  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:46:15.759  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:46:15.759  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 13:46:15.760  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb68129 removed from the list
11-25 13:46:15.760  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:46:15.760  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae removed from the list
11-25 13:46:15.760  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:46:15.760  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:15.760  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:15.761  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:15.761  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:15.761  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:15.761  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 13:46:15.761  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:46:15.761  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:46:15.761  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:15.762  5573  5620 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-25 13:46:15.763  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:46:15.763  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:46:15.763  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:46:15.763  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:46:15.763  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:46:15.763  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb68129 not in the list
11-25 13:46:15.763  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:46:15.763  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:15.763  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 13:46:15.763  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:15.763  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:15.764  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:15.764  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:15.764  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:15.764  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:46:15.764  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:46:15.764  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:46:15.764  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
,11-25 13:46:15.767  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-25 13:46:15.767  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-25 13:46:15.767  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-25 13:46:15.767  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-25 13:46:15.767  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,11-25 13:46:15.767  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-25 13:46:15.767  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-25 13:46:15.767  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,11-25 13:46:15.767  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-25 13:46:15.767  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-25 13:46:15.767  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,11-25 13:46:15.767  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-25 13:46:15.767  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-25 13:46:15.767  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-25 13:46:15.767  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-25 13:46:15.767  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-25 13:46:15.767  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-25 13:46:15.767  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-25 13:46:15.767  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-25 13:46:15.768  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,11-25 13:46:15.768  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-25 13:46:15.768  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-25 13:46:15.768  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,11-25 13:46:15.768  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-25 13:46:15.768  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-25 13:46:15.768  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-25 13:46:15.768  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-25 13:46:15.768  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-25 13:46:15.768  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-25 13:46:15.768  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-25 13:46:15.768  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,11-25 13:46:15.768  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:46:15.768  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:46:15.768  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:46:15.768  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 13:46:15.768  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:46:15.768  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb68129 not in the list
,11-25 13:46:15.768  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:46:15.768  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:15.768  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:46:15.768  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:15.768  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:15.769  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:15.769  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:15.769  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:15.769  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:46:15.769  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:46:15.769  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:46:15.769  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:15.770  5573  5620 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-25 13:46:15.771  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 13:46:15.771  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-25 13:46:15.789  5573  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 13:46:15.789  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:46:15.789  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:46:15.789  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:46:15.789  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 13:46:15.789  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 13:46:15.789  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 13:46:15.789  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 13:46:15.789  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-25 13:46:15.790  5573  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 13:46:15.790  5573  5620 D io.jxcore.node.ConnectivityMonitor: start: OK
11-25 13:46:15.790  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:46:15.791  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 13:46:15.791  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 13:46:15.791  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 13:46:15.791  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-25 13:46:15.792  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 13:46:15.793  5573  5620 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 13:46:15.793  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 13:46:15.794  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:46:15.797  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:15.798  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 13:46:15.798  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:46:15.799  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 13:46:15.799  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 13:46:15.799  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-25 13:46:15.800  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-25 13:46:15.801  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-25 13:46:15.801  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:15.802  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 13:46:15.802  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 13:46:15.802  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 13:46:15.802  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 13:46:15.802  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:15.803  5573  5620 D BluetoothAdapter: STATE_ON
11-25 13:46:15.805  4617  4637 D BtGatt.GattService: registerClient() - UUID=dfbace2f-1aca-4786-b01c-912bff93d897
11-25 13:46:15.805  4617  4691 D BtGatt.GattService: onClientRegistered() - UUID=dfbace2f-1aca-4786-b01c-912bff93d897, clientIf=5
11-25 13:46:15.806  5573  5584 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 13:46:15.808  4617  4850 D BtGatt.GattService: start scan with filters
11-25 13:46:15.813  4617  4694 D BtGatt.ScanManager: handling starting scan
11-25 13:46:15.813  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 13:46:15.814  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:15.814  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 13:46:15.814  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:15.814  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 13:46:15.814  5573  5573 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 13:46:15.814  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:46:15.814  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 13:46:15.814  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 13:46:15.815  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 13:46:15.815  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:46:15.815  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:15.815  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 13:46:15.815  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:46:15.815  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:15.815  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 13:46:15.815  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:15.816  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:15.816  4617  4694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7222f0c
11-25 13:46:15.816  5573  5620 I io.jxcore.node.ConnectionHelper: start: OK
11-25 13:46:15.817  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:46:15.821  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:46:15.821  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 13:46:15.821  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:46:15.821  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 13:46:15.821  5573  5573 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 13:46:15.824  4617  4691 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 13:46:15.824  4617  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:46:15.824  4617  4694 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 13:46:15.830  4617  4691 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 13:46:15.830  4617  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:46:15.831  4617  4694 D BtGatt.ScanManager: Starting BLE batch scan
11-25 13:46:15.831  4617  4694 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-25 13:46:15.843  4617  4691 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 13:46:15.843  4617  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:46:15.850  4617  4691 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 13:46:15.850  4617  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:46:16.323  5573  5573 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-25 13:46:16.323  5573  5573 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:46:16.324  5573  5573 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-25 13:46:16.401   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:46:17.402   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:46:18.403   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:46:19.076   928  5326 D NetlinkSocketObserver: NeighborEvent{elapsedMs=168637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 13:46:19.404   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:46:20.405   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-25 13:46:20.820  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 13:46:20.820  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-25 13:46:20.820  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-25 13:46:20.821  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-25 13:46:20.821  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-25 13:46:20.821  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 13:46:20.821  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-25 13:46:20.821  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-25 13:46:20.821  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:20.822  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 13:46:20.822  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 13:46:20.822  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:20.823  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:20.823  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:20.823  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 13:46:20.823  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:20.824  5573  5620 D BluetoothAdapter: STATE_ON
11-25 13:46:20.825  4617  4639 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 13:46:20.825  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 13:46:20.826  4617  4694 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 13:46:20.827  5573  5620 D BluetoothAdapter: STATE_ON
,11-25 13:46:20.829  4617  4637 D BtGatt.GattService: stopScan() - queue size =1
11-25 13:46:20.831  4617  4850 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 13:46:20.832  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-25 13:46:20.832  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:20.832  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 13:46:20.832  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:20.833  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:20.833  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:20.833  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:20.834  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 13:46:20.834  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:20.834  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:20.834  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:20.835  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 13:46:20.835  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 13:46:20.837  4617  4617 D BtGatt.ScanManager: awakened up at time 170398
11-25 13:46:20.837  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:46:20.837  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:20.839  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:20.839  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-25 13:46:20.840  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:20.840  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:20.840  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:46:20.840  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:46:20.840  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-25 13:46:20.840  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:46:20.840  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:46:20.840  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:46:20.840  5573  5573 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 13:46:20.841  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb68129 not in the list
11-25 13:46:20.841  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:46:20.841  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-25 13:46:20.841  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:20.841  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:46:20.841  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 13:46:20.841  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 13:46:20.841  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,11-25 13:46:20.841  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:46:20.841  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 13:46:20.841  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:46:20.841  5573  5573 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:46:20.842  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
,11-25 13:46:20.842  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:46:20.844  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:46:20.844  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:46:20.844  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-25 13:46:20.860  4617  4691 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-25 13:46:20.860  4617  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:46:20.861  4617  4691 D BtGatt.GattService: current time is 170422127842
11-25 13:46:20.861  4617  4691 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -78, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -89, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -90, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -81, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -88, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -90, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-25 13:46:20.863  4617  4691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-25 13:46:20.866  4617  4691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-25 13:46:20.866  4617  4691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-25 13:46:20.866  4617  4691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-25 13:46:20.867  4617  4691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-25 13:46:20.867  4617  4691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-25 13:46:20.875  4617  4691 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 13:46:20.875  4617  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:46:20.875  4617  4694 D BtGatt.ScanManager: stopping BLe Batch
,11-25 13:46:20.884  4617  4691 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-25 13:46:20.884  4617  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:46:20.884  4617  4694 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 13:46:20.892  4617  4691 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-25 13:46:20.892  4617  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:46:21.343  5573  5573 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 13:46:22.465   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-25 13:46:25.844  5573  5620 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-25 13:46:25.849  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-25 13:46:25.850  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-25 13:46:25.863  5573  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 13:46:25.863  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:46:25.863  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:46:25.863  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:46:25.863  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 13:46:25.863  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 13:46:25.863  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 13:46:25.863  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 13:46:25.863  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-25 13:46:25.868  5573  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 13:46:25.868  5573  5620 D io.jxcore.node.ConnectivityMonitor: start: OK
11-25 13:46:25.868  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:46:25.869  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 13:46:25.869  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 13:46:25.869  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 13:46:25.869  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-25 13:46:25.875  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:46:25.878  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 13:46:25.878  5573  5620 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-25 13:46:25.878  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 13:46:25.880  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:46:25.886  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:25.887  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 13:46:25.888  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-25 13:46:25.888  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 13:46:25.888  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-25 13:46:25.893  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:25.893  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 13:46:25.893  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-25 13:46:25.893  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 13:46:25.893  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 13:46:25.893  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:25.895  5573  5620 D BluetoothAdapter: STATE_ON
,11-25 13:46:25.900  4617  4842 D BtGatt.GattService: registerClient() - UUID=8ef895f3-3b68-4ff5-9d8b-01078215ef06
,11-25 13:46:25.901  4617  4691 D BtGatt.GattService: onClientRegistered() - UUID=8ef895f3-3b68-4ff5-9d8b-01078215ef06, clientIf=5
,11-25 13:46:25.901  5573  5584 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 13:46:25.901  4617  4637 D BtGatt.GattService: start scan with filters
,11-25 13:46:25.906  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 13:46:25.906  4617  4694 D BtGatt.ScanManager: handling starting scan
11-25 13:46:25.906  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:25.906  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 13:46:25.906  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:25.906  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 13:46:25.907  5573  5573 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 13:46:25.907  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:46:25.907  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 13:46:25.907  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 13:46:25.907  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:46:25.907  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 13:46:25.907  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:46:25.908  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-25 13:46:25.908  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 13:46:25.909  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:25.915  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:25.916  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-25 13:46:25.917  4617  4691 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 13:46:25.917  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:25.917  4617  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:46:25.917  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:25.917  4617  4694 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 13:46:25.917  5573  5620 I io.jxcore.node.ConnectionHelper: start: OK
11-25 13:46:25.917  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:46:25.921  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:46:25.921  5573  5620 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-25 13:46:25.921  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-25 13:46:25.921  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-25 13:46:25.921  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:46:25.921  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-25 13:46:25.921  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:46:25.921  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-25 13:46:25.923  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:46:25.923  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:46:25.924  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 13:46:25.924  5573  5573 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-25 13:46:25.924  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 13:46:25.924  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:25.924  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 13:46:25.924  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 13:46:25.924  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:25.924  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:25.925  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:25.925  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 13:46:25.925  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:25.927  4617  4691 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 13:46:25.927  4617  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:46:25.927  5573  5620 D BluetoothAdapter: STATE_ON
11-25 13:46:25.927  4617  4694 D BtGatt.ScanManager: Starting BLE batch scan
,11-25 13:46:25.927  4617  4694 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-25 13:46:25.927  4617  4637 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 13:46:25.927  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 13:46:25.929  5573  5620 D BluetoothAdapter: STATE_ON
11-25 13:46:25.930  4617  4842 D BtGatt.GattService: stopScan() - queue size =1
11-25 13:46:25.931  4617  4850 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-25 13:46:25.931  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 13:46:25.931  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:25.932  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 13:46:25.932  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:25.932  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:25.932  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:25.932  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:25.932  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 13:46:25.932  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:25.932  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:25.932  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:25.932  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 13:46:25.932  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 13:46:25.933  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:46:25.933  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:25.935  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:25.935  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:46:25.936  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:25.936  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:25.936  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:46:25.936  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:46:25.936  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:46:25.936  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 13:46:25.936  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-25 13:46:25.936  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb68129 not in the list
11-25 13:46:25.936  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:46:25.936  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:46:25.936  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:25.936  5573  5573 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 13:46:25.936  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:46:25.936  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-25 13:46:25.936  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 13:46:25.936  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 13:46:25.937  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 13:46:25.937  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:46:25.937  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 13:46:25.937  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:46:25.937  5573  5573 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:46:25.937  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 13:46:25.937  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-25 13:46:25.939  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:46:25.939  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:46:25.940  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 13:46:25.940  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:25.940  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:25.941  4617  4691 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 13:46:25.941  4617  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:46:25.941  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:25.942  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:25.942  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:25.942  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:46:25.942  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:46:25.942  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:46:25.942  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:25.943  5573  5620 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-25 13:46:25.945  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-25 13:46:25.945  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-25 13:46:25.948  4617  4691 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-25 13:46:25.948  4617  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:46:25.951  4617  4694 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 13:46:25.953  5573  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 13:46:25.953  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:46:25.953  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:46:25.953  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:46:25.953  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 13:46:25.953  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 13:46:25.953  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 13:46:25.953  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 13:46:25.953  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-25 13:46:25.955  5573  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 13:46:25.955  5573  5620 D io.jxcore.node.ConnectivityMonitor: start: OK
11-25 13:46:25.955  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:46:25.955  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 13:46:25.955  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 13:46:25.955  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 13:46:25.955  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-25 13:46:25.956  4617  4691 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 13:46:25.956  4617  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:46:25.956  4617  4691 E BtGatt.ContextMap: Context not found for ID 5
,11-25 13:46:25.959  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:46:25.959  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 13:46:25.960  5573  5620 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 13:46:25.960  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-25 13:46:25.963  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:46:25.964  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:25.964  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 13:46:25.965  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 13:46:25.965  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 13:46:25.965  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-25 13:46:25.966  4617  4691 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 13:46:25.966  4617  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:46:25.966  4617  4694 D BtGatt.ScanManager: stopping BLe Batch
,11-25 13:46:25.969  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:25.969  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 13:46:25.969  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 13:46:25.969  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 13:46:25.969  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 13:46:25.969  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:25.970  5573  5620 D BluetoothAdapter: STATE_ON
11-25 13:46:25.971  4617  4639 D BtGatt.GattService: registerClient() - UUID=81810127-dab6-4bca-b2a8-1ad910d49d29
,11-25 13:46:25.972  4617  4691 D BtGatt.GattService: onClientRegistered() - UUID=81810127-dab6-4bca-b2a8-1ad910d49d29, clientIf=5
11-25 13:46:25.973  4617  4691 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-25 13:46:25.973  5573  5583 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 13:46:25.973  4617  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:46:25.973  4617  4694 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 13:46:25.973  4617  4637 D BtGatt.GattService: start scan with filters
,11-25 13:46:25.976  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 13:46:25.976  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:25.976  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 13:46:25.976  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:25.976  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 13:46:25.977  5573  5573 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 13:46:25.977  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:46:25.977  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 13:46:25.977  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 13:46:25.977  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:46:25.977  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 13:46:25.977  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:46:25.977  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 13:46:25.978  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 13:46:25.978  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:25.978  4617  4691 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 13:46:25.978  4617  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:46:25.979  4617  4694 D BtGatt.ScanManager: handling starting scan
11-25 13:46:25.980  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:25.980  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 13:46:25.980  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:25.980  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:25.980  5573  5620 I io.jxcore.node.ConnectionHelper: start: OK
11-25 13:46:25.980  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-25 13:46:25.983  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:46:25.983  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:46:25.983  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 13:46:25.983  5573  5573 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-25 13:46:25.988  4617  4691 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-25 13:46:25.988  4617  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:46:25.988  4617  4694 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 13:46:25.993  4617  4691 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 13:46:25.993  4617  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:46:25.994  4617  4694 D BtGatt.ScanManager: Starting BLE batch scan
11-25 13:46:25.994  4617  4694 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-25 13:46:26.003  4617  4691 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 13:46:26.003  4617  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:46:26.008  4617  4691 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 13:46:26.008  4617  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:46:26.484  5573  5573 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-25 13:46:26.484  5573  5573 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-25 13:46:26.484  5573  5573 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-25 13:46:28.524   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-25 13:46:30.981  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 13:46:30.981  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-25 13:46:30.981  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-25 13:46:30.981  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-25 13:46:30.981  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-25 13:46:30.982  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:46:30.982  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-25 13:46:30.982  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 13:46:30.982  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:30.982  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 13:46:30.983  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 13:46:30.983  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:30.983  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:30.983  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:30.983  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 13:46:30.984  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:30.987  5573  5620 D BluetoothAdapter: STATE_ON
11-25 13:46:30.988  4617  4639 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 13:46:30.989  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 13:46:30.989  4617  4694 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 13:46:30.990  5573  5620 D BluetoothAdapter: STATE_ON
11-25 13:46:30.993  4617  4850 D BtGatt.GattService: stopScan() - queue size =1
,11-25 13:46:30.994  4617  4849 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-25 13:46:30.995  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 13:46:30.996  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:30.996  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 13:46:30.996  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:30.996  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:30.996  4617  4617 D BtGatt.ScanManager: awakened up at time 180557
11-25 13:46:30.997  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:30.997  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:30.997  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 13:46:30.997  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:30.997  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:30.998  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:30.998  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 13:46:30.998  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-25 13:46:30.999  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:46:31.000  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:31.001  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:31.001  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-25 13:46:31.002  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:31.002  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:31.002  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:46:31.002  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:46:31.003  5573  5573 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 13:46:31.003  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:46:31.003  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 13:46:31.003  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 13:46:31.003  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:46:31.003  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 13:46:31.003  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:46:31.004  5573  5573 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:46:31.004  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 13:46:31.004  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:46:31.006  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:46:31.006  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:46:31.006  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-25 13:46:31.021  4617  4691 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-25 13:46:31.021  4617  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:46:31.021  4617  4691 D BtGatt.GattService: current time is 180582942979
,11-25 13:46:31.022  4617  4691 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -89, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -90, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -92, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -78, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -89, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -88, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-25 13:46:31.022  4617  4691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-25 13:46:31.023  4617  4691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-25 13:46:31.023  4617  4691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-25 13:46:31.023  4617  4691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-25 13:46:31.023  4617  4691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-25 13:46:31.024  4617  4691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-25 13:46:31.024  4617  4691 E BtGatt.ContextMap: Context not found for ID 5
,11-25 13:46:31.033  4617  4691 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 13:46:31.033  4617  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:46:31.033  4617  4694 D BtGatt.ScanManager: stopping BLe Batch
,11-25 13:46:31.041  4617  4691 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-25 13:46:31.041  4617  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:46:31.041  4617  4694 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 13:46:31.048  4617  4691 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 13:46:31.048  4617  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:46:31.504  5573  5573 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 13:46:31.505  5573  5573 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:46:31.505  5573  5573 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-25 13:46:32.617   928  2944 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 13:46:33.583   928  5326 D NetlinkSocketObserver: NeighborEvent{elapsedMs=183144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-25 13:46:36.004  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 13:46:36.004  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 13:46:36.004  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-25 13:46:36.004  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 13:46:36.004  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-25 13:46:36.005  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-25 13:46:36.005  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 13:46:36.005  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb68129 not in the list
11-25 13:46:36.005  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:46:36.006  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:36.006  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:46:36.006  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 13:46:36.008  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.010  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:36.013  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.013  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:36.014  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.014  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:46:36.014  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:46:36.014  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:46:36.014  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
,11-25 13:46:36.016  5573  5620 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-25 13:46:36.017  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:46:36.017  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:46:36.018  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:46:36.018  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:46:36.018  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:46:36.018  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb68129 not in the list
11-25 13:46:36.018  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:46:36.018  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:36.019  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:46:36.019  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.019  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.023  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.023  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.023  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.023  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:46:36.023  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:46:36.023  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:46:36.023  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:36.025  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-25 13:46:36.025  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:46:36.025  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:46:36.025  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:46:36.026  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:46:36.026  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:46:36.026  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb68129 not in the list
11-25 13:46:36.026  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:46:36.026  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListene,r: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
,11-25 13:46:36.026  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:46:36.026  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:36.026  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.028  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.028  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:36.028  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.029  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:46:36.029  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-25 13:46:36.029  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:46:36.029  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:36.030  5573  5620 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-25 13:46:36.030  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:46:36.030  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:46:36.030  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:46:36.031  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:46:36.031  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:46:36.031  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb68129 not in the list
11-25 13:46:36.031  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:46:36.031  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:36.031  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:46:36.031  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.032  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.033  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.033  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.034  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.034  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:46:36.034  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:46:36.034  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:46:36.034  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:36.035  5573  5620 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-25 13:46:36.035  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:46:36.035  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:46:36.036  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-25 13:46:36.036  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:46:36.036  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:46:36.036  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb68129 not in the list
11-25 13:46:36.036  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:46:36.036  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:36.036  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 13:46:36.036  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.037  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.039  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.039  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.040  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.040  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:46:36.040  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:46:36.040  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:46:36.040  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:36.041  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-25 13:46:36.041  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 13:46:36.042  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 13:46:36.042  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-25 13:46:36.042  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 13:46:36.042  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 13:46:36.042  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-25 13:46:36.042  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 13:46:36.042  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-25 13:46:36.043  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:46:36.043  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:46:36.043  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:46:36.043  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:46:36.043  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:46:36.043  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb68129 not in the list
11-25 13:46:36.043  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:46:36.043  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:36.043  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:46:36.044  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.044  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.046  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.046  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:36.046  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.046  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:46:36.046  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:46:36.046  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:46:36.046  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:36.047  5573  5620 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 13:46:36.048  5573  5620 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,11-25 13:46:36.048  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-25 13:46:36.052  5573  5620 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 13:46:36.052  5573  5620 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-25 13:46:36.053  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-25 13:46:36.053  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-25 13:46:36.053  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,11-25 13:46:36.053  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-25 13:46:36.053  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-25 13:46:36.053  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-25 13:46:36.053  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-25 13:46:36.053  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-25 13:46:36.053  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-25 13:46:36.053  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-25 13:46:36.053  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-25 13:46:36.053  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-25 13:46:36.053  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-25 13:46:36.053  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-25 13:46:36.054  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-25 13:46:36.054  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-25 13:46:36.054  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-25 13:46:36.054  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-25 13:46:36.054  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-25 13:46:36.054  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-25 13:46:36.054  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-25 13:46:36.054  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-25 13:46:36.054  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-25 13:46:36.054  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-25 13:46:36.054  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-25 13:46:36.054  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,11-25 13:46:36.054  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-25 13:46:36.054  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-25 13:46:36.054  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-25 13:46:36.054  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-25 13:46:36.055  5573  5620 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-25 13:46:36.055  5573  5620 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-25 13:46:36.055  5573  5620 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-25 13:46:36.055  5573  5620 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 13:46:36.055  5573  5620 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-25 13:46:36.055  5573  5620 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,11-25 13:46:36.056  5573  5620 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 13:46:36.056  5573  5620 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-25 13:46:36.056  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-25 13:46:36.060  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-25 13:46:36.061  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-25 13:46:36.061  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-25 13:46:36.062  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-25 13:46:36.062  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-25 13:46:36.062  5573  5625 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
11-25 13:46:36.063  5573  5625 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-25 13:46:36.063  5573  5625 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-25 13:46:36.063  5573  5625 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-25 13:46:36.062  5573  5620 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-25 13:46:36.063  5573  5620 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 13:46:36.064  5573  5620 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-25 13:46:36.065  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:46:36.065  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:46:36.065  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:46:36.065  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:46:36.065  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:46:36.065  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-25 13:46:36.066  5573  5625 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-25 13:46:36.066  5573  5625 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 13:46:36.067  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb68129 not in the list
11-25 13:46:36.067  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:46:36.067  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:36.067  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:46:36.068  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.068  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.069  5573  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
11-25 13:46:36.069  5573  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-25 13:46:36.069  5573  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 121)
11-25 13:46:36.069  5573  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 121)
,11-25 13:46:36.068  4637  4637 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33927]" dev="sockfs" ino=33927 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-25 13:46:36.068  4637  4637 W Binder_1: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[33927]" dev="sockfs" ino=33927 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-25 13:46:36.070  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.070  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.071  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.071  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:46:36.071  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:46:36.071  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:46:36.071  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:36.071  5573  5625 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
11-25 13:46:36.071  5573  5625 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-25 13:46:36.071  5573  5625 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
11-25 13:46:36.072  5573  5620 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-25 13:46:36.072  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:46:36.073  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:46:36.073  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:46:36.073  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:46:36.073  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:46:36.073  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb68129 not in the list
11-25 13:46:36.073  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:46:36.073  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:36.073  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:46:36.073  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.073  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:36.075  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.075  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.075  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.075  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:46:36.075  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-25 13:46:36.075  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:46:36.075  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:36.077  5573  5620 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-25 13:46:36.077  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:46:36.077  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:46:36.077  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:46:36.077  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:46:36.077  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:46:36.077  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb68129 not in the list
11-25 13:46:36.077  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:46:36.077  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:36.077  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:46:36.077  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.077  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.078  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.078  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.079  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.079  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 13:46:36.079  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:46:36.079  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:46:36.079  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
,11-25 13:46:36.080  5573  5620 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-25 13:46:36.080  5573  5620 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-25 13:46:36.080  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-25 13:46:36.080  5573  5620 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-25 13:46:36.080  5573  5620 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-25 13:46:36.080  5573  5620 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-25 13:46:36.080  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-25 13:46:36.080  5573  5620 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-25 13:46:36.080  5573  5620 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,11-25 13:46:36.080  5573  5620 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-25 13:46:36.080  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-25 13:46:36.080  5573  5620 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-25 13:46:36.080  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:46:36.080  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 13:46:36.080  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:46:36.081  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:46:36.081  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:46:36.081  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb68129 not in the list
11-25 13:46:36.081  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:46:36.081  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:36.081  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:46:36.081  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.081  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.082  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:36.082  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.082  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:36.082  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:46:36.082  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:46:36.082  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:46:36.083  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:36.083  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:46:36.083  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:46:36.083  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb68129 not in the list
11-25 13:46:36.083  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:46:36.083  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
,11-25 13:46:36.083  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 13:46:40.406   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:46:41.084  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:46:41.084  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:41.085  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:46:41.085  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:46:41.085  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb68129 not in the list
,11-25 13:46:41.085  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:46:41.086  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:46:41.086  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:46:41.086  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:46:41.086  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:46:41.086  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb68129 not in the list
11-25 13:46:41.087  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:46:41.087  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
,11-25 13:46:41.087  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:46:41.087  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:41.087  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:41.090  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:41.091  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:41.091  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:41.091  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 13:46:41.091  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-25 13:46:41.091  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:46:41.091  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:41.095  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-25 13:46:41.096  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 13:46:41.096  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-25 13:46:41.102  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-25 13:46:41.105  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-25 13:46:41.105  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-25 13:46:41.105  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-25 13:46:41.106  5573  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-25 13:46:41.106  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-25 13:46:41.106  5573  5573 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-25 13:46:41.106  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-25 13:46:41.107  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 13:46:41.107  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-25 13:46:41.108  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-25 13:46:41.108  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-25 13:46:41.108  5573  5627 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 13:46:41.108  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 13:46:41.109  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-25 13:46:41.110  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-25 13:46:41.110  5573  5573 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-25 13:46:41.110  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb68129 not in the list
11-25 13:46:41.110  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:46:41.110  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 13:46:41.110  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:41.111  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-25 13:46:41.111  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 13:46:41.111  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:41.112  4842  4842 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32551]" dev="sockfs" ino=32551 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-25 13:46:41.112  4842  4842 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32551]" dev="sockfs" ino=32551 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-25 13:46:41.114  5573  5627 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-25 13:46:41.115  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:41.115  5573  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-25 13:46:41.115  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:46:41.115  5573  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-25 13:46:41.115  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:41.115  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:41.115  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:41.115  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:46:41.116  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:46:41.116  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:46:41.116  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:46:41.116  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:46:41.116  5573  5573 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:46:41.116  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:46:41.116  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-25 13:46:41.116  5573  5573 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-25 13:46:41.116  5573  5573 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:46:41.116  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb68129 not in the list
11-25 13:46:41.116  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:46:41.116  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:41.116  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:46:41.117  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:41.117  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:41.119  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:41.119  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:41.119  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:41.120  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 13:46:41.120  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:46:41.120  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:46:41.120  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:41.122  5573  5620 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-25 13:46:41.123  5573  5620 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-25 13:46:41.123  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-25 13:46:41.123  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 13:46:41.123  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-25 13:46:41.123  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:46:41.124  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:46:41.124  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:46:41.124  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:46:41.124  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:46:41.124  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb68129 not in the list
11-25 13:46:41.124  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:46:41.124  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:41.124  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:46:41.125  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:41.125  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:41.127  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:41.127  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:41.127  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:41.127  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:46:41.127  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-25 13:46:41.127  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:46:41.127  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
,11-25 13:46:41.134  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 13:46:41.134  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:46:41.134  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:46:41.134  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 13:46:41.134  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:46:41.134  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb68129 not in the list
11-25 13:46:41.134  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:46:41.135  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
,11-25 13:46:41.135  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:46:41.135  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:41.135  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:41.137  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:41.137  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:41.137  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:41.137  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 13:46:41.137  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:46:41.137  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:46:41.137  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
,11-25 13:46:41.138  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 13:46:41.138  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:46:41.138  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:46:41.139  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 13:46:41.139  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:46:41.139  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb68129 not in the list
11-25 13:46:41.139  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:46:41.139  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:41.139  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:46:41.139  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:41.139  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:41.141  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:41.141  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:46:41.141  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:46:41.141  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:46:41.141  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:46:41.141  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:46:41.141  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c5acae not in the list
11-25 13:46:41.142  5573  5620 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-25 13:46:41.143  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-25 13:46:41.143  5573  5620 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,11-25 13:46:41.143  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-25 13:46:41.143  5573  5620 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-25 13:46:41.143  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-25 13:46:41.145  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-25 13:46:41.145  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,11-25 13:46:41.146  5573  5620 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-25 13:46:41.146  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-25 13:46:41.146  5573  5620 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-25 13:46:41.146  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-25 13:46:41.146  5573  5620 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,11-25 13:46:41.146  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-25 13:46:41.146  5573  5620 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-25 13:46:41.147  5573  5620 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-25 13:46:41.147  5573  5620 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-25 13:46:41.147  5573  5620 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-25 13:46:41.147  5573  5620 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,11-25 13:46:41.147  5573  5620 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-25 13:46:41.148  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:46:41.148  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fc5d53f added. We now have 3 listener(s)
11-25 13:46:41.148  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:46:41.151  5573  5620 D BluetoothAdapter: enable(): BT is already enabled..!
11-25 13:46:41.151   928  3774 D WifiService: setWifiEnabled: true pid=5573, uid=10077
,11-25 13:46:41.151   928  3774 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 13:46:41.197  4617  4811 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-25 13:46:41.198  4617  4839 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-25 13:46:41.407   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:46:41.616  5573  5573 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 13:46:42.408   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:46:43.409   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:46:44.410   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:46:45.411   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-25 13:46:46.157  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:46:46.157  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bef2e0c added. We now have 4 listener(s)
11-25 13:46:46.158  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 13:46:46.171  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:46:46.171  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bef2e0c removed from the list
,11-25 13:46:46.171  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 13:46:46.173  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 13:46:46.174  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e267355 added. We now have 4 listener(s)
11-25 13:46:46.174  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 13:46:46.177  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:46:46.177  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e267355 removed from the list
11-25 13:46:46.178  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:46:46.180  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:46:46.180  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@641316a added. We now have 4 listener(s)
,11-25 13:46:46.180  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 13:46:46.186   928  3636 D WifiService: setWifiEnabled: false pid=5573, uid=10077
,11-25 13:46:46.187   928  3636 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 13:46:46.191   928  2944 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-25 13:46:46.192   928  2944 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-25 13:46:46.192   928  2944 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-25 13:46:46.192   928  2944 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 13:46:46.197  4617  4687 D BluetoothAdapterState: Current state: ON, message: 23
11-25 13:46:46.197  4617  4687 D BluetoothAdapterProperties: Setting state to 13
11-25 13:46:46.197  4617  4687 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-25 13:46:46.199  4617  4687 D BluetoothAdapterProperties: onBluetoothDisable()
11-25 13:46:46.202  4617  4687 I BluetoothAdapterState: Entering PendingCommandState
,11-25 13:46:46.208  4617  4691 D BluetoothAdapterProperties: Scan Mode:20
11-25 13:46:46.209  4617  4687 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-25 13:46:46.211  4617  4617 D BluetoothMapService: onReceive
,11-25 13:46:46.211   928  5327 D DhcpClient: Clearing IP address
11-25 13:46:46.211   508   919 D CommandListener: Clearing all IP addresses on wlan0
,11-25 13:46:46.211  4617  4617 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-25 13:46:46.212  4617  4617 D BluetoothMapService: STATE_TURNING_OFF
11-25 13:46:46.212  4617  4617 D BluetoothMapService: MAP Service closeService in
11-25 13:46:46.212  4617  4617 D BluetoothMapMasInstance0: MAP Service shutdown
11-25 13:46:46.212  4617  4617 D ObexServerSockets0: shutdown(block = true)
,11-25 13:46:46.213  4617  4617 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-25 13:46:46.213  4617  4617 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-25 13:46:46.213  4617  4839 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-25 13:46:46.214  4617  4853 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-25 13:46:46.214  4617  4852 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-25 13:46:46.215  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 13:46:46.215  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-25 13:46:46.216  4617  4617 I BtOppRfcommListener: stopping Accept Thread
11-25 13:46:46.217  4617  5259 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-25 13:46:46.217  4617  5259 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-25 13:46:46.219   508   919 D CommandListener: Setting iface cfg
,11-25 13:46:46.223   928  5328 D DhcpClient: Receive thread stopped
,11-25 13:46:46.226  3556  5381 V NativeCrypto: Read error: ssl=0x7f72d85700: I/O error during system call, Connection timed out
,11-25 13:46:46.228  3556  5381 V NativeCrypto: SSL shutdown failed: ssl=0x7f72d85700: I/O error during system call, Broken pipe
11-25 13:46:46.231   928  3774 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-25 13:46:46.231   928  5324 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,11-25 13:46:46.231   928   941 I ActivityManager: Start proc 5631:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-25 13:46:46.235   928  5324 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,11-25 13:46:46.236   928  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,11-25 13:46:46.236   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-25 13:46:46.237  4617  4617 D HeadsetService: Received stop request...Stopping profile...
11-25 13:46:46.238   928  2946 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-25 13:46:46.241   928   928 D BluetoothHeadset: Proxy object disconnected
,11-25 13:46:46.241   928   928 D BluetoothHeadset: Proxy object disconnected
11-25 13:46:46.241   928   928 D BluetoothHeadset: Proxy object disconnected
11-25 13:46:46.242  3089  3959 D BluetoothHeadset: Proxy object disconnected
,11-25 13:46:46.242  3748  3985 D BluetoothHeadset: Proxy object disconnected
11-25 13:46:46.243  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:46:46.243  5573  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 13:46:46.243  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:46:46.243  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:46:46.243  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:46:46.243  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 13:46:46.243  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 13:46:46.243  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 13:46:46.243  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 13:46:46.243  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-25 13:46:46.244  4617  4617 D A2dpService: Received stop request...Stopping profile...
,11-25 13:46:46.245  4617  4844 D A2dpStateMachine: Exit Disconnected: -1
11-25 13:46:46.245   928  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-25 13:46:46.245   928  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-25 13:46:46.246  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:46:46.246  5573  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-25 13:46:46.246  5573  5620 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-25 13:46:46.247   534   534 E Parcel  : Reading a NULL string not supported here.
11-25 13:46:46.247   928   928 D BluetoothA2dp: Proxy object disconnected
11-25 13:46:46.249   928  2946 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-25 13:46:46.250  4617  4617 D HidService: Received stop request...Stopping profile...
11-25 13:46:46.250  4617  4617 D HidService: Stopping Bluetooth HidService
,11-25 13:46:46.250  3722  3844 W QCNEJ   : |CORE| network lost: 100
11-25 13:46:46.250  5573  5573 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:46:46.251  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:46:46.251  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:46:46.251  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:46:46.251  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:46:46.251  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 13:46:46.251  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 13:46:46.251  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 13:46:46.251  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 13:46:46.251  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-25 13:46:46.251  3089  3089 D HeadsetProfile: Bluetooth service disconnected
11-25 13:46:46.251  3722  3844 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-25 13:46:46.252   928   928 D RttService: SCAN_AVAILABLE : 1
11-25 13:46:46.252  3089  3089 D BluetoothA2dp: Proxy object disconnected
11-25 13:46:46.252  5573  5573 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:46:46.252   928  3054 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-25 13:46:46.252  5573  5573 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 13:46:46.253  4617  4617 D HealthService: Received stop request...Stopping profile...
11-25 13:46:46.254  4617  4617 V BluetoothAdapterState: isTurningOff()=true
11-25 13:46:46.254  4617  4617 V BluetoothAdapterState: isTurningOn()=false
11-25 13:46:46.254  4617  4617 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:46:46.254  4617  4617 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:46:46.255  5573  5573 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:46:46.255  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:46:46.255  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:46:46.255  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:46:46.255  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:46:46.255  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 13:46:46.255  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 13:46:46.255  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 13:46:46.255  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 13:46:46.255  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 13:46:46.255  4617  4617 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-25 13:46:46.256  4617  4617 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-25 13:46:46.256  4617  4691 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,11-25 13:46:46.256  4617  4811 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:46:46.256  4617  4811 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:46:46.256  4617  4811 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:46:46.257  4617  4617 D PanService: Received stop request...Stopping profile...
,11-25 13:46:46.257  4617  4691 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-25 13:46:46.258  4617  4617 D BluetoothMapService: Received stop request...Stopping profile...
11-25 13:46:46.259  4617  4617 D BluetoothMapService: stop()
11-25 13:46:46.261  4617  4617 D BluetoothMapAppObserver: deinitObservers()
11-25 13:46:46.261  4617  4617 D BluetoothMapAppObserver: removeReceiver()
,11-25 13:46:46.262  4617  4617 V BluetoothAdapterState: isTurningOff()=true
,11-25 13:46:46.262  4617  4617 V BluetoothAdapterState: isTurningOn()=false
11-25 13:46:46.262  4617  4617 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:46:46.262  4617  4617 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:46:46.263   928  2944 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-25 13:46:46.264  4617  4617 D SapService: Received stop request...Stopping profile...
11-25 13:46:46.264  4617  4617 V SapService: stop()
,11-25 13:46:46.266  4617  4691 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-25 13:46:46.266  4617  4811 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:46:46.266  4617  4811 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:46:46.267  4617  4811 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-25 13:46:46.267  4617  4811 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-25 13:46:46.267  4617  4811 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-25 13:46:46.267  4617  4811 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-25 13:46:46.267  4617  4617 V BluetoothAdapterState: isTurningOff()=true
11-25 13:46:46.267  4617  4617 V BluetoothAdapterState: isTurningOn()=false
11-25 13:46:46.267  4617  4617 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:46:46.267  4617  4617 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:46:46.267  4617  4617 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-25 13:46:46.267  4617  4691 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-25 13:46:46.267  4617  4617 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-25 13:46:46.268  4617  4617 V BluetoothAdapterState: isTurningOff()=true
,11-25 13:46:46.268  4617  4617 V BluetoothAdapterState: isTurningOn()=false
11-25 13:46:46.268  4617  4617 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:46:46.268  4617  4617 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:46:46.268  4617  4617 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-25 13:46:46.268  4617  4691 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-25 13:46:46.268  4617  4617 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-25 13:46:46.268  4617  4617 V BluetoothAdapterState: isTurningOff()=true
11-25 13:46:46.268  4617  4617 V BluetoothAdapterState: isTurningOn()=false
11-25 13:46:46.268  4617  4617 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:46:46.268  4617  4617 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:46:46.269  4617  4617 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-25 13:46:46.269  4617  4617 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-25 13:46:46.269  3089  3089 D BluetoothInputDevice: Proxy object disconnected
11-25 13:46:46.269  3089  3089 D HidProfile: Bluetooth service disconnected
11-25 13:46:46.269  3089  3089 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-25 13:46:46.269  3089  3089 D PanProfile: Bluetooth service disconnected
11-25 13:46:46.269  3089  3089 D BluetoothMap: Proxy object disconnected
11-25 13:46:46.269  3089  3089 D MapProfile: Bluetooth service disconnected
11-25 13:46:46.270  4617  4617 D BluetoothMapService: MAP Service closeService in
11-25 13:46:46.270  4617  4617 V BluetoothAdapterState: isTurningOff()=true
11-25 13:46:46.270  4617  4617 V BluetoothAdapterState: isTurningOn()=false
11-25 13:46:46.270  4617  4617 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:46:46.270  4617  4617 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 13:46:46.270  4617  4617 D BluetoothMapService: cleanup()
,11-25 13:46:46.270  4617  4617 D BluetoothMapService: MAP Service closeService in
11-25 13:46:46.270  4617  4617 V BluetoothAdapterState: isTurningOff()=true
11-25 13:46:46.270  4617  4617 V BluetoothAdapterState: isTurningOn()=false
11-25 13:46:46.270  4617  4617 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:46:46.270  4617  4617 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:46:46.270  4617  4687 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-25 13:46:46.270  4617  4687 D BluetoothAdapterProperties: Setting state to 15
11-25 13:46:46.270  4617  4687 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-25 13:46:46.271  4617  4687 I BluetoothAdapterState: Entering BleOnState
11-25 13:46:46.275   928  2944 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-25 13:46:46.276  3089  3104 D BluetoothMap: onBluetoothStateChange: up=false
11-25 13:46:46.277   508   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-25 13:46:46.278  3089  3101 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-25 13:46:46.285   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-25 13:46:46.285  3089  3958 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-25 13:46:46.285   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-25 13:46:46.285  3089  3101 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 13:46:46.286   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 13:46:46.286  3748  3963 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 13:46:46.286   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 13:46:46.286  3089  3958 D BluetoothPan: onBluetoothStateChange on: false
11-25 13:46:46.287  3089  3104 D BluetoothPbap: onBluetoothStateChange: up=false
,11-25 13:46:46.288  4617  4687 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-25 13:46:46.288  4617  4687 D BluetoothAdapterProperties: Setting state to 16
11-25 13:46:46.288  4617  4687 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-25 13:46:46.289  4617  4687 D BluetoothAdapterProperties: onBleDisable
,11-25 13:46:46.289  4617  4687 I BluetoothAdapterState: Entering PendingCommandState
11-25 13:46:46.289  4617  4688 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-25 13:46:46.291  4617  4811 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-25 13:46:46.291  4617  4811 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:46:46.292  4617  4691 D BluetoothAdapterProperties: Scan Mode:20
,11-25 13:46:46.293  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:46:46.294  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:46:46.297   508   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-25 13:46:46.298   508   919 D CommandListener: Clearing all IP addresses on wlan0
11-25 13:46:46.298   508   919 D TetherController: Setting IP forward enable = 0
11-25 13:46:46.299   928  2946 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-25 13:46:46.299   928  2946 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-25 13:46:46.302   928   945 D Tethering: MasterInitialState.processMessage what=3
,11-25 13:46:46.303   928  2944 D DhcpClient: doQuit
11-25 13:46:46.303   928  2944 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-25 13:46:46.303   928  5327 D DhcpClient: onQuitting
11-25 13:46:46.303  3412  3412 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-25 13:46:46.304  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:46:46.306  5213  5213 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@97d1159 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,11-25 13:46:46.309  5573  5573 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:46:46.309  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:46:46.309  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:46:46.309  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:46:46.309  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 13:46:46.309  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 13:46:46.309  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 13:46:46.309  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 13:46:46.309  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 13:46:46.309  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 13:46:46.309  5573  5573 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:46:46.309  5573  5573 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 13:46:46.310  4993  5007 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-25 13:46:46.311  4993  5007 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,11-25 13:46:46.311  4993  5007 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-25 13:46:46.311  4993  5007 E SarControlService: no key has been found,reset the power
11-25 13:46:46.311  4993  5039 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-25 13:46:46.311  4993  5039 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-25 13:46:46.311  4993  5039 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-25 13:46:46.312  3937  3937 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-25 13:46:46.313  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 13:46:46.313  5026  5026 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-25 13:46:46.317  5026  5041 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6056947 HexData = [00000000ea03000000000000ffffffff]
11-25 13:46:46.317  5026  5041 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 13:46:46.317  5026  5041 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-25 13:46:46.318  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 13:46:46.318  4993  5003 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-25 13:46:46.319  4993  5039 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-25 13:46:46.320  4993  5039 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-25 13:46:46.321  4993  5039 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-25 13:46:46.321  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 13:46:46.321  5026  5026 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-25 13:46:46.328  5631  5631 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
11-25 13:46:46.330  5026  5041 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6056947 HexData = [00000000eb03000000000000ffffffff]
11-25 13:46:46.330  5026  5041 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 13:46:46.330  5026  5041 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,11-25 13:46:46.330  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 13:46:46.331  4993  5004 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-25 13:46:46.342  5631  5631 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-25 13:46:46.347  3556  3556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 13:46:46.347   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@569133f:true
,11-25 13:46:46.356  3412  3412 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-25 13:46:46.360   928  3774 I ActivityManager: Start proc 5661:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-25 13:46:46.360   508   919 E Netd    : netlink response contains error (No such file or directory)
11-25 13:46:46.360  3412  3412 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-25 13:46:46.361   508   919 D TetherController: Setting IP forward enable = 0
11-25 13:46:46.363   928  2946 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-25 13:46:46.363   928  2946 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-25 13:46:46.375  5631  5631 D LocalBluetoothProfileManager: Adding local MAP profile
,11-25 13:46:46.378  5631  5631 D BluetoothMap: Create BluetoothMap proxy object
,11-25 13:46:46.391  3412  3412 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-25 13:46:46.392  5631  5631 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-25 13:46:46.402  3412  3412 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-25 13:46:46.408  4474  4474 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-25 13:46:46.408   928  2944 D wifi    : In wifi stop Hal
11-25 13:46:46.408   928  2944 D wifi    : halHandle = 0x7f70e6d580, mVM = 0x7f8d44d140, mCls = 0x100a02
11-25 13:46:46.408   928  3411 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-25 13:46:46.408   928  3411 D WifiHAL : Got a signal to exit!!!
11-25 13:46:46.408   928  3411 I WifiHAL : Exit wifi_event_loop
11-25 13:46:46.410   928  2944 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-25 13:46:46.410   928  2944 E WifiHAL : Event processing terminated
11-25 13:46:46.411   928  2944 D wifi    : In wifi cleaned up handler
11-25 13:46:46.411   928  2944 I WifiHAL : Internal cleanup completed
11-25 13:46:46.411  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:46:46.411  3924  4192 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-25 13:46:46.415  5661  5661 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-25 13:46:46.418  5631  5631 D DockEventReceiver: finishStartingService: stopping service
,11-25 13:46:46.423   928  3390 I ActivityManager: Killing 5353:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-25 13:46:46.431   928  3411 D wifi    : set interface wlan0 flags (DOWN)
11-25 13:46:46.431   928  2944 D WifiNative-HAL: HAL event thread stopped successfully
,11-25 13:46:46.498  4617  4691 I bt_hci  : shut_down
,11-25 13:46:46.502  4617  4695 D bt_hwcfg: hw_epilog_process
,11-25 13:46:46.502  4617  4695 I bt_vendor: low_power_mode_cb
,11-25 13:46:46.505  4617  4695 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-25 13:46:46.505  4617  4695 I bt_vendor: epilog_cb
11-25 13:46:46.505  4617  4695 I bt_hci  : epilog_finished_callback
11-25 13:46:46.507  4617  4691 I bt_hci_h4: hal_close
11-25 13:46:46.507  4617  4691 I bt_userial_vendor: device fd = 54 close
,11-25 13:46:46.620  4617  4688 D bt_stack_manager: event_shut_down_stack finished.
,11-25 13:46:46.620  4617  4687 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-25 13:46:46.622  5661  5661 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 13:46:46.622  5661  5661 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at java.io.File.exists(File.java:361)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-25 13:46:46.622  5661  5661 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 13:46:46.622  5661  5661 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 13:46:46.622  5661  5661 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-25 13:46:46.622  4617  4687 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-25 13:46:46.622  4617  4617 D BtGatt.DebugUtils: handleDebugAction() action=null
11-25 13:46:46.629  5661  5661 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-25 13:46:46.629  5661  5661 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.r.e.b(PG:170)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 13:46:46.629  5661  5661 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream,.java:290)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.r.k.d(PG:583)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.r.e.b(PG:170)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 13:46:46.629  5661  5661 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at java.io.File.exists(File.java:361)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
1,1-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 13:46:46.629  5661  5661 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at java.io.File.exists(File.java:361)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 13:46:46.629  4617  4617 D BtGatt.GattService: Received stop request...Stopping profile...
11-25 13:46:46.629  4617  4617 D BtGatt.GattService: stop()
11-25 13:46:46.629  5661  5661 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 13:46:46.629  5661  5661 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 13:46:46.629  4617  4617 D BtGatt.AdvertiseManager: advertise clients cleared
11-25 13:46:46.633  4617  4617 V BluetoothAdapterState: isTurningOff()=false
11-25 13:46:46.633  4617  4617 V BluetoothAdapterState: isTurningOn()=false
11-25 13:46:46.633  4617  4617 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:46:46.633  4617  4617 V BluetoothAdapterState: isBleTurningOff()=true
11-25 13:46:46.635   928   945 D Tethering: InitialState.processMessage what=4
11-25 13:46:46.635  4617  4687 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-25 13:46:46.635  4617  4687 D BluetoothAdapterProperties: Setting state to 10
11-25 13:46:46.635  4617  4687 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-25 13:46:46.636  4617  4687 I BluetoothAdapterState: Entering OffState
11-25 13:46:46.636  5631  5631 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-25 13:46:46.640   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
11-25 13:46:46.641   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-25 13:46:46.643  3556  3556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 13:46:46.648  4617  4617 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-25 13:46:46.648  4617  4617 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-25 13:46:46.648  4617  4617 I BluetoothServiceJni: cleanupNative: return from cleanup
11-25 13:46:46.649  4617  4688 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-25 13:46:46.655  5631  5631 D DockEventReceiver: finishStartingService: stopping service
11-25 13:46:46.659  4617  4617 I art     : System.exit called, status: 0
11-25 13:46:46.659  4617  4617 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-25 13:46:46.683   928  3774 I ActivityManager: Killing 5368:com.android.chrome/u0a39 (adj 15): empty #17
,11-25 13:46:46.713  4050  4050 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-25 13:46:46.713   928  3681 I ActivityManager: Process com.android.bluetooth (pid 4617) has died
,11-25 13:46:46.716  4050  4050 D SystemUpdateService: onCreate
,11-25 13:46:46.719  4050  4050 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-25 13:46:46.727  4050  4050 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-25 13:46:46.731  4050  5349 I iu.UploadsManager: num queued entries: 0
,11-25 13:46:46.731  4050  5349 I iu.UploadsManager: num updated entries: 0
11-25 13:46:46.732  4050  5349 I iu.SyncManager: NEXT; no task
,11-25 13:46:46.733  4050  4050 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-25 13:46:46.735  4050  4050 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-25 13:46:46.745  4050  5696 I SystemUpdateService: active receiver: enabled
,11-25 13:46:46.747   928  3636 I ActivityManager: Start proc 5698:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-25 13:46:46.757  4050  5696 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-25 13:46:46.784  5698  5698 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-25 13:46:46.785  4050  5696 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-25 13:46:46.786  4050  5696 I SystemUpdateService: now status is 0 (complete)
11-25 13:46:46.786  4050  5696 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-25 13:46:46.786  4050  5696 I SystemUpdateService: file has been verified
11-25 13:46:46.786  4050  5696 I SystemUpdateService: OTA package size = 21989297
,11-25 13:46:46.791  5698  5698 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-25 13:46:46.798  5698  5698 D SprintDMHelper: simOperator: 
11-25 13:46:46.798  5698  5698 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-25 13:46:46.801  4050  5696 I SystemUpdateService: showing system update notification
,11-25 13:46:46.810   928  3780 I ActivityManager: Start proc 5710:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-25 13:46:46.825   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-25 13:46:46.830  4050  4050 D SystemUpdateService: onDestroy
,11-25 13:46:46.832   928  3390 I ActivityManager: Killing 5213:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-25 13:46:46.920  4474  5724 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-25 13:46:46.933   928   939 I ActivityManager: Start proc 5725:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-25 13:46:46.934   928   939 I ActivityManager: Killing 3858:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-25 13:46:46.983  5725  5725 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-25 13:46:46.993   928   939 I ActivityManager: Killing 5435:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-25 13:46:47.063  5661  5686 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-25 13:46:47.072   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@46ba840:true
,11-25 13:46:51.248   928  3124 D WifiService: setWifiEnabled: true pid=5573, uid=10077
11-25 13:46:51.249   928  3124 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 13:46:51.256   508   919 D SoftapController: Softap fwReload - Ok
,11-25 13:46:51.262   508   919 D CommandListener: Setting iface cfg
,11-25 13:46:51.262   508   919 D CommandListener: Trying to bring down wlan0
,11-25 13:46:51.264   508   919 D CommandListener: Clearing all IP addresses on wlan0
,11-25 13:46:51.270   928  2944 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-25 13:46:51.833   928  2944 D wifi    : set interface wlan0 flags (UP)
,11-25 13:46:51.836   928  2944 I WifiHAL : Initializing wifi
11-25 13:46:51.836   928  2944 I WifiHAL : Creating socket
,11-25 13:46:51.837   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-25 13:46:51.839   928  2944 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-25 13:46:51.839   928  2944 D wifi    : Did set static halHandle = 0x7f70e6d580
,11-25 13:46:51.839   928  2944 D wifi    : halHandle = 0x7f70e6d580, mVM = 0x7f8d44d140, mCls = 0x19ea
11-25 13:46:51.839   928  2944 D wifi    : array field set
,11-25 13:46:51.839   928  2944 I WifiNative-HAL: interface[0] = wlan0
11-25 13:46:51.842   928  5742 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547355022720
11-25 13:46:51.842   928  5742 D wifi    : waitForHalEvents called, vm = 0x7f8d44d140, obj = 0x19ea, env = 0x7f75db9140
,11-25 13:46:51.909  5743  5743 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-25 13:46:51.943   928  2944 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-25 13:46:51.946  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:46:51.960  5743  5743 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-25 13:46:52.015  5743  5743 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-25 13:46:52.015  5743  5743 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-25 13:46:52.037   928  2944 D WifiConfigStore: Loading config and enabling all networks 
,11-25 13:46:52.040  5573  5573 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:46:52.040  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:46:52.040  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:46:52.040  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:46:52.040  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:46:52.040  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 13:46:52.040  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 13:46:52.040  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 13:46:52.040  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 13:46:52.040  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 13:46:52.040  5573  5573 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:46:52.040  5573  5573 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-25 13:46:52.066   928  2944 D WifiConfigStore: loaded 0 passpoint configs
,11-25 13:46:52.067   928  2944 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-25 13:46:52.068   928  2944 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-25 13:46:52.068   928  2944 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-25 13:46:52.069   928  2944 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-25 13:46:52.069   928  2944 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-25 13:46:52.070   928  2944 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-25 13:46:52.071   928  2944 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-25 13:46:52.071   928  2944 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-25 13:46:52.071   928  2944 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-25 13:46:52.071   928  2944 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-25 13:46:52.071   928  2944 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-25 13:46:52.071   928  2944 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-25 13:46:52.074   928  2944 D WifiNative-HAL: Setting external_sim to 1
,11-25 13:46:52.074  4474  4474 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-25 13:46:52.074   928  2944 D wifi    : setting dfs flag to true, 0x7f71f3fca0
11-25 13:46:52.075   928  2944 D WifiStateMachine: Setting OUI to DA-A1-19
11-25 13:46:52.075   928  2944 D wifi    : setting scan oui 0x7f71f3fca0
11-25 13:46:52.075   928  2944 D WifiHAL : Sending mac address OUI
,11-25 13:46:52.078   928  2944 E native  : do suspend false
,11-25 13:46:52.085   928  2944 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-25 13:46:52.086   928   928 D RttService: SCAN_AVAILABLE : 3
11-25 13:46:52.086   508   919 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-25 13:46:52.086   928  3054 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-25 13:46:52.087   508   919 D CommandListener: Setting iface cfg
,11-25 13:46:52.091   928  2943 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '125 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 125 Failed to set address (No such device)'
,11-25 13:46:52.091   928  2943 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-25 13:46:52.100   928  2943 D WifiNative-HAL: p2pGetDeviceAddress
,11-25 13:46:52.105   928  2943 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-25 13:46:52.106   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=201667 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,11-25 13:46:52.618   928  2944 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 11, 12 -> obsolete
,11-25 13:46:55.144  5743  5743 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 13:46:55.149  5743  5743 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 13:46:55.202   928  2944 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-25 13:46:55.204   928  2944 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-25 13:46:55.204   928  2944 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 13:46:55.215   928  2944 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-25 13:46:55.251   928  2944 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-25 13:46:55.258  5743  5743 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-25 13:46:55.680  5743  5743 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-25 13:46:55.719  5743  5743 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-25 13:46:55.720  5743  5743 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-25 13:46:55.728   928  2944 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-25 13:46:55.729   928  2944 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-25 13:46:55.729   928  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-25 13:46:55.746   928  2944 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 13:46:55.758   508   919 D CommandListener: Setting iface cfg
,11-25 13:46:55.764   928  2944 D WifiStateMachine: Start Dhcp Watchdog 2
,11-25 13:46:55.770   928  5751 D DhcpClient: Receive thread started
,11-25 13:46:55.775   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-25 13:46:55.775   928  2944 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-25 13:46:55.775   928  2946 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-25 13:46:55.856   928  2944 E native  : do suspend false
,11-25 13:46:55.869   928  5750 D DhcpClient: Broadcasting DHCPDISCOVER
,11-25 13:46:55.895   928  5751 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172636, domain null
,11-25 13:46:55.896   928  5750 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172636 seconds
,11-25 13:46:55.897   928  5750 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-25 13:46:55.915   928  5751 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-25 13:46:55.915   928  5750 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-25 13:46:55.918   508   919 D CommandListener: Setting iface cfg
,11-25 13:46:55.921   928  2944 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-25 13:46:55.928   928  5750 D DhcpClient: Scheduling renewal in 86399s
,11-25 13:46:55.941   928  2944 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-25 13:46:55.943   928  2944 D WifiConfigStore: No blacklist allowed without epno enabled
,11-25 13:46:55.944   928  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-25 13:46:55.945   928  2946 D ConnectivityService: Adding iface wlan0 to network 101
11-25 13:46:55.955   928  2944 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-25 13:46:55.992   928  2946 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-25 13:46:55.993   928  2946 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-25 13:46:55.994   928  2946 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-25 13:46:55.997   928  2946 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-25 13:46:56.000   928  2946 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-25 13:46:56.007   928  2946 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-25 13:46:56.011   928  2946 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-25 13:46:56.011   928  2946 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-25 13:46:56.011   928  2946 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-25 13:46:56.011   928  2946 D ConnectivityService:    accepting network in place of null
11-25 13:46:56.011   928  2944 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-25 13:46:56.012   928  2944 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-25 13:46:56.012   928  2946 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-25 13:46:56.024   928  5749 D NetlinkSocketObserver: NeighborEvent{elapsedMs=205585, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 13:46:56.036   508   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 13:46:56.057   508   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 13:46:56.060   928  2946 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-25 13:46:56.060  3722  3844 W QCNEJ   : |CORE| network available: 101
11-25 13:46:56.060   928  2946 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-25 13:46:56.061   928  2946 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-25 13:46:56.062   928   945 D Tethering: MasterInitialState.processMessage what=3
11-25 13:46:56.067  5573  5573 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:46:56.067  3722  3844 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-25 13:46:56.067  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:46:56.067  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:46:56.067  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:46:56.067  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:46:56.067  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 13:46:56.067  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 13:46:56.067  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 13:46:56.067  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 13:46:56.067  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-25 13:46:56.067  5573  5573 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:46:56.067  5573  5573 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-25 13:46:56.068  3722  3844 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-25 13:46:56.069  3722  3844 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-25 13:46:56.077  4993  5007 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-25 13:46:56.077  4993  5007 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-25 13:46:56.077  4993  5007 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-25 13:46:56.077  4993  5007 E SarControlService: no key has been found,reset the power
11-25 13:46:56.078  4993  5039 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-25 13:46:56.078  4993  5039 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-25 13:46:56.078  4993  5039 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-25 13:46:56.078  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 13:46:56.078  5026  5026 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-25 13:46:56.082  4993  5039 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-25 13:46:56.083  4993  5039 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-25 13:46:56.083  4993  5039 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-25 13:46:56.084  3937  3937 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-25 13:46:56.084  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 13:46:56.085  5026  5026 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-25 13:46:56.086  5026  5041 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6056947 HexData = [00000000ec03000000000000ffffffff]
,11-25 13:46:56.086  5026  5041 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 13:46:56.086  5026  5041 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-25 13:46:56.089   928  5748 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
11-25 13:46:56.091  4050  4050 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-25 13:46:56.094  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-25 13:46:56.094  4993  5003 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-25 13:46:56.096  4050  4050 D SystemUpdateService: onCreate
,11-25 13:46:56.100  4050  4050 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-25 13:46:56.101  5026  5041 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6056947 HexData = [00000000ed03000000000000ffffffff]
11-25 13:46:56.101  5026  5041 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 13:46:56.101  5026  5041 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-25 13:46:56.102  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 13:46:56.102  4993  5004 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-25 13:46:56.113  4050  4050 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-25 13:46:56.120  4050  5761 I SystemUpdateService: active receiver: enabled
,11-25 13:46:56.124  4050  4050 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-25 13:46:56.125  4050  4050 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-25 13:46:56.127  5698  5698 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-25 13:46:56.131  5698  5698 D SprintDMHelper: simOperator: 
11-25 13:46:56.131  5698  5698 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-25 13:46:56.132  4050  5349 I iu.UploadsManager: num queued entries: 0
,11-25 13:46:56.150   928  5748 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 25 Nov 2016 12:46:56 GMT], X-Android-Received-Millis=[1480078016144], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480078016120]}
,11-25 13:46:56.151   928  2946 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-25 13:46:56.151   928  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,11-25 13:46:56.151   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-25 13:46:56.152   928  2946 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-25 13:46:56.153  4050  5349 I iu.UploadsManager: num updated entries: 0
11-25 13:46:56.154  4050  5349 I iu.SyncManager: NEXT; no task
,11-25 13:46:56.166  4050  5761 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-25 13:46:56.173  4050  5761 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-25 13:46:56.173  4050  5761 I SystemUpdateService: now status is 0 (complete)
11-25 13:46:56.173  4050  5761 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-25 13:46:56.173  4050  5761 I SystemUpdateService: file has been verified
11-25 13:46:56.173  4050  5761 I SystemUpdateService: OTA package size = 21989297
,11-25 13:46:56.182  4050  5761 I SystemUpdateService: showing system update notification
,11-25 13:46:56.190   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-25 13:46:56.191  4050  4050 D SystemUpdateService: onDestroy
,11-25 13:46:56.247  4474  5765 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-25 13:46:56.253   928  3389 D WifiService: setWifiEnabled: false pid=5573, uid=10077
,11-25 13:46:56.253   928  3389 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 13:46:56.254   928  2944 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-25 13:46:56.255   928  2944 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-25 13:46:56.255   928  2944 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-25 13:46:56.255   928  2944 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 13:46:56.264   928  5750 D DhcpClient: Clearing IP address
11-25 13:46:56.264   508   919 D CommandListener: Clearing all IP addresses on wlan0
,11-25 13:46:56.266   508   919 D CommandListener: Setting iface cfg
,11-25 13:46:56.267  3556  5771 V NativeCrypto: Read error: ssl=0x7f72945b80: I/O error during system call, Connection timed out
11-25 13:46:56.268  3556  5771 V NativeCrypto: SSL shutdown failed: ssl=0x7f72945b80: I/O error during system call, Broken pipe
,11-25 13:46:56.274   928   939 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
,11-25 13:46:56.274   928  5748 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
,11-25 13:46:56.274   928  5748 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-25 13:46:56.279   928  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-25 13:46:56.279   928  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-25 13:46:56.281   534   534 E Parcel  : Reading a NULL string not supported here.
11-25 13:46:56.281   928   928 D RttService: SCAN_AVAILABLE : 1
11-25 13:46:56.281   928  3054 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-25 13:46:56.283   928  5748 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:81d::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,11-25 13:46:56.285   928  2946 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,11-25 13:46:56.287   928  2944 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-25 13:46:56.287  3722  3844 W QCNEJ   : |CORE| network lost: 101
11-25 13:46:56.287  3722  3844 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-25 13:46:56.289   928  2944 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-25 13:46:56.290   928  5751 D DhcpClient: Receive thread stopped
,11-25 13:46:56.309   508   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 13:46:56.327   508   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 13:46:56.327   508   919 D CommandListener: Clearing all IP addresses on wlan0
11-25 13:46:56.327   928  2946 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-25 13:46:56.328   928  2946 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-25 13:46:56.329   928   945 D Tethering: MasterInitialState.processMessage what=3
,11-25 13:46:56.331  5573  5573 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:46:56.331  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:46:56.331  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:46:56.331  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:46:56.331  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:46:56.331  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 13:46:56.331  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 13:46:56.331  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 13:46:56.331  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 13:46:56.331  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 13:46:56.332  5573  5573 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:46:56.332  5573  5573 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 13:46:56.332   928  2944 D DhcpClient: doQuit
,11-25 13:46:56.332   928  2944 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-25 13:46:56.332   928  5750 D DhcpClient: onQuitting
11-25 13:46:56.333  5743  5743 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-25 13:46:56.336  5573  5573 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:46:56.336  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:46:56.336  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:46:56.336  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:46:56.336  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 13:46:56.336  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 13:46:56.336  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 13:46:56.336  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 13:46:56.336  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 13:46:56.336  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 13:46:56.337  5573  5573 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:46:56.337  5573  5573 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 13:46:56.335  3937  3937 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-25 13:46:56.339  4050  4050 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-25 13:46:56.341  4993  5007 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-25 13:46:56.341  4993  5007 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-25 13:46:56.341  4993  5007 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-25 13:46:56.342  4993  5007 E SarControlService: no key has been found,reset the power
11-25 13:46:56.342  4993  5039 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-25 13:46:56.342  4993  5039 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-25 13:46:56.342  4993  5039 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-25 13:46:56.342  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 13:46:56.342  5026  5026 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-25 13:46:56.344  4993  5039 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-25 13:46:56.344  4993  5039 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-25 13:46:56.344  4993  5039 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-25 13:46:56.344  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 13:46:56.344  5026  5026 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-25 13:46:56.347  4050  4050 D SystemUpdateService: onCreate
,11-25 13:46:56.349  5026  5041 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6056947 HexData = [00000000ee03000000000000ffffffff]
11-25 13:46:56.349  5026  5041 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 13:46:56.349  5026  5041 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-25 13:46:56.349  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 13:46:56.349  4993  5004 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-25 13:46:56.351  5026  5041 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6056947 HexData = [00000000ef03000000000000ffffffff]
,11-25 13:46:56.351  5026  5041 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 13:46:56.351  5026  5041 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-25 13:46:56.352  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-25 13:46:56.352  4993  5003 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-25 13:46:56.353  4050  4050 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-25 13:46:56.353  5743  5743 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-25 13:46:56.358  5743  5743 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-25 13:46:56.362  4050  5781 I SystemUpdateService: active receiver: enabled
,11-25 13:46:56.364  4050  4050 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-25 13:46:56.368  4050  5349 I iu.UploadsManager: num queued entries: 0
,11-25 13:46:56.369  4050  5349 I iu.UploadsManager: num updated entries: 0
11-25 13:46:56.370  4050  5349 I iu.SyncManager: NEXT; no task
,11-25 13:46:56.373  4050  4050 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-25 13:46:56.374  4050  4050 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-25 13:46:56.376  5698  5698 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-25 13:46:56.380  5698  5698 D SprintDMHelper: simOperator: 
11-25 13:46:56.380  5698  5698 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-25 13:46:56.384   508   919 E Netd    : netlink response contains error (No such file or directory)
,11-25 13:46:56.386   928  2946 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-25 13:46:56.386   928  2946 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-25 13:46:56.389  5743  5743 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-25 13:46:56.390  4050  5781 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-25 13:46:56.393  4474  5785 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-25 13:46:56.397  4050  5781 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-25 13:46:56.397  4050  5781 I SystemUpdateService: now status is 0 (complete)
11-25 13:46:56.397  4050  5781 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-25 13:46:56.397  4050  5781 I SystemUpdateService: file has been verified
11-25 13:46:56.398  4050  5781 I SystemUpdateService: OTA package size = 21989297
,11-25 13:46:56.406  5743  5743 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-25 13:46:56.413  4050  5781 I SystemUpdateService: showing system update notification
,11-25 13:46:56.419   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-25 13:46:56.420  4050  4050 D SystemUpdateService: onDestroy
,11-25 13:46:56.510   928  2944 D wifi    : In wifi stop Hal
,11-25 13:46:56.510  4474  4474 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-25 13:46:56.511   928  2944 D wifi    : halHandle = 0x7f70e6d580, mVM = 0x7f8d44d140, mCls = 0x19ea
11-25 13:46:56.511   928  5742 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,11-25 13:46:56.512   928  5742 D WifiHAL : Got a signal to exit!!!
11-25 13:46:56.512   928  5742 I WifiHAL : Exit wifi_event_loop
11-25 13:46:56.513   928  2944 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-25 13:46:56.513   928  2944 E WifiHAL : Event processing terminated
11-25 13:46:56.514   928  2944 D wifi    : In wifi cleaned up handler
11-25 13:46:56.514   928  2944 I WifiHAL : Internal cleanup completed
,11-25 13:46:56.518  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:46:56.518  3924  4192 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-25 13:46:56.538   928  5742 D wifi    : set interface wlan0 flags (DOWN)
,11-25 13:46:56.538   928  2944 D WifiNative-HAL: HAL event thread stopped successfully
,11-25 13:46:56.744   928   945 D Tethering: InitialState.processMessage what=4
,11-25 13:46:56.750   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-25 13:46:57.061   928  2946 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-25 13:47:01.292   928   945 I ActivityManager: Start proc 5789:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-25 13:47:01.400  5789  5789 D AdapterServiceConfig: Adding HeadsetService
,11-25 13:47:01.400  5789  5789 D AdapterServiceConfig: Adding A2dpService
11-25 13:47:01.401  5789  5789 D AdapterServiceConfig: Adding HidService
11-25 13:47:01.401  5789  5789 D AdapterServiceConfig: Adding HealthService
11-25 13:47:01.401  5789  5789 D AdapterServiceConfig: Adding PanService
11-25 13:47:01.401  5789  5789 D AdapterServiceConfig: Adding GattService
11-25 13:47:01.401  5789  5789 D AdapterServiceConfig: Adding BluetoothMapService
11-25 13:47:01.401  5789  5789 D AdapterServiceConfig: Adding SapService
,11-25 13:47:01.415   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bacd7:true
,11-25 13:47:01.415  5789  5789 D BluetoothAdapterState: make() - Creating AdapterState
,11-25 13:47:01.419  5789  5789 I bt_bluedroid: init
11-25 13:47:01.419  5789  5801 I BluetoothAdapterState: Entering OffState
,11-25 13:47:01.421  5789  5802 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-25 13:47:01.421  5789  5802 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-25 13:47:01.421  5789  5802 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-25 13:47:01.421  5789  5802 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-25 13:47:01.421  5789  5789 I bt_bluedroid: get_profile_interface socket
,11-25 13:47:01.423  5789  5805 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-25 13:47:01.423  5789  5789 I bt_bluedroid: get_profile_interface sdp
11-25 13:47:01.424  5789  5805 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-25 13:47:01.428  5789  5800 I bt_bluedroid: config_hci_snoop_log
,11-25 13:47:01.429   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-25 13:47:01.433  5789  5801 D BluetoothAdapterState: Current state: OFF, message: 0
,11-25 13:47:01.433  5789  5801 D BluetoothAdapterProperties: Setting state to 14
11-25 13:47:01.433  5789  5801 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-25 13:47:01.435  5789  5801 D BluetoothBondStateMachine: make
,11-25 13:47:01.436  5789  5806 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-25 13:47:01.439  5789  5801 I BluetoothAdapterState: Entering PendingCommandState
,11-25 13:47:01.440  5789  5789 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-25 13:47:01.442  5789  5789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7222f0c
,11-25 13:47:01.444  5789  5789 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-25 13:47:01.444  5789  5789 D BtGatt.GattService: Received start request. Starting profile...
11-25 13:47:01.445  5789  5789 D BtGatt.GattService: start()
11-25 13:47:01.445  5789  5789 I bt_bluedroid: get_profile_interface gatt
,11-25 13:47:01.446  5789  5789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7222f0c
11-25 13:47:01.446  5789  5789 D BtGatt.AdvertiseManager: advertise manager created
,11-25 13:47:01.450  5789  5789 V BluetoothAdapterState: isTurningOff()=false
,11-25 13:47:01.450  5789  5789 V BluetoothAdapterState: isTurningOn()=false
11-25 13:47:01.450  5789  5789 V BluetoothAdapterState: isBleTurningOn()=true
11-25 13:47:01.450  5789  5789 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:47:01.451  5789  5801 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-25 13:47:01.452  5789  5801 I bt_bluedroid: bt_bluedroid
,11-25 13:47:01.452  5789  5802 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-25 13:47:01.453  5789  5802 I bt_hci  : start_up
,11-25 13:47:01.457  5789  5802 I bt_vendor: alloc value 0xf3e73871
,11-25 13:47:01.458  5789  5802 I bt_vendor: init
11-25 13:47:01.458  5789  5802 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-25 13:47:01.458  5789  5802 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-25 13:47:01.567  5789  5802 D bt_hci  : start_up starting async portion
,11-25 13:47:01.568  5789  5809 I bt_hci  : event_finish_startup
,11-25 13:47:01.568  5789  5809 I bt_hci_h4: hal_open
,11-25 13:47:01.568  5789  5809 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-25 13:47:01.568  5810  5810 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-25 13:47:01.570  5789  5809 I bt_userial_vendor: device fd = 54 open
,11-25 13:47:01.582  5789  5809 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-25 13:47:01.584  5789  5809 D bt_hwcfg: Chipset BCM4358A3
,11-25 13:47:01.584  5789  5809 D bt_hwcfg: Target name = [BCM4358A3]
11-25 13:47:01.584  5789  5809 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-25 13:47:01.970  5789  5809 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-25 13:47:01.971  5789  5809 D bt_hwcfg: Settlement delay -- 100 ms
,11-25 13:47:01.971  5789  5809 I bt_hwcfg: Setting fw settlement delay to 100 
,11-25 13:47:02.105  5789  5809 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-25 13:47:02.105  5789  5809 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-25 13:47:02.107  5789  5809 I bt_hwcfg: vendor lib fwcfg completed
,11-25 13:47:02.107  5789  5809 I bt_vendor: firmware callback
,11-25 13:47:02.107  5789  5809 I bt_hci  : firmware_config_callback
,11-25 13:47:02.115  5789  5812 I bt_btu  : btu_task pending for preload complete event
,11-25 13:47:02.116  5789  5812 I bt_btu_task: Bluetooth chip preload is complete
11-25 13:47:02.116  5789  5812 I bt_btu  : btu_task received preload complete event
,11-25 13:47:02.125  5789  5812 I         : BTE_InitTraceLevels -- TRC_HCI
,11-25 13:47:02.125  5789  5812 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-25 13:47:02.125  5789  5812 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-25 13:47:02.125  5789  5812 I         : BTE_InitTraceLevels -- TRC_AVDT
11-25 13:47:02.126  5789  5812 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-25 13:47:02.126  5789  5812 I         : BTE_InitTraceLevels -- TRC_A2D
11-25 13:47:02.126  5789  5812 I         : BTE_InitTraceLevels -- TRC_BNEP
11-25 13:47:02.126  5789  5812 I         : BTE_InitTraceLevels -- TRC_BTM
11-25 13:47:02.126  5789  5812 I         : BTE_InitTraceLevels -- TRC_GAP
,11-25 13:47:02.126  5789  5812 I         : BTE_InitTraceLevels -- TRC_PAN
11-25 13:47:02.126  5789  5812 I         : BTE_InitTraceLevels -- TRC_SDP
11-25 13:47:02.127  5789  5812 I         : BTE_InitTraceLevels -- TRC_GATT
11-25 13:47:02.127  5789  5812 I         : BTE_InitTraceLevels -- TRC_SMP
,11-25 13:47:02.127  5789  5812 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-25 13:47:02.127  5789  5812 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-25 13:47:02.214  5789  5812 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3df1549
11-25 13:47:02.214  5789  5812 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3df1549 
,11-25 13:47:02.227  5789  5805 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-25 13:47:02.229  5789  5805 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-25 13:47:02.230  5789  5805 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-25 13:47:02.232  5789  5805 D BluetoothAdapterProperties: Name is: Nexus 6P
11-25 13:47:02.235  5789  5805 D BluetoothAdapterProperties: Scan Mode:20
11-25 13:47:02.235  5789  5805 D BluetoothAdapterProperties: Discoverable Timeout:120
11-25 13:47:02.236  5789  5805 D bt_hci  : do_postload posting postload work item
11-25 13:47:02.236  5789  5809 I bt_hci  : event_postload
11-25 13:47:02.236  5789  5809 I bt_vendor: sco_config_cb
11-25 13:47:02.236  5789  5809 I bt_hci  : sco_config_callback postload finished.
,11-25 13:47:02.240  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:47:02.241  5789  5805 D bt_bte_conf: Device ID record 1 : primary
11-25 13:47:02.241  5789  5805 D bt_bte_conf:   vendorId            = 000f
11-25 13:47:02.241  5789  5805 D bt_bte_conf:   vendorIdSource      = 0001
11-25 13:47:02.241  5789  5805 D bt_bte_conf:   product             = 1200
11-25 13:47:02.241  5789  5805 D bt_bte_conf:   version             = 1436
,11-25 13:47:02.241  5789  5805 D bt_bte_conf:   clientExecutableURL = 
11-25 13:47:02.241  5789  5805 D bt_bte_conf:   serviceDescription  = 
11-25 13:47:02.241  5789  5805 D bt_bte_conf:   documentationURL    = 
11-25 13:47:02.242  5789  5805 D bt_bte_conf: bte_load_did_conf no section named DID2.
,11-25 13:47:02.242  5789  5802 D bt_stack_manager: event_start_up_stack finished
11-25 13:47:02.243  5789  5801 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-25 13:47:02.244  5789  5801 D BluetoothAdapterProperties: Setting state to 15
,11-25 13:47:02.244  5789  5801 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-25 13:47:02.245  5789  5801 I BluetoothAdapterState: Entering BleOnState
,11-25 13:47:02.249  5789  5809 I bt_vendor: low_power_mode_cb
,11-25 13:47:02.249  5789  5801 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-25 13:47:02.249  5789  5801 D BluetoothAdapterProperties: Setting state to 11
,11-25 13:47:02.250  5789  5801 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-25 13:47:02.255  5789  5789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7222f0c
11-25 13:47:02.256  5789  5789 D HeadsetService: Received start request. Starting profile...
11-25 13:47:02.259  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:47:02.261  5789  5789 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-25 13:47:02.261  5789  5789 D HeadsetStateMachine: make
11-25 13:47:02.268  5789  5801 I BluetoothAdapterState: Entering PendingCommandState
,11-25 13:47:02.272  5789  5789 D HeadsetStateMachine: max_hf_connections = 1
,11-25 13:47:02.272  5789  5789 I bt_bluedroid: get_profile_interface handsfree
11-25 13:47:02.273  5789  5805 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-25 13:47:02.273  5789  5805 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-25 13:47:02.276  5789  5789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7222f0c
,11-25 13:47:02.277  5789  5789 D A2dpService: Received start request. Starting profile...
,11-25 13:47:02.278  5789  5789 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-25 13:47:02.278  5789  5789 I bt_bluedroid: get_profile_interface avrcp
,11-25 13:47:02.285  5789  5789 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-25 13:47:02.285  5789  5789 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-25 13:47:02.285  5789  5789 D A2dpStateMachine: make
,11-25 13:47:02.286  5789  5789 I bt_bluedroid: get_profile_interface a2dp
,11-25 13:47:02.288  5789  5805 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-25 13:47:02.289  5789  5789 I BluetoothHidServiceJni: classInitNative: succeeds
11-25 13:47:02.290  5789  5789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7222f0c
11-25 13:47:02.291  5789  5820 D A2dpStateMachine: Enter Disconnected: -2
,11-25 13:47:02.291  5789  5789 D HidService: Received start request. Starting profile...
,11-25 13:47:02.291  5789  5789 I bt_bluedroid: get_profile_interface hidhost
11-25 13:47:02.291  5789  5789 D HidService: setHidService(): set to: null
11-25 13:47:02.291  5789  5805 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3dd256d
11-25 13:47:02.291  5789  5805 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-25 13:47:02.292  5631  5631 D BluetoothInputDevice: Proxy object connected
11-25 13:47:02.292  5789  5789 I BluetoothHealthServiceJni: classInitNative: succeeds
11-25 13:47:02.293  5789  5789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7222f0c
,11-25 13:47:02.294  5631  5631 D HidProfile: Bluetooth service connected
,11-25 13:47:02.294  5789  5789 D HealthService: Received start request. Starting profile...
,11-25 13:47:02.295  5789  5789 I bt_bluedroid: get_profile_interface health
11-25 13:47:02.297  5789  5789 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-25 13:47:02.298  5789  5789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7222f0c
11-25 13:47:02.299  3556  3556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 13:47:02.300  5631  5631 D BluetoothPan: BluetoothPAN Proxy object connected
11-25 13:47:02.300  5789  5789 D PanService: Received start request. Starting profile...
11-25 13:47:02.300  5789  5789 D BluetoothPanServiceJni: initializeNative(L110): pan
11-25 13:47:02.300  5789  5789 I bt_bluedroid: get_profile_interface pan
11-25 13:47:02.300  5631  5631 D PanProfile: Bluetooth service connected
,11-25 13:47:02.302  5789  5789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7222f0c
,11-25 13:47:02.304  5631  5631 D BluetoothMap: Proxy object connected
,11-25 13:47:02.304  5789  5789 D BluetoothMapService: Received start request. Starting profile...
11-25 13:47:02.304  5789  5789 D BluetoothMapService: start()
11-25 13:47:02.304  5631  5631 D MapProfile: Bluetooth service connected
11-25 13:47:02.304  5631  5631 D BluetoothMap: getConnectedDevices()
11-25 13:47:02.305  5631  5631 D BluetoothMap: Bluetooth is Not enabled
,11-25 13:47:02.307  5789  5789 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-25 13:47:02.308  5789  5789 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-25 13:47:02.308  5789  5805 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-25 13:47:02.308  5789  5789 D BluetoothMapAppObserver: createReceiver()
11-25 13:47:02.309  5789  5789 D BluetoothMapAppObserver: initObservers()
11-25 13:47:02.309  5789  5789 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-25 13:47:02.319  5789  5789 V SapService: SapBinder()
,11-25 13:47:02.319  5789  5789 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7222f0c
,11-25 13:47:02.320  5789  5789 D SapService: Received start request. Starting profile...
11-25 13:47:02.320  5789  5789 V SapService: start()
,11-25 13:47:02.323  5789  5789 V BluetoothAdapterState: isTurningOff()=false
,11-25 13:47:02.323  5789  5789 V BluetoothAdapterState: isTurningOn()=true
11-25 13:47:02.323  5789  5789 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:47:02.323  5789  5789 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:47:02.323  5789  5789 V BluetoothAdapterState: isTurningOff()=false
11-25 13:47:02.323  5789  5789 V BluetoothAdapterState: isTurningOn()=true
11-25 13:47:02.323  5789  5789 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:47:02.323  5789  5789 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:47:02.323  5789  5818 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-25 13:47:02.323  5789  5789 V BluetoothAdapterState: isTurningOff()=false
11-25 13:47:02.323  5789  5789 V BluetoothAdapterState: isTurningOn()=true
11-25 13:47:02.323  5789  5789 V BluetoothAdapterState: isBleTurningOn()=false
,11-25 13:47:02.323  5789  5789 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 13:47:02.324  5789  5789 V BluetoothAdapterState: isTurningOff()=false
11-25 13:47:02.324  5789  5789 V BluetoothAdapterState: isTurningOn()=true
11-25 13:47:02.324  5789  5789 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:47:02.324  5789  5789 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:47:02.324  5789  5789 V BluetoothAdapterState: isTurningOff()=false
11-25 13:47:02.324  5789  5789 V BluetoothAdapterState: isTurningOn()=true
11-25 13:47:02.324  5789  5789 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:47:02.324  5789  5789 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:47:02.324  5789  5789 V BluetoothAdapterState: isTurningOff()=false
11-25 13:47:02.324  5789  5789 V BluetoothAdapterState: isTurningOn()=true
11-25 13:47:02.324  5789  5789 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:47:02.325  5789  5789 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 13:47:02.326  5789  5789 V BluetoothAdapterState: isTurningOff()=false
11-25 13:47:02.326  5789  5789 V BluetoothAdapterState: isTurningOn()=true
11-25 13:47:02.326  5789  5789 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:47:02.326  5789  5789 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:47:02.326  5789  5801 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-25 13:47:02.326  5789  5801 D BluetoothAdapterProperties: ScanMode =  20
11-25 13:47:02.326  5789  5801 D BluetoothAdapterProperties: State =  11
11-25 13:47:02.326  5789  5801 D BluetoothAdapterProperties: Setting state to 12
11-25 13:47:02.327  5789  5801 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-25 13:47:02.327  5789  5801 I BluetoothAdapterState: Entering OnState
11-25 13:47:02.327  5789  5805 D BluetoothAdapterProperties: Scan Mode:21
,11-25 13:47:02.327  5631  5643 D BluetoothPbap: onBluetoothStateChange: up=true
11-25 13:47:02.327  5789  5805 D BluetoothAdapterProperties: Discoverable Timeout:120
11-25 13:47:02.328  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-25 13:47:02.329  3089  3104 D BluetoothMap: onBluetoothStateChange: up=true
11-25 13:47:02.331  3089  3089 D BluetoothMap: Proxy object connected
11-25 13:47:02.331  3089  3101 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-25 13:47:02.331  3089  3089 D MapProfile: Bluetooth service connected
,11-25 13:47:02.331  3089  3089 D BluetoothMap: getConnectedDevices()
11-25 13:47:02.332  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:47:02.332  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:47:02.332  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:47:02.332  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 13:47:02.332  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 13:47:02.332  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 13:47:02.332  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 13:47:02.332  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 13:47:02.332  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 13:47:02.333  5631  5647 D BluetoothPan: onBluetoothStateChange on: true
11-25 13:47:02.333  5631  5643 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-25 13:47:02.333  3089  3089 D BluetoothInputDevice: Proxy object connected
11-25 13:47:02.333  3089  3089 D HidProfile: Bluetooth service connected
11-25 13:47:02.333   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 13:47:02.333  3089  3104 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 13:47:02.334  5573  5573 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 13:47:02.334   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-25 13:47:02.335  3089  3101 D BluetoothA2dp: onBluetoothStateChange: up=true
11-25 13:47:02.335   928   928 D BluetoothA2dp: Proxy object connected
11-25 13:47:02.337  3089  3089 D BluetoothA2dp: Proxy object connected
11-25 13:47:02.337   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 13:47:02.337  3748  3985 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 13:47:02.338  5631  5647 D BluetoothMap: onBluetoothStateChange: up=true
11-25 13:47:02.338   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-25 13:47:02.339  3089  3959 D BluetoothPan: onBluetoothStateChange on: true
11-25 13:47:02.339  5789  5789 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-25 13:47:02.340  5789  5789 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-25 13:47:02.341  3089  3104 D BluetoothPbap: onBluetoothStateChange: up=true
11-25 13:47:02.341  3089  3089 D BluetoothPan: BluetoothPAN Proxy object connected
11-25 13:47:02.341  3089  3089 D PanProfile: Bluetooth service connected
11-25 13:47:02.341  5789  5789 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 13:47:02.345  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-25 13:47:02.345   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
11-25 13:47:02.346  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:47:02.347  5789  5789 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 13:47:02.349  5789  5789 D ObexServerSockets: Succeed to create listening sockets 
,11-25 13:47:02.349  5789  5789 D ObexServerSockets0: startAccept()
11-25 13:47:02.349  5789  5789 D ObexServerSockets0: prepareForNewConnect()
11-25 13:47:02.349  5631  5631 D LocalBluetoothProfileManager: Adding local A2DP profile
11-25 13:47:02.351  5789  5789 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-25 13:47:02.351  5789  5789 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-25 13:47:02.352  5789  5789 D BluetoothMapService: onReceive
,11-25 13:47:02.352  5789  5827 D ObexServerSockets0: Accepting socket connection...
11-25 13:47:02.353  5789  5789 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-25 13:47:02.353  5789  5828 D ObexServerSockets0: Accepting socket connection...
11-25 13:47:02.353  5789  5789 D BluetoothMapService: STATE_ON
,11-25 13:47:02.353  5631  5631 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-25 13:47:02.354  5789  5829 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 13:47:02.358  5789  5829 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-25 13:47:02.358  5789  5829 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-25 13:47:02.360  5631  5631 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-25 13:47:02.362  5631  5631 D BluetoothA2dp: Proxy object connected
,11-25 13:47:02.366  3556  3556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 13:47:02.368  5631  5631 D DockEventReceiver: finishStartingService: stopping service
,11-25 13:47:02.375  5631  5631 D BluetoothPbap: Proxy object connected
,11-25 13:47:02.375  5631  5631 D PbapServerProfile: Bluetooth service connected
,11-25 13:47:02.377  3089  3089 D BluetoothPbap: Proxy object connected
,11-25 13:47:02.377  3089  3089 D PbapServerProfile: Bluetooth service connected
,11-25 13:47:02.381  5789  5789 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-25 13:47:02.381  5789  5789 D ObexServerSockets0: prepareForNewConnect()
11-25 13:47:02.383  5789  5833 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 13:47:02.395  5789  5837 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 13:47:02.397  5789  5837 I BtOppRfcommListener: Accept thread started.
,11-25 13:47:02.434   928   928 D BluetoothHeadset: Proxy object connected
,11-25 13:47:02.434   928   928 D BluetoothHeadset: Proxy object connected
11-25 13:47:02.434   928   928 D BluetoothHeadset: Proxy object connected
11-25 13:47:02.435  3089  3101 D BluetoothHeadset: Proxy object connected
11-25 13:47:02.435  3089  3089 D HeadsetProfile: Bluetooth service connected
11-25 13:47:02.435  3748  3769 D BluetoothHeadset: Proxy object connected
11-25 13:47:02.437   928   945 D BluetoothHeadset: Proxy object connected
,11-25 13:47:02.438  3748  3765 D BluetoothHeadset: Proxy object connected
,11-25 13:47:02.439   928   945 D BluetoothHeadset: Proxy object connected
,11-25 13:47:02.457  5631  5647 D BluetoothHeadset: Proxy object connected
,11-25 13:47:02.459  5631  5631 D HeadsetProfile: Bluetooth service connected
,11-25 13:47:04.018   928  2946 D ConnectivityService: handlePromptUnvalidated 101
,11-25 13:47:04.462  3637  3815 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-25 13:47:04.462  3637  3815 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-25 13:47:04.490  3556  3556 I ConfigService: onCreate
,11-25 13:47:06.271  5789  5801 D BluetoothAdapterState: Current state: ON, message: 23
,11-25 13:47:06.271  5789  5801 D BluetoothAdapterProperties: Setting state to 13
11-25 13:47:06.271  5789  5801 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-25 13:47:06.272  5789  5801 D BluetoothAdapterProperties: onBluetoothDisable()
,11-25 13:47:06.275  5789  5801 I BluetoothAdapterState: Entering PendingCommandState
,11-25 13:47:06.285  5789  5789 D BluetoothMapService: onReceive
11-25 13:47:06.285  5789  5789 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-25 13:47:06.285  5789  5789 D BluetoothMapService: STATE_TURNING_OFF
11-25 13:47:06.286  5789  5789 D BluetoothMapService: MAP Service closeService in
,11-25 13:47:06.286  5789  5789 D BluetoothMapMasInstance0: MAP Service shutdown
11-25 13:47:06.286  5789  5789 D ObexServerSockets0: shutdown(block = true)
11-25 13:47:06.288  5789  5789 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-25 13:47:06.288  5789  5789 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-25 13:47:06.288  5789  5827 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-25 13:47:06.288  5789  5814 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-25 13:47:06.289  5573  5573 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:47:06.289  5789  5828 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-25 13:47:06.289  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:47:06.289  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:47:06.289  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:47:06.289  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 13:47:06.289  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 13:47:06.289  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 13:47:06.289  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 13:47:06.289  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 13:47:06.289  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 13:47:06.290  5789  5805 D BluetoothAdapterProperties: Scan Mode:20
11-25 13:47:06.290  5789  5801 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-25 13:47:06.291  5789  5789 I BtOppRfcommListener: stopping Accept Thread
11-25 13:47:06.291  5573  5573 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 13:47:06.291  5789  5837 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-25 13:47:06.291  5573  5573 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 13:47:06.292  5789  5837 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-25 13:47:06.294  5631  5631 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-25 13:47:06.295  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:47:06.302  5631  5631 D DockEventReceiver: finishStartingService: stopping service
,11-25 13:47:06.304  5789  5789 D HeadsetService: Received stop request...Stopping profile...
,11-25 13:47:06.307  5631  5647 D BluetoothHeadset: Proxy object disconnected
11-25 13:47:06.307   928   928 D BluetoothHeadset: Proxy object disconnected
11-25 13:47:06.307   928   928 D BluetoothHeadset: Proxy object disconnected
,11-25 13:47:06.307   928   928 D BluetoothHeadset: Proxy object disconnected
11-25 13:47:06.307  5789  5789 D A2dpService: Received stop request...Stopping profile...
11-25 13:47:06.307  3089  3958 D BluetoothHeadset: Proxy object disconnected
11-25 13:47:06.307  5789  5820 D A2dpStateMachine: Exit Disconnected: -1
11-25 13:47:06.308  3089  3089 D HeadsetProfile: Bluetooth service disconnected
11-25 13:47:06.308  3748  3985 D BluetoothHeadset: Proxy object disconnected
,11-25 13:47:06.309  3089  3089 D BluetoothA2dp: Proxy object disconnected
11-25 13:47:06.310   928   928 D BluetoothA2dp: Proxy object disconnected
,11-25 13:47:06.310  5789  5789 D HidService: Received stop request...Stopping profile...
11-25 13:47:06.311  5789  5789 D HidService: Stopping Bluetooth HidService
11-25 13:47:06.311  5631  5631 D HeadsetProfile: Bluetooth service disconnected
11-25 13:47:06.311  3089  3089 D BluetoothInputDevice: Proxy object disconnected
11-25 13:47:06.311  3089  3089 D HidProfile: Bluetooth service disconnected
11-25 13:47:06.311  5631  5631 D BluetoothA2dp: Proxy object disconnected
11-25 13:47:06.312  5631  5631 D BluetoothInputDevice: Proxy object disconnected
11-25 13:47:06.312  5631  5631 D HidProfile: Bluetooth service disconnected
11-25 13:47:06.312  5789  5789 D HealthService: Received stop request...Stopping profile...
,11-25 13:47:06.315  3556  3556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 13:47:06.316  5789  5789 D PanService: Received stop request...Stopping profile...
,11-25 13:47:06.317  3089  3089 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-25 13:47:06.317  3089  3089 D PanProfile: Bluetooth service disconnected
11-25 13:47:06.317  5789  5789 D BluetoothMapService: Received stop request...Stopping profile...
11-25 13:47:06.317  5631  5631 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-25 13:47:06.317  5631  5631 D PanProfile: Bluetooth service disconnected
11-25 13:47:06.317  5789  5789 D BluetoothMapService: stop()
11-25 13:47:06.318  5789  5789 D BluetoothMapAppObserver: deinitObservers()
11-25 13:47:06.318  5789  5789 D BluetoothMapAppObserver: removeReceiver()
11-25 13:47:06.319  3089  3089 D BluetoothMap: Proxy object disconnected
,11-25 13:47:06.319  3089  3089 D MapProfile: Bluetooth service disconnected
11-25 13:47:06.319  5631  5631 D BluetoothMap: Proxy object disconnected
11-25 13:47:06.319  5789  5789 D SapService: Received stop request...Stopping profile...
11-25 13:47:06.319  5631  5631 D MapProfile: Bluetooth service disconnected
11-25 13:47:06.319  5789  5789 V SapService: stop()
,11-25 13:47:06.322  5789  5789 V BluetoothAdapterState: isTurningOff()=true
,11-25 13:47:06.322  5789  5789 V BluetoothAdapterState: isTurningOn()=false
11-25 13:47:06.322  5789  5789 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:47:06.322  5789  5789 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:47:06.323  5789  5789 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-25 13:47:06.324  5789  5789 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-25 13:47:06.324  5789  5789 V BluetoothAdapterState: isTurningOff()=true
11-25 13:47:06.324  5789  5789 V BluetoothAdapterState: isTurningOn()=false
11-25 13:47:06.324  5789  5789 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:47:06.324  5789  5789 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 13:47:06.325  5789  5789 V BluetoothAdapterState: isTurningOff()=true
11-25 13:47:06.325  5789  5789 V BluetoothAdapterState: isTurningOn()=false
11-25 13:47:06.325  5789  5789 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:47:06.325  5789  5789 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 13:47:06.325  5789  5789 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-25 13:47:06.325  5789  5789 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-25 13:47:06.325  5789  5789 V BluetoothAdapterState: isTurningOff()=true
11-25 13:47:06.325  5789  5789 V BluetoothAdapterState: isTurningOn()=false
11-25 13:47:06.326  5789  5789 V BluetoothAdapterState: isBleTurningOn()=false
,11-25 13:47:06.326  5789  5789 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:47:06.326  5789  5789 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-25 13:47:06.326  5789  5812 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:47:06.326  5789  5812 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:47:06.326  5789  5789 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-25 13:47:06.326  5789  5812 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:47:06.326  5789  5805 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-25 13:47:06.326  5789  5805 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-25 13:47:06.326  5789  5805 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-25 13:47:06.327  5789  5805 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,11-25 13:47:06.327  5789  5805 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-25 13:47:06.327  5789  5812 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:47:06.327  5789  5812 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 13:47:06.327  5789  5812 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-25 13:47:06.327  5789  5812 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-25 13:47:06.327  5789  5812 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-25 13:47:06.327  5789  5812 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-25 13:47:06.328  3089  3089 D BluetoothPbap: Proxy object disconnected
11-25 13:47:06.328  3089  3089 D PbapServerProfile: Bluetooth service disconnected
11-25 13:47:06.328  5789  5789 V BluetoothAdapterState: isTurningOff()=true
11-25 13:47:06.328  5789  5789 V BluetoothAdapterState: isTurningOn()=false
11-25 13:47:06.328  5789  5789 V BluetoothAdapterState: isBleTurningOn()=false
,11-25 13:47:06.328  5789  5789 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:47:06.329  5789  5789 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-25 13:47:06.329  5789  5789 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,11-25 13:47:06.330  5789  5789 D BluetoothMapService: MAP Service closeService in
11-25 13:47:06.331  5789  5789 V BluetoothAdapterState: isTurningOff()=true
,11-25 13:47:06.331  5789  5789 V BluetoothAdapterState: isTurningOn()=false
11-25 13:47:06.331  5789  5789 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:47:06.331  5789  5789 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:47:06.331  5789  5789 D BluetoothMapService: cleanup()
11-25 13:47:06.331  5789  5789 D BluetoothMapService: MAP Service closeService in
11-25 13:47:06.331  5789  5789 V BluetoothAdapterState: isTurningOff()=true
11-25 13:47:06.331  5789  5789 V BluetoothAdapterState: isTurningOn()=false
11-25 13:47:06.331  5789  5789 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:47:06.331  5789  5789 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:47:06.333  5631  5631 D BluetoothPbap: Proxy object disconnected
11-25 13:47:06.334  5789  5801 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-25 13:47:06.334  5789  5801 D BluetoothAdapterProperties: Setting state to 15
11-25 13:47:06.334  5789  5801 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-25 13:47:06.334  5631  5631 D PbapServerProfile: Bluetooth service disconnected
11-25 13:47:06.334  5789  5801 I BluetoothAdapterState: Entering BleOnState
11-25 13:47:06.334  5631  5643 D BluetoothPbap: onBluetoothStateChange: up=false
11-25 13:47:06.335  3089  3958 D BluetoothMap: onBluetoothStateChange: up=false
,11-25 13:47:06.336  5631  5647 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-25 13:47:06.337  3089  3104 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-25 13:47:06.337  5631  5643 D BluetoothPan: onBluetoothStateChange on: false
11-25 13:47:06.338  5631  5647 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-25 13:47:06.338   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 13:47:06.339  3089  3101 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 13:47:06.339  5631  5643 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 13:47:06.339   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-25 13:47:06.339  3089  3959 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 13:47:06.340   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 13:47:06.340  3748  3769 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 13:47:06.340  5631  5647 D BluetoothMap: onBluetoothStateChange: up=false
11-25 13:47:06.341   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 13:47:06.341  3089  3958 D BluetoothPan: onBluetoothStateChange on: false
11-25 13:47:06.341  3089  3104 D BluetoothPbap: onBluetoothStateChange: up=false
11-25 13:47:06.342  5789  5801 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-25 13:47:06.342  5789  5801 D BluetoothAdapterProperties: Setting state to 16
11-25 13:47:06.342  5789  5801 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-25 13:47:06.343  5789  5801 D BluetoothAdapterProperties: onBleDisable
11-25 13:47:06.343  5789  5801 I BluetoothAdapterState: Entering PendingCommandState
11-25 13:47:06.343  5789  5802 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-25 13:47:06.345  5789  5805 D BluetoothAdapterProperties: Scan Mode:20
11-25 13:47:06.345  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:47:06.345  5789  5812 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-25 13:47:06.345  5789  5812 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-25 13:47:06.346  5631  5631 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-25 13:47:06.349  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:47:06.352  5631  5631 D DockEventReceiver: finishStartingService: stopping service
11-25 13:47:06.352  3556  3556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 13:47:06.556  5789  5805 I bt_hci  : shut_down
,11-25 13:47:06.565  5789  5809 D bt_hwcfg: hw_epilog_process
,11-25 13:47:06.566  5789  5809 I bt_vendor: low_power_mode_cb
,11-25 13:47:06.568  5789  5809 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-25 13:47:06.569  5789  5809 I bt_vendor: epilog_cb
,11-25 13:47:06.569  5789  5809 I bt_hci  : epilog_finished_callback
,11-25 13:47:06.573  5789  5805 I bt_hci_h4: hal_close
,11-25 13:47:06.574  5789  5805 I bt_userial_vendor: device fd = 54 close
,11-25 13:47:06.696  5789  5802 D bt_stack_manager: event_shut_down_stack finished.
,11-25 13:47:06.697  5789  5801 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-25 13:47:06.702  5789  5801 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-25 13:47:06.702  5789  5789 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-25 13:47:06.704  5789  5789 D BtGatt.GattService: Received stop request...Stopping profile...
,11-25 13:47:06.704  5789  5789 D BtGatt.GattService: stop()
11-25 13:47:06.704  5789  5789 D BtGatt.AdvertiseManager: advertise clients cleared
11-25 13:47:06.708  5789  5789 V BluetoothAdapterState: isTurningOff()=false
11-25 13:47:06.708  5789  5789 V BluetoothAdapterState: isTurningOn()=false
,11-25 13:47:06.708  5789  5789 V BluetoothAdapterState: isBleTurningOn()=false
,11-25 13:47:06.708  5789  5789 V BluetoothAdapterState: isBleTurningOff()=true
,11-25 13:47:06.708  5789  5801 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-25 13:47:06.709  5789  5801 D BluetoothAdapterProperties: Setting state to 10
,11-25 13:47:06.709  5789  5801 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,11-25 13:47:06.710  5789  5801 I BluetoothAdapterState: Entering OffState
,11-25 13:47:06.711   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-25 13:47:06.724  5789  5789 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-25 13:47:06.724  5789  5789 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-25 13:47:06.724  5789  5789 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-25 13:47:06.726  5789  5802 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-25 13:47:06.732  5789  5789 I art     : System.exit called, status: 0
,11-25 13:47:06.732  5789  5789 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-25 13:47:06.758   928  3744 I ActivityManager: Process com.android.bluetooth (pid 5789) has died
,11-25 13:47:09.523  3556  3556 I ConfigService: onDestroy
,11-25 13:47:10.411   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-25 13:47:10.411   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-25 13:47:11.271  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 13:47:11.271  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-25 13:47:11.277  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:47:11.278  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@641316a removed from the list
11-25 13:47:11.278  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 13:47:11.280  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:47:11.280  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@427efd1 added. We now have 4 listener(s)
11-25 13:47:11.281  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:47:11.282  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:47:11.283  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@427efd1 removed from the list
11-25 13:47:11.283  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:47:11.285  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 13:47:11.286  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cb8fa36 added. We now have 4 listener(s)
11-25 13:47:11.287  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 13:47:16.299  5573  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 13:47:16.338   928   945 I ActivityManager: Start proc 5846:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-25 13:47:16.434  5846  5846 D AdapterServiceConfig: Adding HeadsetService
,11-25 13:47:16.434  5846  5846 D AdapterServiceConfig: Adding A2dpService
,11-25 13:47:16.434  5846  5846 D AdapterServiceConfig: Adding HidService
11-25 13:47:16.435  5846  5846 D AdapterServiceConfig: Adding HealthService
,11-25 13:47:16.435  5846  5846 D AdapterServiceConfig: Adding PanService
11-25 13:47:16.435  5846  5846 D AdapterServiceConfig: Adding GattService
,11-25 13:47:16.435  5846  5846 D AdapterServiceConfig: Adding BluetoothMapService
,11-25 13:47:16.435  5846  5846 D AdapterServiceConfig: Adding SapService
,11-25 13:47:16.449   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a301733:true
,11-25 13:47:16.449  5846  5846 D BluetoothAdapterState: make() - Creating AdapterState
,11-25 13:47:16.452  5846  5846 I bt_bluedroid: init
11-25 13:47:16.453  5846  5858 I BluetoothAdapterState: Entering OffState
,11-25 13:47:16.455  5846  5859 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-25 13:47:16.455  5846  5859 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-25 13:47:16.455  5846  5859 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,11-25 13:47:16.455  5846  5859 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-25 13:47:16.457  5846  5846 I bt_bluedroid: get_profile_interface socket
,11-25 13:47:16.458  5846  5846 I bt_bluedroid: get_profile_interface sdp
,11-25 13:47:16.459  5846  5862 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-25 13:47:16.460  5846  5862 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-25 13:47:16.464  5846  5857 I bt_bluedroid: config_hci_snoop_log
11-25 13:47:16.465   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-25 13:47:16.469  5846  5858 D BluetoothAdapterState: Current state: OFF, message: 0
,11-25 13:47:16.469  5846  5858 D BluetoothAdapterProperties: Setting state to 14
11-25 13:47:16.469  5846  5858 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-25 13:47:16.471  5846  5858 D BluetoothBondStateMachine: make
,11-25 13:47:16.473  5846  5863 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-25 13:47:16.476  5846  5858 I BluetoothAdapterState: Entering PendingCommandState
11-25 13:47:16.477  5846  5846 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-25 13:47:16.480  5846  5846 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7222f0c
,11-25 13:47:16.481  5846  5846 D BtGatt.DebugUtils: handleDebugAction() action=null
11-25 13:47:16.481  5846  5846 D BtGatt.GattService: Received start request. Starting profile...
11-25 13:47:16.481  5846  5846 D BtGatt.GattService: start()
,11-25 13:47:16.481  5846  5846 I bt_bluedroid: get_profile_interface gatt
11-25 13:47:16.482  5846  5846 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7222f0c
11-25 13:47:16.483  5846  5846 D BtGatt.AdvertiseManager: advertise manager created
,11-25 13:47:16.488  5846  5846 V BluetoothAdapterState: isTurningOff()=false
,11-25 13:47:16.488  5846  5846 V BluetoothAdapterState: isTurningOn()=false
11-25 13:47:16.489  5846  5846 V BluetoothAdapterState: isBleTurningOn()=true
11-25 13:47:16.489  5846  5846 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:47:16.489  5846  5858 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
11-25 13:47:16.490  5846  5858 I bt_bluedroid: bt_bluedroid
11-25 13:47:16.490  5846  5859 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-25 13:47:16.491  5846  5859 I bt_hci  : start_up
,11-25 13:47:16.499  5846  5859 I bt_vendor: alloc value 0xf3e73871
11-25 13:47:16.499  5846  5859 I bt_vendor: init
11-25 13:47:16.499  5846  5859 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,11-25 13:47:16.499  5846  5859 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-25 13:47:16.609  5846  5859 D bt_hci  : start_up starting async portion
,11-25 13:47:16.608  5867  5867 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-25 13:47:16.610  5846  5866 I bt_hci  : event_finish_startup
11-25 13:47:16.610  5846  5866 I bt_hci_h4: hal_open
11-25 13:47:16.610  5846  5866 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-25 13:47:16.613  5846  5866 I bt_userial_vendor: device fd = 54 open
,11-25 13:47:16.629  5846  5866 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-25 13:47:16.633  5846  5866 D bt_hwcfg: Chipset BCM4358A3
,11-25 13:47:16.633  5846  5866 D bt_hwcfg: Target name = [BCM4358A3]
11-25 13:47:16.633  5846  5866 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-25 13:47:17.035  5846  5866 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-25 13:47:17.036  5846  5866 D bt_hwcfg: Settlement delay -- 100 ms
11-25 13:47:17.036  5846  5866 I bt_hwcfg: Setting fw settlement delay to 100 
,11-25 13:47:17.169  5846  5866 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-25 13:47:17.170  5846  5866 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-25 13:47:17.171  5846  5866 I bt_hwcfg: vendor lib fwcfg completed
11-25 13:47:17.171  5846  5866 I bt_vendor: firmware callback
11-25 13:47:17.171  5846  5866 I bt_hci  : firmware_config_callback
,11-25 13:47:17.181  5846  5869 I bt_btu  : btu_task pending for preload complete event
,11-25 13:47:17.182  5846  5869 I bt_btu_task: Bluetooth chip preload is complete
,11-25 13:47:17.182  5846  5869 I bt_btu  : btu_task received preload complete event
,11-25 13:47:17.188  5846  5869 I         : BTE_InitTraceLevels -- TRC_HCI
,11-25 13:47:17.189  5846  5869 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-25 13:47:17.189  5846  5869 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-25 13:47:17.189  5846  5869 I         : BTE_InitTraceLevels -- TRC_AVDT
11-25 13:47:17.189  5846  5869 I         : BTE_InitTraceLevels -- TRC_AVRC
11-25 13:47:17.189  5846  5869 I         : BTE_InitTraceLevels -- TRC_A2D
,11-25 13:47:17.189  5846  5869 I         : BTE_InitTraceLevels -- TRC_BNEP
11-25 13:47:17.189  5846  5869 I         : BTE_InitTraceLevels -- TRC_BTM
,11-25 13:47:17.190  5846  5869 I         : BTE_InitTraceLevels -- TRC_GAP
11-25 13:47:17.190  5846  5869 I         : BTE_InitTraceLevels -- TRC_PAN
11-25 13:47:17.190  5846  5869 I         : BTE_InitTraceLevels -- TRC_SDP
11-25 13:47:17.190  5846  5869 I         : BTE_InitTraceLevels -- TRC_GATT
,11-25 13:47:17.190  5846  5869 I         : BTE_InitTraceLevels -- TRC_SMP
11-25 13:47:17.190  5846  5869 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-25 13:47:17.190  5846  5869 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-25 13:47:17.272  5846  5869 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3df1549
,11-25 13:47:17.273  5846  5869 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3df1549 
,11-25 13:47:17.285  5846  5862 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-25 13:47:17.286  5846  5862 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-25 13:47:17.287  5846  5862 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-25 13:47:17.291  5846  5862 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-25 13:47:17.295  5846  5862 D BluetoothAdapterProperties: Scan Mode:20
11-25 13:47:17.296  5846  5862 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-25 13:47:17.296  5846  5862 D bt_hci  : do_postload posting postload work item
11-25 13:47:17.296  5846  5866 I bt_hci  : event_postload
11-25 13:47:17.296  5846  5866 I bt_vendor: sco_config_cb
11-25 13:47:17.296  5846  5866 I bt_hci  : sco_config_callback postload finished.
,11-25 13:47:17.300  5846  5862 D bt_bte_conf: Device ID record 1 : primary
,11-25 13:47:17.300  5846  5862 D bt_bte_conf:   vendorId            = 000f
,11-25 13:47:17.300  5846  5862 D bt_bte_conf:   vendorIdSource      = 0001
,11-25 13:47:17.300  5846  5862 D bt_bte_conf:   product             = 1200
,11-25 13:47:17.300  5846  5862 D bt_bte_conf:   version             = 1436
11-25 13:47:17.300  5846  5862 D bt_bte_conf:   clientExecutableURL = 
11-25 13:47:17.300  5846  5862 D bt_bte_conf:   serviceDescription  = 
11-25 13:47:17.300  5846  5862 D bt_bte_conf:   documentationURL    = 
11-25 13:47:17.300  5846  5862 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-25 13:47:17.301  5846  5859 D bt_stack_manager: event_start_up_stack finished
,11-25 13:47:17.301  5846  5858 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-25 13:47:17.302  5846  5858 D BluetoothAdapterProperties: Setting state to 15
11-25 13:47:17.302  5846  5858 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-25 13:47:17.302  5846  5866 I bt_vendor: low_power_mode_cb
11-25 13:47:17.307  5846  5858 I BluetoothAdapterState: Entering BleOnState
,11-25 13:47:17.310  5846  5858 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-25 13:47:17.310  5846  5858 D BluetoothAdapterProperties: Setting state to 11
11-25 13:47:17.310  5846  5858 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-25 13:47:17.315  5846  5846 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7222f0c
,11-25 13:47:17.317  5846  5846 D HeadsetService: Received start request. Starting profile...
11-25 13:47:17.320  5846  5846 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-25 13:47:17.321  5846  5846 D HeadsetStateMachine: make
,11-25 13:47:17.330  5846  5858 I BluetoothAdapterState: Entering PendingCommandState
,11-25 13:47:17.331  5846  5846 D HeadsetStateMachine: max_hf_connections = 1
11-25 13:47:17.331  5846  5846 I bt_bluedroid: get_profile_interface handsfree
,11-25 13:47:17.331  5846  5862 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,11-25 13:47:17.331  5846  5862 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
11-25 13:47:17.334  5846  5846 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7222f0c
11-25 13:47:17.335  5846  5846 D A2dpService: Received start request. Starting profile...
11-25 13:47:17.335  5846  5846 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-25 13:47:17.335  5846  5846 I bt_bluedroid: get_profile_interface avrcp
,11-25 13:47:17.341  5846  5846 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-25 13:47:17.341  5846  5846 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-25 13:47:17.341  5846  5846 D A2dpStateMachine: make
,11-25 13:47:17.343  5846  5846 I bt_bluedroid: get_profile_interface a2dp
,11-25 13:47:17.344  5846  5862 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-25 13:47:17.345  5846  5877 D A2dpStateMachine: Enter Disconnected: -2
,11-25 13:47:17.347  5846  5846 I BluetoothHidServiceJni: classInitNative: succeeds
11-25 13:47:17.347  5846  5846 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7222f0c
11-25 13:47:17.348  3556  3556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 13:47:17.348  5846  5846 D HidService: Received start request. Starting profile...
11-25 13:47:17.348  5846  5846 I bt_bluedroid: get_profile_interface hidhost
11-25 13:47:17.348  5846  5846 D HidService: setHidService(): set to: null
11-25 13:47:17.348  5846  5862 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3dd256d
,11-25 13:47:17.349  5846  5862 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-25 13:47:17.349  5846  5846 I BluetoothHealthServiceJni: classInitNative: succeeds
11-25 13:47:17.350  5846  5846 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7222f0c
11-25 13:47:17.350  5846  5846 D HealthService: Received start request. Starting profile...
,11-25 13:47:17.352  5846  5846 I bt_bluedroid: get_profile_interface health
11-25 13:47:17.352  5846  5846 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-25 13:47:17.353  5846  5846 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7222f0c
,11-25 13:47:17.353  5846  5846 D PanService: Received start request. Starting profile...
11-25 13:47:17.354  5846  5846 D BluetoothPanServiceJni: initializeNative(L110): pan
11-25 13:47:17.354  5846  5846 I bt_bluedroid: get_profile_interface pan
11-25 13:47:17.356  5846  5846 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7222f0c
11-25 13:47:17.357  5846  5846 D BluetoothMapService: Received start request. Starting profile...
11-25 13:47:17.357  5846  5846 D BluetoothMapService: start()
11-25 13:47:17.359  5846  5846 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-25 13:47:17.360  5846  5846 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-25 13:47:17.360  5846  5846 D BluetoothMapAppObserver: createReceiver()
11-25 13:47:17.361  5846  5846 D BluetoothMapAppObserver: initObservers()
11-25 13:47:17.361  5846  5846 D BluetoothMapAppObserver: getEnabledAccountItems()
11-25 13:47:17.362  5846  5862 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-25 13:47:17.367  5846  5846 V SapService: SapBinder()
11-25 13:47:17.367  5846  5846 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7222f0c
11-25 13:47:17.367  5846  5846 D SapService: Received start request. Starting profile...
,11-25 13:47:17.367  5846  5846 V SapService: start()
,11-25 13:47:17.369  5846  5846 V BluetoothAdapterState: isTurningOff()=false
11-25 13:47:17.369  5846  5846 V BluetoothAdapterState: isTurningOn()=true
11-25 13:47:17.369  5846  5846 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:47:17.369  5846  5846 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 13:47:17.369  5846  5846 V BluetoothAdapterState: isTurningOff()=false
11-25 13:47:17.369  5846  5846 V BluetoothAdapterState: isTurningOn()=true
11-25 13:47:17.370  5846  5846 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:47:17.370  5846  5874 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-25 13:47:17.370  5846  5846 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:47:17.370  5846  5846 V BluetoothAdapterState: isTurningOff()=false
11-25 13:47:17.370  5846  5846 V BluetoothAdapterState: isTurningOn()=true
11-25 13:47:17.370  5846  5846 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:47:17.370  5846  5846 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 13:47:17.370  5846  5846 V BluetoothAdapterState: isTurningOff()=false
11-25 13:47:17.370  5846  5846 V BluetoothAdapterState: isTurningOn()=true
11-25 13:47:17.371  5846  5846 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:47:17.371  5846  5846 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:47:17.371  5846  5846 V BluetoothAdapterState: isTurningOff()=false
11-25 13:47:17.371  5846  5846 V BluetoothAdapterState: isTurningOn()=true
11-25 13:47:17.371  5846  5846 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:47:17.371  5846  5846 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 13:47:17.371  5846  5846 V BluetoothAdapterState: isTurningOff()=false
11-25 13:47:17.371  5846  5846 V BluetoothAdapterState: isTurningOn()=true
11-25 13:47:17.371  5846  5846 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:47:17.371  5846  5846 V BluetoothAdapterState: isBleTurningOff()=false
11-25 13:47:17.372  5846  5846 V BluetoothAdapterState: isTurningOff()=false
11-25 13:47:17.372  5846  5846 V BluetoothAdapterState: isTurningOn()=true
11-25 13:47:17.372  5846  5846 V BluetoothAdapterState: isBleTurningOn()=false
11-25 13:47:17.372  5846  5846 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 13:47:17.372  5846  5858 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-25 13:47:17.373  5846  5858 D BluetoothAdapterProperties: ScanMode =  20
11-25 13:47:17.373  5846  5858 D BluetoothAdapterProperties: State =  11
11-25 13:47:17.374  5846  5862 D BluetoothAdapterProperties: Scan Mode:21
11-25 13:47:17.374  5846  5858 D BluetoothAdapterProperties: Setting state to 12
11-25 13:47:17.374  5846  5858 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-25 13:47:17.374  5846  5862 D BluetoothAdapterProperties: Discoverable Timeout:120
11-25 13:47:17.375  5631  5647 D BluetoothPbap: onBluetoothStateChange: up=true
11-25 13:47:17.375  5846  5858 I BluetoothAdapterState: Entering OnState
11-25 13:47:17.377  3089  3958 D BluetoothMap: onBluetoothStateChange: up=true
11-25 13:47:17.378  5631  5643 D BluetoothA2dp: onBluetoothStateChange: up=true
11-25 13:47:17.379  3089  3089 D BluetoothMap: Proxy object connected
11-25 13:47:17.379  3089  3089 D MapProfile: Bluetooth service connected
11-25 13:47:17.379  3089  3089 D BluetoothMap: getConnectedDevices()
11-25 13:47:17.380  3089  3101 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-25 13:47:17.381  5631  5643 D BluetoothPan: onBluetoothStateChange on: true
11-25 13:47:17.382  3089  3089 D BluetoothInputDevice: Proxy object connected
11-25 13:47:17.382  3089  3089 D HidProfile: Bluetooth service connected
11-25 13:47:17.383  5631  5647 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-25 13:47:17.384  5631  5631 D BluetoothA2dp: Proxy object connected
11-25 13:47:17.385   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-25 13:47:17.385  3089  3104 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 13:47:17.386  5846  5846 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-25 13:47:17.386  5631  5643 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 13:47:17.386   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-25 13:47:17.386  5846  5846 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-25 13:47:17.386   928   928 D BluetoothA2dp: Proxy object connected
11-25 13:47:17.387  3089  3959 D BluetoothA2dp: onBluetoothStateChange: up=true
11-25 13:47:17.387  5846  5846 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 13:47:17.388  5631  5631 D BluetoothPan: BluetoothPAN Proxy object connected
11-25 13:47:17.388  5631  5631 D PanProfile: Bluetooth service connected
11-25 13:47:17.388  5631  5631 D BluetoothInputDevice: Proxy object connected
11-25 13:47:17.388  5631  5631 D HidProfile: Bluetooth service connected
11-25 13:47:17.389   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 13:47:17.389  5846  5846 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 13:47:17.389  3089  3089 D BluetoothA2dp: Proxy object connected
11-25 13:47:17.389  3748  3963 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 13:47:17.390  5631  5647 D BluetoothMap: onBluetoothStateChange: up=true
11-25 13:47:17.391  5846  5846 D ObexServerSockets: Succeed to create listening sockets 
11-25 13:47:17.391  5846  5846 D ObexServerSockets0: startAccept()
11-25 13:47:17.391  5846  5846 D ObexServerSockets0: prepareForNewConnect()
11-25 13:47:17.392  5631  5631 D BluetoothMap: Proxy object connected
11-25 13:47:17.392  5631  5631 D MapProfile: Bluetooth service connected
11-25 13:47:17.392  5631  5631 D BluetoothMap: getConnectedDevices()
11-25 13:47:17.392   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 13:47:17.392  3089  3958 D BluetoothPan: onBluetoothStateChange on: true
11-25 13:47:17.394  5846  5846 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-25 13:47:17.394  3089  3104 D BluetoothPbap: onBluetoothStateChange: up=true
11-25 13:47:17.394  5846  5846 D BluetoothSdpJni: SDP Create record success - handle: 0
11-25 13:47:17.394  3089  3089 D BluetoothPan: BluetoothPAN Proxy object connected
11-25 13:47:17.394  3089  3089 D PanProfile: Bluetooth service connected
11-25 13:47:17.395  5846  5885 D ObexServerSockets0: Accepting socket connection...
11-25 13:47:17.395  5846  5884 D ObexServerSockets0: Accepting socket connection...
11-25 13:47:17.397  5846  5846 D BluetoothMapService: onReceive
11-25 13:47:17.397  5846  5846 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-25 13:47:17.397  5846  5846 D BluetoothMapService: STATE_ON
11-25 13:47:17.397   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
11-25 13:47:17.399  5846  5886 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 13:47:17.401  5631  5631 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-25 13:47:17.401  5846  5886 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-25 13:47:17.401  5846  5886 D BluetoothSdpJni: SDP Create record success - handle: 1
11-25 13:47:17.405  5631  5631 D DockEventReceiver: finishStartingService: stopping service
11-25 13:47:17.408  3556  3556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 13:47:17.414  5631  5631 D BluetoothPbap: Proxy object connected
11-25 13:47:17.414  5631  5631 D PbapServerProfile: Bluetooth service connected
11-25 13:47:17.421  5846  5890 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 13:47:17.426  3089  3089 D BluetoothPbap: Proxy object connected
11-25 13:47:17.426  3089  3089 D PbapServerProfile: Bluetooth service connected
11-25 13:47:17.432  5846  5846 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-25 13:47:17.432  5846  5846 D ObexServerSockets0: prepareForNewConnect()
11-25 13:47:17.437  5846  5894 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 13:47:17.438  5846  5894 I BtOppRfcommListener: Accept thread started.
,11-25 13:47:17.487  5631  5882 D BluetoothHeadset: Proxy object connected
11-25 13:47:17.487   928   928 D BluetoothHeadset: Proxy object connected
11-25 13:47:17.487   928   928 D BluetoothHeadset: Proxy object connected
,11-25 13:47:17.487   928   928 D BluetoothHeadset: Proxy object connected
11-25 13:47:17.488  3089  3958 D BluetoothHeadset: Proxy object connected
11-25 13:47:17.488  3089  3089 D HeadsetProfile: Bluetooth service connected
11-25 13:47:17.488  3748  3985 D BluetoothHeadset: Proxy object connected
11-25 13:47:17.489   928   945 D BluetoothHeadset: Proxy object connected
,11-25 13:47:17.489  5631  5631 D HeadsetProfile: Bluetooth service connected
,11-25 13:47:17.490  3748  3769 D BluetoothHeadset: Proxy object connected
,11-25 13:47:17.492   928   945 D BluetoothHeadset: Proxy object connected
,11-25 13:47:20.413   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:47:21.314  5573  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:47:21.314  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:47:21.314  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:47:21.314  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 13:47:21.314  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 13:47:21.314  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 13:47:21.314  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 13:47:21.314  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 13:47:21.314  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-25 13:47:21.320  5573  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-25 13:47:21.320  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:47:21.321  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cb8fa36 removed from the list
,11-25 13:47:21.321  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 13:47:21.323  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:47:21.323  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c32d37 added. We now have 4 listener(s)
11-25 13:47:21.323  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 13:47:21.328   928  3744 D WifiService: setWifiEnabled: false pid=5573, uid=10077
,11-25 13:47:21.328   928  3744 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 13:47:21.413   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:47:22.414   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:47:23.415   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:47:24.416   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:47:25.417   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-25 13:47:26.337  5573  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 13:47:26.339   928  3774 D WifiService: setWifiEnabled: true pid=5573, uid=10077
,11-25 13:47:26.339   928  3774 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-25 13:47:26.348   508   919 D SoftapController: Softap fwReload - Ok
,11-25 13:47:26.354   508   919 D CommandListener: Setting iface cfg
,11-25 13:47:26.355   508   919 D CommandListener: Trying to bring down wlan0
,11-25 13:47:26.358   508   919 D CommandListener: Clearing all IP addresses on wlan0
,11-25 13:47:26.362   928  2944 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-25 13:47:27.023   928  2944 D wifi    : set interface wlan0 flags (UP)
,11-25 13:47:27.029   928  2944 I WifiHAL : Initializing wifi
11-25 13:47:27.029   928  2944 I WifiHAL : Creating socket
11-25 13:47:27.030   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-25 13:47:27.036   928  2944 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-25 13:47:27.036   928  2944 D wifi    : Did set static halHandle = 0x7f70e6d580
11-25 13:47:27.037   928  2944 D wifi    : halHandle = 0x7f70e6d580, mVM = 0x7f8d44d140, mCls = 0x2016e6
11-25 13:47:27.037   928  2944 D wifi    : array field set
11-25 13:47:27.037   928  2944 I WifiNative-HAL: interface[0] = wlan0
11-25 13:47:27.039   928  5899 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547355022720
,11-25 13:47:27.040   928  5899 D wifi    : waitForHalEvents called, vm = 0x7f8d44d140, obj = 0x2016e6, env = 0x7f75db9680
11-25 13:47:27.043   928  2944 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
11-25 13:47:27.045   928  2944 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,11-25 13:47:27.098  5900  5900 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-25 13:47:27.168  5900  5900 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-25 13:47:27.253  5900  5900 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-25 13:47:27.253  5900  5900 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-25 13:47:28.061   928  2944 D WifiConfigStore: Loading config and enabling all networks 
,11-25 13:47:28.107   928  2944 D WifiConfigStore: loaded 0 passpoint configs
,11-25 13:47:28.107   928  2944 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-25 13:47:28.108   928  2944 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-25 13:47:28.109   928  2944 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-25 13:47:28.109   928  2944 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-25 13:47:28.110   928  2944 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-25 13:47:28.111   928  2944 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-25 13:47:28.112   928  2944 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-25 13:47:28.112   928  2944 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-25 13:47:28.112   928  2944 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-25 13:47:28.112   928  2944 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-25 13:47:28.112   928  2944 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-25 13:47:28.112   928  2944 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-25 13:47:28.117   928  2944 D WifiNative-HAL: Setting external_sim to 1
,11-25 13:47:28.117  4474  4474 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-25 13:47:28.118   928  2944 D wifi    : setting dfs flag to true, 0x7f71f3fda0
11-25 13:47:28.119   928  2944 D WifiStateMachine: Setting OUI to DA-A1-19
11-25 13:47:28.119   928  2944 D wifi    : setting scan oui 0x7f71f3fda0
11-25 13:47:28.119   928  2944 D WifiHAL : Sending mac address OUI
,11-25 13:47:28.125   928  2944 E native  : do suspend false
,11-25 13:47:28.136   928  2944 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-25 13:47:28.137   928   928 D RttService: SCAN_AVAILABLE : 3
11-25 13:47:28.137   508   919 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-25 13:47:28.137   928  3054 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-25 13:47:28.138   508   919 D CommandListener: Setting iface cfg
,11-25 13:47:28.145   928  2943 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '158 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 158 Failed to set address (No such device)'
,11-25 13:47:28.145   928  2943 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-25 13:47:28.157   928  2943 D WifiNative-HAL: p2pGetDeviceAddress
,11-25 13:47:28.158   928  2943 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-25 13:47:28.166   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=237727 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=21 mControllerEnergyUsed=79 }
,11-25 13:47:30.419   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:47:31.202  5900  5900 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 13:47:31.213  5900  5900 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 13:47:31.247   928  2944 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-25 13:47:31.248   928  2944 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-25 13:47:31.249   928  2944 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 13:47:31.263   928  2944 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-25 13:47:31.302   928  2944 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-25 13:47:31.309  5900  5900 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-25 13:47:31.355  5573  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 13:47:31.355  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 13:47:31.355  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 13:47:31.355  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 13:47:31.355  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 13:47:31.355  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 13:47:31.355  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 13:47:31.355  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 13:47:31.355  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-25 13:47:31.357  5573  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-25 13:47:31.358  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:47:31.358  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c32d37 removed from the list
11-25 13:47:31.358  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:47:31.361  5573  5620 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-25 13:47:31.362  5573  5620 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-25 13:47:31.364  5573  5620 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@5983b5b Bundle[{}]
11-25 13:47:31.364  5573  5620 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-25 13:47:31.364  5573  5620 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-25 13:47:31.365  5573  5620 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-25 13:47:31.365  5573  5620 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-25 13:47:31.365  5573  5620 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,11-25 13:47:31.366  5573  5620 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-25 13:47:31.374  5573  5620 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 164)
,11-25 13:47:31.375  5573  5620 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-25 13:47:31.375  5573  5620 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 165)
,11-25 13:47:31.377  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:47:31.377  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46b32a4 added. We now have 3 listener(s)
,11-25 13:47:31.378  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-25 13:47:31.379  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:47:31.379  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:47:31.379  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:47:31.379  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eab80d added. We now have 4 listener(s)
11-25 13:47:31.379  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:47:31.380  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-25 13:47:31.381  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:47:31.382  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41283c2 added. We now have 4 listener(s)
,11-25 13:47:31.383  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:47:31.383  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-25 13:47:31.383  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:47:31.384  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:47:31.384  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1365d3 added. We now have 5 listener(s)
11-25 13:47:31.384  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:47:31.384  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:47:31.384  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:47:31.384  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:47:31.384  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:47:31.385  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:47:31.385  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 13:47:31.385  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46b32a4 removed from the list
11-25 13:47:31.385  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:47:31.385  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eab80d removed from the list
11-25 13:47:31.385  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:47:31.385  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.385  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:47:31.387  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.387  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.387  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:47:31.387  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:47:31.387  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:47:31.387  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:47:31.387  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eab80d not in the list
11-25 13:47:31.388  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.388  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.389  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.389  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.389  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.389  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:47:31.389  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:47:31.389  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:47:31.389  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1365d3 removed from the list
11-25 13:47:31.389  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:47:31.390  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 13:47:31.390  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 13:47:31.390  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41283c2 removed from the list
11-25 13:47:31.390  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:47:31.390  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77ad510 added. We now have 3 listener(s)
11-25 13:47:31.392  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:47:31.392  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:47:31.392  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:47:31.392  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:47:31.392  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@697c809 added. We now have 4 listener(s)
11-25 13:47:31.392  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:47:31.393  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-25 13:47:31.394  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:47:31.395  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d891a0e added. We now have 4 listener(s)
11-25 13:47:31.396  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:47:31.397  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:47:31.397  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-25 13:47:31.397  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:47:31.413  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e248c2f added. We now have 5 listener(s)
11-25 13:47:31.413  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 13:47:31.413  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:47:31.414  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 13:47:31.414  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 13:47:31.414  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 13:47:31.414  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-25 13:47:31.415  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-25 13:47:31.418  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 13:47:31.418  5573  5620 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 13:47:31.418  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-25 13:47:31.420   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:47:31.423  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:47:31.423  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 13:47:31.424  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 13:47:31.424  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 13:47:31.424  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-25 13:47:31.428  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.428  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 13:47:31.428  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 13:47:31.428  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 13:47:31.428  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 13:47:31.428  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:47:31.429  5573  5620 D BluetoothAdapter: STATE_ON
,11-25 13:47:31.432  5846  5857 D BtGatt.GattService: registerClient() - UUID=bf7ad56e-b8b2-4e0f-8775-2556c350c6e9
,11-25 13:47:31.433  5846  5862 D BtGatt.GattService: onClientRegistered() - UUID=bf7ad56e-b8b2-4e0f-8775-2556c350c6e9, clientIf=5
,11-25 13:47:31.434  5573  5583 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 13:47:31.435  5846  5856 D BtGatt.GattService: start scan with filters
,11-25 13:47:31.437  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 13:47:31.438  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.438  5846  5865 D BtGatt.ScanManager: handling starting scan
11-25 13:47:31.438  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 13:47:31.438  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.438  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 13:47:31.438  5573  5573 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 13:47:31.438  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.438  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 13:47:31.438  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 13:47:31.438  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.438  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.439  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.439  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-25 13:47:31.439  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 13:47:31.439  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.440  5846  5865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7222f0c
11-25 13:47:31.441  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.442  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 13:47:31.442  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.442  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.442  5573  5620 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-25 13:47:31.442  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-25 13:47:31.442  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-25 13:47:31.442  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:47:31.442  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:47:31.442  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.442  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:47:31.442  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-25 13:47:31.444  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.444  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.444  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.445  5573  5573 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 13:47:31.445  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 13:47:31.445  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.445  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 13:47:31.445  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 13:47:31.445  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:47:31.445  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.445  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.445  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 13:47:31.445  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.446  5573  5620 D BluetoothAdapter: STATE_ON
11-25 13:47:31.446  5846  5856 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-25 13:47:31.446  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 13:47:31.447  5573  5620 D BluetoothAdapter: STATE_ON
11-25 13:47:31.448  5846  5862 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 13:47:31.448  5846  5875 D BtGatt.GattService: stopScan() - queue size =1
11-25 13:47:31.448  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:47:31.449  5846  5865 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-25 13:47:31.450  5846  5857 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 13:47:31.451  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-25 13:47:31.451  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.451  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 13:47:31.451  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.451  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.451  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.451  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.451  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 13:47:31.451  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.451  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.451  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:47:31.451  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 13:47:31.451  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 13:47:31.452  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 13:47:31.452  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.453  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.453  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:47:31.453  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.453  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.454  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:47:31.454  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:47:31.454  5573  5573 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 13:47:31.454  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.454  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 13:47:31.454  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 13:47:31.454  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.454  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.454  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.454  5573  5573 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:47:31.454  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
,11-25 13:47:31.454  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.455  5846  5862 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 13:47:31.455  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:47:31.455  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.455  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.455  5846  5865 D BtGatt.ScanManager: Starting BLE batch scan
11-25 13:47:31.455  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.455  5846  5865 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-25 13:47:31.456  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:47:31.456  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:47:31.456  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:47:31.456  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:47:31.456  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:47:31.456  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 13:47:31.456  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77ad510 removed from the list
11-25 13:47:31.456  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:47:31.456  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@697c809 removed from the list
11-25 13:47:31.456  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:47:31.456  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:47:31.456  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.457  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.457  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.457  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.457  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:47:31.457  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:47:31.457  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:47:31.457  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@697c809 not in the list
11-25 13:47:31.457  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.458  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.458  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.458  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.458  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.458  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:47:31.459  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:47:31.459  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:47:31.459  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e248c2f removed from the list
11-25 13:47:31.459  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 13:47:31.459  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:47:31.459  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 13:47:31.459  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d891a0e removed from the list
11-25 13:47:31.459  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:47:31.459  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25c3628 added. We now have 3 listener(s)
11-25 13:47:31.461  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:47:31.461  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:47:31.461  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:47:31.461  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:47:31.461  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b36f41 added. We now have 4 listener(s)
11-25 13:47:31.461  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:47:31.462  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 13:47:31.463  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:47:31.463  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9925ce6 added. We now have 4 listener(s)
11-25 13:47:31.464  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:47:31.464  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:47:31.464  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:47:31.464  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:47:31.464  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b83d227 added. We now have 5 listener(s)
,11-25 13:47:31.464  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:47:31.465  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:47:31.465  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:47:31.466  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 13:47:31.466  5846  5862 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 13:47:31.466  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 13:47:31.466  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:47:31.466  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 13:47:31.466  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-25 13:47:31.467  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-25 13:47:31.470  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 13:47:31.470  5573  5620 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 13:47:31.470  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 13:47:31.471  5846  5862 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 13:47:31.471  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:47:31.473  5846  5865 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 13:47:31.474  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.475  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 13:47:31.475  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-25 13:47:31.476  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 13:47:31.476  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-25 13:47:31.478  5846  5862 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 13:47:31.478  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:47:31.479  5846  5862 E BtGatt.ContextMap: Context not found for ID 5
,11-25 13:47:31.480  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.480  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 13:47:31.480  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 13:47:31.480  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 13:47:31.480  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 13:47:31.480  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:47:31.481  5573  5620 D BluetoothAdapter: STATE_ON
,11-25 13:47:31.484  5846  5875 D BtGatt.GattService: registerClient() - UUID=08cfceb7-c7cd-46cf-b7d4-4dcf560a75fd
11-25 13:47:31.485  5846  5862 D BtGatt.GattService: onClientRegistered() - UUID=08cfceb7-c7cd-46cf-b7d4-4dcf560a75fd, clientIf=5
11-25 13:47:31.485  5573  5583 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 13:47:31.485  5846  5857 D BtGatt.GattService: start scan with filters
11-25 13:47:31.487  5846  5862 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 13:47:31.487  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:47:31.487  5846  5865 D BtGatt.ScanManager: stopping BLe Batch
,11-25 13:47:31.489  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-25 13:47:31.489  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.489  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 13:47:31.489  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.490  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 13:47:31.490  5573  5573 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 13:47:31.490  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.490  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 13:47:31.490  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-25 13:47:31.490  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.490  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.490  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.490  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.491  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 13:47:31.491  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.492  5846  5862 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-25 13:47:31.492  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:47:31.492  5846  5865 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 13:47:31.493  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.493  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 13:47:31.493  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.493  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.493  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:47:31.493  5573  5620 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-25 13:47:31.493  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:47:31.493  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.493  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 13:47:31.493  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:47:31.493  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:47:31.493  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:47:31.493  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:47:31.493  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:47:31.493  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 13:47:31.493  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25c3628 removed from the list
11-25 13:47:31.493  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:47:31.493  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b36f41 removed from the list
11-25 13:47:31.493  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:47:31.494  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:47:31.494  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:47:31.494  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.494  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-25 13:47:31.494  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-25 13:47:31.494  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:47:31.494  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:47:31.494  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.495  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.495  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:47:31.495  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.495  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:47:31.495  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:47:31.495  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:47:31.495  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b36f41 not in the list
11-25 13:47:31.495  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.495  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.495  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.495  5573  5573 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 13:47:31.495  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 13:47:31.496  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.496  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 13:47:31.496  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 13:47:31.496  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.496  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:47:31.496  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.496  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 13:47:31.496  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.497  5573  5620 D BluetoothAdapter: STATE_ON
11-25 13:47:31.497  5846  5883 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 13:47:31.497  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 13:47:31.497  5846  5862 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 13:47:31.497  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:47:31.497  5573  5620 D BluetoothAdapter: STATE_ON
11-25 13:47:31.498  5846  5857 D BtGatt.GattService: stopScan() - queue size =0
11-25 13:47:31.498  5846  5856 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 13:47:31.499  5846  5865 D BtGatt.ScanManager: handling starting scan
11-25 13:47:31.499  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 13:47:31.499  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.499  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 13:47:31.500  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:47:31.500  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.500  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:47:31.500  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.500  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 13:47:31.500  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.500  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.500  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.500  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 13:47:31.500  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 13:47:31.501  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 13:47:31.502  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.503  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.503  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:47:31.503  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:47:31.503  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.503  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:47:31.503  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:47:31.503  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:47:31.503  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:47:31.503  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b83d227 removed from the list
11-25 13:47:31.503  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:47:31.503  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:47:31.503  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:47:31.503  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 13:47:31.503  5573  5573 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 13:47:31.503  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.503  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9925ce6 removed from the list
11-25 13:47:31.503  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 13:47:31.504  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,11-25 13:47:31.504  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.504  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.504  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.504  5573  5573 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:47:31.504  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.504  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.504  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:47:31.504  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6b5a240 added. We now have 3 listener(s)
11-25 13:47:31.504  5846  5862 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 13:47:31.504  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:47:31.504  5846  5865 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 13:47:31.505  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.505  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.505  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-25 13:47:31.505  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:47:31.505  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:47:31.505  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:47:31.505  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:47:31.505  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45c579 added. We now have 4 listener(s)
11-25 13:47:31.505  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:47:31.507  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 13:47:31.507  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:47:31.507  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47622be added. We now have 4 listener(s)
11-25 13:47:31.509  5846  5862 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 13:47:31.509  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:47:31.509  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:47:31.509  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-25 13:47:31.510  5846  5865 D BtGatt.ScanManager: Starting BLE batch scan
11-25 13:47:31.510  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:47:31.510  5846  5865 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-25 13:47:31.510  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:47:31.510  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d6df1f added. We now have 5 listener(s)
11-25 13:47:31.510  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:47:31.510  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:47:31.510  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 13:47:31.510  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 13:47:31.510  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 13:47:31.511  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-25 13:47:31.512  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-25 13:47:31.515  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 13:47:31.515  5573  5620 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 13:47:31.515  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-25 13:47:31.518  5846  5862 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 13:47:31.519  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:47:31.519  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.519  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-25 13:47:31.520  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 13:47:31.520  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 13:47:31.520  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-25 13:47:31.525  5846  5862 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-25 13:47:31.525  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:47:31.525  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.525  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 13:47:31.525  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 13:47:31.525  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 13:47:31.525  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 13:47:31.525  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:47:31.526  5573  5620 D BluetoothAdapter: STATE_ON
11-25 13:47:31.526  5846  5865 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 13:47:31.527  5846  5857 D BtGatt.GattService: registerClient() - UUID=57c99092-deac-4647-a0b8-3f9832b374b1
,11-25 13:47:31.528  5846  5862 D BtGatt.GattService: onClientRegistered() - UUID=57c99092-deac-4647-a0b8-3f9832b374b1, clientIf=5
11-25 13:47:31.528  5573  5584 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-25 13:47:31.529  5846  5883 D BtGatt.GattService: start scan with filters
,11-25 13:47:31.530  5846  5862 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 13:47:31.530  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:47:31.531  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 13:47:31.532  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.532  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 13:47:31.532  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:47:31.532  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-25 13:47:31.532  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.532  5573  5573 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 13:47:31.532  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.532  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 13:47:31.532  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 13:47:31.532  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.532  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.532  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.532  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.533  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 13:47:31.533  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.535  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.535  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 13:47:31.535  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.535  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.535  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-25 13:47:31.536  5846  5862 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 13:47:31.536  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:47:31.537  5846  5865 D BtGatt.ScanManager: stopping BLe Batch
11-25 13:47:31.537  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:47:31.537  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:47:31.537  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 13:47:31.538  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 13:47:31.538  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:47:31.538  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:47:31.538  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 13:47:31.538  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 13:47:31.538  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6b5a240 removed from the list
11-25 13:47:31.538  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:47:31.538  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45c579 removed from the list
11-25 13:47:31.538  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:47:31.538  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:47:31.538  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:47:31.538  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.538  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-25 13:47:31.538  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-25 13:47:31.538  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.538  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 13:47:31.538  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 13:47:31.538  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.538  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:47:31.538  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.538  5573  5573 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 13:47:31.539  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.539  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.539  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.540  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:47:31.540  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:47:31.540  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:47:31.540  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45c579 not in the list
11-25 13:47:31.540  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 13:47:31.540  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.540  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 13:47:31.540  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 13:47:31.540  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.540  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.540  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.540  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 13:47:31.540  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:47:31.542  5573  5620 D BluetoothAdapter: STATE_ON
11-25 13:47:31.542  5846  5875 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 13:47:31.542  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 13:47:31.543  5846  5862 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-25 13:47:31.543  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:47:31.543  5573  5620 D BluetoothAdapter: STATE_ON
11-25 13:47:31.543  5846  5865 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 13:47:31.543  5846  5856 D BtGatt.GattService: stopScan() - queue size =0
11-25 13:47:31.544  5846  5857 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 13:47:31.544  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-25 13:47:31.544  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.545  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 13:47:31.545  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.545  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.545  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.545  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.545  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 13:47:31.545  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.545  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.545  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.545  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 13:47:31.545  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 13:47:31.546  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-25 13:47:31.546  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 13:47:31.547  5846  5862 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 13:47:31.547  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:47:31.547  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.548  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 13:47:31.548  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.548  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.548  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:47:31.548  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:47:31.548  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 13:47:31.548  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d6df1f removed from the list
11-25 13:47:31.548  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:47:31.548  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:47:31.548  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:47:31.548  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 13:47:31.548  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 13:47:31.548  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47622be removed from the list
11-25 13:47:31.548  5573  5573 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 13:47:31.548  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.548  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 13:47:31.548  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 13:47:31.548  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.548  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.549  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.549  5846  5865 D BtGatt.ScanManager: handling starting scan
11-25 13:47:31.549  5573  5573 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-25 13:47:31.549  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.549  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.549  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:47:31.550  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41d7958 added. We now have 3 listener(s)
11-25 13:47:31.550  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.550  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.550  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 13:47:31.551  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:47:31.551  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:47:31.551  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 13:47:31.551  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:47:31.552  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d95aab1 added. We now have 4 listener(s)
11-25 13:47:31.552  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:47:31.552  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-25 13:47:31.553  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 13:47:31.554  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a1cb96 added. We now have 4 listener(s)
,11-25 13:47:31.554  5846  5862 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 13:47:31.554  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:47:31.554  5846  5865 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 13:47:31.555  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 13:47:31.555  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 13:47:31.555  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-25 13:47:31.555  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 13:47:31.556  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ef9317 added. We now have 5 listener(s)
11-25 13:47:31.556  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 13:47:31.556  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 13:47:31.556  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 13:47:31.556  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-25 13:47:31.556  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 13:47:31.556  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:47:31.556  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 13:47:31.556  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41d7958 removed from the list
11-25 13:47:31.557  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:47:31.557  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d95aab1 removed from the list
11-25 13:47:31.557  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-25 13:47:31.557  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.557  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.558  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.558  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.558  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.558  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:47:31.559  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:47:31.559  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:47:31.559  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d95aab1 not in the list
,11-25 13:47:31.559  5846  5862 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 13:47:31.559  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.559  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:47:31.559  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.559  5846  5865 D BtGatt.ScanManager: Starting BLE batch scan
11-25 13:47:31.559  5846  5865 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-25 13:47:31.560  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.560  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.560  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 13:47:31.560  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 13:47:31.560  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 13:47:31.561  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 13:47:31.561  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ef9317 removed from the list
11-25 13:47:31.561  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 13:47:31.561  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 13:47:31.561  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 13:47:31.561  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a1cb96 removed from the list
,11-25 13:47:31.562  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-25 13:47:31.562  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-25 13:47:31.562  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-25 13:47:31.562  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:47:31.562  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-25 13:47:31.562  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-25 13:47:31.567  5846  5862 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 13:47:31.568  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:47:31.572  5846  5862 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-25 13:47:31.572  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:47:31.573  5846  5865 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 13:47:31.578  5846  5862 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 13:47:31.578  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:47:31.578  5846  5862 E BtGatt.ContextMap: Context not found for ID 5
,11-25 13:47:31.584  5846  5862 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-25 13:47:31.584  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:47:31.584  5846  5865 D BtGatt.ScanManager: stopping BLe Batch
,11-25 13:47:31.590  5846  5862 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-25 13:47:31.590  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 13:47:31.590  5846  5865 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 13:47:31.594  5846  5862 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-25 13:47:31.594  5846  5862 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 13:47:31.735  5900  5900 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-25 13:47:31.769  5900  5900 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-25 13:47:31.770  5900  5900 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-25 13:47:31.775   928  2944 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-25 13:47:31.775   928  2944 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-25 13:47:31.775   928  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-25 13:47:31.790   928  2944 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 13:47:31.800   508   919 D CommandListener: Setting iface cfg
,11-25 13:47:31.804   928  2944 D WifiStateMachine: Start Dhcp Watchdog 3
,11-25 13:47:31.810   928  5905 D DhcpClient: Receive thread started
,11-25 13:47:31.816   928  2944 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-25 13:47:31.817   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-25 13:47:31.817   928  2946 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-25 13:47:31.904   928  2944 E native  : do suspend false
,11-25 13:47:31.925   928  5904 D DhcpClient: Broadcasting DHCPDISCOVER
,11-25 13:47:31.955  5573  5573 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 13:47:31.956   928  5905 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
11-25 13:47:31.957   928  5904 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,11-25 13:47:31.958   928  5904 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-25 13:47:31.977   928  5905 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-25 13:47:31.978   928  5904 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
11-25 13:47:31.981   508   919 D CommandListener: Setting iface cfg
,11-25 13:47:31.987   928  2944 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-25 13:47:31.993   928  5904 D DhcpClient: Scheduling renewal in 86399s
,11-25 13:47:32.005  5573  5573 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 13:47:32.009   928  2944 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-25 13:47:32.010   928  2944 D WifiConfigStore: No blacklist allowed without epno enabled
,11-25 13:47:32.013   928  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-25 13:47:32.018   928  2946 D ConnectivityService: Adding iface wlan0 to network 102
,11-25 13:47:32.019   928  2944 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-25 13:47:32.049  5573  5573 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 13:47:32.066   928  2946 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-25 13:47:32.067   928  2946 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-25 13:47:32.069   928  2946 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-25 13:47:32.071   928  2946 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-25 13:47:32.073   928  2946 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-25 13:47:32.081   928  2946 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:47:32.087   928  2946 D ConnectivityService: scheduleUnvalidatedPrompt 102
11-25 13:47:32.087   928  2946 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,11-25 13:47:32.087   928  2946 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-25 13:47:32.087   928  2946 D ConnectivityService:    accepting network in place of null
11-25 13:47:32.088   928  2946 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-25 13:47:32.089   928  2944 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-25 13:47:32.090   928  2944 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-25 13:47:32.105   928  5903 D NetlinkSocketObserver: NeighborEvent{elapsedMs=241665, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 13:47:32.117   508   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 13:47:32.148   508   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 13:47:32.154   928  2946 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-25 13:47:32.154   928  2946 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-25 13:47:32.154  3722  3844 W QCNEJ   : |CORE| network available: 102
11-25 13:47:32.155   928  2946 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-25 13:47:32.156   928   945 D Tethering: MasterInitialState.processMessage what=3
11-25 13:47:32.158  3722  3844 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-25 13:47:32.160  3722  3844 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-25 13:47:32.160  3722  3844 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-25 13:47:32.173   928  5902 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-25 13:47:32.177  4993  5007 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-25 13:47:32.177  4993  5007 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,11-25 13:47:32.177  4993  5007 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-25 13:47:32.177  4993  5007 E SarControlService: no key has been found,reset the power
11-25 13:47:32.177  4993  5039 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-25 13:47:32.178  4993  5039 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-25 13:47:32.178  4993  5039 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-25 13:47:32.178  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 13:47:32.178  5026  5026 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-25 13:47:32.179  4993  5039 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-25 13:47:32.179  4993  5039 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-25 13:47:32.179  4993  5039 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-25 13:47:32.182  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 13:47:32.182  5026  5026 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-25 13:47:32.187  3937  3937 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-25 13:47:32.189  5026  5041 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6056947 HexData = [00000000f003000000000000ffffffff]
11-25 13:47:32.189  5026  5041 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 13:47:32.190  5026  5041 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
,11-25 13:47:32.190  4050  4050 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-25 13:47:32.195  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 13:47:32.195  4993  5004 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-25 13:47:32.196  4050  4050 D SystemUpdateService: onCreate
,11-25 13:47:32.202  4050  4050 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-25 13:47:32.203  5026  5041 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6056947 HexData = [00000000f103000000000000ffffffff]
11-25 13:47:32.203  5026  5041 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 13:47:32.203  5026  5041 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
11-25 13:47:32.204  5026  5026 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 13:47:32.204  4993  5003 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-25 13:47:32.217  4050  4050 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-25 13:47:32.221   928  5902 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 25 Nov 2016 12:47:32 GMT], X-Android-Received-Millis=[1480078052220], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480078052198]}
11-25 13:47:32.222   928  2946 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-25 13:47:32.222   928  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-25 13:47:32.222   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:47:32.223   928  2946 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-25 13:47:32.226  4050  5915 I SystemUpdateService: active receiver: enabled
11-25 13:47:32.227  4050  4050 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-25 13:47:32.229  4050  4050 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-25 13:47:32.231  5698  5698 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-25 13:47:32.235  5698  5698 D SprintDMHelper: simOperator: 
,11-25 13:47:32.235  5698  5698 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-25 13:47:32.248  4050  5349 I iu.UploadsManager: num queued entries: 0
,11-25 13:47:32.256  4050  5349 I iu.UploadsManager: num updated entries: 0
,11-25 13:47:32.270  4050  5915 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-25 13:47:32.273  4050  5349 I iu.SyncManager: NEXT; no task
,11-25 13:47:32.279  4050  5915 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-25 13:47:32.279  4050  5915 I SystemUpdateService: now status is 0 (complete)
11-25 13:47:32.279  4050  5915 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-25 13:47:32.279  4050  5915 I SystemUpdateService: file has been verified
11-25 13:47:32.279  4050  5915 I SystemUpdateService: OTA package size = 21989297
,11-25 13:47:32.285  4050  5915 I SystemUpdateService: showing system update notification
,11-25 13:47:32.296   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-25 13:47:32.298  4050  4050 D SystemUpdateService: onDestroy
,11-25 13:47:32.349  4474  5920 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-25 13:47:32.420   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:47:33.421   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:47:33.697  5573  5927 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 173, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-25 13:47:33.697  5573  5927 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 13:47:34.422   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:47:34.481  5573  5927 W !!      : call onHalfStreamCopied
,11-25 13:47:34.481  5573  5927 I testCopyDataAndClose: closing input stream
,11-25 13:47:35.247  5573  5927 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 173, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-25 13:47:35.247  5573  5927 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 13:47:35.247  5573  5927 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-25 13:47:35.247  5573  5927 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 13:47:35.248  5573  5927 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-25 13:47:35.248  5573  5927 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-25 13:47:35.248  5573  5927 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-25 13:47:35.248  5573  5927 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-25 13:47:35.248  5573  5927 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-25 13:47:35.248  5573  5927 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 173, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-25 13:47:35.248  5573  5927 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-25 13:47:35.422   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-25 13:47:37.868   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:47:39.624  5573  5928 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 176, name: My test thread name). Connection data: Peer properties: [null null].
11-25 13:47:39.624  5573  5928 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 13:47:40.090   928  2946 D ConnectivityService: handlePromptUnvalidated 102
,11-25 13:47:41.624  5573  5620 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 176. Connection data: Peer properties: [null null].
11-25 13:47:41.624  5573  5620 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 13:47:41.624  5573  5620 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 176, name: My test thread name)
,11-25 13:47:41.709  5573  5928 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-25 13:47:41.709  5573  5928 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 176, name: My test thread name). Connection data: Peer properties: [null null].
11-25 13:47:41.709  5573  5928 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,11-25 13:47:41.761  5573  5929 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-25 13:47:41.761  5573  5929 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 13:47:43.157   928  2944 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 15 -> obsolete
,11-25 13:47:43.384  5573  5929 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-25 13:47:43.384  5573  5929 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 13:47:43.384  5573  5929 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-25 13:47:43.384  5573  5929 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 13:47:43.384  5573  5929 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-25 13:47:43.384  5573  5929 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-25 13:47:43.384  5573  5929 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-25 13:47:43.384  5573  5929 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-25 13:47:43.384  5573  5929 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-25 13:47:43.384  5573  5929 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-25 13:47:43.384  5573  5929 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-25 13:47:43.912   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:47:45.423   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:47:46.425   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:47:47.426   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:47:47.597  5573  5931 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-25 13:47:47.597  5573  5931 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 13:47:47.598  5573  5931 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 180, thread name: My test thread name). Connection data: Peer properties: [null null].
11-25 13:47:47.598  5573  5931 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 13:47:47.598  5573  5931 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-25 13:47:47.598  5573  5931 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 13:47:47.598  5573  5931 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-25 13:47:47.598  5573  5931 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-25 13:47:47.598  5573  5931 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-25 13:47:47.598  5573  5931 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-25 13:47:47.598  5573  5931 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-25 13:47:47.599  5573  5931 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-25 13:47:47.599  5573  5931 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-25 13:47:47.600  5573  5620 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-25 13:47:47.604  5573  5932 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-25 13:47:47.604  5573  5932 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 13:47:47.604  5573  5932 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 184, thread name: My test thread name): Test exception.
11-25 13:47:47.605  5573  5932 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-25 13:47:47.605  5573  5932 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-25 13:47:47.605  5573  5932 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,11-25 13:47:47.605  5573  5932 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-25 13:47:47.605  5573  5932 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-25 13:47:47.610  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-25 13:47:47.610  5573  5620 I jxcore-log: 
11-25 13:47:47.610  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-25 13:47:47.610  5573  5620 I jxcore-log: 
11-25 13:47:47.610  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-25 13:47:47.610  5573  5620 I jxcore-log: 
11-25 13:47:47.611  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-25 13:47:47.611  5573  5620 I jxcore-log: 
,11-25 13:47:47.611  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - DEBUG UnitTest_app: 'Total duration:  91856'
11-25 13:47:47.611  5573  5620 I jxcore-log: 
,11-25 13:47:47.613  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-25 13:47:47.613  5573  5620 I jxcore-log: 
,11-25 13:47:47.617  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 13:47:47.617  5573  5620 I jxcore-log: 
,11-25 13:47:47.618  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 13:47:47.618  5573  5620 I jxcore-log: 
11-25 13:47:47.619  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-25 13:47:47.619  5573  5620 I jxcore-log: 
,11-25 13:47:47.619  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-25 13:47:47.619  5573  5620 I jxcore-log: 
11-25 13:47:47.619  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 13:47:47.619  5573  5620 I jxcore-log: 
11-25 13:47:47.620  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 13:47:47.620  5573  5620 I jxcore-log: 
11-25 13:47:47.620  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 13:47:47.620  5573  5620 I jxcore-log: 
11-25 13:47:47.620  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 13:47:47.620  5573  5620 I jxcore-log: 
,11-25 13:47:47.621  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 13:47:47.621  5573  5620 I jxcore-log: 
11-25 13:47:47.621  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-25 13:47:47.621  5573  5620 I jxcore-log: 
11-25 13:47:47.621  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-25 13:47:47.621  5573  5620 I jxcore-log: 
11-25 13:47:47.621  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 13:47:47.621  5573  5620 I jxcore-log: 
11-25 13:47:47.622  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 13:47:47.622  5573  5620 I jxcore-log: 
11-25 13:47:47.622  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 13:47:47.622  5573  5620 I jxcore-log: 
11-25 13:47:47.622  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 13:47:47.622  5573  5620 I jxcore-log: 
11-25 13:47:47.622  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 13:47:47.622  5573  5620 I jxcore-log: 
,11-25 13:47:47.622  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-25 13:47:47.622  5573  5620 I jxcore-log: 
11-25 13:47:47.623  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 13:47:47.623  5573  5620 I jxcore-log: 
11-25 13:47:47.623  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-25 13:47:47.623  5573  5620 I jxcore-log: 
11-25 13:47:47.623  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-25 13:47:47.623  5573  5620 I jxcore-log: 
11-25 13:47:47.624  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 13:47:47.624  5573  5620 I jxcore-log: 
11-25 13:47:47.624  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-25 13:47:47.624  5573  5620 I jxcore-log: 
11-25 13:47:47.624  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-25 13:47:47.624  5573  5620 I jxcore-log: 
,11-25 13:47:47.625  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-25 13:47:47.625  5573  5620 I jxcore-log: 
11-25 13:47:47.626  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-25 13:47:47.626  5573  5620 I jxcore-log: 
11-25 13:47:47.627  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-25 13:47:47.627  5573  5620 I jxcore-log: 
11-25 13:47:47.627  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-25 13:47:47.627  5573  5620 I jxcore-log: 
11-25 13:47:47.627  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 13:47:47.627  5573  5620 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-25 13:47:47.627  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 13:47:47.627  5573  5620 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-25 13:47:47.628  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 13:47:47.628  5573  5620 I jxcore-log: 
11-25 13:47:47.628  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 13:47:47.628  5573  5620 I jxcore-log: 
11-25 13:47:47.628  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 13:47:47.628  5573  5620 I jxcore-log: 
11-25 13:47:47.628  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 13:47:47.628  5573  5620 I jxcore-log: 
11-25 13:47:47.629  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 13:47:47.629  5573  5620 I jxcore-log: 
,11-25 13:47:47.629  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 13:47:47.629  5573  5620 I jxcore-log: 
11-25 13:47:47.633  5573  5573 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
11-25 13:47:47.633  5573  5573 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
11-25 13:47:47.634  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-25 13:47:47.634  5573  5620 I jxcore-log: 
11-25 13:47:47.635  5573  5620 I jxcore-log: 2016-11-25 12:47:47 - WARN testUtils: 'myNameCallback not set!'
11-25 13:47:47.635  5573  5620 I jxcore-log: 
,11-25 13:47:48.428   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:47:49.429   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:47:49.696  5573  5620 I jxcore-log: 2016-11-25 12:47:49 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-25 13:47:49.696  5573  5620 I jxcore-log: 
,11-25 13:47:49.697  5573  5620 I jxcore-log: 2016-11-25 12:47:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-25 13:47:49.697  5573  5620 I jxcore-log: 
,11-25 13:47:50.045  5573  5620 I jxcore-log: 2016-11-25 12:47:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-25 13:47:50.045  5573  5620 I jxcore-log: 
,11-25 13:47:50.056  5573  5620 I jxcore-log: 2016-11-25 12:47:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-25 13:47:50.056  5573  5620 I jxcore-log: 
,11-25 13:47:50.430   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-25 13:47:51.175  5573  5620 I jxcore-log: 2016-11-25 12:47:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-25 13:47:51.175  5573  5620 I jxcore-log: 
,11-25 13:47:51.368  5573  5620 I jxcore-log: 2016-11-25 12:47:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-25 13:47:51.368  5573  5620 I jxcore-log: 
,11-25 13:47:51.374  5573  5620 I jxcore-log: 2016-11-25 12:47:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-25 13:47:51.374  5573  5620 I jxcore-log: 
,11-25 13:47:51.379  5573  5620 I jxcore-log: 2016-11-25 12:47:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-25 13:47:51.379  5573  5620 I jxcore-log: 
,11-25 13:47:51.736   928  5903 D NetlinkSocketObserver: NeighborEvent{elapsedMs=261297, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-25 13:47:51.866  5573  5620 I jxcore-log: 2016-11-25 12:47:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-25 13:47:51.866  5573  5620 I jxcore-log: 
,11-25 13:47:51.911  5573  5620 I jxcore-log: 2016-11-25 12:47:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-25 13:47:51.911  5573  5620 I jxcore-log: 
,11-25 13:47:51.924  5573  5620 I jxcore-log: 2016-11-25 12:47:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-25 13:47:51.924  5573  5620 I jxcore-log: 
,11-25 13:47:51.928  5573  5620 I jxcore-log: 2016-11-25 12:47:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-25 13:47:51.928  5573  5620 I jxcore-log: 
,11-25 13:47:52.198  5573  5620 I jxcore-log: 2016-11-25 12:47:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-25 13:47:52.198  5573  5620 I jxcore-log: 
,11-25 13:47:52.328  5573  5620 I jxcore-log: 2016-11-25 12:47:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-25 13:47:52.328  5573  5620 I jxcore-log: 
,11-25 13:47:52.700  5573  5620 I jxcore-log: 2016-11-25 12:47:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-25 13:47:52.700  5573  5620 I jxcore-log: 
,11-25 13:47:52.708  5573  5620 I jxcore-log: 2016-11-25 12:47:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-25 13:47:52.708  5573  5620 I jxcore-log: 
,11-25 13:47:52.712  5573  5620 I jxcore-log: 2016-11-25 12:47:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-25 13:47:52.712  5573  5620 I jxcore-log: 
,11-25 13:47:52.718  5573  5620 I jxcore-log: 2016-11-25 12:47:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-25 13:47:52.718  5573  5620 I jxcore-log: 
,11-25 13:47:52.723  5573  5620 I jxcore-log: 2016-11-25 12:47:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-25 13:47:52.723  5573  5620 I jxcore-log: 
,11-25 13:47:52.750  5573  5620 I jxcore-log: 2016-11-25 12:47:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-25 13:47:52.750  5573  5620 I jxcore-log: 
,11-25 13:47:52.786  5573  5620 I jxcore-log: 2016-11-25 12:47:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-25 13:47:52.786  5573  5620 I jxcore-log: 
,11-25 13:47:52.793  5573  5620 I jxcore-log: 2016-11-25 12:47:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-25 13:47:52.793  5573  5620 I jxcore-log: 
,11-25 13:47:52.800  5573  5620 I jxcore-log: 2016-11-25 12:47:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-25 13:47:52.800  5573  5620 I jxcore-log: 
,11-25 13:47:52.815  5573  5620 I jxcore-log: 2016-11-25 12:47:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-25 13:47:52.815  5573  5620 I jxcore-log: 
,11-25 13:47:52.830  5573  5620 I jxcore-log: 2016-11-25 12:47:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-25 13:47:52.830  5573  5620 I jxcore-log: 
,11-25 13:47:52.837  5573  5620 I jxcore-log: 2016-11-25 12:47:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-25 13:47:52.837  5573  5620 I jxcore-log: 
,11-25 13:47:52.842  5573  5620 I jxcore-log: 2016-11-25 12:47:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-25 13:47:52.842  5573  5620 I jxcore-log: 
,11-25 13:47:52.855  5573  5620 I jxcore-log: 2016-11-25 12:47:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-25 13:47:52.855  5573  5620 I jxcore-log: 
,11-25 13:47:52.872  5573  5620 I jxcore-log: 2016-11-25 12:47:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-25 13:47:52.872  5573  5620 I jxcore-log: 
,11-25 13:47:52.887  5573  5620 I jxcore-log: 2016-11-25 12:47:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-25 13:47:52.887  5573  5620 I jxcore-log: 
,11-25 13:47:52.897  5573  5620 I jxcore-log: 2016-11-25 12:47:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-25 13:47:52.897  5573  5620 I jxcore-log: 
,11-25 13:47:52.910  5573  5620 I jxcore-log: 2016-11-25 12:47:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-25 13:47:52.910  5573  5620 I jxcore-log: 
,11-25 13:47:52.920  5573  5620 I jxcore-log: 2016-11-25 12:47:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-25 13:47:52.920  5573  5620 I jxcore-log: 
,11-25 13:47:52.933  5573  5620 I jxcore-log: 2016-11-25 12:47:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-25 13:47:52.933  5573  5620 I jxcore-log: 
,11-25 13:47:52.943  5573  5620 I jxcore-log: 2016-11-25 12:47:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-25 13:47:52.943  5573  5620 I jxcore-log: 
,11-25 13:47:52.950  5573  5620 I jxcore-log: 2016-11-25 12:47:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-25 13:47:52.950  5573  5620 I jxcore-log: 
,11-25 13:47:52.972  5573  5620 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-25 13:47:52.973  5573  5620 I jxcore-log: 2016-11-25 12:47:52 - INFO testUtils: 'BLE multiple advertisement supported'
11-25 13:47:52.973  5573  5620 I jxcore-log: 
,11-25 13:47:53.006  5573  5620 I jxcore-log: 2016-11-25 12:47:53 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-25 13:47:53.006  5573  5620 I jxcore-log: 
,11-25 13:47:53.284  5573  5620 I jxcore-log: 2016-11-25 12:47:53 - DEBUG CoordinatedClient: 'connected to the test server'
11-25 13:47:53.284  5573  5620 I jxcore-log: 
,11-25 13:47:55.974  5900  5900 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 13:47:58.036   928  5903 D NetlinkSocketObserver: NeighborEvent{elapsedMs=267597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 13:47:59.018   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:48:02.047   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:48:05.431   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:48:06.432   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:48:07.434   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:48:08.435   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:48:09.436   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:48:10.437   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-25 13:48:11.135   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:48:12.073   928  2944 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 13:48:14.166   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:48:29.305   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:48:30.439   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:48:31.440   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:48:32.333   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:48:32.441   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:48:33.442   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:48:34.444   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:48:35.444   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-25 13:48:37.423   928  5903 D NetlinkSocketObserver: NeighborEvent{elapsedMs=306983, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-25 13:48:44.411   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:48:48.316   928  5903 D NetlinkSocketObserver: NeighborEvent{elapsedMs=317877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 13:48:50.474   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:48:52.079   928  2944 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 13:48:56.534   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:48:59.568   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:49:00.445   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-25 13:49:00.445   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-25 13:49:02.601   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:49:05.630   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:49:12.080   928  2944 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 13:49:15.446   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:49:16.448   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:49:17.449   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:49:17.747   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:49:18.450   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:49:19.451   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:49:20.452   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-25 13:49:20.779   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:49:25.453   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:49:26.455   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:49:27.456   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:49:27.503   928  5903 D NetlinkSocketObserver: NeighborEvent{elapsedMs=357063, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-25 13:49:28.457   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:49:29.458   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:49:30.459   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-25 13:49:32.885   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:49:35.861  5900  5900 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 13:49:35.938   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:49:38.370   928  5903 D NetlinkSocketObserver: NeighborEvent{elapsedMs=367930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 13:49:40.460   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:49:41.462   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:49:42.463   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:49:43.464   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:49:44.465   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:49:45.466   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-25 13:49:51.076   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:49:52.083   928  2944 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 13:49:52.516   928  5903 D NetlinkSocketObserver: NeighborEvent{elapsedMs=382077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-25 13:49:57.135   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:50:00.468   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:50:01.468   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:50:02.469   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:50:03.423   928  5903 D NetlinkSocketObserver: NeighborEvent{elapsedMs=392984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 13:50:03.470   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:50:04.471   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:50:05.472   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-25 13:50:06.212   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:50:12.087   928  2944 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 13:50:15.290   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:50:17.529   928  5903 D NetlinkSocketObserver: NeighborEvent{elapsedMs=407090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-25 13:50:24.373   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:50:25.473   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:50:26.474   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:50:27.476   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:50:28.436   928  5903 D NetlinkSocketObserver: NeighborEvent{elapsedMs=417997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 13:50:28.477   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:50:29.478   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 13:50:30.427   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:50:30.478   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-25 13:50:32.088   928  2944 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 13:50:36.488   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:50:42.547   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:50:42.596   928  5903 D NetlinkSocketObserver: NeighborEvent{elapsedMs=432157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-25 13:50:51.620   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:50:53.476   928  5903 D NetlinkSocketObserver: NeighborEvent{elapsedMs=443037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 13:50:54.650   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:50:55.479   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-25 13:50:55.479   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-25 13:50:57.685   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:51:03.748   928  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 13:51:07.609   928  5903 D NetlinkSocketObserver: NeighborEvent{elapsedMs=457170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-25 13:51:08.159  5573  5620 I jxcore-log: 2016-11-25 12:51:08 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-25 13:51:08.159  5573  5620 I jxcore-log: 
,11-25 13:51:08.512  5573  5620 I jxcore-log: 2016-11-25 12:51:08 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-25 13:51:08.512  5573  5620 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-25 13:51:08.512  5573  5620 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-25 13:51:08.512  5573  5620 I jxcore-log: emit@events.js:82:1
11-25 13:51:08.512  5573  5620 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-25 13:51:08.512  5573  5620 I jxcore-log: emit@events.js:82:1''
11-25 13:51:08.512  5573  5620 I jxcore-log: 
,11-25 13:51:08.514  5573  5620 I jxcore-log: 2016-11-25 12:51:08 - DEBUG CoordinatedClient: 'test client failed'
11-25 13:51:08.514  5573  5620 I jxcore-log: 
,11-25 13:51:08.524  5573  5620 I jxcore-log: 2016-11-25 12:51:08 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-25 13:51:08.524  5573  5620 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-25 13:51:08.524  5573  5620 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-25 13:51:08.524  5573  5620 I jxcore-log: emit@events.js:82:1
11-25 13:51:08.524  5573  5620 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-25 13:51:08.524  5573  5620 I jxcore-log: emit@events.js:82:1''
11-25 13:51:08.524  5573  5620 I jxcore-log: 
,11-25 13:51:08.525  5573  5620 I jxcore-log: 2016-11-25 12:51:08 - DEBUG CoordinatedClient: 'test client failed'
11-25 13:51:08.525  5573  5620 I jxcore-log: 
,11-25 13:51:08.529  5573  5620 I jxcore-log: 2016-11-25 12:51:08 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-25 13:51:08.529  5573  5620 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-25 13:51:08.529  5573  5620 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-25 13:51:08.529  5573  5620 I jxcore-log: emit@events.js:82:1
11-25 13:51:08.529  5573  5620 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-25 13:51:08.529  5573  5620 I jxcore-log: emit@events.js:82:1''
11-25 13:51:08.529  5573  5620 I jxcore-log: 
11-25 13:51:08.530  5573  5620 I jxcore-log: 2016-11-25 12:51:08 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-25 13:51:08.530  5573  5620 I jxcore-log: 
,11-25 13:51:09.104  5946  5946 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-25 13:51:09.126  5946  5946 D AndroidRuntime: CheckJNI is OFF
,11-25 13:51:09.154  5946  5946 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-25 13:51:09.186  5946  5946 I Radio-JNI: register_android_hardware_Radio DONE
,11-25 13:51:09.202  5946  5946 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-25 13:51:09.211   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-25 13:51:09.212   928   941 I ActivityManager: Killing 5573:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-25 13:51:09.319   928  3774 I WindowState: WIN DEATH: Window{d08cc13 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-25 13:51:09.320   928  3636 D GraphicsStats: Buffer count: 2
,11-25 13:51:09.321   928  2945 D WifiService: Client connection lost with reason: 4
,11-25 13:51:09.329   928   941 W ActivityManager: Force removing ActivityRecord{284f5d8 u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-25 13:51:09.359   928   951 I art     : Starting a blocking GC Explicit
,11-25 13:51:09.362   928   939 W ActivityManager: Spurious death for ProcessRecord{7970746 0:com.test.thalitest/u0a77}, curProc for 5573: null
,11-25 13:51:09.398   928  3780 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5573 uid 10077
,11-25 13:51:09.399  3637  3637 I Keyboard.Facilitator: onFinishInput()
,11-25 13:51:09.395  3780  3780 W Binder_B: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[26480]" dev="sockfs" ino=26480 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-25 13:51:09.398  3780  3780 W Binder_B: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[26480]" dev="sockfs" ino=26480 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-25 13:51:09.457   928   951 I art     : Explicit concurrent mark sweep GC freed 114409(7MB) AllocSpace objects, 63(2008KB) LOS objects, 33% free, 29MB/44MB, paused 1.799ms total 96.835ms
,11-25 13:51:09.481  3937  5959 I MicroRecognitionRnrImpl: Starting detection.
,11-25 13:51:09.482  3937  5960 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@5f13e5f
,11-25 13:51:09.484   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
11-25 13:51:09.484   513  5962 I AudioFlinger: AudioFlinger's thread 0xf21c0000 ready to run
,11-25 13:51:09.486  5946  5946 I art     : System.exit called, status: 0
,11-25 13:51:09.486  5946  5946 I AndroidRuntime: VM exiting with result code 0.
,11-25 13:51:09.493   513  2966 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-25 13:51:09.495  3937  5960 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@5f13e5f
,11-25 13:51:09.505   513  5962 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
11-25 13:51:09.505   513  5962 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
,11-25 13:51:09.505   513  5962 I ACDB-LOADER: ACDB AFE returned = -19
11-25 13:51:09.505   928   951 I ActivityManager: Start proc 5964:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
11-25 13:51:09.505   513  5962 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
,11-25 13:51:09.505   513  5962 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-25 13:51:09.505   513  5962 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
11-25 13:51:09.505   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-25 13:51:09.514  3637  3637 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-25 13:51:09.515  5846  5846 D BluetoothMapAppObserver: onReceive
11-25 13:51:09.516  5846  5846 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-25 13:51:09.518   513  5962 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-25 13:51:09.523  3924  4112 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-25 13:51:09.526  3637  5974 I Keyboard.Facilitator.DecoderInitializer: run()
,11-25 13:51:09.531   928  2910 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-25 13:51:09.536  3637  5974 I Decoder : createOrResetDecoder
,11-25 13:51:09.542  3373  5978 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-25 13:51:09.584  3748  3748 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-25 13:51:09.591  3556  3556 I ConfigService: onCreate
,11-25 13:51:09.605   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-25 13:51:09.608  3937  3937 I HotwordWorkerImpl: onReady
,11-25 13:51:09.614  3637  5974 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-25 13:51:09.622  5944  5944 W kworker/1:0: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 13:51:09.624  3556  3556 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
11-25 13:51:09.624  3556  3556 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-25 13:51:09.628  5944  5944 W kworker/1:0: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 13:51:09.647  4050  5987 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-25 13:51:09.647  4050  5987 D AccountUtils: Clearing selected account for com.test.thalitest
11-25 13:51:09.648  5944  5944 W kworker/1:0: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 13:51:09.657  4050  5987 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-25 13:51:09.668  4050  5987 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-25 13:51:09.668  4050  5987 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 13:51:09.668  4050  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-25 13:51:09.668  4050  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-25 13:51:09.668  4050  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-25 13:51:09.668  4050  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-25 13:51:09.668  4050  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-25 13:51:09.668  4050  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-25 13:51:09.668  4050  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-25 13:51:09.668  4050  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-25 13:51:09.668  4050  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-25 13:51:09.668  4050  5987 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-25 13:51:09.668  4050  5987 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-25 13:51:09.668  4050  5987 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-25 13:51:09.668  4050  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-25 13:51:09.668  4050  5987 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-25 13:51:09.668  4050  5987 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-25 13:51:09.668  4050  5987 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-25 13:51:09.668  4050  5987 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 13:51:09.668  4050  5987 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-25 13:51:09.668  4050  5987 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-25 13:51:09.668  4050  5987 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-25 13:51:09.668  4050  5987 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 13:51:09.668  4050  5987 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-25 13:51:09.668  4050  5987 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-25 13:51:09.668  4050  5987 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-25 13:51:09.668  4050  5987 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-25 13:51:09.668  4050  5987 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-25 13:51:09.668  4050  5987 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-25 13:51:09.668  4050  5987 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-25 13:51:09.668  4050  5987 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-25 13:51:09.668  4050  5987 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-25 13:51:09.668  4050  5987 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-25 13:51:09.668  4050  5987 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-25 13:51:09.668  4050  5987 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-25 13:51:09.668  4050  5987 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-25 13:51:09.668  4050  5987 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-25 13:51:09.668  4050  5987 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-25 13:51:09.668  4050  5987 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-25 13:51:09.668  4050  5987 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 13:51:09.668  4050  5987 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-25 13:51:09.668  4050  5987 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-25 13:51:09.669  4050  5987 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
11-25 13:51:09.677  4050  4050 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-25 13:51:09.678  4050  4050 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,11-25 13:51:09.683  4050  4050 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,11-25 13:51:09.683  4050  4050 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,11-25 13:51:09.686  3373  5978 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,--------- beginning of crash
11-25 13:51:09.687  3373  5978 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-25 13:51:09.687  3373  5978 E AndroidRuntime: Process: android.process.acore, PID: 3373
11-25 13:51:09.687  3373  5978 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-25 13:51:09.687  3373  5978 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-25 13:51:09.687  3373  5978 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-25 13:51:09.687  3373  5978 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-25 13:51:09.687  3373  5978 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-25 13:51:09.687  3373  5978 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-25 13:51:09.687  3373  5978 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-25 13:51:09.687  3373  5978 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-25 13:51:09.687  3373  5978 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-25 13:51:09.687  3373  5978 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-25 13:51:09.687  3373  5978 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-25 13:51:09.687  3373  5978 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-25 13:51:09.687  3373  5978 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-25 13:51:09.687  3373  5978 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-25 13:51:09.687  3373  5978 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 13:51:09.687  3373  5978 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-25 13:51:09.687  3373  5978 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-25 13:51:09.688  4050  5993 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/metrics.db'.
11-25 13:51:09.688  4050  5993 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 13:51:09.688  4050  5993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-25 13:51:09.688  4050  5993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-25 13:51:09.688  4050  5993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-25 13:51:09.688  4050  5993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-25 13:51:09.688  4050  5993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-25 13:51:09.688  4050  5993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-25 13:51:09.688  4050  5993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-25 13:51:09.688  4050  5993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-25 13:51:09.688  4050  5993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-25 13:51:09.688  4050  5993 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-25 13:51:09.688  4050  5993 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-25 13:51:09.688  4050  5993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-25 13:51:09.688  4050  5993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-25 13:51:09.688  4050  5993 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
11-25 13:51:09.688  4050  5993 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-25 13:51:09.688  4050  5993 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
11-25 13:51:09.688  4050  5993 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-25 13:51:09.688  4050  5993 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-25 13:51:09.688  4050  5993 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 13:51:09.688  4050  5993 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-25 13:51:09.688  4050  5993 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-25 13:51:09.689  4050  5993 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
11-25 13:51:09.689  4050  5993 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 13:51:09.689  4050  5993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-25 13:51:09.689  4050  5993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-25 13:51:09.689  4050  5993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-25 13:51:09.689  4050  5993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-25 13:51:09.689  4050  5993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-25 13:51:09.689  4050  5993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-25 13:51:09.689  4050  5993 E SQLiteOpenHelper: 	at android.databa,se.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-25 13:51:09.689  4050  5993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-25 13:51:09.689  4050  5993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-25 13:51:09.689  4050  5993 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-25 13:51:09.689  4050  5993 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-25 13:51:09.689  4050  5993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-25 13:51:09.689  4050  5993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-25 13:51:09.689  4050  5993 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
11-25 13:51:09.689  4050  5993 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-25 13:51:09.689  4050  5993 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
11-25 13:51:09.689  4050  5993 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-25 13:51:09.689  4050  5993 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-25 13:51:09.689  4050  5993 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 13:51:09.689  4050  5993 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-25 13:51:09.689  4050  5993 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-25 13:51:09.693  4050  5993 W SQLiteOpenHelper: Opened metrics.db in read-only mode
11-25 13:51:09.693  4050  5993 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
11-25 13:51:09.693  4050  5993 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
,11-25 13:51:09.694  4050  5993 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
11-25 13:51:09.695  4050  5993 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
11-25 13:51:09.695  4050  5993 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
11-25 13:51:09.695  4050  5993 E AndroidRuntime: Process: com.google.android.gms, PID: 4050
11-25 13:51:09.695  4050  5993 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
11-25 13:51:09.695  4050  5993 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-25 13:51:09.695  4050  5993 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-25 13:51:09.695  4050  5993 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-25 13:51:09.695  4050  5993 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-25 13:51:09.695  4050  5993 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-25 13:51:09.695  4050  5993 E AndroidRuntime: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
11-25 13:51:09.695  4050  5993 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-25 13:51:09.695  4050  5993 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-25 13:51:09.695  4050  5993 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 13:51:09.695  4050  5993 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-25 13:51:09.695  4050  5993 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-25 13:51:09.698   928  5998 E DropBoxManagerService: Can't write: system_app_crash
11-25 13:51:09.698   928  5998 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
11-25 13:51:09.698   928  5998 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-25 13:51:09.698   928  5998 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-25 13:51:09.698   928  5998 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-25 13:51:09.698   928  5998 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-25 13:51:09.698   928  5998 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-25 13:51:09.698   928  5998 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-25 13:51:09.698   928  5998 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-25 13:51:09.698   928  5998 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-25 13:51:09.698   928  5998 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-25 13:51:09.698   928  5998 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 13:51:09.698   928  5998 E DropBoxManagerService: 	... 5 more
,11-25 13:51:09.713   928  5999 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-25 13:51:09.708   415   415 W Binder_2: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[34956]" dev="sockfs" ino=34956 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-25 13:51:09.708   415   415 W Binder_2: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[34956]" dev="sockfs" ino=34956 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-25 13:51:09.712   415   415 W Binder_2: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[33220]" dev="sockfs" ino=33220 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-25 13:51:09.712   415   415 W Binder_2: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[33220]" dev="sockfs" ino=33220 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 13:51:09.717  3937  5996 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,11-25 13:51:09.721   928  6001 E DropBoxManagerService: Can't write: system_app_crash
11-25 13:51:09.721   928  6001 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
11-25 13:51:09.721   928  6001 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-25 13:51:09.721   928  6001 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-25 13:51:09.721   928  6001 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-25 13:51:09.721   928  6001 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-25 13:51:09.721   928  6001 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-25 13:51:09.721   928  6001 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-25 13:51:09.721   928  6001 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-25 13:51:09.721   928  6001 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-25 13:51:09.721   928  6001 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-25 13:51:09.721   928  6001 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 13:51:09.721   928  6001 E DropBoxManagerService: 	... 5 more
,11-25 13:51:09.726  3637  5974 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
11-25 13:51:09.728  3637  5974 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
11-25 13:51:09.728  3637  5974 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,11-25 13:51:09.736  3637  5974 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
11-25 13:51:09.736  3637  5974 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
11-25 13:51:09.737  3637  5974 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-25 13:51:09.737  3637  5974 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-25 13:51:09.738  3637  5974 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,11-25 13:51:09.738  3637  5974 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-25 13:51:09.738  3637  5974 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-25 13:51:09.738  3637  5974 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-25 13:51:09.738  3637  5974 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-25 13:51:09.738  3637  5974 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
11-25 13:51:09.739  4050  5987 E GMPM-SVC: Scheduler not initialized or shutdown. Not logging error/warn.
,11-25 13:51:09.755  4050  6003 I GMPM-SVC: App measurement is starting up
,11-25 13:51:09.758  4050  6003 E GMPM-SVC: AppMeasurementService not registered/enabled
,11-25 13:51:09.760  4050  6003 E GMPM-SVC: Uploading is not possible. App measurement disabled
,11-25 13:51:09.766   928  3780 I ActivityManager: Start proc 6005:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,11-25 13:51:09.768  4050  6003 E SQLiteLog: (14) cannot open file at line 31278 of [2ef4f3a5b1]
,11-25 13:51:09.768  4050  6003 E SQLiteLog: (14) os_unix.c:31278: (2) open(/data/user/0/com.google.android.gms/databases/google_app_measurement2.db) - 
,11-25 13:51:09.769  4050  6003 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_app_measurement2.db'.
11-25 13:51:09.769  4050  6003 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
11-25 13:51:09.769  4050  6003 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-25 13:51:09.769  4050  6003 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-25 13:51:09.769  4050  6003 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-25 13:51:09.769  4050  6003 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-25 13:51:09.769  4050  6003 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-25 13:51:09.769  4050  6003 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-25 13:51:09.769  4050  6003 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-25 13:51:09.769  4050  6003 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-25 13:51:09.769  4050  6003 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-25 13:51:09.769  4050  6003 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-25 13:51:09.769  4050  6003 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-25 13:51:09.769  4050  6003 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-25 13:51:09.769  4050  6003 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-25 13:51:09.769  4050  6003 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1022)
11-25 13:51:09.769  4050  6003 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.j(SourceFile:271)
11-25 13:51:09.769  4050  6003 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.d(SourceFile:877)
11-25 13:51:09.769  4050  6003 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ao.run(SourceFile:397)
11-25 13:51:09.769  4050  6003 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-25 13:51:09.769  4050  6003 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-25 13:51:09.769  4050  6003 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.al.run(SourceFile:257)
11-25 13:51:09.769  4050  6003 E GMPM-SVC: Opening the database failed, dropping and recreating it
11-25 13:51:09.769  4050  6003 E SQLiteLog: (14) cannot open file at line 31278 of [2ef4f3a5b1]
,11-25 13:51:09.769  4050  6003 E SQLiteLog: (14) os_unix.c:31278: (2) open(/data/user/0/com.google.android.gms/databases/google_app_measurement2.db) - 
11-25 13:51:09.770  4050  5994 W BaseAppContext: Using Auth Proxy for data requests.
11-25 13:51:09.770  4050  6003 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_app_measurement2.db'.
11-25 13:51:09.770  4050  6003 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
11-25 13:51:09.770  4050  6003 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-25 13:51:09.770  4050  6003 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-25 13:51:09.770  4050  6003 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-25 13:51:09.770  4050  6003 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-25 13:51:09.770  4050  6003 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-25 13:51:09.770  4050  6003 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-25 13:51:09.770  4050  6003 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-25 13:51:09.770  4050  6003 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-25 13:51:09.770  4050  6003 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-25 13:51:09.770  4050  6003 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-25 13:51:09.770  4050  6003 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-25 13:51:09.770  4050  6003 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-25 13:51:09.770  4050  6003 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-25 13:51:09.770  4050  6003 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
11-25 13:51:09.770  4050  6003 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.j(SourceFile:271)
11-25 13:51:09.770  4050  6003 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.d(SourceFile:877)
11-25 13:51:09.770  4050  6003 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ao.run(SourceFile:397)
11-25 13:51:09.770  4050  6003 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-25 13:51:09.770  4050  6003 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-25 13:51:09.770  4050  6003 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.al.run(SourceFile:257)
11-25 13:51:09.772  4050  4050 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,11-25 13:51:09.773  4050  4886 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/config_removals.xml.bak
11-25 13:51:09.773  4050  6003 E GMPM-SVC: Failed to open freshly created database: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
11-25 13:51:09.774  4050  6003 W GMPM-SVC: Error opening database: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
11-25 13:51:09.774  4050  6003 E GMPM-SVC: Error deleting application data. appId, error: com.test.thalitest, android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
,11-25 13:51:09.777  4050  4886 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
11-25 13:51:09.777  4050  4886 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
11-25 13:51:09.778  4050  4886 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
11-25 13:51:09.778  4050  4886 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
11-25 13:51:09.779  4050  4886 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
11-25 13:51:09.779  4050  5994 W BaseAppContext: Using Auth Proxy for data requests.
,11-25 13:51:09.780  4050  4886 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
11-25 13:51:09.780  4050  4886 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
11-25 13:51:09.781  4050  4050 I ConfigFetchService: service connected
,11-25 13:51:09.784  4050  6011 I PeopleContactsSync: CP2 sync disabled
,11-25 13:51:09.788  4050  4209 I Icing   : doRemovePackageData com.test.thalitest
,11-25 13:51:09.808   928   941 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{5786e9e u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{a515320 4050 com.google.android.gms/10012/u0 remote:7fbd223}: process crashing
,11-25 13:51:09.814   928  5977 D ConnectivityService: listenForNetwork for Listen from uid/pid:10012/4050 for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,11-25 13:51:09.864  4050  5992 W DriveInitializer: Awaiting to be initialized
,11-25 13:51:09.864  4050  6014 W DriveInitializer: Background init thread started
,11-25 13:51:10.058   384   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
